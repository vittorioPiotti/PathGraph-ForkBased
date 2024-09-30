# (JavaFX) SmartGraphUI

SmartGraphUI is an adapted version of the SmartGraph library, developed to implement new user-experience features in a stable user-friendly interface.

## Index

 1. [About](#about)
 2. [Features](#features)
 3. [Usage](#usage)
 4. [Requirements](#requirements)
 5. [Licenses](#licenses)
    
## About


#### Why SmartGraphUI

If you need a ready-to-use library for user-side representing path graphs in which there are nodes, edges, and associated weights, which offers a user-friendly interface to represent, manage, and interact with path graphs, then SmartGraphUI is the right solution for you.

#### Fork Based Project

This library is a fork based on the source code of the [SmartGraph](https://github.com/brunomnsilva/JavaFXSmartGraph) [v2.0.0](https://github.com/brunomnsilva/JavaFXSmartGraph/releases/tag/v2.0.0) library on which existing classes have been modified and new ones have been added. SmartGraphUI is therefore the adaptation of SmartGraph to improve the user-experience in a user-firendly interface.

#### Development Methodology

Development choices are motivated by the desire to maintain the structure and functionality of the original code with minimal changes to adapt it to the implementations of this specific project.
This is allowed thanks to greater transparency of the changes made in the reconstruction of the classes so that the differences between the original SmartGraph library code and that present in SmartGraphUI are more understandable





## Features

> [!NOTE]  
> The features of the forked repository can be found at [SmartGraph](https://github.com/brunomnsilva/JavaFXSmartGraph?tab=readme-ov-file#features)

### Index

 1. [Smart Callbacks System](Smart-Callbacks-System)
 2. [Intuitive UI System](Intuitive-UI-System)
 3. [Display Found Path](Display-Found-Path)
 4. [Upload and Download Graphs](Upload-and-Download-Graphs)
 5. [Resume](#Resume)

#### Methods refactoring 

 * Each event on the graph is associated with a callback that is defined during the constructor instantiation.
   
   This ensures that developers can apply their custom actions to each event.
   
 * The deactivation of graph interactions is able with empty callbacks
   
#### Callbacks System

Callbacks on component of the graph _node, edge, background_:

|Hover|Click|Drag|Scroll|
|-|-|-|-|
|Node|Yes|Yes| |
|Edge|Yes|Yes| | 
|Background| |Yes|Yes|Yes|

The deactivation of graph interactions is able with empty callbacks.

This involves defining the components as buttons for actions on the graph.



#### Intuitive UI 
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


### Interactions with Graph

The user make **Douple Click** on one of this components of the graph to do:
| Background| Node | Edge |
| ------------ | ------------ | ------------ |
| <img src="https://github.com/vittorioPiotti/PathGraph-JavaFX/blob/master/github/clickBackground.gif" alt="Icona" width="100%"/> | <img src="https://github.com/vittorioPiotti/PathGraph-JavaFX/blob/master/github/clickNode.gif" alt="Icona" width="100%"/> | <img src="https://github.com/vittorioPiotti/PathGraph-JavaFX/blob/master/github/clickEdge.gif" alt="Icona" width="100%"/>|
| New Node | New Edge | Delete Edge |
|  | Delete Node | Direct Edge |
|  |  | Split Edge |
|  |  | Edit Edge |

> The gifs are taken from the SmartGraphUI software

#### Annotations about Interactions with Graph

* Max two edges with different directions connected with two nodes
* The loop is never used in in SmartGraphUI but there in SmartGraph
* Three directions are supported:
    1. Direction of edge creation,
    2. Opposite direction of edge creation,
    3. Bidirectional (edge without arrows)
      

### Interactions with Graph Container

The user interactions with graph container can be:

| Zoom| Drag | Zoom and Drag |
| ------------ | ------------ | ------------ |
|<img src="https://github.com/vittorioPiotti/PathGraph-JavaFX/blob/master/github/zoom.gif" alt="Icona" width="100%"/>|<img src="https://github.com/vittorioPiotti/PathGraph-JavaFX/blob/master/github/drag.gif" alt="Icona" width="100%"/>|<img src="https://github.com/vittorioPiotti/PathGraph-JavaFX/blob/master/github/ZoomAndDragEvent.gif" alt="Icona" width="100%"/>|

> The gifs are taken from the SmartGraphUI software

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
