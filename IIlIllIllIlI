local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()

local Window = Rayfield:CreateWindow({
   Name = "💪 KCE HUB | Free Script 💪",
   Icon = 0, -- Icon in Topbar. Can use Lucide Icons (string) or Roblox Image (number). 0 to use no icon (default).
   LoadingTitle = "Muscle Legends 💪",
   LoadingSubtitle = "by xangelz/zeak  ",
   Theme = "Default", -- Check https://docs.sirius.menu/rayfield/configuration/themes

   DisableRayfieldPrompts = false,
   DisableBuildWarnings = false, -- Prevents Rayfield from warning when the script has a version mismatch with the interface

   ConfigurationSaving = {
      Enabled = true,
      FolderName = nil, -- Create a custom folder for your hub/game
      FileName = "Big Hub"
   },

   Discord = {
      Enabled = false, -- Prompt the user to join your Discord server if their executor supports it
      Invite = "noinvitelink", -- The Discord invite code, do not include discord.gg/. E.g. discord.gg/ ABCD would be ABCD
      RememberJoins = true -- Set this to false to make them join the discord every time they load it up
   },

   KeySystem = true, -- Set this to true to use our key system
   KeySettings = {
      Title = "Muscle Legends | Key",
      Subtitle = "Dm _xangelz or felix7.9m on Discord",
      Note = "Dm _xangelz or felix7.9m on Discord", -- Use this to tell the user how to get a key
      FileName = "examplehubkey", -- It is recommended to use something unique as other scripts using Rayfield may overwrite your key file
      SaveKey = true, -- The user's key will be saved, but if you change the key, they will be unable to use your script
      GrabKeyFromSite = true, -- If this is true, set Key below to the RAW site you would like Rayfield to get the key from
      Key = {"https://pastebin.com/raw/WFAx5r2K"} -- List of keys that will be accepted by the system, can be RAW file links (pastebin, github etc) or simple strings ("hello","key22")
   }
})

local MainTab = Window:CreateTab("Main", nil) -- Title, Image
local MainSection = MainTab:CreateSection("AutoFarm")

Rayfield:Notify({
   Title = "You Executed Script",
   Content = "Sub to xangelz0",
   Duration = 5,
   Image = nil,
})
local Button = MainTab:CreateButton({
   Name = "xangelz v0",
   Callback = function()
    loadstring(game:HttpGet("https://pastebin.com/raw/zmvGeZwP"))()
   end,
})
