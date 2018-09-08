# Mouse_concept

What do you think about when you hear the word 'mouse'?
If the animal is the first thing in mind, you're in the wrong place : D

But, I see it as an input method, which has not chaged inn any form over the past 10- 15 years at all.
That is what I beieve I can change.
I feel that a new way of entering input needs to exist, and this is it.



This is a new mouse design I've come up with.

![demo](https://user-images.githubusercontent.com/26602639/45257122-90d77e80-b3be-11e8-9331-e9bfce973012.PNG)


It consists of 3 photodiode sensors/pressure sensors and an LED setup(green in the image above), to function as a touch-screen like device for accepting input, from the user. The red parts indicate possible positions of proximity sensors, to identify whether or not a palm is placed above it.

Let us consider a user holding a mouse in it's rest state.

To enter the new input, theuserneeds to slidehis thumb along the side of the mouse, as if there were a cursor there.
 Assuming the mouse has the senso on the LHS, the following motion would give an anti clockwise motion.


1)
 ____________
|_o_|_o_|_o_|
 where o indicates position of thumb over mouse.

2)


 ____________
|___|_o_|_o_|
 where o indicates position of thumb over mouse.

3)

 ____________
|___|___|_o_|
 where o indicates position of thumb over mouse.

4)

 ____________
|___|___|___|
 where o indicates position of thumb over mouse.
When the user has his thumb along the side of the mouse, the sements will be no longer covered, allowing light to enter,thus giving loical high.


Thus, circuit changes from 000 to 100 to 110 to 111.




  Assuming the mouse has the senso on the LHS, the following motion would give an anti clockwise motion.


1)
 ____________
|___|___|___|
 where o indicates position of thumb over mouse.

2)


 ____________
|__|___|_o_|
 where o indicates position of thumb over mouse.

3)

 ____________
|___|_o_|_o_|
 where o indicates position of thumb over mouse.

4)

 ____________
|_o_|_o_|_o_|
 where o indicates position of thumb over mouse.
When the user has his thumb along the side of the mouse, the sements will be no longer covered, allowing light to enter,thus giving loical high.


Thus, circuit changes from 111 to 110 to 100 to 000. 

So, we need a circuit to identify when this transition occurs.

The same implementation can be done in case of a pressure sensor, where the circuit within gives logical high(1) when the pressure is released.

# The digital logic I've produced for this circuit:
![Demo](https://user-images.githubusercontent.com/26602639/45257118-7c938180-b3be-11e8-8139-24afeeffa443.png)

# Steps to Operate:
Run the given proteus code on the Proteus design suite, upon testing the required cases, we will get the required output.
