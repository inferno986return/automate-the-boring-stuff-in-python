# automate-the-boring-stuff-in-python

An alternative ePub for the 2<sup>nd</sup> edition of *Automate The Boring Stuff in Python* by Al Sweigart.

<img src="https://github.com/inferno986return/automate-the-boring-stuff-in-python/blob/main/e-book/OEBPS/images/9781593279936.jpg" width="400" height="529" alt="Book cover"/>


## Please support the official book!

If you like this book please purchase a copy from your preferred bookseller:

* No Starch Press: https://nostarch.com/automatestuff2
* Amazon: https://www.amazon.com/dp/B07VSXS4NK
* Amazon UK: https://www.amazon.co.uk/dp/B07VSXS4NK
* Amazon AU: https://www.amazon.com.au/dp/B07VSXS4NK

Humble Bundle regularly feature Al Sweigart's books, as well as other tech books from The Starch Press often at a steep discount. I recommend keeping an eye out for their next bundle.

There is also a dedicated Udemy course for this book: https://www.udemy.com/course/automate/<br/>(Despite the GBP£49.99 price point, Udemy regularly discount their courses.)

## What have I changed?

My initial motivation is to remove unneccessary fonts such as Janson, Trade Gothic and Arial Unicode, as well as swapping out Ubuntu Mono for the superior JetBrains Mono NL. I've also re-enabled the blue underlined hyperlinks.

The final ePub once compiled will be considerably smaller and easier to read.

As a note to would-be e-book developers, you don't need to be overkill with font embedding:

* Many serif typefaces aren't optimised for digital screens (such as Janson, Garamond and Caslon) requiring a specific "eText" version.
* It can significantly increase the size of the ePub file - Arial Unicode MS alone is over 22MB!
* Some e-readers (notably Apple Books) ignore font embedding choices.
* Font embedding for e-books usually requires a specific licence paid per publication that is more expensive than desktop licencing.

## Licencing

The proprietary fonts have been removed, so there shouldn't be any issues there.

I have modified the No Starch Press ePub code (XHTML and CSS). Not sure what licence they have, but it can be swapped out with my own if this is an issue.

Book content is licenced under the Creative Commons Attribution-NonCommercial-ShareAlike 3.0 United States (CC BY-NC-SA 3.0 US): http://creativecommons.org/licenses/by-nc-sa/3.0/us/ 

JetBrains Mono is licenced under the Apache License 2.0: https://www.jetbrains.com/lp/mono/