# unixodbc_homebrew_test

`./run_isql` installs one of two different versions of unixodbc from homebrew, then runs a couple `isql` commands.

It shows that on version `13pre` the program will crash if the table is non-existent.

The `run_isql_2_3_13pre_doc.txt` file shows the output of the run where it crashes.
