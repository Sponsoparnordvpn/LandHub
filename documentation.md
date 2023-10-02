# SGA development documentation
SGA development offer a complete lua obfuscator made by 
sponsoparnordvpn.
Here's an example on how to use
```lua
local obfuscator = loadstring(game:HttpGet("https://raw.githubusercontent.com/Sponsoparnordvpn/SGAdev/main/SGAobfuscator.txt"))()


obfuscator(
 [===[
  --// Paste your source here
  print("Hello World!")
 ]===],
 "SGA_" --- Variable name
)
```
I do not guarantee that it's not deobfuscatable but you can try it if you are interested.
sponso
