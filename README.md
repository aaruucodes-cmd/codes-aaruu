ARYAN CODES
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ARYAN CODES - Template SALE! Professional Web Design</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { 
            font-family: system-ui, sans-serif; 
            line-height: 1.6; 
            color: #fff; 
            background: linear-gradient(135deg, #0a0a0a 0%, #1a1a2e 50%, #16213e 100%);
            overflow-x: hidden; 
        }
        .container { max-width: 1200px; margin: 0 auto; padding: 0 20px; }
        /* Sale Banner */
        .sale-banner {
            background: linear-gradient(45deg, #ff0000, #ff4444);
            color: #fff;
            text-align: center;
            padding: 1rem;
            position: relative;
            z-index: 100;
        }
        .countdown { font-size: 1.5rem; font-weight: bold; margin: 0.5rem 0; }
        .countdown span { background: #000; padding: 0.5rem 1rem; border-radius: 10px; margin: 0 0.2rem; }
        .expired { opacity: 0.5; }
        /* Header */
        header { position: fixed; top: 0; width: 100%; background: rgba(10,10,10,0.95); backdrop-filter: blur(10px); z-index: 99; padding: 1rem 0; }
        nav { display: flex; justify-content: space-between; align-items: center; }
        .logo { font-size: 1.8rem; font-weight: 700; background: linear-gradient(45deg, #00ff88, #ff00ff); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
        .nav-links { display: flex; list-style: none; gap: 2rem; }
        .nav-links a { color: #fff; text-decoration: none; transition: color 0.3s; }
        .nav-links a:hover { color: #00ff88; }
        /* Hero */
        #home { padding: 120px 0; min-height: 100vh; display: flex; align-items: center; }
        h1 { font-size: clamp(3rem, 8vw, 6rem); font-weight: 700; margin-bottom: 1rem; background: linear-gradient(45deg, #00ff88, #ff00ff); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
        .profile-photo { width: 150px; height: 150px; border-radius: 50%; background: linear-gradient(45deg, #00ff88, #ff00ff); margin: 2rem auto; display: flex; align-items: center; justify-content: center; font-size: 3rem; font-weight: 700; box-shadow: 0 10px 30px rgba(0,255,136,0.4); transition: all 0.3s; }
        /* Portfolio */
        #portfolio { padding: 100px 0; }
        h2 { font-size: clamp(2rem, 5vw, 3.5rem); text-align: center; margin-bottom: 4rem; opacity: 0.9; }
        .portfolio-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 2rem; }
        .portfolio-item { position: relative; border-radius: 20px; overflow: hidden; height: 350px; cursor: pointer; transition: transform 0.3s; }
        .portfolio-item:hover { transform: scale(1.05); }
        .portfolio-overlay { position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%); z-index: 2; text-align: center; color: #fff; width: 90%; }
        /* Sale Badge */
        .sale-badge { position: absolute; top: 10px; right: 10px; background: #ff4444; color: #fff; padding: 0.5rem 1rem; border-radius: 20px; font-weight: bold; font-size: 1rem; z-index: 3; box-shadow: 0 4px 12px rgba(255,68,68,0.4); }
        .old-price { text-decoration: line-through; opacity: 0.7; font-size: 0.9rem; margin-left: 0.5rem; }
        /* Buttons */
        .btn { display: inline-block; padding: 15px 40px; background: linear-gradient(45deg, #00ff88, #00cc66); color: #000; text-decoration: none; border-radius: 50px; font-weight: 600; transition: all 0.3s; box-shadow: 0 10px 30px rgba(0,255,136,0.3); }
        .btn:hover { transform: translateY(-5px); box-shadow: 0 15px 40px rgba(0,255,136,0.5); }
        .whatsapp-btn { background: #25D366; color: #fff !important; }
        /* Responsive */
        @media (max-width: 768px) { .portfolio-grid { grid-template-columns: 1fr; } }
        @media (max-width: 480px) { .container { padding: 0 15px; } section { padding: 80px 0; } }
    </style>
</head>
<body>
    <div class="sale-banner" id="saleBanner">
        <h3>🔥 LIMITED FLASH SALE! Template Websites 70% OFF - <span class="countdown" id="countdown"></span></h3>
        <p>Grab now before prices go up! Valid for 10 days only.</p>
    </div>

    <header>
        <nav class="container">
            <div class="logo">ARYAN CODES</div>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#portfolio">Templates</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <div class="container">
            <h1>Template SALE! 💥</h1>
            <div class="profile-photo">AC</div>
            <p>Premium Animated Templates at UNBEATABLE Prices! Perfect for Anniversary, Birthday, Festivals & Proposals. Fully Responsive, Customizable HTML.</p>
            <a href="#portfolio" class="btn">See Templates</a>
            <a href="https://wa.me/917772075898" class="btn whatsapp-btn">Buy Now on WhatsApp</a>
        </div>
    </section>

    <section id="portfolio">
        <div class="container">
            <h2>Limited Time Templates - FLASH SALE!</h2>
            <div class="portfolio-grid">
                <div class="portfolio-item" style="background: linear-gradient(45deg, #ee7752, #e73c7e);" onclick="window.open('templates/anniversary.html', '_blank')">
                    <div class="sale-badge">₹199 <span class="old-price">₹799</span></div>
                    <div class="portfolio-overlay">
                        <h3>💕 Anniversary Template</h3>
                        <p>Romantic timeline, music, floating effects. Perfect celebration page!</p>
                    </div>
                </div>
                <div class="portfolio-item" style="background: linear-gradient(45deg, #f093fb, #fa709a);" onclick="window.open('templates/birthday-festival.html', '_blank')">
                    <div class="sale-badge">₹299 <span class="old-price">₹999</span></div>
                    <div class="portfolio-overlay">
                        <h3>🎂 Birthday / Festival</h3>
                        <p>Diwali, Holi, Birthday - Fireworks, custom wishes, cake animation!</p>
                    </div>
                </div>
                <div class="portfolio-item" style="background: linear-gradient(45deg, #667eea, #764ba2);" onclick="window.open('templates/love-proposal.html', '_blank')">
                    <div class="sale-badge">₹499 <span class="old-price">₹999</span></div>
                    <div class="portfolio-overlay">
                        <h3>💍 Love Proposal</h3>
                        <p>Typing message, heartbeat, confetti explosion - Yes/No modals!</p>
                    </div>
                </div>
            </div>
            <div style="text-align: center; margin-top: 4rem;">
                <a href="https://wa.me/917772075898?text=Hi! I want to buy the %20template" class="btn whatsapp-btn" style="font-size: 1.5rem; padding: 20px 60px;">BUY NOW - WhatsApp 🛒</a>
            </div>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>Ready to Grab Your Template?</h2>
            <p>Instant delivery via WhatsApp. Customize & launch in minutes!</p>
            <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 2rem; margin-top: 3rem;">
                <div style="text-align: center;">
                    <h3>📱 WhatsApp</h3>
                    <a href="https://wa.me/917772075898" class="btn whatsapp-btn">Message Now</a>
                </div>
                <div style="text-align: center;">
                    <h3>✉️ Email</h3>
                    <p>aryanjaiswalji25@gmail.com</p>
                </div>
            </div>
        </div>
    </section>

    <footer style="background: rgba(0,0,0,0.8); text-align: center; padding: 2rem;">
        <p>&copy; 2025 ARYAN CODES | Limited Sale - Only 10 Days! | <a href="#portfolio" style="color: #00ff88;">Templates ↑</a></p>
    </footer>

    <script>
        // 10-Day Countdown
        function updateCountdown() {
            const saleEnd = localStorage.getItem('saleEnd');
            let endTime = saleEnd ? new Date(parseInt(saleEnd)) : new Date(Date.now() + 10 * 24 * 60 * 60 * 1000); // 10 days from now
            localStorage.setItem('saleEnd', endTime.getTime());
            
            const now = new Date().getTime();
            const distance = endTime - now;
            
            if (distance < 0) {
                document.getElementById('saleBanner').innerHTML = '<h3>Sale Ended! Regular prices now apply.</h3>';
                document.getElementById('saleBanner').classList.add('expired');
                return;
            }
            
            const days = Math.floor(distance / (1000 * 60 * 60 * 24));
            const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
            const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
            const seconds = Math.floor((distance % (1000 * 60)) / 1000);
            
            document.getElementById('countdown').innerHTML = `${days}d <span>${hours}h</span> <span>${minutes}m</span> <span>${seconds}s</span>`;
        }
        setInterval(updateCountdown, 1000);
        updateCountdown();

        // Smooth scroll
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({ behavior: 'smooth' });
            });
        });
        
    </script>
</body>
</html> 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anniversary Celebration - ARYAN CODES Template</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { 
            font-family: 'Segoe UI', sans-serif; 
            background: linear-gradient(-45deg, #ee7752, #e73c7e, #23a6d5, #23d5ab);
            background-size: 400% 400%;
            animation: gradientShift 15s ease infinite;
            color: #fff; 
            overflow-x: hidden;
            min-height: 100vh;
        }
        @keyframes gradientShift { 0% {background-position: 0% 50%;} 50% {background-position: 100% 50%;} 100% {background-position: 0% 50%;} }
        .container { max-width: 1000px; margin: 0 auto; padding: 20px; text-align: center; }
        h1 { font-size: clamp(3rem, 10vw, 6rem); margin: 2rem 0; text-shadow: 0 0 20px rgba(255,255,255,0.5); animation: glow 2s ease-in-out infinite alternate; }
        @keyframes glow { from { text-shadow: 0 0 20px #fff, 0 0 30px #fff, 0 0 40px #e73c7e; } to { text-shadow: 0 0 20px #fff, 0 0 30px #23a6d5, 0 0 50px #23d5ab; } }
        .couple-photo { width: 250px; height: 250px; border-radius: 50%; border: 5px solid rgba(255,255,255,0.3); margin: 2rem auto; box-shadow: 0 0 50px rgba(255,255,255,0.4); animation: float 3s ease-in-out infinite; background: radial-gradient(circle, #ffecd2 0%, #fcb69f 100%); display: flex; align-items: center; justify-content: center; font-size: 4rem; }
        @keyframes float { 0%, 100% { transform: translateY(0px); } 50% { transform: translateY(-20px); } }
        .timeline { display: flex; flex-wrap: wrap; justify-content: center; gap: 2rem; margin: 4rem 0; }
        .memory { background: rgba(255,255,255,0.1); backdrop-filter: blur(10px); padding: 2rem; border-radius: 20px; max-width: 300px; transition: transform 0.3s; }
        .memory:hover { transform: scale(1.05); }
        .music-toggle { position: fixed; top: 20px; right: 20px; background: rgba(255,255,255,0.2); border: none; color: #fff; padding: 10px 20px; border-radius: 30px; cursor: pointer; font-size: 1.1rem; }
        .whatsapp-share { display: inline-block; margin-top: 2rem; padding: 15px 30px; background: #25D366; color: #fff; text-decoration: none; border-radius: 30px; font-weight: bold; box-shadow: 0 5px 15px rgba(37,211,102,0.4); }
        footer { margin-top: 4rem; opacity: 0.8; font-size: 0.9rem; }
        @media (max-width: 768px) { .timeline { flex-direction: column; align-items: center; } .container { padding: 10px; } }
        @media (max-width: 480px) { h1 { font-size: 2.5rem; } .couple-photo { width: 200px; height: 200px; font-size: 3rem; } }
    </style>
</head>
<body>
    <button class="music-toggle" onclick="toggleMusic()">🎵 Play Music</button>
    <div class="container">
        <h1>Happy Anniversary ❤️</h1>
        <div class="couple-photo">💑</div>
        <p style="font-size: 1.5rem; margin-bottom: 3rem;">Celebrating another year of love, laughter, and unforgettable memories together!</p>
        <div class="timeline">
            <div class="memory">
                <h3>Our First Date</h3>
                <p>That magical evening that started it all...</p>
            </div>
            <div class="memory">
                <h3>Year 1</h3>
                <p>Building dreams together, hand in hand.</p>
            </div>
            <div class="memory">
                <h3>Today & Forever</h3>
                <p>Stronger than ever, loving you always 💕</p>
            </div>
        </div>
        <a href="https://wa.me/?text=Happy Anniversary! Check out this beautiful template by ARYAN CODES 💝 https://your-link.com" class="whatsapp-share" target="_blank">Share Love 💝</a>
    </div>
    <footer>Template by <a href="../index.html" style="color: #00ff88;">ARYAN CODES</a> | Professional Web Templates</footer>

    <audio id="music" loop>
        <source src="data:audio/wav;base64,UklGRnoGAABXQVZFZm10IBAAAAABAAEAQB8AAEAfAAABAAgAZGF0YQoGAACBhYqFbF1fdJivrJBhNjVgodDbq2EcBj+a2/LDciUFLI..." type="audio/wav">
    </audio>
    <script>
        function toggleMusic() { const audio = document.getElementById('music'); audio.play().catch(() => alert('Enable sound in browser settings')); }
        <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Birthday & Festival Wishes - ARYAN CODES Template</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { 
            font-family: 'Segoe UI', sans-serif; 
            background: radial-gradient(circle at 20% 50%, #f093fb 0%, transparent 50%), radial-gradient(circle at 80% 20%, #fa709a 0%, transparent 50%), radial-gradient(circle at 40% 80%, #ff8a80 0%, transparent 50%), linear-gradient(#667eea 0%, #764ba2 100%);
            color: #fff; 
            overflow-x: hidden;
            min-height: 100vh;
            animation: sparkle 3s ease infinite;
        }
        @keyframes sparkle { 0%, 100% { opacity: 1; } 50% { opacity: 0.95; } }
        .container { max-width: 1000px; margin: 0 auto; padding: 20px; text-align: center; }
        h1 { font-size: clamp(3rem, 10vw, 6rem); margin: 2rem 0; text-shadow: 0 0 30px #ffd700; animation: bounce 2s infinite; }
        @keyframes bounce { 0%, 20%, 50%, 80%, 100% { transform: translateY(0); } 40% { transform: translateY(-30px); } 60% { transform: translateY(-15px); } }
        .cake { font-size: 8rem; margin: 2rem 0; animation: glow 2s ease-in-out infinite alternate; }
        @keyframes glow { 0% { filter: drop-shadow(0 0 20px #ffd700); } 100% { filter: drop-shadow(0 0 40px #ff6b6b); } }
        .fireworks { position: fixed; top: 0; left: 0; width: 100%; height: 100%; pointer-events: none; z-index: -1; }
        .wish-carousel { display: flex; overflow-x: auto; gap: 1rem; padding: 2rem 0; scroll-snap-type: x mandatory; }
        .wish { background: rgba(255,255,255,0.1); backdrop-filter: blur(10px); padding: 2rem; border-radius: 20px; min-width: 300px; scroll-snap-align: center; transition: transform 0.3s; }
        .customize { margin: 2rem 0; }
        input { padding: 10px; border: none; border-radius: 10px; font-size: 1.2rem; width: 200px; margin: 0 10px; }
        .generate-btn { padding: 15px 30px; background: linear-gradient(45deg, #ff6b6b, #ffd93d); color: #000; border: none; border-radius: 30px; font-weight: bold; cursor: pointer; margin-top: 1rem; }
        footer { margin-top: 4rem; opacity: 0.8; }
        @media (max-width: 768px) { .wish-carousel { flex-direction: column; } input { width: 100%; margin: 10px 0; } }
        @media (max-width: 480px) { h1 { font-size: 2.5rem; } .cake { font-size: 6rem; } }
    </style>
</head>
<body>
    <div class="fireworks" id="fireworks"></div>
    <div class="container">
        <h1 id="name">Happy Birthday 🎉</h1>
        <div class="cake">🎂</div>
        <p style="font-size: 1.5rem;">Wishing you a day filled with joy, laughter, and all your favorite things! Diwali, Holi, or Birthday - celebrate big! 🪔🎆</p>
        <div class="customize">
            <input id="nameInput" placeholder="Enter Name" value="Friend">
            <input id="festivalInput" placeholder="Festival/B'day" value="Birthday">
            <button class="generate-btn" onclick="customizeWish()">Generate Wish</button>
        </div>
        <div class="wish-carousel">
            <div class="wish">May this festival/birthday bring endless happiness and prosperity! 🌟</div>
            <div class="wish">Lights, joy, and celebrations just for you! Happy Diwali 🎇</div>
            <div class="wish">Another trip around the sun - make it amazing! 🥳</div>
            <div class="wish">Holi colors of love and friendship! 🌈</div>
        </div>
    </div>
    <footer>Template by <a href="../index.html" style="color: #00ff88;">ARYAN CODES</a></footer>

    <script>
        function customizeWish() {
            const name = document.getElementById('nameInput').value || 'Friend';
            const fest = document.getElementById('festivalInput').value || 'Special Day';
            document.getElementById('name').textContent = `Happy ${fest} ${name} 🎉`;
        }
        // Fireworks animation
        function createFirework() {
            const fw = document.createElement('div');
            fw.style.position = 'fixed'; fw.style.left = Math.random()*100+'vw'; fw.style.top = '100vh'; fw.style.width = '4px'; fw.style.height = '4px'; fw.style.background = `hsl(${Math.random()*360},100%,50%)`; fw.style.pointerEvents = 'none';
            document.getElementById('fireworks').appendChild(fw);
            fw.animate([{ transform: 'translateY(-100vh) scale(0)', opacity: 1 }, { transform: 'translateY(-200vh) scale(3)', opacity: 0 }], { duration: 2000 });
            setTimeout(() => fw.remove(), 2000);
        }
        setInterval(createFirework, 300);
    </script>
</body>
</html>
        // Confetti effect on load
        setTimeout(() => { /* simple CSS confetti */ }, 1000);
    </script> 
    <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Will You Be Mine? 💖 - ARYAN CODES Template</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { 
            font-family: 'Segoe UI', sans-serif; 
            background: linear-gradient(135deg, #667eea 0%, #764ba2 50%, #f093fb 100%); 
            color: #fff; 
            overflow-x: hidden;
            display: flex; align-items: center; justify-content: center; min-height: 100vh; text-align: center;
        }
        .proposal-container { max-width: 800px; padding: 40px; background: rgba(255,255,255,0.1); backdrop-filter: blur(20px); border-radius: 30px; border: 1px solid rgba(255,255,255,0.2); box-shadow: 0 20px 60px rgba(0,0,0,0.3); }
        .heart { font-size: 10rem; margin: 2rem 0; animation: heartbeat 1.5s infinite; color: #ff69b4; text-shadow: 0 0 20px currentColor; }
        @keyframes heartbeat { 0% { transform: scale(1); } 14% { transform: scale(1.3); } 28% { transform: scale(1); } 42% { transform: scale(1.3); } 70% { transform: scale(1); } }
        #message { font-size: clamp(1.5rem, 4vw, 2.5rem); margin: 3rem 0; min-height: 100px; line-height: 1.4; }
        .typing-cursor { display: inline-block; background: #fff; width: 3px; animation: blink 1s infinite; margin-left: 2px; }
        @keyframes blink { 0%, 50% { opacity: 1; } 51%, 100% { opacity: 0; } }
        .buttons { margin-top: 3rem; }
        .btn { padding: 15px 40px; margin: 0 1rem; border: none; border-radius: 50px; font-size: 1.2rem; font-weight: bold; cursor: pointer; transition: all 0.3s; min-width: 150px; }
        .btn-yes { background: linear-gradient(45deg, #ff6b6b, #ff8e8e); color: #fff; }
        .btn-no { background: transparent; color: #fff; border: 2px solid #fff; }
        .btn:hover { transform: translateY(-5px) scale(1.05); }
        .modal { display: none; position: fixed; top: 0; left: 0; width: 100%; height: 100%; background: rgba(0,0,0,0.8); z-index: 1000; }
        .modal-content { position: absolute; top: 50%; left: 50%; transform: translate(-50%,-50%); background: rgba(255,255,255,0.95); color: #333; padding: 4rem; border-radius: 20px; max-width: 500px; text-align: center; animation: modalPop 0.5s ease; }
        @keyframes modalPop { from { transform: translate(-50%,-50%) scale(0.7); opacity: 0; } to { transform: translate(-50%,-50%) scale(1); opacity: 1; } }
        .confetti { position: fixed; width: 10px; height: 10px; background: #ff69b4; pointer-events: none; z-index: 999; }
        footer { position: fixed; bottom: 20px; left: 20px; font-size: 0.8rem; opacity: 0.7; }
        @media (max-width: 768px) { .proposal-container { margin: 20px; padding: 30px 20px; } .heart { font-size: 7rem; } .btn { display: block; margin: 1rem auto; } }
        @media (max-width: 480px) { .proposal-container { margin: 10px; padding: 20px; } .heart { font-size: 5rem; } #message { font-size: 1.3rem; } }
    </style>
</head>
<body>
    <footer>Template by <a href="../index.html" style="color: #00ff88; text-decoration: none;">ARYAN CODES</a></footer>
    <div class="proposal-container">
        <div class="heart">💖</div>
        <div id="message">I have loved you since the moment we met.<br>No one has made my heart beat like this.<br><span class="typing-cursor">|</span></div>
        <p style="font-size: 1.3rem; margin-bottom: 2rem;">Will you be my partner forever?</p>
        <div class="buttons">
            <button class="btn btn-yes" onclick="accept()">💍 YES! 💍</button>
            <button class="btn btn-no" onclick="reject()">Think about it...</button>
        </div>
    </div>

    <div id="yesModal" class="modal">
        <div class="modal-content">
            <div class="heart" style="font-size: 5rem;">💕</div>
            <h2>I love you too! ❤️</h2>
            <p>Our journey together starts now! Forever yours.</p>
            <button onclick="closeModal('yesModal')" class="btn btn-yes">Celebrate! 🎉</button>
        </div>
    </div>
    <div id="noModal" class="modal">
        <div class="modal-content">
            <h2>Take your time 💭</h2>
            <p>I'll wait for you, because you're worth it.</p>
            <button onclick="closeModal('noModal')" class="btn btn-no">Close</button>
        </div>
    </div>

    <script>
        const messages = ['Will you make me the happiest person alive?', 'Be mine forever? 💕', 'Say YES and make my dreams come true!'];
        let msgIndex = 0;
        function typeMessage() {
            const msg = messages[msgIndex];
            let i = 0;
            const typer = setInterval(() => {
                document.getElementById('message').innerHTML = msg.slice(0, i) + '<span class="typing-cursor">|</span>';
                i++;
                if (i > msg.length) { clearInterval(typer); msgIndex = (msgIndex + 1) % messages.length; setTimeout(typeMessage, 3000); }
            }, 100);
        }
        typeMessage();

        function accept() {
            document.getElementById('yesModal').style.display = 'block';
            launchConfetti();
        }
        function reject() {
            document.getElementById('noModal').style.display = 'block';
        }
        function closeModal(id) { document.getElementById(id).style.display = 'none'; }
        function launchConfetti() {
            for (let i = 0; i < 100; i++) {
                const conf = document.createElement('div'); conf.className = 'confetti';
                conf.style.left = Math.random() * 100 + 'vw'; conf.style.top = Math.random() * 100 + 'vh';
                conf.style.background = `hsl(${Math.random()*360}, 100%, 60%)`; conf.style.transform = `rotate(${Math.random()*360}deg)`;
                document.body.appendChild(conf);
                conf.animate([{ transform: `translateY(100vh) rotate(720deg)`, opacity: 1 }, { opacity: 0 }], { duration: 3000 });
                setTimeout(() => conf.remove(), 3000);
            }
        }
    </script>
</body>
</html>
</body>
</html>
