local Fluent = loadstring(game:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()
local SaveManager = loadstring(game:HttpGet("https://raw.githubusercontent.com/dawid-scripts/Fluent/master/Addons/SaveManager.lua"))()
local InterfaceManager = loadstring(game:HttpGet("https://raw.githubusercontent.com/dawid-scripts/Fluent/master/Addons/InterfaceManager.lua"))()
--//

local Window = Fluent:CreateWindow({
    Title = "kamui x hub", --Título do seu Hub
    SubTitle = "by ford dev",--sub título do seu Hub
    TabWidth = 160,
    Size = UDim2.fromOffset(560, 350),--Largura e Estatura do seu hub / Tamanho.
    Acrylic = true, --Blur
    Theme = "Darker",--Temas da cor: [ Dark, Darker, White, Rose, Aqua, Amethyst.
    MinimizeKey = Enum.KeyCode.LeftControl --Key para minimizar o seu hub
})
--//

local Tabs = {
   Main = Window:AddTab({ Title = "Main", Icon = "cloud" }),
   Settings = Window:AddTab({ Title = "Settings", Icon = "settings" })
}
Tabs.Main:AddButton({
        Title = "invisível",--título do botão
        Description = "..",--Descrição do botão
        Callback = function()
loadstring(game:HttpGet('https://pastebin.com/raw/3Rnd9rHf'))()
        end
    })
