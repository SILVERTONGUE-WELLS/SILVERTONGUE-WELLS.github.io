---
layout: default
title: Portfolio
---

<div class="magazine-layout">
  <div class="full-width">
    <h1 class="article-heading fade-in">Portfolio</h1>
    <p class="article-lead fade-in">A showcase of my projects in systems programming, machine learning, and distributed computing</p>
  </div>
</div>

<div class="magazine-layout">
  <div class="two-thirds fade-in-left">
    <div class="feature-article">
      <h2>rCore Operating System</h2>
      <img src="{{ site.baseurl }}/assets/images/os.jpg" alt="Operating System Development" class="featured-image">
      <p class="caption">A microkernel operating system implemented in Rust</p>
      
      <div class="article-columns">
        <p><span class="dropcap">I</span> developed a microkernel operating system based on the rCore architecture, implementing key OS components including memory management, process scheduling, file systems, and device drivers in Rust. This project required deep understanding of both low-level system architecture and Rust's safety guarantees.</p>
        
        <p>The implementation features a virtual memory system with page tables, a preemptive scheduler, a simplified Unix-like file system, and basic device drivers. The project demonstrates how memory-safe languages like Rust can be used for systems programming while maintaining performance comparable to C implementations.</p>
      </div>
      
      <div class="pull-quote">
        "Building a modern OS in Rust allowed me to explore how language-level safety can address traditional systems programming challenges."
      </div>
    </div>
  </div>
  
  <div class="one-third fade-in-right">
    <div class="feature-article">
      <h3>Technologies Used</h3>
      <ul>
        <li>Rust Programming Language</li>
        <li>RISC-V Architecture</li>
        <li>Assembly Programming</li>
        <li>Memory Management</li>
        <li>Interrupt Handling</li>
        <li>Process Scheduling</li>
      </ul>
      
      <h3>Key Features</h3>
      <ul>
        <li>Virtual memory system</li>
        <li>Preemptive scheduler</li>
        <li>Unix-like file system</li>
        <li>Device drivers</li>
        <li>Memory-safe implementation</li>
      </ul>
    </div>
  </div>
</div>

<div class="magazine-layout">
  <div class="half fade-in-up">
    <div class="feature-article">
      <h2>Federated Learning Framework</h2>
      <img src="{{ site.baseurl }}/assets/images/ml.jpg" alt="Federated Learning System" class="featured-image">
      <p>A distributed machine learning system that enables collaborative model training while preserving data privacy. The framework implements secure aggregation protocols and differential privacy techniques to protect sensitive information during the training process.</p>
      
      <a href="#" class="btn">View Project</a>
    </div>
  </div>
  
  <div class="half fade-in-up" style="animation-delay: 0.3s;">
    <div class="feature-article">
      <h2>P2P Video Conferencing System</h2>
      <img src="{{ site.baseurl }}/assets/images/video.jpg" alt="Video Conferencing System" class="featured-image">
      <p>A peer-to-peer video conferencing solution built from scratch with WebRTC. This project implements efficient video and audio transmission with dynamic quality adjustment, end-to-end encryption, and a distributed room management system without relying on centralized servers.</p>
      
      <a href="#" class="btn">View Project</a>
    </div>
  </div>
</div>

<div class="magazine-layout">
  <div class="full-width fade-in">
    <h2>Research Projects</h2>
  </div>
  
  <div class="half fade-in-up">
    <div class="feature-article">
      <h3>Multimodal Alignment in Large Models</h3>
      <p>Research focusing on improving alignment between different modalities (text, images, audio) in large multimodal models. Developed novel techniques for more efficient cross-modal representation learning and transfer.</p>
      <ul>
        <li>Implemented contrastive learning approaches</li>
        <li>Reduced computational requirements by 35%</li>
        <li>Improved cross-modal retrieval performance</li>
        <li>Developed specialized evaluation metrics</li>
      </ul>
    </div>
  </div>
  
  <div class="half fade-in-up" style="animation-delay: 0.3s;">
    <div class="feature-article">
      <h3>Efficient Systems for Machine Learning</h3>
      <p>Designed and implemented systems optimizations for machine learning workloads, focusing on inference acceleration and training pipeline efficiency.</p>
      <ul>
        <li>Kernel fusion techniques for GPU computation</li>
        <li>Memory optimization for large model training</li>
        <li>Distributed training coordination systems</li>
        <li>Model compression and quantization</li>
      </ul>
    </div>
  </div>
</div>

<style>
  .btn {
    display: inline-block;
    background-color: var(--secondary-color);
    color: white;
    padding: 10px 20px;
    text-decoration: none;
    font-weight: 600;
    margin-top: 15px;
    transition: background-color 0.3s;
  }
  
  .btn:hover {
    background-color: var(--accent-color);
  }
</style> 