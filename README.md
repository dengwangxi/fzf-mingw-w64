fzf-mingw-w64
========
See [junegunn/fzf#147](https://github.com/junegunn/fzf/issues/147) for the
history.

### Instruction
1.  Install [msys2](https://msys2.github.io/) and [Go](https://golang.org/dl/)
1.  Install dependencies

    ```
    pacman -S mingw-w64-x86_64-gcc mingw-w64-x86_64-ncurses
    ```

1.  Build `fzf-mingw-w64` with **MinGW-w64 Win64** shell. It won't work with
    MSYS2 shell.
