<!doctype html>
<html lang="zh-Hant">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>Chen &amp; Chun Gender Reveal</title>
<style>
  :root{
    --bg:#FFF9D9;
    --card:#FFF6C2;
    --accent:#FFED8A;
    --accent-2:#FFEFA0;
    --text:#24303a;
    --muted:#6b6b6b;
  }
  html,body{height:100%;margin:0;background:linear-gradient(180deg,var(--bg),#FFF6D0);font-family: -apple-system, BlinkMacSystemFont, "Noto Sans TC", "Helvetica Neue", Arial, sans-serif;color:var(--text);-webkit-font-smoothing:antialiased;}
  .wrap{min-height:100vh;display:flex;flex-direction:column;align-items:center;justify-content:flex-start;padding:20px;gap:12px;box-sizing:border-box;}
  header{width:100%;max-width:720px;display:flex;flex-direction:column;align-items:center;gap:8px;margin-top:6px}
  h1{margin:0;font-size:20px;letter-spacing:0.6px}
  .subtitle{color:var(--muted);font-size:13px}
  main.card{width:100%;max-width:720px;background:linear-gradient(180deg,var(--card),#FFF2B8);border-radius:18px;padding:14px;box-shadow:0 10px 30px rgba(12,18,24,0.06);display:flex;flex-direction:column;align-items:center;gap:12px}
  .balloon-wrap{width:100%;display:flex;align-items:center;justify-content:center;padding:8px 0;height:56vw;max-height:520px;position:relative}
  #bigBalloon{width:60vw;max-width:420px;height:60vw;max-height:420px;border-radius:50%;background:linear-gradient(180deg,#FFF2B0,#FFEFA0);display:flex;align-items:center;justify-content:center;font-size:72px;box-shadow:0 18px 40px rgba(0,0,0,0.12);cursor:pointer;user-select:none;touch-action:manipulation;transition:transform 160ms cubic-bezier(.2,.9,.3,1)}
  #bigBalloon:active{transform:scale(0.98)}
  .clickCounter{position:absolute;right:16px;top:14px;background:rgba(255,255,255,0.65);padding:6px 10px;border-radius:999px;font-weight:700;color:var(--text)}
  .hint{font-size:14px;color:var(--muted);text-align:center;padding:0 12px}
  .btn-row{display:flex;gap:10px;flex-wrap:wrap;justify-content:center;width:100%}
  .btn{background:var(--accent-2);border:1px solid rgba(0,0,0,0.06);padding:10px 14px;border-radius:12px;font-weight:700;color:var(--text);cursor:pointer}
  .small{padding:6px 8px;font-size:13px}
  .overlay{position:fixed;inset:0;display:flex;align-items:center;justify-content:center;background:rgba(5,5,8,0.35);backdrop-filter:blur(4px);z-index:9999;opacity:0;pointer-events:none;transition:opacity 220ms ease}
  .overlay.show{opacity:1;pointer-events:auto}
  .reveal-card{width:calc(100% - 38px);max-width:720px;background:linear-gradient(180deg,#FFFDF0,#FFF9E0);border-radius:14px;padding:18px;text-align:center;box-shadow:0 18px 60px rgba(10,12,12,0.18)}
  .reveal-title{font-size:28px;margin:6px 0 8px;color:#2b2b2b}
  .reveal-sub{color:var(--muted);margin-bottom:8px}
  .baby-badge{width:120px;height:120px;border-radius:50%;display:flex;align-items:center;justify-content:center;margin:8px auto;font-size:48px;background:linear-gradient(180deg,#FFF3C5,#FFE290);box-shadow:0 10px 30px rgba(0,0,0,0.12)}
  .confetti-canvas{position:fixed;left:0;top:0;width:100%;height:100%;pointer-events:none;z-index:9998}
  .ultrasound{width:92%;max-width:560px;border-radius:12px;margin:8px auto;display:block;box-shadow:0 10px 30px rgba(0,0,0,0.12)}
  .guestbook{width:100%;margin-top:6px;background:rgba(255,255,255,0.6);padding:12px;border-radius:12px}
  .guest-input{width:100%;box-sizing:border-box;padding:10px;border-radius:10px;border:1px solid rgba(0,0,0,0.06);margin-bottom:8px;font-size:14px}
  .comments{max-height:220px;overflow:auto;padding:6px;display:flex;flex-direction:column;gap:8px}
  .comment{background:rgba(255,255,255,0.85);padding:8px;border-radius:10px;border:1px solid rgba(0,0,0,0.04);font-size:14px}
  .comment .meta{font-size:12px;color:var(--muted);margin-bottom:4px}
  footer{font-size:12px;color:var(--muted);margin-top:8px;padding-bottom:16px}
  @media (min-width:720px) { h1 { font-size:24px; } }
</style>
</head>
<body>
<div class="wrap">
  <header>
    <h1>Chen &amp; Chun Gender Reveal</h1>
    <div class="subtitle">點擊氣球 10 下 → 爆炸揭曉！</div>
  </header>

  <main class="card" role="main" aria-live="polite">
    <div class="balloon-wrap">
      <div id="bigBalloon" role="button" aria-label="大氣球" tabindex="0">🎈</div>
      <div class="clickCounter" id="clickCounter">0 / 10</div>
    </div>

    <div class="hint">快點按氣球達到 10 次，看看會發生什麼驚喜！</div>

    <div class="btn-row">
      <button id="resetBtn" class="btn small">重設</button>
      <button id="shareBtn" class="btn small">分享</button>
    </div>

    <section class="guestbook" aria-label="匿名留言牆">
      <div style="font-weight:700;margin-bottom:6px">匿名留言牆</div>
      <textarea id="msg" class="guest-input" rows="3" placeholder="寫下你的祝福（匿名）"></textarea>
      <div style="display:flex;gap:8px">
        <button id="postBtn" class="btn small">發布</button>
        <div style="flex:1"></div>
      </div>
      <div class="comments" id="comments" aria-live="polite"></div>
    </section>
  </main>

  <footer>Made with 💛 — Chen &amp; Chun</footer>
</div>

<!-- reveal overlay -->
<div id="overlay" class="overlay" role="dialog" aria-modal="true" aria-hidden="true">
  <canvas id="confetti" class="confetti-canvas"></canvas>
  <div class="reveal-card" role="document">
    <div class="baby-badge">👶</div>
    <div class="reveal-title">It's a BOY!</div>
    <div class="reveal-sub">Baby Boy Coming Soon 💛</div>
    <!-- IMPORTANT: put your ultrasound image file named "ultrasound.jpg" in the same folder as this index.html -->
    <img src="ultrasound.jpg" alt="Ultrasound" class="ultrasound" />
    <div style="margin-top:8px;display:flex;gap:8px;justify-content:center;flex-wrap:wrap">
      <button id="replayBtn" class="btn small">再玩一次</button>
      <button id="closeBtn" class="btn small">關閉</button>
    </div>
  </div>
</div>

<script>
  const TARGET = 10;
  const bigBalloon = document.getElementById('bigBalloon');
  const counterEl = document.getElementById('clickCounter');
  let clicks = 0;
  let exploded = false;

  function updateCounter(){ counterEl.textContent = clicks + ' / ' + TARGET; }

  function popEffect(){
    bigBalloon.style.transition = 'transform 260ms ease, opacity 260ms ease';
    bigBalloon.style.transform = 'scale(0.2) rotate(-20deg)';
    bigBalloon.style.opacity = '0';
    setTimeout(()=>{ bigBalloon.style.display = 'none'; }, 300);
  }

  function showOverlay(){
    const overlay = document.getElementById('overlay');
    overlay.classList.add('show');
    overlay.setAttribute('aria-hidden','false');
    startConfetti();
  }

  function explode(){
    if (exploded) return;
    exploded = true;
    popEffect();
    setTimeout(()=>{ showOverlay(); }, 420);
  }

  bigBalloon.addEventListener('click', ()=>{
    if (exploded) return;
    clicks++;
    bigBalloon.style.transform = 'scale(0.96)';
    setTimeout(()=>{ if(!exploded) bigBalloon.style.transform = ''; }, 120);
    updateCounter();
    if (clicks >= TARGET) explode();
  });

  bigBalloon.addEventListener('keydown', (e)=>{
    if (e.key === 'Enter' || e.key === ' ') { e.preventDefault(); bigBalloon.click(); }
  });

  document.getElementById('resetBtn').addEventListener('click', ()=>{
    clicks = 0; exploded = false; updateCounter();
    bigBalloon.style.display = 'flex'; bigBalloon.style.opacity = '1'; bigBalloon.style.transform = '';
  });

  document.getElementById('replayBtn').addEventListener('click', ()=>{
    document.getElementById('overlay').classList.remove('show');
    document.getElementById('overlay').setAttribute('aria-hidden','true');
    clicks = 0; exploded = false; updateCounter();
    bigBalloon.style.display = 'flex'; bigBalloon.style.opacity = '1'; bigBalloon.style.transform = '';
    stopConfetti();
  });
  document.getElementById('closeBtn').addEventListener('click', ()=>{
    document.getElementById('overlay').classList.remove('show');
    document.getElementById('overlay').setAttribute('aria-hidden','true');
    stopConfetti();
  });

  document.getElementById('shareBtn').addEventListener('click', async ()=>{
    const shareData = { title: 'Chen & Chun Gender Reveal', text: "我們要生男孩啦！一起來看看！", url: location.href };
    try{
      if(navigator.share) await navigator.share(shareData);
      else { await navigator.clipboard.writeText(shareData.text + ' ' + shareData.url); alert('連結已複製'); }
    }catch(e){ alert('分享失敗'); }
  });

  // anonymous guestbook
  const postBtn = document.getElementById('postBtn');
  const commentsEl = document.getElementById('comments');
  postBtn.addEventListener('click', ()=>{
    const txt = document.getElementById('msg').value.trim();
    if(!txt) return alert('請輸入留言');
    const el = document.createElement('div'); el.className = 'comment';
    const meta = document.createElement('div'); meta.className = 'meta';
    const now = new Date();
    meta.textContent = '匿名 · ' + now.toLocaleString();
    const body = document.createElement('div'); body.textContent = txt;
    el.appendChild(meta); el.appendChild(body);
    commentsEl.prepend(el);
    document.getElementById('msg').value = '';
  });

  // confetti
  const canvas = document.getElementById('confetti');
  const ctx = canvas.getContext('2d');
  let pieces = []; let animId = null;
  function resizeCanvas(){ canvas.width = window.innerWidth; canvas.height = window.innerHeight; }
  window.addEventListener('resize', resizeCanvas); resizeCanvas();

  function startConfetti(){
    pieces = []; const count = Math.min(180, Math.floor(window.innerWidth/4));
    for(let i=0;i<count;i++){
      pieces.push({
        x: Math.random()*canvas.width,
        y: Math.random()*-canvas.height,
        w: 8 + Math.random()*10,
        h: 12 + Math.random()*18,
        angle: Math.random()*360,
        speedY: 2 + Math.random()*4,
        speedX: -1.5 + Math.random()*3,
        rot: Math.random()*360,
        rotSpeed: -6 + Math.random()*12,
        color: (Math.random()<0.85) ? randomYellow() : randomLight(),
        opacity: 0.9 + Math.random()*0.1
      });
    }
    if(animId) cancelAnimationFrame(animId);
    confettiLoop();
    try{ playRevealJingle(); }catch(e){}
  }
  function stopConfetti(){ if(animId) cancelAnimationFrame(animId); animId = null; ctx.clearRect(0,0,canvas.width,canvas.height); }
  function confettiLoop(){
    ctx.clearRect(0,0,canvas.width,canvas.height);
    pieces.forEach(p=>{
      p.x += p.speedX; p.y += p.speedY; p.rot += p.rotSpeed; p.speedY += 0.02;
      ctx.save(); ctx.translate(p.x,p.y); ctx.rotate(p.rot * Math.PI / 180); ctx.globalAlpha = p.opacity; ctx.fillStyle = p.color;
      ctx.fillRect(-p.w/2, -p.h/2, p.w, p.h); ctx.restore();
      if(p.y > canvas.height + 60){ p.y = -20 - Math.random()*canvas.height*0.6; p.x = Math.random()*canvas.width; p.speedY = 2 + Math.random()*4; }
    });
    animId = requestAnimationFrame(confettiLoop);
  }
  function randomYellow(){ const arr = ['#FFF1A8','#FFE98A','#FFED8A','#FFEF7D']; return arr[Math.floor(Math.random()*arr.length)]; }
  function randomLight(){ const arr = ['#FFF6BF','#FFF9D9','#FFF8E6']; return arr[Math.floor(Math.random()*arr.length)]; }

  // small jingle
  let audioCtx = null;
  function playRevealJingle(){
    if(!window.AudioContext && !window.webkitAudioContext) return;
    if(!audioCtx) audioCtx = new (window.AudioContext || window.webkitAudioContext)();
    const ctx = audioCtx; const now = ctx.currentTime;
    const o1 = ctx.createOscillator(), g1 = ctx.createGain();
    o1.type='sine'; o1.frequency.setValueAtTime(720, now); g1.gain.setValueAtTime(0.0001, now); g1.gain.exponentialRampToValueAtTime(0.06, now+0.01);
    o1.connect(g1); g1.connect(ctx.destination);
    const o2 = ctx.createOscillator(), g2 = ctx.createGain();
    o2.type='sine'; o2.frequency.setValueAtTime(540, now); g2.gain.setValueAtTime(0.0001, now); g2.gain.exponentialRampToValueAtTime(0.04, now+0.01);
    o2.connect(g2); g2.connect(ctx.destination);
    o1.start(now); o2.start(now);
    o1.frequency.exponentialRampToValueAtTime(320, now+0.5); o2.frequency.exponentialRampToValueAtTime(260, now+0.5);
    g1.gain.exponentialRampToValueAtTime(0.0001, now+0.8); g2.gain.exponentialRampToValueAtTime(0.0001, now+0.8);
    o1.stop(now+0.9); o2.stop(now+0.9);
  }

  document.addEventListener('keydown', (e)=>{ if(e.key === 'Escape'){ const ov = document.getElementById('overlay'); ov.classList.remove('show'); stopConfetti(); } });
  updateCounter();
</script>
</body>
</html>
