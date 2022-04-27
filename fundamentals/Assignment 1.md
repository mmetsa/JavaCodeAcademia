# Java Code Academia

## A1: “ECHO… Echo… echo…”

### Backstory:
You’re in a spacecraft, and in order to measure how far you are from earth, your vehicle sends out an “echo” message towards the Earth, and immediately when the Earth people get the “echo”, they send one back. This is called the “Echo protocol”. You’re a junior programmer, and your job is to automate this echo process.

### Assignment:
Create a java program that asks user for input, and prints out the same input to them.

### Sample input / output:
```java
Enter input: Echo
Echo
Process finished with exit code 0
```

### Hints:
<details>
<summary>Hint 1</summary>
You can read user input with the Scanner object

```java
Scanner input = new Scanner(System.in);
input.nextLine();
```
</details>
<details>
<summary>Hint 2</summary>
You should save the user input in a variable, and print that variable

```java
String in = input.nextLine();
System.out.println(in);
```
</details>