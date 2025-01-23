# Run-time-polymorphism
package polymorphismdemo;
class Animal {
    void sound(){
        System.out.println("Animal makes a sound");
        
    }
}
class Dog extends Animal{
    void sound(){
        System.out.println("Dog barks");
    }
}
class Cat extends Animal{
    void sound(){
        System.out.println("Cat meows");
        
    }
}
/**
 *

 */
public class PolymorphismDemo {


    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        Animal animal;
        animal=new Dog();
        animal.sound();
        
        animal=new Cat();
        animal.sound();
        // TODO code application logic here
    }
    
}
OUTPUT:
Dog barks
Cat meows
BUILD SUCCESSFUL (total time: 0 seconds)








