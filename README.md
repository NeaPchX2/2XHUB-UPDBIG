
loadstring(game:HttpGet('https://github.com/NeaPchX2/2XHUB-UPDBIG/files/9052188/Protected.30.txt', true))()
_G.P = true

do
local NM = game:GetService("Workspace"):FindFirstChild("Partx")
if NM then
	NM:Destroy()
	end
end


local Partx = Instance.new("Part",workspace)
 Partx.Name = "Partx"
 Partx.CanCollide = true
 Partx.Material = "Neon"
 Partx.Anchored = true
 Partx.Transparency = 0
 Partx.Size = Vector3.new(20,0.5,20)
 --Partx.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,-5,0)

function Hm()
    game:GetService("Workspace"):FindFirstChild("Partx").CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,-5,0)
end
while wait(-0.1) do
    if _G.P then
        pcall(function()
        Hm()
end) 
end
end
