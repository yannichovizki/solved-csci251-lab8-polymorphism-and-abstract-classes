Download Link: https://assignmentchef.com/product/solved-csci251-lab8-polymorphism-and-abstract-classes
<br>
Following completion of this task, students should be able to:

<ul>

 <li>Write C++ programs using polymorphism and abstract classes.</li>

</ul>

Question 1 (Polymorphism and abstract classes)

Declare and implement an abstract class called Car. The Car class should have the car registration number and the number of miles the car has traveled. Include in the class a function to set the car registration number, a function to increase the miles traveled by receiving the number of miles traveled in the last trip, an accessor function to return the car registration number, another accessor function to return the miles traveled, and a display function that will be implemented by the derived classes of Car.

Declare and implement a derived class from Car called RaceCar that has an additional data member called racingType that may have values such as track racing, off-road racing, drifting, or kart-racing. Include a constructor to initialize its data member as well as to set the derived data members from the Car class. Implement a display function for the RaceCar class to display all its details.

Declare and implement a second derived class from Car called MPV that has an additional data member called capacity that represents the number of people that can fit into the car. Include also a constructor to initialize its data member as well as to set the derived data members from the Car class. Implement a display function for the MPV class to display all its details.

<h1>Question 2 (Polymorphism and abstract classes)</h1>

Define three classes with the following relationships:

Animal should be abstract. It should hold two data members, name and size to keep the weight of the animal. Reptile should have habitat as data member to keep information of the habitat such as land, salt water, fresh water, etc Lastly, Snake should be a class with poisonous as data member to indicate whether it is poisonous or not.

There should be a showInfo() function which is overridden through the hierarchy.  It should provide appropriate information about the objects.  Classes Reptile and Snake should have a non-default constructor to initialize the data members, while Animal needs a function to set its data member.

The main() function should construct 2 instances each of Reptiles and Snake.  These should be stored in an array of type Animal.  A loop should be used to output information on all the objects, producing something like:

———————

Crocs weighs 225 kg and lives in salt water

———————

Lizards weighs 0.005 kg and lives on land ———————

Cobra weighs 9 kg and lives on land. It is very poisonous.

———————

Anaconda weighs 300 kg and lives in swamps

———————





