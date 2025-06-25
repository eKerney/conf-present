---
theme:
  path: tokyonight-custom.yaml
  override:
    default:
      colors:
        foreground: 74c7ec
---

<!-- alignment: center -->
<!-- new_lines: 6 -->
<!-- font_size: 5 -->
<span style="color: #a6e3a1;">What the Deck!?! </span>
<!-- font_size: 3 -->
<span style="color: #f9e2af;">deck.gl maps for fast spatial data viz </span>
<!-- font_size: 3 -->
<span style="color: #74c7ec;">CMPASS 2025 Conference!</span>

<span style="color: #74c7ec;">Tuesday June 3rd</span>
<!-- font_size: 2 -->
<span style="color: #74c7ec;">Kalamazoo, MI, Radisson Plaza</span>
<!-- font_size: 2 -->
<span style="color: #74c7ec;">Eric Kerney - Blue Raster</span>
![image:width:20%](blueraster-logo.png)
<!-- end_slide -->

<!-- alignment: center -->
<!-- new_lines: 1 -->
What is DeckGL 
---
<!-- new_lines: 1 -->
<!-- font_size: 3 -->
1. GPU powered highly performant large-scale data visualization 
<!-- new_lines: 1 -->
2. Layered Approach to Data Viz
<!-- new_lines: 1 -->
3. High-Precision GPU Computations 
<!-- new_lines: 1 -->
4. React Friendly
<!-- new_lines: 1 -->
6. Integration with Base Map Providers 
<!-- end_slide -->


<!-- new_lines: 6 -->
Background
---
<!-- new_lines: 1 -->
<!-- font_size: 3 -->
1. Developed at Uber
<!-- new_lines: 1 -->
2. Massive spatial data visualization 
<!-- new_lines: 1 -->
3. Transition to Open Source - Vis.gl
<!-- new_lines: 1 -->
4. OpenJS Foundation  
<!-- end_slide -->


<!-- new_lines: 6 -->
Integrations
---
<!-- new_lines: 1 -->
<!-- font_size: 3 -->
1. Basemaps
<!-- font_size: 2 -->
1. ArcGIS 
2. Google Maps
3. Mapbox 
4. MapLibre
<!-- new_lines: 1 -->
<!-- font_size: 3 -->
2. Integration
<!-- font_size: 2 -->
1. @deck.gl/arcgis
2. @deck.gl/carto
3. @deck.gl/google-maps 
4. @deck.gl/mapbox
<!-- new_lines: 1 -->
<!-- font_size: 1 -->
[Using with basemaps: ](https://deck.gl/docs/get-started/using-with-map)
<!-- end_slide -->


<!-- new_lines: 4 -->
H3 Geo	
---
<!-- new_lines: 1 -->
<!-- font_size: 3 -->
1. H3 - hierarchical geospatial index.
<!-- new_lines: 1 -->
2. Address Uber's data science needs
<!-- new_lines: 1 -->
3. Discrete global grid system
<!-- font_size: 2 -->
1. Data can be quickly joined across datasets and aggregated
2. Range of algorithms and optimizations 
3. Nearest neighbors
4. Shortest path, 
5. Gradient smoothing, and more
<!-- new_lines: 1 -->
<!-- font_size: 1 -->
[H3 Geo: ](https://h3geo.org/)
<!-- end_slide -->


<!-- new_lines: 4 -->
Getting Setup	
---
<!-- new_lines: 1 -->
<!-- font_size: 3 -->
1. WSL || MacOS preferred
<!-- new_lines: 1 -->
2. Terminal, NodeJS, npm/yarn, IDE
<!-- new_lines: 1 -->
3. My stack:
<!-- font_size: 2 -->
1. operating system: Mac
2. package manager: brew
3. window manager: aerospace 
4. terminal: zsh, oh-my-zsh, ghostty, tmux 
5. presnetation: presenterm, kitty 
<!-- end_slide -->


<!-- new_lines: 4 -->
Vite Project
---
<!-- new_lines: 1 -->
<!-- font_size: 3 -->
1. create-react-app deprecated
<!-- new_lines: 1 -->
2. Modern app scaffolding 
<!-- new_lines: 1 -->
3. Multiple frameworks/options
<!-- font_size: 2 -->
```bash 
npm create vite@latest

```
<!-- end_slide -->

