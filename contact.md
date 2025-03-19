---
layout: default
title: Contact
permalink: /contact/
---

<div class="magazine-layout">
  <div class="full-width">
    <h1 class="article-heading fade-in">Get in Touch</h1>
    <p class="article-lead fade-in">Let's collaborate on projects that blend technology with thoughtful design</p>
  </div>
</div>

<div class="magazine-layout">
  <div class="two-thirds fade-in-left">
    <div class="contact-form">
      <form action="https://formspree.io/f/xzzeddod" method="POST">
        <div class="form-group">
          <label for="name">Name</label>
          <input type="text" id="name" name="name" required placeholder="Your name">
        </div>
        
        <div class="form-group">
          <label for="email">Email</label>
          <input type="email" id="email" name="_replyto" required placeholder="Your email address">
        </div>
        
        <div class="form-group">
          <label for="subject">Subject</label>
          <input type="text" id="subject" name="subject" required placeholder="Message subject">
        </div>
        
        <div class="form-group">
          <label for="message">Message</label>
          <textarea id="message" name="message" rows="6" required placeholder="Your message here..."></textarea>
        </div>
        
        <input type="text" name="_gotcha" style="display:none">
        
        <input type="hidden" name="_next" value="{{ site.url }}{{ site.baseurl }}/thank-you">
        
        <button type="submit" class="submit-btn">Send Message</button>
      </form>
    </div>
  </div>
  
  <div class="one-third fade-in-right">
    <div class="contact-info">
      <h2>Contact Information</h2>
      
      <div class="contact-item">
        <i class="fas fa-envelope" style="color: white;"></i>
        <div class="contact-detail">
          <h3>Email</h3>
          <p><a href="mailto:your.email@example.com">12212108@mail.sustech.edu.cn</a></p>
        </div>
      </div>
      
      <div class="contact-item">
        <i class="fas fa-phone" style="color: white;"></i>
        <div class="contact-detail">
          <h3>Phone</h3>
          <p>+61 466658703</p>
        </div>
      </div>
      
      <!-- <div class="contact-item">
        <i class="fab fa-linkedin" style="color: white;"></i>
        <div class="contact-detail">
          <h3>LinkedIn</h3>
          <p><a href="https://linkedin.com/in/yourname" target="_blank">linkedin.com/in/yourname</a></p>
        </div>
      </div>
      
      <div class="contact-item">
        <i class="fab fa-github" style="color: white;"></i>
        <div class="contact-detail">
          <h3>GitHub</h3>
          <p><a href="https://github.com/yourusername" target="_blank">github.com/yourusername</a></p>
        </div>
      </div>
    </div> -->
    
    <!-- <div class="availability">
      <h3>Currently Available For</h3>
      <ul>
        <li>UI/UX Design Projects</li>
        <li>Web Development</li>
        <li>Design System Creation</li>
        <li>Editorial Design Consultation</li>
      </ul>
    </div> -->
  </div>
</div>

<style>
  .contact-form {
    background-color: #111;
    padding: 30px;
    border-left: 4px solid var(--secondary-color);
  }
  
  .form-group {
    margin-bottom: 20px;
  }
  
  .form-group label {
    display: block;
    margin-bottom: 5px;
    font-weight: 600;
    color: var(--light-text);
  }
  
  .form-group input, 
  .form-group textarea {
    width: 100%;
    padding: 12px;
    border: 1px solid #444;
    background-color: #1a1a1a;
    color: white;
    font-family: var(--serif-font);
    font-size: 16px;
    border-radius: 3px;
  }
  
  .form-group input::placeholder,
  .form-group textarea::placeholder {
    color: #666;
  }
  
  .form-group input:focus,
  .form-group textarea:focus {
    outline: none;
    border-color: var(--secondary-color);
    box-shadow: 0 0 5px rgba(211, 47, 47, 0.5);
  }
  
  .submit-btn {
    background-color: var(--secondary-color);
    color: white;
    border: none;
    padding: 12px 25px;
    font-size: 16px;
    font-weight: 600;
    cursor: pointer;
    font-family: var(--serif-font);
    transition: background-color 0.3s;
    border-radius: 3px;
  }
  
  .submit-btn:hover {
    background-color: var(--accent-color);
  }
  
  .contact-info {
    background-color: #111;
    padding: 30px;
    margin-bottom: 30px;
    border: 1px solid #333;
  }
  
  .contact-item {
    display: flex;
    margin-bottom: 20px;
    align-items: flex-start;
  }
  
  .contact-item i {
    font-size: 24px;
    color: var(--secondary-color);
    margin-right: 15px;
    margin-top: 3px;
  }
  
  .contact-detail h3 {
    margin: 0 0 5px 0;
    font-size: 18px;
  }
  
  .contact-detail p {
    margin: 0;
    color: #bbb;
  }
  
  .contact-detail a {
    color: #bbb;
    text-decoration: none;
    border-bottom: 1px solid var(--secondary-color);
    transition: color 0.3s;
  }
  
  .contact-detail a:hover {
    color: var(--secondary-color);
  }
  
  .availability {
    background-color: var(--dark-bg);
    color: var(--light-text);
    padding: 25px;
    border: 1px solid #333;
  }
  
  .availability h3 {
    margin-top: 0;
    color: var(--light-text);
    border-bottom: 2px solid var(--secondary-color);
    padding-bottom: 10px;
    display: inline-block;
  }
  
  .availability ul {
    margin: 0;
    padding-left: 20px;
    color: #bbb;
  }
  
  .availability li {
    margin-bottom: 8px;
  }
</style> 