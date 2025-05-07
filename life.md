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
  overflow-x: auto;
  scroll-behavior: smooth;
  padding: 10px 0;
}
.carousel::-webkit-scrollbar {
  display: none;
}

.carousel-item {
  flex: 0 0 300px;
  height: 200px;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 4px 12px rgba(0,0,0,0.15);
}
.carousel-item img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
}

/* 更现代的按钮样式 */
.carousel-btn {
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  background: #ffffff;
  border: none;
  color: #333;
  font-size: 28px;
  width: 45px;
  height: 45px;
  border-radius: 50%;
  box-shadow: 0 4px 8px rgba(0,0,0,0.25);
  cursor: pointer;
  transition: background 0.3s, transform 0.2s;
  display: flex;
  align-items: center;
  justify-content: center;
  z-index: 10;
}
.carousel-btn:hover {
  background: #f2f2f2;
  transform: translateY(-50%) scale(1.1);
}
.carousel-btn.prev { left: 10px; }
.carousel-btn.next { right: 10px; }
</style>

<div class="carousel-wrapper">
  <button class="carousel-btn prev" id="btnPrev">&#10094;</button>
  <div class="carousel" id="imageCarousel">
    <div class="carousel-item"><img src="../img/trip/1.jpg" alt="Travel 1"></div>
    <div class="carousel-item"><img src="../img/trip/2.jpg" alt="Travel 2"></div>
    <div class="carousel-item"><img src="../img/trip/3.jpg" alt="Travel 3"></div>
    <div class="carousel-item"><img src="../img/trip/4.jpg" alt="Travel 4"></div>
    <div class="carousel-item"><img src="../img/trip/5.jpg" alt="Travel 5"></div>
    <div class="carousel-item"><img src="../img/trip/6.jpg" alt="Travel 6"></div>
    <div class="carousel-item"><img src="../img/trip/7.jpg" alt="Travel 7"></div>
  </div>
  <button class="carousel-btn next" id="btnNext">&#10095;</button>
</div>

<script>
document.addEventListener("DOMContentLoaded", function () {
  const carousel = document.getElementById('imageCarousel');
  const scrollAmount = 320;

  document.getElementById('btnPrev').addEventListener('click', () => {
    carousel.scrollBy({ left: -scrollAmount, behavior: 'smooth' });
  });

  document.getElementById('btnNext').addEventListener('click', () => {
    carousel.scrollBy({ left: scrollAmount, behavior: 'smooth' });
  });
});
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
