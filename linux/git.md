### Questions

1. All of files have difference between working directory and the repository.

Reason: Line endings between CRLF and LF.

Solution: Set core.autocrlf to ignore the difference.

[Todo](../Todo.md#Todo): Exact meaning between true and input for autocrlf

```bash
git config --global core.autocrlf true
```
