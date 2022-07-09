
local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local g = Instance.new("TextButton")
local g2 = Instance.new("TextButton")
local TextLabel_2 = Instance.new("TextLabel")
local zomb = Instance.new("TextButton")
local pizza = Instance.new("TextButton")
local TextLabel_3 = Instance.new("TextLabel")
local TextButton = Instance.new("TextButton")
local TextLabel_4 = Instance.new("TextLabel")



ScreenGui.Parent = game.CoreGui

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(76, 76, 76)
Frame.Position = UDim2.new(0.519434631, 0, 0.540031433, 0)
Frame.Size = UDim2.new(0, 381, 0, 286)
Frame.Active = true
Frame.Draggable = true

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(91, 91, 91)
TextLabel.BorderColor3 = Color3.fromRGB(43, 67, 85)
TextLabel.Size = UDim2.new(0, 381, 0, 50)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Dark Hub FE "
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

g.Name = "g"
g.Parent = Frame
g.BackgroundColor3 = Color3.fromRGB(67, 67, 67)
g.Position = UDim2.new(0, 0, 0.213286713, 0)
g.Size = UDim2.new(0, 81, 0, 34)
g.Font = Enum.Font.SourceSans
g.Text = "FE Wizzard"
g.TextColor3 = Color3.fromRGB(0, 0, 0)
g.TextSize = 14.000
g.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(('https://raw.githubusercontent.com/selecteduseromg343/fe-only-lol/main/README.md'),true))()
end)


g2.Name = "g2"
g2.Parent = Frame
g2.BackgroundColor3 = Color3.fromRGB(57, 57, 57)
g2.Position = UDim2.new(0.254593164, 0, 0.213286608, 0)
g2.Size = UDim2.new(0, 75, 0, 33)
g2.Font = Enum.Font.SourceSans
g2.Text = "Linorix"
g2.TextColor3 = Color3.fromRGB(0, 0, 0)
g2.TextSize = 14.000
g2.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(('https://raw.githubusercontent.com/selecteduseromg343/fdsfdsfds/main/README.md'),true))()
end)


TextLabel_2.Parent = Frame
TextLabel_2.BackgroundColor3 = Color3.fromRGB(68, 68, 68)
TextLabel_2.BorderColor3 = Color3.fromRGB(58, 58, 58)
TextLabel_2.Position = UDim2.new(0.769028842, 0, 7.4505806e-09, 0)
TextLabel_2.Size = UDim2.new(0, 82, 0, 22)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "by serventos"
TextLabel_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.TextSize = 14.000
TextLabel_2.TextStrokeColor3 = Color3.fromRGB(63, 63, 63)

zomb.Name = "zomb"
zomb.Parent = Frame
zomb.BackgroundColor3 = Color3.fromRGB(61, 61, 61)
zomb.Position = UDim2.new(0.503937006, 0, 0.209790215, 0)
zomb.Size = UDim2.new(0, 75, 0, 35)
zomb.Font = Enum.Font.SourceSans
zomb.Text = "fezombie"
zomb.TextColor3 = Color3.fromRGB(0, 0, 0)
zomb.TextSize = 14.000
zomb.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(('https://raw.githubusercontent.com/selecteduseromg343/zombie/main/README.md'),true))()
end)


pizza.Name = "pizza"
pizza.Parent = Frame
pizza.BackgroundColor3 = Color3.fromRGB(67, 67, 67)
pizza.Position = UDim2.new(0.745406866, 0, 0.213286713, 0)
pizza.Size = UDim2.new(0, 91, 0, 34)
pizza.Font = Enum.Font.SourceSans
pizza.Text = "Fe PizzaFlinger"
pizza.TextColor3 = Color3.fromRGB(0, 0, 0)
pizza.TextSize = 14.000
pizza.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(('https://raw.githubusercontent.com/selecteduseromg343/oooooo-pizza/main/README.md'),true))()
end)


TextLabel_3.Parent = Frame
TextLabel_3.BackgroundColor3 = Color3.fromRGB(68, 68, 68)
TextLabel_3.BorderColor3 = Color3.fromRGB(58, 58, 58)
TextLabel_3.Position = UDim2.new(0, 0, 7.4505806e-09, 0)
TextLabel_3.Size = UDim2.new(0, 82, 0, 22)
TextLabel_3.Font = Enum.Font.SourceSans
TextLabel_3.Text = "by serventos"
TextLabel_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.TextSize = 14.000
TextLabel_3.TextStrokeColor3 = Color3.fromRGB(63, 63, 63)

crim.Parent = crim
crim.BackgroundColor3 = Color3.fromRGB(77, 77, 77)
crim.Position = UDim2.new(0, 0, 0.440559447, 0)
crim.Size = UDim2.new(0, 81, 0, 33)
crim.Font = Enum.Font.SourceSans
crim.Text = "fe criminal"
crim.TextColor3 = Color3.fromRGB(0, 0, 0)
crim.TextSize = 14.000
crim.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(('https://raw.githubusercontent.com/selecteduseromg343/roblox-criminal-fe-hack/main/README.md'),true))()
end)

TextLabel_4.Parent = Frame
TextLabel_4.BackgroundColor3 = Color3.fromRGB(62, 62, 62)
TextLabel_4.Position = UDim2.new(0, 0, 0.555944145, 0)
TextLabel_4.Size = UDim2.new(0, 381, 0, 126)
TextLabel_4.Font = Enum.Font.SourceSans
TextLabel_4.Text = "SOON SCRİPTS"
TextLabel_4.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_4.TextScaled = true
TextLabel_4.TextSize = 14.000
TextLabel_4.TextWrapped = true
