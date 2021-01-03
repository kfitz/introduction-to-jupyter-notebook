# Styling Text in Your Notebook

As noted in the previous section, there are several different cell types available in Juptyer Notebook, including Code (in our case, Python) and Markdown. Markdown is an easy means of creating richly styled text using minimal text-based formatting commands. (In fact, this page is written in Markdown.) There are two other cell types listed in that little dropdown menu: Heading, which Jupyter will warn you not to use, and Raw NBConvert, which we won't be using.

For the moment, click on your first cell again to highlight it, and then use the Insert menu to insert a cell above it.

![][1]

[1]: images/insert-cell.png

Using that dropdown menu, change this cell type to Markdown. Note that the "In [ ]" notation disappears from the left margin, indicating that this cell is not runnable.

![][2]

[2]: images/not-runnable.png

Now we'll create some introductory text for your notebook using Markdown formatting. There's a great tutorial on using Markdown in Jupyter Notebook at [DataCamp](https://www.datacamp.com/community/tutorials/markdown-in-jupyter-notebook), but for the moment here are a few key tips:

1. The pound sign creates headings; one pound sign creates a level 1 heading, two creates a level 2 heading, and so on.
2. You can create *italicized text* by placing one asterisk before and after the text, and **bold text** by using two asterisks.
3. You can create unordered lists by starting each of a series of new lines with a hyphen, and ordered lists by starting each of a series of new lines with a number.

Using these tips, add a heading to your notebook and a sentence describing what the notebook does. When you're done, hit Run or shift-return, and the cell will transform into nicely styled text.

![][3]

[3]: images/styled-text.png

One last bit of Markdown that might be useful: if you want to include a bit of code that you want to be read rather than run, you can include it in a Markdown cell and make clear that it's code by framing it with backticks.

![][4]

[4]: images/code1.png

When you run that cell, you can see that the code is highlighted and uses a monospaced font, indicating that it's code.

![][5]

[5]: images/code2.png

But here's a neat trick: if you use three backticks instead of one, and the first line of your code block specifies the programming language involved...

![][6]

[6]: images/code3.png

...the result will highlight the code's syntax, making it more readable.

![][7]

[7]: images/code4.png

You can save your notebook by choosing "Save" under the File menu or by clicking the Save icon. Jupyter Notebook will autosave your work as you go, so you don't need to worry about losing anything, but actively saving provides the added benefit of creating a checkpoint. This will allow you to revert your notebook to a prior state if things go wrong or you want to do something differently.

Finally, to close your notebook you need to do more than just close the browser tab; Jupyter Server will keep the kernel of your notebook running in the background until it's stopped. (A nice feature if you've ever lost your work by accidentally closing a tab!) To fully close the notebook, you can select "Close and Halt" under the File menu, or, if you've already closed the browser tab, you can click "Shutdown" under the "Running" tab on Jupyter Server.

![][8]

[8]: images/shutdown.png

That's it for this tutorial. Now that you've been introduced to Jupyter Notebooks, I'll use a notebook for our next set of tasks.


