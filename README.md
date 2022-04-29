local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Made By 2ndalt", "Sentinel")
local Tab = Window:NewTab("InfMoney")
local Section = Tab:NewSection("Get Infinite Money")
Section:NewButton("1.get money", "Buy item dupe cash", function()

local args = {

        [1] = "Gummy Blue"

    }

    game:GetService("ReplicatedStorage").RemoteEvents.Sell:FireServer(unpack(args))

        local args = {

        [1] = "Gummy Blue"

    }

    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))

end)
    
     


    





