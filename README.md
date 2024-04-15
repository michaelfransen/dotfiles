# Michael Fransen's Dotfiles

[Dotfiles](https://dotfiles.github.io) managed by [chezmoi](https://www.chezmoi.io) ❤️

## Setup dotfiles on new machine
1. Install Homebrew
`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
1. Install chezmoi
`brew install chezmoi`
1. Apply dotfiles
`chezmoi init --apply michaelfransen`

## Start your own dotfiles
Want to use Chezmoi to manage your own dotfiles? The best way to get started is to follow the Chezmoi [Quick Start Guide](https://www.chezmoi.io/quick-start/) to start tracking your first dotfile (~/.bashrc, ~/.zshrc, or ~/.gitconfig are great files to start with). Beyond that, I hope you can find some inspiration by looking at my dotfiles and copying things you like!

## Credit
These dotfiles were inspired by a collection of developers in the community whos dotfiles I have used, referenced, or in some cases outright copied. I relied heavily on the dotfiles of @mkasberg, @erikkerber, and @brentleyjones. @mkasberg has written a great [blog post](https://www.mikekasberg.com/blog/2021/05/12/my-dotfiles-story.html) on dotifles. 

## Security
Did you find a vulnerability in my dotfiles? An exposed secret? Some other security issue? Please report vulnerabilities via email to mjfransen@gmail.com.