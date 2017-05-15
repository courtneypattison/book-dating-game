# The Gryph Reads Book Dating Game
Website for Gryph Reads book dating game event

Conceived by the Gryph Reads commitee, including Carrie Breton, Emily Carlisle, Jacqueline Hamilton, Melanie Parlette-Stewart, Hana Storova, Paula Barton, and Robin Sakowski

## How to play
Do you like to read for fun?

Find books in the University of Guelph Library's leisure reading collection, Gryph Reads, by reading the first paragraphs of some of the books from the collection.
1. Find a category that interests you
2. Click one of the coloured boxes
3. Read the first paragraph of a book
4. Click `I'm hooked!` if you want to be brought to a webpage where you can place a hold on the book or click `Not interested` to return to the game board.

## Screenshots
![index](/../master/images/index.png?raw=true)

![modal](/../master/images/modal.png?raw=true)

## How to create your own
To add new boards to the website, use the `board-template.html` filling in a unique id number for the `<button type="button" data-a11y-dialog-show="ID_NUMBER"></button>` button and corresponding dialog `<div id="ID_NUMBER" class="dialog" aria-hidden="true">`. Use index.html as a reference for filling in the other data.
