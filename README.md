Scripts for shellcoding.

## Push String
Generate the opcode to push a string to the stack.
```sh
user@host:~/bin/asmtool/push_string "calc.exe"
Assembler

"\x68\x2E\x65\x78\x65"      # PUSH 6578652E -> ".exe"
"\x68\x63\x61\x6C\x63"      # PUSH 636C6163 -> "calc"

[*] OPCODE

\x68\x2E\x65\x78\x65\x68\x63\x61\x6C\x63
```
