
# rock_paper_scissors
- below are two solutions for the bonus in the classwork





## If conditions/statements (covered in class)
-Simply covering all the cases where player 1 wins or draws ONLY, becuase everything else means player 2 wins.

```dart
  if (random1 == random2) {
    winner = "Draw";
  } else if (random1 == 1 && random2 == 3) {
    winner = "Player 1 wins!";
  } else if (random1 == 2 && random2 == 1) {
    winner = "Player 1 wins!";
  } else if (random1 == 3 && random2 == 2) {
    winner = "Player 1 wins!";
  } else {
    winner = "Player 2 wins!";
  }
```


## Ternary operator (not covered in class)
-This is a special syntax called ternary operator, another way of writing if statements (for fun).<br />
-Below the solution is a breif explanation on how it works.

```dart
 winner = random1 == random2
      ? "Draw"
      : random1 == 1 && random2 == 3
          ? "Player 1 wins!"
          : random1 == 2 && random2 == 1
              ? "Player 1 wins!"
              : random1 == 3 && random2 == 2
                  ? "Player 1 wins!"
                  : "Player 2 wins!";
```

- ? is asking a question.<br />
- : means else/else if.<br />
```dart
condition ? expressionOne : expressionTwo;
```
- Simply we're saying if the condition is true, do ```expressionOne``` else do```expressionTwo```.

##### Example 1
```dart
int age = 30;

age == 30 ? print("Yes") : print("No");
//The output would be "Yes" in this case.
```

##### Example 2
```dart
int age = 30;

age == 25 ? print("Yes") : print("No");
//The output would be "No" in this case.
```
