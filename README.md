# Show-polygon-information-on-click

In this example, when a user clicks a polygon in a specified layer, the map shows a popup containing information about the clicked feature.

When the map loads, it uses addSource and addLayer to add and style a layer called states-layer, which contains state polygons.

When the user clicks a feature in the states-layer layer, the example uses the Popup method to create a new popup, using MapMouseEvent data to set the position and content of the popup.

Lastly, it uses the Map events mouseenter and mouseleave to toggle the user's cursor to a pointer while it hovers over any feature in states-layer.

![image](https://user-images.githubusercontent.com/118595650/202859814-ef470ab9-1a1e-4494-8602-4bc4b7ebb95d.png)


![image](https://user-images.githubusercontent.com/118595650/202859838-32ace6af-f51c-47d2-91b4-bd2440fabe99.png)
