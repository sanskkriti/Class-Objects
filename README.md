# Class-Objects
Everything in C++ is associated with classes and objects, along with its attributes and methods. For example: in real life, a car is an object. The car has attributes, such as weight and color, and methods, such as drive and brake.





# **AIM**

Classes-and-Objects

## **THEORY**


Attributes and methods are basically variables and functions that belongs to the class. These are often referred to as "class members".

A class is a user-defined data type that we can use in our program, and it works as an object constructor, or a "blueprint" for creating objects.

Create a Class

To create a class, use the class keyword:

Example

Create a class called "MyClass":

class MyClass  // The class

{      

  public:  // Access specifier
    
    int myNum;        // Attribute (int variable)
    
    string myString;  // Attribute (string variable)

};

Create an Object
In C++, an object is created from a class. We have already created the class named MyClass, so now we can use this to create objects.

To create an object of MyClass, specify the class name, followed by the object name.

To access the class attributes (myNum and myString), use the dot syntax (.) on the object:

Example

Create an object called "myObj" and access the attributes:

class MyClass {       // The class
 
  public:             // Access specifier
   
    int myNum;        // Attribute (int variable)
    
     string myString;  // Attribute (string variable)

};

int main()
{
  
  MyClass myObj;  // Create an object of MyClass

  // Access attributes and set values
  
  myObj.myNum = 15; 
  
  myObj.myString = "Some text";

  // Print attribute values
 
  cout << myObj.myNum << "\n";
 
  cout << myObj.myString;
 
  return 0;

}


## **ALGORITHM**

- **Find the volume of cube**
  
The code you provided defines a C++ class named cuboid to represent a cuboid (a 3D rectangular shape) with default values for its height, width, and length. It then calculates and prints the volume of the cuboid in the main function. Here's an algorithmic description of the code:

1.Include the necessary header file for input and output operations, i.e., <iostream>.

2.Declare the use of the std namespace to avoid having to prepend std:: before standard library objects like cout.

3.Define a class named cuboid with the following public data members:

- double height with a default value of 2.0.
- double width with a default value of 3.0.
- double length with a default value of 5.0.

4.In the main function:

5.Create an instance of the cuboid class named c1.

6.Calculate the volume of the cuboid using the formula volume = height * width * length, where height, width, and length are the data members of the c1 object.

7.Store the calculated volume in a double variable vol.

8.Print the calculated volume using cout.

- **Write a function to display output**

1.Include the necessary header file for input and output operations, i.e., <iostream>.

2.Declare the use of the std namespace to avoid having to prepend std:: before standard library objects like cout.

3.Define a class named cuboid with the following public data members:

- float l with a default value of 3.0 (length).
- float w with a default value of 5.0 (width).
- float h with a default value of 7.0 (height).

4.Define a member function display that takes a float parameter a (representing the volume of the cuboid) and displays the volume using cout.

5.In the main function:

6.Create an instance of the cuboid class named c1 with default dimensions.

7.Calculate the volume of the cuboid using the formula volume = length * width * height, where length, width, and height are the data members of the c1 object.

8.Store the calculated volume in a float variable vol.

9.Call the display member function of the c1 object, passing vol as an argument to display the volume.

- **Take input from user**

1.Include the necessary header file for input and output operations, i.e., <iostream>.

2.Declare the use of the std namespace to avoid having to prepend std:: before standard library objects like cout.

3.Define a class named cuboid with the following public member functions:

4.float calculate(float a, float b, float c): This function takes three float parameters representing the length, breadth, and height of the cuboid, calculates the volume using the formula volume = a * b * c, and returns the calculated volume as a float.

5.float display(float a): This function takes a float parameter a (the calculated volume) and displays it using cout.

6.In the main function:

7.Create an instance of the cuboid class named c1.

8.Declare float variables l, b, and h to store the length, breadth, and height of the cuboid.

9.Prompt the user to enter the length, breadth, and height of the cuboid.

10.Read the values entered by the user into the variables l, b, and h.

11.Calculate the volume of the cuboid by calling the calculate member function of the c1 object, passing l, b, and h as arguments, and store the result in the variable vol.

12.Call the display member function of the c1 object, passing vol as an argument, to display the calculated volume.

- **shapes_vol_class**

1.Include the necessary header file for input and output operations, i.e., <iostream>.

2.Declare the use of the std namespace to avoid having to prepend std:: before standard library objects like cout.

3.Define a class named shapes with the following public data members for dimensions of various shapes:

double h, double wid, double len for a cuboid.
double s for a cube.
double r for a sphere.

4.Define constructors for each shape:

cuboid(): Prompt the user to enter the dimensions (height, width, length) of a cuboid and read them into the respective class members.

cube(): Prompt the user to enter the dimension (side length) of a cube and read it into the class member.

sphere(): Prompt the user to enter the dimension (radius) of a sphere and read it into the class member.

5.Define member functions to calculate the volume of each shape:

double cuboid_volume(): Calculate the volume of the cuboid using the formula volume = h * wid * len, display it, and return the volume.

double cube_volume(): Calculate the volume of the cube using the formula volume = s * s * s, display it, and return the volume.

double sphere_volume(): Calculate the volume of the sphere using the formula volume = 4/3 * π * r^3, display it, and return the volume.

double cone_volume(): Calculate the volume of the cone (although the formula is incorrect, it should be fixed), display it, and return the volume.

5.In the main function:

Create instances of the shapes class for a cuboid, cube, and sphere.

Use the constructors to input the dimensions of each shape.

6.Calculate the volumes of each shape using their respective member functions and store the results in variables vCu, vC, and vS.

## **OUTPUT**

![Screenshot 2023-10-18 at 10 05 06 PM](https://github.com/sanskkriti/Class-Objects/assets/140137289/5cd13039-0161-49fb-b895-707de748c20b)



![Screenshot 2023-10-18 at 10 05 12 PM](https://github.com/sanskkriti/Class-Objects/assets/140137289/6561f28b-b0bb-4aab-b1c6-cf6f99b85e0d)



![Screenshot 2023-10-18 at 10 05 27 PM](https://github.com/sanskkriti/Class-Objects/assets/140137289/bc6d67e9-a13c-48b4-8f0b-a624f49c0832)
