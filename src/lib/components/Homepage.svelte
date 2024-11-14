
<section class="home">
    <div class="content">
      <h1 class="title">
        Hadiah Penuh Makna,<br> Dari Gus Dur
      </h1>
      <p class="description">
        Koleksi unik yang mencerminkan semangat toleransi
      </p>
      <p class="description">
        dan kebijaksanaan Gus Dur.
      </p>

      <div class="scroll-down">
        <span class="scroll-icon">&#8595;</span>
      </div>
    </div>
  </section>
  
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&display=swap');
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap');
  
    .home {
      display: flex;
      justify-content: center;
      align-items: center;
      height: auto; 
      min-height: 60vh;
      background-color: white;
      border-radius: 15px; 
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1); 
      padding: 20px;
      position: relative;
      margin: 20px;
    }
  
    .content {
      text-align: center;
      max-width: 800px; 
      padding: 20px;
    }
  
    .title {
      font-family: 'Bebas Neue', sans-serif;
      font-size: 5rem; 
      color: #333;
      margin: 0; 
      line-height: 1.1; 
    }
  
    .description {
      font-family: 'Poppins', sans-serif;
      font-size: 1.2rem; 
      font-weight: 400;
      color: #555;
      line-height: 1.1; 
      margin-bottom: 20px; 
    }
  

    .scroll-down {
     
      bottom: 40px;
      left: 50%;
      transform: translateX(-50%);
      animation: bounce 1.5s infinite;
    }
  
    .scroll-icon {
      font-size: 3rem; 
      color: #333;
      font-weight: 600;
      cursor: pointer;
    }
  
    @keyframes bounce {
      0%, 100% {
        transform: translateY(0);
      }
      50% {
        transform: translateY(-10px);
      }
    }
  

    @media (max-width: 768px) {
      .title {
        font-size: 3rem; 
      }
  
      .description {
        font-size: 1rem;
      }
  
      .scroll-icon {
        font-size: 2rem; 
      }
    }
  </style>
  