---
layout: home
---

# Synap

## What is Synap?

Synap is a learning management system for non-traditional education.

Synap focuses on real world applications rather than preparing for tests, and textbook education. While geared mainly towards computer-oriented studies, synap can be used for any number of classes.

We've created a small (and much simpler) example of a classroom, Sort[101]. I'll explain how to use it later down.

Synap could be used to support a much larger school ecosystem once developed, but we leave this small visualization as an example


# Sort[101]

Do you need help understanding or visualizing sorting algorithms?

If you do, Sort[101] is for you!

<br/>

Here is an example of a Synap class (to learn sorting):

![shot 1]({{site.baseurl}}images/shot1.png)

You can see the basics here. Users type code (JavaScript) into the input box, and then hit `run` or `autorun` buttons. 

After this, the code will run (if you use autorun, the example is animated) and (hopefully) sort the graph.

You know the graph is sorted once every bar is colored green.


## Colors

There are three colors implemented right now. To colors and animations, design your code to run in `autorun` mode (your entire code is ran over and over).

  * Orange: sorted, (or starting position)
  * Gray: being switched
  * Red: is larger than the bar before it (out of order)

In this example:

{: .center}
![shot 2]({{site.baseurl}}images/shot2.png)

The left hand side is already somewhat sorted (this is the process of insertion sort), and the ones on the right are not in order.


## Settings

To change settings, click the gear icon in the top right of the page:

{: .center}
![shot 3]({{site.baseurl}}images/shot3.png)

This will expand the list of settings, which you can change the upper and lower limit of the bars produced (the y scale), the amount of bars, the delay between autoruns, whether or not to only produce integers, and whether or not to show the graph.

All of your settings are cached, so if you refresh the page, they will be the same as when you left it.

The same is true with your code, so if you run some code, then refresh the page, the input box will be where you left it.


## Example

All of these pictures so far have been using the `Animated Insertion Sort` code, which can be found by going to the [sorting page](./sorting/), and selecting "Animated Insertion Sort" from the `Examples` list, then click `autorun`.

You should see the bars slowly moving about and changing colors. You can see all the code in the `input` box.

The `array` variable is the dataset, and `length` is the length.

If you use the `autorun` button, see examples for using that (the examples dropdown)

## Custom Functions

There are custom functions you can use as well.

For example:

swap(a, b):

  * swaps index a and b in array

