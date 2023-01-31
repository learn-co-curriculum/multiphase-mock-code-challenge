# Mock Code Challenge

## Learning Goals

- Ensure Python has been installed correctly.
- Practice starting a code challenge.

## Introduction

Towards the end of each phase of this course, you'll receive an assessment in
the form of a code challenge. This code challenge is a chance for you to show
off how much you've learned, see where you are in terms of grasping the
material, and get feedback from us on ways to improve or areas to work on
further.

The workflow for starting and completing a code challenge is different from what
you're used to, and this lesson will walk you through the steps. This ensures
that when the time for code challenges arrives, you can be confident your
machine is properly set up to complete one and just focus on the challenge at
hand.

## Instructions for Working on and Submitting Code Challenge

Instead of forking and cloning a GitHub repository like you do for all your
labs, you will download a `.zip` file and use what is called a GitHub bundle. A
code challenge bundle will hold all the instructions and any starter code you
need for the challenge. We will learn how to use a bundle in this section.

To practice these steps, download this mock code challenge zip file:

> **Note**: This is **not** an actual code challenge, we are just practicing the
> process you will use later on.

Once you've downloaded the `.zip` file, follow along with the steps below to
open the bundle:

1. Unzip the file on your computer.
1. In your terminal, change directory (`cd`) into the unzipped challenge
   directory.
1. Run ls; you should see a `bin/` directory and a
   `code-challenge-practice.bundle` file).
1. Run `./bin/start <your-name>` from the directory; this will create a new
   directory called `code-challenge-practice/`.
1. Change directory into the new `code-challenge-practice/` directory and open
   it in your code editor.

The steps above gives you access to all the content of the bundle. In a normal
code challenge, you would then read through the `README.md` to find and follow
the instructions for the challenge. As you work, you would use some familiar
`git` commands to save your work. Let's practice that as well:

1. In your code editor and the terminal, ensure that you're in the
   `code-challenge-practice/` directory.
1. Follow the instructions in the `README.md` file.
1. Once you're done, `git add .` and `git commit` with a message. This will save
   all your work.

Instead of pushing your work up to a GitHub repository like you're used to, you
will bundle up your work to be uploaded onto Canvas. Again, you will use a
provided script to do so.

1. In the terminal, navigate back up to the **parent directory** of
   `code-challenge-practice/`, which should be `mock` for this
   lesson.
1. Run `./bin/end`, which will create a new file, `<your-name>.bundle` in that
   directory (for example, `alicia.bundle`).
1. Navigate back to this assignment in Canvas.
1. Upload `<your-name>.bundle` to the assignment and submit.

## Conclusion

With that, you've successfully gone through the process of starting and
completing a code challenge!

If you were unable to complete any part of this process, please **reach out to
your instructors immediately**. Be sure you are able to complete this mock
challenge well before your first official challenge day.
