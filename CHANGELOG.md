## 7d501b8 - rlaehd62, 2 days ago

feat(Application): add StringCalculator in main method.

## 856111b - rlaehd62, 2 days ago

docs(CHANGELOG): add CHANGELOG.md

## 982bdc1 - rlaehd62, 2 days ago

feat(calculator): add StringCalculator class for numeric addition
add StringCalculator class which implements Calculator interface.
it use pipeline strategy to check availability of calculation.
it calculates sum of numbers by using tree structure.

## f76198e - rlaehd62, 2 days ago

feat(calculator): add abstract calculator interfacce.
add abstract calculator interface to be used as fundamental
By using the interface, we could increase flexibelity of the software.

## 805adc4 - rlaehd62, 2 days ago

feat(pipeline): add default pipeline class
add default pipeline class, which is consist of three filters.
it ensures that calculation works without any exceptions.
And it could expends its pipeline without side-effect.
Order: Preprocess -> Syntax check -> calculation check.

## b7592fa - rlaehd62, 2 days ago

feat(pipeline): add abstract pipeline class.
add abstract pipeline class to be used as fundamental.
it makes linked list so that it could check validity in a row.
linked list is consist of filter classes we define.

## fd69899 - rlaehd62, 2 days ago

feat(filter): add a filter for calculation error
add a SplitCheckFilter to ensure that it's available to calculate.
it splits whole input by delimiter and comma to make expression tree.
it can check its validity by traversing expression tree.

## 11461f7 - rlaehd62, 2 days ago

feat(filter): add a filter for error detection.
add a FormatCheckFilter to detect and alert syntax error.
it's placed right after preprocessing filter.
it enables detecting syntax erorr made in the previous step.

## 365504b - rlaehd62, 2 days ago

feat(exception): add custom exception classes.
add custom exception classes to recognize the major cause more easily.
IllegalFormatException is used for the preprocessing filter.
InvalidException is used when it's related to operations.
IllegalInputException is used inside the calculator feature.

## dd13c6b - rlaehd62, 2 days ago

docs(README): add new feature into list
add an exception feature to make error managment more clear.
we handle exceptions using custom exception class.

## 4553c68 - rlaehd62, 2 days ago

feat(filter): add filter for preprocessing
add a filter for preprocessing.
it automatically detects custom delimeter sytax using regular expression.
And it configures the delimiter and remove the whole syntax from input.

## 9d16307 - rlaehd62, 2 days ago

feat(filter): add abstract filter class
add abstract filter class to be used as fundamental.
filters have link to another filer, so that It could flow using link.

## 1c16a1f - rlaehd62, 2 days ago

feat(configuration): add config management
add config bean to handle common property in many other instances.

## d011c87 - rlaehd62, 2 days ago

docs(README): define features to be implemented

## d0a82b7 - woowabrie, 5 days ago

feat: setup project

