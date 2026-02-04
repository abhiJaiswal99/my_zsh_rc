# If you come from bash you might have to change your $PATH.
# export PATH=$HOME/bin:$HOME/.local/bin:/usr/local/bin:$PATH

# Path to your Oh My Zsh installation.
export ZSH="$HOME/.oh-my-zsh"

# Theme
ZSH_THEME="robbyrussell"

# Plugins
plugins=(git)

source $ZSH/oh-my-zsh.sh

#### ---------------------------------------------------------
#### JAVA SETUP
#### ---------------------------------------------------------

# Java (Homebrew openjdk@17)
export JAVA_HOME="/opt/homebrew/opt/openjdk@17"
export PATH="$JAVA_HOME/bin:$PATH"

#### ---------------------------------------------------------
#### ANDROID SDK SETUP
#### ---------------------------------------------------------

export ANDROID_HOME="$HOME/Library/Android/sdk"

export PATH="$ANDROID_HOME/emulator:$PATH"
export PATH="$ANDROID_HOME/platform-tools:$PATH"
export PATH="$ANDROID_HOME/tools:$PATH"
export PATH="$ANDROID_HOME/tools/bin:$PATH"

#### ---------------------------------------------------------
#### OTHER TOOLS
#### ---------------------------------------------------------

# Antigravity
export PATH="$HOME/.antigravity/antigravity/bin:$PATH"

#claude
export PATH="$PATH:/Users/your_username/.npm-global/bin"


# Standard macOS paths (ensure system commands like 'open' work)
export PATH="/usr/local/bin:/usr/bin:/bin:/usr/sbin:/sbin:$PATH"

# NVM configuration
export NVM_DIR="$HOME/.nvm"
[ -s "/opt/homebrew/opt/nvm/nvm.sh" ] && \. "/opt/homebrew/opt/nvm/nvm.sh"
[ -s "/opt/homebrew/opt/nvm/etc/bash_completion.d/nvm" ] && \. "/opt/homebrew/opt/nvm/etc/bash_completion.d/nvm"

# flashlight
export PATH="/Users/abhishekjaiswal/.flashlight/bin:$PATH"
export PATH="$HOME/.local/bin:$PATH"


# Android ADB
export PATH="$HOME/Library/Android/sdk/platform-tools:$PATH"
