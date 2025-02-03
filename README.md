

![alt text](https://raw.githubusercontent.com/CGIONE/Token32wiki/refs/heads/main/v110.jpg)


VALUE32 ITO PRINC.
by DVK aka cgi1

0. #define VALUE32 "Tokenized digital asset, \
                    aimed to compound value over time.\

1. Authorship of work.
2. Issuance of proof-of-ownership thus
connection with "physical" world.
3. Author control emission and seniorage.
4. By design, compoundable and mutable over time,
tokenized for distribution.
5. User-side portable, transtional from:
OS derivatived to BIOS alternative
6. Include, like "hyper" struct, separate untangible value art-token and versioned source code.
7. Compiler-specific, transtional from:
language lib dep -> language lib indep.
8. As is, no refund.


// V110
// clean add and remove funcs

// FUNCS

// make reg arr entry based on inc
b32 v32put_entry_inc(u32 inc, char *handle)

// make reg arr last entry
b32 v32put_entry_last(char *handle)

// remove
b32 v32remove_entry_inc(u32 inc)

// 
b32 v32remove_entry_last()

// print reg
void v32print_reg()

//
void debug_token32()

//
void v32emit_token()
