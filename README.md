for i,v in pairs(game:GetService("Workspace").NPCs:GetChildren()) do
    if v.ClassName == "Model" then
        v.Humanoid.Health = die
end
end
