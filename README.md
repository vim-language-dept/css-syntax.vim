# Vim CSS Syntax File

## Adding features

The keywords in this plugin should be limited to those that appear in a W3C
document that has reached the level of Candidate Recommendation or higher. Check
[the "current work" page](https://www.w3.org/Style/CSS/current-work) for more
details.

## Working Draft branch

The `wd` branch contains specs that are in Working Draft status. Switch to this
branch for highlighting for things like ["flow-relative"
properties](https://www.w3.org/TR/css-logical-1/) that haven't made it into
Candidate Recommendation yet.

## Installation

### Manual

Copy `css.vim` file into your `~/.vim/syntax/` directory.

### Using Vundle

Add the following line to your `~/.vimrc` file:

```
Plugin 'vim-language-dept/css-syntax.vim'
```

and run `:PluginInstall` in Vim.

## More Info

- https://www.w3.org/Style/2011/CSS-process
- https://www.w3.org/Style/CSS/current-work
- https://www.w3.org/Consortium/Process#candidate-rec
- https://developer.mozilla.org/en-US/docs/Web/CSS

## Thanks

- JulesWang https://github.com/JulesWang/css.vim
- ChrisYip, amadeus https://github.com/amadeus/Better-CSS-Syntax-for-Vim
- hail2u   https://github.com/hail2u/vim-css3-syntax
- leptrue  https://github.com/lepture/vim-css
