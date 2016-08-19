# Bash on Windows Gotchas

* Line endings, be aware of what your editor is using for line endings. If you intend to open the in bash it's base to ensure that it's using Unix line endings or your editor is capable of converting back and forth.
* Unix filesystem is case sensitive, Windows is not
 * If you create a file in Windows seach as README.md, in unix that case will matter
* There's a huge list of issues since there are plenty of features that are not implemented yet (as of 2016-08-19), https://github.com/Microsoft/BashOnWindows/issues