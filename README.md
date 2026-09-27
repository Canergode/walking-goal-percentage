## What I Learned

- How to calculate a percentage using integer arithmetic (`(steps_taken * 100) / target_steps`)
- How to classify a percentage into three feedback tiers using `if / else if / else`
- How the order of comparisons (checking `>= 100` before `>= 50`) ensures only the correct message is printed
- How a single calculated value can drive both a conditional message and a final status line

## Note
If `target_steps` is entered as `0`, this program will attempt a division by zero, which causes undefined behavior in C. Adding a check for `target_steps == 0` before the calculation would make this safer.
