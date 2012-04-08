FMBingo
=======
Generate custom bingo cards from FileMaker


Usage
-----
It's pretty easy: each record is a bingo game (a "card"). Along the right sidebar are the items that go into each card. Add a new item by clicking in the blank row at the bottom and typing into it. Choose a numer of cells you'd like, and FMBingo will generate a card with whatever item you've entered randomly dispersed throughout.

I've added a couple of sample cards so you can get an idea of how it works.

Printing the cards is a little strange, mostly due to some pecadillos of printing in FileMaker. I've found the best way to print the cards is to export them as HTML, then open up the HTML files in your web browser (Chrome has the best print dialog) and print those.


Notes
-----
FMBingo works by generating HTML for a bingo card based on FileMaker data. The HTML is fully editable from the `setup` layout. Give it a try to change how the card looks!


Props
-----
Props to the [Proof Group](http://proofgroup.com) for their radical and awesome `MergeExpressions` and `GetGUID` custom functions, which make life better for me every day.
