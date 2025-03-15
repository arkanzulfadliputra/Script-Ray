local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()

local Window = Rayfield:CreateWindow({
   Name = "Scp SCRIPT",
   Icon = 0, -- Icon in Topbar. Can use Lucide Icons (string) or Roblox Image (number). 0 to use no icon (default).
   LoadingTitle = "Rayfield Interface Suite",
   LoadingSubtitle = "by SKAYS GAMING",
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

   KeySystem = True, -- Set this to true to use our key system
   KeySettings = {
      Title = "SKAYS GAMING",
      Subtitle = "Key System",
      Note = "Game In Work SCP", -- Use this to tell the user how to get a key
      FileName = "Key", -- It is recommended to use something unique as other scripts using Rayfield may overwrite your key file
      SaveKey = true, -- The user's key will be saved, but if you change the key, they will be unable to use your script
      GrabKeyFromSite = false, -- If this is true, set Key below to the RAW site you would like Rayfield to get the key from
      Key = {"SKAYS"} -- List of keys that will be accepted by the system, can be RAW file links (pastebin, github etc) or simple strings ("hello","key22")
   }
})

local Tab = Window:CreateTab("ROOM GAMEPASS", 4483362458) -- Title, Image

local Section =
Tab:CreateSection("GAMEPASS")

local Paragraph = Tab:CreateParagraph({Title = "WARNING GAMEPASS", Content = "Gamepass Unlock Game SCP NOT ALL GAME"})

local Button = Tab:CreateButton({
   Name = "Unlock Rooms",
   Callback = function()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "Free Gamepass",
   Callback = function()
   -- The function that takes place when the button is pressed
   end,
})

local Tab = Window:CreateTab("Reawrd Badges", 4483362458) -- Title, Image

local Section = Tab:CreateSection("REWARD BADGES")

local Paragraph = Tab:CreateParagraph({Title = "WARNING BADGES", Content = "BADGES IN WORK GAME SCP"})

local Button = Tab:CreateButton({
   Name = "Unlock Rooms Badges",
   Callback = function()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "Gets All Badges",
   Callback = function()
   -- The function that takes place when the button is pressed
   end,
})

local Tab = Window:CreateTab("MORPH", 4483362458) -- Title, Image

local Section = Tab:CreateSection("MORPH")

local Paragraph = Tab:CreateParagraph({Title = "MORPH", Content = "WORK GAME SCP"})

local Button = Tab:CreateButton({
   Name = "SCP 096 SAD",
   Callback = function()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "SCP 096 V2",
   Callback = function()
   -- The function that takes place when the button is pressed
   end,
})

local Button = Tab:CreateButton({
   Name = "SCP 300",
   Callback = function()
   -- The function that takes place when the button is pressed
   end,
})
