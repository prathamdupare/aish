# aish

![Demo](/showcase.gif)

This is a simple Bash script designed to integrate AI for generating Unix shell commands..

- You will need an API key from Groq - [Generate it here](https://console.groq.com/keys). It's free!

- Just change the 'api_key' value in the script.

# Shebang Comments

#!/usr/bin/env bash

## This script is designed for systems with Bash installed and accessible in the PATH.

- Adjust the shebang below if using a different shell or setup:

- For Zsh: Replace the shebang with #!/usr/bin/env zsh if you prefer Zsh.

- For systems without /usr/bin/env: Directly specify the shell path, e.g., #!/bin/bash or #!/bin/zsh

# One-Step Command

1. Run the following command:

   ```bash
   chmod +x aish && mv aish ~/.local/bin/
   ```

2. Ensure `~/.local/bin` is in your `PATH`:
   ```bash
   echo $PATH
   ```
   If it’s not, add it to your shell configuration (e.g., `~/.bashrc` or `~/.zshrc`):
   ```bash
   export PATH="$HOME/.local/bin:$PATH"
   ```

This ensures the script is ready to run from anywhere immediately.
