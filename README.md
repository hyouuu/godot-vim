Vim bindings for Godot 4 at https://github.com/hyouuu/godot-vim

Forked from https://github.com/joshnajera/godot-vim - many thanks to the original author and contributors, but it hasn't been maintained for over 8 months so decided to use this fork to get all the PRs merged.

### Installation
Use the official Godot documentation [here](https://docs.godotengine.org/en/stable/tutorials/plugins/editor/installing_plugins.html) to install the plugin.

### Supported Mode

    - Normal mode
    - Insert mode
    - Visual mode
    - Visual line mode

### Supported motions

    h, l, j, k, +, -
    ^, 0, $, |
    H, L, M,
    c-f, c-b, c-d, c-u,
    G, gg
    w, W, e, E, b, ge
    %, f, F, t, T, ;
    *, #, /, n, N
    aw, a(, a{, a[, a", a'
    iw, i(, i{, i[, i", i'

### Supported operator

    c, C,
    d, D, x, X,
    y, Y,
    u, U, ~

### Supported actions

    p,
    u, c-r,
    c-o, c-i,
    za, zM, zR,
    q, @, .,
    >, <
    m, '

### Override Default Godot Shortcuts with `godot-vim`'s ones

Note that all non-ascii character mappings that are already mapped in the default Godot editor have to be unmapped from the Editor settings (Editor >> Editor Settings >> Shorcuts) before being usable with `godot-vim`.

This currently goes for:

- `Ctrl+R`
- `Ctrl+U`
- `Ctrl+D`

See the full list of non-ascii shortucts that may already be mapped by Godot and thus wouldn't work in `godot-vim` before releasing them in Godot settings: https://github.com/hyouuu/godot-vim/blob/main/addons/godot-vim/godot-vim.gd#L136
