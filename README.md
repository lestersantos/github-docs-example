# Writing Good Documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code.
A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it allows other to copy and paste their code to replicate or research issues.

- In order to create codeblocks in markdown you need to use three backticks (`).
- Not to be confused with quotations (').

```
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

# Test the factorial function
number = 5
result = factorial(number)
puts "The factorial of #{number} is #{result}"
```

- When you can you should attempt to apply syntax highlighting to your codeblocks.

```ruby
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

# Test the factorial function
number = 5
result = factorial(number)
puts "The factorial of #{number} is #{result}"
```
- With markdown, cannot resize an image
![Showing an image, added to the Markdown, of a cat.](https://github.com/lestersantos/github-docs-example/assets/30423581/64ca0e01-37fc-438b-b14d-47f65593db1a)

- With html image resized
<img src="https://github.com/lestersantos/github-docs-example/assets/30423581/64ca0e01-37fc-438b-b14d-47f65593db1a" width="300px"/>

Good Cloud Engineers use codeblocks for both Code and Errors that appears in the console.

```bash
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
NameError: undefined local variable or method `undefined_variable' for main:Object
```
> Here is an example of using a codeblock for an error that appears in bash.

## Step 3 - Use Github Flavoured Markdown Task Lists

Github extends Markdown to have a list where you can check off items. [<sup>[1]</sup>](#references)

- [x] Finish Step 1
- [ ] Finish Step 2
- [x] Finish Step 3

## Step 4 - Use Emojis (Optional)

GitHub Flavored Markdown (GFM) supports emojis shortcodes.
Here are some examples:

| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | ☁️ |
| Cloud with lighting | `:cloud_with_lightning:` | 🌩️|

☁️ :cloud:

## Step 5 - how to create a table

You can use the following markdown format to create tables:

~~~md
| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | ☁️ |
| Cloud with lighting | `:cloud_with_lightning:` | 🌩️|
~~~
Github extends the functionality of Markdown tables to provide more alignment and table cell formatting options.[<sup>[2]</sup>](#references)
## References

- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/)
- [Basic writing and formatting syntax(Github Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#quoting-text)
- [GFM - Task Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists) <sup>[1]</sup>
- [GFM - Emoji Cheatsheet](https://github.com/ikatyang/emoji-cheat-sheet)
- [GFM - Tables (with extensions) ](https://github.github.com/gfm/#tables-extension-). <sup>[2]</sup>
