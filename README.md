local Libary = loadstring(game:HttpGet("https://pastefy.app/aDoohc6D/raw", true))()
workspace.FallenPartsDestroyHeight = -math.huge

local Window = Libary:MakeWindow({
    Title = "Molesta Hub",
    SubTitle = "Criado por: lucas",
    LoadText = "Carregando Molestamento",
    Flags = "Molesta_Broookhaven"
})
Window:AddMinimizeButton({
    Button = { Image = "rbxassetid://", BackgroundTransparency = 0 },
    Corner = { CornerRadius = UDim.new(35, 1) },
})

local InfoTab = Window:MakeTab({ Title = "Info", Icon = "rbxassetid://15309138473" })



InfoTab:AddSection({ "Informações do Script" })
InfoTab:AddParagraph({ "Dev", "Lucas" })
InfoTab:AddParagraph({"Informações", Este Hub e a v1,eu criei ele com ajuda de colaboradores,dentre eles lk e Silva...obrigado a todos voçeis por ajudar!.})
InfoTab:AddParagraph({"Seu executor:", executor})

InfoTab:AddSection({ "Re-entrar" })
InfoTab:AddButton({
    Name = "Re-entrar",
    Callback = function()
        local TeleportService = game:GetService("TeleportService")
        TeleportService:TeleportToPlaceInstance(game.PlaceId, game.JobId, game.Players.LocalPlayer)
    end
})



