# Payment-Receipt
Create our own transaction receipts just by using python

Creating payment receipts is a pretty common task, be it an e-commerce website or any local store for that matter.

Here, we will see how to create our own transaction receipts just by using python. We would be using reportlab to generate the PDFs. Generally, it comes as a built-in package but sometimes it might not be present too. If it’s not present, then simply type the following in your terminal

Installation:
pip install reportlab

Approach:
Import module.
We need the data in the form of a list of lists. The 0th index of the outer index is the headers.
We create a simple doc template with the specified paper size (here A4)
Then get a sample style sheet from the built-in style sheets and add the styling accordingly.
After you have created a style object, feed in the data and the style sheet to the pdf object and build it.
