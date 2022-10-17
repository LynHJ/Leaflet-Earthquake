# Leaflet-Earthquake

![alt text](https://github.com/LynHJ/Leaflet-Earthquake/blob/41ad2b471423ed159e5653eab041018f3bf8e4c9/Image/usgs.png)
## Background

The Earth is our home, which generates a magnetic field as a shield against the impacts from Cosmic rays and the solar wind. The power of the magnetic field comes from the mixture of molten iron and nickel in Earth's outer core. There are 14 tectonic plates on the surface of the Earth. Their moving directions not only depend on the conditions of each plate but the magmatic flow which is under these plates. As to generate enough power to create the magnetic field, we can imagine that the strong magmatic flow produces these plates' relative movement and then causes earthquakes.  
 
The porpose of this project is trying to plot earthquakes by using geojson files sourced from https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php, leaflet for creating layers to visualize the locations of earthquakes. The project has two scripts in two folders, one is displaying a layer which shows where the earthquakes happened in the past 30 days and another one is displaying an extra layer of tectonic plates data. Both are based on two basic layers(street layers and topo layer).  


## Web Page:  
<img src='https://github.com/LynHJ/Leaflet-Earthquake/blob/41ad2b471423ed159e5653eab041018f3bf8e4c9/Image/Image.png' width = 80% class="center" >  

##### Summary: 

From the picture above, we notice that the locations of earthquakes are on the junctions of each plate or near that. The reason is that there are three types of plate boundaries(collide with, move away from, slide past). For example, in the area of the State of Alaska, most earthquakes happened on the North American plate. It means the Pacific plate subducts into the North American plate. Furthermore, We can also find out some earthquakes happened in the middle of tectonic plates. I have to read more research on it as the movements of tectonic plates is just one of the reasons for earthquakes.  
## Content:
```
Project  
├── Image
│   ├── Image.png
│   └── usgs.png
├── InputData
│   └── PB2002_boundaries.json
├── Leaflet-Earthquake
│   ├── index.html
│   └── static
│       ├── css
│       │   └── style.css
│       └── js
│           └── logic.js
├── Leaflet-TectonicPlates
│   ├── index.html
│   └── static
│       ├── css
│       │   └── style.css
│       └── js
│           └── logic.js
├── README.md

```


## Reference

1. https://leaflet-extras.github.io/leaflet-providers/preview/  
2. https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php    
3. https://en.wikipedia.org/wiki/Earth%27s_magnetic_field  
4. https://github.com/fraxen/tectonicplates  
5. https://www.weather.gov/jetstream/plates_max  











