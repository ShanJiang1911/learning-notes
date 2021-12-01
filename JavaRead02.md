## [Packages and imports](https://perso.ensta-paris.fr/~diam/java/online/notes-java/language/10basics/import.html)
* Java classes can be grouped in packages
* The first statement in a Java source file must be the package declaration
* Try not to use default packages
* Three options of Imports:
  * import javax.swing;
  ```
  class ImportTest {
    public static void main(String[] args) {
        JOptionPane.showMessageDialog(null, "Hi");
        System.exit(0);}
    }
  ```
  * import javax.swing.JOptionPane;
  ```
  class ImportTest {
    public static void main(String[] args) {
        JOptionPane.showMessageDialog(null, "Hi");
        System.exit(0);
    }
  }
  ```
  * fully qualified class name without an import;
  ```
  class ImportTest {
    public static void main(String[] args) {
        javax.swing.JOptionPane.showMessageDialog(null, "Hi");
        System.exit(0);
    }
  }
  ```
* Common imports:   
  ```
  import java.awt.*;	Common GUI elements.
  import java.awt.event.*;	The most common GUI event listeners.
  import javax.swing.*;	More common GUI elements. Note "javax".
  import java.util.*;	Data structures (Collections), time, Scanner, etc classes.
  import java.io.*;	Input-output classes.
  import java.text.*;	Some formatting classes.
  import java.util.regex.*;	Regular expression classes.
  ```
## [Different types of loops in Java](https://www.baeldung.com/java-loops)
 * [For Loop](https://www.baeldung.com/java-for-loop)
 * [While Loop](https://www.baeldung.com/java-while-loop)
 * [Do-While Loop](https://www.baeldung.com/java-do-while-loop)
 * [Examples on GitHub](https://github.com/eugenp/tutorials/tree/master/core-java-modules/core-java-lang-syntax)


[<--Back](README.md)