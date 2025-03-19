---
layout: default
title: Blog
permalink: /blog/
---

<div class="magazine-layout">
  <div class="full-width">
    <h1 class="article-heading fade-in">Blog</h1>
    <p class="article-lead fade-in">Thoughts on design, technology, and the intersection of both worlds</p>
  </div>
</div>

<div class="magazine-layout">
  <div class="two-thirds">
    <article class="blog-post fade-in-up">
      <div class="post-meta">June 15, 2023 • Design</div>
      <h2>The Enduring Influence of Print Design in Digital Media</h2>
      <img src="https://source.unsplash.com/random/1000x600/?newspaper" alt="Print Design" class="featured-image">
      <p><span class="dropcap">W</span>hile digital media has transformed how we consume content, the principles of print design continue to influence digital interfaces. From grid systems to typographic hierarchies, the lessons learned from centuries of print design remain relevant in our digital age.</p>
      <p>This post explores how concepts from The New York Times, Rolling Stone, and other iconic print publications can be adapted for the web...</p>
      <a href="#" class="read-more">Continue Reading →</a>
    </article>
    
    <article class="blog-post fade-in-up" style="animation-delay: 0.2s;">
      <div class="post-meta">May 28, 2023 • Technology</div>
      <h2>The Art of Typography in User Interface Design</h2>
      <img src="https://source.unsplash.com/random/1000x600/?typography" alt="Typography" class="featured-image">
      <p>Typography is often the unsung hero of user interface design. The right typeface can establish mood, improve readability, and create visual hierarchy. This post examines how careful type selection and layout can transform a digital interface...</p>
      <a href="#" class="read-more">Continue Reading →</a>
    </article>
    
    <article class="blog-post fade-in-up" style="animation-delay: 0.4s;">
      <div class="post-meta">April 12, 2023 • Development</div>
      <h2>Building CSS Grid Layouts Inspired by Magazine Design</h2>
      <img src="https://source.unsplash.com/random/1000x600/?grid" alt="CSS Grid" class="featured-image">
      <p>CSS Grid has revolutionized web layout, enabling designers to create complex arrangements that were previously difficult to implement. This tutorial shows how to build magazine-inspired layouts using CSS Grid...</p>
      <a href="#" class="read-more">Continue Reading →</a>
    </article>
  </div>
  
  <div class="one-third">
    <div class="sidebar fade-in-right">
      <div class="sidebar-section">
        <h3>Categories</h3>
        <ul class="category-list">
          <li><a href="#">Design <span>(12)</span></a></li>
          <li><a href="#">Technology <span>(8)</span></a></li>
          <li><a href="#">Development <span>(15)</span></a></li>
          <li><a href="#">Typography <span>(6)</span></a></li>
          <li><a href="#">User Experience <span>(9)</span></a></li>
        </ul>
      </div>
      
      <div class="sidebar-section">
        <h3>Recent Posts</h3>
        <ul class="recent-posts">
          <li>
            <a href="#">The Enduring Influence of Print Design in Digital Media</a>
            <span class="post-date">June 15, 2023</span>
          </li>
          <li>
            <a href="#">The Art of Typography in User Interface Design</a>
            <span class="post-date">May 28, 2023</span>
          </li>
          <li>
            <a href="#">Building CSS Grid Layouts Inspired by Magazine Design</a>
            <span class="post-date">April 12, 2023</span>
          </li>
          <li>
            <a href="#">Color Theory for Digital Designers</a>
            <span class="post-date">March 5, 2023</span>
          </li>
        </ul>
      </div>
      
      <div class="sidebar-section">
        <h3>Subscribe</h3>
        <p>Get the latest posts delivered straight to your inbox.</p>
        <form class="subscribe-form">
          <input type="email" placeholder="Your email address" required>
          <button type="submit">Subscribe</button>
        </form>
      </div>
    </div>
  </div>
</div>

<style>
  .blog-post {
    margin-bottom: 60px;
    padding-bottom: 40px;
    border-bottom: 1px solid #eee;
  }
  
  .post-meta {
    font-style: italic;
    color: #666;
    margin-bottom: 10px;
  }
  
  .read-more {
    display: inline-block;
    color: var(--secondary-color);
    font-weight: 600;
    text-decoration: none;
    margin-top: 15px;
    transition: color 0.3s;
  }
  
  .read-more:hover {
    color: var(--accent-color);
  }
  
  .sidebar {
    position: sticky;
    top: 30px;
  }
  
  .sidebar-section {
    background-color: var(--light-bg);
    padding: 25px;
    margin-bottom: 30px;
  }
  
  .sidebar-section h3 {
    margin-top: 0;
    border-bottom: 2px solid var(--secondary-color);
    padding-bottom: 10px;
    display: inline-block;
  }
  
  .category-list {
    list-style: none;
    padding: 0;
    margin: 0;
  }
  
  .category-list li {
    margin-bottom: 10px;
  }
  
  .category-list a {
    color: var(--text-color);
    text-decoration: none;
    transition: color 0.3s;
    display: flex;
    justify-content: space-between;
  }
  
  .category-list a:hover {
    color: var(--secondary-color);
  }
  
  .recent-posts {
    list-style: none;
    padding: 0;
    margin: 0;
  }
  
  .recent-posts li {
    margin-bottom: 15px;
  }
  
  .recent-posts a {
    color: var(--text-color);
    text-decoration: none;
    font-weight: 600;
    display: block;
    transition: color 0.3s;
  }
  
  .recent-posts a:hover {
    color: var(--secondary-color);
  }
  
  .post-date {
    display: block;
    font-size: 14px;
    color: #666;
    font-style: italic;
    margin-top: 3px;
  }
  
  .subscribe-form {
    display: grid;
    grid-template-columns: 1fr;
    gap: 10px;
  }
  
  .subscribe-form input {
    padding: 10px;
    border: 1px solid #ddd;
    font-family: var(--serif-font);
  }
  
  .subscribe-form button {
    background-color: var(--secondary-color);
    color: white;
    border: none;
    padding: 10px;
    font-weight: 600;
    cursor: pointer;
    font-family: var(--serif-font);
    transition: background-color 0.3s;
  }
  
  .subscribe-form button:hover {
    background-color: var(--accent-color);
  }
</style> 