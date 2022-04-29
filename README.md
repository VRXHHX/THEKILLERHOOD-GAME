local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Made By 2ndalt", "Sentinel")
local Tab = Window:NewTab("InfMoney")
local Section = Tab:NewSection("Get Infinite Money")
Section:NewButton("Dupe Money", "Buy item dupe cash", function()

local args = {

        [1] = "Simple Dimple"

    }

    game:GetService("ReplicatedStorage").RemoteEvents.Sell:FireServer(unpack(args))

        local args = {

        [1] = "Simple Dimple"

    }

    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))

end)
Section:NewButton("Dupe Money (250)", "Get 250 money", function()

local args = {

        [1] = "Gummy Blue"

    }

    game:GetService("ReplicatedStorage").RemoteEvents.Sell:FireServer(unpack(args))

        local args = {

        [1] = "Gummy Blue"

    }

    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))

end)  
Section:NewButton("Dupe Money", "Buy item dupe cash", function()

local args = {

        [1] = "Amogus Purple"

    }

    game:GetService("ReplicatedStorage").RemoteEvents.Sell:FireServer(unpack(args))

        local args = {

        [1] = "Amogus Purple"

    }

    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))

end)
   
     


    





