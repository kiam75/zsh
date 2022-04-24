# ZSH
secure current ~/.zshrc  
`cp ~/.zshrc ~/zshrc_$(date +"%d_%m_%Y")` 
create a new file zshrc_test with the content of this .zshrc file form the git repo  
`vim ~/zshrc_test`  
"unload" current configuration 
`zsh -d -f`  
source the new conficuration for testing  
`source ~/zshrc_test`  
after testing replace the current .zshrc file  
