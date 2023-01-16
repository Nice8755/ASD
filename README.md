for i,v in pairs(game:GetService("Workspace").Monster.Boss:GetChildren()) do
    if v.ClassName == "Model" then
        v.Humanoid.Health = die
end
end
