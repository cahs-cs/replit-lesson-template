# Extension Activity

## Colors

Colors are not that hard to add to your program, it just looks SUPER weird.

Explore this website to see a few ways to add color to your console:

- [https://linuxhint.com/print-colored-text-python/](https://linuxhint.com/print-colored-text-python/)

The top section goes over ANSI escape sequences, but there are easier ways if you scroll down.

## ANSI Escape Sequences

Here is a link to a ANSI escape sequence cheat sheet. Feel free to reference it when modifying this code.

[https://www.oreilly.com/library/view/bash-cookbook/0596526784/apas03.html](https://www.oreilly.com/library/view/bash-cookbook/0596526784/apas03.html)

Here is some starter code that will start printing blue text to the console:

```py
print("\033[34m")
print("I am blue")
```

The number `34` is what says to set the color to blue. You will always need to start these escape sequences with `\033[` and end with an `m`. just add numbers in the middle to set different flags.

based on the table above you could set the text to be underlined, red, and have a white background with the following:

```py
print("\033[4;31;47m")
print("well formatted")
```

The only thing to add here is that EVERYTHING will be formatted until you reset the formatting with the following sequence

```py
print("\033[0m")
```

## Extension Activity

Look up examples of [ASCII art](https://www.google.com/search?q=ascii+art&client=firefox-b-1-d&sxsrf=ALiCzsYtM27g1EHn6WjY4NDg6-Qq892EIA:1667949117137&source=lnms&tbm=isch&sa=X&ved=2ahUKEwi7mYXV2p_7AhUUO30KHV-KBXcQ_AUoAXoECAIQAw&biw=1620&bih=947&dpr=2).

See if you can recreate anything, or even come up with your own!
