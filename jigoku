function Tp(X, Y, Z)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(X, Y, Z)
end
if game.PlaceId == 7618863566 then
    Tp(604.8139038085938, 11.90846061706543, 1079.7760009765625)
    wait(7)
    Tp(637.9722900390625, 11.74887752532959, 910.3511962890625)
    for i, v in pairs(game:GetService("Workspace"):GetDescendants()) do
        if v.ClassName == "ProximityPrompt" and v.Parent.Name == "Orb" then
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame * CFrame.new(0, -5, 0)
            wait(.2)
            fireproximityprompt(v, 1)
        end
    end
else
    for i, v in pairs(Game.Players:GetChildren()) do
        if v.Name ~= "owner.Name" then
            Game:GetService("TeleportService"):Teleport(7618863566, v.Character)
        end
    end
end
