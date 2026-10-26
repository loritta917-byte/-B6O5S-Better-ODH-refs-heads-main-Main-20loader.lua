
--> Overdrive H On Top

local shared = odh_shared_plugins

-- Cria uma aba para o plugin
local tab = shared.CreateTab("67", nil)

-- Cria uma seção
local section = tab:AddSection("67", "")

-- Cria apenas um botão
section:AddButton("67", function()
    print("Você clicou no botão 67!")

    if shared.Notify then
        shared.Notify("67", 2)
    end
end)
.
