<div align="center">
  <svg width="100%" height="90" viewBox="0 0 600 90" xmlns="http://www.w3.org/2000/svg">
    <style>
      .slide-text {
        font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
        font-size: 38px;
        font-weight: 800;
        fill: #FFFFFF;
        letter-spacing: 2px;
        opacity: 0;
        animation: slideIn 2.5s cubic-bezier(0.25, 1, 0.5, 1) forwards, glow 3s ease-in-out infinite alternate;
      }

      @keyframes slideIn {
        0% {
          opacity: 0;
          transform: translateX(-120px);
        }
        100% {
          opacity: 1;
          transform: translateX(0);
        }
      }

      @keyframes glow {
        from {
          filter: drop-shadow(0 0 2px rgba(255, 255, 255, 0.2));
        }
        to {
          filter: drop-shadow(0 0 8px rgba(255, 255, 255, 0.8));
        }
      }
    </style>
    <text x="50%" y="55" text-anchor="middle" class="slide-text">Clyde-Nguyen</text>
  </svg>
</div>
