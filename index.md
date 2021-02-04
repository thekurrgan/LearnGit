---
title: LearnGit
layout: default
nav_order: 1
---

Want to git gud with Markdown? Try [this reference](https://www.markdownguide.org/basic-syntax/#code) or [this one](https://guides.github.com/features/mastering-markdown/).

# Book 1: Travels #
## Chapter 1: Airports ##
## Chapter 2: Train Stations ##
## Chapter 3: Catapults ##

# Book 2: Staying in one place #
## Chapter 1: The couch ##
## Chapter 2: The bed ##
## Chapter 3: How to lie down ##

Let's talk formatting. We use asterisks for this.
One is italic, two is bold, three is both.
*Italic*
**Bold**
***Both***

How can we add an image? So glad you asked! Use an exclamation mark, type a tooltip in square brackets, and then in round brackets enter the location of an image file in your repository. So here's a cat.

![His name is Utah](/images/Utah_Shocked.jpg)

What about adding something from the web? Same deal, but URL instead of pointer to your own repo.

![Canoeing](https://live.staticflickr.com/7196/6925998449_44a0d17cc9_b.jpg)

Nice.

Actually, you can add links in the same way BUT without the exclamation mark. So, here's a link to [Wikipedia](https://en.wikipedia.org/wiki/Main_Page).

Now let's make some lists!

An ordered list just uses numbers and dots.
1. Just
2. Like
3. This
4. There, see?

An unordered list uses a symbol (e.g. a dash) in 1st position. Indent items to create a nested list.
- Level 1
- Also level 1
- Another level 1
   - Ah, this is level 2
   - And so is this
      - Will this be level 3? Why, yes!
   - And back to level 2
- And back to level 1

What about adding some code? Ah-hah. Use a backtick to enclose code.
So in this sentence format something `code`.
What about including backticks within code? Use an extra backtick around the outer enclosing backticks.
``So in this sentence format something 'code'.``
For a whole block, add 4 indents at start.
    so this is code
      and this indented code
      and so is this
    and this isn't indented but it's still in the codeblock
    
And a table? Use pipes (vertical lines) and hyphens to delineate the headers, e.g.:
Header 1 | Header 2 | Header 3
---------|----------|---------
Cell 1 contents | Cell 2 contents | Cell 3 contents
Cell 4 (but still column 1, row 2) | 5 (C2,R2) | 6 (C3,R2)

What about adding an emoji? Enclose it in colons! But you might need [this cheatsheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md) to find the emoji's name... :sunglasses:
