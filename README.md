# Installation Guide
- press cmd(ctrl) + space
- search for "terminal" & select terminal from the listed options
- Next, To Install homebrew paste this in terminal `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"` & press enter.
- Then using homebrew, install zsh by pasting `brew install zsh` and press enter.
- if it says brew not found, paste `echo >> "/Users/$USER/.zprofile"
echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> "/Users/$USER/.zprofile"
eval "$(/opt/homebrew/bin/brew shellenv)"` and press enter.
- press `source ~/.zshrc` & press enter.
- Then a cleaner ui called "oh my zsh" by pasting `sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"` & press enter.
- Then install node.js by pasting `brew install node` & press enter.
- verify everything so far is working by pasting `node -v` & press enter. It should show your node.js version. This tells you everything is working.
- now paste `npm install -g @anthropic-ai/claude-code` in your terminal and press enter. Claude code is installed!
- if above command does not work
- now press `claude` in your terminal & press enter
