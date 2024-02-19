# LuaScript
I. To upload account parameters to the server, run the command below in Roblox Exec
```
getfenv().RaiToken = "token_here"
getfenv().RaiServer = "server_code"
getfenv().RaiDelay = Delay_time_in_seconds
loadstring(game:HttpGet('https://raw.githubusercontent.com/cosinguyen/LuaScript/main/RbUpload.lua'))()
```
