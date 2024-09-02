# Branchline Test Template

```cpp
void autonomous() {
  pros::Motor left(1);
  pros::Motor right(-2);

  right.move_relative(1000, 100);
  left.move_relative(1000, 100);
}
```
