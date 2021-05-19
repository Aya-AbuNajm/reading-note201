# CSS Transforms
With CSS3 came new ways to position and alter elements. Now general layout techniques can be revisited with alternative ways to size, position, and change elements. All of these new techniques are made possible by the transform property.

The transform property comes in two different settings, two-dimensional and three-dimensional. Each of these come with their own individual properties and values.

~~~
2D Rotate The transform property accepts a handful of different values. The rotate value provides the ability to rotate an element from 0 to 360 degrees
~~~

## AnimationsTransitions
 do a great job of building out visual interactions from one state to another, and are perfect for these kinds of single state changes. However, when more control is required, transitions need to have multiple states
![ani](https://blog.commlabindia.com/wp-content/uploads/2019/07/animated-gifs-corporate-training.gif)
**Animation Name** :
Once the keyframes for an animation have been declared they need to be assigned to an element. To do so, the animation-name property is used with the animation name, identified from the @keyframes rule, as the property value



---------------------

## CSS Transitions
![tra](https://daqxzxzy8xq3u.cloudfront.net/wp-content/uploads/2019/07/15114208/css-transition-illustration.jpg)
<CSS transitions allows you to change property values smoothly, over a given duration.

**How to Use CSS Transitions**
To create a transition effect, you must specify two things:

the CSS property you want to add an effect to the duration of the effect Note: If the duration part is not specified, the transition will have no effect, because the default value is zero.

## Specify the Speed Curve of the Transition
The transition-timing-function property specifies the speed curve of the transition effect.

The transition-timing-function property can have the following values:

- ease - specifies a transition effect with a slow start, then fast, then end slowly (this is default)
- linear - specifies a transition effect with the same speed from start to end
- ease-in - specifies a transition effect with a slow start
- ease-out - specifies a transition effect with a slow end
- ease-in-out - specifies a transition effect with a slow start and end
- cubic-bezier(n,n,n,n) - lets you define your own values in a cubic-bezier function


## 8 SIMPLE CSS3 TRANSITIONS prpparty
1- Fade in
2- Change color
3- Grow & Shrink
4- Rotate elements
5- Square to circle
6- 3D shadow
7- Swing
8- Inset border