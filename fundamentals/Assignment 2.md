# Java Code Academia

## A2: The Master of students

### Backstory
You're a teacher of 6th grade class. You rarely have anything to talk in your Monday morning class, but instead of letting the students just sleep on Monday mornings, you decide to give them a little bit of motivation.

You come up with the idea that 5 of your best-learning students can take the first class off on Monday mornings. You decide who is best-learning by comparing their average grades. There's just one problem: Your school doesn't have an automated system that tells you the average grade of a student.

You certainly can't let students calculate themselves, as you know they tend to make mistakes. So instead, you decide to create a simple program to help you with that. This way, students only have to tell you how many 5's, 4's, 3's, 2's, 1's and undone work they have.

### Assignment
Create a Java program to calculate an average grade for a student. The program should take the count of each grade as an input (Undone work is marked as 'X' - so if a student was sick and couldn't do 2 tests, they have 2 'X'-s).

Your computer screen is kind of small, so if you can figure out how to round the end result to 3 numbers after comma, it would be beneficial (but not required)

### Sample input / output:
```java
Enter amount of 5's: 7
Enter amount of 4's: 7
Enter amount of 3's: 1
Enter amount of 2's: 0
Enter amount of 1's: 0
Enter amount of X's: 1
The average grade is: 4.125
Process finished with exit code 0
```

### Hints
<details>
<summary>Hint 1</summary>
You can calculate the average grade by adding together the total value of every grade times the amount and dividing it by total amount of grades

Formula: average = (5 * amount of 5's) + (4 * amount of 4's) * ... * (0 * amount of 'X's) / (amount of 5's + amount of 4's + ... + amount of 'X's)
</details>
<details>
<summary>Hint 2</summary>
You can ask for a numeric input from user as such:

```java
Scanner input = new Scanner(System.in);
int in = input.nextInt();
```
</details>