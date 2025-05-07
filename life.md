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

## Travel
<!-- Leaflet CSS & JS -->
<link rel="stylesheet" href="https://unpkg.com/leaflet/dist/leaflet.css" />
<script src="https://unpkg.com/leaflet/dist/leaflet.js"></script>

<!-- 地图容器 -->
<div id="travel-map" style="height: 480px; margin: 20px 0; border: 1px solid #ccc; border-radius: 8px;"></div>

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
