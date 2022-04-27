# Java Code Academia

## A3: This or That?

### Backstory
Your local city wants to create a new Dating game show. The idea behind the game show is simple - 
They have a woman who is looking for someone to date with, and they let this woman answer 10 questions - all "This or That" questions.

Then they bring in the men playing the game, who need to answer those exact same questions. If they choose the same answer that the woman chose, they get to play on. If they choose the other one - they're out!

### Assignment
Create a java program that asks a series of "This or That" questions from users. The correct answers can be coded in the program - no need to ask what is correct.

If the user answers correctly (the same answer that the woman chose), they get to play on. If they chose the other answer, the program finishes and prints out "Sorry, wrong answer!"

Bonus:

1) If the correct answer is car and user inputs CAR or Car or caR, it should be correct.

### Sample input / output:
#### Sample 1
```java
TV series or Movies?: Movies
Correct!
Car or motorcycle?: Car
Correct!
Bus or Train?: Train
Correct!
...
... // More questions here... to which user answers correctly
...
Congratulations! You found your match!
Process finished with exit code 0
```

#### Sample 2
```java
TV series or Movies?: Movies
Correct!
Car or motorcycle?: Car
Correct!
Bus or Train?: Bus
Sorry, wrong answer!
Process finished with exit code 0
```

### Hints
<details>
<summary>Hint 1</summary>
To store correct answers, you can use an array
For example:

```java
 String[] correctAnswers = new String[] {"Movies", "Car", "Bus"};
 ```
</details>
<details>
<summary>Hint 2</summary>
You can exit the program with:

```java
 System.exit(0);
 ```
</details>
<details>
<summary>Hint 3</summary>
You can make a string to lower case letters by using the method .toLowerCase();

This way you can compare two strings so CAR is also a correct answer to "car"

```java
 String text = "HELLO WORLD";
 System.out.println(text.toLowerCase());
 ```
</details>