# ===============================
# ZSH CONFIGURATION FILE
# (Rust + Backend Dev)
# ===============================

# ---- OH-MY-ZSH ----
export ZSH="$HOME/.oh-my-zsh"
ZSH_THEME="robbyrussell"
plugins=(git zsh-autosuggestions zsh-syntax-highlighting)

source $ZSH/oh-my-zsh.sh

# ---- ENVIRONMENT VARIABLES ----
export RUST_HOME="$HOME/.rustup"
export CARGO_HOME="$HOME/.cargo"
export DEV_HOME="$HOME/dev"

export PATH="$CARGO_HOME/bin:$PATH"

# ---- ALIASES (PRODUCTIVITY) ----
alias ll="ls -la"
alias gs="git status"
alias ga="git add ."
alias gc="git commit -m"
alias gp="git push"
alias gl="git pull"
alias cls="clear"
alias rs="cargo run"
alias rb="cargo build"
alias rt="cargo test"

# ---- HISTORY SETTINGS ----
HISTSIZE=10000
SAVEHIST=10000
setopt share_history
setopt hist_ignore_dups

# ---- SHELL BEHAVIOR ----
setopt autocd
setopt correct

# ---- PROMPT ----
PROMPT='%F{cyan}%n@%m %F{yellow}%~ %# %f'

# ---- COMPLETION ----
autoload -Uz compinit
compinit