# zsh-git-flow-avh

This plugin adds short aliases for the [`git-flow (AVH Edition)`](https://github.com/petervanderdoes/gitflow-avh) commands.

## Usage

Without typing full `git-flow` commands in console, like:

   ```zsh
   git flow feature start some-feature
   ```

there is more convenient alias:

   ```zsh
   gflfs some-feature
   ```

## Installation

#### zplug

1. Add the following to your `.zshrc`:

   ```zsh
   zplug "nekofar/zsh-git-flow-avh"
   ```

2. Start a new terminal session.

#### Antigen

1. Add the following to your `.zshrc`:

   ```zsh
   antigen bundle nekofar/zsh-git-flow-avh
   ```

2. Start a new terminal session.

#### Oh My Zsh

1. Clone this repository into `$ZSH_CUSTOM/plugins` (by default `~/.oh-my-zsh/custom/plugins`)

   ```zsh
   git clone https://github.com/nekofar/zsh-git-flow-avh \
     ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-git-flow-avh
   ```

2. Add the plugin to the list of plugins for Oh My Zsh to load (inside `~/.zshrc`):

   ```zsh
   plugins=( [plugins...] zsh-git-flow-avh)
   ```

3. Start a new terminal session.

## Requirements

1. The git-flow tool has to be [installed](https://github.com/petervanderdoes/gitflow-avh#installing-git-flow)
   separately.
