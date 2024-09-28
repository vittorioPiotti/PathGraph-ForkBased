# (JavaFX) PathGraph

PathGraph is an adapted version of the SmartGraph library, developed to implement specific features for the representation, management, and interaction with path graphs.

#### Why PathGraph
If you need a ready-to-use library for representing path graphs with nodes, edges and associated weights, which offers advanced user interface features to represent, manage and interact with path graphs, then PathGraph is the right solution for you .

#### Fork based project
This library is a fork based on the source code of the [SmartGraph](https://github.com/brunomnsilva/JavaFXSmartGraph) [v2.0.0](https://github.com/brunomnsilva/JavaFXSmartGraph/releases/tag/v2.0.0) library on which existing classes have been modified and new ones have been added. PathGraph is therefore the adaptation of SmartGraph for the specific use of path graphs


## Features

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

### Interactions with Graph Container

Other user interaction with graph container events:

| Zoom| Drag | Zoom and Drag |
| ------------ | ------------ | ------------ |
|<img src="https://github.com/vittorioPiotti/PathGraph-JavaFX/blob/master/github/zoom.gif" alt="Icona" width="100%"/>|<img src="https://github.com/vittorioPiotti/PathGraph-JavaFX/blob/master/github/drag.gif" alt="Icona" width="100%"/>|<img src="https://github.com/vittorioPiotti/PathGraph-JavaFX/blob/master/github/ZoomAndDragEvent.gif" alt="Icona" width="100%"/>|


## Requirements

 * Java Version: `21.0.3`
 * JavaFX Version: `22.0.2+4`
 

## Licenses

| Component          | Version         | Copyright                                      | License                                                                                            |
|---------------------|------------------|------------------------------------------------|----------------------------------------------------------------------------------------------------|
| [PathGraph](https://github.com/vittorioPiotti/JavaFXPathGraph) | Not released    | 2024 Vittorio Piotti [(GitHub page)](https://github.com/vittorioPiotti) [(Personal page)](https://vittoriopiotti.altervista.org/)            | [GPL-3.0 ](https://github.com/vittorioPiotti/JavaFXPathGraph/blob/master/LICENSE.txt) |
| [JavaFXSmartGraph](https://github.com/brunomnsilva/JavaFXSmartGraph)        | [v2.0.0](https://github.com/brunomnsilva/JavaFXSmartGraph/releases/tag/v2.0.0)           | 2019 - 2024 Bruno Silva [(GitHub page)](https://github.com/brunomnsilva) [(Personal page)](https://www.brunomnsilva.com/)                          | [MIT](https://github.com/brunomnsilva/JavaFXSmartGraph/blob/master/LICENSE.txt)       |
| Bootstrap          | v4.0.0    | 2011-2018 The Bootstrap Authors   | [MIT ](https://github.com/twbs/bootstrap/blob/master/LICENSE) |





> [!NOTE]
> Di **Bootstrap** sono state utilizzate solo le icone SVG
