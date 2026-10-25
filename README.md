# Turtle Heart 💜

I made this heart with Python's turtle module and a bit of maths.

![Heart drawing](heart.png)

## How it works

The heart comes from two formulas, one for left and right (x) and one for up and down (y):

- x = 15 sin³(t)
- y = 12 cos(t) − 5 cos(2t) − 2 cos(3t) − cos(4t)

The turtle jumps to 6000 points along the curve. Each step moves `t` by a whole number, so instead of tracing a neat outline it zig-zags back and forth across the shape. All those crossing lines build up into the woven, string-art look you can see in the picture. I didn't plan that part, but it's my favourite thing about it.

## Try it yourself

python heart.py

You only need Python. `turtle` and `math` are built in, so there's nothing to install. Run it and watch the heart draw itself.
