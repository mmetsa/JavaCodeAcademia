# Java Code Academia

## A4: What's the lesson?

### Backstory
You're a student in a school. You have trouble every day remembering what lesson is currently ongoing. Your timetable looks like this:

* Lesson 1 - 8:00 - 8:45
* Lesson 2 - 8:55 - 9:40
* Lesson 3 - 9.50 - 10.35
* Lesson 4 - 10.55 - 11:40
* Lesson 5 - 12:00 - 12:45
* Lesson 6 - 12:55 - 13:40
* Lesson 7 - 13:50 - 14:35
* Lesson 8 - 14:45 - 15:30
* Lesson 9 - 15:40 - 16:25

Easy right.. Well not for you sadly. You can see on your phone that it's 12:10 but you have no idea what lesson is currently ongoing.

You want to make it so if it's currently recess (time between two lessons), it tells you what your next lesson is, or that you have no more lessons for today.

### Assignment
Create a java program that asks for the current time (24 hour format), and prints out what lesson it is based on the timetable.

If the time is between two lessons, print out the next lesson (See example below)

If there is no more lessons after the time, print out "No more lessons for today"

Bonus: Handle both types of input: 13:20 and 13.20

### Sample input / output:
#### Sample 1
```java
Enter the current time: 13:20
It is currently Lesson 6
Process finished with exit code 0
```
#### Sample 2
```java
Enter the current time: 07:25
Your next lesson is Lesson 1
Process finished with exit code 0
```
#### Sample 3
```java
Enter the current time: 12:50
Your next lesson is Lesson 6
Process finished with exit code 0
```
#### Sample 4
```java
Enter the current time: 16:50
No more lessons for today
Process finished with exit code 0
```

### Hints
<details>
<summary>Hint 1</summary>
There are many ways in java to convert a String to Date or Time, here's a simple one:

```java
 LocalTime t = LocalTime.parse( "17:40" ) ;
 ```
</details>
<details>