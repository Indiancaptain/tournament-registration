<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VSPORTS | Free Fire Tournament</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>
    <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700;900&family=Exo+2:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Exo 2', sans-serif;
            background-color: #0a0a0f;
            color: #e0e0ff;
            overflow-x: hidden;
            line-height: 1.6;
        }
        
        #bg-canvas {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
            position: relative;
            z-index: 1;
        }
        
        header {
            padding: 30px 0;
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 1px solid rgba(0, 150, 255, 0.2);
            position: relative;
        }
        
        .logo {
            font-family: 'Orbitron', sans-serif;
            font-size: 2.5rem;
            font-weight: 900;
            background: linear-gradient(90deg, #00a8ff, #00ffcc);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            text-shadow: 0 0 15px rgba(0, 168, 255, 0.5);
            letter-spacing: 2px;
        }
        
        .logo span {
            color: #ff0055;
        }
        
        .tournament-tag {
            background: linear-gradient(90deg, #ff0055, #ff5500);
            padding: 8px 20px;
            border-radius: 30px;
            font-family: 'Orbitron', sans-serif;
            font-weight: 700;
            font-size: 1.2rem;
            box-shadow: 0 0 20px rgba(255, 0, 85, 0.5);
            animation: pulse 2s infinite;
        }
        
        @keyframes pulse {
            0% { box-shadow: 0 0 20px rgba(255, 0, 85, 0.5); }
            50% { box-shadow: 0 0 30px rgba(255, 0, 85, 0.8); }
            100% { box-shadow: 0 0 20px rgba(255, 0, 85, 0.5); }
        }
        
        .hero {
            padding: 60px 0;
            text-align: center;
            position: relative;
        }
        
        .hero h1 {
            font-family: 'Orbitron', sans-serif;
            font-size: 3.5rem;
            margin-bottom: 20px;
            background: linear-gradient(90deg, #00ffcc, #0099ff);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            text-shadow: 0 0 20px rgba(0, 255, 204, 0.3);
        }
        
        .hero p {
            font-size: 1.2rem;
            max-width: 800px;
            margin: 0 auto 40px;
            color: #a0a0ff;
        }
        
        .content-wrapper {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 40px;
            margin-bottom: 60px;
        }
        
        @media (max-width: 900px) {
            .content-wrapper {
                grid-template-columns: 1fr;
            }
        }
        
        .instructions, .registration {
            background: rgba(10, 15, 30, 0.8);
            border-radius: 15px;
            padding: 30px;
            border: 1px solid rgba(0, 150, 255, 0.2);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
            backdrop-filter: blur(10px);
            transition: transform 0.3s, box-shadow 0.3s;
        }
        
        .instructions:hover, .registration:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 35px rgba(0, 100, 255, 0.2);
        }
        
        .section-title {
            font-family: 'Orbitron', sans-serif;
            font-size: 1.8rem;
            margin-bottom: 25px;
            color: #00ccff;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .section-title i {
            color: #ff0055;
        }
        
        .instructions-list {
            list-style: none;
        }
        
        .instructions-list li {
            padding: 15px 0;
            border-bottom: 1px solid rgba(255, 255, 255, 0.05);
            display: flex;
            align-items: flex-start;
            gap: 15px;
        }
        
        .instructions-list li:last-child {
            border-bottom: none;
        }
        
        .instructions-list li i {
            color: #00ffcc;
            margin-top: 3px;
        }
        
        .form-group {
            margin-bottom: 25px;
        }
        
        .form-group label {
            display: block;
            margin-bottom: 8px;
            font-weight: 600;
            color: #a0a0ff;
        }
        
        .form-control {
            width: 100%;
            padding: 15px;
            background: rgba(5, 10, 25, 0.7);
            border: 1px solid rgba(0, 150, 255, 0.3);
            border-radius: 8px;
            color: #ffffff;
            font-size: 1rem;
            transition: all 0.3s;
        }
        
        .form-control:focus {
            outline: none;
            border-color: #00a8ff;
            box-shadow: 0 0 15px rgba(0, 168, 255, 0.3);
        }
        
        .submit-btn {
            background: linear-gradient(90deg, #ff0055, #ff5500);
            color: white;
            border: none;
            padding: 18px 40px;
            font-size: 1.2rem;
            font-family: 'Orbitron', sans-serif;
            font-weight: 700;
            border-radius: 10px;
            cursor: pointer;
            width: 100%;
            letter-spacing: 1px;
            transition: all 0.3s;
            box-shadow: 0 5px 15px rgba(255, 0, 85, 0.3);
        }
        
        .submit-btn:hover {
            background: linear-gradient(90deg, #ff0040, #ff4400);
            box-shadow: 0 8px 20px rgba(255, 0, 85, 0.5);
            transform: translateY(-3px);
        }
        
        .registered-players {
            margin-top: 40px;
            background: rgba(10, 15, 30, 0.8);
            border-radius: 15px;
            padding: 30px;
            border: 1px solid rgba(0, 150, 255, 0.2);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
            backdrop-filter: blur(10px);
        }
        
        .players-title {
            font-family: 'Orbitron', sans-serif;
            font-size: 1.8rem;
            margin-bottom: 25px;
            color: #00ffcc;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .players-table {
            width: 100%;
            border-collapse: collapse;
        }
        
        .players-table th {
            background: rgba(0, 50, 100, 0.5);
            padding: 15px;
            text-align: left;
            font-family: 'Orbitron', sans-serif;
            color: #00a8ff;
            border-bottom: 2px solid rgba(0, 168, 255, 0.3);
        }
        
        .players-table td {
            padding: 15px;
            border-bottom: 1px solid rgba(255, 255, 255, 0.05);
        }
        
        .players-table tr:hover {
            background: rgba(0, 100, 200, 0.1);
        }
        
        footer {
            text-align: center;
            padding: 30px 0;
            margin-top: 60px;
            border-top: 1px solid rgba(0, 150, 255, 0.2);
            color: #8080cc;
            font-size: 0.9rem;
        }
        
        .glow-text {
            text-shadow: 0 0 10px rgba(0, 200, 255, 0.7);
        }
        
        .pulse {
            animation: textPulse 2s infinite;
        }
        
        @keyframes textPulse {
            0% { opacity: 0.8; }
            50% { opacity: 1; }
            100% { opacity: 0.8; }
        }
        
        /* Scrollbar styling */
        ::-webkit-scrollbar {
            width: 10px;
        }
        
        ::-webkit-scrollbar-track {
            background: rgba(5, 10, 25, 0.5);
        }
        
        ::-webkit-scrollbar-thumb {
            background: linear-gradient(180deg, #00a8ff, #ff0055);
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <!-- 3D Background Canvas -->
    <canvas id="bg-canvas"></canvas>
    
    <div class="container">
        <header>
            <div class="logo">V<span>SPORTS</span></div>
            <div class="tournament-tag">FREE FIRE TOURNAMENT</div>
        </header>
        
        <section class="hero">
            <h1 class="glow-text pulse">DOMINATE THE BATTLEGROUND</h1>
            <p>Register now for the ultimate Free Fire tournament with a massive prize pool of 1 KILL 10 RUPEES AND 100 RUPEES FOR BOOYAH!. Show off your skills, compete with the best, and claim your glory!</p>
        </section>
        
        <div class="content-wrapper">
            <section class="instructions">
                <h2 class="section-title"><i class="fas fa-scroll"></i> TOURNAMENT INSTRUCTIONS</h2>
                <ul class="instructions-list">
                    <li><i class="fas fa-crosshairs"></i> <strong>Format:</strong> 5v5 Squad matches, double elimination bracket, best of 3 finals</li>
                    <li><i class="fas fa-calendar-alt"></i> <strong>Dates:</strong> Registration open until October 30. Matches begin November 5.</li>
                    <li><i class="fas fa-trophy"></i> <strong>Prize Pool:</strong> $25,000 total - 1st: $12,000, 2nd: $7,000, 3rd: $4,000, 4th: $2,000</li>
                    <li><i class="fas fa-users"></i> <strong>Team Requirements:</strong> 5 main players + 2 substitutes allowed per team</li>
                    <li><i class="fas fa-ban"></i> <strong>Rules:</strong> No hacking, glitching, or unsportsmanlike behavior. Zero tolerance policy.</li>
                    <li><i class="fas fa-headset"></i> <strong>Communication:</strong> Discord server will be provided for team communication</li>
                    <li><i class="fas fa-gamepad"></i> <strong>Game Version:</strong> Latest version of Free Fire must be installed</li>
                    <li><i class="fas fa-exclamation-triangle"></i> <strong>Important:</strong> All players must be available for scheduled matches</li>
                </ul>
            </section>
            
            <section class="registration">
                <h2 class="section-title"><i class="fas fa-user-plus"></i> PLAYER REGISTRATION</h2>
                <form id="registrationForm">
                    <div class="form-group">
                        <label for="playerName"><i class="fas fa-user"></i> PLAYER NAME</label>
                        <input type="text" id="playerName" class="form-control" placeholder="Enter your in-game name" required>
                    </div>
                    
                    <div class="form-group">
                        <label for="freeFireID"><i class="fas fa-id-card"></i> FREE FIRE ID</label>
                        <input type="text" id="freeFireID" class="form-control" placeholder="Enter your Free Fire ID" required>
                    </div>
                    
                    <div class="form-group">
                        <label for="playerMobile"><i class="fas fa-mobile-alt"></i> MOBILE NUMBER</label>
                        <input type="tel" id="playerMobile" class="form-control" placeholder="Enter your mobile number" required>
                    </div>
                    
                    <div class="form-group">
                        <label for="playerEmail"><i class="fas fa-envelope"></i> EMAIL ADDRESS</label>
                        <input type="email" id="playerEmail" class="form-control" placeholder="Enter your email address" required>
                    </div>
                    
                    <div class="form-group">
                        <label for="teamName"><i class="fas fa-users"></i> TEAM NAME (Optional)</label>
                        <input type="text" id="teamName" class="form-control" placeholder="Enter your team name if applicable">
                    </div>
                    
                    <button type="submit" class="submit-btn">
                        <i class="fas fa-paper-plane"></i> REGISTER FOR TOURNAMENT
                    </button>
                </form>
            </section>
        </div>
        
        <section class="registered-players">
            <h2 class="players-title"><i class="fas fa-list-ol"></i> RECENTLY REGISTERED PLAYERS</h2>
            <table class="players-table">
                <thead>
                    <tr>
                        <th>Player Name</th>
                        <th>Free Fire ID</th>
                        <th>Team</th>
                    </tr>
                </thead>
                <tbody id="playersList">
                    <!-- Players will be added here dynamically -->
                </tbody>
            </table>
        </section>
        
        <footer>
            <p>&copy; 2023 NEXUS ESPORTS. ALL RIGHTS RESERVED.</p>
            <p>This tournament is not affiliated with Garena Free Fire. Free Fire is a registered trademark of Garena International.</p>
            <p>Contact: tournament@nexusesports.com | Discord: discord.gg/nexusff</p>
        </footer>
    </div>

    <script>
        // 3D Background with Three.js
        let scene, camera, renderer, particles;
        
        function init3DBackground() {
            scene = new THREE.Scene();
            camera = new THREE.PerspectiveCamera(75, window.innerWidth / window.innerHeight, 0.1, 1000);
            renderer = new THREE.WebGLRenderer({ canvas: document.getElementById('bg-canvas'), alpha: true });
            renderer.setSize(window.innerWidth, window.innerHeight);
            
            // Create particles
            const particleCount = 1500;
            const particleGeometry = new THREE.BufferGeometry();
            const positions = new Float32Array(particleCount * 3);
            const colors = new Float32Array(particleCount * 3);
            
            for (let i = 0; i < particleCount * 3; i += 3) {
                positions[i] = (Math.random() - 0.5) * 100;
                positions[i + 1] = (Math.random() - 0.5) * 100;
                positions[i + 2] = (Math.random() - 0.5) * 100;
                
                colors[i] = Math.random() * 0.5 + 0.1;     // R
                colors[i + 1] = Math.random() * 0.7 + 0.3; // G
                colors[i + 2] = Math.random() * 1.0 + 0.5; // B
            }
            
            particleGeometry.setAttribute('position', new THREE.BufferAttribute(positions, 3));
            particleGeometry.setAttribute('color', new THREE.BufferAttribute(colors, 3));
            
            const particleMaterial = new THREE.PointsMaterial({
                size: 0.1,
                vertexColors: true,
                transparent: true,
                opacity: 0.8
            });
            
            particles = new THREE.Points(particleGeometry, particleMaterial);
            scene.add(particles);
            
            camera.position.z = 5;
            
            // Handle window resize
            window.addEventListener('resize', () => {
                camera.aspect = window.innerWidth / window.innerHeight;
                camera.updateProjectionMatrix();
                renderer.setSize(window.innerWidth, window.innerHeight);
            });
            
            animateParticles();
        }
        
        function animateParticles() {
            requestAnimationFrame(animateParticles);
            particles.rotation.x += 0.0005;
            particles.rotation.y += 0.001;
            renderer.render(scene, camera);
        }
        
        // Form submission and player registration
        document.getElementById('registrationForm').addEventListener('submit', function(e) {
            e.preventDefault();
            
            const playerName = document.getElementById('playerName').value;
            const freeFireID = document.getElementById('freeFireID').value;
            const playerMobile = document.getElementById('playerMobile').value;
            const playerEmail = document.getElementById('playerEmail').value;
            const teamName = document.getElementById('teamName').value || 'Solo';
            
            // Add player to the table
            const playersList = document.getElementById('playersList');
            const newRow = document.createElement('tr');
            
            newRow.innerHTML = `
                <td>${playerName}</td>
                <td>${freeFireID}</td>
                <td>${teamName}</td>
            `;
            
            playersList.prepend(newRow);
            
            // Show confirmation message
            alert(`Registration successful! Welcome to the tournament, ${playerName}. Check your email for confirmation.`);
            
            // Reset form
            document.getElementById('registrationForm').reset();
            
            // Add some visual feedback
            const submitBtn = document.querySelector('.submit-btn');
            submitBtn.innerHTML = '<i class="fas fa-check"></i> REGISTRATION SUCCESSFUL!';
            submitBtn.style.background = 'linear-gradient(90deg, #00cc66, #00ff99)';
            
            setTimeout(() => {
                submitBtn.innerHTML = '<i class="fas fa-paper-plane"></i> REGISTER FOR TOURNAMENT';
                submitBtn.style.background = 'linear-gradient(90deg, #ff0055, #ff5500)';
            }, 3000);
        });
        
        // Pre-populate with some example players
        const examplePlayers = [
            { name: 'GHOST', id: '1122334455', team: 'Phantom Wolves' },
            { name: 'VENOM', id: '2233445566', team: 'Toxic Legends' },
            { name: 'SPECTRE', id: '3344556677', team: 'Shadow Strike' },
            { name: 'BLAZE', id: '4455667788', team: 'Inferno Squad' },
            { name: 'FROST', id: '5566778899', team: 'Arctic Assault' }
        ];
        
        function populateExamplePlayers() {
            const playersList = document.getElementById('playersList');
            
            examplePlayers.forEach(player => {
                const row = document.createElement('tr');
                row.innerHTML = `
                    <td>${player.name}</td>
                    <td>${player.id}</td>
                    <td>${player.team}</td>
                `;
                playersList.appendChild(row);
            });
        }
        
        // Initialize everything when page loads
        window.addEventListener('DOMContentLoaded', () => {
            init3DBackground();
            populateExamplePlayers();
            
            // Add some interactive effects
            const inputs = document.querySelectorAll('.form-control');
            inputs.forEach(input => {
                input.addEventListener('focus', function() {
                    this.parentElement.classList.add('glow-text');
                });
                
                input.addEventListener('blur', function() {
                    this.parentElement.classList.remove('glow-text');
                });
            });
        });
    </script>
</body>
</html>
