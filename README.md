LetCmd
 
A custom god-mode terminal for Windows, statically compiled in C++ as a single executable with no dependencies.
 
Core Features
 
- Forced password setup on first run. Password is stored locally in let_pwd.dat.
​
- Built-in real CMD pipeline, supports all standard Windows CMD commands.
​
- SYSTEM privilege execution after unlocking with the let command.
​
- Administrator mode for launching apps with elevated rights.
​
- Lightweight, clean, and portable.
​
- Can be placed in System32 for global system-wide access.
 
Commands
 
let [password]      Unlock god mode
let [program]       Run a program with SYSTEM privileges
let cd [drive]      Simulate system backup
let wq [src] [dst]  Simulate system restore
admin [program]     Run a program as administrator
cmd go              Enter native CMD mode
cmd exit            Return to LetCmd
help                Show command list
wq                  Exit the program
js                  Open calculator
 
Password Storage
 
- On first launch, you must set a password to continue.
​
- The password is saved in let_pwd.dat in the same directory.
​
- To reset the password, delete let_pwd.dat and restart LetCmd.
 
Build Requirements
 
- Visual Studio 2022 or later
​
- Release x64 configuration
​
- Runtime Library: Multi-threaded (/MT)
​
- C++20 Standard
 
Usage
 
1. Download the release executable
​
2. Run LetCmd.exe
​
3. Set your password on first launch
​
4. Unlock using "let [yourpassword]"
​
5. Use god-mode commands freely
 
License
 
MIT License