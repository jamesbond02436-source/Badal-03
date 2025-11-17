<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Happy Birthday Manisha 🎀</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Poppins", sans-serif;
    }

    body {
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 16px;
      background: linear-gradient(135deg, #ffeaf4, #fdf6ff, #e4f3ff);
      position: relative;
      overflow: hidden;
    }

    /* soft floating elements */
    .bubble {
      position: absolute;
      width: 90px;
      height: 90px;
      border-radius: 50%;
      background: radial-gradient(circle, rgba(255,255,255,0.9), rgba(255,204,230,0.2));
      filter: blur(0.5px);
      opacity: 0.7;
      animation: float 10s infinite linear;
      z-index: 0;
    }

    .bubble:nth-child(1) { top: 10%; left: 5%; animation-duration: 13s; }
    .bubble:nth-child(2) { top: 70%; right: 10%; animation-duration: 16s; }
    .bubble:nth-child(3) { top: 40%; left: 75%; animation-duration: 11s; }
    .bubble:nth-child(4) { top: 85%; left: 35%; animation-duration: 18s; }

    @keyframes float {
      0% { transform: translateY(0) translateX(0); }
      50% { transform: translateY(-30px) translateX(10px); }
      100% { transform: translateY(0) translateX(0); }
    }

    .card {
      position: relative;
      z-index: 1;
      max-width: 480px;
      width: 100%;
      background: rgba(255, 255, 255, 0.85);
      border-radius: 24px;
      padding: 28px 24px 26px;
      box-shadow: 0 12px 35px rgba(255, 184, 214, 0.6);
      text-align: center;
      border: 1.5px solid #ffd6ec;
      backdrop-filter: blur(6px);
    }

    .tag {
      display: inline-block;
      font-size: 0.8rem;
      letter-spacing: 1px;
      text-transform: uppercase;
      padding: 4px 10px;
      border-radius: 999px;
      background: #ffe4f5;
      color: #ff6f9c;
      margin-bottom: 10px;
    }

    .photo-wrapper {
      margin: 10px 0 18px;
    }

    .photo {
      width: 130px;
      height: 130px;
      border-radius: 999px;
      border: 3px solid #ffcbe7;
      object-fit: cover;
      box-shadow: 0 8px 18px rgba(255, 140, 180, 0.4);
      animation: softBounce 3.5s infinite ease-in-out;
    }

    @keyframes softBounce {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-5px); }
    }

    h1 {
      font-size: 1.9rem;
      margin-bottom: 6px;
      color: #ff5f9a;
    }

    h2 {
      font-size: 1.05rem;
      font-weight: 500;
      margin-bottom: 16px;
      color: #ff92b9;
    }

    p {
      font-size: 0.98rem;
      line-height: 1.7;
      color: #714b63;
      margin-bottom: 14px;
    }

    .name {
      font-weight: 600;
      color: #ff4f9b;
    }

    .from {
      font-size: 0.92rem;
      margin-top: 8px;
      color: #9a6c8b;
    }

    .divider {
      width: 60%;
      height: 1px;
      background: linear-gradient(to right, transparent, #ffc6e4, transparent);
      margin: 12px auto 10px;
    }

    .btn {
      margin-top: 10px;
      padding: 9px 22px;
      border-radius: 999px;
      border: none;
      cursor: pointer;
      font-size: 0.9rem;
      font-weight: 600;
      background: linear-gradient(135deg, #ffb3d9, #ffd6f0);
      color: #7a385d;
      box-shadow: 0 8px 18px rgba(255, 158, 196, 0.6);
      transition: transform 0.15s ease, box-shadow 0.15s ease;
    }

    .btn:hover {
      transform: translateY(-2px);
      box-shadow: 0 11px 26px rgba(255, 133, 187, 0.8);
    }

    .tiny {
      font-size: 0.8rem;
      margin-top: 8px;
      color: #b17fa2;
    }

    .tiny span {
      font-size: 0.9rem;
    }

    /* cute butterfly in the corner */
    .butterfly {
      position: absolute;
      top: -12px;
      right: 16px;
      font-size: 1.6rem;
      animation: flutter 4s infinite ease-in-out;
    }

    @keyframes flutter {
      0%, 100% { transform: translateY(0) rotate(0deg); }
      50% { transform: translateY(-8px) rotate(6deg); }
    }
  </style>
</head>
<body>

  <!-- soft bubbles in background -->
  <div class="bubble"></div>
  <div class="bubble"></div>
  <div class="bubble"></div>
  <div class="bubble"></div>

  <div class="card">
    <div class="butterfly">🦋</div>
    <div class="tag">Happy Birthday</div>

    <!-- Replace this with Manisha's real photo file or URL -->
    <div class="photo-wrapper">
      <img class="photo" src="manisha-cute.jpg" alt="Manisha">
    </div>

    <h1>Happy Birthday, <span class="name">Manisha 🌸</span></h1>
    <h2>You are the softest kind of magic in my world ✨</h2>

    <p>
      Manisha, you don’t just add days to the calendar, you add color to my life.  
      Your smile feels like sunshine on a gentle morning, and your presence makes
      even simple moments feel a little more special and a lot more beautiful.
    </p>

    <p>
      On your birthday, I wish you silly laughs, tight hugs, warm chai on rainy days,
      and a heart that always feels safe and loved. You deserve soft things, calm days,
      big dreams, and someone who never stops choosing you — and my heart already does. 💖
    </p>

    <div class="divider"></div>

    <p class="from">
      With all my affection,<br>
      <span class="name">[Your Name]</span>
    </p>

    <button class="btn">
      Tap for a secret wish 💫
    </button>

    <div class="tiny">
      (P.S. I secretly wish your smile is something I get to protect forever. <span>🤍</span>)
    </div>
  </div>

</body>
</html>
