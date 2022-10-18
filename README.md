# Exercise Sheet 01
The first exercise will get you to know the Hamster Simulator – a Mini Programming World with a protagonist named Paule.
Paule is a hamster that can be controlled programmatically.
Starting with the basic implementation you see in this repository, you will learn how to implement new features throughout the course.


# How to use
To install Java, set up your Integrated Development Environment (IDE), and clone the repository into your workspace, please follow the instructions in "exercise sheet, Part 0 - Preparation".

### Run the project in IntelliJ
- First, make sure again to have the correct Java version set in your project:
  Go to `File` > `Project Structure...`
  In `Project Settings` > `Project` > `SDK` select `Java 17`.
- In the menu, Go to `Run` > `Edit Configurations...`, click on the plus icon and select `Application`.
- Give it a name, e.g., "HasterSimulator"
- Now, you have to select the Main class, i.e., the starting point for running the application.
  To do so, under `Build and Run`, click on `Main class` (or the dollar sign to the right) and select the class `FirstHamsterGameApp`.
- Start the Hamster Simulator by hitting the "Play Button" in the top right corner or in the menu under `Run` > `Run 'HamsterSimulator'`.

### Run the project in Eclipse
- First, make sure again to have the correct Java version set in your project:
  Go to `Eclipse` > `Preferences` > `Java` > `Compiler` and set the `Compiler compliance level` to `17`.
- Start the Hamster Simulator by hitting the "Play Button" in the top left corner or in the menu under `Run` > `Run`.

### Run the project via command line:
- Make sure to have set the correct Java version.
  Test with running ```java -version```
- Start app using Maven:
  ```mvn compile exec:java```
