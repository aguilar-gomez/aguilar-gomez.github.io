---
title: projects 
layout: post
permalink: /projects/
---

#### **Ongoing projects**
<style>
  .image-hover-container {
    position: relative;
    display: inline-block;
    border-radius: 50%;
    overflow: hidden;
    width: 100%;
    height: auto;
  }

  .image-hover-container img {
    transition: all 0.3s ease-in-out;
    width: 100%;
    height: auto;
    border-radius: 50%;
  }

  .image-hover-container:hover img {
    filter: blur(3px);
  }

  .hover-text {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: white;
    font-size: 20px;
    font-weight: bold;
    opacity: 0;
    transition: opacity 0.3s ease-in-out;
  }

  .image-hover-container:hover .hover-text {
    opacity: 1;
  }

  .image-gallery {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
  }

  .image-gallery a {
    flex: 1 1 calc(33.333% - 20px); /* Three columns with some space between */
    margin: 10px;
    box-sizing: border-box;
  }

  @media (max-width: 768px) {
    .image-gallery a {
      flex: 1 1 100%; /* Single column on smaller screens */
      margin: 10px 0;
    }
  }
</style>

<div style="display: flex; justify-content: space-between;">
  <a href="https://aguilar-gomez.github.io/whales/">
    <div class="image-hover-container">
      <img src="/figures/RicesWhaleCircle.png" alt="Rice's whale drawing">
      <div class="hover-text">Understanding the demography of the critically endangered Rice's whale</div>
    </div>
  </a>
  <a href="https://aguilar-gomez.github.io/pumas/">
    <div class="image-hover-container">
      <img src="/figures/greenPuma.png" alt="Dalle generated puma">
      <div class="hover-text">Evaluating the genomic rescue in Florida Panthers</div>
    </div>
  </a>
  <a href="https://aguilar-gomez.github.io/haenyeo/">
    <div class="image-hover-container">
      <img src="/figures/haenyeoCircle.png" alt="Haenyeo">
      <div class="hover-text">Genomic adaptation to free diving in the Haenyeo</div>
    </div>
  </a>
</div>


#### **Previous projects**

<div style="display: flex; justify-content: space-between;">
  <a href="https://aguilar-gomez.github.io/pumilio/">
  <div class="image-hover-container">
    <img src="/figures/pumilioCircle.png" alt="Solarte Oophaga pumilio">
      <div class="hover-text">Color genomics of the strawberry poison frog in Bocas del Toro</div>
    </div>
  </a> 
  <a href="https://aguilar-gomez.github.io/phrynocephalus/">
<div class="image-hover-container">
 <img src="/figures/lizarddrawingCircle.png" alt="ying yang lizard">
  <div class="hover-text">Lizard adaptation genomics</div>
    </div>
  </a>
  <a href="https://aguilar-gomez.github.io/basiliscus/">
    <div class="image-hover-container">
   <img src="/figures/Basiliscus5_machoDCircle.png" alt="Basiliscus">
    <div class="hover-text">Evolution of sex chromosomes</div>
    </div>
  </a>
</div>


<div style="display: flex; justify-content: space-between;">
<a href="https://aguilar-gomez.github.io/microfluidics/">
    <div class="image-hover-container">
   <img src="/figures/microfluidicsCircle.png" alt="Microfluidics"> 
   <div class="hover-text">Microfluidics and transcriptional memory in yeast</div>
    </div>
</a>
  <a href="https://aguilar-gomez.github.io/microfluidics/">
    <div class="image-hover-container">
   <img src="/figures/microfluidicsCircle.png" alt="Microfluidics"> 
   <div class="hover-text">Microfluidics and transcriptional memory in yeast</div>
    </div>
</a>
  <a href="https://aguilar-gomez.github.io/microfluidics/">
    <div class="image-hover-container">
   <img src="/figures/microfluidicsCircle.png" alt="Microfluidics"> 
   <div class="hover-text">Microfluidics and transcriptional memory in yeast</div>
    </div>
</a>
</div>




[jekyll-organization]: https://github.com/jekyll
