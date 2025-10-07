---
description: Vous trouverez ici le code pénal de la ville .
---

# 🔨 Code Pénal



### 🚗 Délit Routier

<img src="/assets/image_2023-11-08_220515481.png" alt="Délit Routier" class="lightbox" onclick="openLightbox(this.src, this.alt)">
*� Cliquez sur l'image pour l'agrandir*

### 📋 Délit Catégorie I

<img src="/assets/image_2023-11-08_220601239.png" alt="Délit Catégorie I" class="lightbox" onclick="openLightbox(this.src, this.alt)">
*� Cliquez sur l'image pour l'agrandir*

### 📋 Délit Catégorie II

<img src="/assets/image_2023-11-08_220654863.png" alt="Délit Catégorie II" class="lightbox" onclick="openLightbox(this.src, this.alt)">
*� Cliquez sur l'image pour l'agrandir*

### 📋 Délit Catégorie III

<img src="/assets/image_2023-11-08_220746218.png" alt="Délit Catégorie III" class="lightbox" onclick="openLightbox(this.src, this.alt)">
*� Cliquez sur l'image pour l'agrandir*

### ⚖️ Crimes

<img src="/assets/image_2023-11-08_220833757.png" alt="Crimes" class="lightbox" onclick="openLightbox(this.src, this.alt)">
*🔍 Cliquez sur l'image pour l'agrandir*

<!-- Lightbox Overlay -->
<div id="lightbox-overlay" class="lightbox-overlay" onclick="closeLightbox()">
  <span class="lightbox-close" onclick="closeLightbox()">&times;</span>
  <img id="lightbox-image" class="lightbox-image" src="" alt="">
</div>

<script>
function openLightbox(src, alt) {
  document.getElementById('lightbox-overlay').classList.add('active');
  document.getElementById('lightbox-image').src = src;
  document.getElementById('lightbox-image').alt = alt;
  document.body.style.overflow = 'hidden';
}

function closeLightbox() {
  document.getElementById('lightbox-overlay').classList.remove('active');
  document.body.style.overflow = 'auto';
}

// Fermer avec Echap
document.addEventListener('keydown', function(e) {
  if (e.key === 'Escape') {
    closeLightbox();
  }
});
</script>
