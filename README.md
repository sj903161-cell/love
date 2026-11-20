# love

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>For My Sweet Budhu 💗</title>

<style>
*{margin:0;padding:0;box-sizing:border-box}
body{
 font-family:'Georgia',serif;
 background:linear-gradient(135deg,#ffe0ef,#ffc1dc,#fff0f6);
 color:#8b2854;
 overflow-x:hidden;
}
html{scroll-behavior:smooth}
section{
 padding:55px 20px;
 text-align:center;
}
.hero{
 min-height:100vh;
 display:flex;
 flex-direction:column;
 justify-content:center;
 align-items:center;
 padding:30px 20px;
 background:linear-gradient(145deg,#ff9fc9,#ffd6e8,#fff0f6);
}
h1{font-size:42px;color:#b51d63;margin:15px}
h2{font-size:29px;color:#c02b70;margin-bottom:20px}
h3{color:#b51d63;margin-bottom:12px}
p{
 font-size:17px;
 line-height:1.9;
 max-width:750px;
 margin:12px auto;
}
.heart{font-size:55px;animation:pulse 1.5s infinite}
@keyframes pulse{
 50%{transform:scale(1.2)}
}
.card{
 background:rgba(255,255,255,.78);
 padding:25px;
 border-radius:24px;
 max-width:780px;
 margin:20px auto;
 box-shadow:0 8px 25px #d95b9140;
 border:1px solid #ffffff;
}
button{
 border:0;
 background:linear-gradient(90deg,#e83e88,#ff75ad);
 color:white;
 padding:14px 24px;
 border-radius:30px;
 font-size:16px;
 margin:12px 5px;
 cursor:pointer;
 box-shadow:0 5px 15px #d84d8a55;
}
button:active{transform:scale(.96)}
.hidden{display:none}
.shayari{
 background:#fff1f7;
 border-radius:18px;
 padding:18px;
 margin:15px auto;
 max-width:650px;
 line-height:2;
 font-size:17px;
}
#countdown{
 display:flex;
 justify-content:center;
 flex-wrap:wrap;
 gap:12px;
 margin:25px auto;
}
.timebox{
 background:white;
 padding:15px;
 border-radius:16px;
 min-width:75px;
 box-shadow:0 5px 15px #d84d8a30;
}
.timebox strong{font-size:25px;color:#d52e78;display:block}
.timebox span{font-size:12px}
.promise,.reason{
 background:#fff1f7;
 padding:15px;
 border-radius:15px;
 margin:12px auto;
 max-width:650px;
}
footer{
 padding:35px 15px;
 text-align:center;
 background:#f78fba;
 color:white;
 line-height:2;
}
.floating{
 position:fixed;
 bottom:-30px;
 pointer-events:none;
 animation:floatUp 8s linear forwards;
 z-index:10;
}
@keyframes floatUp{
 0%{transform:translateY(0) rotate(0);opacity:.8}
 100%{transform:translateY(-110vh) rotate(360deg);opacity:0}
}
.highlight{color:#d32977;font-weight:bold}
</style>
</head>

<body>

<!-- FLOATING HEARTS -->
<div class="hero">
 <div class="heart">💗</div>
 <h1>My Sweet Budhu</h1>
 <h2>For My Anshika 🥰</h2>
 <p>
 Some people enter our lives and make everything feel a little more beautiful.
 You are one of those special people. This little website is a collection
 of warm thoughts, smiles and beautiful wishes made especially for you.
 </p>
 <p><b>With affection, Sanyam Jain ❤️</b></p>
 <a href="#birthday"><button>Open Your Special World 💌</button></a>
</div>

<!-- BIRTHDAY -->
<section id="birthday">
 <h2>🎂 A Special Birthday Wish 🎂</h2>
 <div class="card">
  <div class="heart">🎀</div>
  <h3>Happy Birthday, Anshika!</h3>
  <p>
   May your birthday bring countless reasons to smile, peaceful moments,
   beautiful surprises and wonderful opportunities. May every new day
   bring you closer to your dreams. Never stop believing in yourself,
   because you deserve all the happiness, success and kindness that life
   has to offer.
  </p>
  <p>
   Keep shining with your beautiful personality, keep laughing with
   your lovely smile and always remember how special your existence is.
   May your coming year be filled with unforgettable memories! 💗
  </p>
  <button onclick="birthdayWish()">Open Birthday Surprise 🎁</button>
  <p id="birthdayMessage" class="hidden highlight">
   A thousand wishes for your happiness! Happy Birthday, Budhu! 🎂🌷💖
  </p>
 </div>
</section>

<!-- COUNTDOWN -->
<section>
 <h2>⏳ Our Special Countdown</h2>
 <div class="card">
  <p>A little countdown to 21 November 2026! 💕</p>
  <div id="countdown">
   <div class="timebox"><strong id="days">00</strong><span>Days</span></div>
   <div class="timebox"><strong id="hours">00</strong><span>Hours</span></div>
   <div class="timebox"><strong id="minutes">00</strong><span>Minutes</span></div>
   <div class="timebox"><strong id="seconds">00</strong><span>Seconds</span></div>
  </div>
  <p id="countText">Every special moment deserves a beautiful memory. 💗</p>
 </div>
</section>

<!-- LOVE LETTER -->
<section>
 <h2>💌 A Little Letter for You</h2>
 <div class="card">
  <h3>Dear Anshika, My Budhu 💗</h3>
  <p>
   Sometimes words are not enough to express how much a person means
   to us. Still, I wanted to create something special to remind you
   that you are appreciated. Your conversations, your laughter and
   the little moments we share can make an ordinary day feel brighter.
  </p>
  <p>
   Thank you for being a beautiful part of my memories. Thank you for
   the smiles, the conversations and all those little moments that
   become special without even trying. I hope life always gives you
   reasons to smile and courage to follow your dreams.
  </p>
  <p class="highlight">Keep smiling always, Budhu! 💗</p>
  <p>With lots of warm wishes,<br><b>Sanyam Jain 🌹</b></p>
 </div>
</section>

<!-- FOUR SHAYARI -->
<section>
 <h2>🌹 Four Little Shayaris</h2>
 <div class="shayari">
  तेरी मुस्कान से रोशन हर शाम हो जाए,<br>
  तेरी खुशी से खूबसूरत हर मुकाम हो जाए।<br>
  यूँ ही हँसती रहना हमेशा तुम,<br>
  तुम्हारे नाम हर खुशी तमाम हो जाए। 💗
 </div>
 <div class="shayari">
  कुछ बातें दिल को छू जाती हैं,<br>
  कुछ यादें चेहरे पर मुस्कान लाती हैं।<br>
  कुछ लोग इतने खास होते हैं,<br>
  उनकी मौजूदगी ही खुशियाँ दे जाती है। 🌸
 </div>
 <div class="shayari">
  चाँद की रोशनी से प्यारी हो तुम्हारी हँसी,<br>
  फूलों की खुशबू से प्यारी हो तुम्हारी खुशी।<br>
  हर सपना तुम्हारा पूरा हो जाए,<br>
  जिंदगी में कभी कम न हो हँसी। 🦋
 </div>
 <div class="shayari">
  हर दिन तुम्हारे लिए नई उम्मीद लाए,<br>
  हर सुबह तुम्हारे चेहरे पर मुस्कान सजाए।<br>
  खुशियों से भरी रहे तुम्हारी दुनिया,<br>
  और हर पल तुम्हें आगे बढ़ना सिखाए। 💕
 </div>
</section>

<!-- SURPRISE -->
<section>
 <h2>🎁 A Little Surprise</h2>
 <div class="card">
  <p>
   There is a little message hidden here, specially written for you.
   Click the button and discover it!
  </p>
  <button onclick="reveal('surprise')">Click for Your Surprise 💝</button>
  <div id="surprise" class="hidden">
   <h3>Surprise, Budhu! 🥰</h3>
   <p>
    If I could give you one thing, it would be the ability to see
    yourself through the eyes of the people who appreciate you.
    You would understand how much happiness your smile can bring.
    Never underestimate your worth. You are one of a kind! 💗
   </p>
  </div>
 </div>
</section>

<!-- OUR LITTLE UNIVERSE -->
<section>
 <h2>🌍 Our Little Universe</h2>
 <div class="card">
  <p>
   Imagine a little universe where every star represents a happy memory,
   every moon represents a peaceful night and every sunrise brings a new
   reason to smile. That is how I imagine the beauty of special connections.
  </p>
  <p>
   It is not always about grand gestures or perfect moments. Sometimes
   it is a simple conversation, a random laugh, a small message or just
   knowing that someone is doing well. These little things can make
   ordinary days feel extraordinary.
  </p>
  <p>
   I hope your own universe is always filled with kindness, confidence,
   good people, exciting dreams and endless reasons to be happy. ✨
  </p>
 </div>
</section>

<!-- 100 REASONS -->
<section>
 <h2>😊 100 Reasons to Smile</h2>
 <div class="card">
  <p>
   There are so many little things worth appreciating about life.
   Here is a collection of 100 sweet reminders for you.
  </p>
  <h3 id="reasonNumber">Reason 1 of 100</h3>
  <p id="reasonText" class="highlight">Your smile can brighten an ordinary day. 💗</p>
  <button onclick="nextReason()">Next Reason 🌷</button>
  <p id="reasonCount">1 / 100</p>
 </div>
</section>

<!-- PROMISES -->
<section>
 <h2>💞 Promises from My Heart</h2>
 <div class="card">
  <div class="promise">🌸 I promise to respect your thoughts, choices and dreams.</div>
  <div class="promise">🤝 I promise to value honesty and trust in every conversation.</div>
  <div class="promise">🌷 I promise to encourage you whenever you work towards something important.</div>
  <div class="promise">😊 I promise to appreciate the little things and never take kindness for granted.</div>
  <div class="promise">🦋 I promise to respect your personal space and individuality.</div>
  <div class="promise">💗 I promise to always wish the best for your happiness and success.</div>
  <p>
   Real care is not about perfect words. It is about respect, patience,
   honesty and showing kindness through everyday actions.
  </p>
 </div>
</section>

<!-- BEAUTIFUL MEMORIES -->
<section>
 <h2>✨ Our Beautiful Memories</h2>
 <div class="card">
  <p>
   Some memories do not need photographs to stay special. They live
   in little conversations, unexpected laughter, funny moments and
   the small details that make us smile later.
  </p>
  <p>
   Maybe one day, we will look back and remember how simple moments
   became beautiful stories. Until then, let's keep collecting good
   memories, learning new things and making every day meaningful.
  </p>
  <p class="highlight">
   The little moments often become the biggest memories. 🌷
  </p>
 </div>
</section>

<!-- DIFFICULT DAYS -->
<section>
 <h2>🦋 A Letter for Your Difficult Days</h2>
 <div class="card">
  <p>
   Dear Budhu, if a day ever feels difficult, remember that one difficult
   moment does not define your entire story. You are allowed to take
   your time, learn slowly, rest when needed and begin again.
  </p>
  <p>
   Never feel that you have to be perfect every day. Your dreams matter,
   your feelings matter and your happiness matters. Celebrate your small
   achievements because every little step forward counts.
  </p>
  <p>
   I hope you always find the strength to believe in yourself and the
   courage to keep moving towards the life you dream of. May tomorrow
   bring you fresh hope and a beautiful reason to smile. 💗
  </p>
  <h3>You are capable of wonderful things! 🌈</h3>
 </div>
</section>

<!-- REASONS TO SMILE -->
<section>
 <h2>🌸 Little Reminders</h2>
 <div class="card">
  <div class="reason">Your dreams are worth working for. ✨</div>
  <div class="reason">Your happiness deserves attention. 💗</div>
  <div class="reason">You do not need to compare your journey with anyone else's. 🦋</div>
  <div class="reason">Small progress is still progress. 🌷</div>
  <div class="reason">You deserve kindness, respect and peace. 🌼</div>
  <div class="reason">Never forget to celebrate yourself. 🎀</div>
 </div>
</section>

<!-- SECRET MESSAGE -->
<section>
 <h2>🤫 One Secret Message</h2>
 <div class="card">
  <p>
   There is one little message waiting for you.
   Open it whenever you are ready! 💌
  </p>
  <button onclick="reveal('secret')">Open My Secret ❤️</button>
  <div id="secret" class="hidden">
   <h2>I LOVE YOU 💗🥰🌹</h2>
   <p>
    You are someone I genuinely appreciate. I hope we always treat
    each other with honesty, care, respect and understanding.
    Keep being your wonderful self, Anshika! 💕
   </p>
  </div>
 </div>
</section>

<!-- LAST SURPRISE -->
<section>
 <h2>🎀 One Last Precious Surprise</h2>
 <div class="card">
  <p>
   Before you leave this little pink world, there is one final message
   written especially for you.
  </p>
  <button onclick="reveal('lastSurprise')">Open the Final Surprise 🎁</button>
  <div id="lastSurprise" class="hidden">
   <h3>For You, Budhu 💗</h3>
   <p>
    If this website could speak, it would tell you that you deserve
    beautiful mornings, peaceful evenings, genuine friendships,
    exciting opportunities and countless happy memories.
   </p>
   <p>
    Never stop dreaming. Never stop learning. Never stop being kind.
    I hope every chapter of your life brings something meaningful,
    and whenever you look back, you find many reasons to feel proud
    of yourself.
   </p>
   <p>
    Thank you for being a beautiful part of my memories.
    Keep smiling always! 💗
   </p>
   <h2>You are a beautiful chapter in my life. 🌷</h2>
   <h2>Keep Smiling, Budhu! 💗🥰</h2>
   <h3>With affection, Sanyam ❤️</h3>
  </div>
 </div>
</section>

<footer>
 <h2>Made with 💗</h2>
 <p>Especially for Anshika (My Sweet Budhu)</p>
 <p>From Sanyam Jain 🌹</p>
 <p>May your life always be filled with happiness and beautiful memories.</p>
 <p>© 2026 | A Little World of Pink Love</p>
</footer>

<script>
function reveal(id){
 const el=document.getElementById(id);
 el.classList.toggle('hidden');
}

function birthdayWish(){
 document.getElementById('birthdayMessage').classList.remove('hidden');
}

const target=new Date('2026-11-21T00:00:00+05:30').getTime();

function updateCountdown(){
 const now=Date.now();
 const distance=target-now;

 if(distance<=0){
  document.getElementById('days').textContent='00';
  document.getElementById('hours').textContent='00';
  document.getElementById('minutes').textContent='00';
  document.getElementById('seconds').textContent='00';
  document.getElementById('countText').textContent='The special day is here! 💗';
  return;
 }

 document.getElementById('days').textContent=Math.floor(distance/(1000*60*60*24));
 document.getElementById('hours').textContent=Math.floor((distance%(1000*60*60*24))/(1000*60*60));
 document.getElementById('minutes').textContent=Math.floor((distance%(1000*60*60))/(1000*60));
 document.getElementById('seconds').textContent=Math.floor((distance%(1000*60))/1000);
}
updateCountdown();
setInterval(updateCountdown,1000);

const reasons=[
"Your smile can brighten an ordinary day. 💗",
"Your dreams deserve to be followed. ✨",
"You bring your own special energy to the world. 🌸",
"Your laughter makes moments memorable. 😊",
"You deserve kindness every single day. 🌷",
"You have the courage to learn and grow. 🦋",
"Your little achievements matter. 🎀",
"You make ordinary conversations special. 💕",
"You deserve peace and happiness. 🌼",
"You are unique in your own beautiful way. 💖",
"Your future holds so many possibilities. 🌈",
"You should always believe in yourself. 🌹",
"Your kindness can make a difference. 💗",
"Every new day is a fresh beginning. ☀️",
"You deserve to celebrate your progress. 🥰"
];

for(let i=16;i<=100;i++){
 reasons.push("Reason "+i+": There is always something wonderful about you worth appreciating. 💗");
}

let currentReason=0;

function nextReason(){
 currentReason=(currentReason+1)%reasons.length;
 document.getElementById('reasonNumber').textContent='Reason '+(currentReason+1)+' of 100';
 document.getElementById('reasonText').textContent=reasons[currentReason];
 document.getElementById('reasonCount').textContent=(currentReason+1)+' / 100';
}

function createHeart(){
 const heart=document.createElement('div');
 heart.className='floating';
 heart.textContent=['💗','💕','💖','🌸','💘'][Math.floor(Math.random()*5)];
 heart.style.left=Math.random()*100+'vw';
 heart.style.fontSize=(15+Math.random()*20)+'px';
 heart.style.animationDuration=(5+Math.random()*5)+'s';
 document.body.appendChild(heart);
 setTimeout(()=>heart.remove(),10000);
}
setInterval(createHeart,650);
</script>

</body>
</html>
