# What does it do?
The function `flipCard.flipCard()` will take in three parameters

1. Front image layer
2. Back image layer
3. Perspective, see [docs for reference](http://framerjs.com/docs/#layer.perspective)

![What it does](http://i.imgur.com/GBWvMkm.png)

# Example
[![Flip Card Example](flipCardExample.gif)](http://share.framerjs.com/5ggio6opb1iw/)

# Instructions

1. Include the module
```
flipCard = require "flipCard"
```

2. Add a front image layer + back image layer + the perspective
```
flipCard.flipEffect(frontLayer, backLayer, 1600)
```

note: 1600 is the perspective number used in the example above. The smaller the number the more perspective you get.