# Simple Border Layout in java

This project demonstrates a basic graphical user interface (GUI) in Java using Swing components like `JFrame`, `JPanel`, and the `BorderLayout` from the Swing library. The main window is divided into five primary panels, each with distinct colors and sizes. The center panel includes a nested layout with five sub-panels arranged using `BorderLayout`, showcasing the versatility of nested layouts in Swing.

The project serves as an excellent introduction to Swing's layout managers, panel customization, and nested GUI components, making it suitable for learning and experimenting with Java GUI design.



-----------

## Features
- A main window (`JFrame`) with a `BorderLayout`.
- Five main panels, each styled with distinct background colors and dimensions.
- The center panel contains a nested `BorderLayout` with five sub-panels, each styled differently.
- Easy-to-understand code, ideal for beginners learning Swing and GUI layout techniques.

--------

## Project Structure
The GUI layout is divided as follows:
1. **Main Panels:**
   - **Panel 1:** Positioned at the top (`NORTH`) with a red background.
   - **Panel 2:** Center panel (`CENTER`) containing five sub-panels.
   - **Panel 3:** Positioned at the bottom (`SOUTH`) with a yellow background.
   - **Panel 4:** Positioned to the right (`EAST`) with a magenta background.
   - **Panel 5:** Positioned to the left (`WEST`) with a blue background.

2. **Sub Panels within Panel 2:**
   - **Panel 6:** Center sub-panel with a gray background.
   - **Panel 7:** Bottom sub-panel with a dark gray background.
   - **Panel 8:** Right sub-panel with a pink background.
   - **Panel 9:** Left sub-panel with an orange background.
   - **Panel 10:** Top sub-panel with a light gray background.

-------------

## Prerequisites
- Java Development Kit (JDK) 17 or later.
- A Java IDE or text editor (e.g., IntelliJ IDEA, Eclipse, or VS Code).

-------------

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/saharzakersoltani/java-swing-gui-demo.git
   cd java-swing-gui-demo

2. Compile the code:
   ```bash
   javac Main.java
   ````

3. Run the program:
   ```bash
   java Main
   ```
-----------

## Use Case
This project is an excellent resource for:

- Beginners exploring Java Swing.
- Developers needing a foundation for building complex GUI applications.
- Experimenting with nested layouts and panel customization.

