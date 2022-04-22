# Script-dahood-funny
Dc : Pedro27#0017

script:

local ScreenGui = Instance.new("ScreenGui")
local Main = Instance.new("ImageLabel")
local Corner1 = Instance.new("UICorner")
local MainUnderlay = Instance.new("ImageLabel")
local UICorner = Instance.new("UICorner")
local Background = Instance.new("ImageLabel")
local UICorner_2 = Instance.new("UICorner")
local NameWelcome = Instance.new("TextLabel")
local WelcomeText = Instance.new("TextLabel")
local Dahood = Instance.new("Frame")
local UICorner_3 = Instance.new("UICorner")
local Fly1 = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local ChatSpy1 = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local Faded = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local Notification1 = Instance.new("ImageLabel")
local UICorner_7 = Instance.new("UICorner")
local Underlay1 = Instance.new("ImageLabel")
local UICorner_8 = Instance.new("UICorner")
local NotiHead1 = Instance.new("TextLabel")
local NotiMsg1 = Instance.new("TextLabel")
local CountDown1 = Instance.new("TextLabel")
local Notification2 = Instance.new("ImageLabel")
local UICorner_9 = Instance.new("UICorner")
local Underlay2 = Instance.new("ImageLabel")
local UICorner_10 = Instance.new("UICorner")
local NotiHead2 = Instance.new("TextLabel")
local NotiMsg2 = Instance.new("TextLabel")
local CountDown2 = Instance.new("TextLabel")

--Properties:

ScreenGui.Parent = game.CoreGui
ScreenGui.ResetOnSpawn = false

Main.Name = "Main"
Main.Parent = ScreenGui
Main.AnchorPoint = Vector2.new(0.5, 0.5)
Main.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Main.BackgroundTransparency = 1.000
Main.Position = UDim2.new(0.5, 0, 0.499000013, 0)
Main.Size = UDim2.new(0, 20, 0, 20)
Main.Image = "rbxassetid://8269175594"
Main.ScaleType = Enum.ScaleType.Crop
Main.Active = true
Main.Draggable = true

Corner1.CornerRadius = UDim.new(0, 5)
Corner1.Name = "Corner1"
Corner1.Parent = Main

MainUnderlay.Name = "MainUnderlay"
MainUnderlay.Parent = Main
MainUnderlay.AnchorPoint = Vector2.new(0.5, 0.5)
MainUnderlay.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
MainUnderlay.Position = UDim2.new(0.497999996, 0, 0.5, 0)
MainUnderlay.Size = UDim2.new(0, 235, 0, 394)
MainUnderlay.Visible = false
MainUnderlay.ZIndex = 0
MainUnderlay.Image = "rbxassetid://8269154504"
MainUnderlay.ScaleType = Enum.ScaleType.Crop

UICorner.CornerRadius = UDim.new(0, 20)
UICorner.Parent = MainUnderlay

Background.Name = "Background"
Background.Parent = Main
Background.AnchorPoint = Vector2.new(0.5, 0.5)
Background.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Background.BackgroundTransparency = 1.000
Background.Position = UDim2.new(0.497999996, 0, 0.502376378, 0)
Background.Size = UDim2.new(0, 210, 0, 372)
Background.Image = "rbxassetid://8269190834"
Background.ImageTransparency = 1.000
Background.ScaleType = Enum.ScaleType.Crop

UICorner_2.CornerRadius = UDim.new(0, 20)
UICorner_2.Parent = Background

NameWelcome.Name = "NameWelcome"
NameWelcome.Parent = Background
NameWelcome.AnchorPoint = Vector2.new(0.5, 0.5)
NameWelcome.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
NameWelcome.BackgroundTransparency = 1.000
NameWelcome.Position = UDim2.new(0.5, 0, 0.115591399, 0)
NameWelcome.Size = UDim2.new(0, 200, 0, 40)
NameWelcome.Font = Enum.Font.Kalam
NameWelcome.Text = ""
NameWelcome.TextColor3 = Color3.fromRGB(0, 0, 0)
NameWelcome.TextScaled = true
NameWelcome.TextSize = 14.000
NameWelcome.TextTransparency = 1.000
NameWelcome.TextWrapped = true

WelcomeText.Name = "WelcomeText"
WelcomeText.Parent = Background
WelcomeText.AnchorPoint = Vector2.new(0.5, 0.5)
WelcomeText.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
WelcomeText.BackgroundTransparency = 1.000
WelcomeText.Position = UDim2.new(0.5, 0, 0.0537634417, 0)
WelcomeText.Size = UDim2.new(0, 200, 0, 35)
WelcomeText.Font = Enum.Font.Kalam
WelcomeText.Text = " Welcome,"
WelcomeText.TextColor3 = Color3.fromRGB(0, 0, 0)
WelcomeText.TextScaled = true
WelcomeText.TextSize = 14.000
WelcomeText.TextTransparency = 1.000
WelcomeText.TextWrapped = true

Dahood.Name = "Dahood"
Dahood.Parent = Main
Dahood.Active = true
Dahood.AnchorPoint = Vector2.new(0.5, 0.5)
Dahood.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Dahood.BackgroundTransparency = 1.000
Dahood.Position = UDim2.new(0.5, 0, 0.5, 0)
Dahood.Size = UDim2.new(0, 210, 0, 372)
Dahood.Visible = false

UICorner_3.CornerRadius = UDim.new(0, 20)
UICorner_3.Parent = Dahood

Fly1.Name = "Fly1"
Fly1.Parent = Dahood
Fly1.BackgroundColor3 = Color3.fromRGB(24, 24, 24)
Fly1.BackgroundTransparency = 1.000
Fly1.Position = UDim2.new(0.547619164, 0, 0.311827958, 0)
Fly1.Size = UDim2.new(0, 85, 0, 60)
Fly1.Font = Enum.Font.Kalam
Fly1.Text = "Fly"
Fly1.TextColor3 = Color3.fromRGB(255, 255, 255)
Fly1.TextScaled = true
Fly1.TextSize = 14.000
Fly1.TextTransparency = 1.000
Fly1.TextWrapped = true

UICorner_4.CornerRadius = UDim.new(0, 20)
UICorner_4.Parent = Fly1

ChatSpy1.Name = "ChatSpy1"
ChatSpy1.Parent = Dahood
ChatSpy1.BackgroundColor3 = Color3.fromRGB(24, 24, 24)
ChatSpy1.BackgroundTransparency = 1.000
ChatSpy1.Position = UDim2.new(0.547619164, 0, 0.752688169, 0)
ChatSpy1.Size = UDim2.new(0, 85, 0, 60)
ChatSpy1.Font = Enum.Font.Kalam
ChatSpy1.Text = "ChatSpy"
ChatSpy1.TextColor3 = Color3.fromRGB(255, 255, 255)
ChatSpy1.TextScaled = true
ChatSpy1.TextSize = 14.000
ChatSpy1.TextTransparency = 1.000
ChatSpy1.TextWrapped = true

UICorner_5.CornerRadius = UDim.new(0, 20)
UICorner_5.Parent = ChatSpy1

Faded.Name = "Faded"
Faded.Parent = Dahood
Faded.BackgroundColor3 = Color3.fromRGB(24, 24, 24)
Faded.BackgroundTransparency = 1.000
Faded.Position = UDim2.new(0.547619164, 0, 0.529569864, 0)
Faded.Size = UDim2.new(0, 85, 0, 60)
Faded.Font = Enum.Font.Kalam
Faded.Text = "Faded"
Faded.TextColor3 = Color3.fromRGB(255, 255, 255)
Faded.TextScaled = true
Faded.TextSize = 14.000
Faded.TextTransparency = 1.000
Faded.TextWrapped = true

UICorner_6.CornerRadius = UDim.new(0, 20)
UICorner_6.Parent = Faded

Notification1.Name = "Notification1"
Notification1.Parent = ScreenGui
Notification1.AnchorPoint = Vector2.new(0.5, 0.5)
Notification1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Notification1.BackgroundTransparency = 1.000
Notification1.Position = UDim2.new(1.5, 0, 0.864000022, 0)
Notification1.Size = UDim2.new(0, 200, 0, 65)
Notification1.Image = "rbxassetid://8269175594"
Notification1.ScaleType = Enum.ScaleType.Crop

UICorner_7.CornerRadius = UDim.new(0, 20)
UICorner_7.Parent = Notification1

Underlay1.Name = "Underlay1"
Underlay1.Parent = Notification1
Underlay1.AnchorPoint = Vector2.new(0.5, 0.5)
Underlay1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Underlay1.BackgroundTransparency = 1.000
Underlay1.Position = UDim2.new(0.467701763, 0, 0.627832532, 0)
Underlay1.Size = UDim2.new(0, 200, 0, 65)
Underlay1.ZIndex = 0
Underlay1.Image = "rbxassetid://8269154504"
Underlay1.ScaleType = Enum.ScaleType.Crop

UICorner_8.CornerRadius = UDim.new(0, 20)
UICorner_8.Parent = Underlay1

NotiHead1.Name = "NotiHead1"
NotiHead1.Parent = Notification1
NotiHead1.AnchorPoint = Vector2.new(0.5, 0.5)
NotiHead1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
NotiHead1.BackgroundTransparency = 1.000
NotiHead1.BorderSizePixel = 0
NotiHead1.Position = UDim2.new(0.137500003, 0, 0.223076925, 0)
NotiHead1.Size = UDim2.new(0, 55, 0, 25)
NotiHead1.Font = Enum.Font.Kalam
NotiHead1.Text = "Notice"
NotiHead1.TextColor3 = Color3.fromRGB(255, 255, 255)
NotiHead1.TextScaled = true
NotiHead1.TextSize = 14.000
NotiHead1.TextWrapped = true

NotiMsg1.Name = "NotiMsg1"
NotiMsg1.Parent = Notification1
NotiMsg1.AnchorPoint = Vector2.new(0.5, 0.5)
NotiMsg1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
NotiMsg1.BackgroundTransparency = 1.000
NotiMsg1.BorderSizePixel = 0
NotiMsg1.Position = UDim2.new(0.5, 0, 0.5, 0)
NotiMsg1.Size = UDim2.new(0, 180, 0, 29)
NotiMsg1.Font = Enum.Font.Kalam
NotiMsg1.Text = "V to toggle."
NotiMsg1.TextColor3 = Color3.fromRGB(255, 255, 255)
NotiMsg1.TextScaled = true
NotiMsg1.TextSize = 14.000
NotiMsg1.TextWrapped = true

CountDown1.Name = "CountDown1"
CountDown1.Parent = Notification1
CountDown1.AnchorPoint = Vector2.new(0.5, 0.5)
CountDown1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
CountDown1.BackgroundTransparency = 1.000
CountDown1.BorderSizePixel = 0
CountDown1.Position = UDim2.new(0.912500322, 0, 0.792307675, 0)
CountDown1.Size = UDim2.new(0, 35, 0, 27)
CountDown1.Font = Enum.Font.Kalam
CountDown1.Text = ""
CountDown1.TextColor3 = Color3.fromRGB(255, 255, 255)
CountDown1.TextScaled = true
CountDown1.TextSize = 14.000
CountDown1.TextWrapped = true

Notification2.Name = "Notification2"
Notification2.Parent = ScreenGui
Notification2.AnchorPoint = Vector2.new(0.5, 0.5)
Notification2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Notification2.BackgroundTransparency = 1.000
Notification2.Position = UDim2.new(1.5, 0, 0.864000022, 0)
Notification2.Size = UDim2.new(0, 200, 0, 65)
Notification2.Visible = false
Notification2.Image = "rbxassetid://8269175594"
Notification2.ScaleType = Enum.ScaleType.Crop

UICorner_9.CornerRadius = UDim.new(0, 20)
UICorner_9.Parent = Notification2

Underlay2.Name = "Underlay2"
Underlay2.Parent = Notification2
Underlay2.AnchorPoint = Vector2.new(0.5, 0.5)
Underlay2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Underlay2.BackgroundTransparency = 1.000
Underlay2.Position = UDim2.new(0.467701763, 0, 0.627832532, 0)
Underlay2.Size = UDim2.new(0, 200, 0, 65)
Underlay2.ZIndex = 0
Underlay2.Image = "rbxassetid://8269154504"
Underlay2.ScaleType = Enum.ScaleType.Crop

UICorner_10.CornerRadius = UDim.new(0, 20)
UICorner_10.Parent = Underlay2

NotiHead2.Name = "NotiHead2"
NotiHead2.Parent = Notification2
NotiHead2.AnchorPoint = Vector2.new(0.5, 0.5)
NotiHead2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
NotiHead2.BackgroundTransparency = 1.000
NotiHead2.BorderSizePixel = 0
NotiHead2.Position = UDim2.new(0.5, 0, 0.223076925, 0)
NotiHead2.Size = UDim2.new(0, 180, 0, 29)
NotiHead2.Font = Enum.Font.Kalam
NotiHead2.Text = ""
NotiHead2.TextColor3 = Color3.fromRGB(255, 255, 255)
NotiHead2.TextScaled = true
NotiHead2.TextSize = 14.000
NotiHead2.TextWrapped = true

NotiMsg2.Name = "NotiMsg2"
NotiMsg2.Parent = Notification2
NotiMsg2.AnchorPoint = Vector2.new(0.5, 0.5)
NotiMsg2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
NotiMsg2.BackgroundTransparency = 1.000
NotiMsg2.BorderSizePixel = 0
NotiMsg2.Position = UDim2.new(0.5, 0, 0.5, 0)
NotiMsg2.Size = UDim2.new(0, 180, 0, 29)
NotiMsg2.Font = Enum.Font.Kalam
NotiMsg2.Text = ""
NotiMsg2.TextColor3 = Color3.fromRGB(255, 255, 255)
NotiMsg2.TextScaled = true
NotiMsg2.TextSize = 14.000
NotiMsg2.TextWrapped = true

CountDown2.Name = "CountDown2"
CountDown2.Parent = Notification2
CountDown2.AnchorPoint = Vector2.new(0.5, 0.5)
CountDown2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
CountDown2.BackgroundTransparency = 1.000
CountDown2.BorderSizePixel = 0
CountDown2.Position = UDim2.new(0.912500322, 0, 0.792307675, 0)
CountDown2.Size = UDim2.new(0, 35, 0, 27)
CountDown2.Font = Enum.Font.Kalam
CountDown2.Text = ""
CountDown2.TextColor3 = Color3.fromRGB(255, 255, 255)
CountDown2.TextScaled = true
CountDown2.TextSize = 14.000
CountDown2.TextWrapped = true

-- Scripts:

local function KWDB_fake_script() -- Fly1.Fly1Toggle 
	local script = Instance.new('LocalScript', Fly1)

	local Fly1 = script.Parent
	
	Fly1.MouseButton1Down:connect(function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/oAlexanderr/UiTesting-/main/Fly",true))()
	end)
	
	
end
coroutine.wrap(KWDB_fake_script)()
local function TOLFS_fake_script() -- ChatSpy1.ChatSpyToggle1 
	local script = Instance.new('LocalScript', ChatSpy1)

	local ChatSpy1 = script.Parent
	
	ChatSpy1.MouseButton1Down:connect(function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/oAlexanderr/UiTesting-/main/ChatSpy",true))()
	end)
	
	
end
coroutine.wrap(TOLFS_fake_script)()
local function DDOD_fake_script() -- Faded.FadedToggle1 
	local script = Instance.new('LocalScript', Faded)

	local Faded = script.Parent
	
	Faded.MouseButton1Down:connect(function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/NighterEpic/Faded/main/YesEpic", true))()
	end)
	
	
end
coroutine.wrap(DDOD_fake_script)()
local function MQYHSKI_fake_script() -- Main.GameDeterm1 
	local script = Instance.new('LocalScript', Main)

	if game.PlaceId ==2788229376 then
		print("Game: Dahood")
		local Dahood = script.parent.Dahood
		local Fly1 = Dahood.Fly1
		local Faded = Dahood.Faded	
		local ChatSpy1 = Dahood.ChatSpy1
		local TweenService = game:GetService("TweenService")
		Dahood.Visible = true
		Fly1.Visible = true
		Faded.Visible = true
		ChatSpy1.Visible = true
		wait(6)
	
	
	
	
		local Fade1 = TweenInfo.new(
			.35, -- The time the tween takes to complete
			Enum.EasingStyle.Sine, -- The tween style.
			Enum.EasingDirection.Out, -- EasingDirection
			0, -- How many times you want the tween to repeat. If you make it less than 0 it will repeat forever.
			false, -- Reverse?
			0 -- Delay
		)
	
		local Tween1 = TweenService:Create(Fly1, Fade1, {TextTransparency = 0})
		local Tween2 = TweenService:Create(ChatSpy1, Fade1, {TextTransparency = 0})
		local Tween3 = TweenService:Create(Faded, Fade1, {TextTransparency = 0})
		local Tween4 = TweenService:Create(Fly1, Fade1, {BackgroundTransparency = 0.4})
		local Tween5 = TweenService:Create(ChatSpy1, Fade1, {BackgroundTransparency = 0.4})
		local Tween6 = TweenService:Create(Faded, Fade1, {BackgroundTransparency = 0.4})
		wait(1)
		Tween1:Play()
		Tween2:Play()
		Tween3:Play()
		Tween4:Play()
		Tween5:Play()
		Tween6:Play()
	else
	
	end
end
coroutine.wrap(MQYHSKI_fake_script)()
local function NISITNU_fake_script() -- Main.KeybindToggle 
	local script = Instance.new('LocalScript', Main)

	local open = true
	local keystatus
	local mouse = game.Players.LocalPlayer:GetMouse()
	keystatus=mouse.KeyDown:connect(function(key)
		if key == "z" then
			if script.Parent.Visible == true then
				script.Parent.Visible = false
					else
				script.Parent.Visible = true
	end
	end
	end)
end
coroutine.wrap(NISITNU_fake_script)()
local function RVILP_fake_script() -- Main.Welcome 
	local script = Instance.new('LocalScript', Main)

	local NameWelcome = script.parent.Background.NameWelcome
	local WelcomeText = script.Parent.Background.WelcomeText
	local name = game:GetService("Players").LocalPlayer.DisplayName
	local TweenService = game:GetService(("TweenService"))
	
	
	local Fade1 = TweenInfo.new(
		.35, -- The time the tween takes to complete
		Enum.EasingStyle.Sine, -- The tween style.
		Enum.EasingDirection.Out, -- EasingDirection
		0, -- How many times you want the tween to repeat. If you make it less than 0 it will repeat forever.
		false, -- Reverse?
		0 -- Delay
	)
	
	wait(5.1)
	local Tween1 = TweenService:Create(WelcomeText, Fade1, {TextTransparency = 0})
	Tween1:Play()
	wait(.25)
	local Tween2 = TweenService:Create(NameWelcome, Fade1, {TextTransparency = 0})
	Tween2:Play()
	NameWelcome.Text = name
	
end
coroutine.wrap(RVILP_fake_script)()
local function KFNAUKP_fake_script() -- Main.Boot 
	local script = Instance.new('LocalScript', Main)

	print("Attempting to Boot")
	local TweenService = game:GetService("TweenService")
	
	local Main = script.Parent
	local MainUnderlay = script.Parent.MainUnderlay
	local Background = script.parent.Background
	local Corner1 = script.parent.Corner1
	
	local Rotate1 = TweenInfo.new(
		1.15, -- The time the tween takes to complete
		Enum.EasingStyle.Sine, -- The tween style.
		Enum.EasingDirection.Out, -- EasingDirection
		0, -- How many times you want the tween to repeat. If you make it less than 0 it will repeat forever.
		false, -- Reverse?
		2 -- Delay
	)
	
	local Fade1 = TweenInfo.new(
		.35, -- The time the tween takes to complete
		Enum.EasingStyle.Sine, -- The tween style.
		Enum.EasingDirection.Out, -- EasingDirection
		0, -- How many times you want the tween to repeat. If you make it less than 0 it will repeat forever.
		false, -- Reverse?
		0 -- Delay
	)
	
	local Tween1 = TweenService:Create(Main, Rotate1, {Rotation = 360}) -- Creates the tween with the TweenInfo and what properties you want to change
	Tween1:Play() -- Plays the tween
	
	wait(2.7)
	Corner1.CornerRadius = UDim.new(0, 20)
	Main:TweenSize(UDim2.new(0, 235, 0, 394))
	
	wait(1.2)
	
	MainUnderlay.Visible = true
	MainUnderlay:TweenPosition(UDim2.new(0.472, 0, 0.52, 0), Enum.EasingDirection.Out, Enum.EasingStyle.Elastic)
	wait(.3)
	
	local Tween2 = TweenService:Create(Background, Fade1, {ImageTransparency = 0})
	Tween2:Play()
	print("Boot Successful")
	
end
coroutine.wrap(KFNAUKP_fake_script)()
local function NCRTFN_fake_script() -- Notification1.NotiSend1 
	local script = Instance.new('LocalScript', Notification1)

	if game.PlaceId ==2788229376 then
		print("Normal procedures")
		local Notification1 = script.Parent
		local CountDown1 = script.parent.CountDown1
		local TS = game:GetService("TweenService")
		wait(3.5)
		Notification1.Visible = true
		Notification1:TweenPosition(UDim2.new(0.897, 0, 0.864, 0), Enum.EasingDirection.Out, Enum.EasingStyle.Back)
	
		wait(2.5)
		CountDown1.Text = "(5)"
		wait(1)
		CountDown1.Text = ""
		wait(.2)
		CountDown1.Text = "(4)"
		wait(1)
		CountDown1.Text = ""
		wait(.2)
		CountDown1.Text = "(3)"
		wait(1)
		CountDown1.Text = ""
		wait(.2)
		CountDown1.Text = "(2)"
		wait(1)
		CountDown1.Text = ""
		wait(.2)
		CountDown1.Text = "(1)"
		wait(.5)
		CountDown1.Text = ""
	
	
		Notification1:TweenPosition(UDim2.new(1.5, 0, 0.864, 0), Enum.EasingDirection.In, Enum.EasingStyle.Back)
	
		wait(2)
	
		Notification1.Visible = false 
	else
		print("Not a supported game, showing Notification2")
		script.Disabled = true
	end
	
	
	
end
coroutine.wrap(NCRTFN_fake_script)()
local function OOQPLD_fake_script() -- Notification2.NotiSend2 
	local script = Instance.new('LocalScript', Notification2)

	if game.PlaceId ==2788229376 then
		print("Boot as normal!")
	else
		print("Preparing shutdown")
		local Kill = script.parent.parent
		local Notification2 = script.Parent
		local CountDown2 = script.parent.CountDown2
		local NotiHead2 = script.parent.NotiHead2
		local NotiMsg2 = script.parent.NotiMsg2
		local TS = game:GetService("TweenService")
		Notification2.Visible = true
		wait(3.5)
	
		Notification2:TweenPosition(UDim2.new(0.897, 0, 0.864, 0), Enum.EasingDirection.Out, Enum.EasingStyle.Back)
	
		NotiHead2.Text = "Game not supported."
		NotiMsg2.Text = "Shutting down."
	
		wait(1.5)
		CountDown2.Text = "(5)"
		wait(1)
		CountDown2.Text = ""
		wait(.2)
		CountDown2.Text = "(4)"
		wait(1)
		CountDown2.Text = ""
		wait(.2)
		CountDown2.Text = "(3)"
		wait(1)
		CountDown2.Text = ""
		wait(.2)
		CountDown2.Text = "(2)"
		wait(1)
		CountDown2.Text = ""
		wait(.2)
		CountDown2.Text = "(1)"
		wait(.5)
		CountDown2.Text = ""
	
		Notification2:TweenPosition(UDim2.new(1.5, 0, 0.864, 0), Enum.EasingDirection.In, Enum.EasingStyle.Back)
		wait(2)
		Notification2.Visible = false
		print("Shutdown notice has been given, proceeding to kill Gui")
	end
	
	
	
	
	
end
coroutine.wrap(OOQPLD_fake_script)()
local function QGPF_fake_script() -- Notification2.KillFunction 
	local script = Instance.new('LocalScript', Notification2)

	if game.PlaceId ==2788229376 then
		print("Normal procedures")
	else
		wait(12)
		script.parent.parent.Enabled = false
		print("Gui has been killed")
	end
end
coroutine.wrap(QGPF_fake_script)()
