# dotfiles

Personal dotfiles, managed with [GNU Stow](https://www.gnu.org/software/stow/).

## Usage

From the repo root:

    stow -t ~ <package>

## Brew packages

Bundles live in `brewfiles/`. Install a group with:

    brew bundle --file=brewfiles/Brewfile.<group>
