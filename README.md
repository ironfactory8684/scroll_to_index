# scroll_to_index

This package modifies the highlighting functionality of <a href="https://pub.dev/packages/scroll_to_index">scroll_to_index.</a></br> 

scroll_to_index allows you to move the position of a variable-sized item in a listview to the index, and has the ability to highlight the color of a specific item. </br>
However, the specific item behavior was not happening, so we fixed it.</br>
The modification allows a simple animation to occur when selecting a specific item. 


```
hilight => highlightAnimation;
controller.highlightAnimation(index);  use animation

hilight => highlightAnimation;
controller.highlightColor(index); use highlight
```

