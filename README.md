
_G.Key = " "

local keychecked = false
local hwid = nill
local hwidplr = game:GetService("RbxAnalyticsService"):GetClientId()

if _G.Key == "MA-7988-999" then
      hwid = "7ac1b16c-132c-4aae-b295-14eca674dc08"
      keychecked = true
end

if keychecked == true then
if hwidplr == hwid then
        loadstring(game:HttpGet('https://link.trwxz.com/LS-Wolf-Hub'))()
    else
     game.Players.LocalPlayer:Kick("incorrect hwid")
 end
 else
       game.Players.LocalPlayer:Kick("incorrect key")
 end


setclipboard(game:GetService("RbxAnalyticsService"):GetClientId())
