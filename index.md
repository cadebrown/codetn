---
layout: home
---

Do you need help understanding or visualizing sorting algorithms?

If you do, Synap is for you!

<br/>

Here is an example of a Synap class (to learn sorting):

![shot 1]({{site.baseurl}}images/shot1.png)

You can see the basics here. Users type code (JavaScript) into the input box, and then hit `run` or `autorun` buttons. 

After this, the code will run (if you use autorun, the example is animated) and (hopefully) will sort the graph.

You know the graph is sorted once every bar is colored green.


## Colors

There are three colors implemented right now. To colors and animations, design your code to run in `autorun` mode (your entire code is ran over and over).

  * <span style="color: #c40000;">Red</span>: The bars have not been swapped, and they are not in order.
  * <span style="color: #06a656;">Green</span>: The bar after the current one is larger, and the one before is smaller. This shows that green bars are ordered among other green bars.
  * <span style="color: #0000df;">Blue</span>: The bars have just been swapped (using the swap() method)

In this example:

{: .center}
![shot 2]({{site.baseurl}}images/shot2.png)

The right hand side is already somewhat sorted (this is to be expected with a bubble sort), a large portion of the mid range bars are still being switched, and the ones on the very left are somewhat in order.


## Settings

To change settings, click the gear icon in the top right of the page:

{: .center}
![shot 3]({{site.baseurl}}images/shot3.png)

This will expand the list of settings, which you can change the upper and lower limit of the bars produced (the y scale), the amount of bars, the delay between autoruns, whether or not to only produce integers, and whether or not to show the graph.

All of your settings are cached, so if you refresh the page, they will be the same as when you left it.

The same is true with your code, so if you run some code, then refresh the page, the input box will be where you left it.


## Example

All of these pictures so far have been using the `Animated Bubblesort` code, which can be found by going to the [sorting page](./sorting/), and selecting "Animated Bubblesort" from the `Examples` list, then click `autorun`.

You should see the bars slowly moving about and changing colors. You can see all the code in the `input` box.

The `array` variable is the dataset, and `length` is the length.

If you use the `autorun` button, see examples for using that (the examples dropdown)

## Custom Functions

There are custom functions you can use as well.

For example:

swap(a, b):

  * swaps index a and b in array

