---
layout: page
title: Leisure Life
subtitle: 
---
## Game
- <img src="/img/unity.png" alt="Unity" style="height: 20px; vertical-align: middle;"> Game Developer (Unity)
- <img src="/img/steam.png" alt="Steam" style="height: 20px; vertical-align: middle;"> Steam
- <img src="/img/nintendo-switch.png" alt="Switch" style="height: 20px; vertical-align: middle;"> Switch
- <img src="/img/ps.png" alt="Play Station" style="height: 20px; vertical-align: middle;"> Play Station
- <img src="/img/epic.png" alt="EPIC" style="height: 20px; vertical-align: middle;"> EPIC


## Live
- <img src="/img/obs-studio.png" alt="OBS" style="height: 20px; vertical-align: middle;"> OBS
- <img src="/img/studio-one.png" alt="Studio One" style="height: 20px; vertical-align: middle;"> Studio One
- <img src="/img/audio-interface.png" alt="Audio Interface" style="height: 20px; vertical-align: middle;"> Audio Interface

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
    <div class="carousel-item"><img src="/img/trip/1.jpg" alt="Travel 1"></div>
    <div class="carousel-item"><img src="/img/trip/2.jpg" alt="Travel 2"></div>
    <div class="carousel-item"><img src="/img/trip/3.jpg" alt="Travel 3"></div>
    <div class="carousel-item"><img src="/img/trip/4.jpg" alt="Travel 4"></div>
    <div class="carousel-item"><img src="/img/trip/5.jpg" alt="Travel 5"></div>
    <div class="carousel-item"><img src="/img/trip/6.jpg" alt="Travel 6"></div>
    <div class="carousel-item"><img src="/img/trip/7.jpg" alt="Travel 7"></div>
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
  { name: "West New York, NJ", coords: [40.7879, -74.0143] },
  { name: "Montauk, NY", coords: [41.0359, -71.9545] },
  { name: "Manhattan, NY", coords: [40.7831, -73.9712] },
  { name: "Brooklyn, NY", coords: [40.6782, -73.9442] },
  { name: "Atlantic City, NJ", coords: [39.3643, -74.4229] },
  { name: "Cape May, NJ", coords: [38.9351, -74.9060] },
  { name: "Vermont", coords: [44.5588, -72.5778] },
  { name: "Buffalo, NY", coords: [42.8864, -78.8784] },
  { name: "Toronto, Canada", coords: [43.651070, -79.347015] },
  { name: "Rainbow Bridge", coords: [43.0896, -79.0704] },
  { name: "Niagara Falls", coords: [43.0962, -79.0377] },
  { name: "Charlotte, NC", coords: [35.2271, -80.8431] },
  { name: "Great Smoky Mountains", coords: [35.6532, -83.5070] },
  { name: "Atlanta, GA", coords: [33.7490, -84.3880] },
  { name: "Chattanooga, TN", coords: [35.0456, -85.3097] },
  { name: "Vanderbilt University, TN", coords: [36.1465, -86.8039] },
  { name: "Nashville, TN", coords: [36.1627, -86.7816] },
  { name: "Chicago, IL", coords: [41.8781, -87.6298] },
  { name: "Champaign, IL", coords: [40.1164, -88.2434] },
  { name: "San Francisco, CA", coords: [37.7749, -122.4194] },
  { name: "Portland, OR", coords: [45.5051, -122.6750] },
  { name: "Seattle, WA", coords: [47.6062, -122.3321] },
  { name: "Osaka, Japan", coords: [34.6937, 135.5023] },
  { name: "Nara, Japan", coords: [34.6851, 135.8048] },
  { name: "Tokyo, Japan", coords: [35.6762, 139.6503] },
  { name: "Seoul, South Korea", coords: [37.5665, 126.9780] },
  { name: "Wuxi, China", coords: [31.4912, 120.3119] },
  { name: "Qingdao, China", coords: [36.0671, 120.3826] },
  { name: "Suzhou, China", coords: [31.2989, 120.5853] },
  { name: "Hangzhou, China", coords: [30.2741, 120.1551] },
  { name: "Nanxun, China", coords: [30.8729, 120.4205] },
  { name: "Shanghai, China", coords: [31.2304, 121.4737] },
  { name: "Nanjing, China", coords: [32.0603, 118.7969] },
  { name: "Wuyishan, China", coords: [27.5485, 118.0364] },
  { name: "Macau", coords: [22.1987, 113.5439] },
  { name: "Hong Kong", coords: [22.3193, 114.1694] },
  { name: "Guangzhou, China", coords: [23.1291, 113.2644] },
  { name: "Zhuhai, China", coords: [22.2760, 113.5675] },
  { name: "Zhangzhou, China", coords: [24.5132, 117.6556] },
  { name: "Xiamen, China", coords: [24.4798, 118.0894] },
  { name: "Chongqing, China", coords: [29.5630, 106.5516] },
  { name: "Sichuan, China", coords: [30.6517, 104.0759] },
  { name: "Xi'an, China", coords: [34.3416, 108.9398] },
  { name: "Beijing, China", coords: [39.9042, 116.4074] },
  { name: "Changchun, China", coords: [43.8171, 125.3235] },
  { name: "Dalian, China", coords: [38.9140, 121.6147] },
  { name: "Yanji, China", coords: [42.9156, 129.5127] },
  { name: "Malaysia", coords: [3.1390, 101.6869] },
  { name: "Thailand", coords: [13.7563, 100.5018] },
  { name: "Singapore", coords: [1.3521, 103.8198] },
  { name: "Dubai, UAE", coords: [25.2048, 55.2708] },
  { name: "Rome, Italy", coords: [41.9028, 12.4964] },
  { name: "Florence, Italy", coords: [43.7696, 11.2558] },
  { name: "Venice, Italy", coords: [45.4408, 12.3155] },
  { name: "Brescia, Italy", coords: [45.5416, 10.2118] },
  { name: "Milan, Italy", coords: [45.4642, 9.1900] },
  { name: "Domodossola, Italy", coords: [46.1141, 8.2958] },
  { name: "Zurich, Switzerland", coords: [47.3769, 8.5417] }
];


places.forEach(function(place) {
  L.marker(place.coords).addTo(map)
    .bindPopup(`<b>${place.name}</b>`);
});

</script>
