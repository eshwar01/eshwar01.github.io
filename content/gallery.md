---
title: Photo Gallery
---

<style>
.gallery-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
    gap: 20px;
    margin-top: 2rem;
}

.gallery-item {
    position: relative;
    overflow: hidden;
    border-radius: 8px;
}

.gallery-item img {
    width: 100%;
    height: auto;
    transition: transform 0.3s ease;
}

.gallery-item:hover img {
    transform: scale(1.05);
}
</style>

<div class="gallery-grid">
     <div class="gallery-item">
        <a href="/images/DSC_0250.jpg" data-fancybox="gallery">
            <img src="/images/DSC_0250.jpg" alt="Description of image 1">
        </a>
    </div>
    
   <div class="gallery-item">
        <a href="/images/DSC_1089.jpg" data-fancybox="gallery">
            <img src="/images/DSC_1089.jpg" alt="Description of image 2">
        </a>
    </div>
    
</div>