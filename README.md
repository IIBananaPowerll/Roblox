# Roblox
Dungeon Quest info:

_G.idk = {
    ["GetDaily"] = false, --Will auto get daily reward
    autopoints = {
        ["Enabled"] = true,
        ["Point"] = "physicalPower" --Types: physicalPower, spellPower, stamina
    }
}

_G.shit = { --Normal dungeon autofarm
    ["Enabled"] = true, --Turn off / on normal autofarm
    ["AutoDungeon"] = true, --Will find the best dungeon
    moarshit = {
        ["Enabled"] = true, --Custom dungeon settings
        ["CustomDungeon"] = "Orbital Outpost",
    },
    ["Difficulty"] = "Nightmare", --This will change if you uh have auto dungeon on
    ["Hardcore"] = true,
    ["Name_Protect"] = true,
    namesettings = {
        ["CustomName"] = "Player",
        ["CustomLevel"] = "78787878787877",
        ["CustomExp"] = "69billion",
        ["CustomHp"] = "69",
        ["CustomMoney"] = "69",
        ["CustomSnowflakes"] = "69",
        ["CustomImage"] = "https://www.roblox.com/asset-thumbnai..."
    }
}

_G.Raid = { --Raid autofarm
    ["Enabled"] = false,
    ["Auto"] = false, --Will auto find your best key
  ["Tier"] = 20, --Does not matter what you put in here if you have auto set 2 true.
  ["wait_time"] = 0 --If you have good gear, just leave this at 0, if you have bad gear read this:
  --The more time you wait = more damage.
  --READ THIS OKAY: Only spells that has 4 seconds of cooldown, or less will work with the spell spammer.
}

_G.test = { --Autosell 
    ["Common"] = true,
    ["Uncommon"] = true,
    ["Rare"] = false,
    ["Epic"] = false,
    ["Legendary"] = false,
}
