# Set Up Jupyter Notebook

If you are already running Python 3 and comfortable with the command line, you can easily install Jupyter Notebook by using **pip**:

`$ pip install jupyter`

Otherwise, you'll want to download and install the free individual edition of [Anaconda](https://www.anaconda.com/products/individual). Anaconda is a robust toolkit that makes it easier to learn a wide variety of data science applications. What follows assumes that you're using Anaconda; once it's installed, go ahead and launch it.

You'll notice a few things:

![][1]

[1]: images/anaconda.png

First, you can create an account at [Anaconda Cloud](https://anaconda.org) that will allow you to share your work with others, if you like; if so, you can then sign in using the green "Sign In" button at upper right.

Second, in the main part of the screen, you can see the range of applications that Anaconda makes available, including Jupyter Notebook, of course, but also including things like RStudio.

Finally, in the left-hand menu, you'll find access to a range of reference tools and community forums.

For now, find the Jupyter Notebook application and click "Launch."

![][2]

[2]: images/jupyter-launch.png

Jupyter Notebook will launch by opening a Terminal window and running the required commands to start the environment, and then opening the Jupyter Notebook server in a browser tab. At startup, the server will show you a directory of all the files in your user folder; I'd encourage you to create a subfolder called something like "Notebooks" somewhere you find convenient. Mine is inside Documents. You can create that subfolder the usual way, in the Finder, or you can navigate within the Jupyter server to the place you'd like to create the subfolder and click New > Folder at upper right.

You can refresh your Jupyter server view by clicking the circular arrows next to New if need be. Once you've created your subfolder and navigated into it, you should see something like this:

![][3]

[3]: images/notebooks-folder.png

If so, you're ready for [Part 2: Create a Notebook](https://github.com/kfitz/introduction-to-jupyter-notebook/blob/master/create-notebook.md)