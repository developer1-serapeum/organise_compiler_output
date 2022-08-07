# organise_compiler_output
Format the output of a compiler into excel format

It is a very specific script needed when you want to organise the output of a compiler and display it in excel forma.

You might need this as a requirement for Automotive SPICE becuase any C warning should be fixed or justified.


# Usgae

In this example, I just copied the compilation output and pasted it into the file "compiler_in_example.txt".

~\organise_compiler_output>python.exe organise_compiler_output.py

```
Found compiler warnings count (552)
Warning ids count = (552) times
Line numbers count = (552) times
File names count = (552) times
Warning titles count = (552) times
The excel sheet {"compiler_out.xlsx"} was written successfully...
```