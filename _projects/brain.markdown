---
layout: page
title: Location based social network analysis
description: On social network analysis with <a href="https://sites.google.com/view/brainiith/home?authuser=0">BRAIN group</a>
img: /assets/img/lbsn.png
importance: 1
category: work
redirect: true
---
Location based social networks offer an unique perspective to analyse social movements and uncover new dynamics between users and their attributes of movements. The results of such analyses are especially useful to recommendation services like <a href="https://foursquare.com/">FourSquare</a>. Recently, these problems have been addressed using the concept of regular hypergraphs where attributes related to each user constitute each hyperedge. A higher order structure, one example of which is a hypergraph, have been proven to be a better model than graphs for dealing with interaction of information from different domains. However, the current machine learning implementations are based on graphical structures which work on expansion of hyperedges. Hence, they are unable to take advantage of the information contained in the higher order of connectivity. This project was aimed at developing techniques for learning node embeddings that do not rely on the expansion of the hyperedges and are capable of capturing the dynamics in higher order connectivities.



<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/1.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/3.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/5.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/hg.png' | relative_url }}" alt="" title="PageRank embedding"/>
    </div>
</div>
<div class="caption">
    This graph was generated using PageRank embedding technique on a network with 8500 nodes.
</div>

Location based social networks offer an unique perspective to analyse social movements and uncover new dynamics between users and their attributes of movements. The results of such analyses are especially useful to recommendation services like <a href="https://foursquare.com/">FourSquare</a>. Recently, these problems have been addressed using the concept of regular hypergraphs where attributes related to each user constitute each hyperedge. A higher order structure, one example of which is a hypergraph, have been proven to be a better model than graphs for dealing with interaction of information from different domains. However, the current machine learning implementations are based on graphical structures which work on expansion of hyperedges. Hence, they are unable to take advantage of the information contained in the higher order of connectivity. This project was aimed at developing techniques for learning node embeddings that do not rely on the expansion of the hyperedges and are capable of capturing the dynamics in higher order connectivities.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/hg.png' | relative_url }}" alt="" title="PageRank embedding"/>
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/11.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>


The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/" target="_blank">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

```html
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/6.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/11.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
```
