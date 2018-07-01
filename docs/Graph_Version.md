# Graph Versioning

The Graph Version feature gives Users the ability to create different versions of Graphs in GraphSpace. The User needs to be signed-in to GraphSpace in order to use this feature. [GraphSpace](http://www.graphspace.org) allows users to create version of a Graph through GraphSpace's REST APIs.

The following features are available in the Graph Version functionality:

- [Graph Versions Tab](#graph-versions-tab)
- [Graph Versioning Using REST APIs](#graph-versioning-using-rest-apis)


## Graph Versions Tab

The `Graph Versions` tab displays information about the different versions of the graph in a table format. The table contains following columns:

1. **Version Name** - Name of the forked graph.
2. **Description** - Tags associated with the forked graph.
3. **Created at** - Email address of the owner of the graph.

The image below shows an example of Graph Versions Tab when a user clicks on the `Graph Version` tab link:

![Forked Graphs Tab Image](_static/gifs/gs-screenshot-LocalUser1-graph_version.gif)


### Graph Version Dropdown Selection

Users of GraphSpace can also select available Graph Versions using the Drop-down menu. The Drop-down menu displays the currently selected Graph Version.


![Forked Graphs Dropdown Image](_static/images/graph-page/gs-screenshot-LocalUser1-graph-version-dropdown.jpg)


## Graph Versioning Using REST APIs

The User can Create, Update & Delete Graph Versions using the [GraphSpace REST APIs](Programmers_Guide.html#api-reference)
