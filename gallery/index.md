---
layout: page
title: Gallery
---

# Gallery

<script>
lightbox.option({
  'resizeDuration': 200,
  'wrapAround': true,
  'fadeDuration': 200,
  'imageFadeDuration': 200,
  'alwaysShowNavOnTouchDevices': true,
  'previousImage': '/files/images/prev.png',
  'nextImage': '/files/images/next.png'
});
</script>

<style>
/* Override the previous button */
.lb-prev {
  background: url('/files/images/prev.png') no-repeat center center;
  background-size: contain;
}

/* Override the next button */
.lb-next {
  background: url('/files/images/next.png') no-repeat center center;
  background-size: contain;
}
</style>

<div style="display: flex; flex-wrap: wrap; gap: 10px; justify-content: space-between;">
  <a href="/files/images/yrsr_qml.jpg" data-lightbox="gallery" data-title="" style="width: 24%;">
    <img src="/files/images/yrsr_qml.jpg" loading="lazy" alt="" style="width: 100%; height: auto;" />
  </a>
  <a href="/files/images/yrsr_tth.jpg" data-lightbox="gallery" data-title="" style="width: 24%;">
    <img src="/files/images/yrsr_tth.jpg" loading="lazy" alt="" style="width: 100%; height: auto;" />
  </a>
  <a href="/files/images/fhs_rts.jpg" data-lightbox="gallery" data-title="" style="width: 24%;">
    <img src="/files/images/fhs_rts.jpg" loading="lazy" alt="" style="width: 100%; height: auto;" />
  </a>
  <a href="/files/images/fhs_bubble.jpg" data-lightbox="gallery" data-title="" style="width: 24%;">
    <img src="/files/images/fhs_bubble.jpg" loading="lazy" alt="" style="width: 100%; height: auto;" />
  </a>
  <!-- Continue as needed -->
</div>