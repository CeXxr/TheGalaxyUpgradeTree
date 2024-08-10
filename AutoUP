while task.wait() do
    local mp = game.Workspace.Stats.Values.MegaPoints
    local mpf = game.Workspace.Buttons.MegaPointButtons

    for _, v in pairs(mpf:GetDescendants()) do
        if v.Name == "ClickDetector" then
            v.MaxActivationDistance = 9e9
            task.wait()
        end
    end

    if mpf.MegaPointButton1.ClickDetector then
    fireclickdetector(mpf.MegaPointButton1.ClickDetector)
    end
    task.wait(.5)
    if mpf.MegaPointButton2.ClickDetector then
    fireclickdetector(mpf.MegaPointButton2.ClickDetector)
    end
    task.wait(.5)
    if mpf.MegaPointButton3.ClickDetector then
    fireclickdetector(mpf.MegaPointButton3.ClickDetector)
    end
    task.wait(.5)
    if mpf.MegaPointButton9.ClickDetector then
    fireclickdetector(mpf.MegaPointButton9.ClickDetector)
    fireclickdetector(mpf.MegaPointButton4.ClickDetector)
    fireclickdetector(mpf.MegaPointButton5.ClickDetector)
    end
    task.wait(.5)
    if mpf.MegaPointButton7.ClickDetector then
    fireclickdetector(mpf.MegaPointButton7.ClickDetector)
    fireclickdetector(mpf.MegaPointButton8.ClickDetector)
    end
    task.wait(.5)
    if mpf.MegaPointButton10.ClickDetector then
    fireclickdetector(mpf.MegaPointButton10.ClickDetector)
    end
    if mpf.MegaPointButton11.ClickDetector then
    wait(5.1)
    fireclickdetector(mpf.Parent.UltraPrestigeButtons.UltraPrestigeReset.ClickDetector)
    end
end
