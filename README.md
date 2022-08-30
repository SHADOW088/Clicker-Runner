local DiscordLib = loadstring(game:HttpGet"https://raw.githubusercontent.com/dawid-scripts/UI-Libs/main/discord%20lib.txt")()

local win = DiscordLib:Window("DirectServer")

local serv = win:Server("DirectServer", "")

local Farm = serv:Channel("Player")
local plr  =  game.Players.LocalPlayer

Farm:Button("AutoFarm", function()
    local plr  =  game.Players.LocalPlayer
        while true do
            plr.Character.HumanoidRootPart.Position = Vector3.new(-4064.5, 15, 0)
            wait()
            plr.Character.HumanoidRootPart.Position = Vector3.new(-10064.5, 15, 0)
            wait()
            plr.Character.HumanoidRootPart.Position = Vector3.new(-22064.5, 15, 0)
            wait()
            plr.Character.HumanoidRootPart.Position = Vector3.new(-40064.5, 15, 0)
            wait()
            plr.Character.HumanoidRootPart.Position = Vector3.new(-64064.5, 15, 0)
            wait()
            plr.Character.HumanoidRootPart.Position = Vector3.new(-94064.5, 15, 0)
            wait()
            plr.Character.HumanoidRootPart.Position = Vector3.new(-130064, 15, 0)
            wait()
            plr.Character.HumanoidRootPart.Position = Vector3.new(-172064, 15, 0)
            wait()
            plr.Character.HumanoidRootPart.Position = Vector3.new(-220064, 15, 0)
            wait()
            plr.Character.HumanoidRootPart.Position = Vector3.new(-274064, 15, 0)
            wait()
            plr.Character.HumanoidRootPart.Position = Vector3.new(-346064, 40, 0)
            wait()
            plr.Character.HumanoidRootPart.Position = Vector3.new(-442064, 40, 0)
            wait()
            plr.Character.HumanoidRootPart.Position = Vector3.new(-275064, 90, 19000)
            wait()
            plr.Character.HumanoidRootPart.Position = Vector3.new(-113064, 90, 19000)
            wait()
            plr.Character.HumanoidRootPart.Position = Vector3.new(-442064, 90, 19000)
            wait()
            plr.Character.HumanoidRootPart.Position = Vector3.new(-442064, 90, 35000)
            wait()
    end
end)







