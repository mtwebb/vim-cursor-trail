#  Cursor Trails

Designed to work with Hellboy and Tuftish themes. Switches gradients based on bg=light/dark[^1]

![A short Vim session. Vim is showing the :help page for the Rainbow Trails plugin. The command :Rainbow Trails is entered, and then the cursor is moved rapidly around the window, leaving rainbows behind it as it zips about.](https://normalmo.de/plugins/images/rainbow-trailser.gif)

## I want fast Hellboy zipping across the screen smashing bugs!

Install with your normal package manager, or just use Vim's built in [packages](https://vimhelp.org/repeat.txt.html#packages) feature:

    mkdir -p ~/.vim/pack/plugins/start
    git clone https://github.com/mtwebb/cursor-trails.git ~/.vim/pack/plugins/start/

Then run `:helptags ALL` in Vim to generate the [documentation](doc/rainbow-trails.txt), and `:RainbowTrails` to start the FUN.

[^1]: Hellboy not included.
