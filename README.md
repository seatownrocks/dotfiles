# dotfiles

Neovim, tmux and Fish shell config files. Neovim config based derived from Netherdrake's config but
modified to use vim-plug plugin manager.

Note that I receive the following error when launching neovim:

function <SNR>51_InitializePythonBuiltin..provider#python#Call..remote#host#Require..<SNR>54_RequirePythonHost, line 15
Vim(if):Channel was closed by the client
Failed to load python host. You can try to see what happened by starting Neovim with the environment variable $NVIM_PYTHON_LOG_FILE set to a file and opening the generated log file. Also, the host stderr will be available in Neovim log, so it may contain useful information. See also ~/.nvimlog.<Paste>

I am not sure if this is due to a missing python library locally or if I need to recompile neovim with a different version of python, or something else but just a warning if you are considering using this config.

Cheers.
