local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Test Gui", "Midnight")
local Test1 = Window:NewTab("Test1")
local Test2 = Window:NewTab("Test2")
local Test1section = Tab:NewSection("Test1")
Test1section:NewSlider("WalkSpeed", "WalkFast 16-750", 750, 16, function(s)
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = s
end)

Section:NewButton("Give Sword", "You get a sword......", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/mhxekj7V"))()
end)





