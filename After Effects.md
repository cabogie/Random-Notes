# After Effects Graph
#knowledge #adobe #aftereffects #software #animation

## Opening Graph View / Value Editor

Start by having an object:

> ![](https://i.imgur.com/qYg4tMl.gif)

Open the properties:

> ![](https://i.imgur.com/ClnZPh5.gif)



Open the graph view:

> ![](https://i.imgur.com/qtgVte1.gif)

Set to the mode to *edit value graph* (or right click to open this menu):

> ![](https://i.imgur.com/IxscQOQ.png)

> ![](https://i.imgur.com/iK4V7pR.gif)



---
---
---
---

## Creating Keyframes

#### Click Method:
- select a property
- ctrl+click
	- hold ctrl to toggle pen tool 
		- NOTE: this is on windows, mac might be command
		- You can also just select it up here (toggling is easier tho) ![](https://i.imgur.com/lljoHVf.png)
	
	- hover on the line 
	- click to add a keyframe

You can easily add and delete keyframes this way!!!

> ![](https://i.imgur.com/2TP76Rb.gif)


#### Stopwatch Icon Method:
 - Click the little stopwatch (idk what it does but it creates the first keyframe)
 - you can create more keyframes by moving the time slider thing and clicking the keyframe icon

> ![](https://i.imgur.com/n96RDbC.gif)


---
---
---

## Navigating the Graph

#### Toggle Graphs
You can toggle which graphs / keyframes are showing with the icon beside the stopwatch.

> ![](https://i.imgur.com/j8ksFHw.gif)


#### Autozoom

> ![](https://i.imgur.com/VmidZUy.png)

You CAN'T move around or scale the graph when this is selected. This can make moving more than one pixel tough, but can be helpful to keep the graph in view. 
> ![](https://i.imgur.com/gAGGvRw.gif)

#### Fit selection
> ![](https://i.imgur.com/jgsRbGG.png)

This fits your selected keyframes to the view.

NOTE: It only shows up when you have keyframes selected.


> ![](https://i.imgur.com/BFJf9yH.gif)


#### Fit all 
> ![](https://i.imgur.com/CCIyyRn.png)

This will bring all keyframes and graphs on the screen to view.

> ![](https://i.imgur.com/iVa5Ufp.gif)


#### Moving and Scaling Keyframes
You can select multiple keyframes and move / scale their time and values!!
> ![](https://i.imgur.com/KBa8uHB.gif)


---
---
---
## Keyframe Values

The keyframes represent the value of a property at a time. Each node (point) is a keyframe value.

**Example:**
If it's rotation it'll be a positive or negative angle.
If it's position it'll be the pixel position (x, y).

###### Dimensions (X, Y): 
For value pairs like (x, y), it'll show both of them at the same time.

It'll show x as red and y as green and their keyframes will both move at the same time.
> ![](https://i.imgur.com/IoKxLzv.png)

You can ***separate dimensions*** to move them independently by right clicking the property and clicking separate dimensions like below:
> ![](https://i.imgur.com/QEmcStI.gif)


---
---
---
## Transitions
select a keyframe and select one of these icons at the bottom to switch between transition types 

#### Different Transition Modes
> ![](https://i.imgur.com/O7oFBv1.png)

- Hold (red)
	- stays  at the value till new keyframe
- linear (blue) 
	- smooth straight line transition
- bezier curve (green)
		- create curves for the transition to speed up, slow down in different ways


> here's an example switch between them: ![](https://i.imgur.com/ZfGFOXr.gif)

---
---
---

## Creating Cool Things
Once you have an idea of how things work you can play around with creating keyframes and curves to see how it affects things!!!

#### Linear Y Example:
Because the composition starts at the top left of (0, 0), a higher pixel number for a y position makes the object go down!!

![](https://i.imgur.com/zbW1wYQ.gif)

#### Let's make it accelerate fast but ease at the end 
Before it was a straight line there, which means it was just a constant speed to fall.

To make it fall faster we give it a curve that reaches the target value faster.

So convert the keyframe to a bezier curve, and drag the handle so that the y value will more quickly hit the get to the target, but at the end it more slowly reaches that point.


![](https://i.imgur.com/5Kdr9ky.gif)

Now it accelerates quickly and then eases out.

#### More natural acceleration
Do the opposite for a slower acceleration. In other words, make it ease into the speed (reach the target fast at the end)


![](https://i.imgur.com/7bxSg6K.gif)


#### BOUNCE EXAMPLE!!!!
Kinda bad lol but I think it gets the point across for how curves can be used

First i just make it slide further for better effect

![](https://i.imgur.com/1Ms3foJ.gif)


Then I do some bouncing! (it's bad)


![](https://i.imgur.com/jAXyfNq.gif)


#### With Some Rotation too (it's also bad)

![](https://i.imgur.com/YIOHgea.gif)


---
---
---

## PLAY AROUND AND HAVE FUN AND LEARN

Putting all this knowledge together you can do this with a bunch of properties and objects to create neat animations!


