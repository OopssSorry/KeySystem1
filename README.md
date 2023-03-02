# Free UI Key System

**Simple convenient free key system**

Version: 1.2

▶ [Example code](https://github.com/OopssSorry/KeySystem1/blob/main/README.md#-example-)

▶ [Discord server](https://discord.com/invite/enmKTMQvFJ)

![Screenshot](https://github.com/OopssSorry/KeySystem1/blob/main/screenshot.png)

##	▶ Example ◀
```lua
_G._,_, Discord = 'discord.gg/enmKTMQvFJ'

,(function() loadstring(game:HttpGet("https://oopshub.vercel.app/libs/KeySystem1.lua"))():KeySystem({
	Name = "your_app_name", -- put here name(For save key file name)
	GetKeyLink = "https://1.kelprepl.repl.co/getkey/your_app_name", -- you can put here discord link
	VerifyLink = "https://1.kelprepl.repl.co/verify/your_app_name?verify_key=",-- KEY == game:HttpGet("https://1.kelprepl.repl.co/verify/your_app_name?verify_key="..KEY)
	SaveKey = true, -- just save key
	});end),[['..==LOL..']];_()
--Below your code
```
