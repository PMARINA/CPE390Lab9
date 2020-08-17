# CPE390Lab9

In order to defuse the bomb, you will need to be able to step through assembler code in gdb.

This code, by Peter Ho, uses some c routines.
you can google the following terms to see the documentation

`man scanf`

note: for scanf, better docs: http://www.cplusplus.com/reference/cstdio/scanf/

`man strcmp`

Your job is to step through the program with the debugger and not blow up. Each group will debug its own executable: group 1: 1001.out and so on, so forth.

Examples:

`> 3`

> BOOM! You blew yourself up to smithereens!

`> 4992`
> Ha! That was just a warmup test. This one will be harder.

`> 2 3`
> BOOM! You blew yourself up to smithereens!

In order to use the debugger:

- `gdb yourexecutable`
- `layout reg`
- `start`

- to step an instruction at a time: `si`
- to print a string in memory at location r0: `x/s $r0`

## To Get Credit

To get credit for this lab, put your answers below:

- Phase 1 Answer: ...
- Phase 2 Answer: ...
- Phase 3 Answer: ...
- Phase 4 Answer: ...

Answer [these questions](https://docs.google.com/document/d/118znb-V8mAS0f1XqggrUcZp2w0s22r1WcIr9NfUSLpc/edit#heading=h.mp3ykn2lx2xt) (lab 6) in the following space:

1. Answer to question 1
2. Answer to question 2
3. Answer to question 3
