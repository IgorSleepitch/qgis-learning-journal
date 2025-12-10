# 10. Module: Online Resources

Inthis module I've learned how to connect QGIS to external online data sources — from simple basemaps to remote vector/raster services and catalogues.

### Steps
1. Explored different types of online GIS resources:
   - **WMS / WMTS** — map images rendered on the server side  
   - **WFS** — dynamic vector features you can query and edit   

2. Added multiple online layers:
   - connected a WMS endpoint and experimented with layer styles  
   - loaded a WFS dataset and tested attribute filtering directly from the server  
   - added OSM for background cartography  

3. Compared advantages and limitations: 
   - WMS: high quality & official sources, but static  
   - WFS: flexible & interactive, but dependent on server performance and a lot less available  

4. Configured authentication and cache settings for stable performance.  
5. Practiced saving online layers locally as GeoPackage for offline use.

### Outcome
- Learned where to find authoritative online data (governments, open-data portals, OSM derivatives).  
- Built a project that mixes local and remote datasets.  
- Understood how online layers behave differently from local files — especially with queries, symbology, and speed.
