# (JavaFX) PathGraph

PathGraph is an adapted version of the SmartGraph library, developed to implement specific features for the representation, management, and interaction with path graphs.

## Index

 1. [About](#about)
 2. [Features](#features)
 3. [Requirements](#requirements)
 4. [Licenses](#licenses)
    
## About

#### Why PathGraph
If you need a ready-to-use library for representing path graphs with nodes, edges and associated weights, which offers advanced user interface features to represent, manage and interact with path graphs, then PathGraph is the right solution for you .

#### Fork based project
This library is a fork based on the source code of the [SmartGraph](https://github.com/brunomnsilva/JavaFXSmartGraph) [v2.0.0](https://github.com/brunomnsilva/JavaFXSmartGraph/releases/tag/v2.0.0) library on which existing classes have been modified and new ones have been added. PathGraph is therefore the adaptation of SmartGraph for the specific use of path graphs

#### Development Methodology

Development choices are motivated by the desire to maintain the structure and functionality of the original code with minimal changes to adapt it to the implementations of this specific project.
This is allowed thanks to greater transparency of the changes made in the reconstruction of the classes so that the differences between the original SmartGraph library code and that present in BoostSmartGraph are more understandable

## Features


### Default Features

You can find the default features in the original forked project: [SmartGraph#features]([v2.0.0](https://github.com/brunomnsilva/JavaFXSmartGraph/releases/tag/v2.0.0) ) 

### Showing Path

Using the path-find algorithm you can see the path found with an animation

### Upload Graph

**Upload Graphs** is possibile to upload **json file** in wich there are the data of nodes, edges and associated weights to rappresent the graph


### Download Graph

**Download Graphs** is possibile to download **json file** in wich there are the data of nodes, edges and associated weights  of the rappresented graph

### Interactions with Graph

The user make **Douple Click** on one of this components of the graph to do:
| Background| Node | Edge |
| ------------ | ------------ | ------------ |
| <img src="https://github.com/vittorioPiotti/PathGraph-JavaFX/blob/master/github/clickBackground.gif" alt="Icona" width="100%"/> | <img src="https://github.com/vittorioPiotti/PathGraph-JavaFX/blob/master/github/clickNode.gif" alt="Icona" width="100%"/> | <img src="https://github.com/vittorioPiotti/PathGraph-JavaFX/blob/master/github/clickEdge.gif" alt="Icona" width="100%"/>|
| New Node | New Edge | Delete Edge |
|  | Delete Node | Direct Edge |
|  |  | Split Edge |
|  |  | Edit Edge |

#### Annotations about Interactions with Graph
* _A maximum of two edges with different directions can be created between two nodes_
* _The loop despite is supported in PathGraph because is implemented by [SmartGraph](https://github.com/brunomnsilva/JavaFXSmartGraph) it is never used in in PathGraph_
* _Three directions are supported: the direction of edge creation, the opposite direction of edge creation, and bidirectional (the edge without arrows)_

### Interactions with Graph Container

The user interactions with graph container can be:

| Zoom| Drag | Zoom and Drag |
| ------------ | ------------ | ------------ |
|<img src="https://github.com/vittorioPiotti/PathGraph-JavaFX/blob/master/github/zoom.gif" alt="Icona" width="100%"/>|<img src="https://github.com/vittorioPiotti/PathGraph-JavaFX/blob/master/github/drag.gif" alt="Icona" width="100%"/>|<img src="https://github.com/vittorioPiotti/PathGraph-JavaFX/blob/master/github/ZoomAndDragEvent.gif" alt="Icona" width="100%"/>|

#### Annotations about Interactions with Graph Container

 * _There is a control thanks to which if you drag the graph beyond the limits of the container so as not to lose the graph, automatic repositioning is implemented._
 * _The graph container is responsive and available to fit into any external container_

## Requirements

 * Java Version: `21.0.3` [(link)](https://www.oracle.com/java/technologies/downloads/#java21)
 * JavaFX Version: `22.0.2+4`[(link)](https://gluonhq.com/products/javafx/)
 

## Licenses

| Component          | Version         | Copyright                                      | License                                                                                            |
|---------------------|------------------|------------------------------------------------|----------------------------------------------------------------------------------------------------|
| [PathGraph](https://github.com/vittorioPiotti/JavaFXPathGraph) | Not released    | 2024 Vittorio Piotti [(GitHub page)](https://github.com/vittorioPiotti) [(Personal page)](https://vittoriopiotti.altervista.org/)            | [GPL-3.0 ](https://github.com/vittorioPiotti/JavaFXPathGraph/blob/master/LICENSE.txt) |
| [JavaFXSmartGraph](https://github.com/brunomnsilva/JavaFXSmartGraph)        | [v2.0.0](https://github.com/brunomnsilva/JavaFXSmartGraph/releases/tag/v2.0.0)           | 2019 - 2024 Bruno Silva [(GitHub page)](https://github.com/brunomnsilva) [(Personal page)](https://www.brunomnsilva.com/)                          | [MIT](https://github.com/brunomnsilva/JavaFXSmartGraph/blob/master/LICENSE.txt)       |
| Bootstrap          | v4.0.0    | 2011-2018 The Bootstrap Authors   | [MIT ](https://github.com/twbs/bootstrap/blob/master/LICENSE) |





> [!NOTE]
> Di **Bootstrap** sono state utilizzate solo le icone SVG
