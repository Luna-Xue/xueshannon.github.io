---
layout: page
title: Leisure Life
subtitle: 
---
## Game
- Game Developer(Unity)

## Live
- OBS
- Studio One

## Photos
<style>
.carousel-wrapper {
  position: relative;
  width: 100%;
  overflow: hidden;
  margin: 20px 0;
}

.carousel {
  display: flex;
  gap: 1rem;
  transition: transform 0.3s ease-in-out;
  scroll-behavior: smooth;
}

.carousel-item {
  flex: 0 0 300px;
  height: 200px;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
}
.carousel-item img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
}

/* 美化箭头按钮 */
.carousel-btn {
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  background: linear-gradient(145deg, #ffffff, #e6e6e6);
  border: 1px solid #ccc;
  font-size: 20px;
  color: #333;
  padding: 10px 14px;
  cursor: pointer;
  border-radius: 50%;
  box-shadow: 0 2px 6px rgba(0,0,0,0.15);
  transition: all 0.2s ease;
  z-index: 10;
}
.carousel-btn:hover {
  background: linear-gradient(145deg, #f0f0f0, #dcdcdc);
  transform: translateY(-50%) scale(1.1);
}
.carousel-btn.prev {
  left: 10px;
}
.carousel-btn.next {
  right: 10px;
}
</style>

<div class="carousel-wrapper">
  <button class="carousel-btn prev" onclick="scrollCarousel(-1)">&#10094;</button>
  <div class="carousel" id="imageCarousel">
    <div class="carousel-item"><img src="img/travel1.jpg" alt="Travel 1"></div>
    <div class="carousel-item"><img src="img/travel2.jpg" alt="Travel 2"></div>
    <div class="carousel-item"><img src="img/travel3.jpg" alt="Travel 3"></div>
    <div class="carousel-item"><img src="img/travel4.jpg" alt="Travel 4"></div>
  </div>
  <button class="carousel-btn next" onclick="scrollCarousel(1)">&#10095;</button>
</div>

<script>
function scrollCarousel(direction) {
  const carousel = document.getElementById('imageCarousel');
  const scrollAmount = 320; // adjust depending on item width + gap
  carousel.scrollBy({
    left: direction * scrollAmount,
    behavior: 'smooth'
  });
}
</script>



## Travel
<!-- Leaflet CSS & JS -->
<link rel="stylesheet" href="https://unpkg.com/leaflet/dist/leaflet.css" />
<script src="https://unpkg.com/leaflet/dist/leaflet.js"></script>

<!-- 地图容器 -->
<div id="travel-map" style="height: 300px; margin: 20px 0; border: 1px solid #ccc; border-radius: 8px;"></div>

<script>
// 初始化地图并设置中心点和缩放等级
var map = L.map('travel-map').setView([20.0, 0.0], 2);

// 加载 OpenStreetMap 图层
L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
  attribution: 'Map data © <a href="https://openstreetmap.org">OpenStreetMap</a> contributors'
}).addTo(map);

// 添加旅游足迹标记点
var places = [
  { name: "New York, USA", coords: [40.7128, -74.0060] },
  { name: "Tokyo, Japan", coords: [35.6762, 139.6503] },
  { name: "Paris, France", coords: [48.8566, 2.3522] },
  { name: "Honolulu, Hawaii", coords: [21.3069, -157.8583] }
];

places.forEach(function(place) {
  L.marker(place.coords).addTo(map)
    .bindPopup(`<b>${place.name}</b>`);
});
</script>
