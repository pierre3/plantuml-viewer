## 0.5.0
* Add support for including multiple source files via relative include paths

## 0.4.1
* Fixed so that hovering over diagram text don't cause the mouse cursor to change
* Fixed a bug where updating a view when it was not visible would cause errors

## 0.4.0
* Added configuration for PlantUML config file, read before each diagram
* Improved viewport handling while doing live update and while resizing panels
* Fixed a bug where svg-pan-zoom was still considered constructed after destruction
* Fixed a bug where resizing view when it was not visible would cause errors

## 0.3.0
* Added pan and zoom controls for the PlantUML diagrams

## 0.2.1
* Updated minimum version of node-plantuml dependency

## 0.2.0
* Added functionality to save diagrams as PNG, SVG or EPS
* Added configuration for Graphviz dot executable

## 0.1.6
* UML diagrams are set to always fill the whole pane
* Added padding to the diagram

## 0.1.3
* Added configuration for live updates
* Added configuration for split pane

## 0.1.2
* Sped up updates by using SVG instead of PNG
* Sped up updates by updating on every change

## 0.1.1
* Displays PlantUML diagram in a new pane when toggling
* Updates the diagram live as the source is updated
