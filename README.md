# Graphichs computer course

![Imagen 1](https://github.com/dgonzalezt2/Graphics_Computer/assets/81880494/014287a9-ae73-4cbc-8183-241389e98f7d | width=100)

![Imagen 2](https://github.com/dgonzalezt2/Graphics_Computer/assets/81880494/82ad12b5-bb39-474d-b3e1-72922c46e160 | width=50%)

# Members
* [David Gonzalez](https://github.com/dgonzalezt2)
* [Hobarlan Uparela](https://github.com/huparelaa)

## Content:
* [Bresenham](#Bresenham)
* [Images from text file](#Draw-from-text-file)
## How to run it?
Before run the commands make sure you are not in a specific directory
### Bresenham
```bash
javac bresenham/Bresenham.java
javac bresenham/Main.java 
java bresenham.Main
```

### Draw from text file
```bash
javac drawFromTextFile/PaintObject.java
javac drawFromTextFile/Main.java
java drawFromTextFile.Main
```
If you want to draw the other object you only need to change this line in PaintObject.java line 22:
```java
readFile("drawFromTextFile/gancho.txt", g);
```
into this:
```java
readFile("drawFromTextFile/house.txt", g);
```
