

![alt text](https://raw.githubusercontent.com/CGIONE/Token32wiki/refs/heads/main/v109.jpg)


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


// FUNCS

// make add

// make token (and todo: check with registry)
val32_t v32make_token()

// make reg arr entry based on inc
entry32_t v32put_entry_inc(u32 inc, char *handle, val32_t token)

// make reg arr last entry
entry32_t v32put_entry_last(char *handle, val32_t token)

// remove
b32 v32remove_entry(u32 inc)

// print

// print reg
void v32print_reg()

// initial emission based on alist
void v32emit_token()
