---
layout: page
title: Map
permalink: /map/
---

<div id='map'></div>
<script>
mapboxgl.accessToken = 'pk.eyJ1IjoidGVtcGVzdGEiLCJhIjoiRlJYSUFySSJ9.TQBYUVacKdHs_GcwuWWUgg';
const map = new mapboxgl.Map({
  container: 'map',
  style: 'mapbox://styles/tempesta/cj70bhriz28d42sqfmk75jvd8',
  center: [12.578289, 41.940479],
  zoom: 8.5
});
</script>
 <script src='https://api.tiles.mapbox.com/mapbox-gl-js/v0.53.0/mapbox-gl.js'></script>
