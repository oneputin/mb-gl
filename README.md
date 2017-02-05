# \<mb-gl\>

wrap a mapbox 

## Strategy

create own elements for 
+ server-query
+ map-element
+ map-slide (overlay)

## elements

### \<mb-map\>
wrap around map based on mapbox-gl-api 

### \<mb-slide\>
wrap a feature-overlay linked to mapbox-gl-map ('map'-property)  
Results of feature-queries are exported (and/or) presented in popup (paper-dialog)  

### \<mb-zoom\>
Bidirectional Zoom-Ctrl related to mapbox-gl-map ('map'-property)  

### \<mb-target\>
Target-box centered on client-map-viewbox.

### \<mb-api\>
Wraps the mapbox-gl-api as separate element

### \<mb-info\>


### \<routing-api\>
The auto-ctrl of trackInfo open/close (start-stop) is organized by property "routeProps.stop" 
+ start if flag stop is not set
+ stop: remove flag stop 
main 

### \<mb-distance\>
OPTIONAL-tool to measure distances on mb-map 

### \<mb-location-log\>
OPTIONAL-tool to query/view/supply mouse-map-location (lonlat)
 