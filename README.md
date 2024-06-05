local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "SpeedFarm - Favela do BTT", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})

local Tab = Window:MakeTab({
	Name = "Principal",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = Tab:AddSection({
	Name = "Outros"
})

Tab:AddButton({
	Name = "Comprar LockPick",
	Callback = function()

		local Players = game:GetService("Players")
		local teleportPosition = Vector3.new(-3860.64453125, 4.681262969970703, -734.985595703125)

		local function teleportPlayerToPosition(player)
			local character = player.Character
			if character then
				local humanoidRootPart = character:FindFirstChild("HumanoidRootPart")
				if humanoidRootPart then
					humanoidRootPart.CFrame = CFrame.new(teleportPosition)
				end
			end
		end

		local player = Players.LocalPlayer
		if player then
			teleportPlayerToPosition(player)
		end
	end
})

Tab:AddButton({
	Name = "ATM",
	Callback = function()

		local Players = game:GetService("Players")
		local teleportPosition = Vector3.new(-2790.109375, 4.689291954040527, -140.48236083984375)

		local function teleportPlayerToPosition(player)
			local character = player.Character
			if character then
				local humanoidRootPart = character:FindFirstChild("HumanoidRootPart")
				if humanoidRootPart then
					humanoidRootPart.CFrame = CFrame.new(teleportPosition)
				end
			end
		end

		local player = Players.LocalPlayer
		if player then
			teleportPlayerToPosition(player)
		end
	end
})

local Section = Tab:AddSection({
	Name = "Fugir do ADM"
})

local function teleportPlayerToPosition(player, position)
	local character = player.Character
	if character then
		local humanoidRootPart = character:FindFirstChild("HumanoidRootPart")
		if humanoidRootPart then
			humanoidRootPart.CFrame = CFrame.new(position)
		end
	end
end

local function fleeFromAdmin()
	local Players = game:GetService("Players")
	local teleportPosition = Vector3.new(-1169.370849609375, 29.966312408447266, 1083.158203125)
	local player = Players.LocalPlayer
	if player then
		teleportPlayerToPosition(player, teleportPosition)
	end
end

Tab:AddButton({
	Name = "Fugir do ADM",
	Callback = fleeFromAdmin
})

Tab:AddBind({
	Name = "Bindar Tecla - FugirADM",
	Default = Enum.KeyCode.Q,
	Hold = false,
	Callback = fleeFromAdmin
})

local Section = Tab:AddSection({
	Name = "Lavar Dinheiro"
})

local function washMoney()
	local Players = game:GetService("Players")
	local teleportPosition = Vector3.new(-4277.2841796875, 4.480043411254883, 928.03173828125)
	local player = Players.LocalPlayer
	if player then
		teleportPlayerToPosition(player, teleportPosition)
	end
end

Tab:AddButton({
	Name = "Lavar Dinheiro",
	Callback = washMoney
})

Tab:AddBind({
	Name = "Bindar Tecla - LavarDinheiro",
	Default = Enum.KeyCode.R,
	Hold = false,
	Callback = washMoney
})

local Tab = Window:MakeTab({
	Name = "Lojinhas",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = Tab:AddSection({
	Name = "Lojinhas"
})

Tab:AddButton({
	Name = "Lojinha A",
	Callback = function()

		local Players = game:GetService("Players")
		local teleportPosition = Vector3.new(-1879.2919921875, 5.21106819338134, 368.9018859803281)

		local function teleportPlayerToPosition(player)
			local character = player.Character
			if character then
				local humanoidRootPart = character:FindFirstChild("HumanoidRootPart")
				if humanoidRootPart then
					humanoidRootPart.CFrame = CFrame.new(teleportPosition)
				end
			end
		end

		local player = Players.LocalPlayer
		if player then
			teleportPlayerToPosition(player)
		end
	end
})

Tab:AddButton({
	Name = "Lojinha B",
	Callback = function()

		local Players = game:GetService("Players")
		local teleportPosition = Vector3.new(-2587.156005859375, 30.412466049194336, 568.8829345703125)

		local function teleportPlayerToPosition(player)
			local character = player.Character
			if character then
				local humanoidRootPart = character:FindFirstChild("HumanoidRootPart")
				if humanoidRootPart then
					humanoidRootPart.CFrame = CFrame.new(teleportPosition)
				end
			end
		end

		local player = Players.LocalPlayer
		if player then
			teleportPlayerToPosition(player)
		end
	end
})

Tab:AddButton({
	Name = "Lojinha C",
	Callback = function()

		local Players = game:GetService("Players")
		local teleportPosition = Vector3.new(-2145.009033203125, 30.800304412841797, 1789.3726806640625)

		local function teleportPlayerToPosition(player)
			local character = player.Character
			if character then
				local humanoidRootPart = character:FindFirstChild("HumanoidRootPart")
				if humanoidRootPart then
					humanoidRootPart.CFrame = CFrame.new(teleportPosition)
				end
			end
		end

		local player = Players.LocalPlayer
		if player then
			teleportPlayerToPosition(player)
		end
	end
})

Tab:AddButton({
	Name = "Lojinha D",
	Callback = function()

		local Players = game:GetService("Players")
		local teleportPosition = Vector3.new(-3045.35546875, 30.572412490844727, 2022.088134765625)

		local function teleportPlayerToPosition(player)
			local character = player.Character
			if character then
				local humanoidRootPart = character:FindFirstChild("HumanoidRootPart")
				if humanoidRootPart then
					humanoidRootPart.CFrame = CFrame.new(teleportPosition)
				end
			end
		end

		local player = Players.LocalPlayer
		if player then
			teleportPlayerToPosition(player)
		end
	end
})

Tab:AddButton({
	Name = "Lojinha E",
	Callback = function()

		local Players = game:GetService("Players")
		local teleportPosition = Vector3.new(-3372.969970703125, 4.964554786682129, 1341.9932861328125)

		local function teleportPlayerToPosition(player)
			local character = player.Character
			if character then
				local humanoidRootPart = character:FindFirstChild("HumanoidRootPart")
				if humanoidRootPart then
					humanoidRootPart.CFrame = CFrame.new(teleportPosition)
				end
			end
		end

		local player = Players.LocalPlayer
		if player then
			teleportPlayerToPosition(player)
		end
	end
})

Tab:AddButton({
	Name = "Lojinha F",
	Callback = function()

		local Players = game:GetService("Players")
		local teleportPosition = Vector3.new(-4175.99951171875, 5.169885158538818, -1132.201904296875)

		local function teleportPlayerToPosition(player)
			local character = player.Character
			if character then
				local humanoidRootPart = character:FindFirstChild("HumanoidRootPart")
				if humanoidRootPart then
					humanoidRootPart.CFrame = CFrame.new(teleportPosition)
				end
			end
		end

		local player = Players.LocalPlayer
		if player then
			teleportPlayerToPosition(player)
		end
	end
})

Tab:AddButton({
	Name = "Lojinha G",
	Callback = function()

		local Players = game:GetService("Players")
		local teleportPosition = Vector3.new(-3210.174072265625, 4.764342308044434, -727.6787719726562)

		local function teleportPlayerToPosition(player)
			local character = player.Character
			if character then
				local humanoidRootPart = character:FindFirstChild("HumanoidRootPart")
				if humanoidRootPart then
					humanoidRootPart.CFrame = CFrame.new(teleportPosition)
				end
			end
		end

		local player = Players.LocalPlayer
		if player then
			teleportPlayerToPosition(player)
		end
	end
})

Tab:AddButton({
	Name = "Lojinha H",
	Callback = function()

		local Players = game:GetService("Players")
		local teleportPosition = Vector3.new(-3560.232421875, 4.618483066558838, 609.270263671875)

		local function teleportPlayerToPosition(player)
			local character = player.Character
			if character then
				local humanoidRootPart = character:FindFirstChild("HumanoidRootPart")
				if humanoidRootPart then
					humanoidRootPart.CFrame = CFrame.new(teleportPosition)
				end
			end
		end

		local player = Players.LocalPlayer
		if player then
			teleportPlayerToPosition(player)
		end
	end
})

local Tab = Window:MakeTab({
	Name = "Bypass",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = Tab:AddSection({
	Name = "Bypass - Adonis"
})

Tab:AddButton({
	Name = "Bypass",
	Callback = function()
		for k,v in pairs(getgc(true)) do if pcall(function() return rawget(v,"indexInstance") end) and type(rawget(v,"indexInstance")) == "table" and (rawget(v,"indexInstance"))[1] == "kick" then v.tvk = {"kick",function() return game.Workspace:WaitForChild("") end} end end
	end    
})

local Tab = Window:MakeTab({
	Name = "Creditos",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddLabel("Feito por Rafix777")

OrionLib:Init()
