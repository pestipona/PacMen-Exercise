# PacMen Exercise

![](images/PacMan1.png)

## I. Project Description:

This exercise is based on the old classic 80's game of **PacMan**. However, this project does not build the full PacMan game but it just shows a feature of the game. Where the PacMan character is displayed on a web browser and bounces off from one side to the other. The program also allows user interaction by allowing the user to create more PacMen that would each behave similarly but move in different directions.

This project is more about demonstrating the basic use and concepts of ```JavaScript```, ```HTML```, and ```CSS``` which are commonly used in today's **web pages** and **front-end applications**. One of the **key concepts** used in this example are the use of ```setTimeout```,  ```setInterval``` and ```checkPageBounds``` methods.

## II. SetTimeout vs SetInterval:

There are **multiple ways** of **solving a problem**, and one of these is choosing between ```setTimeout``` or ```setInterval``` to call on a function every few seconds to make the PacMan object move across the screen.

As per **Mozilla's Web Documents** the following are the definitions for each of the methods:

* [setTimeout()](https://developer.mozilla.org/en-US/docs/Web/API/setTimeout) sets a timer which executes a function or specified piece of code once the timer expires.

* [setInterval()](https://developer.mozilla.org/en-US/docs/Web/API/setInterval) repeatedly calls a function or executes a code snippet, with a fixed time delay between each call.

As you can see **both methods** can be used in this program which would give the same exact results. It is up to the developer to choose which method he or she is comfortable with to use in this program. For this exercise, the ```setTimeout()``` method was used.

## III. How to Run:

The first step would be to **clone the repository** to your local machine by going to the **Project's ReadMe Page** and selecting ```<> Code``` and copy the **project URL** which is the following.

```text
 https://github.com/pestipona/MIT-MOD4.5-PacMan-Coding-Assignment.git
```

The next steps to **clone the repository** would depend on the local machine's **Operating System (OS)** whether it be ```Windows```, ```Mac```, or ```Linux```. Some of the steps or commands may vary but there are some similarities. Here is an overall guide based on an article posted in GitHub Docs.

[Cloning a repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository?platform=linux)

After **cloning the repository** navigate to the **directory location** of the files for the project. Look for the ```index.html``` file which is the HTML file of the program. Open any web browser such as ```Chrome``` or ```Firefox``` and drag and drop the ```index.html``` file into the browser. This initializes and runs the program.

Select the ```Add PacMan``` button to create a PacMan Object, then select the ```Start Game``` button to make the PacMan object move. You can add as many PacMan objects as you want just by clicking on the ```Add PackMan``` button many times and observe all the PacMen objects move across the screen as shown in the following video. To close the program just simply close the web browser running the application.

https://user-images.githubusercontent.com/88525094/208303936-4fc4509a-b9b4-46eb-b387-d113cf36eed9.mp4          

Make sure also that the ```pacmen.js``` file is in the same directory of the ```index.html``` file for the program to work.

### III.A. Roadmap for future improvements:

This program has a lot of great potential and my future plans for this project is to add more features to enhance the program. Such as making the PacMan object resize its shape once it bounces off the wall to make it look like its getting "squished". Or even make the PacMan move its mouth open and close as it moves across the screen just like the classic game.

### III.B. License Information:

The following [document](./LICENSE) shows licensing information from MIT about the program.
