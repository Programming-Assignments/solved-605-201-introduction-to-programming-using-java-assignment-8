Download Link: https://assignmentchef.com/product/solved-605-201-introduction-to-programming-using-java-assignment-8
<br>
Imagine your project team is developing a Java application that will serve as an educational tool to help children learn about various concepts such as vehicles, animals, sounds, etc.  The application will have a need to draw various objects (e.g., animals, vehicles) on the video display as well as to rotate objects, resize objects, and play sounds that are associated with the objects.  Your project manager has specified that all objects in the application should use a common interface for drawing, rotating, resizing, and playing sounds, and that these interfaces should be reusable for other application projects as well.  Some future applications will need to make sounds, some will need drawing capability, some will need rotating capability, some will need resizing capability, and some will need all capabilities.  A method called drawObject() will be used for drawing objects, a method called rotateObject() will be used for rotating objects, a method called resizeObject() will be used for resizing objects, and a playSound() method will be used for playing sounds.




<ol>

 <li>Design the interface classes Drawable, Rotatable, Resizable and Sounds.</li>

 <li>Develop a program called ManipulateAnimals that does the following: An Animal class will be used to model some basic characteristics of animals for the application. An animal will have a name attribute and methods to set the name and get the name.  Animals can make sounds and are drawable, rotatable, and resizable.  A Vehicle class will be used to model some basic characteristics of vehicles.  A vehicle will have a name and an age, and methods to get/set these attributes.  Vehicles can also make sounds and are drawable, rotatable, and resizable. Create a collection of 2 vehicles and 2 animals stored in the same array.  Loop through the array and execute the drawObject(), rotateObject(), resizeObject(), and playSound() methods polymorphically for each element in the array.  The drawObject() method should simply display the message “Drawing a Vehicle” or “Drawing an Animal”; the rotateObject() method should display the message “Rotating a Vehicle” or “Rotating an Animal”; and the playSound() method should display the message “Animal sound” or “Vehicle sound”, depending upon the type of element that is in the array.  The resizeObject() method should display “Resizing a Vehicle” or “Resizing an Animal”.</li>

</ol>




Submit the source code and  screen shots of the program output in a zip file named as follows: Assignment8 followed by an underscore (_) followed by your first name initial, followed by your last name, followed by your course section number. For example, if your name is Jane Smith and you are in section 81 your zip file would be <em>Assignment8_jsmith81.zip</em>.