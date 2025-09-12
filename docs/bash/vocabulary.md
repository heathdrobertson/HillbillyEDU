---
description: Editing Your Bash Profile
---

# Profile

## Profile File Names

* bash - `.bashrc` # Linux
* zsh - `.zshrc` # Mac

```bash
# Always run ls after cd
function cd {
  builtin cd "$@" && ls
}

# Prompt user before overwriting any files
alias cp='cp --interactive'
alias mv='mv --interactive'
alias rm='rm --interactive'

# Always show disk usage in a human readable format
alias df='df -h'
alias du='du -h'
```
