for i,v in pairs(game:GetService("Workspace").Live:GetChildren()) do
    if v.ClassName == "Model" then
        v.Humanoid.Health = die
end
end
