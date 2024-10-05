# (JavaFX) SmartGraphUI


SmartGraphUI is an adapted version of the [SmartGraph](https://github.com/brunomnsilva/JavaFXSmartGraph) library, developed to implement new user-experience features in a stable user-friendly interface.

<img src="https://github.com/vittorioPiotti/PathGraph-JavaFX/blob/master/github/preview906.png" alt="Icona" width="100%"/>




---

## Index

 1. [About](#about)
 2. [Updates](#updates)
 3. [Features](#features)
 4. [Usage](#usage)
 5. [Requirements](#requirements)
 6. [Licenses](#licenses)
    
## About




#### Why SmartGraphUI

If you need a ready-to-use library for user-side representing path graphs in which there are nodes, edges, and associated weights, which offers a user-friendly interface to represent, manage, and interact with path graphs, then SmartGraphUI is the right solution for you.

#### Fork Based Project

This library is a fork based on the source code of the [SmartGraph](https://github.com/brunomnsilva/JavaFXSmartGraph) [v2.0.0](https://github.com/brunomnsilva/JavaFXSmartGraph/releases/tag/v2.0.0) library on which existing classes have been modified and new ones have been added. SmartGraphUI is therefore the adaptation of SmartGraph to improve the user-experience in a user-firendly interface.




## Updates


### Methods refactoring 

|Node|Edge|Graph|
|-|-|-|
|new node|new edge|screenshot|
|delete node|delete edge|display path found|
|rename node|rename edge|upload graph|
||rotate edge|download graph|
||fork edge||

 * Now method parameters are generic and independent of internal classes.
 * The logic has been made more high-level so as to more easily manipulate the components of the graph
 * Graph management requires as parameters only the labels of the nodes involved in the method

### Callbacks System

| |Hover|Click|Drag|Scroll|
|-|-|-|-|-|
|**Node**|Yes|Yes|Yes | |
|**Edge**|Yes|Yes| | |
|**Background**| |Yes|Yes|Yes|

**Empty callbacks** disable graph interactions so set actions in your components to manage the graph _(e.g. button to create new edge)_


### Features

> [!NOTE]  
> The features of the forked repository can be found at [SmartGraph](https://github.com/brunomnsilva/JavaFXSmartGraph?tab=readme-ov-file#features)



### Index

 1. [Intuitive UI System](Intuitive-UI-System)
 2. [Display Found Path](Display-Found-Path)
 3. [Upload and Download Graphs](Upload-and-Download-Graphs)
 4. [Resume](#Resume)


#### Intuitive UI 

<img src="https://github.com/vittorioPiotti/PathGraph-JavaFX/blob/master/github/preview82.png" alt="Icona" width="100%"/>

> Image from SmartGraphUI 


An effective and minimal user interface has been designed based on the Less-is-More principle.  
It is possible to choose whether to use the default UI or configure custom actions for the associated events.



#### Display Found Path

Ability to display the found path with an animation to highlight the edge nodes associated with it

#### Upload and Download Graphs

Ability to upload **json file** of the graph or to download **json file** of the graph

### Resume

 1. Completely responsive container
 2. Smooth and stable Zoom and Drag
 3. Node create/delete
 4. Edge create/delete/rename/rotate/fork
 5. Display the found path
 6. Upload and download of graphs
    



## Usage

### Edge Directions

|Left|Right|Bidirectional|
|---|---|---|

Max two edges with different directions connected with two nodes


### Graph Interactions

The user make **Douple Click** on one of this components of the graph to do:
| Background| Node | Edge |
| ------------ | ------------ | ------------ |
| <img src="https://github.com/vittorioPiotti/PathGraph-JavaFX/blob/master/github/clickBackground.gif" alt="Icona" width="100%"/> | <img src="https://github.com/vittorioPiotti/PathGraph-JavaFX/blob/master/github/clickNode.gif" alt="Icona" width="100%"/> | <img src="https://github.com/vittorioPiotti/PathGraph-JavaFX/blob/master/github/clickEdge.gif" alt="Icona" width="100%"/>|
| New Node | New Edge | Delete Edge |
|  | Delete Node | Direct Edge |
|  |  | Split Edge |
|  |  | Edit Edge |

> Gifs from SmartGraphUI 


### Graph Container Interactions

The user interactions with graph container can be:

| Scroll to Zoom| Drag to Move | Zoom and Drag |
| ------------ | ------------ | ------------ |
|<img src="https://github.com/vittorioPiotti/PathGraph-JavaFX/blob/master/github/zoom.gif" alt="Icona" width="100%"/>|<img src="https://github.com/vittorioPiotti/PathGraph-JavaFX/blob/master/github/drag.gif" alt="Icona" width="100%"/>|<img src="https://github.com/vittorioPiotti/PathGraph-JavaFX/blob/master/github/ZoomAndDragEvent.gif" alt="Icona" width="100%"/>|

> Gifs from SmartGraphUI 

#### Annotations about Interactions with Graph Container

 * **Dragging control** to automatically reposition the graph when it goes out of bounds
 * **Responsive container** available to fit into any external container.

## Requirements

 * Java Version: `21.0.3` [(link)](https://www.oracle.com/java/technologies/downloads/#java21)
 * JavaFX Version: `22.0.2+4` [(link)](https://gluonhq.com/products/javafx/)
 

## Licenses

| Component          | Version         | Copyright                                      | License                                                                                            |
|---------------------|------------------|------------------------------------------------|----------------------------------------------------------------------------------------------------|
| [SmartGraphUI](https://github.com/vittorioPiotti/JavaFXPathGraph) | Not released    | 2024 Vittorio Piotti [(GitHub page)](https://github.com/vittorioPiotti) [(Personal page)](https://vittoriopiotti.altervista.org/)            | [GPL-3.0 ](https://github.com/vittorioPiotti/JavaFXPathGraph/blob/master/LICENSE.txt) |
| [JavaFXSmartGraph](https://github.com/brunomnsilva/JavaFXSmartGraph)        | [v2.0.0](https://github.com/brunomnsilva/JavaFXSmartGraph/releases/tag/v2.0.0)           | 2019 - 2024 Bruno Silva [(GitHub page)](https://github.com/brunomnsilva) [(Personal page)](https://www.brunomnsilva.com/)                          | [MIT](https://github.com/brunomnsilva/JavaFXSmartGraph/blob/master/LICENSE.txt)       |
| Bootstrap          | v4.0.0    | 2011-2018 The Bootstrap Authors   | [MIT ](https://github.com/twbs/bootstrap/blob/master/LICENSE) |





> [!NOTE]
> SVG icons from **Bootstrap**

---

I hope you find SmartGraph useful and look forward to seeing the projects you create with it!

