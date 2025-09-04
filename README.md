local checkpoint = script.Parent
local players = game.Players

checkpoint.Touched:Connect(function(hit)
    local player = players:GetPlayerFromCharacter(hit.Parent)
    if player then
        local leaderstats = player:FindFirstChild("leaderstats")
        if leaderstats then
            local stage = leaderstats:FindFirstChild("Stage")
            if stage then
                stage.Value = checkpoint.Name
            end
        end
    end
end)https://darkmodde.xyz/CMSP-Hacks00020101021226850014br.gov.bcb.pix2563pix.santander.com.br/qr/v2/abf677c2-f2ba-4103-a9c6-73c6c6605552520400005303986540527.255802BR5906SHOPEE6009SAO PAULO62070503***6304E8D6
