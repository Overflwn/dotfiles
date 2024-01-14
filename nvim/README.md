# Requirements (with coc support for python and c++)
- **generally needed:** `nerd-fonts`, and set the terminal font to DroidSans Nerd Mono
- **first of all:** Install vim-plug, then: `:PlugInstall`
- For Python: `python-pylint python-jedi`
    - `:CocInstall coc-python`
- For C++: `clang llvm lldb`
    - `:CocInstall coc-clangd`
- For Go: `go` (obviously)
    - `:CocInstall coc-go`
