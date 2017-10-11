This is just a design I've come up with.
It consists of 3 photodiode sensors/pressure sensors and an LED setup, to function as a touch-screen like device for accepting input, from the user.

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


s