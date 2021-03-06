![](http://cl.ly/image/320J0E0d2p3W/content)

### Lavalamp is a WIP text editor theme. 

**It currently works in Vim, but I hope to port it to Atom and Sublime Text.**

====

### Installation

Copy `lavalamp.vim` to your `.vim/colors` directory.

    $ cd lavalamp/vim
    $ cp lavalamp.vim ~/.vim/colors/
    
Then update your `.vimrc` with these lines:

    syntax enable
    set background=dark
    colorscheme lavalamp
    
If you're using [airline](https://github.com/bling/vim-airline), you can install the lavalamp theme for that.

    $ cd lavalamp/vim/autoload/airline/themes
    $ cp lavalamp.vim ~/.vim/autoload/airline/themes/
    
For the iTerm theme, you should be able to double-click on the `lavalamp/iterm/lavalamp.itermcolors` file to install it.
    
**If you're using CoffeeScript, I highly recommend installing the [vim-coffee-script](https://github.com/kchmck/vim-coffee-script) plugin since it offers much better syntax highlighting (which lavalamp utilizes).**

### Design principles

The idea behind the theme is that each language has its own core color. This way, it's easier to visually differentiate languages when they're used together.

For example, HTML uses shades of blue while Ruby uses red. Then it's easy to see your ERB tags:

![](http://cl.ly/image/3X091e0c3U11/content)

CSS uses purple (an homage to [@mdo](https://github.com/mdo)):

![](http://cl.ly/image/0W223O123E1t/content)

In a Sass file, it's easy to see vanilla CSS vs. Sass (which is red, since it's Ruby):

![](http://cl.ly/image/10100y1Q3g25/content)


I've chosen green for Javascript:

![](http://cl.ly/image/1d3H3Q3V0j0p/content)

And browns for Coffeescript:

![](http://cl.ly/image/3x0k3Q262g0m/content)


### Roadmap

I've been using this theme for a while in this state since these are the languages I mostly use. If more people want to use the theme, more languages will need to be fleshed out.

And I'd really :heart: some help getting this working with Atom and Sublime as similarly as possible.
