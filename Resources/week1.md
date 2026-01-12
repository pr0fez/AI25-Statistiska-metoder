# Week 1 resources

[This Repo on Github](https://github.com/pr0fez/AI25-Statistiska-metoder)

## Setup

This course includes some python exercises and the assignment is a programming task.

A modern and new-ish tool for virtual environment managment for python is `uv`. It's alot
more stable and easier to use than other package managers available for python and I do recommend
using it. 

If you are on linux, `uv` is typically available through your distro's package manager (`apt`, `pacman`, `dnf`, `yum`, `pkg` and so on).

If you are on windows, macos or can't find a package for your distro, check https://docs.astral.sh/uv/getting-started/installation/ for installation instructions.

I recommend creating a new directory/repo for this course. 

Creating a new virtual environment with `uv` is simple, navigate to your created directory and run:
> uv venv 

You then use `uv` just like pip -- simply prepend `uv` to your commands:
> uv pip install numpy pandas scipy

If you need a specific python version in a directory:
> uv python install 3.13

> uv python pin 3.13

## Theory and exercises
### Probability and counting

Professor Dennis Sun at Stanford has published an excellent repo and videoseries regarding probability:
[https://dlsun.github.io/probability/](https://dlsun.github.io/probability/)

The first module regarding "probability and counting" is excellent: https://dlsun.github.io/probability/counting.html

Also check out the companion youtube video: [counting](https://www.youtube.com/watch?v=w9iG_7cuORk)

The first 9 chapters of Prof. Sun's repo reflect the contents of the first week. There are also exercises that look good, but I haven't solved them so can't say anything about the difficulty. They seem entirely reasonable, but it's also easy to construct statistics exercises that look simple but with very tricky calculations. I'm sure we can solve them together though!


> Milton/Arnold: Chapter 1-2

> Exercises: 1.7, 1.9, 1.13, 1.17, 1.21, 1.32, 2.5, 2.9, 2.15, 2.17, 2.19, 2.33, 2.39

NOTE: You aren't expected to do _all_ exercises -- do as many as you find necessary. 

### Python
Go through the [python repetition](../Exercises/python-repetition.ipynb) in the exercises folder. Don't worry about the meaning of the distributions-- just plot them in histograms and ogives as a repetition of previous courses. Soon enough we will talk about what the plots are showing!