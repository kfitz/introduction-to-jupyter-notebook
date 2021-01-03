# Create Your First Jupyter Notebook

At upper right in your Jupyter Server browser tab, click New, and then choose Python 3 under Notebook. Your browser will open a new tab that looks something like this:

![][1]

[1]: images/untitled-notebook.png

You'll notice a menu across the top of the page that contains a fairly recognizable structure: File, Edit, View, Insert, etc. Below that is a row of icons that provide easy access to some important notebook functions. And then below that is an empty cell. Cells are the most basic unit of the Jupyter notebook.

Let's start by renaming the notebook. Click on "Untitled" and type a more descriptive notebook name; I've gone with "Hello Jupyter." Hit "Rename" and the name should now appear at the top of the page.

![][2]

[2]: images/rename-notebook.png

Now let's turn our attention to the first cell in your notebook. There are several different kinds of cells available, but the first cell defaults to runnable code (hence "Code" in the dropdown menu in the icon bar). Since we selected Python 3, that's the language we'll be able to code and run in this notebook.

To be sure that everything is running as it should, type the following into that cell:

`print('Hello Jupyter!')`

Hitting return at the end of that line will take you to a second line in the same cell. To execute the cell's code instead, you can either press the Run button in the icon bar or you can press shift-return on your keyboard.

![][3]

[3]: images/hello-jupyter.png

You'll notice that the empty brackets next to "In" in the first cell have now filled in with the number 1. The next cell you run will fill in with 2, and so on, allowing you to keep track of the order in which you've run the cells.

If you have multiple cells in your Notebook, and you run the cells in order, you can share variables and imported libraries across cells, which makes it easy to produce code in logical chunks without needing to recreate those variables or reimport those libraries every time.

If you want to learn more about the notebook environment -- what's in the menus and so on -- you can continue with the [Real Python introduction](https://realpython.com/jupyter-notebook-introduction/). For the moment, however, let's move on to [Part 3: Styling Text in Your Notebook](https://github.com/kfitz/introduction-to-jupyter-notebook/blob/master/style-text.md).