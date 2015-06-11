## How to install

### Using [pathogen]

``` bash
cd ~/.vim
mkdir -p bundle && cd bundle
git clone git://github.com/ajpaulson/julia-syntax.vim
```

### Using [vundle]

Add a new plugin line to your `.vimrc`:

``` vim
Plugin 'JuliaLang/julia-vim'
```

Run `vim` and update your bundles:

``` vim
:PluginInstall!
```

[pathogen]: https://github.com/tpope/vim-pathogen
[vundle]: https://github.com/gmarik/vundle

### Manually

Copy (or symlink) the contents of this repository into the vim application support directory:

``` bash
git clone git://github.com/ajpaulson/julia-syntax.vim
cd julia-syntax.vim
mkdir -p ~/.vim
cp -R * ~/.vim
```

Julia should appear as a file type and be automatically detected for files with the `.jl` extension.

## Complete documentation

The full documentation is available from Vim. Vundle and other plugin managers will generate the required
help tags automatically, so that you just need to type `:help julia-vim`. Otherwise use `:help helptags`
in ViM and see how to generate them.
