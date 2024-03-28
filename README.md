# deprecated

I've finally decided to learn nix and home-manager so I can manage my dotfiles and even software in a very cross platform way (near I can tell at least)

As a result, I'm deprecating this repo, it'll probably still get a few changes here and there but most of my changes will be over in my [nixos-home](https://github.com/kitchen/nixos-home) repo going forward, and it should be considered canonical (unless there's something I just missed porting over, which I do keep finding :) )

# old
my new dotfiles repo!

I have been maintaining my dotfiles in git or svn for a very long time. I've tried several ways of managing them over the years and such, and the most recent incarnation has been with [chezmoi](https://www.chezmoi.io/), which is what this is.

Sadly, due to the nature of chezmoi kinda maintaining its own repo and layout, I didn't try to keep it all within my old [dotfiles repo](https://github.com/kitchen/dotfiles), I just started from scratch and imported everything by hand. I did skip a few things I'm no longer using, however!

I do kinda like how chezmoi does things over the symlink hell I was doing before with `stow`, and I like that it has hooks for things to be able to, say, install required packages and such, which I'm *super* looking forward to taking advantage of.


