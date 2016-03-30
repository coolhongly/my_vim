# User specific aliases and functions
alias rm='rm -i'
alias cp='cp -i'
alias mv='mv -i'
alias cmu='ssh hongliy@linux.andrew.cmu.edu'
alias cmu_x11='ssh -Y hongliy@linux.andrew.cmu.edu'
alias ec2='ssh -i /Users/coolhongly/.ssh/hongliyandrewcmuedu.pem ubuntu@52.88.111.180'
alias ctags="`brew --prefix`/bin/ctags"
alias ls='ls -G'
alias l='ls -G'
# alias vim='/usr/local/bin/mvim'

# Paths
export PATH="$HOME/Library/Android/sdk/platform-tools:$PATH"
export PATH="$HOME/.cabal/bin:$PATH"
export PATH="$HOME/Documents/CMU/Term3/15411/cc0/bin:$PATH"
export PATH="/usr/local/sbin:$PATH"
export PATH="/usr/local/opt/llvm/bin:$PATH"

parse_git_branch() {
  git branch 2> /dev/null | sed -e '/^[^*]/d' -e 's/* \(.*\)/ (\1)/'
}
export PS1="\[\033[32m\]\w\[\033[33m\]\$(parse_git_branch)\[\033[00m\] $ "

# Source global definitions
if [ -f /etc/bashrc ]; then
	. /etc/bashrc
fi
