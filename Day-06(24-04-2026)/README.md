# Example 01
```java
import java.util.ArrayList;
import java.util.LinkedList;
import java.util.List;

public class Day6Example1 {
    public static void main(String[] args){

        //Creating a List
        List<String> fruits = new ArrayList<>();
        fruits.add("Apple");
        fruits.add("Banana");
        fruits.add("Cherry");
        System.out.println("Fruits "+ fruits);
        String firstFruit = fruits.get(0);
        System.out.println("First Fruit " + firstFruit);

        LinkedList <String> animals= new LinkedList<>();
        animals.add("Dog");
        animals.add("Cat");
        animals.add("Elephant");

        System.out.println("Animals: " + animals);

    }
}import java.util.HashMap;
import java.util.HashSet;

public class Day6Example2 {
    public static void main(String[] args){
        HashSet <String> colors = new HashSet<>();
        colors.add("Red");
        colors.add("Green");
        colors.add("Blue");
        colors.add("Red");
        System.out.println("Colors : "+ colors);

        //hash map
        HashMap<String, Integer> ageMap= new HashMap<>();

        ageMap.put("Rakibul",21);

        ageMap.put("Halima",22);

        ageMap.put("Robiul ",44);

        System.out.println("Age map: "+ ageMap);
        int RakibulAge= ageMap.get("Rakibul");
        System.out.println("Rakibul is " + RakibulAge+" years old");
    }

}
```
```
# Example 02
```java
