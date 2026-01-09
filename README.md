<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>Happy Birthday❤️</title>
        <meta name="viewport" cotent="width=device-width, initial-scale=1.0" />

        <style>
            *{box-sizing: border-box; }
            body{
                margin:0;
                font-family:'Segoe UI',sans-serif;
                background: linear-gradient(180deg, #ff758c, #ff7eb3);
                colour:#fff;
                text-align: center;
                overflow-x: hidden;
            }
            .app {
                max-width:420px;
                margin:auto;
                background:rgba(255,255,255,0.15);
                border-radius:30px;
                padding:20px 0 10px;
                box-shadow: 0 20px 40px rgba(0,0,0,0.3);
                backdrop-filter:blur(10px);
            }
            h1{
                font size: 2.5rem;
                margin:20px 0 10px;

            }
            .name {
             font-size:2.8rem;
             font-weight: bold;
             animation: glow 2s infinite alternate; 
            }
            @keyframes glow {
                form { text_shadow: 0 0 10px #b4f8c6;}
                to {text-shadow: 0 0 25px #ffd700, 0 0 40px #ffea00;}
            }
            .confetti {
                position: fixed;
                top: -10px;
                width: 10px;
                height: 10px;
                background: red;
                animation: fall 5s linear infinite;
            }
            @keyframes fall {
                to { transform: translatey(120vh) rotate(360deg);}
            }
            .slideshow {
                margin: 25px 0;
            }
            .slideshow img{
                width: 100%;
                border-radius:20px;
                display: none;
                box-shadow:0 10px 25px rgba(0,0,0,0.4);
            }
            .shayari {
                background: rgba(140, 220, 244, 0.95);
                color: #514f4f;
                padding: 20px;
                border-radius: 20px;
                margin: 25px 0;
                font-size: 1.1rem;
                line-height: 1.8;
            }
            audio{width: 100%; margin-top: 15px;}
            footer {
                margin-top: 20px;
                font-size: 1.5rem;
                opacity:09
            }
        </style>
    </head>
           <body>
            <script>
                for (let i=0;i<80,i++) {
                    const c=document.createElement("div");
                    c.className='confetti';
                    c.style.left=Math.random() * 100 + 'vw';
                    c.style.background=`hsl(${math.random()*360},100%,50%)`;
                    c.style.animationDelay=Math.random() * 5 + 's';
                    document.body.appendChild(c);
                }
            </script>
            <div class="app">
                <h1>🎂 Happy Birthday 🎂</h1>
                <div class="name">My Love ❤️</div>
                <p>Today is special because YOU exist 💕</p>
            <div class="slideshow">
               <img src="bithday title image.png" class="slide" />
                <img src="cake cutting image.png" class="slide" />
                <img src="birthday dance party.png" class="slide" /> 
            </div>
            <h3>🎵 A Special Voice Wish 🎵</h3>
            <audio controls> 
                <source src="happy-birthday-254480 (1).mp3" type="audio/mpeg"/>
            </audio>
            <audio controls>
                <source src="Dil Hai Chota Sa Ringtone Female Version Mp3 Download.mp3" type="audio/mpeg"/>
            </audio>
            <img width=420px src="img.png"/> 
            <div class="shayari">
              ❤️✨
                मेरी हर खुशी मेरी हर बात में हो तुम,<br />
                मेरी हर हंसी मेरी हर सांस में हो तुम।<br />
                इस जन्मदिन पर दुआ है मेरी जान,<br />
                कि आने वाले हर जन्म में भी मेरे साथ हो तुम। ❤️✨  
                <audio controls>
                    <source src="Tere Dil Pe Shaq Mera Hai.mp3" type="audio/mpeg"/>
                </audio>
            </div>
            <img width="420px" src="img2.png"/>
             <div class="shayari">
               🌹
            चांद से प्यारी चांदनी हो तुम,<br />
            फूलों से प्यारी खुशबू हो तुम।<br />
            जन्मदिन पर बस इतना कहना है जान,<br />
            मेरी पूरी दुनिया हो तुम। 🌹 
             
             <audio controls> 
                <source src="Ab Se Mera Bhi Raasta Hai Ringtone Download - MobCup.Com.Co.mp3" type="audio/mpeg">
             </audio>
             </div>
            <img width="420px" src="new bithday image.png"/>
            <div class="shayari">
                🌸🎉
                तू आई तो ज़िंदगी ने रंग बदले,<br/>
                हर दर्द ने भी प्यार के ढंग बदले।<br/>
                तेरा साथ मिले उम्र भर इसी तरह,<br/>
                यही दुआ है आज और हर पल, हर लम्हा।
            <audio controls>
                <source src="Meri Har Saans Tu Hai - Vatsal Bhoya _ Hindi Love.mp3" type="audio/mpeg">
            </audio>
            </div>
            <img width="420px" src="cartoon birthday.png"/>
            <div class="shayari">
                🎂❤️
                    तेरी एक मुस्कान से दिल सँवर जाता है,<br/>
                    तेरे नाम से ही मेरा हर दिन शुरू हो जाता है।<br/>
                    जन्मदिन पर बस इतना सा अरमान है,<br/>
                    हर जन्म में तू ही मेरी पहचान है।
                    <audio controls>
                        <source src="Arz Kiya Hai – Coke Studio Bharat Ringtone Download - MobCup.Com.Co.mp3" type="audio/mpeg">
                    </audio>
            </div>
            <img width="420px" src="garden birthday.png"/>
            <audio controls>
                <source src="Arz Kiya Hai – Coke Studio Bharat Ringtone Download - MobCup.Com.Co.mp3" type="audio/mpeg">
            </audio>
             <footer>
                Made with endless love 💖
             </footer>
             </div>
             <script>
               let index = 0;
               const slides = document.querySelectorAll('.slide');
               function showSlides() {
               slides.forEach(s => s.style.display = 'none');
               index = (index + 1) % slides.length;
               slides[index].style.display = 'block';
               }
               showSlides();
               setInterval(showSlides, 2500); 
            </script>   
        </body>
</html>
