## Aliaksandr Tarhonski

### Contacts
- __Email__: stdmnstar@gmail.com
- __Tel__: +375 44 739 4747

### Summary
I started programming early. Then I studied at a higher educational institution as a mathematician-programmer. However, it so happened that I had to graduate from another educational institution as a radio engineer. But over time, I moved on to work as an administrator of networks, servers. This is what I have been doing for the last 13 years. But I would like to really do programming.

### Skills
Java, MS SQL, PosgreSQL, MS Server, 1C.....

### Code samples
```java
public class MainClass {
   public static void main(String[] args) {
      int nDisks = 3;
      doTowers(nDisks, 'A', 'B', 'C');
   }
   public static void doTowers(int topN, char from,
   char inter, char to) {
      if (topN == 1){
         System.out.println("Disk 1 from "
         + from + " to " + to);
      }else {
         doTowers(topN - 1, from, to, inter);
         System.out.println("Disk "
         + topN + " from " + from + " to " + to);
         doTowers(topN - 1, inter, from, to);
      }
   }
}
  ```
 ### Experience
- course Java (2017)

### Education
- Military Academy of the Republic of Belarus (radio engineer)

 ### English 
 level is A2
