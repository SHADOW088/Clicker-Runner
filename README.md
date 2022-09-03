local DiscordLib = loadstring(game:HttpGet"https://raw.githubusercontent.com/dawid-scripts/UI-Libs/main/discord%20lib.txt")()

local win = DiscordLib:Window("DirectServer")

local serv = win:Server("DirectServer", "")

local Info = serv:Channel("Info")

local Client = serv:Channel("Play")

local Local = serv:Channel("Local")


Client:Button("AutoFarm", function()
    local plr  =  game.Players.LocalPlayer
        while true do
            plr.Character.HumanoidRootPart.Position = Vector3.new(-4064.5, 15, 0)
            wait(1)
            plr.Character.HumanoidRootPart.Position = Vector3.new(-10064.5, 15, 0)
            wait(1)
            plr.Character.HumanoidRootPart.Position = Vector3.new(-22064.5, 15, 0)
            wait(1)
            plr.Character.HumanoidRootPart.Position = Vector3.new(-40064.5, 15, 0)
            wait(1)
            plr.Character.HumanoidRootPart.Position = Vector3.new(-64064.5, 15, 0)
            wait(1)
            plr.Character.HumanoidRootPart.Position = Vector3.new(-94064.5, 15, 0)
            wait(1)
            plr.Character.HumanoidRootPart.Position = Vector3.new(-130064, 15, 0)
            wait(1)
            plr.Character.HumanoidRootPart.Position = Vector3.new(-172064, 15, 0)
            wait(1)
            plr.Character.HumanoidRootPart.Position = Vector3.new(-220064, 15, 0)
            wait(1)
            plr.Character.HumanoidRootPart.Position = Vector3.new(-274064, 15, 0)
            wait(1)
            plr.Character.HumanoidRootPart.Position = Vector3.new(-346064, 40, 0)
            wait(1)
            plr.Character.HumanoidRootPart.Position = Vector3.new(-442064, 40, 0)
            wait(1)
            plr.Character.HumanoidRootPart.Position = Vector3.new(-275064, 90, 19000)
            wait(1)
            plr.Character.HumanoidRootPart.Position = Vector3.new(-113064, 90, 19000)
            wait(1)
            plr.Character.HumanoidRootPart.Position = Vector3.new(-442064, 90, 19000)
            wait(1)
            plr.Character.HumanoidRootPart.Position = Vector3.new(-442064, 90, 35000)
            wait(1)
    end
end)

Client:Button("Admin Infinity Yield", function()
    loadstring(game:HttpGet"https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source")()
end)
Client:Button("DoorDestroy", function()
	workspace.Lobby.Door:Destroy()
end)

Local:Textbox("Music", "ID", true, function(t)
    workspace.Sound.Music.Song.SoundId = t
end)

Local:Textbox("WalkSpeed", "Speed", true, function(t)
    plr.Character.Humanoid.WalkSpeed = t
end)

Info:Label("THX FOR USING THE SCRIPT!")

Info:Label("Scripter Error0242/Shadow08")

Info:Label("Video Editor Th3Martino")

Info:Label("Https://discord.gg/GfNEFhXG!")




