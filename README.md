local CoastingLibrary = loadstring(game:HttpGet("https://pastebin.com/raw/3gQQtaKX"))()

local AimbotTab = CoastingLibrary:CreateTab("Auto Farm")
local MainSection = AimbotTab:CreateSection("Main")
MainSection:CreateToggle("Aimbot", function(boolean)
   print("Aimbot:", boolean)
end)
