#Compilers

## What is a compiler?
* Broadly speaking, a compiler is a computer program that transforms source code (like the ```.java``` files you will write for class) written in a programming language such as Java, C, or C++, into a lower level language that computers can understand (e.g. machine code or assembly language). 
* The reason that you have compile-time errors is that this is the point when the compiler is translating the source code into machine code-- if you have a set of instructions that doesn't make sense in one language, it follows that they will generate an error in translation. 

## How does this work in Java?
* When you compile your code, the job is done by the Java compiler, which takes in your ```.java``` files and spits out ```.class``` files, which contain Java bytecode. 
* The Java Virtual Machine (JVM) loads the class files and compiles it to machine code which is read by your hardware.
* Note: Java bytecode is universal, but your JVM is machine-specific.


To run a Java program
``` java
javac Test.java   // compile .java files into .class files (containing bytecode) for the JVM
java Test         // invoke the Java virtual machine with the command java
```       
