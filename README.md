BANNED = {}

if table.find(BANNED, game:GetService("Players").LocalPlayer.UserId) then
    game:GetService("Players").LocalPlayer:Kick(game.Players.LocalPlayer.Name.." Is Banned, Direct Message Space#3245 For An Appeal!")
end
