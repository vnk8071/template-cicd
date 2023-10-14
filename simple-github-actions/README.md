# Simple-github-actions
This action prints "Hello Github User" and my information to the log or "Hello" + the name of a person to greet.
```
.github/workflows/simple-github-actions.yml
```
Include:
- action.yml: Define inputs, outputs and run Docker
- Dockerfile: Build image and run container
- entrypoint.sh: Bash script of show console log

![build_action_simple](https://user-images.githubusercontent.com/78080480/242916392-63da4d8e-2c99-4159-94a3-c27bf1a096f5.png)