# POO3_Interface
_______________________________________________________________________________________________________________________________

Challenge {

* Browse the deposit and observe its contents:

    Bird abstract class.
    
    Eagle, class inherited from Bird.
    
    Swim, an interface.
    
    Penguin inherited class Birdthat implements Swim.
    
    Nature, that you will compile and run to test that everything works.
    
* Create an interface Fly

* Add the following methods to the interface Fly:

    takeOff without argument, which does not return anything.
    
    ascend which takes an integer meters, which returns an integer.
    
    descend which takes an integer meters, which returns an integer.
    
    land without argument, which does not return anything.
    
    glide, without argument, which returns nothing and has a default behavior: display the text "It glides into the air."
    
* Have the interface implemented Fly by the class Eagle.

    You will be able to decide the behavior of the methods, but it is mandatory that each method display some text in the         console.
    
    You can inspire you for the implementation of Swim a Penguin.
    
* Discards the call of the methods of Eagle in Nature.

* Compile and test Nature: when everything works, create a git repository and send it all to GitHub.

* Share the GitHub repository link in solution.

                                        ____________________________________________  
                                        
Example of result when running Nature:

$ Eye Cherry takes off in the sky.

$ Eye Cherry flies upward, altitude : 120.

$ Eye Cherry flies upward, altitude : 150.

$ It glides into the air.

$ Eye Cherry flies downward, altitude : 10.

$ Eye Cherry is too high, it can't lands.

$ Eye Cherry flies downward, altitude : 1.

$ Eye Cherry lands on the ground.

}
