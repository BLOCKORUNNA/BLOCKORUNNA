local times = 0.1 --the delay

while true do
   wait(times)

local args = {
    [1] = "Basic"
}

game:GetService("ReplicatedStorage").Events.Abilitie:FireServer(unpack(args))

end
