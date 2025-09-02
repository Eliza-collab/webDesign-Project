<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Customer Testimonials Page</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #0f0f10;
      color: #ffffff;
      line-height: 1.6;
    }
    .section {
      max-width: 1100px;
      margin: auto;
      padding: 40px 20px;
    }
    h1, h2 {
      text-align: center;
    }
    .testimonials {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 20px;
      margin-top: 30px;
    }
    .card {
      background: #1a1a1b;
      padding: 20px;
      border-radius: 10px;
    }
    .stars {
      color: #ffcc00;
      margin-bottom: 10px;
    }
    .user-info {
      display: flex;
      align-items: center;
      margin-top: 15px;
    }
    .user-info img {
      width: 45px;
      height: 45px;
      border-radius: 50%;
      margin-right: 10px;
    }
    .faq-section {
      margin-top: 50px;
    }
    .faq-list {
      max-width: 700px;
      margin: auto;
    }
    .faq-item {
      background: #1a1a1b;
      margin-bottom: 10px;
      padding: 15px;
      border-radius: 8px;
    }
    .faq-item h4 {
      margin: 0;
    }
    .contact-btn {
      display: inline-block;
      background: #1a1a1b;
      color: #fff;
      padding: 10px 20px;
      border-radius: 6px;
      text-decoration: none;
      margin: 20px auto;
      display: block;
      text-align: center;
    }
    .bottom-section {
      text-align: center;
      margin-top: 50px;
    }
    .cta-buttons {
      margin-top: 20px;
    }
    .cta-buttons a {
      text-decoration: none;
      display: inline-block;
      padding: 12px 20px;
      border-radius: 6px;
      margin: 5px;
      font-weight: bold;
    }
    .get-it {
      background: #007bff;
      color: #fff;
    }
    .learn-more {
      background: #fff;
      color: #000;
    }
  </style>
</head>
<body>

  <!-- Testimonials Section -->
  <section class="section">
    <p style="text-align:center; color:#999;">Testimonials</p>
    <h1>What Our Customers Say</h1>
    <p style="text-align:center; color:#bbb;">Hear from our incredible customers who are building at lightning speed.</p>
    
    <div class="testimonials">
      <!-- Card 1 -->
      <div class="card">
        <div class="stars">★★★★★</div>
        <p>UI Blox has revolutionized my design process: its intuitive interface and robust features save me so much time, allowing me to focus on creativity rather than tedious tasks. It’s like having an extra pair of hands!</p>
        <div class="user-info">
          <img src="https://a.storyblok.com/f/191576/1200x800/215e59568f/round_profil_picture_after_.webp" alt="">
          <div>
            <strong>Jillie Bernard</strong><br>
            Founder & CEO
          </div>
        </div>
      </div>
      
      <!-- Card 2 -->
      <div class="card">
        <div class="stars">★★★★★</div>
        <p>UI Blox has revolutionized my design process. It's intuitive and saves me so much time!</p>
        <div class="user-info">
          <img src="https://tse1.mm.bing.net/th/id/OIP.UH4j7JKtLiian1hBzAx36wHaHa?cb=thfc1&w=2000&h=2000&rs=1&pid=ImgDetMain&o=7&rm=3" alt="">
          <div>
            <strong>Jillie Bernard</strong><br>
            Founder & CEO
          </div>
        </div>
      </div>
      
      <!-- Card 3 -->
      <div class="card">
        <div class="stars">★★★★★</div>
        <p>Absolutely love UI Blox! The clean design and ease of use are unmatched. The intuitive interface simplifies complex tasks, making it perfect for both beginners and seasoned professionals. A game-changer in digital design!</p>
        <div class="user-info">
          <img src="https://template.canva.com/EAFfzH4_h-A/1/0/800w-omEfevySsWY.jpg" alt="">
          <div>
            <strong>Jillie Bernard</strong><br>
            Founder & CEO
          </div>
        </div>
      </div>
      
      <!-- Add remaining cards as needed -->
    </div>
  </section>

  <!-- FAQ Section -->
  <section class="section faq-section">
    <p style="text-align:center; color:#999;">FAQ</p>
    <h2>Frequently Asked Questions</h2><p style="text-align:center; color:#bbb;">If you have any other questions, please email us.</p>
    <a class="contact-btn" href="#">Contact us</a>
    <div class="faq-list">
      <div class="faq-item"><h4>What is Framer?</h4></div>
      <div class="faq-item"><h4>Is it easy to learn?</h4></div>
      <div class="faq-item"><h4>Do I need to code?</h4></div>
    </div>
  </section>

  <!-- Bottom CTA Section -->
  <section class="section bottom-section">
    <h2>Build and Ship Your Website Faster</h2>
    <p>Speed up your website build with our ultimate UI kits for Framer. Enjoy high-quality, customizable elements for a seamless, stunning user experience.</p>
    <div class="cta-buttons">
      <a href="#" class="get-it">Get it now</a>
      <a href="#" class="learn-more">Learn more</a>
    </div>
  </section>

</body>
</html>
