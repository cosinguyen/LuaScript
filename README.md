# LuaScript
I. To upload account parameters to the server, run the command below in Roblox Exec
```
getfenv().RaiDelay = delay-time-in-second
getfenv().RaiNote = "your-upload-note"
getfenv().RaiServer = {
  licenseid = "your-license-id",
  apikey = "your-license-api-key"
}
loadstring(game:HttpGet('https://raw.githubusercontent.com/cosinguyen/LuaScript/main/raiUpload.lua'))()
```
