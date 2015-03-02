PyBhuj 2015 - PyKachchh Python Workshop
=======================================================================

Coding guidlines
------------------------------------------------------
**Tabs Vs Space**
The default branch was created with fucking Tabs! Coding with tabs is pain in ass.
To minimize the initial diff we will use 2 spaces while coding and 1 tab while committing.
Fortunatily git and linux is enough to solve this problem.
This is for HTML only. We can do the same for CSS and JS.
Follow the below steps (for Linux only):

In your repository, add a file .git/info/attributes which contains:

`*.html  filter=tabspace`

Now run the commands:

`git config filter.tabspace.smudge 'expand --tabs=2 --initial'
git config  filter.tabspace.clean 'unexpand --tabs=2 --first-only'`

You may now check out all the files of your project. You can do that with:

`git checkout HEAD -- **`

[Reference](http://stackoverflow.com/questions/2316677/can-git-automatically-switch-between-spaces-and-tabskj)

Notes
-------------------------------------------------------
Please use (tilde)(tilde)text(tilde)(tilde) to denote that the item in TODO has been completed.
DO NOT remove it entirely from the list. (refer to GitHub Markdown for further references.
Everyone is free to add TODO items.
Other than adding TODO items and identifying bugs, let's keep suggestions etc in our official group.

TODOS:
-------------------------------------------------------
- Logo
- Proper theme colors and font colors.
- Workshop description
- About workshop description/content
- Talk details
- Portfolio/Showcase section
- Sponsors
- Contact Us / Register

Credits
=======================================================================

Fonts
------------------------------------------------------
- Font Awesome by Dave Gandy - http://fortawesome.github.io/Font-Awesome/
- Google Fonts - http://www.google.com/fonts

Resources
------------------------------------------------------
- Bootstrap Framework by @mdo and @fat - http://getbootstrap.com/
- jQuery - https://jquery.org/
- jQuery Appear - by bas2k - https://github.com/bas2k/jquery.appear/
- Modernizr - http://modernizr.com/
- Animate CSS by Daniel T. Eden - http://daneden.github.io/animate.css/
- Isotope Jquery plugin by metafizzy.co - http://isotope.metafizzy.co/
- Backstrech by Scott Robbin - http://srobbin.com/jquery-plugins/backstretch/

Acknoledgments
-------------------------------------------------------
The theme has been taken from [htmlcoder](http://htmlcoder.me/) and we thank them for providing a cool theme for free.
