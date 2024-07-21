# NRHDXBABYBOT

[![Build status](https://ci.appveyor.com/api/projects/status/m07cnunnni8w82o5?svg=true)](https://ci.appveyor.com/project/madskristensen/markdowneditor)

### COOMINGSOON

![image](https://cdn.discordapp.com/attachments/1190923462546558979/1264653227375198361/Screenshot_51.png?ex=669ea799&is=669d5619&hm=e714ac17a4ab2d99ec281979c0417fff87a4f743c1eb5f52fca9e84d25403709&)
#### Example CONFIG.LUA

```lua
Config = {}

Config.Framework = 'QB'
Config.FrameworkCore = 'qb-core'

Config.Notification = function(message, type)
    TriggerEvent('QBCore:Notify', message, type, 5000)
end

Config.PayMethod = 'cash' --GANTI SESUAI KEINGINAN CASH/BANK

Config.Items = {
    ['water_bottle'] = {
        category = "category_1",
        display = "minuman",
        price = 1000,
        description = "rasa nya wenak sekali, ...",
    },
    ['resto-baso'] = {
        category = "category_1",
        display = "baso",
        price = 1000,
        description = "rasa nya wenak sekali, ...",
    },
}

Config.Locale = {
    buyed = "BERHASIL BELI $%s.",
    nomoney = "KMU TIDAK PUNYA UANG !",
    Interact = "WARLOG PEDAGANG",
}

Config.Shops = {
    --hadi{ vector3(-299.4, 6261.97, 31.48), blipname = "Store", blipsprite = 590, blipcolor = 0, blipscale = 1.0, dist = 2.5 },
}

Config.NPCs = {
    {
        model = "a_m_m_business_01",
        coords = vector4(-299.39, 6261.97, 30.48, 134.1),
    },
}

```


- TARUH FOLDER DAN EXTRAX
- ensure fivemnpctagtext di file server.cfg
# Dependencies

* [qbcore framework](https://github.com/qbcore-framework)
