## Install

```fish
$ fisher install pcleavelin/fish-simple-ass-prompt
```
Or alternatively, just copy the `functions` directory to your fish config directory.

## Fork of lfiohais's [simple-ass-prompt][original_repo]
I've made a few changes, most notably the switch to allowing [fisher][fisher],
but also:
 * Displaying whether you are in a nix-shell or not.
 * Using `rustc` for the rust version instead of `rustup`

## Features
This is [Mathias Bynens][mths] Bash prompt ported to Fish with a few changed
icons and added functionalities.

Features:

- A dirty state of the branch is displayed by `!`
- Untracked files are displayed by `☡`
- The existence of a stash is displayed by `↩`
- A clean branch is displayed by `✓`
- The branch is ahead with `+`
- The branch is behind with `-`
- The branch has diverged from upstream `±`
- Support for Pythons virtual environments
- Support Rust active toolchain
- The last command failed is displayed with `↪` in red

## Configuration
You can change the greeting message with:
```fish
set -g simple_ass_prompt_greeting MyGreeting
```

# License

[MIT][mit] © [pcleavelin][author]


[mit]:            http://opensource.org/licenses/MIT
[author]:         http://github.com/pcleavelin
[mths]: https://github.com/mathiasbynens/dotfiles
[original_repo]: https://github.com/lfiolhais/theme-simple-ass-prompt
[fisher]: https://github.com/jorgebucaran/fisher
