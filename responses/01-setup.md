*Correct!* That answer is describing JavaScript (which is entirely different than Java).

## Prepare your environment

Before we can start writing Java, we need to make sure you have your environment set up. You just need a few things (some of which you might already have!)

- [ ] Check if Java is installed and set path
- [ ] Download a text editor
- [ ] Clone your course repository using git

## Check that Java is installed

Your machine may already have Java, or you might need to install it. To find out, go to your command line terminal and type: 

`java -version`

Then type:

`javac -version`

If you see your Java version displayed for each of these, you're all set!

Otherwise, you'll need to [download Java](https://www.oracle.com/technetwork/java/javase/downloads/jdk12-downloads-5295953.html) for your operating system.

The next step is to [set the java file path](https://www.javatpoint.com/how-to-set-path-in-java) by developing a new environmental variable. Go to the link above for instructions on how to find and set the path for Java. (if you already have a path variable, you can add a ; to the end and include the next path afterwards).

When you make a new environmental variable, you need to close and re-open your terminal. Do this now, then type these lines to make sure the path was set correctly.

`java -version`
`javac -version`

You should see a version for each of these if it was correctly installed.

## Download a text editor

Make sure you have a text editor installed before proceeding (such as [Atom](https://atom.io/), [Sublime Text](https://www.sublimetext.com/3), or [Notepad++](https://notepad-plus-plus.org/)).

## Clone course repository

You will be storing the code for this project in [this repository]({{ repoUrl }}). Before we go any further, clone your template project into the directory you want to store your code locally in, using [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git):`git clone {{ repoUrl }}.git`

To test that your project is set up correctly, navigate into the folder you cloned and run these commands:

`javac custom_order.java`

`java custom_order`

If everything was set up correctly, you should see "Hello World!" printed in your command terminal. We'll describe what we just did in the next step.

*When you have finished these steps, leave a comment for the next step*