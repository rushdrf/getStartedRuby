# Introduction to Ruby Programming
## Prerequisite & steps to setup Ruby for Windows users
1. Download Ruby SDK: https://rubyinstaller.org/
   - type "ruby -v" in command prompt/powershell to check whether Ruby has been install or not.
2. Editor: Visual Studio Code -> Install Visual Studio Code
3. In VScode extension install Ruby LSP.
4. Create one file named .ruby-version
   `
   {
     "rubyLsp.rubyVersionManager": {
       "identifier": "rbenv"
     }
   }
   `
6. Create one .rb file and type
   `puts "Hello, Ruby!";`
   Save it. And in terminal type "ruby [filename].rb"

## Debug Ruby using VScode
1. Create launch.json file at the run & debug panel.
2. Test the debug by put the debugger in the code.
