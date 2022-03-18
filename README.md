wait(0)
   local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
   local Window = Library.CreateLib("EmirHUB", "Synapse")


   

--PrisonLife
   local Prison = Window:NewTab("Animal Similator")
   local PrisonSection = Prison:NewSection("Auto Farm")
   local TrollSection = Prison:NewSection("Troll Menusu")
   PrisonSection:NewButton("Treasure1", "Guns", function()
 local A_1 = game:GetService("Workspace").Treasures.Treasure1
local Event = game:GetService("ReplicatedStorage").TreasureEvent
Event:FireServer(A_1)

end)

   PrisonSection:NewButton("Treasure2", "Guns", function()
local A_1 = game:GetService("Workspace").Treasures.Treasure2
local Event = game:GetService("ReplicatedStorage").TreasureEvent
Event:FireServer(A_1)

end)

   PrisonSection:NewButton("Treasure3", "Guns", function()
local A_1 = game:GetService("Workspace").Treasures.Treasure3
local Event = game:GetService("ReplicatedStorage").TreasureEvent
Event:FireServer(A_1)

end)
   PrisonSection:NewButton("En Az Veren", "Gate", function()
    				local A_1 = game:GetService("Workspace").NPC.LavaGorilla.Humanoid
local A_2 = 3
local Event = game:GetService("ReplicatedStorage").jdskhfsIIIllliiIIIdchgdIiIIIlIlIli
Event:FireServer(A_1, A_2)
end)


local txttte = txxxt
TrollSection:NewTextBox("Kisiyi Trolle", "Troller", function(txt)
    if Enter then
local A_1 = game:GetService("Workspace").txt.Humanoid
local A_2 = 2
local Event = game:GetService("ReplicatedStorage").jdskhfsIIIllliiIIIdchgdIiIIIlIlIli
Event:FireServer(A_1, A_2)
end
end)
