# every_trick_in_the_book

every_trick_in_the_book by SJMcH, a Mattering toolkit: every trick in the book for making books.

It turns a book written in Markdown into an open, static website that can be cited to the paragraph:

- every reading paragraph has a number that depends only on the text, so a citation such as ‘(Nassar 2026: para.
  12)’ keeps pointing at the same words;
- poems number their lines, so poetry can be cited by line;
- frozen versions of the book stay online at their own addresses, and lead readers to the same passage in the newest
  text;
- every page is also offered as plain Markdown, and as data (`page.json`, `publication.json`) for other frontends;
- citations are set in the house style and show their reference in a popup, and images can be zoomed.

It is made of Pandoc, a few Lua filters and one template, and needs no server.

## Where things are

every_trick_in_the_book is developed with its first book, *Hear Here: Spatial Practices* (Mattering Press). For now
its code lives in that book’s repository, in the `every_trick/` folder; it will move here.

- [What’s new](https://github.com/mattering-press/Hear-Here-Spatial-Practices/blob/main/every_trick/CHANGELOG.md): every
  version of the toolkit and what changed in it
- [The contract](https://github.com/mattering-press/Hear-Here-Spatial-Practices/blob/main/every_trick/CONTRACT.md): the
  rules for content (paragraph numbers, poems, versions) and the data the build writes
- [The code](https://github.com/mattering-press/Hear-Here-Spatial-Practices/tree/main/every_trick)
- Made with it: [*Hear Here: Spatial Practices*](https://hearhere.matteringpress.org/)

## Still to come

A publication about every_trick_in_the_book, made with it: a reflection on why it works the way it does, a how-to
for making a book with it, and its documentation.

## Licences

The toolkit is under the Mozilla Public License 2.0. Its Markdown conventions and its documentation, this page
included, are under CC BY-SA 4.0. The designed styles, `sjmch/styles`, are free for non-commercial use, with a paid
licence for commercial use. The details are in
[NOTICE.md](https://github.com/mattering-press/Hear-Here-Spatial-Practices/blob/main/every_trick/NOTICE.md). Please get in
touch before sending changes.

Copyright © 2026 Studio Julien McHardy (SJMcH). Made for Mattering Press, its first publisher.
