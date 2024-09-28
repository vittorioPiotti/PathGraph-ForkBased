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
If you need a ready-to-use library for user-side representing path graphs in wich there are nodes, edges and associated weights, which offers user-firendly interface to represent, manage and interact with path graphs, then SmartGraphUI is the right solution for you.

#### Fork based project
This library is a fork based on the source code of the [SmartGraph](https://github.com/brunomnsilva/JavaFXSmartGraph) [v2.0.0](https://github.com/brunomnsilva/JavaFXSmartGraph/releases/tag/v2.0.0) library on which existing classes have been modified and new ones have been added. SmartGraphUI is therefore the adaptation of SmartGraph to improve the user-experience in a user-firendly interface.


#### Development Methodology

Development choices are motivated by the desire to maintain the structure and functionality of the original code with minimal changes to adapt it to the implementations of this specific project.
This is allowed thanks to greater transparency of the changes made in the reconstruction of the classes so that the differences between the original SmartGraph library code and that present in SmartGraphUI are more understandable

## Features

> [!NOTE]
> The features of the forkd repository can be found at [SmartGraph](https://github.com/brunomnsilva/JavaFXSmartGraph?tab=readme-ov-file#features) 


### Display Found Path

Ability to display the found path with an animation to highlight the edge nodes associated with it

### Upload Graph

Ability to upload **json file** in wich there are the data to rappresent the graph


### Download Graph

Ability to download **json file** in wich there are the data of the rappresented graph



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
* _Max two edges with different directions connected with two nodes_
* _The loop is never used in in SmartGraphUI but there in SmartGraph_
* _Three directions are supported:
    * the direction of edge creation,
    * the opposite direction of edge creation,
    * and bidirectional (the edge without arrows)_
      

### Interactions with Graph Container

The user interactions with graph container can be:

| Zoom| Drag | Zoom and Drag |
| ------------ | ------------ | ------------ |
|<img src="https://github.com/vittorioPiotti/PathGraph-JavaFX/blob/master/github/zoom.gif" alt="Icona" width="100%"/>|<img src="https://github.com/vittorioPiotti/PathGraph-JavaFX/blob/master/github/drag.gif" alt="Icona" width="100%"/>|<img src="https://github.com/vittorioPiotti/PathGraph-JavaFX/blob/master/github/ZoomAndDragEvent.gif" alt="Icona" width="100%"/>|

> The gifs are taken from the SmartGraphUI software

#### Annotations about Interactions with Graph Container

 * _There is a control thanks to which if you drag the graph beyond the limits of the container so as not to lose the graph, automatic repositioning is implemented._
 * _The graph container is responsive and available to fit into any external container_

## Requirements

 * Java Version: `21.0.3` [(link)](https://www.oracle.com/java/technologies/downloads/#java21)
 * JavaFX Version: `22.0.2+4` [(link)](https://gluonhq.com/products/javafx/)
 

## Licenses

| Component          | Version         | Copyright                                      | License                                                                                            |
|---------------------|------------------|------------------------------------------------|----------------------------------------------------------------------------------------------------|
| [PathGraph](https://github.com/vittorioPiotti/JavaFXPathGraph) | Not released    | 2024 Vittorio Piotti [(GitHub page)](https://github.com/vittorioPiotti) [(Personal page)](https://vittoriopiotti.altervista.org/)            | [GPL-3.0 ](https://github.com/vittorioPiotti/JavaFXPathGraph/blob/master/LICENSE.txt) |
| [JavaFXSmartGraph](https://github.com/brunomnsilva/JavaFXSmartGraph)        | [v2.0.0](https://github.com/brunomnsilva/JavaFXSmartGraph/releases/tag/v2.0.0)           | 2019 - 2024 Bruno Silva [(GitHub page)](https://github.com/brunomnsilva) [(Personal page)](https://www.brunomnsilva.com/)                          | [MIT](https://github.com/brunomnsilva/JavaFXSmartGraph/blob/master/LICENSE.txt)       |
| Bootstrap          | v4.0.0    | 2011-2018 The Bootstrap Authors   | [MIT ](https://github.com/twbs/bootstrap/blob/master/LICENSE) |





> [!NOTE]
> Di **Bootstrap** sono state utilizzate solo le icone SVG
