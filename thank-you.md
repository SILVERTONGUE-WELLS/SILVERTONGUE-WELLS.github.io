---
layout: default
title: Thank You
---

<div class="magazine-layout">
  <div class="full-width thank-you-container fade-in">
    <h1 class="article-heading">Thank You</h1>
    <div class="thank-you-content">
      <div class="thank-you-icon">
        <i class="fas fa-check-circle"></i>
      </div>
      <p class="thank-you-message">Your message has been sent successfully!</p>
      <p>Thank you for getting in touch. I'll respond to your message as soon as possible.</p>
      <a href="{{ site.baseurl }}/" class="back-home-btn">Return to Home Page</a>
    </div>
  </div>
</div>

<style>
  .thank-you-container {
    text-align: center;
    padding: 50px 20px;
    background-color: #111;
    border: 1px solid #333;
    border-radius: 5px;
    margin: 50px 0;
  }
  
  .thank-you-content {
    max-width: 600px;
    margin: 0 auto;
  }
  
  .thank-you-icon {
    font-size: 80px;
    color: var(--secondary-color);
    margin-bottom: 30px;
    animation: scaleIn 0.5s ease-out;
  }
  
  .thank-you-message {
    font-size: 24px;
    font-weight: 600;
    margin-bottom: 20px;
    color: var(--light-text);
  }
  
  .back-home-btn {
    display: inline-block;
    background-color: var(--secondary-color);
    color: white;
    text-decoration: none;
    padding: 12px 25px;
    margin-top: 30px;
    font-weight: 600;
    border-radius: 3px;
    transition: background-color 0.3s;
  }
  
  .back-home-btn:hover {
    background-color: var(--accent-color);
    color: white;
  }
  
  @keyframes scaleIn {
    0% {
      transform: scale(0);
      opacity: 0;
    }
    80% {
      transform: scale(1.2);
      opacity: 1;
    }
    100% {
      transform: scale(1);
    }
  }
</style> 