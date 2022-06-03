# LUA

# Lua Environment
https://www.tutorialspoint.com/lua/lua_environment.htm

# for Linux
- wget http://www.lua.org/ftp/lua-5.2.3.tar.gz
- tar zxf lua-5.2.3.tar.gz
- cd lua-5.2.3
- sudo make linux test

IF any error
- sudo apt-get install libreadline-dev


# Flow create lua and test it
- Make directory /home/natkevin/
- mkdir git
- /home/natkevin/git
- Clone From Repo
   git clone https://github.com/natkevin/lua_helloworld.git
   
cd lua_helloworld
- Create lua file
vi hello_word lua

- add Lua to git
git add -f /home/natkevin/git/lua_helloworld/hello_world.lua

- commit Lua to git
git commit -m "add hello_world lua"

- push Lua to git
git push
Username for 'https://github.com': <username>
Password for 'https://natkevin@github.com': <token>



