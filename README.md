# UmbracoBookshelf
![Bookshelf](https://github.com/kgiszewski/UmbracoBookshelf/blob/master/assets/logo.png)

Bookshelf will allow users to create, display and share learning resources quickly through the Umbraco backoffice.

Bookshelf works by reading markdown files from the `UmbracoBookshelf` folder of your website. 

![Sample](https://our.umbraco.org/media/wiki/144508/635650696507955335_Screen-Shot-2015-04-19-at-15038-PMpng.png)

##Install this Package##
Use [NuGet](https://www.nuget.org/packages/umbracobookshelf/) or [Our Umbraco](https://our.umbraco.org/projects/backoffice-extensions/bookshelf) to download and install like you would any other Umbraco package.

##Install a Book##
Books are available on the Bookshelf dashboard or you can install any zipped markdown book.

##Editing a Book##
To edit a book, simply click `Edit` on an `.md` file page.  If the book is hosted on GitHub, please consider sending revisions and additional content.

##Creating a Book#
Books are just `.md` files that live in the `UmbracoBookshelf` folder of your webroot.  So to create a book, just create a sub-folder next to your other books (like this one).  By default when a user clicks the folder in the tree to the left, the `README.md` file is loaded for the user.

Want to add images?  Just add a folder with images and use relative links.

Links beginning with `http` auto open in a new tab.

Books should be written in Markdown and Bookshelf recognizes Github Flavored Markdown.  Please use the following resources when learning Markdown:

* https://help.github.com/articles/markdown-basics/
* https://help.github.com/articles/github-flavored-markdown/

There is now an editor to help you create folders, files and markdown.

*Please refrain from using `HTML` directly when possible.  Some things like embedding videos are unavoidable.*

##Consider Contributing Your Time##
If you like Bookshelf, please consider helping by adding features or creating books for others to use.

##License##
MIT licensed, use it and abuse it.

##Author##
Umbraco Bookshelf is maintained by Kevin Giszewski.

http://twitter.com/kevingiszewski
