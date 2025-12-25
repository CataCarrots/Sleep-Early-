<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Sleep Early</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Poppins", sans-serif;
    }

    body {
      height: 100vh;
      background: radial-gradient(circle at top, #0a0f2c, #02030a);
      overflow: hidden;
      display: flex;
      align-items: center;
      justify-content: center;
      color: #fff;
    }

    /* Stars */
    .stars {
      position: absolute;
      width: 100%;
      height: 100%;
      background: transparent;
    }

    .star {
      position: absolute;
      width: 2px;
      height: 2px;
      background: white;
      border-radius: 50%;
      opacity: 0.8;
      animation: twinkle 3s infinite ease-in-out;
    }

    @keyframes twinkle {
      0%, 100% { opacity: 0.3; }
      50% { opacity: 1; }
    }

    /* Moon */
    .moon {
      position: absolute;
      top: 80px;
      right: 120px;
      width: 120px;
      height: 120px;
      background: #f5f3ce;
      border-radius: 50%;
      box-shadow: 0 0 40px rgba(255, 255, 200, 0.8);
      animation: float 6s ease-in-out infinite;
    }

    @keyframes float {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-15px); }
    }

    /* Text */
    .message {
      text-align: center;
      z-index: 2;
      animation: fadeIn 3s ease forwards;
    }

    .message h1 {
      font-size: 3rem;
      letter-spacing: 2px;
      text-shadow: 0 0 15px rgba(173, 216, 230, 0.8);
    }

    .message p {
      margin-top: 10px;
      font-size: 1.3rem;
      opacity: 0.8;
    }

    @keyframes fadeIn {
      from {
        opacity: 0;
        transform: translateY(20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
  </style>
</head>
<body>

  <div class="stars">
    <!-- Generate stars -->
    <script>
      for (let i = 0; i < 100; i++) {
        const star = document.createElement("div");
        star.className = "star";
        star.style.top = Math.random() * 100 + "%";
        star.style.left = Math.random() * 100 + "%";
        star.style.animationDuration = (2 + Math.random() * 3) + "s";
        document.querySelector(".stars").appendChild(star);
      }
    </script>
  </div>

  <div class="moon"></div>

  <div class="message">
    <h1>Sleep Early!!!</h1>
    <p>– Amiel</p>
  </div>

</body>
</html>
