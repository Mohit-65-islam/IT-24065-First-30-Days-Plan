# Example01
```java
import java.util.HashSet;

public class Example1 {
    public static void main(String[] args) {
        HashSet<Integer> set = new HashSet<>();
        set.add(5);
        set.add(10);
        set.add(5);
        set.add(20);

        for (int num : set) {
            System.out.println(num);
        }
    }
}
```
# Example 02
```java
import java.util.TreeSet;

public class Example2 {
    public static void main(String[] args) {
        TreeSet<String> set = new TreeSet<>();
        set.add("Banana");
        set.add("Apple");
        set.add("Mango");
        set.add("Apple");

        for (String item : set) {
            System.out.println(item);
        }
    }
}
```
