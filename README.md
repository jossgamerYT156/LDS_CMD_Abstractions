# LDS Commands Abstraction
A collection of abstracted commands used by Lilly.

# Abstractors:
## buildall
Helps abstract `clear && make -j$(nproc)` into a single command, because Lilly is lazy and likes single-command execution.

## sys

Helps getting basic system info like `installed ram`, `os release` and used `cmdline`.

## ginit

More complex command to abstract `git init` with a more structured i/o in a single command.

yes, lilly is THAT lazy.