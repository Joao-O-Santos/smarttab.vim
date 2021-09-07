**Fork of Soares/smarttab.vim** aiming for compatibility with more
languages.

**By default this forks sets C, C++ style parentheses auto-align for all
FileTypes other than python.**

This vim plugin makes "tab" honor "expandtab" for indents and always use
spaces for alignment.

It will also auto-align to parentheses in C, C++, and Python. For
example, given:

    ▷   ▷   def function(argument,▊argument):

pressing enter will result in:

    ▷   ▷   def function(argument,
    ▷   ▷                argument):
    
It's still pretty stupid. Install in plugin/smarttab.vim

# TODO:

Add markdown compatibility, *id est*, align text in nested lists.
