# Branchline Test Template

```bash
curl --location --request POST 'http://127.0.0.1:8000/submit?url=https%3A%2F%2Fgithub.com%2Fmayankpatibandla%2Fbranchline-test-template&tag=1.1.1'
```

```cpp
void autonomous() {
  pros::Motor left(1);
  pros::Motor right(-2);

  right.move_relative(1000, 100);
  left.move_relative(1000, 100);
}
```
