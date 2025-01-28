# HEADING

hello world

# sub heading

STILL TESTING

# WHAT DID I LEARN?

I learnt how to clone a repo straight in vs code, how to generate and use SSH keys 
how to set up an ssh agent

# HOW TO GENERATE AN SSH KEY

1. OPEN GIT BASH
2. clone your repo
3.enter your repo
4. in the terminal
5. TYPE ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
6. press enter to use default key name or type new name after colon
7. press enter touse default keyphrase
8. type cat ~/.ssh/id_rsa to show ssh key if you used the default key or cat newname if you used a new key name to shojw key
9. copy key and in github got to settings under access click shh and gps keys 
10. click on add new
11. enter key name
12. paste key

# SETTING UP AN SSH AGENT
IN TERMINAL
1. TYPE eval "$(ssh-agent -s)" and hit enter
2. type ssh-add ~/.ssh/id_rsa or ssh-add newname

1. Open index.html in browser
