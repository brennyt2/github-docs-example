# Writing Good Documentation

## Step 1 - Using Codeblocks

Codeblocks in markdown make it *very easy* for technical people to **copy, paste, share** code.
A good Cloud Engineer uses Codeblocks whenever possible.

It allows others to copy and paste their code to replicate or research issues.
In order to use codeblocks in markdown, you need to use three backticks (on the left of 1 on keyboard and above the TAB key)

```
# This program prints Hello, world!

print('Hello, world!')
```

- When you can, attempt to apply syntax highlighting

```Python
# This program prints Hello, world!

print('Hello, world!')
```

![Screenshot_9](https://github.com/brennyt2/github-docs-example/assets/101442077/2178ae57-a507-45f7-88d7-1d709f2b9cec)

Good Cloud Engineers use codeblocks for both code and errors that appear in Bash.
```Bash
/Users/myname/Documents/MyPythonScript/hello.py: line 3: syntax error near unexpected token `'Hello world''
/Users/hadi/Documents/MyPythonScript/hello.py: line 3: `print('Hello world')'
```
> Here is an example of an error

## Step 3 - Use Github flavoured markdown task lists
Github extends markdown to have a list where you can check off items.<sup>3</sup>
- [x] Finish Step 1
- [ ] Finish Step 2
- [ ] Finish Step 3

## Step 4 - Use emojis
Github Flavoured Markdown(GFM) supports emojis
:cloud:
:star:

## References
- [Terraform reference link](https://app.exampro.co/student/material/terraform-cpb/5351) <sup>1</sup>
- [Stack Overflow link](https://stackoverflow.com/questions/48926119/syntax-error-on-bash-for-running-python-script) <sup>2</sup>
- [GFM - Task List](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) <sup>3</sup>
- [GTM - Emoji Cheatsheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)<sup>4</sup>
