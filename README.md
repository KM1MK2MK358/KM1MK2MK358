local shiroshubv2 = Instance.new("ScreenGui")
local mainframe = Instance.new("Frame")
local Minimise = Instance.new("TextButton")
local Dupe = Instance.new("TextButton")
local DupeFrame = Instance.new("Frame")
local Dupe_2 = Instance.new("TextLabel")
local Main = Instance.new("TextButton")
local MainFrame = Instance.new("Frame")
local Speed = Instance.new("TextButton")
local Fly = Instance.new("TextButton")
local TP = Instance.new("TextButton")
local CarFlight = Instance.new("TextButton")
local NoClip = Instance.new("TextButton")
local InfJump = Instance.new("TextButton")
local Jump = Instance.new("TextButton")
local SpeedValue = Instance.new("TextBox")
local JumpValue = Instance.new("TextBox")
local SecretWalkSpeed = Instance.new("TextButton")
local Plot = Instance.new("TextButton")
local PlotFrame = Instance.new("Frame")
local MaxLand = Instance.new("TextButton")
local Wood = Instance.new("TextButton")
local WoodFrame = Instance.new("Frame")
local TP_2 = Instance.new("TextButton")
local TPFrame = Instance.new("Frame")
local StoreWoodRUs = Instance.new("TextButton")
local StoreLand = Instance.new("TextButton")
local StoreCars = Instance.new("TextButton")
local GreenBox = Instance.new("TextButton")
local StoreFancy = Instance.new("TextButton")
local StoreLogic = Instance.new("TextButton")
local Spawn = Instance.new("TextButton")
local IceWood = Instance.new("TextButton")
local Lodge = Instance.new("TextButton")
local Dock = Instance.new("TextButton")
local Bridge = Instance.new("TextButton")
local Cave = Instance.new("TextButton")
local StrangeMan = Instance.new("TextButton")
local YellowWood = Instance.new("TextButton")
local Volcano = Instance.new("TextButton")
local Palm = Instance.new("TextButton")
local StoreBobs = Instance.new("TextButton")
local EndTimes = Instance.new("TextButton")
local Swamp = Instance.new("TextButton")
local StoreFineArts = Instance.new("TextButton")
local Hub = Instance.new("TextButton")
local HubFrame = Instance.new("Frame")
local Blood = Instance.new("TextButton")
local Orignal = Instance.new("TextButton")
local LT2 = Instance.new("TextButton")
local Venyx = Instance.new("TextButton")
local infiniteyield = Instance.new("TextButton")
local Credits = Instance.new("TextButton")
local CreditsFrame = Instance.new("Frame")
local MadeBy = Instance.new("TextLabel")
local SnowyShiro = Instance.new("TextLabel")
local Close = Instance.new("TextButton")
local Name = Instance.new("TextLabel")
local openbutton = Instance.new("TextButton")
local Move = Instance.new("TextButton")
local Copy = Instance.new("TextButton")
local Delete = Instance.new("TextButton")
local AllBtools = Instance.new("TextButton")
local walkonwater = Instance.new("TextButton")
local UICk = Instance.new("UICorner")
local NoFog = Instance.new("TextButton")
local Back1 = Color3.fromRGB(31, 40, 57)
local Border1 = Color3.fromRGB(11, 43, 118)
 
shiroshubv2.Name = "KM1MK2MK358HubV1.6Beta"
shiroshubv2.Parent = game.CoreGui

local UICk1 = Instance.new("UICorner", mainframe)
mainframe.Name = "mainframe"
mainframe.Parent = shiroshubv2
mainframe.BackgroundColor3 = Back1
mainframe.BorderColor3 = Color3.fromRGB(10, 120, 255)
mainframe.BorderSizePixel = 0
mainframe.Position = UDim2.new(0.202159837, 0, 0.372229487, 0)
mainframe.Size = UDim2.new(0, 400, 0, 280)
mainframe.Visible = false

local UICk2 = Instance.new("UICorner", Minimise)
Minimise.Name = "Minimise"
Minimise.Parent = mainframe
Minimise.BackgroundColor3 = Border1
Minimise.BorderColor3 = Color3.fromRGB(10, 120, 255)
Minimise.BorderSizePixel = 0
Minimise.Position = UDim2.new(0.800000012, 0, 0, 0)
Minimise.Size = UDim2.new(0, 40, 0, 40)
Minimise.Font = Enum.Font.SourceSans
Minimise.Text = "-"
Minimise.TextColor3 = Color3.fromRGB(255, 255, 255)
Minimise.TextSize = 35.000
Minimise.TextWrapped = true
Minimise.MouseButton1Down:connect(function()
openbutton.Visible = true
mainframe.Visible = false
end)

local UICk3 = Instance.new("UICorner", Close)
Close.Name = "Close"
Close.Parent = mainframe
Close.BackgroundColor3 = Border1
Close.BorderColor3 = Color3.fromRGB(10, 120, 255)
Close.BorderSizePixel = 0
Close.Position = UDim2.new(0.899469852, 0, 0, 0)
Close.Size = UDim2.new(0, 40, 0, 40)
Close.Font = Enum.Font.SourceSans
Close.Text = "X"
Close.TextColor3 = Color3.fromRGB(255, 255, 255)
Close.TextSize = 35.000
Close.TextWrapped = true
Close.MouseButton1Down:connect(function()
shiroshubv2:Destroy()
end)

local UICk4 = Instance.new("UICorner", openbutton)
openbutton.Name = "openbutton"
openbutton.Parent = shiroshubv2
openbutton.BackgroundColor3 = Border1
openbutton.BorderColor3 = Color3.fromRGB(10, 120, 255)
openbutton.BorderSizePixel = 0
openbutton.Position = UDim2.new(0.850947857, 0, 0.9, -9)
openbutton.Size = UDim2.new(0, 100, 0, 30)
openbutton.Font = Enum.Font.SourceSans
openbutton.Text = "Open"
openbutton.TextColor3 = Color3.fromRGB(255, 255, 255)
openbutton.TextSize = 32.000
openbutton.MouseButton1Down:connect(function()
mainframe.Visible = true
openbutton.Visible = false
end)
 
local UICk5 = Instance.new("UICorner", Dupe)
Dupe.Name = "Dupe"
Dupe.Parent = mainframe
Dupe.BackgroundColor3 = Border1
Dupe.BorderColor3 = Color3.fromRGB(10, 120, 255)
Dupe.BorderSizePixel = 0
Dupe.Position = UDim2.new(0, 0, 0.42899999, 0)
Dupe.Size = UDim2.new(0, 80, 0, 40)
Dupe.Font = Enum.Font.SourceSans
Dupe.Text = "Dupe"
Dupe.TextColor3 = Color3.fromRGB(255, 255, 255)
Dupe.TextScaled = true
Dupe.TextSize = 32.000
Dupe.TextWrapped = true
Dupe.MouseButton1Down:connect(function()
CreditsFrame.Visible = false
DupeFrame.Visible = true
HubFrame.Visible = false
MainFrame.Visible = false
PlotFrame.Visible = false
TPFrame.Visible = false
WoodFrame.Visible = false
end)

local UICk6 = Instance.new("UICorner", DupeFrame)
DupeFrame.Name = "DupeFrame"
DupeFrame.Parent = Dupe
DupeFrame.BackgroundColor3 = Back1
DupeFrame.BorderSizePixel = 0
DupeFrame.Position = UDim2.new(1, 0, -2.00299978, 0)
DupeFrame.Size = UDim2.new(0, 320, 0, 240)
DupeFrame.Visible = false

local UICk7 = Instance.new("UICorner", Main)
Main.Name = "Main"
Main.Parent = mainframe
Main.BackgroundColor3 = Border1
Main.BorderColor3 = Color3.fromRGB(10, 120, 255)
Main.BorderSizePixel = 0
Main.Size = UDim2.new(0, 80, 0, 40)
Main.Font = Enum.Font.SourceSans
Main.Text = "Main"
Main.TextColor3 = Color3.fromRGB(255, 255, 255)
Main.TextScaled = true
Main.TextSize = 32.000
Main.TextWrapped = true
Main.MouseButton1Down:connect(function()
CreditsFrame.Visible = false
DupeFrame.Visible = false
HubFrame.Visible = false
MainFrame.Visible = true
PlotFrame.Visible = false
TPFrame.Visible = false
WoodFrame.Visible = false
end)

local UICk8 = Instance.new("UICorner", MainFrame)
MainFrame.Name = "MainFrame"
MainFrame.Parent = Main
MainFrame.BackgroundColor3 = Back1
MainFrame.BorderSizePixel = 0
MainFrame.Position = UDim2.new(1, 0, 1, 0)
MainFrame.Size = UDim2.new(0, 320, 0, 240)
MainFrame.Visible = false
 
local UICk9 = Instance.new("UICorner", Speed)
Speed.Name = "Speed"
Speed.Parent = MainFrame
Speed.BackgroundColor3 = Border1
Speed.BorderSizePixel = 0
Speed.Position = UDim2.new(0.0199999809, 0, 0.0250000004, 0)
Speed.Size = UDim2.new(0, 76, 0, 52)
Speed.Font = Enum.Font.SourceSans
Speed.Text = "Speed"
Speed.TextColor3 = Color3.fromRGB(255, 255, 255)
Speed.TextScaled = true
Speed.TextSize = 14.000
Speed.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Speed.TextWrapped = true

local UICk10 = Instance.new("UICorner", Fly)
Fly.Name = "Fly"
Fly.Parent = MainFrame
Fly.BackgroundColor3 = Border1
Fly.BorderSizePixel = 0
Fly.Position = UDim2.new(0.0199999996, 0, 0.270000011, 0)
Fly.Size = UDim2.new(0, 73, 0, 52)
Fly.Font = Enum.Font.SourceSans
Fly.Text = "Fly"
Fly.TextColor3 = Color3.fromRGB(255, 255, 255)
Fly.TextScaled = true
Fly.TextSize = 14.000
Fly.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Fly.TextWrapped = true
 
local UICk11 = Instance.new("UICorner", TP)
TP.Name = "TP"
TP.Parent = MainFrame
TP.BackgroundColor3 = Border1
TP.BorderSizePixel = 0
TP.Position = UDim2.new(0.0199999996, 0, 0.514999986, 0)
TP.Size = UDim2.new(0, 73, 0, 52)
TP.Font = Enum.Font.SourceSans
TP.Text = "CtrlClickTP"
TP.TextColor3 = Color3.fromRGB(255, 255, 255)
TP.TextScaled = true
TP.TextSize = 14.000
TP.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
TP.TextWrapped = true

local UICk12 = Instance.new("UICorner", CarFlight)
CarFlight.Name = "CarFlight"
CarFlight.Parent = MainFrame
CarFlight.BackgroundColor3 = Border1
CarFlight.BorderSizePixel = 0
CarFlight.Position = UDim2.new(0.266874999, 0, 0.269999981, 0)
CarFlight.Size = UDim2.new(0, 73, 0, 52)
CarFlight.Font = Enum.Font.SourceSans
CarFlight.Text = "Car Flight"
CarFlight.TextColor3 = Color3.fromRGB(255, 255, 255)
CarFlight.TextScaled = true
CarFlight.TextSize = 14.000
CarFlight.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
CarFlight.TextWrapped = true

local UICk13 = Instance.new("UICorner", NoClip)
NoClip.Name = "NoClip"
NoClip.Parent = MainFrame
NoClip.BackgroundColor3 = Border1
NoClip.BorderSizePixel = 0
NoClip.Position = UDim2.new(0.753000021, 0, 0.270000011, 0)
NoClip.Size = UDim2.new(0, 73, 0, 52)
NoClip.Font = Enum.Font.SourceSans
NoClip.Text = "No Clip"
NoClip.TextColor3 = Color3.fromRGB(255, 255, 255)
NoClip.TextScaled = true
NoClip.TextSize = 14.000
NoClip.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
NoClip.TextWrapped = true

local UICk14 = Instance.new("UICorner", InfJump)
InfJump.Name = "InfJump"
InfJump.Parent = MainFrame
InfJump.BackgroundColor3 = Border1
InfJump.BorderSizePixel = 0
InfJump.Position = UDim2.new(0.504999995, 0, 0.270000011, 0)
InfJump.Size = UDim2.new(0, 73, 0, 52)
InfJump.Font = Enum.Font.SourceSans
InfJump.Text = "Infinite Jump"
InfJump.TextColor3 = Color3.fromRGB(255, 255, 255)
InfJump.TextScaled = true
InfJump.TextSize = 14.000
InfJump.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
InfJump.TextWrapped = true

local UICk15 = Instance.new("UICorner", Jump)
Jump.Name = "Jump"
Jump.Parent = MainFrame
Jump.BackgroundColor3 = Border1
Jump.BorderSizePixel = 0
Jump.Position = UDim2.new(0.504999995, 0, 0.0250000004, 0)
Jump.Size = UDim2.new(0, 76, 0, 52)
Jump.Font = Enum.Font.SourceSans
Jump.Text = "Jump"
Jump.TextColor3 = Color3.fromRGB(255, 255, 255)
Jump.TextScaled = true
Jump.TextSize = 14.000
Jump.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Jump.TextWrapped = true

local UICk16 = Instance.new("UICorner", SpeedValue)
SpeedValue.Name = "SpeedValue"
SpeedValue.Parent = MainFrame
SpeedValue.BackgroundColor3 = Color3.fromRGB(80, 80, 255)
SpeedValue.BorderSizePixel = 0
SpeedValue.Position = UDim2.new(0.257499993, 0, 0.0250000004, 0)
SpeedValue.Size = UDim2.new(0, 76, 0, 52)
SpeedValue.Font = Enum.Font.SourceSans
SpeedValue.PlaceholderColor3 = Color3.fromRGB(255, 255, 255)
SpeedValue.PlaceholderText = "16"
SpeedValue.Text = ""
SpeedValue.TextColor3 = Color3.fromRGB(255, 255, 255)
SpeedValue.TextScaled = true
SpeedValue.TextSize = 14.000
SpeedValue.TextWrapped = true

local UICk17 = Instance.new("UICorner", JumpValue)
JumpValue.Name = "JumpValue"
JumpValue.Parent = MainFrame
JumpValue.BackgroundColor3 = Color3.fromRGB(80, 80, 255)
JumpValue.BorderSizePixel = 0
JumpValue.Position = UDim2.new(0.742500007, 0, 0.0250000004, 0)
JumpValue.Size = UDim2.new(0, 76, 0, 52)
JumpValue.Font = Enum.Font.SourceSans
JumpValue.PlaceholderColor3 = Color3.fromRGB(255, 255, 255)
JumpValue.PlaceholderText = "50"
JumpValue.Text = ""
JumpValue.TextColor3 = Color3.fromRGB(255, 255, 255)
JumpValue.TextScaled = true
JumpValue.TextSize = 14.000
JumpValue.TextWrapped = true

local UICk18 = Instance.new("UICorner", SecretWalkSpeed)
SecretWalkSpeed.Name = "SecretWalkSpeed"
SecretWalkSpeed.Parent = MainFrame
SecretWalkSpeed.BackgroundColor3 = Border1
SecretWalkSpeed.BorderSizePixel = 0
SecretWalkSpeed.Size = UDim2.new(0, 6, 0, 6)
SecretWalkSpeed.AutoButtonColor = false
SecretWalkSpeed.Font = Enum.Font.SourceSans
SecretWalkSpeed.Text = ""
SecretWalkSpeed.TextColor3 = Color3.fromRGB(255, 255, 255)
SecretWalkSpeed.TextScaled = true
SecretWalkSpeed.TextSize = 14.000
SecretWalkSpeed.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
SecretWalkSpeed.TextWrapped = true

local UICk19 = Instance.new("UICorner", Move)
Move.Name = "Move"
Move.Parent = MainFrame
Move.BackgroundColor3 = Border1
Move.BorderSizePixel = 0
Move.Position = UDim2.new(0.26699999, 0, 0.514999986, 0)
Move.Size = UDim2.new(0, 73, 0, 52)
Move.Font = Enum.Font.SourceSans
Move.Text = "Move"
Move.TextColor3 = Color3.fromRGB(255, 255, 255)
Move.TextScaled = true
Move.TextSize = 14.000
Move.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Move.TextWrapped = true

local UICk56 = Instance.new("UICorner", walkonwater)
walkonwater.Name = "walkonwater"
walkonwater.Parent = MainFrame
walkonwater.BackgroundColor3 = Border1
walkonwater.BorderSizePixel = 0
walkonwater.Position = UDim2.new(0.504999995, 0, 0.514999986, 0)
walkonwater.Size = UDim2.new(0, 73, 0, 52)
walkonwater.Font = Enum.Font.SourceSans
walkonwater.Text = "WalkOnWater"
walkonwater.TextColor3 = Color3.fromRGB(255, 255, 255)
walkonwater.TextScaled = true
walkonwater.TextSize = 14.000
walkonwater.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
walkonwater.TextWrapped = true

local UICk57 = Instance.new("UICorner", NoFog)
NoFog.Name = "NoFog"
NoFog.Parent = MainFrame
NoFog.BackgroundColor3 = Border1
NoFog.BorderSizePixel = 0
NoFog.Position = UDim2.new(0.753000021, 0, 0.514999986, 0)
NoFog.Size = UDim2.new(0, 73, 0, 52)
NoFog.Font = Enum.Font.SourceSans
NoFog.Text = "No Fog"
NoFog.TextColor3 = Color3.fromRGB(255, 255, 255)
NoFog.TextScaled = true
NoFog.TextSize = 14.000
NoFog.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
NoFog.TextWrapped = true

local UICk20 = Instance.new("UICorner", Plot)
Plot.Name = "Plot"
Plot.Parent = mainframe
Plot.BackgroundColor3 = Border1
Plot.BorderColor3 = Color3.fromRGB(10, 120, 255)
Plot.BorderSizePixel = 0
Plot.Position = UDim2.new(0, 0, 0.572000027, 0)
Plot.Size = UDim2.new(0, 80, 0, 40)
Plot.Font = Enum.Font.SourceSans
Plot.Text = "Plot"
Plot.TextColor3 = Color3.fromRGB(255, 255, 255)
Plot.TextScaled = true
Plot.TextSize = 32.000
Plot.TextWrapped = true
Plot.MouseButton1Down:connect(function()
CreditsFrame.Visible = false
DupeFrame.Visible = false
HubFrame.Visible = false
MainFrame.Visible = false
PlotFrame.Visible = true
TPFrame.Visible = false
WoodFrame.Visible = false
end)

local UICk21 = Instance.new("UICorner", PlotFrame)
PlotFrame.Name = "PlotFrame"
PlotFrame.Parent = Plot
PlotFrame.BackgroundColor3 = Back1
PlotFrame.BorderSizePixel = 0
PlotFrame.Position = UDim2.new(1, 0, -3.00299978, 0)
PlotFrame.Size = UDim2.new(0, 320, 0, 240)
PlotFrame.Visible = false

local UICk22 = Instance.new("UICorner", MaxLand)
MaxLand.Name = "MaxLand"
MaxLand.Parent = PlotFrame
MaxLand.BackgroundColor3 = Border1
MaxLand.BorderSizePixel = 0
MaxLand.Position = UDim2.new(0.0199999996, 0, 0.0250000004, 0)
MaxLand.Size = UDim2.new(0, 151, 0, 52)
MaxLand.Font = Enum.Font.SourceSans
MaxLand.Text = "Max Land"
MaxLand.TextColor3 = Color3.fromRGB(255, 255, 255)
MaxLand.TextScaled = true
MaxLand.TextSize = 14.000
MaxLand.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
MaxLand.TextWrapped = true

local UICk23 = Instance.new("UICorner", Wood)
Wood.Name = "Wood"
Wood.Parent = mainframe
Wood.BackgroundColor3 = Border1
Wood.BorderColor3 = Color3.fromRGB(10, 120, 255)
Wood.BorderSizePixel = 0
Wood.Position = UDim2.new(0, 0, 0.143000007, 0)
Wood.Size = UDim2.new(0, 80, 0, 40)
Wood.Font = Enum.Font.SourceSans
Wood.Text = "Wood"
Wood.TextColor3 = Color3.fromRGB(255, 255, 255)
Wood.TextScaled = true
Wood.TextSize = 32.000
Wood.TextWrapped = true
Wood.MouseButton1Down:connect(function()
CreditsFrame.Visible = false
DupeFrame.Visible = false
HubFrame.Visible = false
MainFrame.Visible = false
PlotFrame.Visible = false
TPFrame.Visible = false
WoodFrame.Visible = true
end)

local UICk24 = Instance.new("UICorner", WoodFrame)
WoodFrame.Name = "WoodFrame"
WoodFrame.Parent = Wood
WoodFrame.BackgroundColor3 = Back1
WoodFrame.BorderSizePixel = 0
WoodFrame.Position = UDim2.new(1, 0, -0.00100021367, 0)
WoodFrame.Size = UDim2.new(0, 320, 0, 240)
WoodFrame.Visible = false

local UICk25 = Instance.new("UICorner", TP_2)
TP_2.Name = "TP"
TP_2.Parent = mainframe
TP_2.BackgroundColor3 = Border1
TP_2.BorderColor3 = Color3.fromRGB(10, 120, 255)
TP_2.BorderSizePixel = 0
TP_2.Position = UDim2.new(0, 0, 0.286000013, 0)
TP_2.Size = UDim2.new(0, 80, 0, 40)
TP_2.Font = Enum.Font.SourceSans
TP_2.Text = "TP"
TP_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TP_2.TextScaled = true
TP_2.TextSize = 32.000
TP_2.TextWrapped = true
TP_2.MouseButton1Down:connect(function()
CreditsFrame.Visible = false
DupeFrame.Visible = false
HubFrame.Visible = false
MainFrame.Visible = false
PlotFrame.Visible = false
TPFrame.Visible = true
WoodFrame.Visible = false
end)

local UICk26 = Instance.new("UICorner", TPFrame)
TPFrame.Name = "TPFrame"
TPFrame.Parent = TP_2
TPFrame.BackgroundColor3 = Back1
TPFrame.BorderSizePixel = 0
TPFrame.Position = UDim2.new(1, 0, -1.00200045, 0)
TPFrame.Size = UDim2.new(0, 320, 0, 240)
TPFrame.Visible = false

local UICk27 = Instance.new("UICorner", StoreWoodRUs)
StoreWoodRUs.Name = "StoreWoodRUs"
StoreWoodRUs.Parent = TPFrame
StoreWoodRUs.BackgroundColor3 = Border1
StoreWoodRUs.BorderSizePixel = 0
StoreWoodRUs.Position = UDim2.new(0.0199999809, 0, 0.0250000004, 0)
StoreWoodRUs.Size = UDim2.new(0, 73, 0, 40)
StoreWoodRUs.Font = Enum.Font.SourceSans
StoreWoodRUs.Text = "WoodRUs"
StoreWoodRUs.TextColor3 = Color3.fromRGB(255, 255, 255)
StoreWoodRUs.TextScaled = true
StoreWoodRUs.TextSize = 14.000
StoreWoodRUs.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
StoreWoodRUs.TextWrapped = true

local UICk28 = Instance.new("UICorner", StoreLand)
StoreLand.Name = "StoreLand"
StoreLand.Parent = TPFrame
StoreLand.BackgroundColor3 = Border1
StoreLand.BorderSizePixel = 0
StoreLand.Position = UDim2.new(0.0199999809, 0, 0.216666669, 0)
StoreLand.Size = UDim2.new(0, 73, 0, 40)
StoreLand.Font = Enum.Font.SourceSans
StoreLand.Text = "Land Store"
StoreLand.TextColor3 = Color3.fromRGB(255, 255, 255)
StoreLand.TextScaled = true
StoreLand.TextSize = 14.000
StoreLand.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
StoreLand.TextWrapped = true

local UICk29 = Instance.new("UICorner", StoreCars)
StoreCars.Name = "StoreCars"
StoreCars.Parent = TPFrame
StoreCars.BackgroundColor3 = Border1
StoreCars.BorderSizePixel = 0
StoreCars.Position = UDim2.new(0.0199999996, 0, 0.415833324, 0)
StoreCars.Size = UDim2.new(0, 73, 0, 40)
StoreCars.Font = Enum.Font.SourceSans
StoreCars.Text = "Boxed Cars"
StoreCars.TextColor3 = Color3.fromRGB(255, 255, 255)
StoreCars.TextScaled = true
StoreCars.TextSize = 14.000
StoreCars.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
StoreCars.TextWrapped = true

local UICk30 = Instance.new("UICorner", GreenBox)
GreenBox.Name = "GreenBox"
GreenBox.Parent = TPFrame
GreenBox.BackgroundColor3 = Border1
GreenBox.BorderSizePixel = 0
GreenBox.Position = UDim2.new(0.0199999996, 0, 0.80583334, 0)
GreenBox.Size = UDim2.new(0, 73, 0, 40)
GreenBox.Font = Enum.Font.SourceSans
GreenBox.Text = "Green Box"
GreenBox.TextColor3 = Color3.fromRGB(255, 255, 255)
GreenBox.TextScaled = true
GreenBox.TextSize = 14.000
GreenBox.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
GreenBox.TextWrapped = true

local UICk31 = Instance.new("UICorner", StoreFancy)
StoreFancy.Name = "StoreFancy"
StoreFancy.Parent = TPFrame
StoreFancy.BackgroundColor3 = Border1
StoreFancy.BorderSizePixel = 0
StoreFancy.Position = UDim2.new(0.0199999996, 0, 0.614166677, 0)
StoreFancy.Size = UDim2.new(0, 73, 0, 40)
StoreFancy.Font = Enum.Font.SourceSans
StoreFancy.Text = "Fancy Furnishings"
StoreFancy.TextColor3 = Color3.fromRGB(255, 255, 255)
StoreFancy.TextScaled = true
StoreFancy.TextSize = 14.000
StoreFancy.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
StoreFancy.TextWrapped = true

local UICk32 = Instance.new("UICorner", StoreLogic)
StoreLogic.Name = "StoreLogic"
StoreLogic.Parent = TPFrame
StoreLogic.BackgroundColor3 = Border1
StoreLogic.BorderSizePixel = 0
StoreLogic.Position = UDim2.new(0.26699999, 0, 0.0250000004, 0)
StoreLogic.Size = UDim2.new(0, 73, 0, 40)
StoreLogic.Font = Enum.Font.SourceSans
StoreLogic.Text = "Link's Logic"
StoreLogic.TextColor3 = Color3.fromRGB(255, 255, 255)
StoreLogic.TextScaled = true
StoreLogic.TextSize = 14.000
StoreLogic.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
StoreLogic.TextWrapped = true

local UICk33 = Instance.new("UICorner", Spawn)
Spawn.Name = "Spawn"
Spawn.Parent = TPFrame
Spawn.BackgroundColor3 = Border1
Spawn.BorderSizePixel = 0
Spawn.Position = UDim2.new(0.504999995, 0, 0.0250000004, 0)
Spawn.Size = UDim2.new(0, 73, 0, 40)
Spawn.Font = Enum.Font.SourceSans
Spawn.Text = "Spawn"
Spawn.TextColor3 = Color3.fromRGB(255, 255, 255)
Spawn.TextScaled = true
Spawn.TextSize = 14.000
Spawn.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Spawn.TextWrapped = true

local UICk34 = Instance.new("UICorner", IceWood)
IceWood.Name = "IceWood"
IceWood.Parent = TPFrame
IceWood.BackgroundColor3 = Border1
IceWood.BorderSizePixel = 0
IceWood.Position = UDim2.new(0.753000021, 0, 0.0250000004, 0)
IceWood.Size = UDim2.new(0, 73, 0, 40)
IceWood.Font = Enum.Font.SourceSans
IceWood.Text = "Ice Wood"
IceWood.TextColor3 = Color3.fromRGB(255, 255, 255)
IceWood.TextScaled = true
IceWood.TextSize = 14.000
IceWood.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
IceWood.TextWrapped = true

local UICk35 = Instance.new("UICorner", Lodge)
Lodge.Name = "Lodge"
Lodge.Parent = TPFrame
Lodge.BackgroundColor3 = Border1
Lodge.BorderSizePixel = 0
Lodge.Position = UDim2.new(0.26699999, 0, 0.805999994, 0)
Lodge.Size = UDim2.new(0, 73, 0, 40)
Lodge.Font = Enum.Font.SourceSans
Lodge.Text = "Lodge"
Lodge.TextColor3 = Color3.fromRGB(255, 255, 255)
Lodge.TextScaled = true
Lodge.TextSize = 14.000
Lodge.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Lodge.TextWrapped = true

local UICk36 = Instance.new("UICorner", Dock)
Dock.Name = "Dock"
Dock.Parent = TPFrame
Dock.BackgroundColor3 = Border1
Dock.BorderSizePixel = 0
Dock.Position = UDim2.new(0.504999995, 0, 0.805999994, 0)
Dock.Size = UDim2.new(0, 73, 0, 40)
Dock.Font = Enum.Font.SourceSans
Dock.Text = "Dock"
Dock.TextColor3 = Color3.fromRGB(255, 255, 255)
Dock.TextScaled = true
Dock.TextSize = 14.000
Dock.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Dock.TextWrapped = true

local UICk37 = Instance.new("UICorner", Bridge)
Bridge.Name = "Bridge"
Bridge.Parent = TPFrame
Bridge.BackgroundColor3 = Border1
Bridge.BorderSizePixel = 0
Bridge.Position = UDim2.new(0.753000021, 0, 0.805999994, 0)
Bridge.Size = UDim2.new(0, 73, 0, 40)
Bridge.Font = Enum.Font.SourceSans
Bridge.Text = "Bridge"
Bridge.TextColor3 = Color3.fromRGB(255, 255, 255)
Bridge.TextScaled = true
Bridge.TextSize = 14.000
Bridge.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Bridge.TextWrapped = true

local UICk38 = Instance.new("UICorner", Cave)
Cave.Name = "Cave"
Cave.Parent = TPFrame
Cave.BackgroundColor3 = Border1
Cave.BorderSizePixel = 0
Cave.Position = UDim2.new(0.753000021, 0, 0.614000022, 0)
Cave.Size = UDim2.new(0, 73, 0, 40)
Cave.Font = Enum.Font.SourceSans
Cave.Text = "Cave"
Cave.TextColor3 = Color3.fromRGB(255, 255, 255)
Cave.TextScaled = true
Cave.TextSize = 14.000
Cave.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Cave.TextWrapped = true

local UICk39 = Instance.new("UICorner", StrangeMan)
StrangeMan.Name = "StrangeMan"
StrangeMan.Parent = TPFrame
StrangeMan.BackgroundColor3 = Border1
StrangeMan.BorderSizePixel = 0
StrangeMan.Position = UDim2.new(0.26699999, 0, 0.614000022, 0)
StrangeMan.Size = UDim2.new(0, 73, 0, 40)
StrangeMan.Font = Enum.Font.SourceSans
StrangeMan.Text = "Strange Man"
StrangeMan.TextColor3 = Color3.fromRGB(255, 255, 255)
StrangeMan.TextScaled = true
StrangeMan.TextSize = 14.000
StrangeMan.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
StrangeMan.TextWrapped = true

local UICk40 = Instance.new("UICorner", YellowWood)
YellowWood.Name = "YellowWood"
YellowWood.Parent = TPFrame
YellowWood.BackgroundColor3 = Border1
YellowWood.BorderSizePixel = 0
YellowWood.Position = UDim2.new(0.504999995, 0, 0.614000022, 0)
YellowWood.Size = UDim2.new(0, 73, 0, 40)
YellowWood.Font = Enum.Font.SourceSans
YellowWood.Text = "Yellow Wood"
YellowWood.TextColor3 = Color3.fromRGB(255, 255, 255)
YellowWood.TextScaled = true
YellowWood.TextSize = 14.000
YellowWood.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
YellowWood.TextWrapped = true

local UICk41 = Instance.new("UICorner", Volcano)
Volcano.Name = "Volcano"
Volcano.Parent = TPFrame
Volcano.BackgroundColor3 = Border1
Volcano.BorderSizePixel = 0
Volcano.Position = UDim2.new(0.504999995, 0, 0.216999993, 0)
Volcano.Size = UDim2.new(0, 73, 0, 40)
Volcano.Font = Enum.Font.SourceSans
Volcano.Text = "Volcano"
Volcano.TextColor3 = Color3.fromRGB(255, 255, 255)
Volcano.TextScaled = true
Volcano.TextSize = 14.000
Volcano.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Volcano.TextWrapped = true

local UICk42 = Instance.new("UICorner", Palm)
Palm.Name = "Palm"
Palm.Parent = TPFrame
Palm.BackgroundColor3 = Border1
Palm.BorderSizePixel = 0
Palm.Position = UDim2.new(0.753000021, 0, 0.216999993, 0)
Palm.Size = UDim2.new(0, 73, 0, 40)
Palm.Font = Enum.Font.SourceSans
Palm.Text = "Palm"
Palm.TextColor3 = Color3.fromRGB(255, 255, 255)
Palm.TextScaled = true
Palm.TextSize = 14.000
Palm.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Palm.TextWrapped = true

local UICk43 = Instance.new("UICorner", StoreBobs)
StoreBobs.Name = "StoreBobs"
StoreBobs.Parent = TPFrame
StoreBobs.BackgroundColor3 = Border1
StoreBobs.BorderSizePixel = 0
StoreBobs.Position = UDim2.new(0.26699999, 0, 0.416399986, 0)
StoreBobs.Size = UDim2.new(0, 73, 0, 40)
StoreBobs.Font = Enum.Font.SourceSans
StoreBobs.Text = "Bob's Shack"
StoreBobs.TextColor3 = Color3.fromRGB(255, 255, 255)
StoreBobs.TextScaled = true
StoreBobs.TextSize = 14.000
StoreBobs.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
StoreBobs.TextWrapped = true

local UICk44 = Instance.new("UICorner", EndTimes)
EndTimes.Name = "EndTimes"
EndTimes.Parent = TPFrame
EndTimes.BackgroundColor3 = Border1
EndTimes.BorderSizePixel = 0
EndTimes.Position = UDim2.new(0.753000021, 0, 0.416000009, 0)
EndTimes.Size = UDim2.new(0, 73, 0, 40)
EndTimes.Font = Enum.Font.SourceSans
EndTimes.Text = "End Times"
EndTimes.TextColor3 = Color3.fromRGB(255, 255, 255)
EndTimes.TextScaled = true
EndTimes.TextSize = 14.000
EndTimes.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
EndTimes.TextWrapped = true

local UICk45 = Instance.new("UICorner", Swamp)
Swamp.Name = "Swamp"
Swamp.Parent = TPFrame
Swamp.BackgroundColor3 = Border1
Swamp.BorderSizePixel = 0
Swamp.Position = UDim2.new(0.504999995, 0, 0.416000009, 0)
Swamp.Size = UDim2.new(0, 73, 0, 40)
Swamp.Font = Enum.Font.SourceSans
Swamp.Text = "Swamp"
Swamp.TextColor3 = Color3.fromRGB(255, 255, 255)
Swamp.TextScaled = true
Swamp.TextSize = 14.000
Swamp.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Swamp.TextWrapped = true

local UICk46 = Instance.new("UICorner", StoreFineArts)
StoreFineArts.Name = "StoreFineArts"
StoreFineArts.Parent = TPFrame
StoreFineArts.BackgroundColor3 = Border1
StoreFineArts.BorderSizePixel = 0
StoreFineArts.Position = UDim2.new(0.26699999, 0, 0.216999993, 0)
StoreFineArts.Size = UDim2.new(0, 73, 0, 40)
StoreFineArts.Font = Enum.Font.SourceSans
StoreFineArts.Text = "Fine Arts"
StoreFineArts.TextColor3 = Color3.fromRGB(255, 255, 255)
StoreFineArts.TextScaled = true
StoreFineArts.TextSize = 14.000
StoreFineArts.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
StoreFineArts.TextWrapped = true

local UICk47 = Instance.new("UICorner", Hub)
Hub.Name = "Hub"
Hub.Parent = mainframe
Hub.BackgroundColor3 = Border1
Hub.BorderColor3 = Color3.fromRGB(10, 120, 255)
Hub.BorderSizePixel = 0
Hub.Position = UDim2.new(0, 0, 0.714999974, 0)
Hub.Size = UDim2.new(0, 80, 0, 40)
Hub.Font = Enum.Font.SourceSans
Hub.Text = "Hub's"
Hub.TextColor3 = Color3.fromRGB(255, 255, 255)
Hub.TextScaled = true
Hub.TextSize = 32.000
Hub.TextWrapped = true
Hub.MouseButton1Down:connect(function()
CreditsFrame.Visible = false
DupeFrame.Visible = false
HubFrame.Visible = true
MainFrame.Visible = false
PlotFrame.Visible = false
TPFrame.Visible = false
WoodFrame.Visible = false
end)

local UICk48 = Instance.new("UICorner", HubFrame)
HubFrame.Name = "HubFrame"
HubFrame.Parent = Hub
HubFrame.BackgroundColor3 = Back1
HubFrame.BorderSizePixel = 0
HubFrame.Position = UDim2.new(1, 0, -4.00400019, 0)
HubFrame.Size = UDim2.new(0, 320, 0, 240)
HubFrame.Visible = false

local UICk49 = Instance.new("UICorner", Blood)
Blood.Name = "Butter"
Blood.Parent = HubFrame
Blood.BackgroundColor3 = Border1
Blood.BorderSizePixel = 0
Blood.Position = UDim2.new(0.0199999809, 0, 0.0250000004, 0)
Blood.Size = UDim2.new(0, 151, 0, 72)
Blood.Font = Enum.Font.SourceSans
Blood.Text = "Butter"
Blood.TextColor3 = Color3.fromRGB(255, 255, 255)
Blood.TextScaled = true
Blood.TextSize = 14.000
Blood.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Blood.TextWrapped = true

local UICk50 = Instance.new("UICorner", Orignal)
Orignal.Name = "Original"
Orignal.Parent = HubFrame
Orignal.BackgroundColor3 =Border1
Orignal.BorderSizePixel = 0
Orignal.Position = UDim2.new(0.0199999996, 0, 0.350000024, 0)
Orignal.Size = UDim2.new(0, 151, 0, 72)
Orignal.Font = Enum.Font.SourceSans
Orignal.Text = "Original"
Orignal.TextColor3 = Color3.fromRGB(255, 255, 255)
Orignal.TextScaled = true
Orignal.TextSize = 14.000
Orignal.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Orignal.TextWrapped = true

local UICk51 = Instance.new("UICorner", LT2)
LT2.Name = "LT2"
LT2.Parent = HubFrame
LT2.BackgroundColor3 = Border1
LT2.BorderSizePixel = 0
LT2.Position = UDim2.new(0.508000016, 0, 0.349999994, 0)
LT2.Size = UDim2.new(0, 151, 0, 72)
LT2.Font = Enum.Font.SourceSans
LT2.Text = "LT2"
LT2.TextColor3 = Color3.fromRGB(255, 255, 255)
LT2.TextScaled = true
LT2.TextSize = 14.000
LT2.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
LT2.TextWrapped = true

local UICk52 = Instance.new("UICorner", Venyx)
Venyx.Name = "LumberScript"
Venyx.Parent = HubFrame
Venyx.BackgroundColor3 = Border1
Venyx.BorderSizePixel = 0
Venyx.Position = UDim2.new(0.508000016, 0, 0.0250000004, 0)
Venyx.Size = UDim2.new(0, 151, 0, 72)
Venyx.Font = Enum.Font.SourceSans
Venyx.Text = "LumberScript"
Venyx.TextColor3 = Color3.fromRGB(255, 255, 255)
Venyx.TextScaled = true
Venyx.TextSize = 14.000
Venyx.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Venyx.TextWrapped = true

local UICk58 = Instance.new("UICorner", infiniteyield)
infiniteyield.Name = "infiniteyield"
infiniteyield.Parent = HubFrame
infiniteyield.BackgroundColor3 = Border1
infiniteyield.BorderSizePixel = 0
infiniteyield.Position = UDim2.new(0.0199999996, 0, 0.675000012, 0)
infiniteyield.Size = UDim2.new(0, 151, 0, 72)
infiniteyield.Font = Enum.Font.SourceSans
infiniteyield.Text = "InfiniteYield"
infiniteyield.TextColor3 = Color3.fromRGB(255, 255, 255)
infiniteyield.TextScaled = true
infiniteyield.TextSize = 14.000
infiniteyield.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
infiniteyield.TextWrapped = true

local UICk53 = Instance.new("UICorner", Credits)
Credits.Name = "Credits"
Credits.Parent = mainframe
Credits.BackgroundColor3 = Border1
Credits.BorderColor3 = Color3.fromRGB(10, 120, 255)
Credits.BorderSizePixel = 0
Credits.Position = UDim2.new(0, 0, 0.85799998, 0)
Credits.Size = UDim2.new(0, 80, 0, 40)
Credits.Font = Enum.Font.SourceSans
Credits.Text = "Credits"
Credits.TextColor3 = Color3.fromRGB(255, 255, 255)
Credits.TextScaled = true
Credits.TextSize = 32.000
Credits.TextWrapped = true
Credits.MouseButton1Down:connect(function()
CreditsFrame.Visible = true
DupeFrame.Visible = false
HubFrame.Visible = false
MainFrame.Visible = false
PlotFrame.Visible = false
TPFrame.Visible = false
WoodFrame.Visible = false
end)

local UICk54 = Instance.new("UICorner", CreditsFrame)
CreditsFrame.Name = "CreditsFrame"
CreditsFrame.Parent = Credits
CreditsFrame.BackgroundColor3 = Back1
CreditsFrame.BorderSizePixel = 0
CreditsFrame.Position = UDim2.new(1, 0, -5.00599957, 0)
CreditsFrame.Size = UDim2.new(0, 320, 0, 240)

MadeBy.Name = "Made By"
MadeBy.Parent = CreditsFrame
MadeBy.BackgroundColor3 = Border1
MadeBy.BackgroundTransparency = 100.000
MadeBy.BorderSizePixel = 0
MadeBy.Position = UDim2.new(0.159374997, 0, 0, 0)
MadeBy.Size = UDim2.new(0, 200, 0, 48)
MadeBy.Font = Enum.Font.GothamBold
MadeBy.Text = "Made By"
MadeBy.TextColor3 = Color3.fromRGB(255, 255, 255)
MadeBy.TextScaled = true
MadeBy.TextSize = 13.000
MadeBy.TextWrapped = true
 
SnowyShiro.Name = "KM1MK2MK358"
SnowyShiro.Parent = CreditsFrame
SnowyShiro.BackgroundColor3 = Border1
SnowyShiro.BackgroundTransparency = 100.000
SnowyShiro.BorderSizePixel = 0
SnowyShiro.Position = UDim2.new(0, 0, 0.19600004, 0)
SnowyShiro.Size = UDim2.new(0, 320, 0, 48)
SnowyShiro.Font = Enum.Font.GothamBold
SnowyShiro.Text = "KM1MK2MK358"
SnowyShiro.TextColor3 = Color3.fromRGB(255, 255, 255)
SnowyShiro.TextSize = 27.000
SnowyShiro.TextWrapped = true

local UICk55 = Instance.new("UICorner", Name)
Name.Name = "Name"
Name.Parent = mainframe
Name.BackgroundColor3 = Back1
Name.BorderSizePixel = 0
Name.Position = UDim2.new(0.200000003, 0, 0, 0)
Name.Size = UDim2.new(0, 240, 0, 40)
Name.Font = Enum.Font.SourceSans
Name.Text = "KM1MK2MK358's HubV1.6Beta"
Name.TextColor3 = Color3.fromRGB(255, 255, 255)
Name.TextScaled = true
Name.TextSize = 14.000
Name.TextWrapped = true
 
local function QMMS_fake_script() -- mainframe.LocalScript 
	local script = Instance.new('LocalScript', mainframe)
 
	script.parent.Selectable = true
	script.Parent.Active = true
	script.parent.Draggable = true
end
coroutine.wrap(QMMS_fake_script)()
 
local MoneyCooldown = false
local CurrentSlot = game.Players.LocalPlayer:WaitForChild("CurrentSaveSlot").Value
local ScriptLoadOrSave = false
local CurrentlySavingOrLoading = game.Players.LocalPlayer:WaitForChild("CurrentlySavingOrLoading")
 
local function CheckIfSlotAvailable(Slot)
	for a,b in pairs(game.ReplicatedStorage.LoadSaveRequests.GetMetaData:InvokeServer(game.Players.LocalPlayer)) do 
		if a == Slot then 
			for c,d in pairs(b) do 
				if c == "NumSaves" and d ~= 0 then 
					return true
				else
					return false
				end
			end
		end
	end
end

 

 
local function SendNotification(title,text,duration,...)
  game.StarterGui:SetCore("SendNotification", {
    Title = title;
    Text = text;
    Icon = "";
    Duration = duration;
  })
end
 
--Join Detecter
 
game.Players.ChildAdded:Connect(function(player)
  if not pcall (function()
  SendNotification("Player JOINED",""..player.Name.." has JOINED the game",5 )
  end) then
    print ("Error")
  end
  end)
 
--Leave Detecter
 
  game.Players.ChildRemoved:Connect(function(player)
  if not pcall (function()
  SendNotification("Player LEFT",""..player.Name.." has LEFT the game",4.4 )
  end) then
    print ("Error")
  end
  end)
 
  SendNotification("Loaded","Join and leave detector is loaded",2)
 
--Walkspeed
 
Speed.MouseButton1Down:connect(function()
while true do
    wait()
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = SpeedValue.Text
end
end)
 
--Jumppower
 
Jump.MouseButton1Down:connect(function()
while true do
    wait()
    game.Players.LocalPlayer.Character.Humanoid.JumpPower = JumpValue.Text
end
end)

 
--Fly
 
local toggle = false
	Fly.MouseButton1Click:Connect(function()
		toggle = not toggle
		Fly.TextColor3 = (toggle and Color3.fromRGB(85, 255, 127) or Color3.fromRGB(255,255,255))
		if toggle then
			flying = not flying
	repeat wait()
	until game.Players.LocalPlayer and game.Players.LocalPlayer.Character and game.Players.LocalPlayer.Character:findFirstChild("Torso") and game.Players.LocalPlayer.Character:findFirstChild("Humanoid")
	local mouse = game.Players.LocalPlayer:GetMouse()
	repeat wait() until mouse
	local plr = game.Players.LocalPlayer
	local torso = plr.Character.Torso
	local deb = true
	local ctrl = {f = 0, b = 0, l = 0, r = 0}
	local lastctrl = {f = 0, b = 0, l = 0, r = 0}
	local maxspeed = 200
	local speed = 0
	if flying then
	end
 
	function FlyFunction()
	local bg = Instance.new("BodyGyro", torso)
	bg.P = 9e4
	bg.maxTorque = Vector3.new(9e9, 9e9, 9e9)
	bg.cframe = torso.CFrame
	local bv = Instance.new("BodyVelocity", torso)
	bv.velocity = Vector3.new(0,0.1,0)
	bv.maxForce = Vector3.new(9e9, 9e9, 9e9)
	repeat wait()
	plr.Character.Humanoid.PlatformStand = true
	if ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0 then
	speed = speed+.5+(speed/maxspeed)
	if speed > maxspeed then
	speed = maxspeed
	end
	elseif not (ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0) and speed ~= 0 then
	speed = speed-1
	if speed < 0 then
	speed = 0
	end
	end
	if (ctrl.l + ctrl.r) ~= 0 or (ctrl.f + ctrl.b) ~= 0 then
	bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (ctrl.f+ctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(ctrl.l+ctrl.r,(ctrl.f+ctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
	lastctrl = {f = ctrl.f, b = ctrl.b, l = ctrl.l, r = ctrl.r}
	elseif (ctrl.l + ctrl.r) == 0 and (ctrl.f + ctrl.b) == 0 and speed ~= 0 then
	bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (lastctrl.f+lastctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(lastctrl.l+lastctrl.r,(lastctrl.f+lastctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
	else
	bv.velocity = Vector3.new(0,0.1,0)
	end
	bg.cframe = game.Workspace.CurrentCamera.CoordinateFrame * CFrame.Angles(-math.rad((ctrl.f+ctrl.b)*50*speed/maxspeed),0,0)
	until not flying
	ctrl = {f = 0, b = 0, l = 0, r = 0}
	lastctrl = {f = 0, b = 0, l = 0, r = 0}
	speed = 0
	bg:Destroy()
	bv:Destroy()
	plr.Character.Humanoid.PlatformStand = false
	end
	mouse.KeyDown:connect(function(key)
	if key:lower() == "w" then
	ctrl.f = 1
	elseif key:lower() == "s" then
	ctrl.b = -1
	elseif key:lower() == "a" then
	ctrl.l = -1
	elseif key:lower() == "d" then
	ctrl.r = 1
 
	end
	end)
	mouse.KeyUp:connect(function(key)
	if key:lower() == "w" then
	ctrl.f = 0
	elseif key:lower() == "s" then
	ctrl.b = 0
	elseif key:lower() == "a" then
	ctrl.l = 0
	elseif key:lower() == "d" then
	ctrl.r = 0
	end
	end)
	FlyFunction()
		else
			flying = not flying
	repeat wait()
	until game.Players.LocalPlayer and game.Players.LocalPlayer.Character and game.Players.LocalPlayer.Character:findFirstChild("Torso") and game.Players.LocalPlayer.Character:findFirstChild("Humanoid")
	local mouse = game.Players.LocalPlayer:GetMouse()
	repeat wait() until mouse
	local plr = game.Players.LocalPlayer
	local torso = plr.Character.Torso
	local deb = true
	local ctrl = {f = 0, b = 0, l = 0, r = 0}
	local lastctrl = {f = 0, b = 0, l = 0, r = 0}
	local maxspeed = 200
	local speed = 0
	if flying then
	end
 
	function FlyFunction()
	local bg = Instance.new("BodyGyro", torso)
	bg.P = 9e4
	bg.maxTorque = Vector3.new(9e9, 9e9, 9e9)
	bg.cframe = torso.CFrame
	local bv = Instance.new("BodyVelocity", torso)
	bv.velocity = Vector3.new(0,0.1,0)
	bv.maxForce = Vector3.new(9e9, 9e9, 9e9)
	repeat wait()
	plr.Character.Humanoid.PlatformStand = true
	if ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0 then
	speed = speed+.5+(speed/maxspeed)
	if speed > maxspeed then
	speed = maxspeed
	end
	elseif not (ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0) and speed ~= 0 then
	speed = speed-1
	if speed < 0 then
	speed = 0
	end
	end
	if (ctrl.l + ctrl.r) ~= 0 or (ctrl.f + ctrl.b) ~= 0 then
	bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (ctrl.f+ctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(ctrl.l+ctrl.r,(ctrl.f+ctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
	lastctrl = {f = ctrl.f, b = ctrl.b, l = ctrl.l, r = ctrl.r}
	elseif (ctrl.l + ctrl.r) == 0 and (ctrl.f + ctrl.b) == 0 and speed ~= 0 then
	bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (lastctrl.f+lastctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(lastctrl.l+lastctrl.r,(lastctrl.f+lastctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
	else
	bv.velocity = Vector3.new(0,0.1,0)
	end
	bg.cframe = game.Workspace.CurrentCamera.CoordinateFrame * CFrame.Angles(-math.rad((ctrl.f+ctrl.b)*50*speed/maxspeed),0,0)
	until not flying
	ctrl = {f = 0, b = 0, l = 0, r = 0}
	lastctrl = {f = 0, b = 0, l = 0, r = 0}
	speed = 0
	bg:Destroy()
	bv:Destroy()
	plr.Character.Humanoid.PlatformStand = false
	end
	mouse.KeyDown:connect(function(key)
	if key:lower() == "w" then
	ctrl.f = 1
	elseif key:lower() == "s" then
	ctrl.b = -1
	elseif key:lower() == "a" then
	ctrl.l = -1
	elseif key:lower() == "d" then
	ctrl.r = 1
 
	end
	end)
	mouse.KeyUp:connect(function(key)
	if key:lower() == "w" then
	ctrl.f = 0
	elseif key:lower() == "s" then
	ctrl.b = 0
	elseif key:lower() == "a" then
	ctrl.l = 0
	elseif key:lower() == "d" then
	ctrl.r = 0
	end
	end)
	FlyFunction()
		end
	end)
 
--Car Flight
 
CarFlight.MouseButton1Down:connect(function()
repeat wait()
until game.Players.LocalPlayer and game.Players.LocalPlayer.Character and game.Players.LocalPlayer.Character:findFirstChild("Torso") and game.Players.LocalPlayer.Character:findFirstChild("Humanoid")
local mouse = game.Players.LocalPlayer:GetMouse()
repeat wait() until mouse
local plr = game.Players.LocalPlayer
local torso = plr.Character.Torso
local flying = true
local deb = true
local ctrl = {f = 0, b = 0, l = 0, r = 0}
local lastctrl = {f = 0, b = 0, l = 0, r = 0}
local maxspeed = 500
local speed = 0
 
function Fly()
local bg = Instance.new("BodyGyro", torso)
bg.P = 9e4
bg.maxTorque = Vector3.new(9e9, 9e9, 9e9)
bg.cframe = torso.CFrame
local bv = Instance.new("BodyVelocity", torso)
bv.velocity = Vector3.new(0,0.1,0)
bv.maxForce = Vector3.new(9e9, 9e9, 9e9)
repeat wait()
plr.Character.Humanoid.PlatformStand = false
if ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0 then
speed = speed+125.0+(speed/maxspeed)
if speed > maxspeed then
speed = maxspeed
end
elseif not (ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0) and speed ~= 0 then
speed = speed-250
if speed < 0 then
speed = 0
end
end
if (ctrl.l + ctrl.r) ~= 0 or (ctrl.f + ctrl.b) ~= 0 then
bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (ctrl.f+ctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(ctrl.l+ctrl.r,(ctrl.f+ctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
lastctrl = {f = ctrl.f, b = ctrl.b, l = ctrl.l, r = ctrl.r}
elseif (ctrl.l + ctrl.r) == 0 and (ctrl.f + ctrl.b) == 0 and speed ~= 0 then
bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (lastctrl.f+lastctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(lastctrl.l+lastctrl.r,(lastctrl.f+lastctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
else
bv.velocity = Vector3.new(0,0.1,0)
end
bg.cframe = game.Workspace.CurrentCamera.CoordinateFrame * CFrame.Angles(-math.rad((ctrl.f+ctrl.b)*50*speed/maxspeed),0,0)
until not flying
ctrl = {f = 0, b = 0, l = 0, r = 0}
lastctrl = {f = 0, b = 0, l = 0, r = 0}
speed = 0
bg:Destroy()
bv:Destroy()
plr.Character.Humanoid.PlatformStand = false
end
mouse.KeyDown:connect(function(key)
if key:lower() == "z" then
if flying then flying = false
else
flying = true
Fly()
end
elseif key:lower() == "w" then
ctrl.f = 1
elseif key:lower() == "s" then
ctrl.b = -1
elseif key:lower() == "a" then
ctrl.l = -1
elseif key:lower() == "d" then
ctrl.r = 1
end
end)
mouse.KeyUp:connect(function(key)
if key:lower() == "w" then
ctrl.f = 0
elseif key:lower() == "s" then
ctrl.b = 0
elseif key:lower() == "a" then
ctrl.l = 0
elseif key:lower() == "d" then
ctrl.r = 0
end
wait(5)
end)
end)
 
--Infinite Jump
 
local toggle = false
	InfJump.MouseButton1Click:Connect(function()
		toggle = not toggle
		InfJump.TextColor3 = (toggle and Color3.fromRGB(85, 255, 127) or Color3.fromRGB(255,255,255))
		if toggle then
			InfiniteJumpEnabled = true
		game:GetService("UserInputService").JumpRequest:connect(function()
		if InfiniteJumpEnabled then
			game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")
			InfiniteJumpEnabled = true
		end
	end)
 
		else
				InfiniteJumpEnabled = false
	       game:GetService("UserInputService").JumpRequest:connect(function()
		if InfiniteJumpEnabled then
			game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")
 
		end
	end)
		end
	end)
 
--No Clip
 
	_G.noclip = false
	game:GetService('RunService').Stepped:connect(function()
	if noclip then
	game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
	NoClip.TextColor3 = Color3.fromRGB(85, 255, 127)
	end
	end)
	NoClip.MouseButton1Down:connect(function()
	noclip = not noclip
	NoClip.TextColor3 = Color3.fromRGB(255, 255, 255)
	end)
 
--Ctrl+Click TP
 
TP.MouseButton1Down:connect(function()
local UIS = game:GetService("UserInputService")
 
local Player = game.Players.LocalPlayer
local Mouse = Player:GetMouse()
 
 
function GetCharacter()
   return game.Players.LocalPlayer.Character
end
 
function Teleport(pos)
   local Char = GetCharacter()
   if Char then
       Char:MoveTo(pos)
   end
end
 
 
UIS.InputBegan:Connect(function(input)
   if input.UserInputType == Enum.UserInputType.MouseButton1 and UIS:IsKeyDown(Enum.KeyCode.LeftControl) then
       Teleport(Mouse.Hit.p)
   end
end)
end)

--Move
Move.MouseButton1Click:Connect(
    function()
        local MoveTool = Instance.new("Tool")

        local Moving
        local Target

        MoveTool.Name = "MoveTool"
        MoveTool.RequiresHandle = false
        MoveTool.Activated:Connect(
            function()
                Moving = true
                Target = game.Players.LocalPlayer:GetMouse().Target
                repeat
                    game.Players.LocalPlayer:GetMouse().Move:Wait()
                    Target.CFrame = CFrame.new(game.Players.LocalPlayer:GetMouse().Hit.p)
                    game.Players.LocalPlayer:GetMouse().TargetFilter = Target
                until Moving == false
            end
        )
        MoveTool.Deactivated:Connect(
            function()
                Moving = false
                game.ReplicatedStorage.PlayerEvents["e" .. game.Players.LocalPlayer.UserId].DestroyItem:FireServer(
                    Target
                )
                game.ReplicatedStorage.PlayerEvents["e" .. game.Players.LocalPlayer.UserId].PlaceItem:FireServer(
                    Target.CFrame,
                    Target
                )
            end
        )

        MoveTool.TextureId = "rbxassetid://1048129653"
        MoveTool.Parent = game.Players.LocalPlayer.Backpack
    end
)
--Secret Walkspeed

SecretWalkSpeed.MouseButton1Down:connect(function()
	local walkspeedplayer = game:GetService("Players").LocalPlayer
	local walkspeedmouse = walkspeedplayer:GetMouse()
 
	local walkspeedenabled = false
 
	function x_walkspeed(key)
		if (key == "x") then
			if walkspeedenabled == false then
				_G.WS = 200;
				local Humanoid = game:GetService("Players").LocalPlayer.Character.Humanoid;
				Humanoid:GetPropertyChangedSignal("WalkSpeed"):Connect(function()
				Humanoid.WalkSpeed = _G.WS;
				end)
				Humanoid.WalkSpeed = _G.WS;
 
				walkspeedenabled = true
			elseif walkspeedenabled == true then
				_G.WS = 20;
				local Humanoid = game:GetService("Players").LocalPlayer.Character.Humanoid;
				Humanoid:GetPropertyChangedSignal("WalkSpeed"):Connect(function()
				Humanoid.WalkSpeed = _G.WS;
				end)
				Humanoid.WalkSpeed = _G.WS;
 
				walkspeedenabled = false
			end
		end
	end
 
	walkspeedmouse.KeyDown:connect(x_walkspeed)
 
end)

--walkonwater
 
	local toggle = false
	walkonwater.MouseButton1Click:Connect(function()
		toggle = not toggle
		walkonwater.TextColor3 = (toggle and Color3.fromRGB(85, 255, 127) or Color3.fromRGB(255,255,255))
		if toggle then
			for index, water in pairs(game.Workspace.Water:GetChildren()) do
	   water.CanCollide = true
	end
		else
			for index, water in pairs(game.Workspace.Water:GetChildren()) do
	   water.CanCollide = false
	end
		end
	end)

    --No Fog
NoFog.MouseButton1Down:connect(function()
	--Fog.BackgroundColor3 = Color3.new(0, 0, 0)
                      NoFog.TextColor3 = Color3.new(1, 1, 1)
game.Lighting.Changed:connect(function()
	game.Lighting.TimeOfDay = "12:00:00"
	game.Lighting.FogEnd = 9999
	game.Lighting.Brightness = 2
end)
end)

--Wood R Us
 
StoreWoodRUs.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(265, 5, 57))
end)
 
--Link's Logic
 
StoreLogic.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(4607, 9, -798))
end)
 
--Spawn
 
Spawn.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(155, 5, 74))
end)
 
--Ice Wood
 
IceWood.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(1451.66248, 412.208405, 3183.47607))
end)
 
--Land Store
 
StoreLand.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(258, 5, -99))
end)
 
--Fine Arts
 
StoreFineArts.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(5207, -156, 719))
end)
 
 
--Volcano
 
Volcano.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(-1585, 625, 1140))
end)
 
--Palm
 
Palm.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(2549, 5, -42))
end)
 
--Boxed Cars
 
StoreCars.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(509, 5.2, -1463))
end)
 
--Bob's Shack
 
StoreBobs.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(260, 10, -2542))
end)
 
--Swamp
 
Swamp.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(-1209, 138, -801))
end)
 
--End Times
 
EndTimes.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(113, -204, -951))
end)
 
--Fancy Furnishings
 
StoreFancy.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(491, 13, -1720))
end)
 
--Strange Man
 
StrangeMan.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(1061, 20, 1131))
end)
 
--Yellow Wood
 
YellowWood.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(-1124.91565, 1.10021782, -943.932129))
end)
 
--Cave
 
Cave.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(3581, -177, 430))
end)
 
--Green Box
 
GreenBox.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(-1668.39197, 349.601929, 1475.36255))
end)
 
--Lodge
 
Lodge.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(1244, 66, 2306))
end)
 
--Dock
 
Dock.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(1114, 3.2, -197))
end)
 
--Bridge
 
Bridge.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(113, 15, -977))
end)
 





 


 
--Maxland
 
MaxLand.MouseButton1Down:Connect(function()
for i, v in pairs(game:GetService("Workspace").Properties:GetChildren()) do
        if v:FindFirstChild("Owner") and v.Owner.Value == game.Players.LocalPlayer then
            base = v
            square = v.OriginSquare
            end
        end
    function makebase(pos)
        local Event = game:GetService("ReplicatedStorage").PropertyPurchasing.ClientExpandedProperty
        Event:FireServer(base, pos)
        end
    spos = square.Position
    makebase(CFrame.new(spos.X + 40, spos.Y, spos.Z))
    makebase(CFrame.new(spos.X - 40, spos.Y, spos.Z))
    makebase(CFrame.new(spos.X, spos.Y, spos.Z + 40))
    makebase(CFrame.new(spos.X, spos.Y, spos.Z - 40))
    makebase(CFrame.new(spos.X + 40, spos.Y, spos.Z + 40))
    makebase(CFrame.new(spos.X + 40, spos.Y, spos.Z - 40))
    makebase(CFrame.new(spos.X - 40, spos.Y, spos.Z + 40))
    makebase(CFrame.new(spos.X - 40, spos.Y, spos.Z - 40))
    makebase(CFrame.new(spos.X + 80, spos.Y, spos.Z))
    makebase(CFrame.new(spos.X - 80, spos.Y, spos.Z))
    makebase(CFrame.new(spos.X, spos.Y, spos.Z + 80))
    makebase(CFrame.new(spos.X, spos.Y, spos.Z - 80))
--Corners--
    makebase(CFrame.new(spos.X + 80, spos.Y, spos.Z + 80))
    makebase(CFrame.new(spos.X + 80, spos.Y, spos.Z - 80))
    makebase(CFrame.new(spos.X - 80, spos.Y, spos.Z + 80))
    makebase(CFrame.new(spos.X - 80, spos.Y, spos.Z - 80))
--Corners--
    makebase(CFrame.new(spos.X + 40, spos.Y, spos.Z + 80))
    makebase(CFrame.new(spos.X - 40, spos.Y, spos.Z + 80))
    makebase(CFrame.new(spos.X + 80, spos.Y, spos.Z + 40))
    makebase(CFrame.new(spos.X + 80, spos.Y, spos.Z - 40))
    makebase(CFrame.new(spos.X - 80, spos.Y, spos.Z + 40))
    makebase(CFrame.new(spos.X - 80, spos.Y, spos.Z - 40))
    makebase(CFrame.new(spos.X + 40, spos.Y, spos.Z - 80))
    makebase(CFrame.new(spos.X - 40, spos.Y, spos.Z - 80))
 
end)
 


--Blood
 
Blood.MouseButton1Click:Connect(function()
	loadstring(Game:HttpGet("https://pastebin.com/raw/ALJyH1LN"))("Butter")
end)
--LT2
LT2.MouseButton1Click:Connect(function()
	game:HttpGet("https://getexploits.com/cexecution/699646509528141824")
loadstring(game:HttpGet("https://raw.githubusercontent.com/IHateSchoolIsCool/FuckCheapShops/main/Schoolhub%20Selector"))("Fuck Cheap Shops")
end)

--infiniteyield
infiniteyield.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet(('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'),true))()
end)

--Orignal
Orignal.MouseButton1Click:Connect(function()
	local shiroshubv2 = Instance.new("ScreenGui")
local mainframe = Instance.new("Frame")
local Minimise = Instance.new("TextButton")
local Dupe = Instance.new("TextButton")
local DupeFrame = Instance.new("Frame")
local CountAxes = Instance.new("TextButton")
local StoreAxes = Instance.new("TextButton")
local RestoreAxes = Instance.new("TextButton")
local DupeSlot = Instance.new("TextBox")
local MoneyDupeSlot = Instance.new("TextBox")
local MoneyDupe = Instance.new("TextLabel")
local AxeDupe = Instance.new("TextLabel")
local Dupe_2 = Instance.new("TextLabel")
local MoneyStep1 = Instance.new("TextButton")
local MoneyStep2 = Instance.new("TextButton")
local DupeStep1 = Instance.new("TextButton")
local DupeStep2 = Instance.new("TextButton")
local Main = Instance.new("TextButton")
local MainFrame = Instance.new("Frame")
local Speed = Instance.new("TextButton")
local Fly = Instance.new("TextButton")
local GoldenAxe = Instance.new("TextButton")
local TP = Instance.new("TextButton")
local Paint = Instance.new("TextButton")
local AllBp = Instance.new("TextButton")
local CarFlight = Instance.new("TextButton")
local NoFog = Instance.new("TextButton")
local ResetCharacter = Instance.new("TextButton")
local NoClip = Instance.new("TextButton")
local InfJump = Instance.new("TextButton")
local jesus = Instance.new("TextButton")
local FastDelBps = Instance.new("TextButton")
local Jump = Instance.new("TextButton")
local SpeedValue = Instance.new("TextBox")
local JumpValue = Instance.new("TextBox")
local SecretWalkSpeed = Instance.new("TextButton")
local Plot = Instance.new("TextButton")
local PlotFrame = Instance.new("Frame")
local BlackListAll = Instance.new("TextButton")
local MaxLand = Instance.new("TextButton")
local WipeBase = Instance.new("TextButton")
local AntiBLAll = Instance.new("TextButton")
local CopyBase = Instance.new("TextButton")
local PlayerName = Instance.new("TextBox")
local You = Instance.new("TextLabel")
local Others = Instance.new("TextLabel")
local Wood = Instance.new("TextButton")
local WoodFrame = Instance.new("Frame")
local SellWood = Instance.new("TextButton")
local SellPlanks = Instance.new("TextButton")
local ModWood = Instance.new("TextButton")
local TPWood = Instance.new("TextButton")
local TPPlanks = Instance.new("TextButton")
local RemoveTrees = Instance.new("TextButton")
local TP_2 = Instance.new("TextButton")
local TPFrame = Instance.new("Frame")
local StoreWoodRUs = Instance.new("TextButton")
local StoreLand = Instance.new("TextButton")
local StoreCars = Instance.new("TextButton")
local GreenBox = Instance.new("TextButton")
local StoreFancy = Instance.new("TextButton")
local StoreLogic = Instance.new("TextButton")
local Spawn = Instance.new("TextButton")
local IceWood = Instance.new("TextButton")
local Lodge = Instance.new("TextButton")
local Dock = Instance.new("TextButton")
local Bridge = Instance.new("TextButton")
local Cave = Instance.new("TextButton")
local StrangeMan = Instance.new("TextButton")
local YellowWood = Instance.new("TextButton")
local Volcano = Instance.new("TextButton")
local Palm = Instance.new("TextButton")
local StoreBobs = Instance.new("TextButton")
local EndTimes = Instance.new("TextButton")
local Swamp = Instance.new("TextButton")
local StoreFineArts = Instance.new("TextButton")
local Hub = Instance.new("TextButton")
local HubFrame = Instance.new("Frame")
local Blood = Instance.new("TextButton")
local Venyx = Instance.new("TextButton")
local BringUp = Instance.new("TextButton")
local LightLumber = Instance.new("TextButton")
local Ferry = Instance.new("TextButton")
local JohiroAxeDupe = Instance.new("TextButton")
local Credits = Instance.new("TextButton")
local CreditsFrame = Instance.new("Frame")
local MadeBy = Instance.new("TextLabel")
local SnowyShiro = Instance.new("TextLabel")
local Credits_2 = Instance.new("TextLabel")
local AnimeCheat = Instance.new("TextLabel")
local Johiro = Instance.new("TextLabel")
local Sten = Instance.new("TextLabel")
local Averias = Instance.new("TextLabel")
local Close = Instance.new("TextButton")
local Name = Instance.new("TextLabel")
local openbutton = Instance.new("TextButton")
 
shiroshubv2.Name = "shiroshubv2"
shiroshubv2.Parent = game.CoreGui
 
mainframe.Name = "mainframe"
mainframe.Parent = shiroshubv2
mainframe.BackgroundColor3 = Color3.fromRGB(138, 43, 226)
mainframe.BorderColor3 = Color3.fromRGB(255, 255, 255)
mainframe.BorderSizePixel = 0
mainframe.Position = UDim2.new(0.202159837, 0, 0.372229487, 0)
mainframe.Size = UDim2.new(0, 400, 0, 280)
mainframe.Visible = false
 
Minimise.Name = "Minimise"
Minimise.Parent = mainframe
Minimise.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Minimise.BorderColor3 = Color3.fromRGB(128, 39, 211)
Minimise.BorderSizePixel = 0
Minimise.Position = UDim2.new(0.800000012, 0, 0, 0)
Minimise.Size = UDim2.new(0, 40, 0, 40)
Minimise.Font = Enum.Font.SourceSans
Minimise.Text = "-"
Minimise.TextColor3 = Color3.fromRGB(255, 255, 255)
Minimise.TextSize = 35.000
Minimise.TextWrapped = true
Minimise.MouseButton1Down:connect(function()
openbutton.Visible = true
mainframe.Visible = false
end)
 
Close.Name = "Close"
Close.Parent = mainframe
Close.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Close.BorderColor3 = Color3.fromRGB(128, 39, 211)
Close.BorderSizePixel = 0
Close.Position = UDim2.new(0.899469852, 0, 0, 0)
Close.Size = UDim2.new(0, 40, 0, 40)
Close.Font = Enum.Font.SourceSans
Close.Text = "X"
Close.TextColor3 = Color3.fromRGB(255, 255, 255)
Close.TextSize = 35.000
Close.TextWrapped = true
Close.MouseButton1Down:connect(function()
shiroshubv2:Destroy()
end)
 
openbutton.Name = "openbutton"
openbutton.Parent = shiroshubv2
openbutton.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
openbutton.BorderColor3 = Color3.fromRGB(138, 43, 226)
openbutton.BorderSizePixel = 0
openbutton.Position = UDim2.new(0.850947857, 0, 0.935937285, 0)
openbutton.Size = UDim2.new(0, 100, 0, 30)
openbutton.Font = Enum.Font.SourceSans
openbutton.Text = "Open"
openbutton.TextColor3 = Color3.fromRGB(255, 255, 255)
openbutton.TextSize = 32.000
openbutton.MouseButton1Down:connect(function()
mainframe.Visible = true
openbutton.Visible = false
end)
 
Dupe.Name = "Dupe"
Dupe.Parent = mainframe
Dupe.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Dupe.BorderColor3 = Color3.fromRGB(138, 43, 226)
Dupe.BorderSizePixel = 0
Dupe.Position = UDim2.new(0, 0, 0.42899999, 0)
Dupe.Size = UDim2.new(0, 80, 0, 40)
Dupe.Font = Enum.Font.SourceSans
Dupe.Text = "Dupe"
Dupe.TextColor3 = Color3.fromRGB(255, 255, 255)
Dupe.TextScaled = true
Dupe.TextSize = 32.000
Dupe.TextWrapped = true
Dupe.MouseButton1Down:connect(function()
CreditsFrame.Visible = false
DupeFrame.Visible = true
HubFrame.Visible = false
MainFrame.Visible = false
PlotFrame.Visible = false
TPFrame.Visible = false
WoodFrame.Visible = false
end)
 
DupeFrame.Name = "DupeFrame"
DupeFrame.Parent = Dupe
DupeFrame.BackgroundColor3 = Color3.fromRGB(138, 43, 226)
DupeFrame.BorderSizePixel = 0
DupeFrame.Position = UDim2.new(1, 0, -2.00299978, 0)
DupeFrame.Size = UDim2.new(0, 320, 0, 240)
DupeFrame.Visible = false
 
StoreAxes.Name = "StoreAxes"
StoreAxes.Parent = DupeFrame
StoreAxes.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
StoreAxes.BorderSizePixel = 0
StoreAxes.Position = UDim2.new(0.675000012, 0, 0.26699999, 0)
StoreAxes.Size = UDim2.new(0, 98, 0, 52)
StoreAxes.Font = Enum.Font.SourceSans
StoreAxes.Text = "Store Axes"
StoreAxes.TextColor3 = Color3.fromRGB(255, 255, 255)
StoreAxes.TextScaled = true
StoreAxes.TextSize = 14.000
StoreAxes.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
StoreAxes.TextWrapped = true
 
CountAxes.Name = "CountAxes"
CountAxes.Parent = DupeFrame
CountAxes.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
CountAxes.BorderSizePixel = 0
CountAxes.Position = UDim2.new(0.675000012, 0, 0.754500031, 0)
CountAxes.Size = UDim2.new(0, 98, 0, 52)
CountAxes.Font = Enum.Font.SourceSans
CountAxes.Text = "Count Axes"
CountAxes.TextColor3 = Color3.fromRGB(255, 255, 255)
CountAxes.TextScaled = true
CountAxes.TextSize = 14.000
CountAxes.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
CountAxes.TextWrapped = true
 
RestoreAxes.Name = "RestoreAxes"
RestoreAxes.Parent = DupeFrame
RestoreAxes.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
RestoreAxes.BorderSizePixel = 0
RestoreAxes.Position = UDim2.new(0.675000012, 0, 0.513000011, 0)
RestoreAxes.Size = UDim2.new(0, 98, 0, 52)
RestoreAxes.Font = Enum.Font.SourceSans
RestoreAxes.Text = "Restore Axes"
RestoreAxes.TextColor3 = Color3.fromRGB(255, 255, 255)
RestoreAxes.TextScaled = true
RestoreAxes.TextSize = 14.000
RestoreAxes.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
RestoreAxes.TextWrapped = true
 
DupeSlot.Name = "DupeSlot"
DupeSlot.Parent = DupeFrame
DupeSlot.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
DupeSlot.BorderSizePixel = 0
DupeSlot.Position = UDim2.new(0.0199999809, 0, 0.266666681, 0)
DupeSlot.Size = UDim2.new(0, 98, 0, 52)
DupeSlot.Font = Enum.Font.SourceSans
DupeSlot.PlaceholderColor3 = Color3.fromRGB(255, 255, 255)
DupeSlot.PlaceholderText = "Slot?"
DupeSlot.Text = ""
DupeSlot.TextColor3 = Color3.fromRGB(255, 255, 255)
DupeSlot.TextScaled = true
DupeSlot.TextSize = 14.000
DupeSlot.TextWrapped = true
 
MoneyDupeSlot.Name = "MoneyDupeSlot"
MoneyDupeSlot.Parent = DupeFrame
MoneyDupeSlot.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
MoneyDupeSlot.BorderSizePixel = 0
MoneyDupeSlot.Position = UDim2.new(0.347000003, 0, 0.26699999, 0)
MoneyDupeSlot.Size = UDim2.new(0, 98, 0, 52)
MoneyDupeSlot.Font = Enum.Font.SourceSans
MoneyDupeSlot.PlaceholderColor3 = Color3.fromRGB(255, 255, 255)
MoneyDupeSlot.PlaceholderText = "Slot?"
MoneyDupeSlot.Text = ""
MoneyDupeSlot.TextColor3 = Color3.fromRGB(255, 255, 255)
MoneyDupeSlot.TextScaled = true
MoneyDupeSlot.TextSize = 14.000
MoneyDupeSlot.TextWrapped = true
 
MoneyDupe.Name = "MoneyDupe"
MoneyDupe.Parent = DupeFrame
MoneyDupe.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
MoneyDupe.BorderSizePixel = 0
MoneyDupe.Position = UDim2.new(0.347000003, 0, 0.0250000004, 0)
MoneyDupe.Size = UDim2.new(0, 98, 0, 52)
MoneyDupe.Font = Enum.Font.SourceSans
MoneyDupe.Text = "Money Dupe"
MoneyDupe.TextColor3 = Color3.fromRGB(255, 255, 255)
MoneyDupe.TextScaled = true
MoneyDupe.TextSize = 14.000
MoneyDupe.TextWrapped = true
 
AxeDupe.Name = "AxeDupe"
AxeDupe.Parent = DupeFrame
AxeDupe.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
AxeDupe.BorderSizePixel = 0
AxeDupe.Position = UDim2.new(0.675000012, 0, 0.0250000004, 0)
AxeDupe.Size = UDim2.new(0, 98, 0, 52)
AxeDupe.Font = Enum.Font.SourceSans
AxeDupe.Text = "Axe Dupe"
AxeDupe.TextColor3 = Color3.fromRGB(255, 255, 255)
AxeDupe.TextScaled = true
AxeDupe.TextSize = 14.000
AxeDupe.TextWrapped = true
 
Dupe_2.Name = "Dupe"
Dupe_2.Parent = DupeFrame
Dupe_2.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Dupe_2.BorderSizePixel = 0
Dupe_2.Position = UDim2.new(0.0199999996, 0, 0.0250000004, 0)
Dupe_2.Size = UDim2.new(0, 98, 0, 52)
Dupe_2.Font = Enum.Font.SourceSans
Dupe_2.Text = "Dupe"
Dupe_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Dupe_2.TextScaled = true
Dupe_2.TextSize = 14.000
Dupe_2.TextWrapped = true
 
MoneyStep1.Name = "MoneyStep1"
MoneyStep1.Parent = DupeFrame
MoneyStep1.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
MoneyStep1.BorderSizePixel = 0
MoneyStep1.Position = UDim2.new(0.346875012, 0, 0.513000011, 0)
MoneyStep1.Size = UDim2.new(0, 98, 0, 52)
MoneyStep1.Font = Enum.Font.SourceSans
MoneyStep1.Text = "Step 1"
MoneyStep1.TextColor3 = Color3.fromRGB(255, 255, 255)
MoneyStep1.TextScaled = true
MoneyStep1.TextSize = 14.000
MoneyStep1.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
MoneyStep1.TextWrapped = true
 
MoneyStep2.Name = "MoneyStep2"
MoneyStep2.Parent = DupeFrame
MoneyStep2.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
MoneyStep2.BorderSizePixel = 0
MoneyStep2.Position = UDim2.new(0.347000003, 0, 0.754999995, 0)
MoneyStep2.Size = UDim2.new(0, 98, 0, 52)
MoneyStep2.Font = Enum.Font.SourceSans
MoneyStep2.Text = "Step 2"
MoneyStep2.TextColor3 = Color3.fromRGB(255, 255, 255)
MoneyStep2.TextScaled = true
MoneyStep2.TextSize = 14.000
MoneyStep2.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
MoneyStep2.TextWrapped = true
 
DupeStep2.Name = "DupeStep2"
DupeStep2.Parent = DupeFrame
DupeStep2.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
DupeStep2.BorderSizePixel = 0
DupeStep2.Position = UDim2.new(0.0199999996, 0, 0.754999995, 0)
DupeStep2.Size = UDim2.new(0, 98, 0, 52)
DupeStep2.Font = Enum.Font.SourceSans
DupeStep2.Text = "Step 2"
DupeStep2.TextColor3 = Color3.fromRGB(255, 255, 255)
DupeStep2.TextScaled = true
DupeStep2.TextSize = 14.000
DupeStep2.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
DupeStep2.TextWrapped = true
 
DupeStep1.Name = "DupeStep1"
DupeStep1.Parent = DupeFrame
DupeStep1.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
DupeStep1.BorderSizePixel = 0
DupeStep1.Position = UDim2.new(0.0199999996, 0, 0.513000011, 0)
DupeStep1.Size = UDim2.new(0, 98, 0, 52)
DupeStep1.Font = Enum.Font.SourceSans
DupeStep1.Text = "Step 1"
DupeStep1.TextColor3 = Color3.fromRGB(255, 255, 255)
DupeStep1.TextScaled = true
DupeStep1.TextSize = 14.000
DupeStep1.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
DupeStep1.TextWrapped = true
 
Main.Name = "Main"
Main.Parent = mainframe
Main.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Main.BorderColor3 = Color3.fromRGB(138, 43, 226)
Main.BorderSizePixel = 0
Main.Size = UDim2.new(0, 80, 0, 40)
Main.Font = Enum.Font.SourceSans
Main.Text = "Main"
Main.TextColor3 = Color3.fromRGB(255, 255, 255)
Main.TextScaled = true
Main.TextSize = 32.000
Main.TextWrapped = true
Main.MouseButton1Down:connect(function()
CreditsFrame.Visible = false
DupeFrame.Visible = false
HubFrame.Visible = false
MainFrame.Visible = true
PlotFrame.Visible = false
TPFrame.Visible = false
WoodFrame.Visible = false
end)
 
MainFrame.Name = "MainFrame"
MainFrame.Parent = Main
MainFrame.BackgroundColor3 = Color3.fromRGB(138, 43, 226)
MainFrame.BorderSizePixel = 0
MainFrame.Position = UDim2.new(1, 0, 1, 0)
MainFrame.Size = UDim2.new(0, 320, 0, 240)
MainFrame.Visible = false
 
Speed.Name = "Speed"
Speed.Parent = MainFrame
Speed.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Speed.BorderSizePixel = 0
Speed.Position = UDim2.new(0.0199999809, 0, 0.0250000004, 0)
Speed.Size = UDim2.new(0, 76, 0, 52)
Speed.Font = Enum.Font.SourceSans
Speed.Text = "Speed"
Speed.TextColor3 = Color3.fromRGB(255, 255, 255)
Speed.TextScaled = true
Speed.TextSize = 14.000
Speed.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Speed.TextWrapped = true
 
Fly.Name = "Fly"
Fly.Parent = MainFrame
Fly.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Fly.BorderSizePixel = 0
Fly.Position = UDim2.new(0.0199999996, 0, 0.270000011, 0)
Fly.Size = UDim2.new(0, 73, 0, 52)
Fly.Font = Enum.Font.SourceSans
Fly.Text = "Fly"
Fly.TextColor3 = Color3.fromRGB(255, 255, 255)
Fly.TextScaled = true
Fly.TextSize = 14.000
Fly.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Fly.TextWrapped = true
 
GoldenAxe.Name = "GoldenAxe"
GoldenAxe.Parent = MainFrame
GoldenAxe.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
GoldenAxe.BorderSizePixel = 0
GoldenAxe.Position = UDim2.new(0.0199999996, 0, 0.757499993, 0)
GoldenAxe.Size = UDim2.new(0, 73, 0, 52)
GoldenAxe.Font = Enum.Font.SourceSans
GoldenAxe.Text = "Golden Axe"
GoldenAxe.TextColor3 = Color3.fromRGB(255, 255, 255)
GoldenAxe.TextScaled = true
GoldenAxe.TextSize = 14.000
GoldenAxe.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
GoldenAxe.TextWrapped = true
 
TP.Name = "TP"
TP.Parent = MainFrame
TP.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
TP.BorderSizePixel = 0
TP.Position = UDim2.new(0.0199999996, 0, 0.514999986, 0)
TP.Size = UDim2.new(0, 73, 0, 52)
TP.Font = Enum.Font.SourceSans
TP.Text = "CtrlClickTP"
TP.TextColor3 = Color3.fromRGB(255, 255, 255)
TP.TextScaled = true
TP.TextSize = 14.000
TP.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
TP.TextWrapped = true
 
Paint.Name = "Paint"
Paint.Parent = MainFrame
Paint.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Paint.BorderSizePixel = 0
Paint.Position = UDim2.new(0.26699999, 0, 0.757000029, 0)
Paint.Size = UDim2.new(0, 73, 0, 52)
Paint.Font = Enum.Font.SourceSans
Paint.Text = "Paint"
Paint.TextColor3 = Color3.fromRGB(255, 255, 255)
Paint.TextScaled = true
Paint.TextSize = 14.000
Paint.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Paint.TextWrapped = true
 
AllBp.Name = "AllBp"
AllBp.Parent = MainFrame
AllBp.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
AllBp.BorderSizePixel = 0
AllBp.Position = UDim2.new(0.26699999, 0, 0.514999986, 0)
AllBp.Size = UDim2.new(0, 73, 0, 52)
AllBp.Font = Enum.Font.SourceSans
AllBp.Text = "All Bp's"
AllBp.TextColor3 = Color3.fromRGB(255, 255, 255)
AllBp.TextScaled = true
AllBp.TextSize = 14.000
AllBp.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
AllBp.TextWrapped = true
 
CarFlight.Name = "CarFlight"
CarFlight.Parent = MainFrame
CarFlight.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
CarFlight.BorderSizePixel = 0
CarFlight.Position = UDim2.new(0.266874999, 0, 0.269999981, 0)
CarFlight.Size = UDim2.new(0, 73, 0, 52)
CarFlight.Font = Enum.Font.SourceSans
CarFlight.Text = "Car Flight"
CarFlight.TextColor3 = Color3.fromRGB(255, 255, 255)
CarFlight.TextScaled = true
CarFlight.TextSize = 14.000
CarFlight.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
CarFlight.TextWrapped = true
 
NoFog.Name = "NoFog"
NoFog.Parent = MainFrame
NoFog.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
NoFog.BorderSizePixel = 0
NoFog.Position = UDim2.new(0.753000021, 0, 0.514999986, 0)
NoFog.Size = UDim2.new(0, 73, 0, 52)
NoFog.Font = Enum.Font.SourceSans
NoFog.Text = "No Fog"
NoFog.TextColor3 = Color3.fromRGB(255, 255, 255)
NoFog.TextScaled = true
NoFog.TextSize = 14.000
NoFog.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
NoFog.TextWrapped = true
 
ResetCharacter.Name = "ResetCharacter"
ResetCharacter.Parent = MainFrame
ResetCharacter.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
ResetCharacter.BorderSizePixel = 0
ResetCharacter.Position = UDim2.new(0.753000021, 0, 0.757000029, 0)
ResetCharacter.Size = UDim2.new(0, 73, 0, 52)
ResetCharacter.Font = Enum.Font.SourceSans
ResetCharacter.Text = "Reset Character"
ResetCharacter.TextColor3 = Color3.fromRGB(255, 255, 255)
ResetCharacter.TextScaled = true
ResetCharacter.TextSize = 14.000
ResetCharacter.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
ResetCharacter.TextWrapped = true
 
NoClip.Name = "NoClip"
NoClip.Parent = MainFrame
NoClip.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
NoClip.BorderSizePixel = 0
NoClip.Position = UDim2.new(0.753000021, 0, 0.270000011, 0)
NoClip.Size = UDim2.new(0, 73, 0, 52)
NoClip.Font = Enum.Font.SourceSans
NoClip.Text = "No Clip"
NoClip.TextColor3 = Color3.fromRGB(255, 255, 255)
NoClip.TextScaled = true
NoClip.TextSize = 14.000
NoClip.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
NoClip.TextWrapped = true
 
InfJump.Name = "InfJump"
InfJump.Parent = MainFrame
InfJump.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
InfJump.BorderSizePixel = 0
InfJump.Position = UDim2.new(0.504999995, 0, 0.270000011, 0)
InfJump.Size = UDim2.new(0, 73, 0, 52)
InfJump.Font = Enum.Font.SourceSans
InfJump.Text = "Infinite Jump"
InfJump.TextColor3 = Color3.fromRGB(255, 255, 255)
InfJump.TextScaled = true
InfJump.TextSize = 14.000
InfJump.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
InfJump.TextWrapped = true
 
jesus.Name = "jesus"
jesus.Parent = MainFrame
jesus.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
jesus.BorderSizePixel = 0
jesus.Position = UDim2.new(0.504999995, 0, 0.514999986, 0)
jesus.Size = UDim2.new(0, 73, 0, 52)
jesus.Font = Enum.Font.SourceSans
jesus.Text = "Jesus"
jesus.TextColor3 = Color3.fromRGB(255, 255, 255)
jesus.TextScaled = true
jesus.TextSize = 14.000
jesus.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
jesus.TextWrapped = true
 
FastDelBps.Name = "FastDelBps"
FastDelBps.Parent = MainFrame
FastDelBps.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
FastDelBps.BorderSizePixel = 0
FastDelBps.Position = UDim2.new(0.504999995, 0, 0.757000029, 0)
FastDelBps.Size = UDim2.new(0, 73, 0, 52)
FastDelBps.Font = Enum.Font.SourceSans
FastDelBps.Text = "FastDelBps"
FastDelBps.TextColor3 = Color3.fromRGB(255, 255, 255)
FastDelBps.TextScaled = true
FastDelBps.TextSize = 14.000
FastDelBps.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
FastDelBps.TextWrapped = true
 
Jump.Name = "Jump"
Jump.Parent = MainFrame
Jump.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Jump.BorderSizePixel = 0
Jump.Position = UDim2.new(0.504999995, 0, 0.0250000004, 0)
Jump.Size = UDim2.new(0, 76, 0, 52)
Jump.Font = Enum.Font.SourceSans
Jump.Text = "Jump"
Jump.TextColor3 = Color3.fromRGB(255, 255, 255)
Jump.TextScaled = true
Jump.TextSize = 14.000
Jump.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Jump.TextWrapped = true
 
SpeedValue.Name = "SpeedValue"
SpeedValue.Parent = MainFrame
SpeedValue.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
SpeedValue.BorderSizePixel = 0
SpeedValue.Position = UDim2.new(0.257499993, 0, 0.0250000004, 0)
SpeedValue.Size = UDim2.new(0, 76, 0, 52)
SpeedValue.Font = Enum.Font.SourceSans
SpeedValue.PlaceholderColor3 = Color3.fromRGB(255, 255, 255)
SpeedValue.PlaceholderText = "16"
SpeedValue.Text = ""
SpeedValue.TextColor3 = Color3.fromRGB(255, 255, 255)
SpeedValue.TextScaled = true
SpeedValue.TextSize = 14.000
SpeedValue.TextWrapped = true
 
JumpValue.Name = "JumpValue"
JumpValue.Parent = MainFrame
JumpValue.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
JumpValue.BorderSizePixel = 0
JumpValue.Position = UDim2.new(0.742500007, 0, 0.0250000004, 0)
JumpValue.Size = UDim2.new(0, 76, 0, 52)
JumpValue.Font = Enum.Font.SourceSans
JumpValue.PlaceholderColor3 = Color3.fromRGB(255, 255, 255)
JumpValue.PlaceholderText = "50"
JumpValue.Text = ""
JumpValue.TextColor3 = Color3.fromRGB(255, 255, 255)
JumpValue.TextScaled = true
JumpValue.TextSize = 14.000
JumpValue.TextWrapped = true
 
SecretWalkSpeed.Name = "SecretWalkSpeed"
SecretWalkSpeed.Parent = MainFrame
SecretWalkSpeed.BackgroundColor3 = Color3.fromRGB(138, 43, 226)
SecretWalkSpeed.BorderSizePixel = 0
SecretWalkSpeed.Size = UDim2.new(0, 6, 0, 6)
SecretWalkSpeed.AutoButtonColor = false
SecretWalkSpeed.Font = Enum.Font.SourceSans
SecretWalkSpeed.Text = ""
SecretWalkSpeed.TextColor3 = Color3.fromRGB(255, 255, 255)
SecretWalkSpeed.TextScaled = true
SecretWalkSpeed.TextSize = 14.000
SecretWalkSpeed.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
SecretWalkSpeed.TextWrapped = true
 
Plot.Name = "Plot"
Plot.Parent = mainframe
Plot.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Plot.BorderColor3 = Color3.fromRGB(138, 43, 226)
Plot.BorderSizePixel = 0
Plot.Position = UDim2.new(0, 0, 0.572000027, 0)
Plot.Size = UDim2.new(0, 80, 0, 40)
Plot.Font = Enum.Font.SourceSans
Plot.Text = "Plot"
Plot.TextColor3 = Color3.fromRGB(255, 255, 255)
Plot.TextScaled = true
Plot.TextSize = 32.000
Plot.TextWrapped = true
Plot.MouseButton1Down:connect(function()
CreditsFrame.Visible = false
DupeFrame.Visible = false
HubFrame.Visible = false
MainFrame.Visible = false
PlotFrame.Visible = true
TPFrame.Visible = false
WoodFrame.Visible = false
end)
 
PlotFrame.Name = "PlotFrame"
PlotFrame.Parent = Plot
PlotFrame.BackgroundColor3 = Color3.fromRGB(138, 43, 226)
PlotFrame.BorderSizePixel = 0
PlotFrame.Position = UDim2.new(1, 0, -3.00299978, 0)
PlotFrame.Size = UDim2.new(0, 320, 0, 240)
PlotFrame.Visible = false
 
BlackListAll.Name = "BlackList All"
BlackListAll.Parent = PlotFrame
BlackListAll.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
BlackListAll.BorderSizePixel = 0
BlackListAll.Position = UDim2.new(0.0199999996, 0, 0.754999995, 0)
BlackListAll.Size = UDim2.new(0, 151, 0, 52)
BlackListAll.Font = Enum.Font.SourceSans
BlackListAll.Text = "Blacklist All"
BlackListAll.TextColor3 = Color3.fromRGB(255, 255, 255)
BlackListAll.TextScaled = true
BlackListAll.TextSize = 14.000
BlackListAll.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
BlackListAll.TextWrapped = true
 
MaxLand.Name = "MaxLand"
MaxLand.Parent = PlotFrame
MaxLand.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
MaxLand.BorderSizePixel = 0
MaxLand.Position = UDim2.new(0.0199999996, 0, 0.270000011, 0)
MaxLand.Size = UDim2.new(0, 151, 0, 52)
MaxLand.Font = Enum.Font.SourceSans
MaxLand.Text = "Max Land"
MaxLand.TextColor3 = Color3.fromRGB(255, 255, 255)
MaxLand.TextScaled = true
MaxLand.TextSize = 14.000
MaxLand.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
MaxLand.TextWrapped = true
 
WipeBase.Name = "WipeBase"
WipeBase.Parent = PlotFrame
WipeBase.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
WipeBase.BorderSizePixel = 0
WipeBase.Position = UDim2.new(0.0199999996, 0, 0.514999986, 0)
WipeBase.Size = UDim2.new(0, 151, 0, 52)
WipeBase.Font = Enum.Font.SourceSans
WipeBase.Text = "Wipe Base"
WipeBase.TextColor3 = Color3.fromRGB(255, 255, 255)
WipeBase.TextScaled = true
WipeBase.TextSize = 14.000
WipeBase.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
WipeBase.TextWrapped = true
 
AntiBLAll.Name = "AntiBLAll"
AntiBLAll.Parent = PlotFrame
AntiBLAll.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
AntiBLAll.BorderSizePixel = 0
AntiBLAll.Position = UDim2.new(0.508000016, 0, 0.754999995, 0)
AntiBLAll.Size = UDim2.new(0, 151, 0, 52)
AntiBLAll.Font = Enum.Font.SourceSans
AntiBLAll.Text = "Anti Blacklist All"
AntiBLAll.TextColor3 = Color3.fromRGB(255, 255, 255)
AntiBLAll.TextScaled = true
AntiBLAll.TextSize = 14.000
AntiBLAll.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
AntiBLAll.TextWrapped = true
 
CopyBase.Name = "CopyBase"
CopyBase.Parent = PlotFrame
CopyBase.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
CopyBase.BorderSizePixel = 0
CopyBase.Position = UDim2.new(0.508000016, 0, 0.514999986, 0)
CopyBase.Size = UDim2.new(0, 151, 0, 52)
CopyBase.Font = Enum.Font.SourceSans
CopyBase.Text = "Copy Base"
CopyBase.TextColor3 = Color3.fromRGB(255, 255, 255)
CopyBase.TextScaled = true
CopyBase.TextSize = 14.000
CopyBase.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
CopyBase.TextWrapped = true
 
PlayerName.Name = "PlayerName"
PlayerName.Parent = PlotFrame
PlayerName.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
PlayerName.BorderSizePixel = 0
PlayerName.Position = UDim2.new(0.508000016, 0, 0.270000011, 0)
PlayerName.Size = UDim2.new(0, 151, 0, 52)
PlayerName.Font = Enum.Font.SourceSans
PlayerName.PlaceholderColor3 = Color3.fromRGB(255, 255, 255)
PlayerName.PlaceholderText = "Player Name?"
PlayerName.Text = ""
PlayerName.TextColor3 = Color3.fromRGB(255, 255, 255)
PlayerName.TextScaled = true
PlayerName.TextSize = 14.000
PlayerName.TextWrapped = true
 
You.Name = "You"
You.Parent = PlotFrame
You.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
You.BorderSizePixel = 0
You.Position = UDim2.new(0.0199999996, 0, 0.0250000004, 0)
You.Size = UDim2.new(0, 151, 0, 52)
You.Font = Enum.Font.SourceSans
You.Text = "You"
You.TextColor3 = Color3.fromRGB(255, 255, 255)
You.TextScaled = true
You.TextSize = 14.000
You.TextWrapped = true
 
Others.Name = "Others"
Others.Parent = PlotFrame
Others.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Others.BorderSizePixel = 0
Others.Position = UDim2.new(0.508000016, 0, 0.0250000004, 0)
Others.Size = UDim2.new(0, 151, 0, 52)
Others.Font = Enum.Font.SourceSans
Others.Text = "Others"
Others.TextColor3 = Color3.fromRGB(255, 255, 255)
Others.TextScaled = true
Others.TextSize = 14.000
Others.TextWrapped = true
 
Wood.Name = "Wood"
Wood.Parent = mainframe
Wood.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Wood.BorderColor3 = Color3.fromRGB(138, 43, 226)
Wood.BorderSizePixel = 0
Wood.Position = UDim2.new(0, 0, 0.143000007, 0)
Wood.Size = UDim2.new(0, 80, 0, 40)
Wood.Font = Enum.Font.SourceSans
Wood.Text = "Wood"
Wood.TextColor3 = Color3.fromRGB(255, 255, 255)
Wood.TextScaled = true
Wood.TextSize = 32.000
Wood.TextWrapped = true
Wood.MouseButton1Down:connect(function()
CreditsFrame.Visible = false
DupeFrame.Visible = false
HubFrame.Visible = false
MainFrame.Visible = false
PlotFrame.Visible = false
TPFrame.Visible = false
WoodFrame.Visible = true
end)
 
WoodFrame.Name = "WoodFrame"
WoodFrame.Parent = Wood
WoodFrame.BackgroundColor3 = Color3.fromRGB(138, 43, 226)
WoodFrame.BorderSizePixel = 0
WoodFrame.Position = UDim2.new(1, 0, -0.00100021367, 0)
WoodFrame.Size = UDim2.new(0, 320, 0, 240)
WoodFrame.Visible = false
 
SellWood.Name = "SellWood"
SellWood.Parent = WoodFrame
SellWood.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
SellWood.BorderSizePixel = 0
SellWood.Position = UDim2.new(0.0199999809, 0, 0.0250000004, 0)
SellWood.Size = UDim2.new(0, 151, 0, 72)
SellWood.Font = Enum.Font.SourceSans
SellWood.Text = "Sell Wood"
SellWood.TextColor3 = Color3.fromRGB(255, 255, 255)
SellWood.TextScaled = true
SellWood.TextSize = 14.000
SellWood.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
SellWood.TextWrapped = true
 
SellPlanks.Name = "SellPlanks"
SellPlanks.Parent = WoodFrame
SellPlanks.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
SellPlanks.BorderSizePixel = 0
SellPlanks.Position = UDim2.new(0.508000016, 0, 0.0250000004, 0)
SellPlanks.Size = UDim2.new(0, 151, 0, 72)
SellPlanks.Font = Enum.Font.SourceSans
SellPlanks.Text = "Sell Planks"
SellPlanks.TextColor3 = Color3.fromRGB(255, 255, 255)
SellPlanks.TextScaled = true
SellPlanks.TextSize = 14.000
SellPlanks.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
SellPlanks.TextWrapped = true
 
ModWood.Name = "ModWood"
ModWood.Parent = WoodFrame
ModWood.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
ModWood.BorderSizePixel = 0
ModWood.Position = UDim2.new(0.0199999996, 0, 0.675000012, 0)
ModWood.Size = UDim2.new(0, 151, 0, 72)
ModWood.Font = Enum.Font.SourceSans
ModWood.Text = "Mod Wood"
ModWood.TextColor3 = Color3.fromRGB(255, 255, 255)
ModWood.TextScaled = true
ModWood.TextSize = 14.000
ModWood.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
ModWood.TextWrapped = true
 
TPWood.Name = "TPWood"
TPWood.Parent = WoodFrame
TPWood.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
TPWood.BorderSizePixel = 0
TPWood.Position = UDim2.new(0.0199999996, 0, 0.350000024, 0)
TPWood.Size = UDim2.new(0, 151, 0, 72)
TPWood.Font = Enum.Font.SourceSans
TPWood.Text = "TP Wood"
TPWood.TextColor3 = Color3.fromRGB(255, 255, 255)
TPWood.TextScaled = true
TPWood.TextSize = 14.000
TPWood.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
TPWood.TextWrapped = true
 
TPPlanks.Name = "TPPlanks"
TPPlanks.Parent = WoodFrame
TPPlanks.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
TPPlanks.BorderSizePixel = 0
TPPlanks.Position = UDim2.new(0.508000016, 0, 0.349999994, 0)
TPPlanks.Size = UDim2.new(0, 151, 0, 72)
TPPlanks.Font = Enum.Font.SourceSans
TPPlanks.Text = "TP Planks"
TPPlanks.TextColor3 = Color3.fromRGB(255, 255, 255)
TPPlanks.TextScaled = true
TPPlanks.TextSize = 14.000
TPPlanks.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
TPPlanks.TextWrapped = true
 
RemoveTrees.Name = "RemoveTrees"
RemoveTrees.Parent = WoodFrame
RemoveTrees.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
RemoveTrees.BorderSizePixel = 0
RemoveTrees.Position = UDim2.new(0.508000016, 0, 0.675000012, 0)
RemoveTrees.Size = UDim2.new(0, 151, 0, 72)
RemoveTrees.Font = Enum.Font.SourceSans
RemoveTrees.Text = "Remove Trees"
RemoveTrees.TextColor3 = Color3.fromRGB(255, 255, 255)
RemoveTrees.TextScaled = true
RemoveTrees.TextSize = 14.000
RemoveTrees.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
RemoveTrees.TextWrapped = true
 
TP_2.Name = "TP"
TP_2.Parent = mainframe
TP_2.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
TP_2.BorderColor3 = Color3.fromRGB(138, 43, 226)
TP_2.BorderSizePixel = 0
TP_2.Position = UDim2.new(0, 0, 0.286000013, 0)
TP_2.Size = UDim2.new(0, 80, 0, 40)
TP_2.Font = Enum.Font.SourceSans
TP_2.Text = "TP"
TP_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TP_2.TextScaled = true
TP_2.TextSize = 32.000
TP_2.TextWrapped = true
TP_2.MouseButton1Down:connect(function()
CreditsFrame.Visible = false
DupeFrame.Visible = false
HubFrame.Visible = false
MainFrame.Visible = false
PlotFrame.Visible = false
TPFrame.Visible = true
WoodFrame.Visible = false
end)
 
TPFrame.Name = "TPFrame"
TPFrame.Parent = TP_2
TPFrame.BackgroundColor3 = Color3.fromRGB(138, 43, 226)
TPFrame.BorderSizePixel = 0
TPFrame.Position = UDim2.new(1, 0, -1.00200045, 0)
TPFrame.Size = UDim2.new(0, 320, 0, 240)
TPFrame.Visible = false
 
StoreWoodRUs.Name = "StoreWoodRUs"
StoreWoodRUs.Parent = TPFrame
StoreWoodRUs.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
StoreWoodRUs.BorderSizePixel = 0
StoreWoodRUs.Position = UDim2.new(0.0199999809, 0, 0.0250000004, 0)
StoreWoodRUs.Size = UDim2.new(0, 73, 0, 40)
StoreWoodRUs.Font = Enum.Font.SourceSans
StoreWoodRUs.Text = "WoodRUs"
StoreWoodRUs.TextColor3 = Color3.fromRGB(255, 255, 255)
StoreWoodRUs.TextScaled = true
StoreWoodRUs.TextSize = 14.000
StoreWoodRUs.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
StoreWoodRUs.TextWrapped = true
 
StoreLand.Name = "StoreLand"
StoreLand.Parent = TPFrame
StoreLand.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
StoreLand.BorderSizePixel = 0
StoreLand.Position = UDim2.new(0.0199999809, 0, 0.216666669, 0)
StoreLand.Size = UDim2.new(0, 73, 0, 40)
StoreLand.Font = Enum.Font.SourceSans
StoreLand.Text = "Land Store"
StoreLand.TextColor3 = Color3.fromRGB(255, 255, 255)
StoreLand.TextScaled = true
StoreLand.TextSize = 14.000
StoreLand.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
StoreLand.TextWrapped = true
 
StoreCars.Name = "StoreCars"
StoreCars.Parent = TPFrame
StoreCars.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
StoreCars.BorderSizePixel = 0
StoreCars.Position = UDim2.new(0.0199999996, 0, 0.415833324, 0)
StoreCars.Size = UDim2.new(0, 73, 0, 40)
StoreCars.Font = Enum.Font.SourceSans
StoreCars.Text = "Boxed Cars"
StoreCars.TextColor3 = Color3.fromRGB(255, 255, 255)
StoreCars.TextScaled = true
StoreCars.TextSize = 14.000
StoreCars.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
StoreCars.TextWrapped = true
 
GreenBox.Name = "GreenBox"
GreenBox.Parent = TPFrame
GreenBox.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
GreenBox.BorderSizePixel = 0
GreenBox.Position = UDim2.new(0.0199999996, 0, 0.80583334, 0)
GreenBox.Size = UDim2.new(0, 73, 0, 40)
GreenBox.Font = Enum.Font.SourceSans
GreenBox.Text = "Green Box"
GreenBox.TextColor3 = Color3.fromRGB(255, 255, 255)
GreenBox.TextScaled = true
GreenBox.TextSize = 14.000
GreenBox.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
GreenBox.TextWrapped = true
 
StoreFancy.Name = "StoreFancy"
StoreFancy.Parent = TPFrame
StoreFancy.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
StoreFancy.BorderSizePixel = 0
StoreFancy.Position = UDim2.new(0.0199999996, 0, 0.614166677, 0)
StoreFancy.Size = UDim2.new(0, 73, 0, 40)
StoreFancy.Font = Enum.Font.SourceSans
StoreFancy.Text = "Fancy Furnishings"
StoreFancy.TextColor3 = Color3.fromRGB(255, 255, 255)
StoreFancy.TextScaled = true
StoreFancy.TextSize = 14.000
StoreFancy.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
StoreFancy.TextWrapped = true
 
StoreLogic.Name = "StoreLogic"
StoreLogic.Parent = TPFrame
StoreLogic.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
StoreLogic.BorderSizePixel = 0
StoreLogic.Position = UDim2.new(0.26699999, 0, 0.0250000004, 0)
StoreLogic.Size = UDim2.new(0, 73, 0, 40)
StoreLogic.Font = Enum.Font.SourceSans
StoreLogic.Text = "Link's Logic"
StoreLogic.TextColor3 = Color3.fromRGB(255, 255, 255)
StoreLogic.TextScaled = true
StoreLogic.TextSize = 14.000
StoreLogic.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
StoreLogic.TextWrapped = true
 
Spawn.Name = "Spawn"
Spawn.Parent = TPFrame
Spawn.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Spawn.BorderSizePixel = 0
Spawn.Position = UDim2.new(0.504999995, 0, 0.0250000004, 0)
Spawn.Size = UDim2.new(0, 73, 0, 40)
Spawn.Font = Enum.Font.SourceSans
Spawn.Text = "Spawn"
Spawn.TextColor3 = Color3.fromRGB(255, 255, 255)
Spawn.TextScaled = true
Spawn.TextSize = 14.000
Spawn.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Spawn.TextWrapped = true
 
IceWood.Name = "IceWood"
IceWood.Parent = TPFrame
IceWood.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
IceWood.BorderSizePixel = 0
IceWood.Position = UDim2.new(0.753000021, 0, 0.0250000004, 0)
IceWood.Size = UDim2.new(0, 73, 0, 40)
IceWood.Font = Enum.Font.SourceSans
IceWood.Text = "Ice Wood"
IceWood.TextColor3 = Color3.fromRGB(255, 255, 255)
IceWood.TextScaled = true
IceWood.TextSize = 14.000
IceWood.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
IceWood.TextWrapped = true
 
Lodge.Name = "Lodge"
Lodge.Parent = TPFrame
Lodge.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Lodge.BorderSizePixel = 0
Lodge.Position = UDim2.new(0.26699999, 0, 0.805999994, 0)
Lodge.Size = UDim2.new(0, 73, 0, 40)
Lodge.Font = Enum.Font.SourceSans
Lodge.Text = "Lodge"
Lodge.TextColor3 = Color3.fromRGB(255, 255, 255)
Lodge.TextScaled = true
Lodge.TextSize = 14.000
Lodge.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Lodge.TextWrapped = true
 
Dock.Name = "Dock"
Dock.Parent = TPFrame
Dock.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Dock.BorderSizePixel = 0
Dock.Position = UDim2.new(0.504999995, 0, 0.805999994, 0)
Dock.Size = UDim2.new(0, 73, 0, 40)
Dock.Font = Enum.Font.SourceSans
Dock.Text = "Dock"
Dock.TextColor3 = Color3.fromRGB(255, 255, 255)
Dock.TextScaled = true
Dock.TextSize = 14.000
Dock.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Dock.TextWrapped = true
 
Bridge.Name = "Bridge"
Bridge.Parent = TPFrame
Bridge.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Bridge.BorderSizePixel = 0
Bridge.Position = UDim2.new(0.753000021, 0, 0.805999994, 0)
Bridge.Size = UDim2.new(0, 73, 0, 40)
Bridge.Font = Enum.Font.SourceSans
Bridge.Text = "Bridge"
Bridge.TextColor3 = Color3.fromRGB(255, 255, 255)
Bridge.TextScaled = true
Bridge.TextSize = 14.000
Bridge.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Bridge.TextWrapped = true
 
Cave.Name = "Cave"
Cave.Parent = TPFrame
Cave.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Cave.BorderSizePixel = 0
Cave.Position = UDim2.new(0.753000021, 0, 0.614000022, 0)
Cave.Size = UDim2.new(0, 73, 0, 40)
Cave.Font = Enum.Font.SourceSans
Cave.Text = "Cave"
Cave.TextColor3 = Color3.fromRGB(255, 255, 255)
Cave.TextScaled = true
Cave.TextSize = 14.000
Cave.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Cave.TextWrapped = true
 
StrangeMan.Name = "StrangeMan"
StrangeMan.Parent = TPFrame
StrangeMan.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
StrangeMan.BorderSizePixel = 0
StrangeMan.Position = UDim2.new(0.26699999, 0, 0.614000022, 0)
StrangeMan.Size = UDim2.new(0, 73, 0, 40)
StrangeMan.Font = Enum.Font.SourceSans
StrangeMan.Text = "Strange Man"
StrangeMan.TextColor3 = Color3.fromRGB(255, 255, 255)
StrangeMan.TextScaled = true
StrangeMan.TextSize = 14.000
StrangeMan.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
StrangeMan.TextWrapped = true
 
YellowWood.Name = "YellowWood"
YellowWood.Parent = TPFrame
YellowWood.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
YellowWood.BorderSizePixel = 0
YellowWood.Position = UDim2.new(0.504999995, 0, 0.614000022, 0)
YellowWood.Size = UDim2.new(0, 73, 0, 40)
YellowWood.Font = Enum.Font.SourceSans
YellowWood.Text = "Yellow Wood"
YellowWood.TextColor3 = Color3.fromRGB(255, 255, 255)
YellowWood.TextScaled = true
YellowWood.TextSize = 14.000
YellowWood.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
YellowWood.TextWrapped = true
 
Volcano.Name = "Volcano"
Volcano.Parent = TPFrame
Volcano.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Volcano.BorderSizePixel = 0
Volcano.Position = UDim2.new(0.504999995, 0, 0.216999993, 0)
Volcano.Size = UDim2.new(0, 73, 0, 40)
Volcano.Font = Enum.Font.SourceSans
Volcano.Text = "Volcano"
Volcano.TextColor3 = Color3.fromRGB(255, 255, 255)
Volcano.TextScaled = true
Volcano.TextSize = 14.000
Volcano.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Volcano.TextWrapped = true
 
Palm.Name = "Palm"
Palm.Parent = TPFrame
Palm.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Palm.BorderSizePixel = 0
Palm.Position = UDim2.new(0.753000021, 0, 0.216999993, 0)
Palm.Size = UDim2.new(0, 73, 0, 40)
Palm.Font = Enum.Font.SourceSans
Palm.Text = "Palm"
Palm.TextColor3 = Color3.fromRGB(255, 255, 255)
Palm.TextScaled = true
Palm.TextSize = 14.000
Palm.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Palm.TextWrapped = true
 
StoreBobs.Name = "StoreBobs"
StoreBobs.Parent = TPFrame
StoreBobs.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
StoreBobs.BorderSizePixel = 0
StoreBobs.Position = UDim2.new(0.26699999, 0, 0.416399986, 0)
StoreBobs.Size = UDim2.new(0, 73, 0, 40)
StoreBobs.Font = Enum.Font.SourceSans
StoreBobs.Text = "Bob's Shack"
StoreBobs.TextColor3 = Color3.fromRGB(255, 255, 255)
StoreBobs.TextScaled = true
StoreBobs.TextSize = 14.000
StoreBobs.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
StoreBobs.TextWrapped = true
 
EndTimes.Name = "EndTimes"
EndTimes.Parent = TPFrame
EndTimes.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
EndTimes.BorderSizePixel = 0
EndTimes.Position = UDim2.new(0.753000021, 0, 0.416000009, 0)
EndTimes.Size = UDim2.new(0, 73, 0, 40)
EndTimes.Font = Enum.Font.SourceSans
EndTimes.Text = "End Times"
EndTimes.TextColor3 = Color3.fromRGB(255, 255, 255)
EndTimes.TextScaled = true
EndTimes.TextSize = 14.000
EndTimes.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
EndTimes.TextWrapped = true
 
Swamp.Name = "Swamp"
Swamp.Parent = TPFrame
Swamp.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Swamp.BorderSizePixel = 0
Swamp.Position = UDim2.new(0.504999995, 0, 0.416000009, 0)
Swamp.Size = UDim2.new(0, 73, 0, 40)
Swamp.Font = Enum.Font.SourceSans
Swamp.Text = "Swamp"
Swamp.TextColor3 = Color3.fromRGB(255, 255, 255)
Swamp.TextScaled = true
Swamp.TextSize = 14.000
Swamp.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Swamp.TextWrapped = true
 
StoreFineArts.Name = "StoreFineArts"
StoreFineArts.Parent = TPFrame
StoreFineArts.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
StoreFineArts.BorderSizePixel = 0
StoreFineArts.Position = UDim2.new(0.26699999, 0, 0.216999993, 0)
StoreFineArts.Size = UDim2.new(0, 73, 0, 40)
StoreFineArts.Font = Enum.Font.SourceSans
StoreFineArts.Text = "Fine Arts"
StoreFineArts.TextColor3 = Color3.fromRGB(255, 255, 255)
StoreFineArts.TextScaled = true
StoreFineArts.TextSize = 14.000
StoreFineArts.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
StoreFineArts.TextWrapped = true
 
Hub.Name = "Hub"
Hub.Parent = mainframe
Hub.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Hub.BorderColor3 = Color3.fromRGB(138, 43, 226)
Hub.BorderSizePixel = 0
Hub.Position = UDim2.new(0, 0, 0.714999974, 0)
Hub.Size = UDim2.new(0, 80, 0, 40)
Hub.Font = Enum.Font.SourceSans
Hub.Text = "Hub's"
Hub.TextColor3 = Color3.fromRGB(255, 255, 255)
Hub.TextScaled = true
Hub.TextSize = 32.000
Hub.TextWrapped = true
Hub.MouseButton1Down:connect(function()
CreditsFrame.Visible = false
DupeFrame.Visible = false
HubFrame.Visible = true
MainFrame.Visible = false
PlotFrame.Visible = false
TPFrame.Visible = false
WoodFrame.Visible = false
end)
 
HubFrame.Name = "HubFrame"
HubFrame.Parent = Hub
HubFrame.BackgroundColor3 = Color3.fromRGB(138, 43, 226)
HubFrame.BorderSizePixel = 0
HubFrame.Position = UDim2.new(1, 0, -4.00400019, 0)
HubFrame.Size = UDim2.new(0, 320, 0, 240)
HubFrame.Visible = false
 
Blood.Name = "Blood"
Blood.Parent = HubFrame
Blood.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Blood.BorderSizePixel = 0
Blood.Position = UDim2.new(0.0199999809, 0, 0.0250000004, 0)
Blood.Size = UDim2.new(0, 151, 0, 72)
Blood.Font = Enum.Font.SourceSans
Blood.Text = "Blood"
Blood.TextColor3 = Color3.fromRGB(255, 255, 255)
Blood.TextScaled = true
Blood.TextSize = 14.000
Blood.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Blood.TextWrapped = true
 
Venyx.Name = "Venyx"
Venyx.Parent = HubFrame
Venyx.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Venyx.BorderSizePixel = 0
Venyx.Position = UDim2.new(0.508000016, 0, 0.0250000004, 0)
Venyx.Size = UDim2.new(0, 151, 0, 72)
Venyx.Font = Enum.Font.SourceSans
Venyx.Text = "Venyx"
Venyx.TextColor3 = Color3.fromRGB(255, 255, 255)
Venyx.TextScaled = true
Venyx.TextSize = 14.000
Venyx.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Venyx.TextWrapped = true
 
BringUp.Name = "Bring Up"
BringUp.Parent = HubFrame
BringUp.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
BringUp.BorderSizePixel = 0
BringUp.Position = UDim2.new(0.0199999996, 0, 0.675000012, 0)
BringUp.Size = UDim2.new(0, 151, 0, 72)
BringUp.Font = Enum.Font.SourceSans
BringUp.Text = "Bring Up"
BringUp.TextColor3 = Color3.fromRGB(255, 255, 255)
BringUp.TextScaled = true
BringUp.TextSize = 14.000
BringUp.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
BringUp.TextWrapped = true
 
LightLumber.Name = "Light Lumber"
LightLumber.Parent = HubFrame
LightLumber.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
LightLumber.BorderSizePixel = 0
LightLumber.Position = UDim2.new(0.0199999996, 0, 0.350000024, 0)
LightLumber.Size = UDim2.new(0, 151, 0, 72)
LightLumber.Font = Enum.Font.SourceSans
LightLumber.Text = "Light Lumber"
LightLumber.TextColor3 = Color3.fromRGB(255, 255, 255)
LightLumber.TextScaled = true
LightLumber.TextSize = 14.000
LightLumber.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
LightLumber.TextWrapped = true
 
Ferry.Name = "Ferry"
Ferry.Parent = HubFrame
Ferry.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Ferry.BorderSizePixel = 0
Ferry.Position = UDim2.new(0.508000016, 0, 0.675000012, 0)
Ferry.Size = UDim2.new(0, 151, 0, 72)
Ferry.Font = Enum.Font.SourceSans
Ferry.Text = "Ferry"
Ferry.TextColor3 = Color3.fromRGB(255, 255, 255)
Ferry.TextScaled = true
Ferry.TextSize = 14.000
Ferry.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Ferry.TextWrapped = true
 
JohiroAxeDupe.Name = "JohiroAxeDupe"
JohiroAxeDupe.Parent = HubFrame
JohiroAxeDupe.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
JohiroAxeDupe.BorderSizePixel = 0
JohiroAxeDupe.Position = UDim2.new(0.508000016, 0, 0.349999994, 0)
JohiroAxeDupe.Size = UDim2.new(0, 151, 0, 72)
JohiroAxeDupe.Font = Enum.Font.SourceSans
JohiroAxeDupe.Text = "Johiro's Axe Dupe"
JohiroAxeDupe.TextColor3 = Color3.fromRGB(255, 255, 255)
JohiroAxeDupe.TextScaled = true
JohiroAxeDupe.TextSize = 14.000
JohiroAxeDupe.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
JohiroAxeDupe.TextWrapped = true
 
Credits.Name = "Credits"
Credits.Parent = mainframe
Credits.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Credits.BorderColor3 = Color3.fromRGB(138, 43, 226)
Credits.BorderSizePixel = 0
Credits.Position = UDim2.new(0, 0, 0.85799998, 0)
Credits.Size = UDim2.new(0, 80, 0, 40)
Credits.Font = Enum.Font.SourceSans
Credits.Text = "Credits"
Credits.TextColor3 = Color3.fromRGB(255, 255, 255)
Credits.TextScaled = true
Credits.TextSize = 32.000
Credits.TextWrapped = true
Credits.MouseButton1Down:connect(function()
CreditsFrame.Visible = true
DupeFrame.Visible = false
HubFrame.Visible = false
MainFrame.Visible = false
PlotFrame.Visible = false
TPFrame.Visible = false
WoodFrame.Visible = false
end)
 
CreditsFrame.Name = "CreditsFrame"
CreditsFrame.Parent = Credits
CreditsFrame.BackgroundColor3 = Color3.fromRGB(138, 43, 226)
CreditsFrame.BorderSizePixel = 0
CreditsFrame.Position = UDim2.new(1, 0, -5.00599957, 0)
CreditsFrame.Size = UDim2.new(0, 320, 0, 240)
 
MadeBy.Name = "Made By"
MadeBy.Parent = CreditsFrame
MadeBy.BackgroundColor3 = Color3.fromRGB(138, 43, 226)
MadeBy.BackgroundTransparency = 100.000
MadeBy.BorderSizePixel = 0
MadeBy.Position = UDim2.new(0.159374997, 0, 0, 0)
MadeBy.Size = UDim2.new(0, 200, 0, 48)
MadeBy.Font = Enum.Font.GothamBold
MadeBy.Text = "Made By"
MadeBy.TextColor3 = Color3.fromRGB(255, 255, 255)
MadeBy.TextScaled = true
MadeBy.TextSize = 13.000
MadeBy.TextWrapped = true
 
SnowyShiro.Name = "SnowyShiro"
SnowyShiro.Parent = CreditsFrame
SnowyShiro.BackgroundColor3 = Color3.fromRGB(138, 43, 226)
SnowyShiro.BackgroundTransparency = 100.000
SnowyShiro.BorderSizePixel = 0
SnowyShiro.Position = UDim2.new(0, 0, 0.19600004, 0)
SnowyShiro.Size = UDim2.new(0, 320, 0, 48)
SnowyShiro.Font = Enum.Font.GothamBold
SnowyShiro.Text = "SnowyShiro#0001"
SnowyShiro.TextColor3 = Color3.fromRGB(255, 255, 255)
SnowyShiro.TextSize = 27.000
SnowyShiro.TextWrapped = true
 
Credits_2.Name = "Credits"
Credits_2.Parent = CreditsFrame
Credits_2.BackgroundColor3 = Color3.fromRGB(138, 43, 226)
Credits_2.BackgroundTransparency = 100.000
Credits_2.BorderSizePixel = 0
Credits_2.Position = UDim2.new(0.159374997, 0, 0.40016669, 0)
Credits_2.Size = UDim2.new(0, 200, 0, 48)
Credits_2.Font = Enum.Font.GothamBold
Credits_2.Text = "Credits"
Credits_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Credits_2.TextScaled = true
Credits_2.TextSize = 13.000
Credits_2.TextWrapped = true
 
AnimeCheat.Name = "AnimeCheat"
AnimeCheat.Parent = CreditsFrame
AnimeCheat.BackgroundColor3 = Color3.fromRGB(138, 43, 226)
AnimeCheat.BackgroundTransparency = 100.000
AnimeCheat.BorderSizePixel = 0
AnimeCheat.Position = UDim2.new(0, 0, 0.596000135, 0)
AnimeCheat.Size = UDim2.new(0, 160, 0, 48)
AnimeCheat.Font = Enum.Font.GothamBold
AnimeCheat.Text = "AnimeCheat"
AnimeCheat.TextColor3 = Color3.fromRGB(255, 255, 255)
AnimeCheat.TextSize = 26.000
AnimeCheat.TextWrapped = true
 
Johiro.Name = "Johiro"
Johiro.Parent = CreditsFrame
Johiro.BackgroundColor3 = Color3.fromRGB(138, 43, 226)
Johiro.BackgroundTransparency = 100.000
Johiro.BorderSizePixel = 0
Johiro.Position = UDim2.new(0.5, 0, 0.596000135, 0)
Johiro.Size = UDim2.new(0, 160, 0, 48)
Johiro.Font = Enum.Font.GothamBold
Johiro.Text = "Johiro"
Johiro.TextColor3 = Color3.fromRGB(255, 255, 255)
Johiro.TextSize = 27.000
Johiro.TextWrapped = true
 
Sten.Name = "Sten"
Sten.Parent = CreditsFrame
Sten.BackgroundColor3 = Color3.fromRGB(138, 43, 226)
Sten.BackgroundTransparency = 100.000
Sten.BorderSizePixel = 0
Sten.Position = UDim2.new(0, 0, 0.800166547, 0)
Sten.Size = UDim2.new(0, 160, 0, 48)
Sten.Font = Enum.Font.GothamBold
Sten.Text = "Sten"
Sten.TextColor3 = Color3.fromRGB(255, 255, 255)
Sten.TextSize = 30.000
Sten.TextWrapped = true
 
Averias.Name = "Averias"
Averias.Parent = CreditsFrame
Averias.BackgroundColor3 = Color3.fromRGB(138, 43, 226)
Averias.BackgroundTransparency = 100.000
Averias.BorderSizePixel = 0
Averias.Position = UDim2.new(0.5, 0, 0.796000063, 0)
Averias.Size = UDim2.new(0, 160, 0, 48)
Averias.Font = Enum.Font.GothamBold
Averias.Text = "Averias"
Averias.TextColor3 = Color3.fromRGB(255, 255, 255)
Averias.TextSize = 27.000
Averias.TextWrapped = true
 
Name.Name = "Name"
Name.Parent = mainframe
Name.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Name.BorderSizePixel = 0
Name.Position = UDim2.new(0.200000003, 0, 0, 0)
Name.Size = UDim2.new(0, 240, 0, 40)
Name.Font = Enum.Font.SourceSans
Name.Text = "Shiro's Hub"
Name.TextColor3 = Color3.fromRGB(255, 255, 255)
Name.TextScaled = true
Name.TextSize = 14.000
Name.TextWrapped = true
 
local function QMMS_fake_script() -- mainframe.LocalScript 
	local script = Instance.new('LocalScript', mainframe)
 
	script.parent.Selectable = true
	script.Parent.Active = true
	script.parent.Draggable = true
end
coroutine.wrap(QMMS_fake_script)()
 
local MoneyCooldown = false
local CurrentSlot = game.Players.LocalPlayer:WaitForChild("CurrentSaveSlot").Value
local ScriptLoadOrSave = false
local CurrentlySavingOrLoading = game.Players.LocalPlayer:WaitForChild("CurrentlySavingOrLoading")
 
local function CheckIfSlotAvailable(Slot)
	for a,b in pairs(game.ReplicatedStorage.LoadSaveRequests.GetMetaData:InvokeServer(game.Players.LocalPlayer)) do 
		if a == Slot then 
			for c,d in pairs(b) do 
				if c == "NumSaves" and d ~= 0 then 
					return true
				else
					return false
				end
			end
		end
	end
end
 
local function CheckSlotNumber1() --Checks if the slot number is right
    if MoneyDupeSlot.Text == "1" or MoneyDupeSlot.Text == "2" or MoneyDupeSlot.Text == "3" or MoneyDupeSlot.Text == "4" or MoneyDupeSlot.Text == "5" or MoneyDupeSlot.Text == "6" then
		local SlotNumber = tonumber(MoneyDupeSlot.Text)
		return SlotNumber
		else return false
	end
end
 
local function CheckSlotNumber2() --Checks if the slot number is right
    if DupeSlot.Text == "1" or DupeSlot.Text == "2" or DupeSlot.Text == "3" or DupeSlot.Text == "4" or DupeSlot.Text == "5" or DupeSlot.Text == "6" then
		local SlotNumber = tonumber(DupeSlot.Text)
		return SlotNumber
		else return false
	end
end
 
local function SendNotification(title,text,duration,...)
  game.StarterGui:SetCore("SendNotification", {
    Title = title;
    Text = text;
    Icon = "";
    Duration = duration;
  })
end
 
--Join Detecter
 
game.Players.ChildAdded:Connect(function(player)
  if not pcall (function()
  SendNotification("Player JOINED",""..player.Name.." has JOINED the game",5 )
  end) then
    print ("Error")
  end
  end)
 
--Leave Detecter
 
  game.Players.ChildRemoved:Connect(function(player)
  if not pcall (function()
  SendNotification("Player LEFT",""..player.Name.." has LEFT the game",4.4 )
  end) then
    print ("Error")
  end
  end)
 
  SendNotification("Loaded","Join and leave detector is loaded",2)
 
--Walkspeed
 
Speed.MouseButton1Down:connect(function()
while true do
    wait()
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = SpeedValue.Text
end
end)
 
--Jumppower
 
Jump.MouseButton1Down:connect(function()
while true do
    wait()
    game.Players.LocalPlayer.Character.Humanoid.JumpPower = JumpValue.Text
end
end)
 
--Fly
 
local toggle = false
	Fly.MouseButton1Click:Connect(function()
		toggle = not toggle
		Fly.TextColor3 = (toggle and Color3.fromRGB(85, 255, 127) or Color3.fromRGB(255,255,255))
		if toggle then
			flying = not flying
	repeat wait()
	until game.Players.LocalPlayer and game.Players.LocalPlayer.Character and game.Players.LocalPlayer.Character:findFirstChild("Torso") and game.Players.LocalPlayer.Character:findFirstChild("Humanoid")
	local mouse = game.Players.LocalPlayer:GetMouse()
	repeat wait() until mouse
	local plr = game.Players.LocalPlayer
	local torso = plr.Character.Torso
	local deb = true
	local ctrl = {f = 0, b = 0, l = 0, r = 0}
	local lastctrl = {f = 0, b = 0, l = 0, r = 0}
	local maxspeed = 200
	local speed = 0
	if flying then
	end
 
	function FlyFunction()
	local bg = Instance.new("BodyGyro", torso)
	bg.P = 9e4
	bg.maxTorque = Vector3.new(9e9, 9e9, 9e9)
	bg.cframe = torso.CFrame
	local bv = Instance.new("BodyVelocity", torso)
	bv.velocity = Vector3.new(0,0.1,0)
	bv.maxForce = Vector3.new(9e9, 9e9, 9e9)
	repeat wait()
	plr.Character.Humanoid.PlatformStand = true
	if ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0 then
	speed = speed+.5+(speed/maxspeed)
	if speed > maxspeed then
	speed = maxspeed
	end
	elseif not (ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0) and speed ~= 0 then
	speed = speed-1
	if speed < 0 then
	speed = 0
	end
	end
	if (ctrl.l + ctrl.r) ~= 0 or (ctrl.f + ctrl.b) ~= 0 then
	bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (ctrl.f+ctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(ctrl.l+ctrl.r,(ctrl.f+ctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
	lastctrl = {f = ctrl.f, b = ctrl.b, l = ctrl.l, r = ctrl.r}
	elseif (ctrl.l + ctrl.r) == 0 and (ctrl.f + ctrl.b) == 0 and speed ~= 0 then
	bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (lastctrl.f+lastctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(lastctrl.l+lastctrl.r,(lastctrl.f+lastctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
	else
	bv.velocity = Vector3.new(0,0.1,0)
	end
	bg.cframe = game.Workspace.CurrentCamera.CoordinateFrame * CFrame.Angles(-math.rad((ctrl.f+ctrl.b)*50*speed/maxspeed),0,0)
	until not flying
	ctrl = {f = 0, b = 0, l = 0, r = 0}
	lastctrl = {f = 0, b = 0, l = 0, r = 0}
	speed = 0
	bg:Destroy()
	bv:Destroy()
	plr.Character.Humanoid.PlatformStand = false
	end
	mouse.KeyDown:connect(function(key)
	if key:lower() == "w" then
	ctrl.f = 1
	elseif key:lower() == "s" then
	ctrl.b = -1
	elseif key:lower() == "a" then
	ctrl.l = -1
	elseif key:lower() == "d" then
	ctrl.r = 1
 
	end
	end)
	mouse.KeyUp:connect(function(key)
	if key:lower() == "w" then
	ctrl.f = 0
	elseif key:lower() == "s" then
	ctrl.b = 0
	elseif key:lower() == "a" then
	ctrl.l = 0
	elseif key:lower() == "d" then
	ctrl.r = 0
	end
	end)
	FlyFunction()
		else
			flying = not flying
	repeat wait()
	until game.Players.LocalPlayer and game.Players.LocalPlayer.Character and game.Players.LocalPlayer.Character:findFirstChild("Torso") and game.Players.LocalPlayer.Character:findFirstChild("Humanoid")
	local mouse = game.Players.LocalPlayer:GetMouse()
	repeat wait() until mouse
	local plr = game.Players.LocalPlayer
	local torso = plr.Character.Torso
	local deb = true
	local ctrl = {f = 0, b = 0, l = 0, r = 0}
	local lastctrl = {f = 0, b = 0, l = 0, r = 0}
	local maxspeed = 200
	local speed = 0
	if flying then
	end
 
	function FlyFunction()
	local bg = Instance.new("BodyGyro", torso)
	bg.P = 9e4
	bg.maxTorque = Vector3.new(9e9, 9e9, 9e9)
	bg.cframe = torso.CFrame
	local bv = Instance.new("BodyVelocity", torso)
	bv.velocity = Vector3.new(0,0.1,0)
	bv.maxForce = Vector3.new(9e9, 9e9, 9e9)
	repeat wait()
	plr.Character.Humanoid.PlatformStand = true
	if ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0 then
	speed = speed+.5+(speed/maxspeed)
	if speed > maxspeed then
	speed = maxspeed
	end
	elseif not (ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0) and speed ~= 0 then
	speed = speed-1
	if speed < 0 then
	speed = 0
	end
	end
	if (ctrl.l + ctrl.r) ~= 0 or (ctrl.f + ctrl.b) ~= 0 then
	bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (ctrl.f+ctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(ctrl.l+ctrl.r,(ctrl.f+ctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
	lastctrl = {f = ctrl.f, b = ctrl.b, l = ctrl.l, r = ctrl.r}
	elseif (ctrl.l + ctrl.r) == 0 and (ctrl.f + ctrl.b) == 0 and speed ~= 0 then
	bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (lastctrl.f+lastctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(lastctrl.l+lastctrl.r,(lastctrl.f+lastctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
	else
	bv.velocity = Vector3.new(0,0.1,0)
	end
	bg.cframe = game.Workspace.CurrentCamera.CoordinateFrame * CFrame.Angles(-math.rad((ctrl.f+ctrl.b)*50*speed/maxspeed),0,0)
	until not flying
	ctrl = {f = 0, b = 0, l = 0, r = 0}
	lastctrl = {f = 0, b = 0, l = 0, r = 0}
	speed = 0
	bg:Destroy()
	bv:Destroy()
	plr.Character.Humanoid.PlatformStand = false
	end
	mouse.KeyDown:connect(function(key)
	if key:lower() == "w" then
	ctrl.f = 1
	elseif key:lower() == "s" then
	ctrl.b = -1
	elseif key:lower() == "a" then
	ctrl.l = -1
	elseif key:lower() == "d" then
	ctrl.r = 1
 
	end
	end)
	mouse.KeyUp:connect(function(key)
	if key:lower() == "w" then
	ctrl.f = 0
	elseif key:lower() == "s" then
	ctrl.b = 0
	elseif key:lower() == "a" then
	ctrl.l = 0
	elseif key:lower() == "d" then
	ctrl.r = 0
	end
	end)
	FlyFunction()
		end
	end)
 
--Car Flight
 
CarFlight.MouseButton1Down:connect(function()
repeat wait()
until game.Players.LocalPlayer and game.Players.LocalPlayer.Character and game.Players.LocalPlayer.Character:findFirstChild("Torso") and game.Players.LocalPlayer.Character:findFirstChild("Humanoid")
local mouse = game.Players.LocalPlayer:GetMouse()
repeat wait() until mouse
local plr = game.Players.LocalPlayer
local torso = plr.Character.Torso
local flying = true
local deb = true
local ctrl = {f = 0, b = 0, l = 0, r = 0}
local lastctrl = {f = 0, b = 0, l = 0, r = 0}
local maxspeed = 500
local speed = 0
 
function Fly()
local bg = Instance.new("BodyGyro", torso)
bg.P = 9e4
bg.maxTorque = Vector3.new(9e9, 9e9, 9e9)
bg.cframe = torso.CFrame
local bv = Instance.new("BodyVelocity", torso)
bv.velocity = Vector3.new(0,0.1,0)
bv.maxForce = Vector3.new(9e9, 9e9, 9e9)
repeat wait()
plr.Character.Humanoid.PlatformStand = false
if ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0 then
speed = speed+125.0+(speed/maxspeed)
if speed > maxspeed then
speed = maxspeed
end
elseif not (ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0) and speed ~= 0 then
speed = speed-250
if speed < 0 then
speed = 0
end
end
if (ctrl.l + ctrl.r) ~= 0 or (ctrl.f + ctrl.b) ~= 0 then
bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (ctrl.f+ctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(ctrl.l+ctrl.r,(ctrl.f+ctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
lastctrl = {f = ctrl.f, b = ctrl.b, l = ctrl.l, r = ctrl.r}
elseif (ctrl.l + ctrl.r) == 0 and (ctrl.f + ctrl.b) == 0 and speed ~= 0 then
bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (lastctrl.f+lastctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(lastctrl.l+lastctrl.r,(lastctrl.f+lastctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
else
bv.velocity = Vector3.new(0,0.1,0)
end
bg.cframe = game.Workspace.CurrentCamera.CoordinateFrame * CFrame.Angles(-math.rad((ctrl.f+ctrl.b)*50*speed/maxspeed),0,0)
until not flying
ctrl = {f = 0, b = 0, l = 0, r = 0}
lastctrl = {f = 0, b = 0, l = 0, r = 0}
speed = 0
bg:Destroy()
bv:Destroy()
plr.Character.Humanoid.PlatformStand = false
end
mouse.KeyDown:connect(function(key)
if key:lower() == "z" then
if flying then flying = false
else
flying = true
Fly()
end
elseif key:lower() == "w" then
ctrl.f = 1
elseif key:lower() == "s" then
ctrl.b = -1
elseif key:lower() == "a" then
ctrl.l = -1
elseif key:lower() == "d" then
ctrl.r = 1
end
end)
mouse.KeyUp:connect(function(key)
if key:lower() == "w" then
ctrl.f = 0
elseif key:lower() == "s" then
ctrl.b = 0
elseif key:lower() == "a" then
ctrl.l = 0
elseif key:lower() == "d" then
ctrl.r = 0
end
wait(5)
end)
end)
 
--Infinite Jump
 
local toggle = false
	InfJump.MouseButton1Click:Connect(function()
		toggle = not toggle
		InfJump.TextColor3 = (toggle and Color3.fromRGB(85, 255, 127) or Color3.fromRGB(255,255,255))
		if toggle then
			InfiniteJumpEnabled = true
		game:GetService("UserInputService").JumpRequest:connect(function()
		if InfiniteJumpEnabled then
			game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")
			InfiniteJumpEnabled = true
		end
	end)
 
		else
				InfiniteJumpEnabled = false
	       game:GetService("UserInputService").JumpRequest:connect(function()
		if InfiniteJumpEnabled then
			game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")
 
		end
	end)
		end
	end)
 
--No Clip
 
	_G.noclip = false
	game:GetService('RunService').Stepped:connect(function()
	if noclip then
	game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
	NoClip.TextColor3 = Color3.fromRGB(85, 255, 127)
	end
	end)
	NoClip.MouseButton1Down:connect(function()
	noclip = not noclip
	NoClip.TextColor3 = Color3.fromRGB(255, 255, 255)
	end)
 
--Ctrl+Click TP
 
TP.MouseButton1Down:connect(function()
local UIS = game:GetService("UserInputService")
 
local Player = game.Players.LocalPlayer
local Mouse = Player:GetMouse()
 
 
function GetCharacter()
   return game.Players.LocalPlayer.Character
end
 
function Teleport(pos)
   local Char = GetCharacter()
   if Char then
       Char:MoveTo(pos)
   end
end
 
 
UIS.InputBegan:Connect(function(input)
   if input.UserInputType == Enum.UserInputType.MouseButton1 and UIS:IsKeyDown(Enum.KeyCode.LeftControl) then
       Teleport(Mouse.Hit.p)
   end
end)
end)
 
--All BP's
 
AllBp.MouseButton1Click:Connect(function()
	for i,v in pairs(game.ReplicatedStorage.Purchasables.Structures.BlueprintStructures:GetChildren()) do
	local clone = v:Clone()
	clone.Parent = game.Players.LocalPlayer.PlayerBlueprints.Blueprints
	end
end)
 
--Jesus
 
	local toggle = false
	jesus.MouseButton1Click:Connect(function()
		toggle = not toggle
		jesus.TextColor3 = (toggle and Color3.fromRGB(85, 255, 127) or Color3.fromRGB(255,255,255))
		if toggle then
			for index, water in pairs(game.Workspace.Water:GetChildren()) do
	   water.CanCollide = true
	end
		else
			for index, water in pairs(game.Workspace.Water:GetChildren()) do
	   water.CanCollide = false
	end
		end
	end)
 
--No Fog
 
NoFog.MouseButton1Down:connect(function()
	--Fog.BackgroundColor3 = Color3.new(0, 0, 0)
                      NoFog.TextColor3 = Color3.new(1, 1, 1)
game.Lighting.Changed:connect(function()
	game.Lighting.TimeOfDay = "12:00:00"
	game.Lighting.FogEnd = 9999
	game.Lighting.Brightness = 2
end)
end)
 
--Golden Axe
 
spawn(function()
	GAxe = false
	function GetAxe() --Gets your current axe thats equiped when called
	    if game.Players.LocalPlayer.Character:FindFirstChild("Tool") then
	        return game.Players.LocalPlayer.Character.Tool --returns the axe when found
	    else
	        return false --returns false when not equiped
	    end
	end
 
	function GetDamage(Axe, TreeClass)-- Gets the right Damage of the axe and returns it if called to prevent killing yourself like gold axe
	    if Axe.ToolTip == "Basic Hatchet" then return 0.2
	    elseif Axe.ToolTip == "Plain Axe" then return 0.55
	    elseif Axe.ToolTip == "Steel Axe" then return 0.93
	    elseif Axe.ToolTip == "Hardened Axe" then return 1.45
	    elseif Axe.ToolTip == "Silver Axe" then return 1.6
	    elseif Axe.ToolTip == "Rukiryaxe" then return 1.68
	    elseif Axe.ToolTip == "Beta Axe of Bosses" then return 1.45
	    elseif Axe.ToolTip == "Alpha Axe of Testing" then return 1.5
	    elseif Axe.ToolTip == "Fire Axe" then
	        if TreeClass ~= "Volcano" then return 0.6 else return 6.35 end
	    elseif Axe.ToolTip == "End Times Axe" then
	        if TreeClass ~= "LoneCave" then return 1.58 else return 10000000 end
	    elseif Axe.ToolTip == "Candy Cane Axe" then return 0
	    elseif Axe.ToolTip == "Johiro" then return 1.8
	    elseif Axe.ToolTip == "Beesaxe" then return 1.4
	    elseif Axe.ToolTip == "CHICKEN AXE" then return 0.9
	    elseif Axe.ToolTip == "Amber Axe" then return 3.39
	    elseif Axe.ToolTip == "The Many Axe" then return 10.2
	    elseif Axe.ToolTip == "Gingerbread Axe" then
	        if TreeClass == "Walnut" then return 8.5
	    elseif TreeClass == "Koa" then return 11 else return 1.2 end
	    elseif Axe.ToolTip == "Bird Axe" then
	        if TreeClass == "Volcano" then return 2.5 elseif TreeClass == "CaveCrawler" then return 3.9 else return 1.65 end
	    end
	end
 
 
	function GCut(TreePart) --Cuts the tree when called with the tree you want to cut
	    if GetAxe() ~= false then --checks if you have a axe equiped
	        Damage = GetDamage(GetAxe(), TreePart.Parent.TreeClass.Value) --gets the Damage
	        Height = TreePart.CFrame:pointToObjectSpace(mouse.Hit.p).Y + TreePart.Size.Y/2 --Gets the Height
	        local CutArguments = {
	            sectionId = TreePart.ID.Value,
	            faceVector = Vector3.new(0,0,-1),
	            height = Height,
	            hitPoints = Damage,
	            cooldown = 0,
	            cuttingClass = "Axe",
	            tool = GetAxe()
	        }
	        for i=1, 50 do
	            game.ReplicatedStorage.Interaction.RemoteProxy:FireServer(TreePart.Parent.CutEvent, CutArguments)
	        end
	    end
	end
 
	function CutTree(Tree) --Cuts the tree when called with the tree you want to cut
	    if GetAxe() ~= false then --checks if you have a axe equiped
	        Damage = GetDamage(GetAxe(), Tree.TreeClass.Value) --gets the Damage
	        local CutArguments = {
	            sectionId = 1,
	            faceVector = Vector3.new(0,0,-1),
	            height = 0.5,
	            hitPoints = Damage,
	            cooldown = 0,
	            cuttingClass = "Axe",
	            tool = GetAxe()
	        }
	        for i=1, 50 do
	            game.ReplicatedStorage.Interaction.RemoteProxy:FireServer(Tree.CutEvent, CutArguments)
	        end
	    end
	end
 
	TreeList = {} --Creates a table of the trees
	for a,b in pairs(workspace:GetChildren()) do
	    if b.name == "TreeRegion" then
	        b.ChildAdded:Connect(function(NewTree)--Creates functions that Adds new trees to the list
	            table.insert(TreeList, NewTree)
	        end)
	        for c,d in pairs(b:GetChildren()) do-- Adds the trees when first time starting the script
	            if d.Name == "Model" then
	                table.insert(TreeList, d)
	            end
	        end
	    end
	end
 
	spawn(function() --used spawn so it wont interrupt any of the other things
	CutEnabled = false
	while wait(.5) do --Main loop to do the stuff
	    if CutEnabled == true then
	        if GetAxe() ~= false then --Checks if you have a axe equiped
	            for a,b in pairs(TreeList) do
	                if not b:FindFirstChild("RootCut") and b:FindFirstChild("CutEvent") then --Checks if the tree is already cut
	                    distance = (game.Players.LocalPlayer.Character.Head.Position - b.WoodSection.Position).magnitude --gets the distance between player and tree
	                    if distance < 225 then --if distance lower than 225 then it will cut the tree
	                        CutTree(b) --Calls the function with the tree to cut
	                    end
	                else
	                    table.remove(TreeList, a)--if tree already cut then it gets removed from the list
	                end
	            end
	        end
	    end
	end
	end)
 
	mouse = game.Players.LocalPlayer:GetMouse() --Gets the Mouse
	mouse.Button1Down:connect(function()
	    if GAxe == true and GetAxe() ~= false then
	        Target = mouse.Target
	        GCut(Target)
	    end
	end)
	--Credits to Johiro, if you decide to skid atleast give credits
	end)
	GoldenAxe.MouseButton1Down:connect(function()
 
	    if GAxe == true then
	        GAxe = false
	GoldenAxe.TextColor3 = Color3.fromRGB(255, 255, 255)
	    elseif GAxe == false then
	        GAxe = true
	GoldenAxe.TextColor3 = Color3.fromRGB(85, 255, 127)
	--Credits to Johiro
	    end
	end)
 
--Paint
 
Paint.MouseButton1Click:connect(function()
	loadstring(game:HttpGet('https://pastebin.com/raw/3Bk4KVYq',true))()
end)
 
--Fast Delete BP's
 
FastDelBps.MouseButton1Click:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/1YR8cpNE", true))()
end)
 
--Reset Character
 
ResetCharacter.MouseButton1Click:connect(function()
	game.Players.LocalPlayer.Character.Head:Destroy()
end)
 
--Secret Walkspeed
 
SecretWalkSpeed.MouseButton1Down:connect(function()
	local walkspeedplayer = game:GetService("Players").LocalPlayer
	local walkspeedmouse = walkspeedplayer:GetMouse()
 
	local walkspeedenabled = false
 
	function x_walkspeed(key)
		if (key == "x") then
			if walkspeedenabled == false then
				_G.WS = 200;
				local Humanoid = game:GetService("Players").LocalPlayer.Character.Humanoid;
				Humanoid:GetPropertyChangedSignal("WalkSpeed"):Connect(function()
				Humanoid.WalkSpeed = _G.WS;
				end)
				Humanoid.WalkSpeed = _G.WS;
 
				walkspeedenabled = true
			elseif walkspeedenabled == true then
				_G.WS = 20;
				local Humanoid = game:GetService("Players").LocalPlayer.Character.Humanoid;
				Humanoid:GetPropertyChangedSignal("WalkSpeed"):Connect(function()
				Humanoid.WalkSpeed = _G.WS;
				end)
				Humanoid.WalkSpeed = _G.WS;
 
				walkspeedenabled = false
			end
		end
	end
 
	walkspeedmouse.KeyDown:connect(x_walkspeed)
 
end)
 
--Sell Wood
 
SellWood.MouseButton1Down:connect(function()
            for _, Log in pairs(workspace.LogModels:GetChildren()) do
        if Log.Name:sub(1, 6) == "Loose_" and Log:findFirstChild("Owner") then
            if Log.Owner.Value == game.Players.LocalPlayer then
                for i,v in pairs(Log:GetChildren()) do
                    if v.Name=="WoodSection" then
                        spawn(function()
                            for i=1,10 do
                                wait()
                                v.CFrame=CFrame.new(Vector3.new(315, -0.296, 85.791))*CFrame.Angles(math.rad(90),0,0)
                            end
                        end)
                    end
                end
                spawn(function()
                    for i=1,20 do
                        wait()
                        game.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(Log)
                    end
                end)
            end
        end
    end
end)
 
--Sell Planks
 
SellPlanks.MouseButton1Click:Connect(function()
	for _, Plank in pairs(game.Workspace.PlayerModels:GetChildren()) do
		if Plank.Name=="Plank" and Plank:findFirstChild("Owner") then
			if Plank.Owner.Value == game.Players.LocalPlayer then
				for i,v in pairs(Plank:GetChildren()) do
					if v.Name=="WoodSection" then
						spawn(function()
							for i=1,10 do
								wait()
								v.CFrame=CFrame.new(Vector3.new(315, -0.296, 85.791))*CFrame.Angles(math.rad(90),0,0)
							end
						end)
					end
				end
				spawn(function()
					for i=1,20 do
						wait()
						game.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(Plank)
					end
				end)
			end
		end
	end
end)
 
--TP Wood
 
TPWood.MouseButton1Click:Connect(function()
    for _, Log in pairs(game.Workspace.LogModels:GetChildren()) do
        if Log.Name:sub(1, 6) == "Loose_" and Log:findFirstChild("Owner") then
            if Log.Owner.Value == game.Players.LocalPlayer then
                Log:MoveTo(game.Players.LocalPlayer.Character.HumanoidRootPart.Position + Vector3.new(0, 20, 0))
                for i=1,100 do
                    game.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(Log)
                end
            end
        end
    end
end)
 
--TP Planks
 
TPPlanks.MouseButton1Click:Connect(function()
	for _, Plank in pairs(game.Workspace.PlayerModels:GetChildren()) do
		if Plank.Name=="Plank" and Plank:findFirstChild("Owner") then
			if Plank.Owner.Value == game.Players.LocalPlayer then
				sendNotice = game.ReplicatedStorage.Notices.SendUserNotice
				sendNotice:Fire("Click where you want ALL the Planks to TP to")
				local ButtonPress
				ButtonPress = game.Players.LocalPlayer:GetMouse().Button1Down:Connect(function()
					Square = game.Players.LocalPlayer:GetMouse().Target
					if (Square.Name == "OriginSquare" or Square.Name == "Square") then
						ButtonPress:Disconnect()
						Plank:MoveTo(Square.Position)
						for i=1,100 do
							game.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(Plank)
						end
					end
				end)
			end
		end
	end
end)
 
--Mod Wood
 
ModWood.MouseButton1Click:Connect(function()
	           for _, Log in pairs(workspace.LogModels:GetChildren()) do
	        if Log.Name:sub(1, 6) == "Loose_" and Log:findFirstChild("Owner") then
	            if Log.Owner.Value == game.Players.LocalPlayer then
	                for i,v in pairs(Log:GetChildren()) do
	                    if v.Name=="WoodSection" then
	                        spawn(function()
	                            for i=1,10 do
	                                wait()
	                                v.CFrame=CFrame.new(Vector3.new(315, -0.296, 85.791))*CFrame.Angles(math.rad(90),0,0)
	                            end
	                        end)
	                    end
	                end
	                spawn(function()
	                    for i=1,20 do
	                        wait()
	                        game.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(Log.WoodSection)
	            game.ReplicatedStorage.Interaction.ClientRequestOwnership:FireServer(Log.WoodSection)
	                    end
	                end)
	            end
	        end
	    end
	wait(2.0)
	    for _, Log in pairs(game.Workspace.LogModels:GetChildren()) do
	        if Log.Name:sub(1, 6) == "Loose_" and Log:findFirstChild("Owner") then
	            if Log.Owner.Value == game.Players.LocalPlayer then
	                Log:MoveTo(game.Players.LocalPlayer.Character.HumanoidRootPart.Position)
	                for i=1,20 do
	                    game.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(Log.WoodSection)
	                    game.ReplicatedStorage.Interaction.ClientRequestOwnership:FireServer(Log.WoodSection)
	                end
	            end
	        end
	    end
end)
 
--Remove Tree's
 
RemoveTrees.MouseButton1Click:Connect(function()
	for i,v in pairs(game.Workspace:GetDescendants()) do
	    if v.Name == "WoodSection" and v.Parent:FindFirstChild("CutEvent") then
	        game.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(v.Parent)
	        game.ReplicatedStorage.Interaction.DestroyStructure:FireServer(v.Parent)
	    end
	end
	game.Workspace.DescendantAdded:connect(function(Thing)
	    wait(0.1)
	    if Thing.Name == "WoodSection" and Thing.Parent:FindFirstChild("CutEvent") then
	        game.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(Thing.Parent)
	        game.ReplicatedStorage.Interaction.DestroyStructure:FireServer(Thing.Parent)
	    end
	end)
	end)
 
--Wood R Us
 
StoreWoodRUs.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(265, 5, 57))
end)
 
--Link's Logic
 
StoreLogic.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(4607, 9, -798))
end)
 
--Spawn
 
Spawn.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(155, 5, 74))
end)
 
--Ice Wood
 
IceWood.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(1451.66248, 412.208405, 3183.47607))
end)
 
--Land Store
 
StoreLand.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(258, 5, -99))
end)
 
--Fine Arts
 
StoreFineArts.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(5207, -156, 719))
end)
 
 
--Volcano
 
Volcano.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(-1585, 625, 1140))
end)
 
--Palm
 
Palm.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(2549, 5, -42))
end)
 
--Boxed Cars
 
StoreCars.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(509, 5.2, -1463))
end)
 
--Bob's Shack
 
StoreBobs.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(260, 10, -2542))
end)
 
--Swamp
 
Swamp.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(-1209, 138, -801))
end)
 
--End Times
 
EndTimes.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(113, -204, -951))
end)
 
--Fancy Furnishings
 
StoreFancy.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(491, 13, -1720))
end)
 
--Strange Man
 
StrangeMan.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(1061, 20, 1131))
end)
 
--Yellow Wood
 
YellowWood.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(-1124.91565, 1.10021782, -943.932129))
end)
 
--Cave
 
Cave.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(3581, -177, 430))
end)
 
--Green Box
 
GreenBox.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(-1668.39197, 349.601929, 1475.36255))
end)
 
--Lodge
 
Lodge.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(1244, 66, 2306))
end)
 
--Dock
 
Dock.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(1114, 3.2, -197))
end)
 
--Bridge
 
Bridge.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(113, 15, -977))
end)
 
--Dupe Step 1
 
DupeStep1.MouseButton1Click:Connect(function()
	ScriptLoadOrSave = true
	local CheckSlot = CheckSlotNumber2()
	if CheckSlot ~= false then
		if CheckIfSlotAvailable(CheckSlot) == true then
			local LoadSlot = game.ReplicatedStorage.LoadSaveRequests.RequestLoad:InvokeServer(CheckSlot)
			if LoadSlot == false then
				SendNotification("Cooldown Notification", "You aren't abled to load now", 1)
			end
			if LoadSlot == true then 
				SendNotification("Reload Notification", "Loaded Your Slot", 2)
				CurrentSlot = CheckSlot
			end
		else
			SendNotification("Slot not Available", "This Slot is not Available, please choose another slot", 2)
		end
	else
		SendNotification("Incorrect Slot", "Enter a Valid number in the upper field", 1)
	end
	ScriptLoadOrSave = false
end)
 
--Dupe Step 2
 
DupeStep2.MouseButton1Click:Connect(function()
	ScriptLoadOrSave = true
	local CheckSlot = CheckSlotNumber2()
	if CheckSlot ~= false then
		if CheckIfSlotAvailable(CheckSlot) == true then
			local LoadSlot = game.ReplicatedStorage.LoadSaveRequests.RequestLoad:InvokeServer(CheckSlot)
			if LoadSlot == false then
				SendNotification("Cooldown Notification", "You aren't abled to load now", 1)
			end
			if LoadSlot == true then 
				SendNotification("Reload Notification", "Loaded Your Slot", 2)
				CurrentSlot = CheckSlot
			end
		else
			SendNotification("Slot not Available", "This Slot is not Available, please choose another slot", 2)
		end
	else
		SendNotification("Incorrect Slot", "Enter a Valid number in the upper field", 1)
	end
	ScriptLoadOrSave = false
end)
 
--Money Step 1
 
MoneyStep1.MouseButton1Click:Connect(function()
 
	local CheckSlot = CheckSlotNumber1()
	if CheckSlot ~= false then
		if CurrentSlot ~= -1 then
			ScriptLoadOrSave = true
			local SaveSlot = game.ReplicatedStorage.LoadSaveRequests.RequestSave:InvokeServer(CheckSlot)
			if SaveSlot == true then
				SendNotification("Save Notification", "Saved your Slot", 2)
				wait(.5)
				ScriptLoadOrSave = false
			elseif SaveSlot == false then
				SendNotification("Already Saving", "Saving/Loading is currently in Progress", 1)
				wait(.5)
				ScriptLoadOrSave = false
			end
		else
			SendNotification("Error", "Load Your Slot First before saving", 1)
		end
	else
		SendNotification("Incorrect Slot", "Enter a number in the upper field", 1)
	end
wait(3)
 
	if MoneyCooldown == true then
		SendNotification("Cooldown Notification", "Wait for your Money to come back",2)
		return
	elseif MoneyCooldown == false then
		MoneyCooldown = true
		SendNotification("Money Sent", "Wait about 2 minutes for your Money to come back", 5)
		game.ReplicatedStorage.Transactions.ClientToServer.Donate:InvokeServer(game.Players.LocalPlayer, game.Players.LocalPlayer.leaderstats.Money.Value, 1)
		SendNotification("Money Received", "You received your money that you have sent earlier", 5)
		MoneyCooldown = false
	end
end)
 
--Money Step 2
 
MoneyStep2.MouseButton1Click:Connect(function()
		ScriptLoadOrSave = true
	local CheckSlot = CheckSlotNumber1()
	if CheckSlot ~= false then
		if CheckIfSlotAvailable(CheckSlot) == true then
			local LoadSlot = game.ReplicatedStorage.LoadSaveRequests.RequestLoad:InvokeServer(CheckSlot)
			if LoadSlot == false then
				SendNotification("Cooldown Notification", "You aren't abled to load now", 1)
			end
			if LoadSlot == true then 
				SendNotification("Reload Notification", "Loaded Your Slot", 2)
				CurrentSlot = CheckSlot
			end
		else
			SendNotification("Slot not Available", "This Slot is not Available, please choose another slot", 2)
		end
	else
		SendNotification("Incorrect Slot", "Enter a Valid number in the upper field", 1)
	end
	ScriptLoadOrSave = false
end)
 
--Axe Store Axes
 
StoreAxes.MouseButton1Down:connect(function() --Stores the Axes somewhere so you can restore them later
	Amount = 0
	for a,b in pairs(game.Players.LocalPlayer.Backpack:GetChildren())do
		if b.Name ~= "BlueprintTool" and b.Name == "Tool" then
			b.Parent = game.Players.LocalPlayer
			Amount = Amount + 1
		end
	end
	SendNotification("Store Notification", "Stored "..Amount.." Axes, you can restore them later", 2)
end)
 
--Axe Restore Axes
 
RestoreAxes.MouseButton1Down:connect(function() --Restores the axes that you stored with the Store function
	Amount = 0
	for a,b in pairs(game.Players.LocalPlayer:GetChildren()) do
		if b.Name ~= "BlueprintTool" and b.Name == "Tool" then
			b.Parent = game.Players.LocalPlayer.Backpack
			Amount = Amount + 1
		end
	end
	SendNotification("Restore Notification", "Restored "..Amount.." Axes that you Stored", 2)
end)
 
--Axe Count Axes
 
CountAxes.MouseButton1Down:connect(function() --Counts Axes in your Backpack (Equiped Axes dont Count)
	Amount = 0
	for a,b in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
		if b.Name ~= "BlueprintTool" and b.Name == "Tool" then
			Amount = Amount + 1
		end
	end
	SendNotification("Axe Amount", "You have "..Amount.." Axes in your Backpack",2)
end)
 
--Maxland
 
MaxLand.MouseButton1Down:Connect(function()
for i, v in pairs(game:GetService("Workspace").Properties:GetChildren()) do
        if v:FindFirstChild("Owner") and v.Owner.Value == game.Players.LocalPlayer then
            base = v
            square = v.OriginSquare
            end
        end
    function makebase(pos)
        local Event = game:GetService("ReplicatedStorage").PropertyPurchasing.ClientExpandedProperty
        Event:FireServer(base, pos)
        end
    spos = square.Position
    makebase(CFrame.new(spos.X + 40, spos.Y, spos.Z))
    makebase(CFrame.new(spos.X - 40, spos.Y, spos.Z))
    makebase(CFrame.new(spos.X, spos.Y, spos.Z + 40))
    makebase(CFrame.new(spos.X, spos.Y, spos.Z - 40))
    makebase(CFrame.new(spos.X + 40, spos.Y, spos.Z + 40))
    makebase(CFrame.new(spos.X + 40, spos.Y, spos.Z - 40))
    makebase(CFrame.new(spos.X - 40, spos.Y, spos.Z + 40))
    makebase(CFrame.new(spos.X - 40, spos.Y, spos.Z - 40))
    makebase(CFrame.new(spos.X + 80, spos.Y, spos.Z))
    makebase(CFrame.new(spos.X - 80, spos.Y, spos.Z))
    makebase(CFrame.new(spos.X, spos.Y, spos.Z + 80))
    makebase(CFrame.new(spos.X, spos.Y, spos.Z - 80))
--Corners--
    makebase(CFrame.new(spos.X + 80, spos.Y, spos.Z + 80))
    makebase(CFrame.new(spos.X + 80, spos.Y, spos.Z - 80))
    makebase(CFrame.new(spos.X - 80, spos.Y, spos.Z + 80))
    makebase(CFrame.new(spos.X - 80, spos.Y, spos.Z - 80))
--Corners--
    makebase(CFrame.new(spos.X + 40, spos.Y, spos.Z + 80))
    makebase(CFrame.new(spos.X - 40, spos.Y, spos.Z + 80))
    makebase(CFrame.new(spos.X + 80, spos.Y, spos.Z + 40))
    makebase(CFrame.new(spos.X + 80, spos.Y, spos.Z - 40))
    makebase(CFrame.new(spos.X - 80, spos.Y, spos.Z + 40))
    makebase(CFrame.new(spos.X - 80, spos.Y, spos.Z - 40))
    makebase(CFrame.new(spos.X + 40, spos.Y, spos.Z - 80))
    makebase(CFrame.new(spos.X - 40, spos.Y, spos.Z - 80))
 
end)
 
--Wipe Base
 
WipeBase.MouseButton1Click:Connect(function()
		local plr = game.Players.LocalPlayer
	local torso = plr.Character.HumanoidRootPart
 
	local delaybeweenchecks = 0.5
	local opendistance = 10
 
	for i, v in pairs(game:GetService("Workspace").Stores.ShopItems:GetChildren()) do
	local A_1 = v
	local Event = game:GetService("ReplicatedStorage").Interaction.ClientIsDragging
	Event:FireServer(A_1)
	end
end)
 
--Copy Base
 
local script = Instance.new('LocalScript', CopyBase)
 
	script.Parent.MouseButton1Click:Connect(function()
		local RunService = game:GetService("RunService")
	local TargetPlayer = script.Parent.Parent.PlayerName.Text
	local SlowMode = true
	local WipeLocal = false
 
	local CopyStructure = true
	local CopyWire = true
	local CopyItems = true
	local CopyFurniture = true
 
	if WipeLocal then
	for i,v in pairs(game.Workspace.PlayerModels:GetChildren()) do
	if v:FindFirstChild("Owner") then
	if v.Owner.Value == game.Players.LocalPlayer then
	game.ReplicatedStorage.Interaction.DestroyStructure:FireServer(v)
	end
	end
	end
	wait(0.5)
	end
 
	for i,v in pairs(game.Players:GetChildren()) do
	if v ~= game.Players.LocalPlayer then
	if v.Name:find(TargetPlayer) then
	TargetPlayer = v
	break
	end
	end
	end
 
	local LocalLand, TargetLand
 
	for i,v in pairs(game.Workspace.Properties:GetChildren()) do
	if v:FindFirstChild("Owner") then
	if v.Owner.Value == TargetPlayer then
	TargetLand = v
	elseif v.Owner.Value == game.Players.LocalPlayer then
	LocalLand = v
	end
	end
	end
 
	local CollectedTargetStructures, CollectedLocalStructures, CollectedLocalFurnitures, CollectedTargetFurnitures, CollectedLocalItems, CollectedTargetItems  = {}, {}, {}, {}, {}, {}
	local CollectedTargetItemsCopy, CollectedTargetFurnituresCopy = {}, {}
	local TotalCollectedBlueprints = 0
 
	if CopyStructure then
	for i,v in pairs(game.Workspace.PlayerModels:GetChildren()) do
	if v:FindFirstChild("Owner") and v.Owner.Value == TargetPlayer then
	if v:FindFirstChild("BuildDependentWood") and (v.Type.Value == "Structure" or v.Type.Value == "Furniture") then
	local Data = {}
	Data.WoodClass = v:FindFirstChild("BlueprintWoodClass") and v.BlueprintWoodClass.Value
	Data.OffSet = (v:FindFirstChild("MainCFrame") and v.MainCFrame.Value or v.PrimaryPart.CFrame) - TargetLand.OriginSquare.Position
	Data.BlueprintType = v.ItemName.Value
	table.insert(CollectedTargetStructures,Data)
	end
	end
	end
 
	for i, Data in pairs(CollectedTargetStructures) do
	game.ReplicatedStorage.PlaceStructure.ClientPlacedBlueprint:FireServer(Data.BlueprintType, LocalLand.OriginSquare.CFrame - Vector3.new(0,20,0), game.Players.LocalPlayer)
 
	if SlowMode and (math.random(1,2) ~= 1) then
	RunService.RenderStepped:Wait()
	end
	end
	end
 
	function blueprintHasBeenCollected(Model)
	if CollectedLocalStructures[Model.Name] then
	for i, BlueprintModel in pairs(CollectedLocalStructures[Model.Name]) do
	if BlueprintModel == Model then
	return true
	end
	end
	end
	return false
	end
 
	repeat
	for i,v in pairs(game.Workspace.PlayerModels:GetChildren()) do
	if v:FindFirstChild("Owner") and v.Owner.Value == game.Players.LocalPlayer and v:FindFirstChild("Type") and v.Type.Value == "Blueprint" and not blueprintHasBeenCollected(v) then
	if not CollectedLocalStructures[v.Name] then
	CollectedLocalStructures[v.Name] = {}
	end
	table.insert(CollectedLocalStructures[v.Name], v)
	TotalCollectedBlueprints = TotalCollectedBlueprints + 1
	end
	end
	wait()
	until TotalCollectedBlueprints == #CollectedTargetStructures
 
	function SpawnStructure(Data, Blueprint)
	local Position = Data.OffSet + LocalLand.OriginSquare.Position
	game.ReplicatedStorage.PlaceStructure.ClientPlacedStructure:FireServer(Blueprint.ItemName.Value, Position, game.Players.LocalPlayer, Data.WoodClass, Blueprint, not Data.WoodClass)
	end
 
	for i, Data in pairs(CollectedTargetStructures) do
	local Blueprint = CollectedLocalStructures[Data.BlueprintType][1]
	table.remove(CollectedLocalStructures[Data.BlueprintType], 1)
 
	SpawnStructure(Data, Blueprint)
 
	if SlowMode and (math.random(1,2) ~= 1) then
	RunService.RenderStepped:Wait()
	end
	end
 
	function CreateWire(WireType, Points)
	local Wire = game.ReplicatedStorage.Purchasables.WireObjects[WireType]
 
	for i,v in pairs(Points) do
	Points[i] = v + LocalLand.OriginSquare.Position
	end
 
	game.ReplicatedStorage.PlaceStructure.ClientPlacedWire:FireServer(Wire, Points)
	end
 
	if CopyWire then
	for i,v in pairs(game.Workspace.PlayerModels:GetChildren()) do
	if v:FindFirstChild("Owner") and v.Owner.Value == TargetPlayer and v:FindFirstChild("Type") and v.Type.Value == "Wire" and v:FindFirstChild("End1") then
	local Points = {}
	local PointCount = 1
 
	table.insert(Points, (v.End1.Position - TargetLand.OriginSquare.Position))
 
	for i,w in pairs(v:GetChildren()) do
	if w.Name:find("Point") then
	PointCount = PointCount + 1
	end
	end
 
	for i=2, PointCount do
	local Point = v:FindFirstChild("Point"..tostring(i))
	table.insert(Points, (Point.Position - TargetLand.OriginSquare.Position))
	end
 
	table.insert(Points, (v.End2.Position - TargetLand.OriginSquare.Position))
	CreateWire(v.ItemName.Value, Points)
 
	if SlowMode and (math.random(1,2) ~= 1)then
	RunService.RenderStepped:Wait()
	end
	end
	end
	end
 
	function isValidFurniture(Model)
	if Model:FindFirstChild("Type") and (Model.Type.Value == "Structure" or Model.Type.Value == "Furniture" or Model.Type.Value == "Vehicle Spot") then
	if Model:FindFirstChild("BuildDependentWood") or Model:FindFirstChild("PurchasedBoxItemName") then
	return false
	end
	return true
	end
	return false
	end
 
	function Spawn(ItemName, Position)
	   local Info = {}
	   Info.Name = ItemName.Value
	   Info.Type = ItemName.Name == "PurchasedBoxItemName" and ItemName or game.ReplicatedStorage.Purchasables.Structures.HardStructures.Sawmill2.Type
	   Info.OtherInfo = game.ReplicatedStorage.Purchasables.WireObjects.Wire.OtherInfo
	   local Points = {Position.p, Position.p}
	   game.ReplicatedStorage.PlaceStructure.ClientPlacedWire:FireServer(Info, Points)
	end
 
	if CopyFurniture then
	for i, Model in pairs(game.Workspace.PlayerModels:GetChildren()) do
	if Model:FindFirstChild("Owner") and Model.Owner.Value == TargetPlayer and isValidFurniture(Model) then
	local ItemName = Model:FindFirstChild("ItemName") or Model:FindFirstChild("PurchasedBoxItemName")
	local Position = (Model:FindFirstChild("MainCFrame") and Model.MainCFrame.Value or Model.PrimaryPart.CFrame) - TargetLand.OriginSquare.Position
 
	if ItemName.Name == "PurchasedBoxItemName" then
	Spawn(ItemName, Position + LocalLand.OriginSquare.Position)
	else
	Spawn(ItemName, LocalLand.OriginSquare.CFrame - Vector3.new(0,20,0))
	end
 
	local Data = {}
	Data.ItemName = ItemName.Value
	Data.OffSet = Position
 
	table.insert(CollectedTargetFurnitures, Data)
 
	if SlowMode and (math.random(1,2) ~= 1)then
	RunService.RenderStepped:Wait()
	end
	end
	end
	end
 
	for i, v in pairs(CollectedTargetFurnitures) do
	table.insert(CollectedTargetFurnituresCopy,v)
	end
 
	function isValidFurnitureModel(Model)
	for i, Data in pairs(CollectedTargetFurnitures) do
	if Data.ItemName == Model.ItemName.Value then
	table.remove(CollectedTargetFurnitures, i)
	return true
	end
	end
	return false
	end
 
	repeat
	for i, Model in pairs(game.Workspace.PlayerModels:GetChildren()) do
	if Model.Name == "Wire" and Model:FindFirstChild("Owner") and Model.Owner.Value == game.Players.LocalPlayer and Model.ItemName.Value ~= "Wire" and isValidFurnitureModel(Model) then
	table.insert(CollectedLocalFurnitures, Model)
	end
	end
	wait()
	until #CollectedTargetFurnitures == 0
 
	function GrabModelFromCollectedFurnitures(ItemName)
	for i, Model in pairs(CollectedLocalFurnitures) do
	if Model.ItemName.Value == ItemName then
	table.remove(CollectedLocalFurnitures,i)
	return Model
	end
	end
	end
 
	for i, Data in pairs(CollectedTargetFurnituresCopy) do
	local Model = GrabModelFromCollectedFurnitures(Data.ItemName)
	local ItemName = Data.ItemName
	local Position = Data.OffSet + LocalLand.OriginSquare.Position
	game.ReplicatedStorage.PlaceStructure.ClientPlacedStructure:FireServer(ItemName,Position,game.Players.LocalPlayer,false,Model,true)
 
	if SlowMode and (math.random(1,2) ~= 1)then
	RunService.RenderStepped:Wait()
	end
	end
 
	function isValidItem(Model)
	if Model:FindFirstChild("Type") and (Model.Type.Value == "Structure" or Model.Type.Value == "Loose Item" or Model.Type.Value == "Tool" or Model.Type.Value == "Wire" or Model.Type.Value == "Furniture" or Model.Type.Value == "Gift") then
	if (Model.Type.Value == "Structure" or Model.Type.Value == "Wire" or Model.Type.Value == "Furniture") and not Model:FindFirstChild("PurchasedBoxItemName") then
	return false
	end
 
	return true
	elseif not Model:FindFirstChild("Type") then
	if Model:FindFirstChild("ItemName") then
	local ItemName = Model.ItemName.Value:lower()
 
	if ItemName:find("bob") and (ItemName:find("wob") or ItemName:find("head"))then
	return true
	end
	end
	end
	return false
	end
	function itemIsOnLand(Position)
	if (math.abs(Position.X - TargetLand.OriginSquare.Position.X) > 101 or math.abs(Position.Z - TargetLand.OriginSquare.Position.Z) > 101) then
	return false
	end
	for i, Square in pairs(TargetLand:GetChildren()) do
	if Square.Name == "Square" then
	if (math.abs(Position.X - Square.Position.X) < 21 and math.abs(Position.Z - Square.Position.Z) < 21) then
	return true
	end
	end
	end
	return false
	end
 
	if CopyItems then
	for i, Model in pairs(game.Workspace.PlayerModels:GetChildren()) do
	if Model:FindFirstChild("Owner") and Model.Owner.Value == TargetPlayer and isValidItem(Model) then
	local ItemName = Model:FindFirstChild("ItemName") or Model:FindFirstChild("PurchasedBoxItemName")
	local Position = (Model:FindFirstChild("MainCFrame") and Model.MainCFrame.Value or Model.PrimaryPart.CFrame) - TargetLand.OriginSquare.Position
 
	if itemIsOnLand((Model:FindFirstChild("MainCFrame") and Model.MainCFrame.Value or Model.PrimaryPart.CFrame).p) then
	Spawn(ItemName, LocalLand.OriginSquare.CFrame - Vector3.new(0,20,0))
 
	local Data = {}
	Data.ItemName = ItemName.Value
	Data.OffSet = Position
 
	table.insert(CollectedTargetItems, Data)
 
	if SlowMode and (math.random(1,2) ~= 1)then
	RunService.RenderStepped:Wait()
	end
	end
	end
	end
	end
 
	for i, v in pairs(CollectedTargetItems) do
	table.insert(CollectedTargetItemsCopy,v)
	end
 
	function isValidItemModel(Model)
	for i, Data in pairs(CollectedTargetItems) do
	if Data.ItemName == Model.ItemName.Value then
	table.remove(CollectedTargetItems, i)
	return true
	end
	end
	return false
	end
	function itemHasBeenCollected(Model)
	for i, Data in pairs(CollectedLocalItems) do
	if Data.ItemName == Model.ItemName.Value then
	return true
	end
	end
	return false
	end
 
	repeat
	for i, Model in pairs(game.Workspace.PlayerModels:GetChildren()) do
	if Model.Name == "Wire" and Model:FindFirstChild("Owner") and Model.Owner.Value == game.Players.LocalPlayer and (Model.ItemName.Value ~= "Wire" or (Model:FindFirstChild("ItemName") and Model.ItemName.Value == "Wire" and Model:FindFirstChild("PurchasedBoxItemName"))) and isValidItemModel(Model) and not itemHasBeenCollected(Model) then
	table.insert(CollectedLocalItems, Model)
	end
	end
	wait()
	until #CollectedTargetItems == 0
 
	function GrabModelFromCollectedItems(ItemName)
	for i, Model in pairs(CollectedLocalItems) do
	if Model.ItemName.Value == ItemName then
	table.remove(CollectedLocalItems,i)
	return Model
	end
	end
	end
 
	for i, Data in pairs(CollectedTargetItemsCopy) do
	local Model = GrabModelFromCollectedItems(Data.ItemName)
	local ItemName = Data.ItemName
	local Position = Data.OffSet + LocalLand.OriginSquare.Position
 
	if Model:FindFirstChild("PurchasedBoxItemName") then
	game.ReplicatedStorage.PlaceStructure.ClientPlacedStructure:FireServer(false, Position, false, false, Model)
	Model.Parent = nil
	else
	game.ReplicatedStorage.PlaceStructure.ClientPlacedStructure:FireServer(ItemName,Position,game.Players.LocalPlayer,false,Model,true)
	end
 
	if SlowMode and (math.random(1,2) ~= 1)then
	RunService.RenderStepped:Wait()
	end
	end
end)
 
--Blacklist All
 
BlackListAll.MouseButton1Click:Connect(function()
		Client = game.ReplicatedStorage.Interaction.ClientSetListPlayer
	players = game.Players
	for i, v in pairs(players:GetPlayers()) do
	    if v.Name ~= players.LocalPlayer.Name then
	        Client:InvokeServer(players.LocalPlayer.BlacklistFolder, v, true)
	    end
	end
	players.PlayerAdded:connect(function(plr)
	    Client:InvokeServer(players.LocalPlayer.BlacklistFolder, plr, true)
	end)
	end)
 
--Anti Blacklist All
 
AntiBLAll.MouseButton1Click:Connect(function()
	local plr = game.Players.LocalPlayer
	    local cframe
	    for i,v in next, workspace:GetDescendants() do
	        if v:IsA("SpawnLocation") then
	            v.Touched:Connect(function(h)
	            if h.Parent == plr.Character and cframe then
	                plr.Character:SetPrimaryPartCFrame(cframe)
	                end
	            end)
	        end
	    end
 
	    game:GetService("RunService"):BindToRenderStep("NO HACKS",Enum.RenderPriority.Last.Value,function()
	    if game.Players.LocalPlayer.Character.PrimaryPart then
	        cframe = game.Players.LocalPlayer.Character.PrimaryPart.CFrame
	        end
	    end)
 
	    for i,v in next, debug.getregistry() do
	        if type(v)=='function' and debug.getupvalues(v).lastUpdate then
	            debug.setupvalue(v,"lastUpdate",math.huge)
	            break
	        end
	    end
 
	    for i,v in next, workspace.Effects:GetChildren() do
	        if v:IsA("BasePart") and v.Name == "BlacklistWall" then
	            v:Destroy()
	        end
	    end
	end)
 
--Blood
 
Blood.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/jJ48V2yi", true))()
end)
 
--Venyx
 
Venyx.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/guLbXvSu", true))()
end)
 
--Light Lumber
 
LightLumber.MouseButton1Click:Connect(function()
	loadstring(game:GetObjects("rbxassetid://03271460677")[1].Source)()
end)
 
--Ferry
 
Ferry.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/WfpzEV2d", true))()
end)
 
--Bring Up
 
BringUp.MouseButton1Click:Connect(function()
	loadstring(game:GetObjects("rbxassetid://01925396229")[1].Source)()
end)
 
--Johiro Axe Dupe
 
JohiroAxeDupe.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/fmEYwvqn", true))()
end)
end)
 
--Venyx
 
Venyx.MouseButton1Click:Connect(function()
	-- Farewell Infortality.
-- Version: 2.82
-- Instances:
local ScreenGui = Instance.new("ScreenGui")
local Main = Instance.new("Frame")
local FillBox = Instance.new("Frame")
local Frame = Instance.new("Frame")
local Frame_2 = Instance.new("Frame")
local FillAll = Instance.new("TextButton")
local NSP3 = Instance.new("TextButton")
local Wood = Instance.new("TextBox")
local CopyFrame3 = Instance.new("Frame")
local Player666 = Instance.new("TextButton")
local Player555 = Instance.new("TextButton")
local Player333 = Instance.new("TextButton")
local Player444 = Instance.new("TextButton")
local Player111 = Instance.new("TextButton")
local Player222 = Instance.new("TextButton")
local FillClose = Instance.new("TextButton")
local OpGui = Instance.new("TextButton")
local JAMESGUI = Instance.new("TextButton")
local MainC = Instance.new("TextButton")
local Frame_3 = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local Frame_4 = Instance.new("Frame")
local TextLabel_2 = Instance.new("TextLabel")
local HailStone = Instance.new("TextButton")
local TextLabel_3 = Instance.new("TextLabel")
local TextButton = Instance.new("TextButton")
local TextButton_2 = Instance.new("TextButton")
local CLOSE = Instance.new("TextButton")
local FillOpen = Instance.new("TextButton")
local InfoBox = Instance.new("Frame")
local TextLabel_4 = Instance.new("TextLabel")
local TextLabel_5 = Instance.new("TextLabel")
local TextLabel_6 = Instance.new("TextLabel")
local TextLabel_7 = Instance.new("TextLabel")
local TextLabel_8 = Instance.new("TextLabel")
local TextLabel_9 = Instance.new("TextLabel")
local TextLabel_10 = Instance.new("TextLabel")
local TextLabel_11 = Instance.new("TextLabel")
local TextLabel_12 = Instance.new("TextLabel")
local TextLabel_13 = Instance.new("TextLabel")
local CloseInfo = Instance.new("TextButton")
local Info = Instance.new("TextButton")
local MaxLand = Instance.new("TextButton")
local NSP1 = Instance.new("TextButton")
local NSP2 = Instance.new("TextButton")
local CopyFrame2 = Instance.new("Frame")
local Player66 = Instance.new("TextButton")
local Player55 = Instance.new("TextButton")
local Player33 = Instance.new("TextButton")
local Player44 = Instance.new("TextButton")
local Player11 = Instance.new("TextButton")
local Player22 = Instance.new("TextButton")
local CopyFrame1 = Instance.new("Frame")
local Player6 = Instance.new("TextButton")
local Player5 = Instance.new("TextButton")
local Player3 = Instance.new("TextButton")
local Player4 = Instance.new("TextButton")
local Player1 = Instance.new("TextButton")
local Player2 = Instance.new("TextButton")
local OPEN = Instance.new("TextButton")
--Properties:
ScreenGui.Parent = game.CoreGui
Main.Name = "Main"
Main.Parent = ScreenGui
Main.Active = true
Main.BackgroundColor3 = Color3.new(0.4, 0.631373, 1)
Main.Position = UDim2.new(0.293345809, 0, 0.121513948, 0)
Main.Size = UDim2.new(0, 403, 0, 293)
Main.Draggable = true

FillBox.Name = "FillBox"
FillBox.Parent = Main
FillBox.BackgroundColor3 = Color3.new(0.4, 0.631373, 1)
FillBox.BorderColor3 = Color3.new(0.4, 0.631373, 1)
FillBox.Position = UDim2.new(-0.632754326, 0, -0.0102389082, 0)
FillBox.Size = UDim2.new(0, 249, 0, 149)
FillBox.Visible = false

Frame.Parent = FillBox
Frame.BackgroundColor3 = Color3.new(0.419608, 0.227451, 1)
Frame.BorderColor3 = Color3.new(0.419608, 0.227451, 1)
Frame.Size = UDim2.new(0, 248, 0, 13)

Frame_2.Parent = FillBox
Frame_2.BackgroundColor3 = Color3.new(0.419608, 0.227451, 1)
Frame_2.BorderColor3 = Color3.new(0.419608, 0.227451, 1)
Frame_2.Position = UDim2.new(0, 0, 0.910340786, 0)
Frame_2.Size = UDim2.new(0, 249, 0, 13)

FillAll.Name = "FillAll"
FillAll.Parent = Frame_2
FillAll.BackgroundColor3 = Color3.new(0.278431, 0.945098, 0.129412)
FillAll.Position = UDim2.new(0.175740212, 0, -2.71229267, 0)
FillAll.Size = UDim2.new(0, 161, 0, 24)
FillAll.Font = Enum.Font.SourceSans
FillAll.Text = "Fill  All"
FillAll.TextColor3 = Color3.new(0, 0, 0)
FillAll.TextScaled = true
FillAll.TextSize = 14
FillAll.TextWrapped = true

NSP3.Name = "NSP3"
NSP3.Parent = FillBox
NSP3.BackgroundColor3 = Color3.new(1, 0.678431, 0.117647)
NSP3.Position = UDim2.new(0.171724141, 0, 0.222658262, 0)
NSP3.Size = UDim2.new(0, 161, 0, 24)
NSP3.Font = Enum.Font.SourceSans
NSP3.Text = "No Player Selected"
NSP3.TextColor3 = Color3.new(0, 0, 0)
NSP3.TextSize = 14

Wood.Name = "Wood"
Wood.Parent = NSP3
Wood.BackgroundColor3 = Color3.new(0, 1, 1)
Wood.Position = UDim2.new(-0.125021815, 0, 1.35968482, 0)
Wood.Size = UDim2.new(0, 203, 0, 25)
Wood.Font = Enum.Font.SourceSans
Wood.Text = ""
Wood.TextColor3 = Color3.new(0, 0, 0)
Wood.TextSize = 14

CopyFrame3.Name = "CopyFrame3"
CopyFrame3.Parent = FillBox
CopyFrame3.BackgroundColor3 = Color3.new(0.666667, 0, 1)
CopyFrame3.BackgroundTransparency = 0.30000001192093
CopyFrame3.Position = UDim2.new(0.171724126, 0, 0.380056709, 0)
CopyFrame3.Size = UDim2.new(0, 161, 0, 202)
CopyFrame3.Visible = false

Player666.Name = "Player666"
Player666.Parent = CopyFrame3
Player666.BackgroundColor3 = Color3.new(0, 0.921569, 0.921569)
Player666.Position = UDim2.new(0.0426829271, 0, 0.846479356, 0)
Player666.Size = UDim2.new(0, 149, 0, 25)
Player666.Font = Enum.Font.SourceSans
Player666.Text = "> No Player <"
Player666.TextColor3 = Color3.new(0, 0, 0)
Player666.TextSize = 14

Player555.Name = "Player555"
Player555.Parent = CopyFrame3
Player555.BackgroundColor3 = Color3.new(0, 0.921569, 0.921569)
Player555.Position = UDim2.new(0.0426829271, 0, 0.688063502, 0)
Player555.Size = UDim2.new(0, 149, 0, 25)
Player555.Font = Enum.Font.SourceSans
Player555.Text = "> No Player <"
Player555.TextColor3 = Color3.new(0, 0, 0)
Player555.TextSize = 14

Player333.Name = "Player333"
Player333.Parent = CopyFrame3
Player333.BackgroundColor3 = Color3.new(0, 0.921569, 0.921569)
Player333.Position = UDim2.new(0.0426829271, 0, 0.366281331, 0)
Player333.Size = UDim2.new(0, 149, 0, 25)
Player333.Font = Enum.Font.SourceSans
Player333.Text = "> No Player <"
Player333.TextColor3 = Color3.new(0, 0, 0)
Player333.TextSize = 14

Player444.Name = "Player444"
Player444.Parent = CopyFrame3
Player444.BackgroundColor3 = Color3.new(0, 0.921569, 0.921569)
Player444.Position = UDim2.new(0.0426829271, 0, 0.524697185, 0)
Player444.Size = UDim2.new(0, 149, 0, 25)
Player444.Font = Enum.Font.SourceSans
Player444.Text = "> No Player <"
Player444.TextColor3 = Color3.new(0, 0, 0)
Player444.TextSize = 14

Player111.Name = "Player111"
Player111.Parent = CopyFrame3
Player111.BackgroundColor3 = Color3.new(0, 0.921569, 0.921569)
Player111.Position = UDim2.new(0.0426829271, 0, 0.0494496524, 0)
Player111.Size = UDim2.new(0, 149, 0, 25)
Player111.Font = Enum.Font.SourceSans
Player111.Text = "> No Player <"
Player111.TextColor3 = Color3.new(0, 0, 0)
Player111.TextSize = 14

Player222.Name = "Player222"
Player222.Parent = CopyFrame3
Player222.BackgroundColor3 = Color3.new(0, 0.921569, 0.921569)
Player222.Position = UDim2.new(0.0426829271, 0, 0.207865506, 0)
Player222.Size = UDim2.new(0, 149, 0, 25)
Player222.Font = Enum.Font.SourceSans
Player222.Text = "> No Player <"
Player222.TextColor3 = Color3.new(0, 0, 0)
Player222.TextSize = 14

FillClose.Name = "FillClose"
FillClose.Parent = FillBox
FillClose.BackgroundColor3 = Color3.new(0.419608, 0.227451, 1)
FillClose.BorderColor3 = Color3.new(0.419608, 0.227451, 1)
FillClose.Position = UDim2.new(0.931726813, 0, 0, 0)
FillClose.Size = UDim2.new(0, 17, 0, 13)
FillClose.Font = Enum.Font.SourceSans
FillClose.Text = "X"
FillClose.TextColor3 = Color3.new(0, 0, 0)
FillClose.TextScaled = true
FillClose.TextSize = 14
FillClose.TextWrapped = true

OpGui.Name = "OpGui"
OpGui.Parent = Main
OpGui.BackgroundColor3 = Color3.new(0.0666667, 1, 0.172549)
OpGui.Position = UDim2.new(0.0372208394, 0, 0.209523812, 0)
OpGui.Size = UDim2.new(0, 102, 0, 27)
OpGui.Font = Enum.Font.Fantasy
OpGui.Text = "OP LT2 GUI"
OpGui.TextColor3 = Color3.new(0, 0, 0)
OpGui.TextScaled = true
OpGui.TextSize = 14
OpGui.TextWrapped = true

JAMESGUI.Name = "JAMESGUI"
JAMESGUI.Parent = Main
JAMESGUI.BackgroundColor3 = Color3.new(0.0666667, 1, 0.172549)
JAMESGUI.Position = UDim2.new(0.372208416, 0, 0.214285716, 0)
JAMESGUI.Size = UDim2.new(0, 102, 0, 27)
JAMESGUI.Font = Enum.Font.Fantasy
JAMESGUI.Text = "James"
JAMESGUI.TextColor3 = Color3.new(0, 0, 0)
JAMESGUI.TextScaled = true
JAMESGUI.TextSize = 14
JAMESGUI.TextWrapped = true

MainC.Name = "MainC"
MainC.Parent = Main
MainC.BackgroundColor3 = Color3.new(0.0666667, 1, 0.172549)
MainC.Position = UDim2.new(0.245657563, 0, 0.404599428, 0)
MainC.Size = UDim2.new(0, 202, 0, 37)
MainC.Font = Enum.Font.Fantasy
MainC.Text = "Copy"
MainC.TextColor3 = Color3.new(0, 0, 0)
MainC.TextScaled = true
MainC.TextSize = 14
MainC.TextWrapped = true

Frame_3.Parent = MainC
Frame_3.BackgroundColor3 = Color3.new(0.419608, 0.227451, 1)
Frame_3.Position = UDim2.new(-0.490099013, 0, -3.24791622, 0)
Frame_3.Size = UDim2.new(0, 403, 0, 33)

TextLabel.Parent = Frame_3
TextLabel.BackgroundColor3 = Color3.new(0.419608, 0.227451, 1)
TextLabel.BorderColor3 = Color3.new(0.419608, 0.227451, 1)
TextLabel.Position = UDim2.new(0.189181656, 0, 0.0939255357, 0)
TextLabel.Size = UDim2.new(0, 248, 0, 27)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Extreme Lumber Tycoon 2 V2"
TextLabel.TextColor3 = Color3.new(0, 0, 0)
TextLabel.TextScaled = true
TextLabel.TextSize = 14
TextLabel.TextWrapped = true

Frame_4.Parent = Frame_3
Frame_4.BackgroundColor3 = Color3.new(0.419608, 0.227451, 1)
Frame_4.Position = UDim2.new(0, 0, 8.11529732, 0)
Frame_4.Size = UDim2.new(0, 403, 0, 33)

TextLabel_2.Parent = MainC
TextLabel_2.BackgroundColor3 = Color3.new(0.419608, 0.227451, 1)
TextLabel_2.BorderColor3 = Color3.new(0.419608, 0.227451, 1)
TextLabel_2.Position = UDim2.new(-0.0644482896, 0, 4.0603466, 0)
TextLabel_2.Size = UDim2.new(0, 247, 0, 27)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "By MichaelJacksonOffice"
TextLabel_2.TextColor3 = Color3.new(0, 0, 0)
TextLabel_2.TextScaled = true
TextLabel_2.TextSize = 14
TextLabel_2.TextWrapped = true

HailStone.Name = "HailStone"
HailStone.Parent = Main
HailStone.BackgroundColor3 = Color3.new(0.0666667, 1, 0.172549)
HailStone.Position = UDim2.new(0.712158799, 0, 0.209523812, 0)
HailStone.Size = UDim2.new(0, 102, 0, 27)
HailStone.Font = Enum.Font.Fantasy
HailStone.Text = "HailStone"
HailStone.TextColor3 = Color3.new(0, 0, 0)
HailStone.TextScaled = true
HailStone.TextSize = 14
HailStone.TextWrapped = true

TextLabel_3.Parent = Main
TextLabel_3.BackgroundColor3 = Color3.new(0.4, 0.631373, 1)
TextLabel_3.BorderColor3 = Color3.new(0.4, 0.631373, 1)
TextLabel_3.Position = UDim2.new(0.48563993, 0, 0.565880775, 0)
TextLabel_3.Size = UDim2.new(0, 29, 0, 24)
TextLabel_3.Font = Enum.Font.SourceSans
TextLabel_3.Text = "To"
TextLabel_3.TextColor3 = Color3.new(0, 0, 0)
TextLabel_3.TextSize = 14

TextButton.Parent = Main
TextButton.BackgroundColor3 = Color3.new(1, 0.133333, 0.133333)
TextButton.Position = UDim2.new(0.0198511165, 0, 0.347456515, 0)
TextButton.Size = UDim2.new(0, 78, 0, 49)
TextButton.Font = Enum.Font.ArialBold
TextButton.Text = "Wipe(BP)"
TextButton.TextColor3 = Color3.new(0, 0, 0)
TextButton.TextScaled = true
TextButton.TextSize = 14
TextButton.TextWrapped = true

TextButton_2.Parent = Main
TextButton_2.BackgroundColor3 = Color3.new(1, 0.133333, 0.133333)
TextButton_2.Position = UDim2.new(0.784119129, 0, 0.333170831, 0)
TextButton_2.Size = UDim2.new(0, 78, 0, 49)
TextButton_2.Font = Enum.Font.Arial
TextButton_2.Text = "Paint"
TextButton_2.TextColor3 = Color3.new(0, 0, 0)
TextButton_2.TextScaled = true
TextButton_2.TextSize = 14
TextButton_2.TextWrapped = true

CLOSE.Name = "CLOSE"
CLOSE.Parent = Main
CLOSE.BackgroundColor3 = Color3.new(0.419608, 0.227451, 1)
CLOSE.BorderColor3 = Color3.new(0.419608, 0.227451, 1)
CLOSE.Position = UDim2.new(0.913858354, 0, 0.00521722436, 0)
CLOSE.Size = UDim2.new(0, 28, 0, 27)
CLOSE.Font = Enum.Font.SourceSans
CLOSE.Text = "x"
CLOSE.TextColor3 = Color3.new(0, 0, 0)
CLOSE.TextScaled = true
CLOSE.TextSize = 14
CLOSE.TextWrapped = true

FillOpen.Name = "FillOpen"
FillOpen.Parent = Main
FillOpen.BackgroundColor3 = Color3.new(0.0666667, 1, 0.172549)
FillOpen.Position = UDim2.new(0.245657563, 0, 0.677636981, 0)
FillOpen.Size = UDim2.new(0, 202, 0, 37)
FillOpen.Font = Enum.Font.Fantasy
FillOpen.Text = "Fill Menu"
FillOpen.TextColor3 = Color3.new(0, 0, 0)
FillOpen.TextScaled = true
FillOpen.TextSize = 14
FillOpen.TextWrapped = true

InfoBox.Name = "InfoBox"
InfoBox.Parent = Main
InfoBox.BackgroundColor3 = Color3.new(0.72549, 0.278431, 1)
InfoBox.BackgroundTransparency = 0.5
InfoBox.Position = UDim2.new(1, 0, -0.00682593836, 0)
InfoBox.Size = UDim2.new(0, 157, 0, 295)
InfoBox.Visible = false

TextLabel_4.Parent = InfoBox
TextLabel_4.Active = true
TextLabel_4.BackgroundColor3 = Color3.new(0.352941, 0.807843, 1)
TextLabel_4.BackgroundTransparency = 0.30000001192093
TextLabel_4.Position = UDim2.new(0.0191082805, 0, 0.0135593219, 0)
TextLabel_4.Size = UDim2.new(0, 148, 0, 26)
TextLabel_4.Font = Enum.Font.SourceSans
TextLabel_4.Text = "You Should Click"
TextLabel_4.TextColor3 = Color3.new(0, 0, 0)
TextLabel_4.TextSize = 14

TextLabel_5.Parent = InfoBox
TextLabel_5.Active = true
TextLabel_5.BackgroundColor3 = Color3.new(0.352941, 0.807843, 1)
TextLabel_5.BackgroundTransparency = 0.30000001192093
TextLabel_5.Position = UDim2.new(0.0191082805, 0, 0.101694919, 0)
TextLabel_5.Size = UDim2.new(0, 148, 0, 26)
TextLabel_5.Font = Enum.Font.SourceSans
TextLabel_5.Text = "No Selected Plr to Select"
TextLabel_5.TextColor3 = Color3.new(0, 0, 0)
TextLabel_5.TextSize = 14

TextLabel_6.Parent = InfoBox
TextLabel_6.Active = true
TextLabel_6.BackgroundColor3 = Color3.new(1, 0.235294, 0.0823529)
TextLabel_6.BackgroundTransparency = 0.30000001192093
TextLabel_6.Position = UDim2.new(0.0191082805, 0, 0.21355933, 0)
TextLabel_6.Size = UDim2.new(0, 148, 0, 26)
TextLabel_6.Font = Enum.Font.SourceSans
TextLabel_6.Text = "Wood Type:"
TextLabel_6.TextColor3 = Color3.new(0, 0, 0)
TextLabel_6.TextSize = 14

TextLabel_7.Parent = InfoBox
TextLabel_7.Active = true
TextLabel_7.BackgroundColor3 = Color3.new(0.352941, 0.807843, 1)
TextLabel_7.BackgroundTransparency = 0.30000001192093
TextLabel_7.Position = UDim2.new(0.0192202423, 0, 0.345905989, 0)
TextLabel_7.Size = UDim2.new(0, 151, 0, 22)
TextLabel_7.Font = Enum.Font.SourceSans
TextLabel_7.Text = "Spooky / SpookyNeon"
TextLabel_7.TextColor3 = Color3.new(0, 0, 0)
TextLabel_7.TextSize = 14

TextLabel_8.Parent = InfoBox
TextLabel_8.Active = true
TextLabel_8.BackgroundColor3 = Color3.new(0.352941, 0.807843, 1)
TextLabel_8.BackgroundTransparency = 0.30000001192093
TextLabel_8.Position = UDim2.new(0.0192202423, 0, 0.441283882, 0)
TextLabel_8.Size = UDim2.new(0, 151, 0, 22)
TextLabel_8.Font = Enum.Font.SourceSans
TextLabel_8.Text = "LoneCave/CaveCrawler"
TextLabel_8.TextColor3 = Color3.new(0, 0, 0)
TextLabel_8.TextSize = 14

TextLabel_9.Parent = InfoBox
TextLabel_9.Active = true
TextLabel_9.BackgroundColor3 = Color3.new(0.352941, 0.807843, 1)
TextLabel_9.BackgroundTransparency = 0.30000001192093
TextLabel_9.Position = UDim2.new(0.0192202423, 0, 0.53330493, 0)
TextLabel_9.Size = UDim2.new(0, 151, 0, 22)
TextLabel_9.Font = Enum.Font.SourceSans
TextLabel_9.Text = "nil/Walnut"
TextLabel_9.TextColor3 = Color3.new(0, 0, 0)
TextLabel_9.TextSize = 14

TextLabel_10.Parent = InfoBox
TextLabel_10.Active = true
TextLabel_10.BackgroundColor3 = Color3.new(0.352941, 0.807843, 1)
TextLabel_10.BackgroundTransparency = 0.30000001192093
TextLabel_10.Position = UDim2.new(0.0258027092, 0, 0.628682792, 0)
TextLabel_10.Size = UDim2.new(0, 151, 0, 22)
TextLabel_10.Font = Enum.Font.SourceSans
TextLabel_10.Text = "Generic"
TextLabel_10.TextColor3 = Color3.new(0, 0, 0)
TextLabel_10.TextScaled = true
TextLabel_10.TextSize = 14
TextLabel_10.TextWrapped = true

TextLabel_11.Parent = InfoBox
TextLabel_11.Active = true
TextLabel_11.BackgroundColor3 = Color3.new(0.352941, 0.807843, 1)
TextLabel_11.BackgroundTransparency = 0.30000001192093
TextLabel_11.Position = UDim2.new(0.0258027092, 0, 0.721744418, 0)
TextLabel_11.Size = UDim2.new(0, 151, 0, 22)
TextLabel_11.Font = Enum.Font.SourceSans
TextLabel_11.Text = "Frost/SnowGlow"
TextLabel_11.TextColor3 = Color3.new(0, 0, 0)
TextLabel_11.TextSize = 14

TextLabel_12.Parent = InfoBox
TextLabel_12.Active = true
TextLabel_12.BackgroundColor3 = Color3.new(0.352941, 0.807843, 1)
TextLabel_12.BackgroundTransparency = 0.30000001192093
TextLabel_12.Position = UDim2.new(0.0189999994, 0, 0.82099998, 0)
TextLabel_12.Size = UDim2.new(0, 151, 0, 22)
TextLabel_12.Font = Enum.Font.SourceSans
TextLabel_12.Text = "GenericSpecial/GoldSwampy"
TextLabel_12.TextColor3 = Color3.new(0, 0, 0)
TextLabel_12.TextSize = 14

TextLabel_13.Parent = InfoBox
TextLabel_13.Active = true
TextLabel_13.BackgroundColor3 = Color3.new(0.352941, 0.807843, 1)
TextLabel_13.BackgroundTransparency = 0.30000001192093
TextLabel_13.Position = UDim2.new(0.0258027092, 0, 0.922815382, 0)
TextLabel_13.Size = UDim2.new(0, 151, 0, 22)
TextLabel_13.Font = Enum.Font.SourceSans
TextLabel_13.Text = "Birch/Green Swampy"
TextLabel_13.TextColor3 = Color3.new(0, 0, 0)
TextLabel_13.TextSize = 14

CloseInfo.Name = "CloseInfo"
CloseInfo.Parent = InfoBox
CloseInfo.BackgroundColor3 = Color3.new(1, 0.117647, 0.129412)
CloseInfo.BackgroundTransparency = 0.30000001192093
CloseInfo.Position = UDim2.new(1, 0, 0, 0)
CloseInfo.Size = UDim2.new(0, 33, 0, 30)
CloseInfo.Font = Enum.Font.SourceSans
CloseInfo.Text = "X"
CloseInfo.TextColor3 = Color3.new(0, 0, 0)
CloseInfo.TextScaled = true
CloseInfo.TextSize = 14
CloseInfo.TextWrapped = true

Info.Name = "Info"
Info.Parent = Main
Info.BackgroundColor3 = Color3.new(0.0666667, 1, 0.172549)
Info.Position = UDim2.new(0.801488876, 0, 0.698114812, 0)
Info.Size = UDim2.new(0, 64, 0, 31)
Info.Font = Enum.Font.Fantasy
Info.Text = "Info/GetBP"
Info.TextColor3 = Color3.new(0, 0, 0)
Info.TextScaled = true
Info.TextSize = 14
Info.TextWrapped = true

MaxLand.Name = "MaxLand"
MaxLand.Parent = Main
MaxLand.BackgroundColor3 = Color3.new(0.0666667, 1, 0.172549)
MaxLand.Position = UDim2.new(0.0372208953, 0, 0.698114812, 0)
MaxLand.Size = UDim2.new(0, 64, 0, 31)
MaxLand.Font = Enum.Font.Fantasy
MaxLand.Text = "Max Land"
MaxLand.TextColor3 = Color3.new(0, 0, 0)
MaxLand.TextScaled = true
MaxLand.TextSize = 14
MaxLand.TextWrapped = true

NSP1.Name = "NSP1"
NSP1.Parent = Main
NSP1.BackgroundColor3 = Color3.new(1, 0.678431, 0.117647)
NSP1.Position = UDim2.new(0.0372209176, 0, 0.564882994, 0)
NSP1.Size = UDim2.new(0, 161, 0, 24)
NSP1.Font = Enum.Font.SourceSans
NSP1.Text = "No Player Selected"
NSP1.TextColor3 = Color3.new(0, 0, 0)
NSP1.TextSize = 14

NSP2.Name = "NSP2"
NSP2.Parent = Main
NSP2.BackgroundColor3 = Color3.new(1, 0.678431, 0.117647)
NSP2.Position = UDim2.new(0.575682402, 0, 0.562958896, 0)
NSP2.Size = UDim2.new(0, 160, 0, 24)
NSP2.Font = Enum.Font.SourceSans
NSP2.Text = "No Player Selected"
NSP2.TextColor3 = Color3.new(0, 0, 0)
NSP2.TextSize = 14

CopyFrame2.Name = "CopyFrame2"
CopyFrame2.Parent = Main
CopyFrame2.BackgroundColor3 = Color3.new(0.666667, 0, 1)
CopyFrame2.BackgroundTransparency = 0.30000001192093
CopyFrame2.Position = UDim2.new(0.575077534, 0, 0.647365212, 0)
CopyFrame2.Size = UDim2.new(0, 160, 0, 202)
CopyFrame2.Visible = false

Player66.Name = "Player66"
Player66.Parent = CopyFrame2
Player66.BackgroundColor3 = Color3.new(0, 0.921569, 0.921569)
Player66.Position = UDim2.new(0.0426829271, 0, 0.846479356, 0)
Player66.Size = UDim2.new(0, 149, 0, 25)
Player66.Font = Enum.Font.SourceSans
Player66.Text = "> No Player <"
Player66.TextColor3 = Color3.new(0, 0, 0)
Player66.TextSize = 14

Player55.Name = "Player55"
Player55.Parent = CopyFrame2
Player55.BackgroundColor3 = Color3.new(0, 0.921569, 0.921569)
Player55.Position = UDim2.new(0.0426829271, 0, 0.688063502, 0)
Player55.Size = UDim2.new(0, 149, 0, 25)
Player55.Font = Enum.Font.SourceSans
Player55.Text = "> No Player <"
Player55.TextColor3 = Color3.new(0, 0, 0)
Player55.TextSize = 14

Player33.Name = "Player33"
Player33.Parent = CopyFrame2
Player33.BackgroundColor3 = Color3.new(0, 0.921569, 0.921569)
Player33.Position = UDim2.new(0.0426829271, 0, 0.366281331, 0)
Player33.Size = UDim2.new(0, 149, 0, 25)
Player33.Font = Enum.Font.SourceSans
Player33.Text = "> No Player <"
Player33.TextColor3 = Color3.new(0, 0, 0)
Player33.TextSize = 14

Player44.Name = "Player44"
Player44.Parent = CopyFrame2
Player44.BackgroundColor3 = Color3.new(0, 0.921569, 0.921569)
Player44.Position = UDim2.new(0.0426829271, 0, 0.524697185, 0)
Player44.Size = UDim2.new(0, 149, 0, 25)
Player44.Font = Enum.Font.SourceSans
Player44.Text = "> No Player <"
Player44.TextColor3 = Color3.new(0, 0, 0)
Player44.TextSize = 14

Player11.Name = "Player11"
Player11.Parent = CopyFrame2
Player11.BackgroundColor3 = Color3.new(0, 0.921569, 0.921569)
Player11.Position = UDim2.new(0.0426829271, 0, 0.0494496524, 0)
Player11.Size = UDim2.new(0, 149, 0, 25)
Player11.Font = Enum.Font.SourceSans
Player11.Text = "> No Player <"
Player11.TextColor3 = Color3.new(0, 0, 0)
Player11.TextSize = 14

Player22.Name = "Player22"
Player22.Parent = CopyFrame2
Player22.BackgroundColor3 = Color3.new(0, 0.921569, 0.921569)
Player22.Position = UDim2.new(0.0426829271, 0, 0.207865506, 0)
Player22.Size = UDim2.new(0, 149, 0, 25)
Player22.Font = Enum.Font.SourceSans
Player22.Text = "> No Player <"
Player22.TextColor3 = Color3.new(0, 0, 0)
Player22.TextSize = 14

CopyFrame1.Name = "CopyFrame1"
CopyFrame1.Parent = Main
CopyFrame1.BackgroundColor3 = Color3.new(0.666667, 0, 1)
CopyFrame1.BackgroundTransparency = 0.30000001192093
CopyFrame1.Position = UDim2.new(0.0371746495, 0, 0.647792041, 0)
CopyFrame1.Size = UDim2.new(0, 161, 0, 201)
CopyFrame1.Visible = false

Player6.Name = "Player6"
Player6.Parent = CopyFrame1
Player6.BackgroundColor3 = Color3.new(0, 0.921569, 0.921569)
Player6.Position = UDim2.new(0.0426829271, 0, 0.846479356, 0)
Player6.Size = UDim2.new(0, 149, 0, 25)
Player6.Font = Enum.Font.SourceSans
Player6.Text = "> No Player <"
Player6.TextColor3 = Color3.new(0, 0, 0)
Player6.TextSize = 14

Player5.Name = "Player5"
Player5.Parent = CopyFrame1
Player5.BackgroundColor3 = Color3.new(0, 0.921569, 0.921569)
Player5.Position = UDim2.new(0.0426829271, 0, 0.688063502, 0)
Player5.Size = UDim2.new(0, 149, 0, 25)
Player5.Font = Enum.Font.SourceSans
Player5.Text = "> No Player <"
Player5.TextColor3 = Color3.new(0, 0, 0)
Player5.TextSize = 14

Player3.Name = "Player3"
Player3.Parent = CopyFrame1
Player3.BackgroundColor3 = Color3.new(0, 0.921569, 0.921569)
Player3.Position = UDim2.new(0.0426829271, 0, 0.366281331, 0)
Player3.Size = UDim2.new(0, 149, 0, 25)
Player3.Font = Enum.Font.SourceSans
Player3.Text = "> No Player <"
Player3.TextColor3 = Color3.new(0, 0, 0)
Player3.TextSize = 14

Player4.Name = "Player4"
Player4.Parent = CopyFrame1
Player4.BackgroundColor3 = Color3.new(0, 0.921569, 0.921569)
Player4.Position = UDim2.new(0.0426829271, 0, 0.524697185, 0)
Player4.Size = UDim2.new(0, 149, 0, 25)
Player4.Font = Enum.Font.SourceSans
Player4.Text = "> No Player <"
Player4.TextColor3 = Color3.new(0, 0, 0)
Player4.TextSize = 14

Player1.Name = "Player1"
Player1.Parent = CopyFrame1
Player1.BackgroundColor3 = Color3.new(0, 0.921569, 0.921569)
Player1.Position = UDim2.new(0.0426829271, 0, 0.0494496524, 0)
Player1.Size = UDim2.new(0, 149, 0, 25)
Player1.Font = Enum.Font.SourceSans
Player1.Text = "> No Player <"
Player1.TextColor3 = Color3.new(0, 0, 0)
Player1.TextSize = 14

Player2.Name = "Player2"
Player2.Parent = CopyFrame1
Player2.BackgroundColor3 = Color3.new(0, 0.921569, 0.921569)
Player2.Position = UDim2.new(0.0426829271, 0, 0.207865506, 0)
Player2.Size = UDim2.new(0, 149, 0, 25)
Player2.Font = Enum.Font.SourceSans
Player2.Text = "> No Player <"
Player2.TextColor3 = Color3.new(0, 0, 0)
Player2.TextSize = 14

OPEN.Name = "OPEN"
OPEN.Parent = ScreenGui
OPEN.BackgroundColor3 = Color3.new(0.470588, 0.0392157, 0.901961)
OPEN.BorderColor3 = Color3.new(0.756863, 0.176471, 0.262745)
OPEN.Position = UDim2.new(0.916588545, 0, 0.802788854, 0)
OPEN.Size = UDim2.new(0, 89, 0, 25)
OPEN.Visible = false
OPEN.Font = Enum.Font.SourceSans
OPEN.Text = "OPEN"
OPEN.TextColor3 = Color3.new(0, 0, 0)
OPEN.TextSize = 14

FillOpen.MouseButton1Down:Connect(function()
FillBox.Visible = true
end)

FillClose.MouseButton1Down:Connect(function()
FillBox.Visible = false
end)

OPEN.MouseButton1Down:Connect(function()
Main.Visible = true
OPEN.Visible = false
end)

CLOSE.MouseButton1Down:Connect(function()
Main.Visible = false
OPEN.Visible = true
end)

Info.MouseButton1Down:Connect(function()
InfoBox.Visible = true
for i,v in pairs(game.ReplicatedStorage.Purchasables.Structures.BlueprintStructures:GetChildren()) do
local clone = v:Clone()
clone.Parent = game.Players.LocalPlayer.PlayerBlueprints.Blueprints
end
end)

CloseInfo.MouseButton1Down:Connect(function()
InfoBox.Visible = false
end)

NSP1.MouseButton1Down:Connect(function()
CopyFrame1.Visible = true
end)
NSP2.MouseButton1Down:Connect(function()
CopyFrame2.Visible = true
end)
NSP3.MouseButton1Down:connect(function()
CopyFrame3.Visible = true
end)
Player1.MouseButton1Down:connect(function()
    NSP1.Text = Player1.Text
CopyFrame1.Visible = false
end)
 
Player2.MouseButton1Down:connect(function()
    NSP1.Text = Player2.Text
CopyFrame1.Visible = false
end)
 
Player3.MouseButton1Down:connect(function()
    NSP1.Text = Player3.Text
CopyFrame1.Visible = false
end)
 
Player4.MouseButton1Down:connect(function()
    NSP1.Text = Player4.Text
CopyFrame1.Visible = false
end)
 
Player5.MouseButton1Down:connect(function()
    NSP1.Text = Player5.Text
CopyFrame1.Visible = false
end)
 
Player6.MouseButton1Down:connect(function()
    NSP1.Text = Player6.Text
CopyFrame1.Visible = false
end)
 
Player11.MouseButton1Down:connect(function()
    NSP2.Text = Player11.Text
CopyFrame2.Visible = false
end)
 
Player22.MouseButton1Down:connect(function()
    NSP2.Text = Player22.Text
CopyFrame2.Visible = false
end)
 
Player33.MouseButton1Down:connect(function()
    NSP2.Text = Player33.Text
CopyFrame2.Visible = false
end)
 
Player44.MouseButton1Down:connect(function()
    NSP2.Text = Player44.Text
CopyFrame2.Visible = false
end)
 
Player55.MouseButton1Down:connect(function()
    NSP2.Text = Player55.Text
CopyFrame2.Visible = false
end)
 
Player66.MouseButton1Down:connect(function()
    NSP2.Text = Player66.Text
CopyFrame2.Visible = false
end)

Player111.MouseButton1Down:connect(function()
    NSP3.Text = Player111.Text
CopyFrame3.Visible = false
end)
 
Player222.MouseButton1Down:connect(function()
    NSP3.Text = Player222.Text
CopyFrame3.Visible = false
end)
 
Player333.MouseButton1Down:connect(function()
    NSP3.Text = Player333.Text
CopyFrame3.Visible = false
end)
 
Player444.MouseButton1Down:connect(function()
    NSP3.Text = Player444.Text
CopyFrame3.Visible = false
end)

Player555.MouseButton1Down:connect(function()
    NSP3.Text = Player555.Text
CopyFrame3.Visible = false
end)
 
Player666.MouseButton1Down:connect(function()
    NSP3.Text = Player666.Text
CopyFrame3.Visible = false
end)

local buttons = { Player1, Player2, Player3, Player4, Player5, Player6 }

local buttons1 = { Player11, Player22, Player33, Player44, Player55, Player66 }

local buttons2 = { Player111, Player222, Player333, Player444, Player555, Player666 }

for i,v in pairs(game.Players:GetChildren()) do
    buttons[i].Text = v.Name
end

for i,v in pairs(game.Players:GetChildren()) do
    buttons1[i].Text = v.Name
end

for i,v in pairs(game.Players:GetChildren()) do
    buttons2[i].Text = v.Name
end

game.Players.PlayerAdded:connect(function()
    for i,v in pairs(game.Players:GetChildren()) do
        buttons[i].Text = v.Name
    end
end)

game.Players.PlayerAdded:connect(function()
    for i,v in pairs(game.Players:GetChildren()) do
        buttons1[i].Text = v.Name
    end
end)

game.Players.PlayerAdded:connect(function()
    for i,v in pairs(game.Players:GetChildren()) do
        buttons2[i].Text = v.Name
    end
end)



HailStone.MouseButton1Down:Connect(function()
-- Objects

local Hailstone = Instance.new("ScreenGui")
local OpenBtn = Instance.new("TextButton")
local Drag = Instance.new("Frame")
local AAPressQ = Instance.new("TextLabel")
local AnimWelcomeScreen = Instance.new("Frame")
local ImageLabel = Instance.new("ImageLabel")
local Main = Instance.new("Frame")
local HomeLocal = Instance.new("TextButton")
local HomeTopBar = Instance.new("TextButton")
local HomePlayers = Instance.new("TextButton")
local HomeTeleports = Instance.new("TextButton")
local HomeWood = Instance.new("TextButton")
local HomeTools = Instance.new("TextButton")
local HomeChangelog = Instance.new("TextButton")
local HomeLogo = Instance.new("ImageLabel")
local HiName = Instance.new("TextLabel")
local HomeSepBar = Instance.new("TextButton")
local X = Instance.new("TextButton")
local WoodScreen = Instance.new("Frame")
local TeleportCutWood = Instance.new("TextButton")
local SellCutWood = Instance.new("TextButton")
local TeleportEndTimesWood = Instance.new("TextButton")
local TeleportCaveCrawlerWood = Instance.new("TextButton")
local TeleportGifts = Instance.new("TextButton")
local ToolsScreen = Instance.new("Frame")
local Dupe = Instance.new("TextButton")
local Move = Instance.new("TextButton")
local GoldAxe = Instance.new("TextButton")
local LeakedItems = Instance.new("TextButton")
local TeleportTool = Instance.new("TextButton")
local GreyWood = Instance.new("TextButton")
local DupeLabel = Instance.new("TextLabel")
local TeleportsScreen = Instance.new("Frame")
local Spawn = Instance.new("TextButton")
local Den = Instance.new("TextButton")
local StrangeMan = Instance.new("TextButton")
local Swamp = Instance.new("TextButton")
local Fancy = Instance.new("TextButton")
local BoxedCars = Instance.new("TextButton")
local Dropoff = Instance.new("TextButton")
local GreenBox = Instance.new("TextButton")
local Cave = Instance.new("TextButton")
local Palm = Instance.new("TextButton")
local WoodRUs = Instance.new("TextButton")
local LinksLogic = Instance.new("TextButton")
local YourPlot = Instance.new("TextButton")
local BobsShack = Instance.new("TextButton")
local EndTimes = Instance.new("TextButton")
local Volcano = Instance.new("TextButton")
local Lodge = Instance.new("TextButton")
local Shrine = Instance.new("TextButton")
local PlayersScreen = Instance.new("Frame")
local P1 = Instance.new("TextButton")
local P2 = Instance.new("TextButton")
local P4 = Instance.new("TextButton")
local P3 = Instance.new("TextButton")
local P6 = Instance.new("TextButton")
local P5 = Instance.new("TextButton")
local TpToPlayer = Instance.new("TextButton")
local TpToPlayerBase = Instance.new("TextButton")
local PSelected = Instance.new("TextLabel")
local LocalScreen = Instance.new("Frame")
local God = Instance.new("TextButton")
local Noclip = Instance.new("TextButton")
local Walkspeed = Instance.new("TextButton")
local Jumppower = Instance.new("TextButton")
local NoclipLabel = Instance.new("TextLabel")
local WalkspeedValue = Instance.new("TextBox")
local JumppowerValue = Instance.new("TextBox")
local EtoFly = Instance.new("TextLabel")
local HomeScreen = Instance.new("Frame")
local WelcomeName = Instance.new("TextLabel")
local WelcomeMOTD = Instance.new("TextLabel")
local WelcomeAuthor = Instance.new("TextLabel")
local ChangelogScreen = Instance.new("Frame")
local Logs = Instance.new("TextLabel")
local Logs2 = Instance.new("TextLabel")
local Logs3 = Instance.new("TextLabel")
local Log1and2Div = Instance.new("TextButton")
local Log2and3Div = Instance.new("TextButton")

-- Properties

Hailstone.Name = "Hailstone"
Hailstone.Parent = game.CoreGui
Hailstone.ResetOnSpawn = false

OpenBtn.Name = "OpenBtn"
OpenBtn.Parent = Hailstone
OpenBtn.BackgroundColor3 = Color3.new(0.105882, 0.164706, 0.207843)
OpenBtn.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
OpenBtn.BorderSizePixel = 3
OpenBtn.Position = UDim2.new(0, 0, 0.826086938, 0)
OpenBtn.Size = UDim2.new(0, 79, 0, 23)
OpenBtn.Visible = false
OpenBtn.Font = Enum.Font.SourceSans
OpenBtn.Text = "Open"
OpenBtn.TextColor3 = Color3.new(0.117647, 0.501961, 0.639216)
OpenBtn.TextSize = 14
OpenBtn.TextWrapped = true

Drag.Name = "Drag"
Drag.Parent = Hailstone
Drag.Active = true
Drag.BackgroundColor3 = Color3.new(1, 1, 1)
Drag.BackgroundTransparency = 1
Drag.BorderSizePixel = 0
Drag.Draggable = true
Drag.Position = UDim2.new(0.373752683, 0, 0.267786592, 0)
Drag.Selectable = true
Drag.Size = UDim2.new(0, 451, 0, 234)

AAPressQ.Name = "AAPressQ"
AAPressQ.Parent = Hailstone
AAPressQ.BackgroundColor3 = Color3.new(1, 1, 1)
AAPressQ.BackgroundTransparency = 1
AAPressQ.BorderSizePixel = 0
AAPressQ.Position = UDim2.new(0.283759117, 0, 0.252964437, 0)
AAPressQ.Size = UDim2.new(0, 573, 0, 257)
AAPressQ.Font = Enum.Font.SourceSans
AAPressQ.Text = "Press \"Q\""
AAPressQ.TextSize = 100

AnimWelcomeScreen.Name = "AnimWelcomeScreen"
AnimWelcomeScreen.Parent = Drag
AnimWelcomeScreen.BackgroundColor3 = Color3.new(0.105882, 0.164706, 0.207843)
AnimWelcomeScreen.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
AnimWelcomeScreen.BorderSizePixel = 3
AnimWelcomeScreen.Position = UDim2.new(0.328511298, 0, -0.20692715, 0)
AnimWelcomeScreen.Size = UDim2.new(0, 209, 0, 199)
AnimWelcomeScreen.Visible = false

ImageLabel.Parent = AnimWelcomeScreen
ImageLabel.BackgroundColor3 = Color3.new(1, 1, 1)
ImageLabel.BackgroundTransparency = 1
ImageLabel.BorderSizePixel = 0
ImageLabel.Size = UDim2.new(0, 209, 0, 199)
ImageLabel.Image = "rbxassetid://1393851029"

Main.Name = "Main"
Main.Parent = Drag
Main.BackgroundColor3 = Color3.new(0.105882, 0.164706, 0.207843)
Main.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Main.BorderSizePixel = 3
Main.Position = UDim2.new(-0.00221729279, 0, 0.0128205121, 0)
Main.Size = UDim2.new(0, 450, 0, 232)
Main.Visible = false

HomeLocal.Name = "HomeLocal"
HomeLocal.Parent = Main
HomeLocal.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
HomeLocal.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
HomeLocal.BorderSizePixel = 2
HomeLocal.Position = UDim2.new(0.0244444441, 0, 0.206896558, 0)
HomeLocal.Size = UDim2.new(0, 84, 0, 21)
HomeLocal.Font = Enum.Font.SourceSans
HomeLocal.Text = "Local"
HomeLocal.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
HomeLocal.TextSize = 24
HomeLocal.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

HomeTopBar.Name = "HomeTopBar"
HomeTopBar.Parent = Main
HomeTopBar.BackgroundColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
HomeTopBar.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
HomeTopBar.Position = UDim2.new(0, 0, 0.159482777, 0)
HomeTopBar.Size = UDim2.new(0, 450, 0, 1)
HomeTopBar.Font = Enum.Font.SourceSans
HomeTopBar.Text = ""
HomeTopBar.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
HomeTopBar.TextSize = 24
HomeTopBar.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

HomePlayers.Name = "HomePlayers"
HomePlayers.Parent = Main
HomePlayers.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
HomePlayers.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
HomePlayers.BorderSizePixel = 2
HomePlayers.Position = UDim2.new(0.0244444441, 0, 0.331896544, 0)
HomePlayers.Size = UDim2.new(0, 84, 0, 21)
HomePlayers.Font = Enum.Font.SourceSans
HomePlayers.Text = "Players"
HomePlayers.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
HomePlayers.TextSize = 24
HomePlayers.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

HomeTeleports.Name = "HomeTeleports"
HomeTeleports.Parent = Main
HomeTeleports.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
HomeTeleports.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
HomeTeleports.BorderSizePixel = 2
HomeTeleports.Position = UDim2.new(0.0244444441, 0, 0.459051698, 0)
HomeTeleports.Size = UDim2.new(0, 84, 0, 21)
HomeTeleports.Font = Enum.Font.SourceSans
HomeTeleports.Text = "Teleports"
HomeTeleports.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
HomeTeleports.TextSize = 24
HomeTeleports.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

HomeWood.Name = "HomeWood"
HomeWood.Parent = Main
HomeWood.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
HomeWood.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
HomeWood.BorderSizePixel = 2
HomeWood.Position = UDim2.new(0.0244444441, 0, 0.594827592, 0)
HomeWood.Size = UDim2.new(0, 84, 0, 21)
HomeWood.Font = Enum.Font.SourceSans
HomeWood.Text = "Wood"
HomeWood.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
HomeWood.TextSize = 24
HomeWood.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

HomeTools.Name = "HomeTools"
HomeTools.Parent = Main
HomeTools.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
HomeTools.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
HomeTools.BorderSizePixel = 2
HomeTools.Position = UDim2.new(0.0244444441, 0, 0.732758641, 0)
HomeTools.Size = UDim2.new(0, 84, 0, 21)
HomeTools.Font = Enum.Font.SourceSans
HomeTools.Text = "Tools"
HomeTools.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
HomeTools.TextSize = 24
HomeTools.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

HomeChangelog.Name = "HomeChangelog"
HomeChangelog.Parent = Main
HomeChangelog.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
HomeChangelog.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
HomeChangelog.BorderSizePixel = 2
HomeChangelog.Position = UDim2.new(0.0244444441, 0, 0.875, 0)
HomeChangelog.Size = UDim2.new(0, 84, 0, 21)
HomeChangelog.Font = Enum.Font.SourceSans
HomeChangelog.Text = "Changelog"
HomeChangelog.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
HomeChangelog.TextSize = 22
HomeChangelog.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

HomeLogo.Name = "HomeLogo"
HomeLogo.Parent = Main
HomeLogo.BackgroundColor3 = Color3.new(1, 1, 1)
HomeLogo.BackgroundTransparency = 1
HomeLogo.BorderSizePixel = 0
HomeLogo.Position = UDim2.new(0.456999987, 0, -0.11896389, 0)
HomeLogo.Size = UDim2.new(0, 156, 0, 99)
HomeLogo.Image = "rbxassetid://1393851029"

HiName.Name = "HiName"
HiName.Parent = Main
HiName.BackgroundColor3 = Color3.new(1, 1, 1)
HiName.BackgroundTransparency = 1
HiName.BorderSizePixel = 0
HiName.Position = UDim2.new(0.0244444441, 0, 0.0258620698, 0)
HiName.Size = UDim2.new(0, 189, 0, 25)
HiName.Font = Enum.Font.SourceSans
HiName.Text = "Hi"
HiName.TextColor3 = Color3.new(0.117647, 0.501961, 0.639216)
HiName.TextScaled = true
HiName.TextSize = 14
HiName.TextStrokeColor3 = Color3.new(0.000153787, 0.000246059, 0.000322953)
HiName.TextStrokeTransparency = 0.64899998903275
HiName.TextWrapped = true
HiName.TextXAlignment = Enum.TextXAlignment.Left

HomeSepBar.Name = "HomeSepBar"
HomeSepBar.Parent = Main
HomeSepBar.BackgroundColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
HomeSepBar.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
HomeSepBar.Position = UDim2.new(0.24888888, 0, 0.206896558, 0)
HomeSepBar.Size = UDim2.new(0, 1, 0, 176)
HomeSepBar.Font = Enum.Font.SourceSans
HomeSepBar.Text = ""
HomeSepBar.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
HomeSepBar.TextSize = 24
HomeSepBar.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

X.Name = "X"
X.Parent = Main
X.BackgroundColor3 = Color3.new(1, 1, 1)
X.BackgroundTransparency = 1
X.BorderSizePixel = 0
X.Position = UDim2.new(0.937777758, 0, 0, 0)
X.Size = UDim2.new(0, 28, 0, 25)
X.Font = Enum.Font.SourceSans
X.Text = "X"
X.TextColor3 = Color3.new(0.117647, 0.501961, 0.639216)
X.TextScaled = true
X.TextSize = 14
X.TextWrapped = true

WoodScreen.Name = "WoodScreen"
WoodScreen.Parent = Drag
WoodScreen.BackgroundColor3 = Color3.new(0.105882, 0.164706, 0.207843)
WoodScreen.BackgroundTransparency = 1
WoodScreen.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
WoodScreen.BorderSizePixel = 0
WoodScreen.Draggable = true
WoodScreen.Position = UDim2.new(0.0164813697, 0, -0.000777035952, 0)
WoodScreen.Size = UDim2.new(0, 444, 0, 230)
WoodScreen.Visible = false

TeleportCutWood.Name = "Teleport Cut Wood"
TeleportCutWood.Parent = WoodScreen
TeleportCutWood.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
TeleportCutWood.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
TeleportCutWood.BorderSizePixel = 2
TeleportCutWood.Position = UDim2.new(0.457207203, 0, 0.226086959, 0)
TeleportCutWood.Size = UDim2.new(0, 147, 0, 21)
TeleportCutWood.Font = Enum.Font.SourceSans
TeleportCutWood.Text = "Teleport Cut Wood"
TeleportCutWood.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
TeleportCutWood.TextScaled = true
TeleportCutWood.TextSize = 24
TeleportCutWood.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
TeleportCutWood.TextWrapped = true

SellCutWood.Name = "Sell Cut Wood"
SellCutWood.Parent = WoodScreen
SellCutWood.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
SellCutWood.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
SellCutWood.BorderSizePixel = 2
SellCutWood.Position = UDim2.new(0.457207203, 0, 0.391304344, 0)
SellCutWood.Size = UDim2.new(0, 147, 0, 21)
SellCutWood.Font = Enum.Font.SourceSans
SellCutWood.Text = "Sell Cut Wood"
SellCutWood.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
SellCutWood.TextSize = 24
SellCutWood.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

TeleportEndTimesWood.Name = "Teleport End Times Wood"
TeleportEndTimesWood.Parent = WoodScreen
TeleportEndTimesWood.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
TeleportEndTimesWood.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
TeleportEndTimesWood.BorderSizePixel = 2
TeleportEndTimesWood.Position = UDim2.new(0.457207203, 0, 0.556521714, 0)
TeleportEndTimesWood.Size = UDim2.new(0, 147, 0, 21)
TeleportEndTimesWood.Font = Enum.Font.SourceSans
TeleportEndTimesWood.Text = "Teleport End Times"
TeleportEndTimesWood.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
TeleportEndTimesWood.TextScaled = true
TeleportEndTimesWood.TextSize = 24
TeleportEndTimesWood.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
TeleportEndTimesWood.TextWrapped = true

TeleportCaveCrawlerWood.Name = "Teleport Cave Crawler Wood"
TeleportCaveCrawlerWood.Parent = WoodScreen
TeleportCaveCrawlerWood.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
TeleportCaveCrawlerWood.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
TeleportCaveCrawlerWood.BorderSizePixel = 2
TeleportCaveCrawlerWood.Position = UDim2.new(0.457207203, 0, 0.70869565, 0)
TeleportCaveCrawlerWood.Size = UDim2.new(0, 147, 0, 21)
TeleportCaveCrawlerWood.Font = Enum.Font.SourceSans
TeleportCaveCrawlerWood.Text = "Teleport Cave Crawler"
TeleportCaveCrawlerWood.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
TeleportCaveCrawlerWood.TextScaled = true
TeleportCaveCrawlerWood.TextSize = 24
TeleportCaveCrawlerWood.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
TeleportCaveCrawlerWood.TextWrapped = true

TeleportGifts.Name = "Teleport Gifts"
TeleportGifts.Parent = WoodScreen
TeleportGifts.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
TeleportGifts.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
TeleportGifts.BorderSizePixel = 2
TeleportGifts.Position = UDim2.new(0.456081063, 0, 0.869565248, 0)
TeleportGifts.Size = UDim2.new(0, 147, 0, 21)
TeleportGifts.Font = Enum.Font.SourceSans
TeleportGifts.Text = "Teleport Gifts"
TeleportGifts.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
TeleportGifts.TextScaled = true
TeleportGifts.TextSize = 24
TeleportGifts.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
TeleportGifts.TextWrapped = true

ToolsScreen.Name = "ToolsScreen"
ToolsScreen.Parent = Drag
ToolsScreen.BackgroundColor3 = Color3.new(0.105882, 0.164706, 0.207843)
ToolsScreen.BackgroundTransparency = 1
ToolsScreen.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
ToolsScreen.BorderSizePixel = 0
ToolsScreen.Draggable = true
ToolsScreen.Position = UDim2.new(0.0164813697, 0, -0.000777035952, 0)
ToolsScreen.Size = UDim2.new(0, 444, 0, 230)
ToolsScreen.Visible = false

Dupe.Name = "Dupe"
Dupe.Parent = ToolsScreen
Dupe.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
Dupe.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Dupe.BorderSizePixel = 2
Dupe.Position = UDim2.new(0.457207203, 0, 0.199999988, 0)
Dupe.Size = UDim2.new(0, 147, 0, 20)
Dupe.Font = Enum.Font.SourceSans
Dupe.Text = "Duplication"
Dupe.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Dupe.TextScaled = true
Dupe.TextSize = 24
Dupe.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Dupe.TextWrapped = true

Move.Name = "Move"
Move.Parent = ToolsScreen
Move.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
Move.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Move.BorderSizePixel = 2
Move.Position = UDim2.new(0.457207203, 0, 0.347826093, 0)
Move.Size = UDim2.new(0, 147, 0, 20)
Move.Font = Enum.Font.SourceSans
Move.Text = "Hard Dragger"
Move.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Move.TextScaled = true
Move.TextSize = 24
Move.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Move.TextWrapped = true

GoldAxe.Name = "Gold Axe"
GoldAxe.Parent = ToolsScreen
GoldAxe.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
GoldAxe.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
GoldAxe.BorderSizePixel = 2
GoldAxe.Position = UDim2.new(0.457207233, 0, 0.478260875, 0)
GoldAxe.Size = UDim2.new(0, 147, 0, 20)
GoldAxe.Font = Enum.Font.SourceSans
GoldAxe.Text = "Golden Axe"
GoldAxe.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
GoldAxe.TextScaled = true
GoldAxe.TextSize = 24
GoldAxe.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
GoldAxe.TextWrapped = true

LeakedItems.Name = "Leaked Items"
LeakedItems.Parent = ToolsScreen
LeakedItems.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
LeakedItems.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
LeakedItems.BorderSizePixel = 2
LeakedItems.Position = UDim2.new(0.456081092, 0, 0.617391288, 0)
LeakedItems.Size = UDim2.new(0, 147, 0, 20)
LeakedItems.Font = Enum.Font.SourceSans
LeakedItems.Text = "Leaked Items"
LeakedItems.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
LeakedItems.TextScaled = true
LeakedItems.TextSize = 24
LeakedItems.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
LeakedItems.TextWrapped = true

TeleportTool.Name = "Teleport Tool"
TeleportTool.Parent = ToolsScreen
TeleportTool.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
TeleportTool.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
TeleportTool.BorderSizePixel = 2
TeleportTool.Position = UDim2.new(0.456081092, 0, 0.756521761, 0)
TeleportTool.Size = UDim2.new(0, 147, 0, 20)
TeleportTool.Font = Enum.Font.SourceSans
TeleportTool.Text = "Ctrl + Click TP"
TeleportTool.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
TeleportTool.TextScaled = true
TeleportTool.TextSize = 24
TeleportTool.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
TeleportTool.TextWrapped = true

GreyWood.Name = "Grey Wood"
GreyWood.Parent = ToolsScreen
GreyWood.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
GreyWood.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
GreyWood.BorderSizePixel = 2
GreyWood.Position = UDim2.new(0.456081092, 0, 0.900000036, 0)
GreyWood.Size = UDim2.new(0, 147, 0, 20)
GreyWood.Font = Enum.Font.SourceSans
GreyWood.Text = "Grey Wood"
GreyWood.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
GreyWood.TextScaled = true
GreyWood.TextSize = 24
GreyWood.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
GreyWood.TextWrapped = true

DupeLabel.Name = "DupeLabel"
DupeLabel.Parent = ToolsScreen
DupeLabel.BackgroundColor3 = Color3.new(1, 1, 1)
DupeLabel.BackgroundTransparency = 1
DupeLabel.BorderColor3 = Color3.new(0.666667, 0, 0)
DupeLabel.BorderSizePixel = 0
DupeLabel.Position = UDim2.new(0.493243247, 0, 0.286956519, 0)
DupeLabel.Size = UDim2.new(0, 115, 0, 14)
DupeLabel.Font = Enum.Font.SciFi
DupeLabel.Text = "Disabled"
DupeLabel.TextColor3 = Color3.new(0.666667, 0, 0)
DupeLabel.TextSize = 14

TeleportsScreen.Name = "TeleportsScreen"
TeleportsScreen.Parent = Drag
TeleportsScreen.BackgroundColor3 = Color3.new(0.105882, 0.164706, 0.207843)
TeleportsScreen.BackgroundTransparency = 1
TeleportsScreen.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
TeleportsScreen.BorderSizePixel = 0
TeleportsScreen.Draggable = true
TeleportsScreen.Position = UDim2.new(0.0164813697, 0, -0.000777035952, 0)
TeleportsScreen.Size = UDim2.new(0, 444, 0, 230)
TeleportsScreen.Visible = false

Spawn.Name = "Spawn"
Spawn.Parent = TeleportsScreen
Spawn.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
Spawn.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Spawn.BorderSizePixel = 2
Spawn.Position = UDim2.new(0.290540546, 0, 0.226086959, 0)
Spawn.Size = UDim2.new(0, 84, 0, 21)
Spawn.Font = Enum.Font.SourceSans
Spawn.Text = "Spawn"
Spawn.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Spawn.TextSize = 24
Spawn.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Spawn.TextWrapped = true

Den.Name = "Den"
Den.Parent = TeleportsScreen
Den.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
Den.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Den.BorderSizePixel = 2
Den.Position = UDim2.new(0.290540546, 0, 0.352173924, 0)
Den.Size = UDim2.new(0, 84, 0, 21)
Den.Font = Enum.Font.SourceSans
Den.Text = "The Den"
Den.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Den.TextSize = 24
Den.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Den.TextWrapped = true

StrangeMan.Name = "Strange Man"
StrangeMan.Parent = TeleportsScreen
StrangeMan.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
StrangeMan.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
StrangeMan.BorderSizePixel = 2
StrangeMan.Position = UDim2.new(0.290540546, 0, 0.482608676, 0)
StrangeMan.Size = UDim2.new(0, 84, 0, 21)
StrangeMan.Font = Enum.Font.SourceSans
StrangeMan.Text = "Strange Man"
StrangeMan.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
StrangeMan.TextScaled = true
StrangeMan.TextSize = 24
StrangeMan.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
StrangeMan.TextWrapped = true

Swamp.Name = "Swamp"
Swamp.Parent = TeleportsScreen
Swamp.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
Swamp.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Swamp.BorderSizePixel = 2
Swamp.Position = UDim2.new(0.290540546, 0, 0.617391288, 0)
Swamp.Size = UDim2.new(0, 84, 0, 21)
Swamp.Font = Enum.Font.SourceSans
Swamp.Text = "Swamp"
Swamp.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Swamp.TextSize = 24
Swamp.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Swamp.TextWrapped = true

Fancy.Name = "Fancy"
Fancy.Parent = TeleportsScreen
Fancy.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
Fancy.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Fancy.BorderSizePixel = 2
Fancy.Position = UDim2.new(0.290540546, 0, 0.747826099, 0)
Fancy.Size = UDim2.new(0, 84, 0, 21)
Fancy.Font = Enum.Font.SourceSans
Fancy.Text = "Fancy"
Fancy.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Fancy.TextSize = 24
Fancy.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Fancy.TextWrapped = true

BoxedCars.Name = "Boxed Cars"
BoxedCars.Parent = TeleportsScreen
BoxedCars.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
BoxedCars.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
BoxedCars.BorderSizePixel = 2
BoxedCars.Position = UDim2.new(0.290540546, 0, 0.87391305, 0)
BoxedCars.Size = UDim2.new(0, 84, 0, 21)
BoxedCars.Font = Enum.Font.SourceSans
BoxedCars.Text = "Boxed Cars"
BoxedCars.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
BoxedCars.TextScaled = true
BoxedCars.TextSize = 24
BoxedCars.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
BoxedCars.TextWrapped = true

Dropoff.Name = "Dropoff"
Dropoff.Parent = TeleportsScreen
Dropoff.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
Dropoff.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Dropoff.BorderSizePixel = 2
Dropoff.Position = UDim2.new(0.538288295, 0, 0.226086959, 0)
Dropoff.Size = UDim2.new(0, 84, 0, 21)
Dropoff.Font = Enum.Font.SourceSans
Dropoff.Text = "Dropoff"
Dropoff.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Dropoff.TextSize = 24
Dropoff.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Dropoff.TextWrapped = true

GreenBox.Name = "Green Box"
GreenBox.Parent = TeleportsScreen
GreenBox.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
GreenBox.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
GreenBox.BorderSizePixel = 2
GreenBox.Position = UDim2.new(0.538288295, 0, 0.352173924, 0)
GreenBox.Size = UDim2.new(0, 84, 0, 21)
GreenBox.Font = Enum.Font.SourceSans
GreenBox.Text = "Green Box"
GreenBox.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
GreenBox.TextScaled = true
GreenBox.TextSize = 24
GreenBox.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
GreenBox.TextWrapped = true

Cave.Name = "Cave"
Cave.Parent = TeleportsScreen
Cave.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
Cave.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Cave.BorderSizePixel = 2
Cave.Position = UDim2.new(0.538288295, 0, 0.482608676, 0)
Cave.Size = UDim2.new(0, 84, 0, 21)
Cave.Font = Enum.Font.SourceSans
Cave.Text = "Cave"
Cave.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Cave.TextSize = 24
Cave.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Cave.TextWrapped = true

Palm.Name = "Palm"
Palm.Parent = TeleportsScreen
Palm.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
Palm.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Palm.BorderSizePixel = 2
Palm.Position = UDim2.new(0.538288295, 0, 0.617391288, 0)
Palm.Size = UDim2.new(0, 84, 0, 21)
Palm.Font = Enum.Font.SourceSans
Palm.Text = "Palm"
Palm.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Palm.TextSize = 24
Palm.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Palm.TextWrapped = true

WoodRUs.Name = "Wood R Us"
WoodRUs.Parent = TeleportsScreen
WoodRUs.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
WoodRUs.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
WoodRUs.BorderSizePixel = 2
WoodRUs.Position = UDim2.new(0.538288295, 0, 0.747826099, 0)
WoodRUs.Size = UDim2.new(0, 84, 0, 21)
WoodRUs.Font = Enum.Font.SourceSans
WoodRUs.Text = "Wood R Us"
WoodRUs.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
WoodRUs.TextScaled = true
WoodRUs.TextSize = 24
WoodRUs.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
WoodRUs.TextWrapped = true

LinksLogic.Name = "Links Logic"
LinksLogic.Parent = TeleportsScreen
LinksLogic.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
LinksLogic.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
LinksLogic.BorderSizePixel = 2
LinksLogic.Position = UDim2.new(0.538288295, 0, 0.87391305, 0)
LinksLogic.Size = UDim2.new(0, 84, 0, 21)
LinksLogic.Font = Enum.Font.SourceSans
LinksLogic.Text = "Link's Logic"
LinksLogic.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
LinksLogic.TextScaled = true
LinksLogic.TextSize = 24
LinksLogic.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
LinksLogic.TextWrapped = true

YourPlot.Name = "Your Plot"
YourPlot.Parent = TeleportsScreen
YourPlot.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
YourPlot.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
YourPlot.BorderSizePixel = 2
YourPlot.Position = UDim2.new(0.77477479, 0, 0.87391305, 0)
YourPlot.Size = UDim2.new(0, 84, 0, 21)
YourPlot.Font = Enum.Font.SourceSans
YourPlot.Text = "Your Plot"
YourPlot.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
YourPlot.TextSize = 24
YourPlot.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
YourPlot.TextWrapped = true

BobsShack.Name = "Bobs Shack"
BobsShack.Parent = TeleportsScreen
BobsShack.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
BobsShack.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
BobsShack.BorderSizePixel = 2
BobsShack.Position = UDim2.new(0.77477479, 0, 0.747826099, 0)
BobsShack.Size = UDim2.new(0, 84, 0, 21)
BobsShack.Font = Enum.Font.SourceSans
BobsShack.Text = "Bob's Shack"
BobsShack.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
BobsShack.TextScaled = true
BobsShack.TextSize = 24
BobsShack.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
BobsShack.TextWrapped = true

EndTimes.Name = "End Times"
EndTimes.Parent = TeleportsScreen
EndTimes.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
EndTimes.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
EndTimes.BorderSizePixel = 2
EndTimes.Position = UDim2.new(0.77477479, 0, 0.617391288, 0)
EndTimes.Size = UDim2.new(0, 84, 0, 21)
EndTimes.Font = Enum.Font.SourceSans
EndTimes.Text = "End Times"
EndTimes.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
EndTimes.TextScaled = true
EndTimes.TextSize = 24
EndTimes.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
EndTimes.TextWrapped = true

Volcano.Name = "Volcano"
Volcano.Parent = TeleportsScreen
Volcano.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
Volcano.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Volcano.BorderSizePixel = 2
Volcano.Position = UDim2.new(0.77477479, 0, 0.482608676, 0)
Volcano.Size = UDim2.new(0, 84, 0, 21)
Volcano.Font = Enum.Font.SourceSans
Volcano.Text = "Volcano"
Volcano.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Volcano.TextSize = 24
Volcano.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Volcano.TextWrapped = true

Lodge.Name = "Lodge"
Lodge.Parent = TeleportsScreen
Lodge.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
Lodge.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Lodge.BorderSizePixel = 2
Lodge.Position = UDim2.new(0.77477479, 0, 0.352173924, 0)
Lodge.Size = UDim2.new(0, 84, 0, 21)
Lodge.Font = Enum.Font.SourceSans
Lodge.Text = "Lodge"
Lodge.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Lodge.TextSize = 24
Lodge.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Lodge.TextWrapped = true

Shrine.Name = "Shrine"
Shrine.Parent = TeleportsScreen
Shrine.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
Shrine.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Shrine.BorderSizePixel = 2
Shrine.Position = UDim2.new(0.77477479, 0, 0.226086959, 0)
Shrine.Size = UDim2.new(0, 84, 0, 21)
Shrine.Font = Enum.Font.SourceSans
Shrine.Text = "Shrine"
Shrine.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Shrine.TextSize = 24
Shrine.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Shrine.TextWrapped = true

PlayersScreen.Name = "PlayersScreen"
PlayersScreen.Parent = Drag
PlayersScreen.BackgroundColor3 = Color3.new(0.105882, 0.164706, 0.207843)
PlayersScreen.BackgroundTransparency = 1
PlayersScreen.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
PlayersScreen.BorderSizePixel = 0
PlayersScreen.Draggable = true
PlayersScreen.Position = UDim2.new(0.0164813697, 0, -0.000777035952, 0)
PlayersScreen.Size = UDim2.new(0, 444, 0, 230)
PlayersScreen.Visible = false

P1.Name = "P1"
P1.Parent = PlayersScreen
P1.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
P1.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
P1.BorderSizePixel = 2
P1.Position = UDim2.new(0.272522509, 0, 0.226086959, 0)
P1.Size = UDim2.new(0, 147, 0, 21)
P1.Font = Enum.Font.SourceSans
P1.Text = " "
P1.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
P1.TextSize = 24
P1.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

P2.Name = "P2"
P2.Parent = PlayersScreen
P2.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
P2.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
P2.BorderSizePixel = 2
P2.Position = UDim2.new(0.628378332, 0, 0.226086974, 0)
P2.Size = UDim2.new(0, 158, 0, 21)
P2.Font = Enum.Font.SourceSans
P2.Text = " "
P2.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
P2.TextSize = 24
P2.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

P4.Name = "P4"
P4.Parent = PlayersScreen
P4.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
P4.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
P4.BorderSizePixel = 2
P4.Position = UDim2.new(0.628378332, 0, 0.352173924, 0)
P4.Size = UDim2.new(0, 158, 0, 21)
P4.Font = Enum.Font.SourceSans
P4.Text = " "
P4.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
P4.TextSize = 24
P4.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

P3.Name = "P3"
P3.Parent = PlayersScreen
P3.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
P3.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
P3.BorderSizePixel = 2
P3.Position = UDim2.new(0.272522509, 0, 0.352173924, 0)
P3.Size = UDim2.new(0, 147, 0, 21)
P3.Font = Enum.Font.SourceSans
P3.Text = " "
P3.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
P3.TextSize = 24
P3.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

P6.Name = "P6"
P6.Parent = PlayersScreen
P6.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
P6.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
P6.BorderSizePixel = 2
P6.Position = UDim2.new(0.628378332, 0, 0.482608706, 0)
P6.Size = UDim2.new(0, 158, 0, 21)
P6.Font = Enum.Font.SourceSans
P6.Text = ""
P6.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
P6.TextSize = 24
P6.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

P5.Name = "P5"
P5.Parent = PlayersScreen
P5.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
P5.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
P5.BorderSizePixel = 2
P5.Position = UDim2.new(0.272522509, 0, 0.482608706, 0)
P5.Size = UDim2.new(0, 147, 0, 21)
P5.Font = Enum.Font.SourceSans
P5.Text = " "
P5.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
P5.TextSize = 24
P5.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

TpToPlayer.Name = "TpToPlayer"
TpToPlayer.Parent = PlayersScreen
TpToPlayer.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
TpToPlayer.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
TpToPlayer.BorderSizePixel = 2
TpToPlayer.Position = UDim2.new(0.405405402, 0, 0.656521738, 0)
TpToPlayer.Size = UDim2.new(0, 179, 0, 21)
TpToPlayer.Font = Enum.Font.SourceSans
TpToPlayer.Text = "Teleport To Player"
TpToPlayer.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
TpToPlayer.TextSize = 24
TpToPlayer.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

TpToPlayerBase.Name = "TpToPlayerBase"
TpToPlayerBase.Parent = PlayersScreen
TpToPlayerBase.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
TpToPlayerBase.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
TpToPlayerBase.BorderSizePixel = 2
TpToPlayerBase.Position = UDim2.new(0.405405402, 0, 0.813043475, 0)
TpToPlayerBase.Size = UDim2.new(0, 179, 0, 21)
TpToPlayerBase.Font = Enum.Font.SourceSans
TpToPlayerBase.Text = "Teleport To Base"
TpToPlayerBase.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
TpToPlayerBase.TextSize = 24
TpToPlayerBase.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

PSelected.Name = "PSelected"
PSelected.Parent = PlayersScreen
PSelected.BackgroundColor3 = Color3.new(1, 1, 1)
PSelected.BackgroundTransparency = 1
PSelected.BorderSizePixel = 0
PSelected.Position = UDim2.new(0.405405402, 0, 0.904347837, 0)
PSelected.Size = UDim2.new(0, 179, 0, 22)
PSelected.Font = Enum.Font.SourceSans
PSelected.Text = ""
PSelected.TextColor3 = Color3.new(0.117647, 0.501961, 0.639216)
PSelected.TextSize = 20

LocalScreen.Name = "LocalScreen"
LocalScreen.Parent = Drag
LocalScreen.BackgroundColor3 = Color3.new(0.105882, 0.164706, 0.207843)
LocalScreen.BackgroundTransparency = 1
LocalScreen.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
LocalScreen.BorderSizePixel = 0
LocalScreen.Draggable = true
LocalScreen.Position = UDim2.new(0.0164813697, 0, -0.000777035952, 0)
LocalScreen.Size = UDim2.new(0, 444, 0, 230)
LocalScreen.Visible = false

God.Name = "God"
God.Parent = LocalScreen
God.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
God.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
God.BorderSizePixel = 2
God.Position = UDim2.new(0.457207203, 0, 0.226086944, 0)
God.Size = UDim2.new(0, 158, 0, 21)
God.Font = Enum.Font.SourceSans
God.Text = "God"
God.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
God.TextSize = 24
God.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

Noclip.Name = "Noclip"
Noclip.Parent = LocalScreen
Noclip.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
Noclip.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Noclip.BorderSizePixel = 2
Noclip.Position = UDim2.new(0.457207203, 0, 0.352173924, 0)
Noclip.Size = UDim2.new(0, 158, 0, 21)
Noclip.Font = Enum.Font.SourceSans
Noclip.Text = "Noclip"
Noclip.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Noclip.TextSize = 24
Noclip.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

Walkspeed.Name = "Walkspeed"
Walkspeed.Parent = LocalScreen
Walkspeed.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
Walkspeed.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Walkspeed.BorderSizePixel = 2
Walkspeed.Position = UDim2.new(0.457207203, 0, 0.523913026, 0)
Walkspeed.Size = UDim2.new(0, 158, 0, 21)
Walkspeed.Font = Enum.Font.SourceSans
Walkspeed.Text = "Walkspeed"
Walkspeed.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Walkspeed.TextSize = 24
Walkspeed.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

Jumppower.Name = "Jumppower"
Jumppower.Parent = LocalScreen
Jumppower.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
Jumppower.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Jumppower.BorderSizePixel = 2
Jumppower.Position = UDim2.new(0.457207203, 0, 0.70869565, 0)
Jumppower.Size = UDim2.new(0, 158, 0, 21)
Jumppower.Font = Enum.Font.SourceSans
Jumppower.Text = "Jumppower"
Jumppower.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Jumppower.TextSize = 24
Jumppower.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

NoclipLabel.Name = "NoclipLabel"
NoclipLabel.Parent = LocalScreen
NoclipLabel.BackgroundColor3 = Color3.new(1, 1, 1)
NoclipLabel.BackgroundTransparency = 1
NoclipLabel.BorderColor3 = Color3.new(0.666667, 0, 0)
NoclipLabel.BorderSizePixel = 0
NoclipLabel.Position = UDim2.new(0.504504502, 0, 0.443478256, 0)
NoclipLabel.Size = UDim2.new(0, 115, 0, 19)
NoclipLabel.Font = Enum.Font.SciFi
NoclipLabel.Text = "Disabled"
NoclipLabel.TextColor3 = Color3.new(0.666667, 0, 0)
NoclipLabel.TextSize = 14

WalkspeedValue.Name = "WalkspeedValue"
WalkspeedValue.Parent = LocalScreen
WalkspeedValue.BackgroundColor3 = Color3.new(1, 1, 1)
WalkspeedValue.BackgroundTransparency = 1
WalkspeedValue.BorderSizePixel = 0
WalkspeedValue.Position = UDim2.new(0.457207203, 0, 0.617391288, 0)
WalkspeedValue.Size = UDim2.new(0, 158, 0, 21)
WalkspeedValue.Font = Enum.Font.SourceSans
WalkspeedValue.Text = "Walkspeed Value"
WalkspeedValue.TextColor3 = Color3.new(0.117647, 0.501961, 0.639216)
WalkspeedValue.TextSize = 14

JumppowerValue.Name = "JumppowerValue"
JumppowerValue.Parent = LocalScreen
JumppowerValue.BackgroundColor3 = Color3.new(1, 1, 1)
JumppowerValue.BackgroundTransparency = 1
JumppowerValue.BorderSizePixel = 0
JumppowerValue.Position = UDim2.new(0.457207203, 0, 0.799999952, 0)
JumppowerValue.Size = UDim2.new(0, 158, 0, 21)
JumppowerValue.Font = Enum.Font.SourceSans
JumppowerValue.Text = "Jumppower Value"
JumppowerValue.TextColor3 = Color3.new(0.117647, 0.501961, 0.639216)
JumppowerValue.TextSize = 14

EtoFly.Name = "EtoFly"
EtoFly.Parent = LocalScreen
EtoFly.BackgroundColor3 = Color3.new(1, 1, 1)
EtoFly.BackgroundTransparency = 1
EtoFly.BorderSizePixel = 0
EtoFly.Position = UDim2.new(0.409909904, 0, 0.895652175, 0)
EtoFly.Size = UDim2.new(0, 200, 0, 29)
EtoFly.Font = Enum.Font.SourceSans
EtoFly.Text = "Press \"Q\" to Fly"
EtoFly.TextColor3 = Color3.new(0.117647, 0.501961, 0.639216)
EtoFly.TextSize = 14

HomeScreen.Name = "HomeScreen"
HomeScreen.Parent = Drag
HomeScreen.BackgroundColor3 = Color3.new(1, 1, 1)
HomeScreen.BackgroundTransparency = 1
HomeScreen.BorderSizePixel = 0
HomeScreen.Position = UDim2.new(-0.208425716, 0, -0.273504287, 0)
HomeScreen.Size = UDim2.new(0, 450, 0, 232)
HomeScreen.Visible = false

WelcomeName.Name = "WelcomeName"
WelcomeName.Parent = HomeScreen
WelcomeName.BackgroundColor3 = Color3.new(1, 1, 1)
WelcomeName.BackgroundTransparency = 1
WelcomeName.BorderSizePixel = 0
WelcomeName.Position = UDim2.new(0.512882888, 0, 0.402361304, 0)
WelcomeName.Size = UDim2.new(0, 295, 0, 50)
WelcomeName.Font = Enum.Font.SourceSans
WelcomeName.Text = "Welcome"
WelcomeName.TextColor3 = Color3.new(0.117647, 0.501961, 0.639216)
WelcomeName.TextSize = 26
WelcomeName.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
WelcomeName.TextStrokeTransparency = 0.64999997615814
WelcomeName.TextWrapped = true

WelcomeMOTD.Name = "WelcomeMOTD"
WelcomeMOTD.Parent = HomeScreen
WelcomeMOTD.BackgroundColor3 = Color3.new(1, 1, 1)
WelcomeMOTD.BackgroundTransparency = 1
WelcomeMOTD.Position = UDim2.new(0.524598598, 0, 0.615812302, 0)
WelcomeMOTD.Size = UDim2.new(0, 295, 0, 122)
WelcomeMOTD.Font = Enum.Font.SourceSans
WelcomeMOTD.Text = "I heard there are a lot of wild haxors on the lose. Be careful out there."
WelcomeMOTD.TextColor3 = Color3.new(0.117647, 0.501961, 0.639216)
WelcomeMOTD.TextSize = 30
WelcomeMOTD.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
WelcomeMOTD.TextStrokeTransparency = 0.64999997615814
WelcomeMOTD.TextWrapped = true

WelcomeAuthor.Name = "WelcomeAuthor"
WelcomeAuthor.Parent = HomeScreen
WelcomeAuthor.BackgroundColor3 = Color3.new(1, 1, 1)
WelcomeAuthor.BackgroundTransparency = 1
WelcomeAuthor.BorderSizePixel = 0
WelcomeAuthor.Position = UDim2.new(0.621117353, 0, 1.14139926, 0)
WelcomeAuthor.Size = UDim2.new(0, 200, 0, 22)
WelcomeAuthor.Font = Enum.Font.SourceSans
WelcomeAuthor.Text = "By Casual#2435"
WelcomeAuthor.TextColor3 = Color3.new(0.117647, 0.501961, 0.639216)
WelcomeAuthor.TextSize = 12
WelcomeAuthor.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
WelcomeAuthor.TextStrokeTransparency = 0.64999997615814
WelcomeAuthor.TextWrapped = true

ChangelogScreen.Name = "ChangelogScreen"
ChangelogScreen.Parent = Drag
ChangelogScreen.BackgroundColor3 = Color3.new(1, 1, 1)
ChangelogScreen.BackgroundTransparency = 1
ChangelogScreen.BorderSizePixel = 0
ChangelogScreen.Position = UDim2.new(0.24833703, 0, 0.17521368, 0)
ChangelogScreen.Size = UDim2.new(0, 337, 0, 193)
ChangelogScreen.Visible = false

Logs.Name = "Logs"
Logs.Parent = ChangelogScreen
Logs.BackgroundColor3 = Color3.new(1, 1, 1)
Logs.BackgroundTransparency = 1
Logs.BorderSizePixel = 0
Logs.Position = UDim2.new(0.0207715146, 0, 0, 0)
Logs.Size = UDim2.new(0, 322, 0, 39)
Logs.Font = Enum.Font.SourceSans
Logs.Text = "-1.0 Huge Improvement on Look of Gui"
Logs.TextColor3 = Color3.new(0.117647, 0.501961, 0.639216)
Logs.TextSize = 20

Logs2.Name = "Logs2"
Logs2.Parent = ChangelogScreen
Logs2.BackgroundColor3 = Color3.new(1, 1, 1)
Logs2.BackgroundTransparency = 1
Logs2.BorderSizePixel = 0
Logs2.Position = UDim2.new(0.0296735913, 0, 0.160621762, 0)
Logs2.Size = UDim2.new(0, 322, 0, 85)
Logs2.Font = Enum.Font.SourceSans
Logs2.Text = "-1.1 Fixed bug that caused you not to be able to changewalkspeed and made you walk slow when you turned on god mode."
Logs2.TextColor3 = Color3.new(0.117647, 0.501961, 0.639216)
Logs2.TextSize = 20
Logs2.TextWrapped = true

Logs3.Name = "Logs3"
Logs3.Parent = ChangelogScreen
Logs3.BackgroundColor3 = Color3.new(1, 1, 1)
Logs3.BackgroundTransparency = 1
Logs3.BorderSizePixel = 0
Logs3.Position = UDim2.new(0.0296735913, 0, 0.46632123, 0)
Logs3.Size = UDim2.new(0, 322, 0, 85)
Logs3.Font = Enum.Font.SourceSans
Logs3.Text = "-1.2 Added 3 new features - Hard Dragger, Teleport Gifts and Flight"
Logs3.TextColor3 = Color3.new(0.117647, 0.501961, 0.639216)
Logs3.TextSize = 20
Logs3.TextWrapped = true

Log1and2Div.Name = "Log1and2Div"
Log1and2Div.Parent = ChangelogScreen
Log1and2Div.BackgroundColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Log1and2Div.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Log1and2Div.Position = UDim2.new(0.0534124635, 0, 0.196891189, 0)
Log1and2Div.Size = UDim2.new(0, 306, 0, 1)
Log1and2Div.Font = Enum.Font.SourceSans
Log1and2Div.Text = ""
Log1and2Div.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Log1and2Div.TextSize = 24
Log1and2Div.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

Log2and3Div.Name = "Log2and3Div"
Log2and3Div.Parent = ChangelogScreen
Log2and3Div.BackgroundColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Log2and3Div.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Log2and3Div.Position = UDim2.new(0.0534124635, 0, 0.569948196, 0)
Log2and3Div.Size = UDim2.new(0, 306, 0, 1)
Log2and3Div.Font = Enum.Font.SourceSans
Log2and3Div.Text = ""
Log2and3Div.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Log2and3Div.TextSize = 24
Log2and3Div.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

--------
-- Fly
repeat wait()
    until game.Players.LocalPlayer and game.Players.LocalPlayer.Character and game.Players.LocalPlayer.Character:findFirstChild("Torso") and game.Players.LocalPlayer.Character:findFirstChild("Humanoid")
local mouse = game.Players.LocalPlayer:GetMouse()
repeat wait() until mouse
local plr = game.Players.LocalPlayer
local torso = plr.Character.Torso
local flying = true
local deb = true
local ctrl = {f = 0, b = 0, l = 0, r = 0}
local lastctrl = {f = 0, b = 0, l = 0, r = 0}
local maxspeed = 50
local speed = 0
 
function Fly()
local bg = Instance.new("BodyGyro", torso)
bg.P = 9e4
bg.maxTorque = Vector3.new(9e9, 9e9, 9e9)
bg.cframe = torso.CFrame
local bv = Instance.new("BodyVelocity", torso)
bv.velocity = Vector3.new(0,0.1,0)
bv.maxForce = Vector3.new(9e9, 9e9, 9e9)
repeat wait()
plr.Character.Humanoid.PlatformStand = true
if ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0 then
speed = speed+.5+(speed/maxspeed)
if speed > maxspeed then
speed = maxspeed
end
elseif not (ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0) and speed ~= 0 then
speed = speed-1
if speed < 0 then
speed = 0
end
end
if (ctrl.l + ctrl.r) ~= 0 or (ctrl.f + ctrl.b) ~= 0 then
bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (ctrl.f+ctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(ctrl.l+ctrl.r,(ctrl.f+ctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
lastctrl = {f = ctrl.f, b = ctrl.b, l = ctrl.l, r = ctrl.r}
elseif (ctrl.l + ctrl.r) == 0 and (ctrl.f + ctrl.b) == 0 and speed ~= 0 then
bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (lastctrl.f+lastctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(lastctrl.l+lastctrl.r,(lastctrl.f+lastctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
else
bv.velocity = Vector3.new(0,0.1,0)
end
bg.cframe = game.Workspace.CurrentCamera.CoordinateFrame * CFrame.Angles(-math.rad((ctrl.f+ctrl.b)*50*speed/maxspeed),0,0)
until not flying
ctrl = {f = 0, b = 0, l = 0, r = 0}
lastctrl = {f = 0, b = 0, l = 0, r = 0}
speed = 0
bg:Destroy()
bv:Destroy()
plr.Character.Humanoid.PlatformStand = false
end
mouse.KeyDown:connect(function(key)
if key:lower() == "q" then
if flying then flying = false
AAPressQ.Visible = false
else
flying = true
Fly()
end
elseif key:lower() == "w" then
ctrl.f = 1
elseif key:lower() == "s" then
ctrl.b = -1
elseif key:lower() == "a" then
ctrl.l = -1
elseif key:lower() == "d" then
ctrl.r = 1
end
end)
mouse.KeyUp:connect(function(key)
if key:lower() == "w" then
ctrl.f = 0
elseif key:lower() == "s" then
ctrl.b = 0
elseif key:lower() == "a" then
ctrl.l = 0
elseif key:lower() == "d" then
ctrl.r = 0
end
end)
Fly()

AnimWelcomeScreen.Visible = true
AnimWelcomeScreen:TweenSizeAndPosition(UDim2.new(0, 200, 0, 200), UDim2.new(0.5, -100, 0.5, -100), "Out", "Quad", .25)
wait(2)
ImageLabel:Destroy()
AnimWelcomeScreen:TweenSizeAndPosition(UDim2.new(0, 0, 0, 0),UDim2.new(0.5, 0, 0.5, 0), "Out", "Bounce", 0.5);wait(0.5);AnimWelcomeScreen:Destroy();
wait(2)
HomeScreen.Visible = true
Main.Visible = true


HiName.Text = "Hi "..game.Players.LocalPlayer.Name
WelcomeName.Text = "Welcome "..game.Players.LocalPlayer.Name

--Opening Tabs
 P1.MouseButton1Down:connect(function()
      PSelected.Text = P1.Text
    end)
 P2.MouseButton1Down:connect(function()
      PSelected.Text = P2.Text
    end)
 P3.MouseButton1Down:connect(function()
      PSelected.Text = P3.Text
    end)
 P4.MouseButton1Down:connect(function()
      PSelected.Text = P4.Text
    end)
 P5.MouseButton1Down:connect(function()
      PSelected.Text = P5.Text
    end)
 P6.MouseButton1Down:connect(function()
      PSelected.Text = P6.Text
    end)
    local buttons = {
     PlayersScreen.P1,
     PlayersScreen.P2,
     PlayersScreen.P3,
     PlayersScreen.P4,
     PlayersScreen.P5,
     PlayersScreen.P6
    }

for i, v in pairs(game.Players:GetChildren()) do
      buttons[i].Text = v.Name
      buttons[i].Visible = true
    end
    game.Players.PlayerRemoving:connect(function()
      for i, v in pairs(game.Players:GetChildren()) do
        buttons[i].Text = v.Name
        buttons[i].Visible = true
      end
    end)
    game.Players.PlayerAdded:connect(function()
      for i, v in pairs(game.Players:GetChildren()) do
        buttons[i].Text = v.Name
        buttons[i].Visible = true
      end
    end)

if PlayersScreen.P1.text == " " then
P1.Visible = false
end

if PlayersScreen.P2.text == " " then
P2.Visible = false
end

if PlayersScreen.P3.text == " " then
P3.Visible = false
end

if PlayersScreen.P4.text == " " then
P4.Visible = false
end

if PlayersScreen.P5.text == " " then
P5.Visible = false
end

if PlayersScreen.P6.text == "" then
P6.Visible = false
end

TpToPlayer.MouseButton1Down:connect(function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = workspace[PSelected.Text].HumanoidRootPart.CFrame
end)

TpToPlayerBase.MouseButton1Down:connect(function()
for i, v in pairs(game.Workspace.Properties:GetChildren()) do
		if v.Owner.Value == game.Players[PSelected.Text] then
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.OriginSquare.CFrame
end
end
end)

X.MouseButton1Down:connect(function()
Drag.Visible = false
OpenBtn.Visible = true
end)

OpenBtn.MouseButton1Down:connect(function()
Drag.Visible = true
OpenBtn.Visible = false
end)

HomeLocal.MouseButton1Down:connect(function()
Main.Visible = true
AnimWelcomeScreen.Visible = false
HomeScreen.Visible = false
LocalScreen.Visible = true
PlayersScreen.Visible = false
WoodScreen.Visible = false
TeleportsScreen.Visible = false
ToolsScreen.Visible = false
OpenBtn.Visible = false
ChangelogScreen.Visible = false
end)

HomePlayers.MouseButton1Down:connect(function()
Main.Visible = true
AnimWelcomeScreen.Visible = false
HomeScreen.Visible = false
LocalScreen.Visible = false
PlayersScreen.Visible = true
WoodScreen.Visible = false
TeleportsScreen.Visible = false
ToolsScreen.Visible = false
OpenBtn.Visible = false
ChangelogScreen.Visible = false
end)

HomeWood.MouseButton1Down:connect(function()
Main.Visible = true
AnimWelcomeScreen.Visible = false
HomeScreen.Visible = false
LocalScreen.Visible = false
PlayersScreen.Visible = false
WoodScreen.Visible = true
TeleportsScreen.Visible = false
ToolsScreen.Visible = false
OpenBtn.Visible = false
ChangelogScreen.Visible = false
end)

HomeTeleports.MouseButton1Down:connect(function()
Main.Visible = true
AnimWelcomeScreen.Visible = false
HomeScreen.Visible = false
LocalScreen.Visible = false
PlayersScreen.Visible = false
WoodScreen.Visible = false
TeleportsScreen.Visible = true
ToolsScreen.Visible = false
OpenBtn.Visible = false
ChangelogScreen.Visible = false
end)

HomeTools.MouseButton1Down:connect(function()
Main.Visible = true
AnimWelcomeScreen.Visible = false
HomeScreen.Visible = false
LocalScreen.Visible = false
PlayersScreen.Visible = false
WoodScreen.Visible = false
TeleportsScreen.Visible = false
ToolsScreen.Visible = true
OpenBtn.Visible = false
ChangelogScreen.Visible = false
end)

HomeChangelog.MouseButton1Down:connect(function()
Main.Visible = true
AnimWelcomeScreen.Visible = false
HomeScreen.Visible = false
LocalScreen.Visible = false
PlayersScreen.Visible = false
WoodScreen.Visible = false
TeleportsScreen.Visible = false
ToolsScreen.Visible = false
OpenBtn.Visible = false
ChangelogScreen.Visible = true
end)

--Teleports
Palm.MouseButton1Down:connect(function() 
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(2570, -5, -32))
end)

BobsShack.MouseButton1Down:connect(function() 
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(259, 8, -2542))
end)

WoodRUs.MouseButton1Down:connect(function() 
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(251, 2, 57))
end)

Volcano.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character:MoveTo(Vector3.new(-1585, 622, 1140))
end)

Swamp.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character:MoveTo(Vector3.new(-1209, 132, -801))
end)

StrangeMan.MouseButton1Down:connect(function() 
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(1061, 16, 1130))
end)

Spawn.MouseButton1Down:connect(function() 
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(155, 3, 74))
end)

Shrine.MouseButton1Down:connect(function() 
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(1606, 195, 929)) 
end)

Lodge.MouseButton1Down:connect(function() 
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(1243, 63, 2305))
end)

LinksLogic.MouseButton1Down:connect(function() 
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(4606, 7, -779))
end)

GreenBox.MouseButton1Down:connect(function() 
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(-1675, 348, 1476))
end)

Fancy.MouseButton1Down:connect(function() 
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(491, 3, -1719))
end)

EndTimes.MouseButton1Down:connect(function() 
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(113, -213, -950))
end)

Dropoff.MouseButton1Down:connect(function() 
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(314, -2, 123))
end)

Den.MouseButton1Down:connect(function() 
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(331, 45, 1941))
end)

Cave.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character:MoveTo(Vector3.new(3581, -179, 430))
end)

BoxedCars.MouseButton1Down:connect(function() 
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(508, 3, -1463))
end)

YourPlot.MouseButton1Down:connect(function()
	for i, v in pairs(game.Workspace.Properties:GetChildren()) do
		if v.Owner.Value == game.Players.LocalPlayer then
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.OriginSquare.CFrame
		end
	end
end)
--------------
--LocalPlayer Commands
-- God
God.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.Humanoid.Name = "1"
	local l = game.Players.LocalPlayer.Character["1"]:Clone()
	l.Parent = game.Players.LocalPlayer.Character
	l.Name = "Humanoid"
	wait(0.1)
	game.Players.LocalPlayer.Character["1"]:Destroy()
	game.Workspace.CurrentCamera.CameraSubject = game.Players.LocalPlayer.Character
	game.Players.LocalPlayer.Character.Animate.Disabled = true
	l.Changed:Connect(function()
		if l then
			l.WalkSpeed=game.Players.LocalPlayer.Character.Humanoid.WalkSpeed
			l.JumpPower=game.Players.LocalPlayer.Character.Humanoid.JumpPower
		end
	end)
end)
-- Noclip
noclip = false
game:GetService('RunService').Stepped:connect(function()
if noclip then
game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
NoclipLabel.TextColor3 = Color3.new(0, 1, 0)
NoclipLabel.Text = "Enabled"
end
end)
Noclip.MouseButton1Down:connect(function()
noclip = not noclip
NoclipLabel.TextColor3 = Color3.new(0.7, 0, 0)
NoclipLabel.Text = "Disabled"
end)
-- Walkspeed
Walkspeed.MouseButton1Down:connect(function()
while true do
	wait()
	game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = WalkspeedValue.Text
end
end)
-- Jumppower
Jumppower.MouseButton1Down:connect(function()
while true do
	wait()
	game.Players.LocalPlayer.Character.Humanoid.JumpPower = JumppowerValue.Text
end
end)
--Players Commands
-- Teleport To Player
-- teleport To Player Base

--Wood Commands
-- Teleport Cut Wood
TeleportCutWood.MouseButton1Down:connect(function()
for _, Log in pairs(game.Workspace.LogModels:GetChildren()) do
if Log.Name:sub(1, 6) == "Loose_" and Log:findFirstChild("Owner") then
if Log.Owner.Value == game.Players.LocalPlayer then
Log:MoveTo(game.Players.LocalPlayer.Character.Torso.Position + Vector3.new(0, 15, 0))
end
end
end
end)

-- Sell Cut Wood
SellCutWood.MouseButton1Down:connect(function()
	        for _, Log in pairs(workspace.LogModels:GetChildren()) do
        if Log.Name:sub(1, 6) == "Loose_" and Log:findFirstChild("Owner") then
            if Log.Owner.Value == game.Players.LocalPlayer then
                for i,v in pairs(Log:GetChildren()) do
                    if v.Name=="WoodSection" then
                        spawn(function()
                            for i=1,10 do
                                wait()
                                v.CFrame=CFrame.new(Vector3.new(315, -0.296, 85.791))*CFrame.Angles(math.rad(90),0,0)
                            end
                        end)
                    end
                end
                spawn(function()
                    for i=1,20 do
                        wait()
                        game.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(Log)
                    end
                end)
            end
        end
    end
end)
-- Teleport End Times Wood
TeleportEndTimesWood.MouseButton1Down:connect(function()
	for i, v in pairs(game.Workspace:GetChildren()) do
if v.Name == "TreeRegion" then
for a, b in pairs(v:GetChildren()) do
tree(b, "LoneCave")
end
end
end
end)
-- Teleport Cave Crawler Wood
TeleportCaveCrawlerWood.MouseButton1Down:connect(function()
	for i, v in pairs(game.Workspace:GetChildren()) do
if v.Name == "TreeRegion" then
for a, b in pairs(v:GetChildren()) do
tree(b, "CaveCrawler")
end
end
end
end)

--Tools Commands
-- Dupe
Dupe.MouseButton1Down:connect(function()
plr = game:GetService("Players").LocalPlayer
slot = plr.CurrentSaveSlot
if Option == false then
if slot.Value == -1 then
Option = true
slot.RobloxLocked = true
DupeLabel.TextColor3 = Color3.new(0, 1, 0)
DupeLabel.Text = "Enabled"
end
else
Option = false
slot.RobloxLocked = false
DupeLabel.TextColor3 = Color3.new(0.7, 0, 0)
DupeLabel.Text = "Disabled"
end
end)
-- Move Tools
Move.MouseButton1Down:connect(function()
local player = game.Players.LocalPlayer
local Character = player.Character or player.CharacterAdded:wait()
local Humanoid = Character:WaitForChild("Humanoid")
local walkSpeed = Humanoid.WalkSpeed
game.Players.LocalPlayer.PlayerGui.ItemDraggingGUI.Dragger.Disabled = true
_G.dragRangeMin = 5
fivefour = coroutine.wrap(function()
EKey = false
QKey = false
player:GetMouse().KeyDown:connect(function(key)
	if string.lower(key) == "e" then
		EKey = true
	elseif string.lower(key) == "q" then
		QKey = true
	end
end)
player:GetMouse().KeyUp:connect(function(key)
	if string.lower(key) == "e" then
		EKey = false
	elseif string.lower(key) == "q" then
		QKey = false
	end
end)
while wait(0.1) do
	if EKey then
		F = FVal
		FVal = FVal + 1000
		ChangeForce(F+1000)
		print(F)
	end
	if QKey then
		F = FVal
		FVal = FVal - 1000
		ChangeForce(F-1000)
		print(F)
	end
end

end)
fivefour()
local dragPart = Instance.new("Part",game.Players.LocalPlayer.PlayerGui)--game.Players.LocalPlayer.PlayerGui.ItemDraggingGUI.Dragger.Dragger
dragPart.Size = Vector3.new(0.2,0.2,0.2)
dragPart.BrickColor = BrickColor.new("Really red")
player.CharacterAdded:connect(function()
	Character = player.Character
	Humanoid = Character:WaitForChild("Humanoid")
	Humanoid.Died:connect(function()
		dragPart.Parent = nil
	end)
end)

wait(1)
local dragRangeMax = 10000
local dragRangeMin = _G.dragRangeMin

local camera = workspace.CurrentCamera
local mouse = player:GetMouse()

local button1Down = false
local dragRange = dragRangeMax
FVal = 80000
local bodyPosition = Instance.new("BodyPosition", dragPart)
bodyPosition.maxForce = Vector3.new(1, 1, 1) * FVal
bodyPosition.D = 1000
bodyPosition.P = 4000
function ChangeForce(F)
if F > 0 then
F = bodyPosition.maxForce.X+F
bodyPosition.maxForce = Vector3.new(1, 1, 1) * F
else
F = bodyPosition.maxForce.X-F
bodyPosition.maxForce = Vector3.new(1, 1, 1) * F
end
end

local bodyGyro = Instance.new("BodyGyro", dragPart) 
bodyGyro.maxTorque = Vector3.new(1, 1, 1) * 200 --4000 -- * 0.000012
bodyGyro.P = 1200
bodyGyro.D = 140 --15

--bodyPosition.P = bodyPosition.P * 1/19
--bodyPosition.D = bodyPosition.D  * 1/19
--bodyGyro.P = bodyGyro.P * 1/19
--bodyGyro.D = bodyGyro.D  * 1/19

local rotateCFrame = CFrame.new()

local weld = Instance.new("Weld", dragPart)

--local interactPermission = require(game.ReplicatedStorage.Interaction.InteractionPermission)
local clientIsDragging = game.ReplicatedStorage.Interaction.ClientIsDragging

local carryAnimationTrack


--------------------------------[[ Drag Main ]]------------------------------------

local draggingPart = false

function click()
	button1Down = true

	local targetObject = game.Players.LocalPlayer:GetMouse().Target
	if not canDrag(targetObject) then
		return
	end
	
	local mouseHit = game.Players.LocalPlayer:GetMouse().Hit.p
	if (mouseHit - Character.Head.Position).magnitude > dragRangeMax then
		return
	end
	
	initializeDrag(targetObject, mouseHit)
	rotateCFrame = CFrame.new()
	
	carryAnimationTrack:Play(0.1, 1, 1)
	
	local dragIsFailing = 0 
	local dragTime = 0
	
	
	while button1Down and canDrag(targetObject) do
		local desiredPos = Character.Head.Position + (game.Players.LocalPlayer:GetMouse().Hit.p - Character.Head.Position).unit * dragRange
		
		local dragRay = Ray.new(Character.Head.Position, desiredPos - Character.Head.Position)
		local part, pos = workspace:FindPartOnRayWithIgnoreList(dragRay, {Character, dragPart, targetObject.Parent})
		
		if part then
			desiredPos = pos
		end
		
		if (camera.CoordinateFrame.p - Character.Head.Position).magnitude > 2 then
			desiredPos = desiredPos + Vector3.new(0, 1.8, 0)
		end
		
		moveDrag(desiredPos)
		bodyGyro.cframe = CFrame.new(dragPart.Position, camera.CoordinateFrame.p) * rotateCFrame
		
		local targParent = findHighestParent(targetObject) or targetObject		
		
		local attemptingToSurf  = false
		for _, check in pairs({{Ray = Ray.new((Character.HumanoidRootPart.CFrame * CFrame.new(0.7, -2.8, 0)).p, Vector3.new(0, -2, 0))}, 
							{Ray = Ray.new((Character.HumanoidRootPart.CFrame * CFrame.new(0.35, -2.8, 0)).p, Vector3.new(0, -2, 0))}, 
							{Ray = Ray.new((Character.HumanoidRootPart.CFrame * CFrame.new(0, -2.8, 0)).p, Vector3.new(0, -2, 0))},
							{Ray = Ray.new((Character.HumanoidRootPart.CFrame * CFrame.new(0.35, -2.8, 0)).p, Vector3.new(0, -2, 0))}, 
							{Ray = Ray.new((Character.HumanoidRootPart.CFrame * CFrame.new(-0.7, -2.8, 0)).p, Vector3.new(0, -2, 0))}, 
							
							{Ray = Ray.new((Character.HumanoidRootPart.CFrame * CFrame.new(0.35, -2.8, 0.6)).p, Vector3.new(0, -2, 0))}, 
							{Ray = Ray.new((Character.HumanoidRootPart.CFrame * CFrame.new(0, -2.8, 0.6)).p, Vector3.new(0, -2, 0))},
							{Ray = Ray.new((Character.HumanoidRootPart.CFrame * CFrame.new(0.35, -2.8, 0.6)).p, Vector3.new(0, -2, 0))}, 
							
							{Ray = Ray.new((Character.HumanoidRootPart.CFrame * CFrame.new(0.35, -2.8, -0.6)).p, Vector3.new(0, -2, 0))}, 
							{Ray = Ray.new((Character.HumanoidRootPart.CFrame * CFrame.new(0, -2.8, -0.6)).p, Vector3.new(0, -2, 0))},
							{Ray = Ray.new((Character.HumanoidRootPart.CFrame * CFrame.new(0.35, -2.8, -0.6)).p, Vector3.new(0, -2, 0))}, 
							
							{Ray = Ray.new((Character.HumanoidRootPart.CFrame * CFrame.new(0.5, -0.8, 0)).p, Character.HumanoidRootPart.CFrame.lookVector), State = Enum.HumanoidStateType.Climbing},
							{Ray = Ray.new((Character.HumanoidRootPart.CFrame * CFrame.new(-0.5, -0.8, 0)).p, Character.HumanoidRootPart.CFrame.lookVector), State = Enum.HumanoidStateType.Climbing},
							{Ray = Ray.new((Character.HumanoidRootPart.CFrame * CFrame.new(0.5, -1.3, 0)).p, Character.HumanoidRootPart.CFrame.lookVector), State = Enum.HumanoidStateType.Climbing},
							{Ray = Ray.new((Character.HumanoidRootPart.CFrame * CFrame.new(-0.5, -1.3, 0)).p, Character.HumanoidRootPart.CFrame.lookVector), State = Enum.HumanoidStateType.Climbing}
									
					}) do
		
			local ray = check.Ray
			local part, _ = workspace:FindPartOnRayWithIgnoreList(ray, {Character})
			local op = part
			part = part and findHighestParent(part)
			
			if part and (not check.State or Humanoid:GetState() == check.State) then
				if part == targParent then
					attemptingToSurf = true
				else
					for _, connectedPart in pairs(op:GetConnectedParts(true)) do

						if connectedPart == targetObject--[[targParent]] then
							attemptingToSurf = true
							break
						end
					end
				end

				if attemptingToSurf then
					break
				end
			end
		end
		
		
		
		
		
		local falling = Humanoid:GetState() == Enum.HumanoidStateType.Freefall or Humanoid:GetState() == Enum.HumanoidStateType.FallingDown--not part1 and not part2
		
		
		if attemptingToSurf then
			dragIsFailing = 0
		elseif falling then
			dragIsFailing = 0
		elseif (dragPart.Position - desiredPos).magnitude > 5 then
			dragIsFailing = 0
		else
			dragIsFailing = 0
		end
		if dragIsFailing > 16 then
			break
		end
		
		
		if dragTime % 10 == 0 and targParent.Parent:FindFirstChild("BedInfo") and targParent.Parent:FindFirstChild("Main") then
			game.Players.LocalPlayer.PlayerGui.ItemDraggingGUI.Parent.Scripts.VehicleControl.SetVehicleOwnership:Fire(targParent.Parent.Main)
		end
		
		clientIsDragging:FireServer(targParent.Parent)
		
		wait()
		dragTime = 0
	end
	
	carryAnimationTrack:Stop()
	
	endDrag()
end


function findHighestParent(child)
	if not child or not child.Parent or child.Parent == workspace then
		return nil
	end
	
	local ret = child.Parent:FindFirstChild("Owner") and child
	return findHighestParent(child.Parent) or ret
end



function clickEnded()
	button1Down = false
end

function holdDistanceChanged()
	dragRange = dragRangeMax--[[_G.dragRangeMin + (1 - dist) * (dragRangeMax - _G.dragRangeMin)]]
end


function canDrag(targetObject)
	
	
	if not (targetObject and not targetObject.Anchored and targetObject.Parent and Humanoid.Health > 0) then -- General conditions
		return false
	end
	
	if targetObject.Name == "LeafPart" then
		return false
	end
	
	local originTargetObject = targetObject
	targetObject = findHighestParent(targetObject) or targetObject
	
	bodyGyro.Parent = dragPart
	
	
	--[[if not (targetObject.Parent:FindFirstChild("Owner") or targetObject.Parent.Parent:FindFirstChild("Owner")) then
		return otherDraggable(targetObject, originTargetObject)
	end]]

	if targetObject.Parent:FindFirstChild("Owner") or targetObject.Parent.Parent:FindFirstChild("Owner") then
		return true
	end
	
	if targetObject.Parent:FindFirstChild("TreeClass") then -- Wood class
		return true
	end
	if targetObject.Parent:FindFirstChild("BoxItemName") then -- Shop items
		return true
	end
	if targetObject.Parent:FindFirstChild("PurchasedBoxItemName") then -- Purchased box items
		return true
	end
	if targetObject.Parent:FindFirstChild("Handle") then -- Tool items
		return true
	end
	
	return otherDraggable(targetObject, originTargetObject)
end

function otherDraggable(targetObject, originTargetObject)
	local draggable = targetObject and targetObject.Parent and targetObject.Parent:FindFirstChild("DraggableItem") or originTargetObject and originTargetObject.Parent and originTargetObject.Parent:FindFirstChild("DraggableItem")
	if draggable then -- Other stuff
		if draggable:FindFirstChild("NoRotate") then
			bodyGyro.Parent  = nil
		end
		return true
	end
end

function initializeDrag(targetObject,mouseHit)
	draggingPart = true
	mouse.TargetFilter = targetObject and findHighestParent(targetObject) and findHighestParent(targetObject).Parent or targetObject

	dragPart.CFrame = CFrame.new(mouseHit, camera.CoordinateFrame.p)

	weld.Part0 = dragPart
	weld.Part1 = targetObject
	weld.C0 =  CFrame.new(mouseHit,camera.CoordinateFrame.p):inverse() * targetObject.CFrame
	weld.Parent = dragPart
	
	dragPart.Parent = workspace
end

function endDrag()
	mouse.TargetFilter = nil
	dragPart.Parent = nil
	draggingPart = false
end

--------------------------------[[ Do Prompt ]]------------------------------------


local dragGuiState = ""
function interactLoop()
	while true do
		wait()
		
		local newState = ""
		
		local mouseHit = game.Players.LocalPlayer:GetMouse().Hit.p
		local targetObject = game.Players.LocalPlayer:GetMouse().Target
		
		
		if draggingPart then
			newState = "Dragging"
		elseif canDrag(targetObject) and not button1Down and (mouseHit - Character.Head.Position).magnitude < dragRangeMax then
			newState = "Mouseover"
		end
		
		if true then-- not (newState == dragGuiState) then
			dragGuiState = newState
			setPlatformControls()
			
			if dragGuiState == "" then
				game.Players.LocalPlayer.PlayerGui.ItemDraggingGUI.CanDrag.Visible = false
				game.Players.LocalPlayer.PlayerGui.ItemDraggingGUI.CanRotate.Visible = false
			elseif dragGuiState ==  "Mouseover" then
				game.Players.LocalPlayer.PlayerGui.ItemDraggingGUI.CanDrag.Visible = true
				game.Players.LocalPlayer.PlayerGui.ItemDraggingGUI.CanRotate.Visible = false
			elseif dragGuiState ==  "Dragging" then
				game.Players.LocalPlayer.PlayerGui.ItemDraggingGUI.CanDrag.Visible = false
				game.Players.LocalPlayer.PlayerGui.ItemDraggingGUI.CanRotate.Visible = not (bodyGyro.Parent == nil) and (not player:FindFirstChild("IsChatting") or player.IsChatting.Value < 1)
			end
		end
		
	end
end


--------------------------------[[ Drag Moving ]]------------------------------------


function moveDrag(pos)
	bodyPosition.position = pos
end
local rotateSpeedReduce = 0.036

local lastRotateTick
function crotate(amount, speed)

	if not draggingPart then
		if not player:FindFirstChild("IsChatting") or player.IsChatting.Value < 2 then
			Humanoid.WalkSpeed = walkSpeed
		end
		return
	end
	
	if Humanoid.WalkSpeed > 1 then
		walkSpeed = Humanoid.WalkSpeed
		Humanoid.WalkSpeed = 0
	end
	
	lastRotateTick = tick()
	local thisRotateTick = lastRotateTick
	
	while draggingPart and amount.magnitude > 0 and lastRotateTick == thisRotateTick do
		rotateCFrame = CFrame.Angles(0, -amount.X * rotateSpeedReduce, 0) * CFrame.Angles(amount.Y * rotateSpeedReduce, 0, 0) * rotateCFrame
		wait()
	end
	
	if amount.magnitude == 0 then
		if not player:FindFirstChild("IsChatting") or  player.IsChatting.Value < 2 then
			Humanoid.WalkSpeed = walkSpeed
		end
	end
end

--------------------------------[[ User Input ]]------------------------------------

wait(1)

carryAnimationTrack = Humanoid:LoadAnimation(game.Players.LocalPlayer.PlayerGui.ItemDraggingGUI.Dragger:WaitForChild("CarryItem"))

--input = require(game.Players.LocalPlayer.PlayerGui.ItemDraggingGUI.Parent:WaitForChild("Scripts"):WaitForChild("UserInput"))

game.Players.LocalPlayer:GetMouse().Button1Down:connect(function()
	click()
	holdDistanceChanged()
end)
game.Players.LocalPlayer:GetMouse().Button1Up:connect(function()
	clickEnded()
end)
--input.ClickBegan(click, holdDistanceChanged)
--input.ClickEnded(clickEnded)

--input.Rotate(crotate)


function setPlatformControls()
		game.Players.LocalPlayer.PlayerGui.ItemDraggingGUI.CanDrag.PlatformButton.Image = game.Players.LocalPlayer.PlayerGui.ItemDraggingGUI.CanDrag.PlatformButton.PC.Value
		game.Players.LocalPlayer.PlayerGui.ItemDraggingGUI.CanDrag.PlatformButton.KeyLabel.Text = "CLICK"
		game.Players.LocalPlayer.PlayerGui.ItemDraggingGUI.CanRotate.PlatformButton.Image = game.Players.LocalPlayer.PlayerGui.ItemDraggingGUI.CanRotate.PlatformButton.PC.Value
		game.Players.LocalPlayer.PlayerGui.ItemDraggingGUI.CanRotate.PlatformButton.KeyLabel.Text = "SHIFT + WASD"
end


interactLoop()
end)
-- Golden Axe
GoldAxe.MouseButton1Down:connect(function()

local mouse1 = game:GetService("Players").LocalPlayer:GetMouse()
mouse1.Button1Down:connect(function(key)
       Pressing=false
end)

function GetAxe()
if game.Players.LocalPlayer.Character:FindFirstChild("Tool") then
return game.Players.LocalPlayer.Character:FindFirstChild("Tool")
end
end

local HitPoints={
['GoldAxe']= 50;
['BasicHatchet']= 0.2;
['Axe1']= 0.55;
['Axe2']= 0.93;
['AxeAlphaTesters']= 1.5;
['Rukiryaxe']= 1.68;
['Axe3']= 1.45;
['AxeBetaTesters']= 1.45;
['FireAxe']= 0.6;
['SilverAxe']= 1.6;
['EndTimesAxe']= 10000000;
['AxeChicken']= 0.1;
['CandyCaneAxe']= 0;
}

local Pressing = false

local mouse1 = game:GetService("Players").LocalPlayer:GetMouse()
mouse1.Button1Down:connect(function(key)
       Pressing=true
       poop(GetAxe())
end)

local mouse1 = game:GetService("Players").LocalPlayer:GetMouse()
mouse1.Button1Down:connect(function(key)
       Pressing=false
end)

function cut(Height,Tool)
local Tree=game.Players.LocalPlayer:GetMouse().Target
game.ReplicatedStorage.Interaction.RemoteProxy:FireServer(Tree.Parent.CutEvent,{
["cuttingClass"] = "Axe",
["cooldown"] = 0,
["hitPoints"] = HitPoints[Tool.ToolName.Value],
["sectionId"] = 1,
["tool"] = Tool,
["faceVector"] = Vector3.new(-1,0,0),
["height"] = Height})
end

function poop(Tool)
   while Pressing do
       for i=1,100 do
wait()
cut(_G.SIZE,Tool)
cut(1,Tool)
end
   end
end
end)
-- Leaked Items
LeakedItems.MouseButton1Down:connect(function() 
game.ReplicatedStorage.Purchasables:Clone().Parent = game.Workspace.PlayerModels
end)

-- Ctrl + Click TP
TeleportTool.MouseButton1Down:connect(function() 
local Plr = game:GetService("Players").LocalPlayer
local Mouse = Plr:GetMouse()

Mouse.Button1Down:connect(function()
if not game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftControl) then return end
if not Mouse.Target then return end
Plr.Character:MoveTo(Mouse.Hit.p)
end)
end)
-- Grey Wood
GreyWood.MouseButton1Down:connect(function()
	for i,v in next,workspace.PlayerModels:GetChildren() do
	    if v:FindFirstChild("Type") then
	        if v.Type.Value == "Blueprint" then
	            v.Type.Value = "Structure"
	        end
	    end
	end
end)
-- Teleport Gifts
TeleportGifts.MouseButton1Down:connect(function()
	for i,v in next,workspace.PlayerModels:GetChildren() do
    if v:FindFirstChild("Main") and v.Owner.Value == game.Players.LocalPlayer then
    for q,p in pairs(v:GetChildren()) do       
        if p.Name:lower():match("box") or p.Name == "DraggableItem" then
            wait()
                v.PrimaryPart = v.Main
                game.ReplicatedStorage.Interaction.Verify:FireServer('Item owned by player',v)
                   v:SetPrimaryPartCFrame(game.Players.LocalPlayer.Character.Head.CFrame)
                 game.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(v)
        end
    end
    end
end
end)
end)
JAMESGUI.MouseButton1Down:Connect(function()
local service = setmetatable({}, {
    __index = function(t, k)
        return game:GetService(k)
    end
})
-- Instances:
local Hi = Instance.new("ScreenGui")
local Menu = Instance.new("Frame")
local Main = Instance.new("Frame")
local CloseB = Instance.new("TextButton")
local MTitle = Instance.new("TextLabel")
local ExpandButton = Instance.new("ImageButton")
local ExpandFrame = Instance.new("Frame")
local LabelExpand = Instance.new("TextLabel")
local EXBMain = Instance.new("TextButton")
local EXBTeleports = Instance.new("TextButton")
local EXBInfo = Instance.new("TextButton")
local EXBSecond = Instance.new("TextButton")
local closeexpand = Instance.new("TextButton")
local Functions = Instance.new("Frame")
local UIGridLayout = Instance.new("UIGridLayout")
local Fly = Instance.new("TextButton")
local MaxLand = Instance.new("TextButton")
local AntiBlacklist = Instance.new("TextButton")
local GodAxe = Instance.new("TextButton")
local SellTree = Instance.new("TextButton")
local SellPlank = Instance.new("TextButton")
local WipeBase = Instance.new("TextButton")
local Fastwalk = Instance.new("TextButton")
local SawmillTp = Instance.new("TextButton")
local Functions2 = Instance.new("Frame")
local UIGridLayout_2 = Instance.new("UIGridLayout")
local PlotTp = Instance.new("TextButton")
local Noclip = Instance.new("TextButton")
local WoodTool = Instance.new("TextButton")
local InfWires = Instance.new("TextButton")
local BuyItems = Instance.new("TextButton")
local BuyBlueprints = Instance.new("TextButton")
local Info = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local Teleports = Instance.new("ScrollingFrame")
local UIGridLayout_3 = Instance.new("UIGridLayout")
local SpawnPoint = Instance.new("TextButton")
local SkiLodge = Instance.new("TextButton")
local TheDen = Instance.new("TextButton")
local ShrineOfSight = Instance.new("TextButton")
local Bridge = Instance.new("TextButton")
local Dock = Instance.new("TextButton")
local FrostTreeArea = Instance.new("TextButton")
local SnowGlow = Instance.new("TextButton")
local VolcanoWin = Instance.new("TextButton")
local EndTimes = Instance.new("TextButton")
local BobsShack = Instance.new("TextButton")
local FineArtsShop = Instance.new("TextButton")
local BoxedCars = Instance.new("TextButton")
local FancyFurnishings = Instance.new("TextButton")
local PalmIsland = Instance.new("TextButton")
local Swamp = Instance.new("TextButton")
local Volcano = Instance.new("TextButton")
local Cave = Instance.new("TextButton")
local LinksLogic = Instance.new("TextButton")
local WoodRUs = Instance.new("TextButton")
local LandStore = Instance.new("TextButton")
--Properties:
Hi.Name = "Hi"
Hi.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
Hi.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
 
Menu.Name = "Menu"
Menu.Parent = Hi
Menu.BackgroundColor3 = Color3.new(0, 0, 0)
Menu.BackgroundTransparency = 1
Menu.BorderColor3 = Color3.new(0, 0, 0)
Menu.BorderSizePixel = 0
Menu.Size = UDim2.new(0, 100, 0, 100)
 
Main.Name = "Main"
Main.Parent = Menu
Main.Active = true
Main.BackgroundColor3 = Color3.new(0.427451, 0.109804, 0.109804)
Main.BorderColor3 = Color3.new(0, 0, 0)
Main.BorderSizePixel = 2
Main.Position = UDim2.new(5.76999998, 0, 1.56000006, 0)
Main.Selectable = true
Main.Size = UDim2.new(0, 371, 0, 228)
Main.ZIndex = 3
Main.Draggable = true
 
CloseB.Name = "CloseB"
CloseB.Parent = Main
CloseB.BackgroundColor3 = Color3.new(0.384314, 0.2, 0.2)
CloseB.BorderColor3 = Color3.new(0, 0, 0)
CloseB.BorderSizePixel = 0
CloseB.Position = UDim2.new(0.86522913, 0, 0, 0)
CloseB.Size = UDim2.new(0, 50, 0, 50)
CloseB.Font = Enum.Font.SourceSans
CloseB.Text = ""
CloseB.TextColor3 = Color3.new(0, 0, 0)
CloseB.TextSize = 14
 
MTitle.Name = "MTitle"
MTitle.Parent = Main
MTitle.BackgroundColor3 = Color3.new(0, 0, 0)
MTitle.BackgroundTransparency = 0.99000000953674
MTitle.BorderColor3 = Color3.new(0, 0, 0)
MTitle.BorderSizePixel = 0
MTitle.Position = UDim2.new(0.199460924, 0, 0, 0)
MTitle.Size = UDim2.new(0, 247, 0, 50)
MTitle.Font = Enum.Font.SourceSans
MTitle.Text = "JamesLT2GUI"
MTitle.TextColor3 = Color3.new(0.309804, 0.0784314, 0.0784314)
MTitle.TextSize = 40
MTitle.TextStrokeTransparency = 0.69999998807907
MTitle.TextWrapped = true
 
ExpandButton.Name = "ExpandButton"
ExpandButton.Parent = Main
ExpandButton.BackgroundColor3 = Color3.new(0, 0, 0)
ExpandButton.BackgroundTransparency = 1
ExpandButton.BorderColor3 = Color3.new(0, 0, 0)
ExpandButton.BorderSizePixel = 0
ExpandButton.Size = UDim2.new(0, 50, 0, 50)
ExpandButton.ZIndex = 4
ExpandButton.Image = "rbxassetid://2781388145"
 
ExpandFrame.Name = "ExpandFrame"
ExpandFrame.Parent = Main
ExpandFrame.BackgroundColor3 = Color3.new(0.384314, 0.2, 0.2)
ExpandFrame.BorderColor3 = Color3.new(0, 0, 0)
ExpandFrame.BorderSizePixel = 0
ExpandFrame.Size = UDim2.new(0, 100, 0, 228)
ExpandFrame.Visible = false
ExpandFrame.ZIndex = 6
 
LabelExpand.Name = "LabelExpand"
LabelExpand.Parent = ExpandFrame
LabelExpand.BackgroundColor3 = Color3.new(0, 0, 0)
LabelExpand.BackgroundTransparency = 1
LabelExpand.BorderColor3 = Color3.new(0, 0, 0)
LabelExpand.BorderSizePixel = 0
LabelExpand.Position = UDim2.new(0, 0, 0.114035085, 0)
LabelExpand.Size = UDim2.new(0, 100, 0, 36)
LabelExpand.ZIndex = 7
LabelExpand.Font = Enum.Font.SourceSans
LabelExpand.Text = "Features"
LabelExpand.TextColor3 = Color3.new(0, 0, 0)
LabelExpand.TextSize = 24
 
EXBMain.Name = "EXBMain"
EXBMain.Parent = ExpandFrame
EXBMain.BackgroundColor3 = Color3.new(0.223529, 0.223529, 0.223529)
EXBMain.BackgroundTransparency = 0.5
EXBMain.BorderColor3 = Color3.new(0, 0, 0)
EXBMain.BorderSizePixel = 0
EXBMain.Position = UDim2.new(0, 0, 0.271929801, 0)
EXBMain.Size = UDim2.new(0, 100, 0, 35)
EXBMain.ZIndex = 7
EXBMain.Font = Enum.Font.SourceSans
EXBMain.Text = "Functions"
EXBMain.TextColor3 = Color3.new(0, 0, 0)
EXBMain.TextSize = 18
 
EXBTeleports.Name = "EXBTeleports"
EXBTeleports.Parent = ExpandFrame
EXBTeleports.BackgroundColor3 = Color3.new(0.223529, 0.223529, 0.223529)
EXBTeleports.BackgroundTransparency = 0.5
EXBTeleports.BorderColor3 = Color3.new(0, 0, 0)
EXBTeleports.BorderSizePixel = 0
EXBTeleports.Position = UDim2.new(0, 0, 0.425438583, 0)
EXBTeleports.Size = UDim2.new(0, 100, 0, 35)
EXBTeleports.ZIndex = 7
EXBTeleports.Font = Enum.Font.SourceSans
EXBTeleports.Text = "Teleports"
EXBTeleports.TextColor3 = Color3.new(0, 0, 0)
EXBTeleports.TextSize = 18
 
EXBInfo.Name = "EXBInfo"
EXBInfo.Parent = ExpandFrame
EXBInfo.BackgroundColor3 = Color3.new(0.223529, 0.223529, 0.223529)
EXBInfo.BackgroundTransparency = 0.5
EXBInfo.BorderColor3 = Color3.new(0, 0, 0)
EXBInfo.BorderSizePixel = 0
EXBInfo.Position = UDim2.new(0, 0, 0.72807014, 0)
EXBInfo.Size = UDim2.new(0, 100, 0, 35)
EXBInfo.ZIndex = 7
EXBInfo.Font = Enum.Font.SourceSans
EXBInfo.Text = "Info"
EXBInfo.TextColor3 = Color3.new(0, 0, 0)
EXBInfo.TextSize = 18
 
EXBSecond.Name = "EXBSecond"
EXBSecond.Parent = ExpandFrame
EXBSecond.BackgroundColor3 = Color3.new(0.223529, 0.223529, 0.223529)
EXBSecond.BackgroundTransparency = 0.5
EXBSecond.BorderColor3 = Color3.new(0, 0, 0)
EXBSecond.BorderSizePixel = 0
EXBSecond.Position = UDim2.new(0, 0, 0.578947306, 0)
EXBSecond.Size = UDim2.new(0, 100, 0, 35)
EXBSecond.ZIndex = 7
EXBSecond.Font = Enum.Font.SourceSans
EXBSecond.Text = "Functions(2)"
EXBSecond.TextColor3 = Color3.new(0, 0, 0)
EXBSecond.TextSize = 18
 
closeexpand.Name = "closeexpand"
closeexpand.Parent = ExpandFrame
closeexpand.BackgroundColor3 = Color3.new(0, 0, 0)
closeexpand.BackgroundTransparency = 1
closeexpand.BorderColor3 = Color3.new(0, 0, 0)
closeexpand.BorderSizePixel = 0
closeexpand.Size = UDim2.new(0, 100, 0, 36)
closeexpand.Font = Enum.Font.SourceSans
closeexpand.Text = "close"
closeexpand.TextColor3 = Color3.new(1, 1, 1)
closeexpand.TextSize = 24
closeexpand.TextWrapped = true
 
Functions.Name = "Functions"
Functions.Parent = Main
Functions.BackgroundColor3 = Color3.new(0, 0, 0)
Functions.BackgroundTransparency = 0.89999997615814
Functions.BorderColor3 = Color3.new(0, 0, 0)
Functions.BorderSizePixel = 0
Functions.Position = UDim2.new(0, 0, 0.219298244, 0)
Functions.Size = UDim2.new(0, 371, 0, 178)
Functions.Visible = false
Functions.ZIndex = 4
 
UIGridLayout.Parent = Functions
UIGridLayout.HorizontalAlignment = Enum.HorizontalAlignment.Center
UIGridLayout.VerticalAlignment = Enum.VerticalAlignment.Center
UIGridLayout.CellPadding = UDim2.new(0, 7, 0, 7)
UIGridLayout.CellSize = UDim2.new(0, 100, 0, 50)
 
Fly.Name = "Fly"
Fly.Parent = Functions
Fly.BackgroundColor3 = Color3.new(0.384314, 0.2, 0.2)
Fly.BorderColor3 = Color3.new(0, 0, 0)
Fly.BorderSizePixel = 0
Fly.Size = UDim2.new(0, 200, 0, 50)
Fly.Font = Enum.Font.SourceSans
Fly.Text = "Fly"
Fly.TextColor3 = Color3.new(0, 0, 0)
Fly.TextSize = 20
 
MaxLand.Name = "MaxLand"
MaxLand.Parent = Functions
MaxLand.BackgroundColor3 = Color3.new(0.384314, 0.2, 0.2)
MaxLand.BorderColor3 = Color3.new(0, 0, 0)
MaxLand.BorderSizePixel = 0
MaxLand.Size = UDim2.new(0, 200, 0, 50)
MaxLand.Font = Enum.Font.SourceSans
MaxLand.Text = "MaxLand"
MaxLand.TextColor3 = Color3.new(0, 0, 0)
MaxLand.TextSize = 20
 
AntiBlacklist.Name = "AntiBlacklist"
AntiBlacklist.Parent = Functions
AntiBlacklist.BackgroundColor3 = Color3.new(0.384314, 0.2, 0.2)
AntiBlacklist.BorderColor3 = Color3.new(0, 0, 0)
AntiBlacklist.BorderSizePixel = 0
AntiBlacklist.Size = UDim2.new(0, 200, 0, 50)
AntiBlacklist.Font = Enum.Font.SourceSans
AntiBlacklist.Text = "AntiBlacklist"
AntiBlacklist.TextColor3 = Color3.new(0, 0, 0)
AntiBlacklist.TextSize = 20
 
GodAxe.Name = "GodAxe"
GodAxe.Parent = Functions
GodAxe.BackgroundColor3 = Color3.new(0.384314, 0.2, 0.2)
GodAxe.BorderColor3 = Color3.new(0, 0, 0)
GodAxe.BorderSizePixel = 0
GodAxe.Size = UDim2.new(0, 200, 0, 50)
GodAxe.Font = Enum.Font.SourceSans
GodAxe.Text = "GodAxe"
GodAxe.TextColor3 = Color3.new(0, 0, 0)
GodAxe.TextSize = 20
 
SellTree.Name = "SellTree"
SellTree.Parent = Functions
SellTree.BackgroundColor3 = Color3.new(0.384314, 0.2, 0.2)
SellTree.BorderColor3 = Color3.new(0, 0, 0)
SellTree.BorderSizePixel = 0
SellTree.Size = UDim2.new(0, 200, 0, 50)
SellTree.Font = Enum.Font.SourceSans
SellTree.Text = "SellTree(H)"
SellTree.TextColor3 = Color3.new(0, 0, 0)
SellTree.TextSize = 20
 
SellPlank.Name = "SellPlank"
SellPlank.Parent = Functions
SellPlank.BackgroundColor3 = Color3.new(0.384314, 0.2, 0.2)
SellPlank.BorderColor3 = Color3.new(0, 0, 0)
SellPlank.BorderSizePixel = 0
SellPlank.Size = UDim2.new(0, 200, 0, 50)
SellPlank.Font = Enum.Font.SourceSans
SellPlank.Text = "SellPlanks(G)"
SellPlank.TextColor3 = Color3.new(0, 0, 0)
SellPlank.TextSize = 20
 
WipeBase.Name = "WipeBase"
WipeBase.Parent = Functions
WipeBase.BackgroundColor3 = Color3.new(0.384314, 0.2, 0.2)
WipeBase.BorderColor3 = Color3.new(0, 0, 0)
WipeBase.BorderSizePixel = 0
WipeBase.Size = UDim2.new(0, 200, 0, 50)
WipeBase.Font = Enum.Font.SourceSans
WipeBase.Text = "WipeBase"
WipeBase.TextColor3 = Color3.new(0, 0, 0)
WipeBase.TextSize = 20
 
Fastwalk.Name = "Fastwalk"
Fastwalk.Parent = Functions
Fastwalk.BackgroundColor3 = Color3.new(0.384314, 0.2, 0.2)
Fastwalk.BorderColor3 = Color3.new(0, 0, 0)
Fastwalk.BorderSizePixel = 0
Fastwalk.Size = UDim2.new(0, 200, 0, 50)
Fastwalk.Font = Enum.Font.SourceSans
Fastwalk.Text = "Fastwalk(X)"
Fastwalk.TextColor3 = Color3.new(0, 0, 0)
Fastwalk.TextSize = 20
 
SawmillTp.Name = "SawmillTp"
SawmillTp.Parent = Functions
SawmillTp.BackgroundColor3 = Color3.new(0.384314, 0.2, 0.2)
SawmillTp.BorderColor3 = Color3.new(0, 0, 0)
SawmillTp.BorderSizePixel = 0
SawmillTp.Size = UDim2.new(0, 200, 0, 50)
SawmillTp.Font = Enum.Font.SourceSans
SawmillTp.Text = "Wood2Sawmill"
SawmillTp.TextColor3 = Color3.new(0, 0, 0)
SawmillTp.TextSize = 18
 
Functions2.Name = "Functions2"
Functions2.Parent = Main
Functions2.BackgroundColor3 = Color3.new(0, 0, 0)
Functions2.BackgroundTransparency = 0.89999997615814
Functions2.BorderColor3 = Color3.new(0, 0, 0)
Functions2.BorderSizePixel = 0
Functions2.Position = UDim2.new(0, 0, 0.219298244, 0)
Functions2.Size = UDim2.new(0, 371, 0, 178)
Functions2.Visible = false
 
UIGridLayout_2.Parent = Functions2
UIGridLayout_2.HorizontalAlignment = Enum.HorizontalAlignment.Center
UIGridLayout_2.VerticalAlignment = Enum.VerticalAlignment.Center
UIGridLayout_2.CellPadding = UDim2.new(0, 7, 0, 7)
UIGridLayout_2.CellSize = UDim2.new(0, 100, 0, 50)
 
PlotTp.Name = "PlotTp"
PlotTp.Parent = Functions2
PlotTp.BackgroundColor3 = Color3.new(0.384314, 0.2, 0.2)
PlotTp.BorderColor3 = Color3.new(0, 0, 0)
PlotTp.BorderSizePixel = 0
PlotTp.Size = UDim2.new(0, 200, 0, 50)
PlotTp.Font = Enum.Font.SourceSans
PlotTp.Text = "PlotTp(m)"
PlotTp.TextColor3 = Color3.new(0, 0, 0)
PlotTp.TextSize = 24
 
Noclip.Name = "Noclip"
Noclip.Parent = Functions2
Noclip.BackgroundColor3 = Color3.new(0.384314, 0.2, 0.2)
Noclip.BorderColor3 = Color3.new(0, 0, 0)
Noclip.BorderSizePixel = 0
Noclip.Size = UDim2.new(0, 200, 0, 50)
Noclip.Font = Enum.Font.SourceSans
Noclip.Text = "Noclip(n)"
Noclip.TextColor3 = Color3.new(0, 0, 0)
Noclip.TextSize = 24
 
WoodTool.Name = "WoodTool"
WoodTool.Parent = Functions2
WoodTool.BackgroundColor3 = Color3.new(0.384314, 0.2, 0.2)
WoodTool.BorderColor3 = Color3.new(0, 0, 0)
WoodTool.BorderSizePixel = 0
WoodTool.Size = UDim2.new(0, 200, 0, 50)
WoodTool.Font = Enum.Font.SourceSans
WoodTool.Text = "WoodTool"
WoodTool.TextColor3 = Color3.new(0, 0, 0)
WoodTool.TextSize = 24
 
InfWires.Name = "InfWires"
InfWires.Parent = Functions2
InfWires.BackgroundColor3 = Color3.new(0.384314, 0.2, 0.2)
InfWires.BorderColor3 = Color3.new(0, 0, 0)
InfWires.BorderSizePixel = 0
InfWires.Size = UDim2.new(0, 200, 0, 50)
InfWires.Font = Enum.Font.SourceSans
InfWires.Text = "InfWires"
InfWires.TextColor3 = Color3.new(0, 0, 0)
InfWires.TextSize = 24
 
BuyItems.Name = "BuyItems"
BuyItems.Parent = Functions2
BuyItems.BackgroundColor3 = Color3.new(0.384314, 0.2, 0.2)
BuyItems.BorderColor3 = Color3.new(0, 0, 0)
BuyItems.BorderSizePixel = 0
BuyItems.Size = UDim2.new(0, 200, 0, 50)
BuyItems.Font = Enum.Font.SourceSans
BuyItems.Text = "BuyItems"
BuyItems.TextColor3 = Color3.new(0, 0, 0)
BuyItems.TextSize = 24
 
BuyBlueprints.Name = "BuyBlueprints"
BuyBlueprints.Parent = Functions2
BuyBlueprints.BackgroundColor3 = Color3.new(0.384314, 0.2, 0.2)
BuyBlueprints.BorderColor3 = Color3.new(0, 0, 0)
BuyBlueprints.BorderSizePixel = 0
BuyBlueprints.Size = UDim2.new(0, 200, 0, 50)
BuyBlueprints.Font = Enum.Font.SourceSans
BuyBlueprints.Text = "BuyBlueprints"
BuyBlueprints.TextColor3 = Color3.new(0, 0, 0)
BuyBlueprints.TextScaled = true
BuyBlueprints.TextSize = 18
BuyBlueprints.TextWrapped = true
 
Info.Name = "Info"
Info.Parent = Main
Info.BackgroundColor3 = Color3.new(0, 0, 0)
Info.BackgroundTransparency = 0.89999997615814
Info.BorderColor3 = Color3.new(0, 0, 0)
Info.BorderSizePixel = 0
Info.Position = UDim2.new(0, 0, 0.219298244, 0)
Info.Size = UDim2.new(0, 371, 0, 178)
Info.Visible = false
 
TextLabel.Parent = Info
TextLabel.BackgroundColor3 = Color3.new(0, 0, 0)
TextLabel.BackgroundTransparency = 0.97000002861023
TextLabel.BorderColor3 = Color3.new(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Size = UDim2.new(0, 371, 0, 178)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "gui by v1pejames disc:Wtrv6UB For more information visit the Thread"
TextLabel.TextColor3 = Color3.new(0, 0, 0)
TextLabel.TextSize = 24
TextLabel.TextWrapped = true
 
Teleports.Name = "Teleports"
Teleports.Parent = Main
Teleports.BackgroundColor3 = Color3.new(0, 0, 0)
Teleports.BackgroundTransparency = 0.89999997615814
Teleports.BorderColor3 = Color3.new(0, 0, 0)
Teleports.BorderSizePixel = 0
Teleports.Position = UDim2.new(0, 0, 0.219298244, 0)
Teleports.Size = UDim2.new(0, 371, 0, 178)
Teleports.Visible = false
 
UIGridLayout_3.Parent = Teleports
UIGridLayout_3.HorizontalAlignment = Enum.HorizontalAlignment.Center
UIGridLayout_3.SortOrder = Enum.SortOrder.LayoutOrder
UIGridLayout_3.CellPadding = UDim2.new(0, 7, 0, 7)
UIGridLayout_3.CellSize = UDim2.new(0, 100, 0, 50)
 
SpawnPoint.Name = "SpawnPoint"
SpawnPoint.Parent = Teleports
SpawnPoint.BackgroundColor3 = Color3.new(0.384314, 0.2, 0.2)
SpawnPoint.BorderColor3 = Color3.new(0, 0, 0)
SpawnPoint.BorderSizePixel = 0
SpawnPoint.Size = UDim2.new(0, 200, 0, 50)
SpawnPoint.Font = Enum.Font.SourceSans
SpawnPoint.Text = "SpawnPoint"
SpawnPoint.TextColor3 = Color3.new(0, 0, 0)
SpawnPoint.TextSize = 24
 
SkiLodge.Name = "SkiLodge"
SkiLodge.Parent = Teleports
SkiLodge.BackgroundColor3 = Color3.new(0.384314, 0.2, 0.2)
SkiLodge.BorderColor3 = Color3.new(0, 0, 0)
SkiLodge.BorderSizePixel = 0
SkiLodge.Size = UDim2.new(0, 200, 0, 50)
SkiLodge.Font = Enum.Font.SourceSans
SkiLodge.Text = "SkiLodge"
SkiLodge.TextColor3 = Color3.new(0, 0, 0)
SkiLodge.TextSize = 24
 
TheDen.Name = "TheDen"
TheDen.Parent = Teleports
TheDen.BackgroundColor3 = Color3.new(0.384314, 0.2, 0.2)
TheDen.BorderColor3 = Color3.new(0, 0, 0)
TheDen.BorderSizePixel = 0
TheDen.Size = UDim2.new(0, 200, 0, 50)
TheDen.Font = Enum.Font.SourceSans
TheDen.Text = "TheDen"
TheDen.TextColor3 = Color3.new(0, 0, 0)
TheDen.TextSize = 24
 
ShrineOfSight.Name = "ShrineOfSight"
ShrineOfSight.Parent = Teleports
ShrineOfSight.BackgroundColor3 = Color3.new(0.384314, 0.2, 0.2)
ShrineOfSight.BorderColor3 = Color3.new(0, 0, 0)
ShrineOfSight.BorderSizePixel = 0
ShrineOfSight.Size = UDim2.new(0, 200, 0, 50)
ShrineOfSight.Font = Enum.Font.SourceSans
ShrineOfSight.Text = "ShrineOfSight"
ShrineOfSight.TextColor3 = Color3.new(0, 0, 0)
ShrineOfSight.TextSize = 24
 
Bridge.Name = "Bridge"
Bridge.Parent = Teleports
Bridge.BackgroundColor3 = Color3.new(0.384314, 0.2, 0.2)
Bridge.BorderColor3 = Color3.new(0, 0, 0)
Bridge.BorderSizePixel = 0
Bridge.Size = UDim2.new(0, 200, 0, 50)
Bridge.Font = Enum.Font.SourceSans
Bridge.Text = "Bridge"
Bridge.TextColor3 = Color3.new(0, 0, 0)
Bridge.TextSize = 24
 
Dock.Name = "Dock"
Dock.Parent = Teleports
Dock.BackgroundColor3 = Color3.new(0.384314, 0.2, 0.2)
Dock.BorderColor3 = Color3.new(0, 0, 0)
Dock.BorderSizePixel = 0
Dock.Size = UDim2.new(0, 200, 0, 50)
Dock.Font = Enum.Font.SourceSans
Dock.Text = "Dock"
Dock.TextColor3 = Color3.new(0, 0, 0)
Dock.TextSize = 24
 
FrostTreeArea.Name = "FrostTreeArea"
FrostTreeArea.Parent = Teleports
FrostTreeArea.BackgroundColor3 = Color3.new(0.384314, 0.2, 0.2)
FrostTreeArea.BorderColor3 = Color3.new(0, 0, 0)
FrostTreeArea.BorderSizePixel = 0
FrostTreeArea.Size = UDim2.new(0, 200, 0, 50)
FrostTreeArea.Font = Enum.Font.SourceSans
FrostTreeArea.Text = "FrostTreeArea"
FrostTreeArea.TextColor3 = Color3.new(0, 0, 0)
FrostTreeArea.TextSize = 24
 
SnowGlow.Name = "SnowGlow"
SnowGlow.Parent = Teleports
SnowGlow.BackgroundColor3 = Color3.new(0.384314, 0.2, 0.2)
SnowGlow.BorderColor3 = Color3.new(0, 0, 0)
SnowGlow.BorderSizePixel = 0
SnowGlow.Size = UDim2.new(0, 200, 0, 50)
SnowGlow.Font = Enum.Font.SourceSans
SnowGlow.Text = "SnowGlow"
SnowGlow.TextColor3 = Color3.new(0, 0, 0)
SnowGlow.TextSize = 24
 
VolcanoWin.Name = "VolcanoWin"
VolcanoWin.Parent = Teleports
VolcanoWin.BackgroundColor3 = Color3.new(0.384314, 0.2, 0.2)
VolcanoWin.BorderColor3 = Color3.new(0, 0, 0)
VolcanoWin.BorderSizePixel = 0
VolcanoWin.Size = UDim2.new(0, 200, 0, 50)
VolcanoWin.Font = Enum.Font.SourceSans
VolcanoWin.Text = "VolcanoWin"
VolcanoWin.TextColor3 = Color3.new(0, 0, 0)
VolcanoWin.TextSize = 24
 
EndTimes.Name = "EndTimes"
EndTimes.Parent = Teleports
EndTimes.BackgroundColor3 = Color3.new(0.384314, 0.2, 0.2)
EndTimes.BorderColor3 = Color3.new(0, 0, 0)
EndTimes.BorderSizePixel = 0
EndTimes.Size = UDim2.new(0, 200, 0, 50)
EndTimes.Font = Enum.Font.SourceSans
EndTimes.Text = "EndTimes"
EndTimes.TextColor3 = Color3.new(0, 0, 0)
EndTimes.TextSize = 24
 
BobsShack.Name = "BobsShack"
BobsShack.Parent = Teleports
BobsShack.BackgroundColor3 = Color3.new(0.384314, 0.2, 0.2)
BobsShack.BorderColor3 = Color3.new(0, 0, 0)
BobsShack.BorderSizePixel = 0
BobsShack.Size = UDim2.new(0, 200, 0, 50)
BobsShack.Font = Enum.Font.SourceSans
BobsShack.Text = "BobsShack"
BobsShack.TextColor3 = Color3.new(0, 0, 0)
BobsShack.TextSize = 24
 
FineArtsShop.Name = "FineArtsShop"
FineArtsShop.Parent = Teleports
FineArtsShop.BackgroundColor3 = Color3.new(0.384314, 0.2, 0.2)
FineArtsShop.BorderColor3 = Color3.new(0, 0, 0)
FineArtsShop.BorderSizePixel = 0
FineArtsShop.Size = UDim2.new(0, 200, 0, 50)
FineArtsShop.Font = Enum.Font.SourceSans
FineArtsShop.Text = "FineArtsShop"
FineArtsShop.TextColor3 = Color3.new(0, 0, 0)
FineArtsShop.TextSize = 24
 
BoxedCars.Name = "BoxedCars"
BoxedCars.Parent = Teleports
BoxedCars.BackgroundColor3 = Color3.new(0.384314, 0.2, 0.2)
BoxedCars.BorderColor3 = Color3.new(0, 0, 0)
BoxedCars.BorderSizePixel = 0
BoxedCars.Size = UDim2.new(0, 200, 0, 50)
BoxedCars.Font = Enum.Font.SourceSans
BoxedCars.Text = "BoxedCars"
BoxedCars.TextColor3 = Color3.new(0, 0, 0)
BoxedCars.TextSize = 24
 
FancyFurnishings.Name = "FancyFurnishings"
FancyFurnishings.Parent = Teleports
FancyFurnishings.BackgroundColor3 = Color3.new(0.384314, 0.2, 0.2)
FancyFurnishings.BorderColor3 = Color3.new(0, 0, 0)
FancyFurnishings.BorderSizePixel = 0
FancyFurnishings.Size = UDim2.new(0, 200, 0, 50)
FancyFurnishings.Font = Enum.Font.SourceSans
FancyFurnishings.Text = "FancyFurnishings"
FancyFurnishings.TextColor3 = Color3.new(0, 0, 0)
FancyFurnishings.TextScaled = true
FancyFurnishings.TextSize = 24
FancyFurnishings.TextWrapped = true
 
PalmIsland.Name = "PalmIsland"
PalmIsland.Parent = Teleports
PalmIsland.BackgroundColor3 = Color3.new(0.384314, 0.2, 0.2)
PalmIsland.BorderColor3 = Color3.new(0, 0, 0)
PalmIsland.BorderSizePixel = 0
PalmIsland.Size = UDim2.new(0, 200, 0, 50)
PalmIsland.Font = Enum.Font.SourceSans
PalmIsland.Text = "PalmIsland"
PalmIsland.TextColor3 = Color3.new(0, 0, 0)
PalmIsland.TextSize = 24
 
Swamp.Name = "Swamp"
Swamp.Parent = Teleports
Swamp.BackgroundColor3 = Color3.new(0.384314, 0.2, 0.2)
Swamp.BorderColor3 = Color3.new(0, 0, 0)
Swamp.BorderSizePixel = 0
Swamp.Size = UDim2.new(0, 200, 0, 50)
Swamp.Font = Enum.Font.SourceSans
Swamp.Text = "Swamp"
Swamp.TextColor3 = Color3.new(0, 0, 0)
Swamp.TextSize = 24
 
Volcano.Name = "Volcano"
Volcano.Parent = Teleports
Volcano.BackgroundColor3 = Color3.new(0.384314, 0.2, 0.2)
Volcano.BorderColor3 = Color3.new(0, 0, 0)
Volcano.BorderSizePixel = 0
Volcano.Size = UDim2.new(0, 200, 0, 50)
Volcano.Font = Enum.Font.SourceSans
Volcano.Text = "Volcano"
Volcano.TextColor3 = Color3.new(0, 0, 0)
Volcano.TextSize = 24
 
Cave.Name = "Cave"
Cave.Parent = Teleports
Cave.BackgroundColor3 = Color3.new(0.384314, 0.2, 0.2)
Cave.BorderColor3 = Color3.new(0, 0, 0)
Cave.BorderSizePixel = 0
Cave.Size = UDim2.new(0, 200, 0, 50)
Cave.Font = Enum.Font.SourceSans
Cave.Text = "Cave"
Cave.TextColor3 = Color3.new(0, 0, 0)
Cave.TextSize = 24
 
LinksLogic.Name = "LinksLogic"
LinksLogic.Parent = Teleports
LinksLogic.BackgroundColor3 = Color3.new(0.384314, 0.2, 0.2)
LinksLogic.BorderColor3 = Color3.new(0, 0, 0)
LinksLogic.BorderSizePixel = 0
LinksLogic.Size = UDim2.new(0, 200, 0, 50)
LinksLogic.Font = Enum.Font.SourceSans
LinksLogic.Text = "LinksLogic"
LinksLogic.TextColor3 = Color3.new(0, 0, 0)
LinksLogic.TextSize = 24
 
WoodRUs.Name = "WoodRUs"
WoodRUs.Parent = Teleports
WoodRUs.BackgroundColor3 = Color3.new(0.384314, 0.2, 0.2)
WoodRUs.BorderColor3 = Color3.new(0, 0, 0)
WoodRUs.BorderSizePixel = 0
WoodRUs.Size = UDim2.new(0, 200, 0, 50)
WoodRUs.Font = Enum.Font.SourceSans
WoodRUs.Text = "WoodRUs"
WoodRUs.TextColor3 = Color3.new(0, 0, 0)
WoodRUs.TextSize = 24
 
LandStore.Name = "LandStore"
LandStore.Parent = Teleports
LandStore.BackgroundColor3 = Color3.new(0.384314, 0.2, 0.2)
LandStore.BorderColor3 = Color3.new(0, 0, 0)
LandStore.BorderSizePixel = 0
LandStore.Size = UDim2.new(0, 200, 0, 50)
LandStore.Font = Enum.Font.SourceSans
LandStore.Text = "LandStore"
LandStore.TextColor3 = Color3.new(0, 0, 0)
LandStore.TextSize = 24
-- Scripts:
 
closeexpand.MouseButton1Down:Connect(function()
 ExpandFrame.Visible = false
end)
EXBMain.MouseButton1Down:Connect(function()
Functions.Visible = true
 Info.Visible = false
 Teleports.Visible = false
Functions2.Visible = false
end)
EXBSecond.MouseButton1Down:Connect(function()
 Functions2.Visible = true
 Functions.Visible = false
 Info.Visible = false
 Teleports.Visible = false
end)
EXBTeleports.MouseButton1Down:Connect(function()
 Functions.Visible = false
 Info.Visible = false
Functions2.Visible = false
Teleports.Visible = true
end)
EXBInfo.MouseButton1Down:Connect(function()
 Teleports.Visible = false
Functions.Visible = false
Functions2.Visible = false
Info.Visible = true
end)
CloseB.MouseButton1Down:Connect(function()
    Hi:Destroy()
end)
Mouse = game.Players.LocalPlayer:GetMouse()
Mouse.KeyDown:connect(function(key)
    if key:lower() == "k" then
        if Main.Visible == true then
            Main.Visible = false
        else Main.Visible = true
        end
    end
end)
 
function fly()
    for i,v in pairs(script:GetChildren()) do
    pcall(function() v.Value = "" end)
            game:GetService("Debris"):AddItem(v,.1)
        end
   
        function weld(p0,p1,c0,c1,par)
            local w = Instance.new("Weld",p0 or par)
            w.Part0 = p0
            w.Part1 = p1
            w.C0 = c0 or CFrame.new()
            w.C1 = c1 or CFrame.new()
            return w
        end
   
        local motors = {}
   
        function motor(p0,p1,c0,c1,des,vel,par)
            local w = Instance.new("Motor6D",p0 or par)
            w.Part0 = p0
            w.Part1 = p1
            w.C0 = c0 or CFrame.new()
            w.C1 = c1 or CFrame.new()
            w.MaxVelocity = tonumber(vel) or .05
            w.DesiredAngle = tonumber(des) or 0
            return w
        end
   
        function lerp(a,b,c)
            return a+(b-a)*c
        end
   
        function clerp(c1,c2,al)
            local com1 = {c1.X,c1.Y,c1.Z,c1:toEulerAnglesXYZ()}
            local com2 = {c2.X,c2.Y,c2.Z,c2:toEulerAnglesXYZ()}
            for i,v in pairs(com1) do
                com1[i] = lerp(v,com2[i],al)
            end
            return CFrame.new(com1[1],com1[2],com1[3]) * CFrame.Angles(select(4,unpack(com1)))
        end
   
        function ccomplerp(c1,c2,al)
            local com1 = {c1:components()}
            local com2 = {c2:components()}
            for i,v in pairs(com1) do
                com1[i] = lerp(v,com2[i],al)
            end
            return CFrame.new(unpack(com1))
        end
   
        function tickwave(time,length,offset)
            return (math.abs((tick()+(offset or 0))%time-time/2)*2-time/2)/time/2*length
        end
 
        function invcol(c)
            c = c.Color
            return BrickColor.new(Color3.new(1-c.b,1-c.g,1-c.r))
        end
        local oc = oc or function(...) return ... end
        local plr = game.Players.LocalPlayer
        local char = plr.Character
        local tor = char.Torso
        local hum = char.Humanoid
        hum.PlatformStand = false
        pcall(function()
            char.Wings:Destroy()
        end)
        pcall(function()
            char.Angel:Destroy() -- hat
        end)
        local mod = Instance.new("Model",char)
        mod.Name = "Wings"
        local special = {
            [game.Players.LocalPlayer.Name] = {"Black","Bright red",.5,0,false,Color3.new(1,0,0),Color3.new(0,0,0)},
        }
        local topcolor = BrickColor.new("Really black")
        local feacolor = BrickColor.new("Black")
        local ptrans = 0
        local pref = 0
        local fire = true
        local fmcol = Color3.new()
        local fscol = Color3.new()
        local spec = special[plr.Name:lower()]
        if spec then
            topcolor,feacolor,ptrans,pref,fire,fmcol,fscol = spec[1] and BrickColor.new(spec[1]) or topcolor,spec[2] and BrickColor.new(spec[2]) or feacolor,spec[3],spec[4],spec[5],spec[6],spec[7]
        end
        local part = Instance.new("Part")
        part.FormFactor = "Custom"
        part.Size = Vector3.new(.2,.2,.2)
        part.TopSurface,part.BottomSurface = 0,0
        part.CanCollide = false
        part.BrickColor = BrickColor.new("Black")
        part.Transparency = ptrans
        part.Reflectance = pref
        local ef = Instance.new("Fire",fire and part or nil)
        ef.Size = .15
        ef.Color = BrickColor.new("Black").Color
        ef.SecondaryColor = BrickColor.new("Bright red").Color
        part:BreakJoints()
        function newpart()
            local clone = part:Clone()
            clone.Parent = mod
            clone:BreakJoints()
            return clone
        end
        local feath = newpart()
        feath.BrickColor = feacolor
        feath.Transparency = 0
        Instance.new("SpecialMesh",feath).MeshType = "Sphere"
        function newfeather()
            local clone = feath:Clone()
            clone.Parent = mod
            clone:BreakJoints()
            return clone
        end
        flying = false
        moving = false
        for i,v in pairs(tor:GetChildren()) do
            if v.ClassName:lower():match("body") then
                v:Destroy()
            end
        end
        local ctor = tor:Clone()
        ctor:ClearAllChildren()
        ctor.Name = "cTorso"
        ctor.Transparency = 1
        ctor.CanCollide = false
        ctor.FormFactor = "Custom"
        ctor.Size = Vector3.new(.2,.2,.2)
        ctor.Parent = mod
        weld(tor,ctor)
        local bg = Instance.new("BodyGyro",ctor)
        bg.maxTorque = Vector3.new()
        bg.P = 15000
        bg.D = 1000
        local bv = Instance.new("BodyVelocity",ctor)
        bv.maxForce = Vector3.new()
        bv.P = 15000
        vel = Vector3.new()
        cf = CFrame.new()
        flspd = 0
        keysdown = {}
        keypressed = {}
        ktime = {}
        descendtimer = 0
        jumptime = tick()
        hum.Jumping:connect(function()
            jumptime = tick()
        end)
        cam = workspace.CurrentCamera
        kd = plr:GetMouse().KeyDown:connect(oc(function(key)
            keysdown[key] = true
            keypressed[key] = true
            if key == "q" then
                descendtimer = tick()
            elseif key == " " and not hum.Jump then
                jumptime = tick()
            elseif (key == "a" or key == "d") and ktime[key] and tick()-ktime[key] < .3 and math.abs(reqrotx) < .3 then
                reqrotx = key == "a" and math.pi*2 or -math.pi*2
            end
            ktime[key] = tick()
        end))
   
        ku = plr:GetMouse().KeyUp:connect(function(key)
            keysdown[key] = false
            if key == " " then
                descendtimer = tick()
            end
        end)
        function mid(a,b,c)
            return math.max(a,math.min(b,c or -a))
        end
        function bn(a)
            return a and 1 or 0
        end
        function gm(tar)
            local m = 0
            for i,v in pairs(tar:GetChildren()) do
                if v:IsA("BasePart") then
                    m = m + v:GetMass()
                end
                m = m + gm(v)
            end
            return m
        end
        reqrotx = 0
        local grav = 196.2
        local con
        con = game:GetService("RunService").Stepped:connect(oc(function()
            local obvel = tor.CFrame:vectorToObjectSpace(tor.Velocity)
            local sspd, uspd,fspd = obvel.X,obvel.Y,obvel.Z
            if flying then
                local lfldir = fldir
                fldir = cam.CoordinateFrame:vectorToWorldSpace(Vector3.new(bn(keysdown.d)-bn(keysdown.a),0,bn(keysdown.s)-bn(keysdown.w))).unit
                local lmoving = moving
                moving = fldir.magnitude > .1
                if lmoving and not moving then
                    idledir = lfldir*Vector3.new(1,0,1)
                    descendtimer = tick()
                end
                local dbomb = fldir.Y < -.6 or (moving and keysdown["1"])
                if moving and keysdown["0"] and lmoving then
                    fldir = (Vector3.new(lfldir.X,math.min(fldir.Y,lfldir.Y+.01)-.1,lfldir.Z)+(fldir*Vector3.new(1,0,1))*.05).unit
                end
                local down = tor.CFrame:vectorToWorldSpace(Vector3.new(0,-1,0))
                local descending = (not moving and keysdown["q"] and not keysdown[" "])
                cf = ccomplerp(cf,CFrame.new(tor.Position,tor.Position+(not moving and idledir or fldir)),keysdown["0"] and .02 or .07)
                local gdown = not dbomb and cf.lookVector.Y < -.2 and tor.Velocity.unit.Y < .05
                hum.PlatformStand = true
                bg.maxTorque = Vector3.new(1,1,1)*9e5
                local rotvel = CFrame.new(Vector3.new(),tor.Velocity):toObjectSpace(CFrame.new(Vector3.new(),fldir)).lookVector
                bg.cframe = cf * CFrame.Angles(not moving and -.1 or -math.pi/2+.2,moving and mid(-2.5,rotvel.X/1.5) + reqrotx or 0,0)
                reqrotx = reqrotx - reqrotx/10
                bv.maxForce = Vector3.new(1,1,1)*9e4*.5
                local anioff =(bn(keysdown[" "])-bn(keysdown["q"]))/2
                local ani = tickwave(1.5-anioff,1)
                bv.velocity = bv.velocity:Lerp(Vector3.new(0,bn(not moving)*-ani*15+(descending and math.min(20,tick()-descendtimer)*-8 or bn(keysdown[" "])-bn(keysdown["q"]))*15,0)+vel,.6)
                vel = moving and cf.lookVector*flspd or Vector3.new()
                flspd = math.min(120,lerp(flspd,moving and (fldir.Y<0 and flspd+(-fldir.Y)*grav/60 or math.max(50,flspd-fldir.Y*grav/300)) or 60,.4))
                local hit,ray = workspace:FindPartOnRayWithIgnoreList(Ray.new(tor.Position,Vector3.new(0,-3.5+math.min(0,bv.velocity.y)/30,0)),{char})
                if hit and down.Y < -.85 and tick()-flystart > 1 then
                    flying = false
                    hum.PlatformStand = false
                    tor.Velocity = Vector3.new()
                end
            else
                bg.maxTorque = Vector3.new()
                bv.maxForce = Vector3.new()
                local x,y,z = fspd/160,uspd/700,sspd/900
                if keypressed[" "] and not flying and (tick()-jumptime > .05 and (tick()-jumptime < 3 or hum.Jump)) then
                    vel = Vector3.new(0,50,0)
                    bv.velocity = vel
                    idledir = cam.CoordinateFrame.lookVector*Vector3.new(1,0,1)
                    cf = tor.CFrame * CFrame.Angles(-.01,0,0)
                    tor.CFrame = cf
                    bg.cframe = cf
                    flystart = tick()
                    flying = true
            end
        end
        keypressed = {}
    end))
end
Fly.MouseButton1Down:Connect(function()
    fly()
end)
local WayPoints = {
["Wood R Us"] = CFrame.new(265, 5, 57),
["SpawnPoint"] = CFrame.new(155, 5, 74),
["Land Store"] = CFrame.new(258, 5, -99),
["Link's Logic"] = CFrame.new(4607, 9, -798),
["Cave"] = CFrame.new(3581, -177, 430),
["Volcano"] = CFrame.new(-1585, 625, 1140),
["Swamp"] = CFrame.new(-1209, 138, -801),
["Palm Island"] = CFrame.new(2549, 5, -42),
["Fancy Furnishings"] = CFrame.new(491, 13, -1720),
["Boxed Cars"] = CFrame.new(509, 5.2, -1463),
["Fine Arts Shop"] = CFrame.new(5207, -156, 719),
["Bob's Shack"] = CFrame.new(260, 10, -2542),
["Dock"] = CFrame.new(1114, 3.2, -197),
["Bridge"] = CFrame.new(113, 15, -977),
["End Times"] = CFrame.new(113, -204, -951),
["Shrine Of Sight"] = CFrame.new(-1600, 205, 919),
["The Den"] = CFrame.new(323, 49, 1930),
["Volcano Win"] = CFrame.new(-1675, 358, 1476),
["Ski Lodge"] = CFrame.new(1244, 66, 2306),
["Strange Man"] = CFrame.new(1061, 20, 1131),
["Frost Tree"] = CFrame.new(1448.3, 413, 3185.2),
["SnowGlow Tree"] = CFrame.new(-1105.9, -6, -894)
}
 
WoodRUs.MouseButton1Down:connect(function()
    local uTorso = workspace:WaitForChild(game.Players.LocalPlayer.Name).HumanoidRootPart
    uTorso.CFrame = WayPoints["Wood R Us"]
end)
 
SpawnPoint.MouseButton1Down:connect(function()
    local uTorso = workspace:WaitForChild(game.Players.LocalPlayer.Name).HumanoidRootPart
    uTorso.CFrame = WayPoints["SpawnPoint"]
end)
 
LandStore.MouseButton1Down:connect(function()
    local uTorso = workspace:WaitForChild(game.Players.LocalPlayer.Name).HumanoidRootPart
    uTorso.CFrame = WayPoints["Land Store"]
end)
 
LinksLogic.MouseButton1Down:connect(function()
    local uTorso = workspace:WaitForChild(game.Players.LocalPlayer.Name).HumanoidRootPart
    uTorso.CFrame = WayPoints["Link's Logic"]
end)
 
Cave.MouseButton1Down:connect(function()
    local uTorso = workspace:WaitForChild(game.Players.LocalPlayer.Name).HumanoidRootPart
    uTorso.CFrame = WayPoints["Cave"]
end)
 
Volcano.MouseButton1Down:connect(function()
    local uTorso = workspace:WaitForChild(game.Players.LocalPlayer.Name).HumanoidRootPart
    uTorso.CFrame = WayPoints["Volcano"]
end)
 
Swamp.MouseButton1Down:connect(function()
    local uTorso = workspace:WaitForChild(game.Players.LocalPlayer.Name).HumanoidRootPart
    uTorso.CFrame = WayPoints["Swamp"]
end)
 
PalmIsland.MouseButton1Down:connect(function()
    local uTorso = workspace:WaitForChild(game.Players.LocalPlayer.Name).HumanoidRootPart
    uTorso.CFrame = WayPoints["Palm Island"]
end)
 
FancyFurnishings.MouseButton1Down:connect(function()
    local uTorso = workspace:WaitForChild(game.Players.LocalPlayer.Name).HumanoidRootPart
    uTorso.CFrame = WayPoints["Fancy Furnishings"]
end)
 
BoxedCars.MouseButton1Down:connect(function()
    local uTorso = workspace:WaitForChild(game.Players.LocalPlayer.Name).HumanoidRootPart
    uTorso.CFrame = WayPoints["Boxed Cars"]
end)
 
FineArtsShop.MouseButton1Down:connect(function()
    local uTorso = workspace:WaitForChild(game.Players.LocalPlayer.Name).HumanoidRootPart
    uTorso.CFrame = WayPoints["Fine Arts Shop"]
end)
 
BobsShack.MouseButton1Down:connect(function()
    local uTorso = workspace:WaitForChild(game.Players.LocalPlayer.Name).HumanoidRootPart
    uTorso.CFrame = WayPoints["Bob's Shack"]
end)
 
Dock.MouseButton1Down:connect(function()
    local uTorso = workspace:WaitForChild(game.Players.LocalPlayer.Name).HumanoidRootPart
    uTorso.CFrame = WayPoints["Dock"]
end)
 
Bridge.MouseButton1Down:connect(function()
    local uTorso = workspace:WaitForChild(game.Players.LocalPlayer.Name).HumanoidRootPart
    uTorso.CFrame = WayPoints["Bridge"]
end)
 
EndTimes.MouseButton1Down:connect(function()
    local uTorso = workspace:WaitForChild(game.Players.LocalPlayer.Name).HumanoidRootPart
    uTorso.CFrame = WayPoints["End Times"]
end)
 
ShrineOfSight.MouseButton1Down:connect(function()
    local uTorso = workspace:WaitForChild(game.Players.LocalPlayer.Name).HumanoidRootPart
    uTorso.CFrame = WayPoints["Shrine Of Sight"]
end)
 
TheDen.MouseButton1Down:connect(function()
    local uTorso = workspace:WaitForChild(game.Players.LocalPlayer.Name).HumanoidRootPart
    uTorso.CFrame = WayPoints["The Den"]
end)
 
VolcanoWin.MouseButton1Down:connect(function()
    local uTorso = workspace:WaitForChild(game.Players.LocalPlayer.Name).HumanoidRootPart
    uTorso.CFrame = WayPoints["Volcano Win"]
end)
 
SkiLodge.MouseButton1Down:connect(function()
    local uTorso = workspace:WaitForChild(game.Players.LocalPlayer.Name).HumanoidRootPart
    uTorso.CFrame = WayPoints["Ski Lodge"]
end)
 
 
 
FrostTreeArea.MouseButton1Down:connect(function()
    local uTorso = workspace:WaitForChild(game.Players.LocalPlayer.Name).HumanoidRootPart
    uTorso.CFrame = WayPoints["Frost Tree"]
end)
 
SnowGlow.MouseButton1Down:connect(function()
    local uTorso = workspace:WaitForChild(game.Players.LocalPlayer.Name).HumanoidRootPart
    uTorso.CFrame = WayPoints["SnowGlow Tree"]
end)
 
MaxLand.MouseButton1Down:Connect(function()
for i, v in pairs(game:GetService("Workspace").Properties:GetChildren()) do
        if v:FindFirstChild("Owner") and v.Owner.Value == game.Players.LocalPlayer then
            base = v
            square = v.OriginSquare
            end
        end
    function makebase(pos)
        local Event = game:GetService("ReplicatedStorage").PropertyPurchasing.ClientExpandedProperty
        Event:FireServer(base, pos)
        end
    spos = square.Position
    makebase(CFrame.new(spos.X + 40, spos.Y, spos.Z))
    makebase(CFrame.new(spos.X - 40, spos.Y, spos.Z))
    makebase(CFrame.new(spos.X, spos.Y, spos.Z + 40))
    makebase(CFrame.new(spos.X, spos.Y, spos.Z - 40))
    makebase(CFrame.new(spos.X + 40, spos.Y, spos.Z + 40))
    makebase(CFrame.new(spos.X + 40, spos.Y, spos.Z - 40))
    makebase(CFrame.new(spos.X - 40, spos.Y, spos.Z + 40))
    makebase(CFrame.new(spos.X - 40, spos.Y, spos.Z - 40))
    makebase(CFrame.new(spos.X + 80, spos.Y, spos.Z))
    makebase(CFrame.new(spos.X - 80, spos.Y, spos.Z))
    makebase(CFrame.new(spos.X, spos.Y, spos.Z + 80))
    makebase(CFrame.new(spos.X, spos.Y, spos.Z - 80))
--Corners--
    makebase(CFrame.new(spos.X + 80, spos.Y, spos.Z + 80))
    makebase(CFrame.new(spos.X + 80, spos.Y, spos.Z - 80))
    makebase(CFrame.new(spos.X - 80, spos.Y, spos.Z + 80))
    makebase(CFrame.new(spos.X - 80, spos.Y, spos.Z - 80))
--Corners--
    makebase(CFrame.new(spos.X + 40, spos.Y, spos.Z + 80))
    makebase(CFrame.new(spos.X - 40, spos.Y, spos.Z + 80))
    makebase(CFrame.new(spos.X + 80, spos.Y, spos.Z + 40))
    makebase(CFrame.new(spos.X + 80, spos.Y, spos.Z - 40))
    makebase(CFrame.new(spos.X - 80, spos.Y, spos.Z + 40))
    makebase(CFrame.new(spos.X - 80, spos.Y, spos.Z - 40))
    makebase(CFrame.new(spos.X + 40, spos.Y, spos.Z - 80))
    makebase(CFrame.new(spos.X - 40, spos.Y, spos.Z - 80))
 
end)
 
InfWires.MouseButton1Down:Connect(function()
        for i,v in next,game.ReplicatedStorage.Purchasables.WireObjects:GetChildren() do
  if v:FindFirstChild("Type") then
      if v.Type.Value == "Wire" then
          v.Type.Parent.OtherInfo.MaxLength.Value = math.huge
      end
  end
end
end)
GodAxe.MouseButton1Down:Connect(function()
Detect = coroutine.wrap(function()
    Player = game.Players.LocalPlayer
    mouse = Player:GetMouse()
    mouse.Button1Down:connect(function()
        MouseDown = true
    end)
    mouse.Button1Up:connect(function()
        MouseDown = false
    end)
end)
Detect()
Player = game.Players.LocalPlayer
 
mouse = Player:GetMouse()
for i = 1,50 do
wait(.5)
game:GetService('RunService').RenderStepped:connect(function()
    if Player.Character:FindFirstChild("Tool") then
        if MouseDown == true then
            if mouse.Target.Name == "WoodSection" then
                targetWood = mouse.Target
                Tool=Player.Character.Tool
                ---FaceVector
                Height = targetWood.CFrame:pointToObjectSpace(mouse.Hit.p).Y + targetWood.Size.Y/2
                local ray = Ray.new(Player.Character.Head.Position, ((targetWood.CFrame * CFrame.new(0, Height - targetWood.Size.Y/2, 0)).p - Player.Character.Head.Position).unit * 200)
                part,_,p = workspace:FindPartOnRay(ray, Player.Character)
                function fixVector(V)
                    return Vector3.new(math.floor(V.X + 0.5), math.floor(V.Y + 0.5), math.floor(V.Z + 0.5))
                end
                local faceVector = fixVector(targetWood.CFrame:vectorToObjectSpace(p))
                if faceVector.Y ~= 0 then
                    return
                end
                local lookAtCFrame = CFrame.new(Player.Character.Head.Position, mouse.Hit.p)
                local relativeCFrame = lookAtCFrame:toObjectSpace(targetWood.CFrame * CFrame.Angles(math.pi/2, 0, 0))
                local relativeLookVector = relativeCFrame.lookVector
                local m = relativeLookVector.Y >= 0 and 1 or -1
                if faceVector.X == 1 then
                    faceVector = Vector3.new(0, 0, -1) * m
                elseif faceVector.X == -1 then
                    faceVector = Vector3.new(0, 0, 1) * m
                elseif faceVector.Z == 1 then
                    faceVector = Vector3.new(1, 0, 0) * m
                elseif faceVector.Z == -1 then
                    faceVector = Vector3.new(-1, 0, 0) * m
                end
                local cutEvent = targetWood.Parent.CutEvent
                game.ReplicatedStorage.Interaction.RemoteProxy:FireServer(cutEvent, {sectionId = targetWood.ID.Value, faceVector = faceVector, height = Height, hitPoints = 0.2, cooldown = 0, cuttingClass = "Axe", tool = Player.Character.Tool})
            end
        end
    end
end)
end
end)
WipeBase.Text = "GlitchShopItems"
WipeBase.MouseButton1Down:Connect(function()
    local plr = game.Players.LocalPlayer
local torso = plr.Character.HumanoidRootPart
 
local delaybeweenchecks = 0.5
local opendistance = 10
 
for i, v in pairs(game:GetService("Workspace").Stores.ShopItems:GetChildren()) do
local A_1 = v
local Event = game:GetService("ReplicatedStorage").Interaction.ClientIsDragging
Event:FireServer(A_1)
end
end)
SellTree.MouseButton1Down:Connect(function()
Mouse = game.Players.LocalPlayer:GetMouse()
   
Mouse.KeyDown:connect(function(key)
if key:lower() == "h" then
    for _, Log in pairs(game.Workspace.LogModels:GetChildren()) do
        if Log.Name:sub(1, 6) == "Loose_" and Log:findFirstChild("Owner") then
            if Log.Owner.Value == game.Players.LocalPlayer then
                for i,v in pairs(Log:GetChildren()) do
                    if v.Name=="WoodSection" then
                        spawn(function()
                            for i=1,10 do
                                wait()
                                v.CFrame=CFrame.new(Vector3.new(315, -0.296, 85.791))*CFrame.Angles(math.rad(90),0,0)
                            end
                        end)
                    end
                end
                spawn(function()
                    for i=1,20 do
                        wait()
                        game.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(Log)
                    end
                end)
            end
        end
    end
end
end)
end)
SellPlank.MouseButton1Down:Connect(function()
 
Mouse = game.Players.LocalPlayer:GetMouse()
Mouse.KeyDown:Connect(function(key)
    for _, Plank in pairs(service.Workspace.PlayerModels:GetChildren()) do
        if Plank.Name=="Plank" and Plank:findFirstChild("Owner") then
            if Plank.Owner.Value == service.Players.LocalPlayer then
                for i,v in pairs(Plank:GetChildren()) do
                    if key:lower() == "g" then
                        if Mouse.Target == v then
                          v.Name="WoodSection"
                        spawn(function()
                            for i=1,10 do
                                wait()
                                v.CFrame=CFrame.new(Vector3.new(315, -0.296, 85.791))*CFrame.Angles(math.rad(90),0,0)
                            end
                        end)
                      end
                    end
                end
                spawn(function()
                    for i=1,20 do
                        wait()
                        service.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(Plank)
                    end
                end)
            end
        end
    end
end)
end)
 
PlotTp.MouseButton1Down:connect(function()
Mouse.KeyDown:Connect(function(key)
    if key:lower() =="m" then
    for i,v in pairs(game.Workspace.Properties:GetChildren()) do
        if v.Owner.Value == game.Players.LocalPlayer then
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.OriginSquare.CFrame + Vector3.new(0,10,0)
        end
    end
end
end)
end)
AntiBlacklist.MouseButton1Down:Connect(function()
    local plr = game.Players.LocalPlayer
    local cframe
    for i,v in next, workspace:GetDescendants() do
        if v:IsA("SpawnLocation") then
            v.Touched:Connect(function(h)
            if h.Parent == plr.Character and cframe then
                plr.Character:SetPrimaryPartCFrame(cframe)
                end
            end)
        end
    end
 
    game:GetService("RunService"):BindToRenderStep("NO HACKS",Enum.RenderPriority.Last.Value,function()
    if game.Players.LocalPlayer.Character.PrimaryPart then
        cframe = game.Players.LocalPlayer.Character.PrimaryPart.CFrame
        end
    end)
 
    for i,v in next, debug.getregistry() do
        if type(v)=='function' and debug.getupvalues(v).lastUpdate then
            debug.setupvalue(v,"lastUpdate",math.huge)
            break
        end
    end
wait(2)
    for i,v in next, workspace.Effects:GetChildren() do
        if v:IsA("BasePart") and v.Name == "BlacklistWall" then
            v:Destroy()
        end
    end
end)
WoodTool.MouseButton1Down:Connect(function()
    -- Instances:
local ColorPicker = Instance.new("ScreenGui")
local ChangeColor = Instance.new("Frame")
local CurrentColor = Instance.new("ImageButton")
local Picker = Instance.new("ScrollingFrame")
local Birch = Instance.new("ImageButton")
local DropShadow = Instance.new("Frame")
local Grey = Instance.new("ImageButton")
local DropShadow_2 = Instance.new("Frame")
local Walnut = Instance.new("ImageButton")
local DropShadow_3 = Instance.new("Frame")
local Generic = Instance.new("ImageButton")
local DropShadow_4 = Instance.new("Frame")
local Oak = Instance.new("ImageButton")
local DropShadow_5 = Instance.new("Frame")
local Pine = Instance.new("ImageButton")
local DropShadow_6 = Instance.new("Frame")
local Palm = Instance.new("ImageButton")
local DropShadow_7 = Instance.new("Frame")
local Cherry = Instance.new("ImageButton")
local DropShadow_8 = Instance.new("Frame")
local Koa = Instance.new("ImageButton")
local DropShadow_9 = Instance.new("Frame")
local Volcano = Instance.new("ImageButton")
local DropShadow_10 = Instance.new("Frame")
local GreenSwampy = Instance.new("ImageButton")
local DropShadow_11 = Instance.new("Frame")
local GoldSwampy = Instance.new("ImageButton")
local DropShadow_12 = Instance.new("Frame")
local GenericSpecial = Instance.new("ImageButton")
local DropShadow_13 = Instance.new("Frame")
local SnowGlow = Instance.new("ImageButton")
local DropShadow_14 = Instance.new("Frame")
local Frost = Instance.new("ImageButton")
local DropShadow_15 = Instance.new("Frame")
local CaveCrawler = Instance.new("ImageButton")
local DropShadow_16 = Instance.new("Frame")
local LoneCave = Instance.new("ImageButton")
local DropShadow_17 = Instance.new("Frame")
local Spooky = Instance.new("ImageButton")
local DropShadow_18 = Instance.new("Frame")
local SpookyNeon = Instance.new("ImageButton")
local DropShadow_19 = Instance.new("Frame")
--Properties:
ColorPicker.Name = "ColorPicker"
ColorPicker.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
 
ChangeColor.Name = "ChangeColor"
ChangeColor.Parent = ColorPicker
ChangeColor.BackgroundColor3 = Color3.new(0.176471, 0.254902, 0.427451)
ChangeColor.BorderColor3 = Color3.new(0, 0, 0)
ChangeColor.BorderSizePixel = 2
ChangeColor.Position = UDim2.new(0, 10, 1, -110)
ChangeColor.Size = UDim2.new(0, 100, 0, 100)
ChangeColor.ZIndex = 2
ColorPicker.Enabled = false
 
CurrentColor.Name = "CurrentColor"
CurrentColor.Parent = ChangeColor
CurrentColor.BackgroundColor3 = Color3.new(0.176471, 0.254902, 0.427451)
CurrentColor.BorderColor3 = Color3.new(0, 0, 0)
CurrentColor.BorderSizePixel = 2
CurrentColor.Position = UDim2.new(0, 10, 0, 10)
CurrentColor.Size = UDim2.new(0, 80, 0, 80)
CurrentColor.ZIndex = 2
CurrentColor.Image = "rbxassetid://2712547918"
CurrentColor.ScaleType = Enum.ScaleType.Crop
 
Picker.Name = "Picker"
Picker.Parent = ColorPicker
Picker.BackgroundColor3 = Color3.new(0.176471, 0.254902, 0.427451)
Picker.BorderColor3 = Color3.new(0, 0, 0)
Picker.BorderSizePixel = 2
Picker.Position = UDim2.new(0, 10, 1, -320)
Picker.Size = UDim2.new(0, 100, 0, 200)
Picker.CanvasPosition = Vector2.new(0, 700)
Picker.CanvasSize = UDim2.new(0, 0, 0, 900)
Picker.ScrollBarThickness = 7
Picker.VerticalScrollBarPosition = Enum.VerticalScrollBarPosition.Left
Picker.Visible = false
 
Birch.Name = "Birch"
Birch.Parent = Picker
Birch.BackgroundColor3 = Color3.new(1, 1, 1)
Birch.BorderColor3 = Color3.new(0, 0, 0)
Birch.Position = UDim2.new(0, 10, 0, 5)
Birch.Size = UDim2.new(0, 80, 0, 40)
Birch.ZIndex = 3
Birch.Image = "rbxassetid://2712547918"
Birch.ScaleType = Enum.ScaleType.Crop
 
DropShadow.Name = "DropShadow"
DropShadow.Parent = Birch
DropShadow.BackgroundColor3 = Color3.new(0, 0, 0)
DropShadow.BorderSizePixel = 0
DropShadow.Position = UDim2.new(0, 4, 0, 4)
DropShadow.Size = UDim2.new(1, 0, 1, 0)
DropShadow.ZIndex = 2
 
Grey.Name = "Grey"
Grey.Parent = Picker
Grey.BackgroundColor3 = Color3.new(1, 1, 1)
Grey.BorderColor3 = Color3.new(0, 0, 0)
Grey.Position = UDim2.new(0, 10, 0, 55)
Grey.Size = UDim2.new(0, 80, 0, 40)
Grey.ZIndex = 3
Grey.Image = "rbxassetid://924320031"
Grey.ScaleType = Enum.ScaleType.Crop
 
DropShadow_2.Name = "DropShadow"
DropShadow_2.Parent = Grey
DropShadow_2.BackgroundColor3 = Color3.new(0, 0, 0)
DropShadow_2.BorderSizePixel = 0
DropShadow_2.Position = UDim2.new(0, 4, 0, 4)
DropShadow_2.Size = UDim2.new(1, 0, 1, 0)
DropShadow_2.ZIndex = 2
 
Walnut.Name = "Walnut"
Walnut.Parent = Picker
Walnut.BackgroundColor3 = Color3.new(1, 1, 1)
Walnut.BorderColor3 = Color3.new(0, 0, 0)
Walnut.Position = UDim2.new(0, 10, 0, 105)
Walnut.Size = UDim2.new(0, 80, 0, 40)
Walnut.ZIndex = 3
Walnut.Image = "rbxassetid://2712559790"
Walnut.ScaleType = Enum.ScaleType.Crop
 
DropShadow_3.Name = "DropShadow"
DropShadow_3.Parent = Walnut
DropShadow_3.BackgroundColor3 = Color3.new(0, 0, 0)
DropShadow_3.BorderSizePixel = 0
DropShadow_3.Position = UDim2.new(0, 4, 0, 4)
DropShadow_3.Size = UDim2.new(1, 0, 1, 0)
DropShadow_3.ZIndex = 2
 
Generic.Name = "Generic"
Generic.Parent = Picker
Generic.BackgroundColor3 = Color3.new(1, 1, 1)
Generic.BorderColor3 = Color3.new(0, 0, 0)
Generic.Position = UDim2.new(0, 10, 0, 155)
Generic.Size = UDim2.new(0, 80, 0, 40)
Generic.ZIndex = 3
Generic.Image = "rbxassetid://2712568624"
Generic.ScaleType = Enum.ScaleType.Crop
 
DropShadow_4.Name = "DropShadow"
DropShadow_4.Parent = Generic
DropShadow_4.BackgroundColor3 = Color3.new(0, 0, 0)
DropShadow_4.BorderSizePixel = 0
DropShadow_4.Position = UDim2.new(0, 4, 0, 4)
DropShadow_4.Size = UDim2.new(1, 0, 1, 0)
DropShadow_4.ZIndex = 2
 
Oak.Name = "Oak"
Oak.Parent = Picker
Oak.BackgroundColor3 = Color3.new(1, 1, 1)
Oak.BorderColor3 = Color3.new(0, 0, 0)
Oak.Position = UDim2.new(0, 10, 0, 205)
Oak.Size = UDim2.new(0, 80, 0, 40)
Oak.ZIndex = 3
Oak.Image = "rbxassetid://2712579185"
Oak.ScaleType = Enum.ScaleType.Crop
 
DropShadow_5.Name = "DropShadow"
DropShadow_5.Parent = Oak
DropShadow_5.BackgroundColor3 = Color3.new(0, 0, 0)
DropShadow_5.BorderSizePixel = 0
DropShadow_5.Position = UDim2.new(0, 4, 0, 4)
DropShadow_5.Size = UDim2.new(1, 0, 1, 0)
DropShadow_5.ZIndex = 2
 
Pine.Name = "Pine"
Pine.Parent = Picker
Pine.BackgroundColor3 = Color3.new(1, 1, 1)
Pine.BorderColor3 = Color3.new(0, 0, 0)
Pine.Position = UDim2.new(0, 10, 0, 255)
Pine.Size = UDim2.new(0, 80, 0, 40)
Pine.ZIndex = 3
Pine.Image = "rbxassetid://2712591183"
Pine.ScaleType = Enum.ScaleType.Crop
 
DropShadow_6.Name = "DropShadow"
DropShadow_6.Parent = Pine
DropShadow_6.BackgroundColor3 = Color3.new(0, 0, 0)
DropShadow_6.BorderSizePixel = 0
DropShadow_6.Position = UDim2.new(0, 4, 0, 4)
DropShadow_6.Size = UDim2.new(1, 0, 1, 0)
DropShadow_6.ZIndex = 2
 
Palm.Name = "Palm"
Palm.Parent = Picker
Palm.BackgroundColor3 = Color3.new(1, 1, 1)
Palm.BorderColor3 = Color3.new(0, 0, 0)
Palm.Position = UDim2.new(0, 10, 0, 305)
Palm.Size = UDim2.new(0, 80, 0, 40)
Palm.ZIndex = 3
Palm.Image = "rbxassetid://2712597395"
Palm.ScaleType = Enum.ScaleType.Crop
 
DropShadow_7.Name = "DropShadow"
DropShadow_7.Parent = Palm
DropShadow_7.BackgroundColor3 = Color3.new(0, 0, 0)
DropShadow_7.BorderSizePixel = 0
DropShadow_7.Position = UDim2.new(0, 4, 0, 4)
DropShadow_7.Size = UDim2.new(1, 0, 1, 0)
DropShadow_7.ZIndex = 2
 
Cherry.Name = "Cherry"
Cherry.Parent = Picker
Cherry.BackgroundColor3 = Color3.new(1, 1, 1)
Cherry.BorderColor3 = Color3.new(0, 0, 0)
Cherry.Position = UDim2.new(0, 10, 0, 355)
Cherry.Size = UDim2.new(0, 80, 0, 40)
Cherry.ZIndex = 3
Cherry.Image = "rbxassetid://2712608599"
Cherry.ScaleType = Enum.ScaleType.Crop
 
DropShadow_8.Name = "DropShadow"
DropShadow_8.Parent = Cherry
DropShadow_8.BackgroundColor3 = Color3.new(0, 0, 0)
DropShadow_8.BorderSizePixel = 0
DropShadow_8.Position = UDim2.new(0, 4, 0, 4)
DropShadow_8.Size = UDim2.new(1, 0, 1, 0)
DropShadow_8.ZIndex = 2
 
Koa.Name = "Koa"
Koa.Parent = Picker
Koa.BackgroundColor3 = Color3.new(1, 1, 1)
Koa.BorderColor3 = Color3.new(0, 0, 0)
Koa.Position = UDim2.new(0, 10, 0, 355)
Koa.Size = UDim2.new(0, 80, 0, 40)
Koa.ZIndex = 3
Koa.Image = "rbxassetid://2712612798"
Koa.ScaleType = Enum.ScaleType.Crop
 
DropShadow_9.Name = "DropShadow"
DropShadow_9.Parent = Koa
DropShadow_9.BackgroundColor3 = Color3.new(0, 0, 0)
DropShadow_9.BorderSizePixel = 0
DropShadow_9.Position = UDim2.new(0, 4, 0, 4)
DropShadow_9.Size = UDim2.new(1, 0, 1, 0)
DropShadow_9.ZIndex = 2
 
Volcano.Name = "Volcano"
Volcano.Parent = Picker
Volcano.BackgroundColor3 = Color3.new(1, 1, 1)
Volcano.BorderColor3 = Color3.new(0, 0, 0)
Volcano.Position = UDim2.new(0, 10, 0, 405)
Volcano.Size = UDim2.new(0, 80, 0, 40)
Volcano.ZIndex = 3
Volcano.Image = "rbxassetid://2712618609"
Volcano.ScaleType = Enum.ScaleType.Crop
 
DropShadow_10.Name = "DropShadow"
DropShadow_10.Parent = Volcano
DropShadow_10.BackgroundColor3 = Color3.new(0, 0, 0)
DropShadow_10.BorderSizePixel = 0
DropShadow_10.Position = UDim2.new(0, 4, 0, 4)
DropShadow_10.Size = UDim2.new(1, 0, 1, 0)
DropShadow_10.ZIndex = 2
 
GreenSwampy.Name = "GreenSwampy"
GreenSwampy.Parent = Picker
GreenSwampy.BackgroundColor3 = Color3.new(1, 1, 1)
GreenSwampy.BorderColor3 = Color3.new(0, 0, 0)
GreenSwampy.Position = UDim2.new(0, 10, 0, 455)
GreenSwampy.Size = UDim2.new(0, 80, 0, 40)
GreenSwampy.ZIndex = 3
GreenSwampy.Image = "rbxassetid://2712623896"
GreenSwampy.ScaleType = Enum.ScaleType.Crop
 
DropShadow_11.Name = "DropShadow"
DropShadow_11.Parent = GreenSwampy
DropShadow_11.BackgroundColor3 = Color3.new(0, 0, 0)
DropShadow_11.BorderSizePixel = 0
DropShadow_11.Position = UDim2.new(0, 4, 0, 4)
DropShadow_11.Size = UDim2.new(1, 0, 1, 0)
DropShadow_11.ZIndex = 2
 
GoldSwampy.Name = "GoldSwampy"
GoldSwampy.Parent = Picker
GoldSwampy.BackgroundColor3 = Color3.new(1, 1, 1)
GoldSwampy.BorderColor3 = Color3.new(0, 0, 0)
GoldSwampy.Position = UDim2.new(0, 10, 0, 505)
GoldSwampy.Size = UDim2.new(0, 80, 0, 40)
GoldSwampy.ZIndex = 3
GoldSwampy.Image = "rbxassetid://2712631457"
GoldSwampy.ScaleType = Enum.ScaleType.Crop
 
DropShadow_12.Name = "DropShadow"
DropShadow_12.Parent = GoldSwampy
DropShadow_12.BackgroundColor3 = Color3.new(0, 0, 0)
DropShadow_12.BorderSizePixel = 0
DropShadow_12.Position = UDim2.new(0, 4, 0, 4)
DropShadow_12.Size = UDim2.new(1, 0, 1, 0)
DropShadow_12.ZIndex = 2
 
GenericSpecial.Name = "GenericSpecial"
GenericSpecial.Parent = Picker
GenericSpecial.BackgroundColor3 = Color3.new(1, 1, 1)
GenericSpecial.BorderColor3 = Color3.new(0, 0, 0)
GenericSpecial.Position = UDim2.new(0, 10, 0, 555)
GenericSpecial.Size = UDim2.new(0, 80, 0, 40)
GenericSpecial.ZIndex = 3
GenericSpecial.Image = "rbxassetid://2712639396"
GenericSpecial.ScaleType = Enum.ScaleType.Crop
 
DropShadow_13.Name = "DropShadow"
DropShadow_13.Parent = GenericSpecial
DropShadow_13.BackgroundColor3 = Color3.new(0, 0, 0)
DropShadow_13.BorderSizePixel = 0
DropShadow_13.Position = UDim2.new(0, 4, 0, 4)
DropShadow_13.Size = UDim2.new(1, 0, 1, 0)
DropShadow_13.ZIndex = 2
 
SnowGlow.Name = "SnowGlow"
SnowGlow.Parent = Picker
SnowGlow.BackgroundColor3 = Color3.new(1, 1, 1)
SnowGlow.BorderColor3 = Color3.new(0, 0, 0)
SnowGlow.Position = UDim2.new(0, 10, 0, 605)
SnowGlow.Size = UDim2.new(0, 80, 0, 40)
SnowGlow.ZIndex = 3
SnowGlow.Image = "rbxassetid://2712651454"
SnowGlow.ScaleType = Enum.ScaleType.Crop
 
DropShadow_14.Name = "DropShadow"
DropShadow_14.Parent = SnowGlow
DropShadow_14.BackgroundColor3 = Color3.new(0, 0, 0)
DropShadow_14.BorderSizePixel = 0
DropShadow_14.Position = UDim2.new(0, 4, 0, 4)
DropShadow_14.Size = UDim2.new(1, 0, 1, 0)
DropShadow_14.ZIndex = 2
 
Frost.Name = "Frost"
Frost.Parent = Picker
Frost.BackgroundColor3 = Color3.new(1, 1, 1)
Frost.BorderColor3 = Color3.new(0, 0, 0)
Frost.Position = UDim2.new(0, 10, 0, 655)
Frost.Size = UDim2.new(0, 80, 0, 40)
Frost.ZIndex = 3
Frost.Image = "rbxassetid://2712667804"
Frost.ScaleType = Enum.ScaleType.Crop
 
DropShadow_15.Name = "DropShadow"
DropShadow_15.Parent = Frost
DropShadow_15.BackgroundColor3 = Color3.new(0, 0, 0)
DropShadow_15.BorderSizePixel = 0
DropShadow_15.Position = UDim2.new(0, 4, 0, 4)
DropShadow_15.Size = UDim2.new(1, 0, 1, 0)
DropShadow_15.ZIndex = 2
 
CaveCrawler.Name = "CaveCrawler"
CaveCrawler.Parent = Picker
CaveCrawler.BackgroundColor3 = Color3.new(1, 1, 1)
CaveCrawler.BorderColor3 = Color3.new(0, 0, 0)
CaveCrawler.Position = UDim2.new(0, 10, 0, 705)
CaveCrawler.Size = UDim2.new(0, 80, 0, 40)
CaveCrawler.ZIndex = 3
CaveCrawler.Image = "rbxassetid://2712673980"
CaveCrawler.ScaleType = Enum.ScaleType.Crop
 
DropShadow_16.Name = "DropShadow"
DropShadow_16.Parent = CaveCrawler
DropShadow_16.BackgroundColor3 = Color3.new(0, 0, 0)
DropShadow_16.BorderSizePixel = 0
DropShadow_16.Position = UDim2.new(0, 4, 0, 4)
DropShadow_16.Size = UDim2.new(1, 0, 1, 0)
DropShadow_16.ZIndex = 2
 
LoneCave.Name = "LoneCave"
LoneCave.Parent = Picker
LoneCave.BackgroundColor3 = Color3.new(1, 1, 1)
LoneCave.BorderColor3 = Color3.new(0, 0, 0)
LoneCave.Position = UDim2.new(0, 10, 0, 755)
LoneCave.Size = UDim2.new(0, 80, 0, 40)
LoneCave.ZIndex = 3
LoneCave.Image = "rbxassetid://2712693147"
LoneCave.ScaleType = Enum.ScaleType.Crop
 
DropShadow_17.Name = "DropShadow"
DropShadow_17.Parent = LoneCave
DropShadow_17.BackgroundColor3 = Color3.new(0, 0, 0)
DropShadow_17.BorderSizePixel = 0
DropShadow_17.Position = UDim2.new(0, 4, 0, 4)
DropShadow_17.Size = UDim2.new(1, 0, 1, 0)
DropShadow_17.ZIndex = 2
 
Spooky.Name = "Spooky"
Spooky.Parent = Picker
Spooky.BackgroundColor3 = Color3.new(1, 1, 1)
Spooky.BorderColor3 = Color3.new(0, 0, 0)
Spooky.Position = UDim2.new(0, 10, 0, 805)
Spooky.Size = UDim2.new(0, 80, 0, 40)
Spooky.ZIndex = 3
Spooky.Image = "rbxassetid://2712696822"
Spooky.ScaleType = Enum.ScaleType.Crop
 
DropShadow_18.Name = "DropShadow"
DropShadow_18.Parent = Spooky
DropShadow_18.BackgroundColor3 = Color3.new(0, 0, 0)
DropShadow_18.BorderSizePixel = 0
DropShadow_18.Position = UDim2.new(0, 4, 0, 4)
DropShadow_18.Size = UDim2.new(1, 0, 1, 0)
DropShadow_18.ZIndex = 2
 
SpookyNeon.Name = "SpookyNeon"
SpookyNeon.Parent = Picker
SpookyNeon.BackgroundColor3 = Color3.new(1, 1, 1)
SpookyNeon.BorderColor3 = Color3.new(0, 0, 0)
SpookyNeon.Position = UDim2.new(0, 10, 0, 855)
SpookyNeon.Size = UDim2.new(0, 80, 0, 40)
SpookyNeon.ZIndex = 3
SpookyNeon.Image = "rbxassetid://2712700047"
SpookyNeon.ScaleType = Enum.ScaleType.Crop
 
DropShadow_19.Name = "DropShadow"
DropShadow_19.Parent = SpookyNeon
DropShadow_19.BackgroundColor3 = Color3.new(0, 0, 0)
DropShadow_19.BorderSizePixel = 0
DropShadow_19.Position = UDim2.new(0, 4, 0, 4)
DropShadow_19.Size = UDim2.new(1, 0, 1, 0)
DropShadow_19.ZIndex = 2
-- Scripts:
woodtype = "Birch"
 
local tool = Instance.new("Tool", game.Players.LocalPlayer.Backpack)
tool.RequiresHandle = false
--tool.RobloxLocked = true
tool.Name = "Paint"
tool.ToolTip = "Changes A Stucture's Wood Type"
tool.Equipped:connect(function(Mouse)
ColorPicker.Enabled = true
Mouse.Button1Down:connect(function()
if Mouse.Target.Parent:FindFirstChild("Type") or Mouse.Target.Parent:FindFirstChild("BlueprintWoodClass") then
local Cframe
if Mouse.Target.Parent:FindFirstChild("MainCFrame") then
Cframe = Mouse.Target.Parent.MainCFrame.Value
else
Cframe = Mouse.Target.Parent.PrimaryPart.CFrame
end
if Mouse.Target.Parent ~= nil then
game.ReplicatedStorage.PlaceStructure.ClientPlacedStructure:FireServer(Mouse.Target.Parent.ItemName.Value, Cframe, game.Players.LocalPlayer, woodtype, Mouse.Target.Parent, false)
end
else
--do nothing
end
end)
end)
 
tool.Unequipped:connect(function(mouse)
ColorPicker.Enabled = false
end)
 
 
Birch.MouseButton1Click:Connect(function()
CurrentColor.Image = Birch.Image
woodtype = "Birch"
end)
 
Grey.MouseButton1Click:Connect(function()
CurrentColor.Image = Grey.Image
woodtype = nil
end)
 
Walnut.MouseButton1Click:Connect(function()
CurrentColor.Image = Walnut.Image
woodtype = "Walnut"
end)
 
Generic.MouseButton1Click:Connect(function()
CurrentColor.Image = Generic.Image
woodtype = "Generic"
end)
 
Oak.MouseButton1Click:Connect(function()
CurrentColor.Image = Oak.Image
woodtype = "Oak"
end)
 
Pine.MouseButton1Click:Connect(function()
CurrentColor.Image = Pine.Image
woodtype = "Pine"
end)
 
Palm.MouseButton1Click:Connect(function()
CurrentColor.Image = Palm.Image
woodtype = "Palm"
end)
 
Koa.MouseButton1Click:Connect(function()
CurrentColor.Image = Koa.Image
woodtype = "Koa"
end)
 
Volcano.MouseButton1Click:Connect(function()
CurrentColor.Image = Volcano.Image
woodtype = "Volcano"
end)
 
GreenSwampy.MouseButton1Click:Connect(function()
CurrentColor.Image = GreenSwampy.Image
woodtype = "GreenSwampy"
end)
 
GoldSwampy.MouseButton1Click:Connect(function()
CurrentColor.Image = GoldSwampy.Image
woodtype = "GoldSwampy"
end)
 
GenericSpecial.MouseButton1Click:Connect(function()
CurrentColor.Image = GenericSpecial.Image
woodtype = "GenericSpecial"
end)
 
SnowGlow.MouseButton1Click:Connect(function()
CurrentColor.Image = SnowGlow.Image
woodtype = "SnowGlow"
end)
 
Frost.MouseButton1Click:Connect(function()
CurrentColor.Image = Frost.Image
woodtype = "Frost"
end)
 
CaveCrawler.MouseButton1Click:Connect(function()
CurrentColor.Image = CaveCrawler.Image
woodtype = "CaveCrawler"
end)
 
LoneCave.MouseButton1Click:Connect(function()
CurrentColor.Image = LoneCave.Image
woodtype = "LoneCave"
end)
 
Spooky.MouseButton1Click:Connect(function()
CurrentColor.Image = Spooky.Image
woodtype = "Spooky"
end)
 
SpookyNeon.MouseButton1Click:Connect(function()
CurrentColor.Image = SpookyNeon.Image
woodtype = "SpookyNeon"
end)
 
--bring up menu
CurrentColor.MouseButton1Click:Connect(function()
if Picker.Visible == false then
Picker.Visible = true
else
Picker.Visible = false
end
end)
 
end)
 
Fastwalk.MouseButton1Down:Connect(function()
game:GetService("UserInputService").InputBegan:connect(onKeyPress)
down = false
velocity = Instance.new("BodyVelocity")
velocity.maxForce = Vector3.new(100000, 0, 100000)
local speed = 35
gyro = Instance.new("BodyGyro")
gyro.maxTorque = Vector3.new(100000, 0, 100000)
 
local hum = game.Players.LocalPlayer.Character.Humanoid
 
function onButton1Down(mouse)
down = true
velocity.Parent = game.Players.LocalPlayer.Character.Torso
velocity.velocity = (hum.MoveDirection) * speed
gyro.Parent = game.Players.LocalPlayer.Character.Torso
while down do
if not down then break end
velocity.velocity = (hum.MoveDirection) * speed
local refpos = gyro.Parent.Position + (gyro.Parent.Position - workspace.CurrentCamera.CoordinateFrame.p).unit * 5
gyro.cframe = CFrame.new(gyro.Parent.Position, Vector3.new(refpos.x, gyro.Parent.Position.y, refpos.z))
wait(0.1)
end
end
 
function onButton1Up(mouse)
velocity.Parent = nil
gyro.Parent = nil
down = false
end
 
function onSelected(mouse)
mouse.KeyDown:connect(function(k) if k:lower()=="x"then onButton1Down(mouse)end end)
mouse.KeyUp:connect(function(k) if k:lower()=="x"then onButton1Up(mouse)end end)
end
 
onSelected(game.Players.LocalPlayer:GetMouse())
end)
BuyItems.Text = "CopyBase"
ExpandButton.MouseButton1Down:Connect(function()
    ExpandFrame.Visible = true
    ExpandButton.Visible = true
end)
SawmillTp.MouseButton1Down:Connect(function()
    SawmillC = false
Mouse = game.Players.LocalPlayer:GetMouse()
_G.MAIN=Instance.new("ScreenGui",game.Players.LocalPlayer.PlayerGui)
Instruction = Instance.new("TextLabel",_G.MAIN)
Instruction.Position = UDim2.new(0,200,0,400)
Instruction.Size = UDim2.new(0,250,0,50)
Instruction.TextWrapped = true
Instruction.TextScaled = true
Instruction.Text = "'Q' to select a tree, Press P to select a sawmill!(Credits to austin k) Select Tree first also works with any item as long as you select the sawmill after selecting the item."
Instruction.Active = true
Instruction.Draggable = true
Instruction.ZIndex = 2
Exit = Instance.new("TextButton",Instruction)
Exit.Position=UDim2.new(1,0,0,0)
Exit.Size = UDim2.new(0,30,0,30)
Exit.Text = "Exit"
Exit.MouseButton1Click:connect(function()
_G.MAIN:Destroy()
end)
Mouse.KeyDown:connect(function(key)
if key:lower() == "q" then
Treee = Mouse.Target
end
end)
Mouse.KeyDown:connect(function(key)
if key:lower() == "p" then
if Mouse.Target.Parent:FindFirstChild("BlockageAlert") then
Sawmill = Mouse.Target.Parent
else
Sawmill=Mouse.Target.Parent.Parent
end
if Sawmill:FindFirstChild("BlockageAlert") and Sawmill:FindFirstChild("Owner") then
SawmillC = true
else
SawmillC = false
print"Something went wrong while setting the sawmill!"
end
if Treee ~= nil then
Mod(Treee)
else
print("Select tree with 'Q'!")
end
end
end)
 
function Mod(SelectedPart)
if SawmillC ~= true then
print'Set the sawmill with "P"!'
return
end
if SelectedPart.Parent:FindFirstChild("TreeClass") and SelectedPart.Parent:FindFirstChild("Owner") then
print("Tree: "..SelectedPart.Parent.TreeClass.Value)
Tree = SelectedPart.Parent
Tree.PrimaryPart = SelectedPart
game.ReplicatedStorage.Interaction.Verify:FireServer('Item owned by player',Tree)
Tree:SetPrimaryPartCFrame(Sawmill.Particles.CFrame)
game.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(Tree)
end
end
end)
Noclip.MouseButton1Down:Connect(function()
    local noclipplayer = game:GetService("Players").LocalPlayer
    local noclipmouse = noclipplayer:GetMouse()
   
    local donoclip = false
    local noclip = false
   
    function b_noclip(key)
        if (key == "b") then
            if noclip == false then
                donoclip = true
               
                noclip = true
            elseif noclip == true then
                donoclip = false
               
                noclip = false
            end
        end
    end
   
    noclipmouse.KeyDown:connect(b_noclip)
   
    game:GetService("Players").LocalPlayer.Character.Head.Touched:connect(function(obj)
        if obj ~= workspace.Terrain then
            if donoclip == true then
                obj.CanCollide = false
            else
                obj.CanCollide = true
            end
        end
    end)  
end)
 
local CopyBase = Instance.new("TextBox")
CopyBase.Name = "CopyBase"
CopyBase.Parent = Menu
CopyBase.BackgroundColor3 = Color3.new(1, 1, 0.498039)
CopyBase.BorderSizePixel = 3
CopyBase.Position = UDim2.new(0.0424746051, 0, 0.40607211, 0)
CopyBase.Size = UDim2.new(0, 200, 0, 50)
CopyBase.Font = Enum.Font.SourceSans
CopyBase.PlaceholderColor3 = Color3.new(0.454902, 0.454902, 0.454902)
CopyBase.PlaceholderText = "Type PlayersNameHere"
CopyBase.Text = ""
CopyBase.TextColor3 = Color3.new(0, 0, 0)
CopyBase.TextSize = 14
CopyBase.Visible = false
CopyBase.Draggable = true
 
BuyItems.MouseButton1Down:Connect(function()
CopyBase.Visible = true
plr = CopyBase.Text
pmds = game.Workspace.PlayerModels
PlaceR = game.ReplicatedStorage.PlaceStructure.ClientPlacedBlueprint
PlaceS = game.ReplicatedStorage.PlaceStructure.ClientPlacedStructure
Property = nil
MProperty = nil
 
for i, v in pairs(game.Workspace.Properties:GetChildren()) do
if v:FindFirstChild("Owner") and v.Owner.Value ~= nil and v.Owner.Value == game.Players[plr] then
Property = v.OriginSquare
end
end
 
for i, v in pairs(game.Workspace.Properties:GetChildren()) do
if v:FindFirstChild("Owner") and v.Owner.Value ~= nil and v.Owner.Value == game.Players.LocalPlayer then
MProperty = v.OriginSquare
end
end
 
 
function copypart(mod)
if mod:FindFirstChild("MainCFrame") then
Cframe = mod.MainCFrame.Value
else
Cframe = mod.PrimaryPart.CFrame
end
X = Property.Position.X - Cframe.X
Y = Property.Position.Y - Cframe.Y
Z = Property.Position.Z - Cframe.Z
PlaceR:FireServer(mod.ItemName.Value, (CFrame.new(MProperty.Position.X, MProperty.Position.Y, MProperty.Position.Z)*CFrame.Angles(Cframe:toEulerAnglesXYZ())) - Vector3.new(X, Y, Z), game.Players.LocalPlayer)
wait()
end
 
 
 
for i, v in pairs(pmds:GetChildren()) do
if v:FindFirstChild("Owner") and v.Owner.Value ~= nil and v.Owner.Value == game.Players[plr] and v:FindFirstChild("ItemName") and v:FindFirstChild("Type") and (v.PrimaryPart ~= nil or v:FindFirstChild("MainCFrame")) then
copypart(v)
end
end
wait(.1)
if CopyBase.Text ~= nil then
    CopyBase.Visible = false
end
end)
BuyBlueprints.Text = "WipeBase(BP)"
 
 
BuyBlueprints.MouseButton1Down:Connect(function()
   
plr = game.Players.LocalPlayer.Name
pmds = game.Workspace.PlayerModels
PlaceR = game.ReplicatedStorage.Interaction.DestroyStructure
 
 
 
for i, v in pairs(pmds:GetChildren()) do
if v:FindFirstChild("Owner") and v.Owner.Value ~= nil and v.Owner.Value == game.Players[plr] and v:FindFirstChild("ItemName") and v:FindFirstChild("Type") and (v.PrimaryPart ~= nil or v:FindFirstChild("MainCFrame")) then
PlaceR:FireServer(v)
end
end
 
end)
Noclip.MouseButton1Down:Connet(function()
    local noclipplayer = game:GetService("Players").LocalPlayer
    local noclipmouse = noclipplayer:GetMouse()
   
    local donoclip = false
    local noclip = false
   
    function b_noclip(key)
        if (key == "n") then
            if noclip == false then
                donoclip = true
               
                noclip = true
            elseif noclip == true then
                donoclip = false
               
                noclip = false
            end
        end
    end
   
    noclipmouse.KeyDown:connect(b_noclip)
   
    game:GetService("Players").LocalPlayer.Character.Head.Touched:connect(function(obj)
        if obj ~= workspace.Terrain then
            if donoclip == true then
                obj.CanCollide = false
            else
                obj.CanCollide = true
            end
        end
    end)
end)
end)
OpGui.MouseButton1Down:Connect(function()
-- Farewell Infortality.
-- Version: 2.82
-- Instances:
local ScreenGui = Instance.new("ScreenGui")
local MainFrame = Instance.new("Frame")
local ExitButton = Instance.new("TextButton")
local MiniMazeButton = Instance.new("TextButton")
local AutoDupe = Instance.new("TextButton")
local StopDupe = Instance.new("TextButton")
local TpPlanks = Instance.new("TextButton")
local SellPlanks = Instance.new("TextButton")
local BringWood = Instance.new("TextButton")
local SellWood = Instance.new("TextButton")
local NormalLand = Instance.new("TextButton")
local StopLand = Instance.new("TextButton")
local WayPoint = Instance.new("TextButton")
local WayPoint_2 = Instance.new("TextButton")
local TpGifts = Instance.new("TextButton")
local BringUp = Instance.new("TextButton")
local HailStone = Instance.new("TextButton")
local Speed = Instance.new("TextButton")
local Jpower = Instance.new("TextButton")
local GoldAxe = Instance.new("TextButton")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")
local LT2GUD = Instance.new("TextButton")
local DupeGui = Instance.new("TextButton")
local OpenButton = Instance.new("TextButton")
--Properties:
ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

MainFrame.Name = "MainFrame"
MainFrame.Parent = ScreenGui
MainFrame.BackgroundColor3 = Color3.new(0, 0, 0)
MainFrame.Position = UDim2.new(0.0925266892, 0, 0.221343875, 0)
MainFrame.Size = UDim2.new(0, 560, 0, 218)
MainFrame.Active = true 
MainFrame.Draggable = true 

ExitButton.Name = "ExitButton"
ExitButton.Parent = MainFrame
ExitButton.BackgroundColor3 = Color3.new(0, 0, 0)
ExitButton.BorderColor3 = Color3.new(0, 1, 0)
ExitButton.BorderSizePixel = 3
ExitButton.Position = UDim2.new(0, 0, -0.00917431153, 0)
ExitButton.Size = UDim2.new(0, 47, 0, 41)
ExitButton.Font = Enum.Font.SciFi
ExitButton.Text = "x"
ExitButton.TextColor3 = Color3.new(0, 1, 0)
ExitButton.TextScaled = true
ExitButton.TextSize = 14
ExitButton.TextWrapped = true
ExitButton.MouseButton1Click:connect(function()
	MainFrame.Visible = false
	end)
MiniMazeButton.Name = "MiniMazeButton"
MiniMazeButton.Parent = MainFrame
MiniMazeButton.BackgroundColor3 = Color3.new(0, 0, 0)
MiniMazeButton.BorderColor3 = Color3.new(0, 1, 0)
MiniMazeButton.BorderSizePixel = 3
MiniMazeButton.Position = UDim2.new(0.0910714269, 0, -0.00917431153, 0)
MiniMazeButton.Size = UDim2.new(0, 50, 0, 47)
MiniMazeButton.Font = Enum.Font.SciFi
MiniMazeButton.Text = "-"
MiniMazeButton.TextColor3 = Color3.new(0, 1, 0)
MiniMazeButton.TextScaled = true
MiniMazeButton.TextSize = 14
MiniMazeButton.TextWrapped = true
MiniMazeButton.MouseButton1Click:connect(function()
	MainFrame.Visible = false
	OpenButton.Visible = true
end)
AutoDupe.Name = "AutoDupe"
AutoDupe.Parent = MainFrame
AutoDupe.BackgroundColor3 = Color3.new(0, 0, 0)
AutoDupe.BorderColor3 = Color3.new(0, 1, 0)
AutoDupe.BorderSizePixel = 5
AutoDupe.Position = UDim2.new(0.00714285765, 0, 0.426605493, 0)
AutoDupe.Size = UDim2.new(0, 97, 0, 41)
AutoDupe.Font = Enum.Font.SciFi
AutoDupe.Text = "AutoDupe"
AutoDupe.TextColor3 = Color3.new(0, 1, 0)
AutoDupe.TextScaled = true
AutoDupe.TextSize = 14
AutoDupe.TextWrapped = true
AutoDupe.MouseButton1Down:connect(function()
Screen = Instance.new("ScreenGui",game.Players.LocalPlayer.PlayerGui)
Scrolling = Instance.new("ScrollingFrame",Screen)
Scrolling.Size = UDim2.new(0,300,0,500)
Scrolling.CanvasSize = UDim2.new(0,300,3,0)
Exit = Instance.new("TextButton", Scrolling)
Exit.Size = UDim2.new(0,30,0,20)
Exit.Position = UDim2.new(1,-40,0,0)
Exit.Text = "Exit"
DontTP = Instance.new("TextButton", Scrolling)
DontTP.Size = UDim2.new(0,40,0,40)
DontTP.Position = UDim2.new(1,-60,0,50)
DontTP.Text = "Don't TP back"
DontTP.TextWrapped = true
DontTPVar = false
DontTP.MouseButton1Click:connect(function()
	DontTPVar = true
end)
Exit.MouseButton1Click:connect(function()
	Screen:Destroy()
end)
g = 0
Sniggle = false
gg = {}
function Start()
Sniggle = true
for i,v in pairs(game.Workspace.PlayerModels:GetChildren()) do
	if v:FindFirstChild("Owner") and v.Owner.Value == game.Players.LocalPlayer then
		if v:FindFirstChild("TreeClass") then
			game:GetService("RunService").RenderStepped:wait()
			if Scrolling:FindFirstChild(v.TreeClass.Value) then
				if not gg[i] then
					Scrolling[v.TreeClass.Value.." Value"].Value = Scrolling[v.TreeClass.Value.." Value"].Value+1
					Scrolling[v.TreeClass.Value].Text = v.TreeClass.Value.." ("..Scrolling[v.TreeClass.Value.." Value"].Value..")"
				end
			else
				g = g+1
				TreeButton = Instance.new("TextButton",Scrolling)
				TreeButton.Size = UDim2.new(0,100,0,50)
				TreeButton.Position = UDim2.new(0,10,0,70*g)
				TreeButton.Name = v.TreeClass.Value
				TreeButton.Text = v.TreeClass.Value.." (1)"
				TreeButton.MouseButton1Click:connect(function()
					Scrolling.Visible = false
					TP(TreeButton.Name)
				end)
				TreeVal = Instance.new("NumberValue",Scrolling)
				TreeVal.Name = v.TreeClass.Value.." Value"
				TreeVal.Value = 1
				gg[i] = v.TreeClass.Value
			end
		end
	end
end
end
if not Sniggle then
	Start()
end
--[[game.Workspace.PlayerModels.ChildAdded:connect(function(Item)
	Item:WaitForChild("Owner")
	if Item.Owner.Value == game.Players.LocalPlayer then
		Start()
	end
end)]]
game.Workspace.PlayerModels.ChildRemoved:connect(function(Item)
	if Item:FindFirstChild("Owner") and Item.Owner.Value == game.Players.LocalPlayer and Item:FindFirstChild("TreeClass") and Scrolling[Item.TreeClass.Value.." Value"] then
		Scrolling[Item.TreeClass.Value.." Value"].Value = Scrolling[Item.TreeClass.Value.." Value"].Value-1
		if Scrolling[Item.TreeClass.Value.." Value"].Value == 0 then
			Scrolling[Item.TreeClass.Value]:Destroy()
			Scrolling[Item.TreeClass.Value.." Value"]:Destroy()
		else
			Scrolling[Item.TreeClass.Value].Text = Item.TreeClass.Value.." ("..Scrolling[Item.TreeClass.Value.." Value"].Value..")"
		end
	end
end)

function TP(Name)
	sendNotice = game.ReplicatedStorage.Notices.SendUserNotice
	sendNotice:Fire("Click on a whitelisted base")
	local ButtonPress
	ButtonPress = game.Players.LocalPlayer:GetMouse().Button1Down:Connect(function()
		Square = game.Players.LocalPlayer:GetMouse().Target
		if (Square.Name == "OriginSquare" or Square.Name == "Square") then
			ButtonPress:Disconnect()
			game.ReplicatedStorage.LoadSaveRequests.RequestSave:InvokeServer(game.Players.LocalPlayer.CurrentSaveSlot.Value)
			local success, errorMessage = game.ReplicatedStorage.LoadSaveRequests.RequestLoad:InvokeServer(game.Players.LocalPlayer.CurrentSaveSlot.Value,game.Players.LocalPlayer)
			if success then
				print'Initial Reload Success'
				sendNotice:Fire("Reload success", 0.8)
				game.Players.LocalPlayer.CurrentSaveSlot.RobloxLocked = true
				game.Players.LocalPlayer.CurrentSaveSlot.Set.RobloxLocked = true
				for i,v in pairs(game.Workspace.PlayerModels:GetChildren()) do
					if v:FindFirstChild("TreeClass") and v.TreeClass.Value == Name and v.Owner.Value == game.Players.LocalPlayer then
						v:MoveTo(Square.Position)
						v.Name = "TpMe"
						for i=1,10 do
							game:GetService("RunService").RenderStepped:wait()
							for i=1,10 do
								v.WoodSection.CFrame = (CFrame.new(Vector3.new(Square.Position.X,Square.Position.Y+5,Square.Position.Z))*CFrame.Angles(math.rad(90),0,0))
								game.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(v)
							end
						end
					end
				end
				Wait = 0
				while Wait < 60 do
				Wait = Wait + 1
				sendNotice:Fire("Waiting: "..60-Wait,1)
				wait(1)
				end
				local succes, errormessage = game.ReplicatedStorage.LoadSaveRequests.RequestLoad:InvokeServer(game.Players.LocalPlayer.CurrentSaveSlot.Value,game.Players.LocalPlayer)
				if succes then
					sendNotice:Fire("Reload success", 0.8)
					game.Players.LocalPlayer.CurrentSaveSlot.RobloxLocked = false
					game.Players.LocalPlayer.CurrentSaveSlot.Set.RobloxLocked = false
					if not DontTPVar then
					DontTPVar = false
					for i,v in pairs(game.Workspace.Properties:GetChildren()) do
						if v.Owner and v.Owner.Value == game.Players.LocalPlayer and v:FindFirstChild("OriginSquare") then
							Square = v.OriginSquare
							for i,v in pairs(game.Workspace.PlayerModels:GetChildren()) do
								if v.Name == "TpMe" then
									v.Name = "Model"
									print'Secondary Reload Success'
									game.Players.LocalPlayer.CurrentSaveSlot.RobloxLocked = false
									game.Players.LocalPlayer.CurrentSaveSlot.Set.RobloxLocked = false
									game.ReplicatedStorage.Interaction.ClientRequestOwnership:FireServer(v)
									v:MoveTo(Square.Position)
									for i=1,10 do
									game:GetService("RunService").RenderStepped:wait()
									for i=1,10 do
										v.WoodSection.CFrame = (CFrame.new(Vector3.new(Square.Position.X,Square.Position.Y+5,Square.Position.Z))*CFrame.Angles(math.rad(90),0,0))
										game.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(v)
									end
									end	
									Scrolling.Visible = true
								end
							end
						end
					end
					end
				else
					print('Secondary Reload Error: '..errormessage)
					sendNotice:Fire(errormessage)
				end
			else
				OOF = true
				while OOF do
					wait(0.5)
					local _,Fail = game.ReplicatedStorage.LoadSaveRequests.RequestLoad:InvokeServer(game.Players.LocalPlayer.CurrentSaveSlot.Value,game.Players.LocalPlayer)
					print(string.sub(Fail,49,50))
					if tonumber(string.sub(Fail,49,50)) == 1 then
						OOF = false
					end
					print('Initial Reload Error: '..Fail)
					Deb = true
					sendNotice:Fire("Wait "..string.sub(Fail,49,50),1)
				end
				if Deb then
					Deb = false
					TP(Name)
				end
			end
		end
	end)
	game.Players.LocalPlayer.CurrentSaveSlot.RobloxLocked = false
	game.Players.LocalPlayer.CurrentSaveSlot.Set.RobloxLocked = false
end

function restartStart()

end
--game.ReplicatedStorage.Interaction.ClientIsDragging:FireServer()
--v:MoveTo(game.Players.LocalPlayer.Character.Torso.Position)

--game.Players.LocalPlayer.PlayerGui.ScreenGui:Destroy()
end)	
StopDupe.Name = "StopDupe"
StopDupe.Parent = MainFrame
StopDupe.BackgroundColor3 = Color3.new(0, 0, 0)
StopDupe.BorderColor3 = Color3.new(0, 1, 0)
StopDupe.BorderSizePixel = 5
StopDupe.Position = UDim2.new(0.00714285718, 0, 0.848623872, 0)
StopDupe.Size = UDim2.new(0, 97, 0, 28)
StopDupe.Font = Enum.Font.SciFi
StopDupe.Text = "StopDupe"
StopDupe.TextColor3 = Color3.new(0, 1, 0)
StopDupe.TextScaled = true
StopDupe.TextSize = 14
StopDupe.TextWrapped = true
StopDupe.MouseButton1Down:connect(function()
option = false

a = game.Players.LocalPlayer.CurrentSaveSlot
a.RobloxLocked = option
a.Set.RobloxLocked = option
print(a.Value)

if a.RobloxLocked == true then
print("CurrentSaveSlot RobloxLocked = true, save file won't save")
print("Set RobloxLocked = true, save file won't save")

else

print("CurrentSaveSlot RobloxLocked = false, save file will save")
print("Set RobloxLocked = false, save file will save")
end	
end)
TpPlanks.Name = "TpPlanks"
TpPlanks.Parent = MainFrame
TpPlanks.BackgroundColor3 = Color3.new(0, 0, 0)
TpPlanks.BorderColor3 = Color3.new(0, 1, 0)
TpPlanks.BorderSizePixel = 5
TpPlanks.Position = UDim2.new(0.18928571, 0, 0.848623872, 0)
TpPlanks.Size = UDim2.new(0, 96, 0, 28)
TpPlanks.Font = Enum.Font.SciFi
TpPlanks.Text = "Tp Planks"
TpPlanks.TextColor3 = Color3.new(0, 1, 0)
TpPlanks.TextScaled = true
TpPlanks.TextSize = 14
TpPlanks.TextWrapped = true
TpPlanks.MouseButton1Down:connect(function()
for _, Plank in pairs(service.Workspace.PlayerModels:GetChildren()) do
		if Plank.Name == "Plank" and Plank.Owner.Value==service.Players.LocalPlayer then
			Plank:MoveTo(service.Players.LocalPlayer.Character.HumanoidRootPart.Position + Vector3.new(0, 20, 0))
				for i=1,100 do
					service.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(Plank)
				end
			end
		end
end)	
SellPlanks.Name = "SellPlanks"
SellPlanks.Parent = MainFrame
SellPlanks.BackgroundColor3 = Color3.new(0, 0, 0)
SellPlanks.BorderColor3 = Color3.new(0, 1, 0)
SellPlanks.BorderSizePixel = 5
SellPlanks.Position = UDim2.new(0.5625, 0, 0.646789014, 0)
SellPlanks.Size = UDim2.new(0, 92, 0, 34)
SellPlanks.Font = Enum.Font.SciFi
SellPlanks.Text = "SellPlanks"
SellPlanks.TextColor3 = Color3.new(0, 1, 0)
SellPlanks.TextScaled = true
SellPlanks.TextSize = 14
SellPlanks.TextWrapped = true
SellPlanks.MouseButton1Down:connect(function()
for _, Plank in pairs(service.Workspace.PlayerModels:GetChildren()) do
		if Plank.Name=="Plank" and Plank.Owner.Value==service.Players.LocalPlayer then
				for i,v in pairs(Plank:GetChildren()) do
					if v.Name=="WoodSection" then
						spawn(function()
							for i=1,10 do
								wait()
								v.CFrame=CFrame.new(Vector3.new(315, -0.296, 85.791))*CFrame.Angles(math.rad(90),0,0)
							end
						end)
					end
				end
				spawn(function()
					for i=1,20 do
						wait()
						service.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(Plank)
					end
				end)
			end
		end
end)	
BringWood.Name = "BringWood"
BringWood.Parent = MainFrame
BringWood.BackgroundColor3 = Color3.new(0, 0, 0)
BringWood.BorderColor3 = Color3.new(0, 1, 0)
BringWood.BorderSizePixel = 5
BringWood.Position = UDim2.new(0.5625, 0, 0.211009175, 0)
BringWood.Size = UDim2.new(0, 92, 0, 38)
BringWood.Font = Enum.Font.SciFi
BringWood.Text = "BringWood"
BringWood.TextColor3 = Color3.new(0, 1, 0)
BringWood.TextScaled = true
BringWood.TextSize = 14
BringWood.TextWrapped = true
BringWood.MouseButton1Down:connect(function()
for _, Log in pairs(game.Workspace.LogModels:GetChildren()) do
if Log.Name:sub(1,6) == "Loose_" and Log:findFirstChild("Owner") then
if Log.Owner.Value == game.Players.LocalPlayer then
Log:MoveTo(game.Players.LocalPlayer.Character.Torso.Position + Vector3.new(0,15,0))
end
end
end	
end)
SellWood.Name = "SellWood"
SellWood.Parent = MainFrame
SellWood.BackgroundColor3 = Color3.new(0, 0, 0)
SellWood.BorderColor3 = Color3.new(0, 1, 0)
SellWood.BorderSizePixel = 5
SellWood.Position = UDim2.new(0.00714285765, 0, 0.646789014, 0)
SellWood.Size = UDim2.new(0, 97, 0, 34)
SellWood.Font = Enum.Font.SciFi
SellWood.Text = "SellWood"
SellWood.TextColor3 = Color3.new(0.333333, 1, 0)
SellWood.TextScaled = true
SellWood.TextSize = 14
SellWood.TextWrapped = true
SellWood.MouseButton1Click:Connect(function()
	for _, Log in pairs(service.Workspace.LogModels:GetChildren()) do
		if Log.Name:sub(1, 6) == "Loose_" and Log:findFirstChild("Owner") then
			if Log.Owner.Value == service.Players.LocalPlayer then
				for i,v in pairs(Log:GetChildren()) do
					if v.Name=="WoodSection" then
						spawn(function()
							for i=1,10 do
								wait()
								v.CFrame=CFrame.new(Vector3.new(315, -0.296, 85.791))*CFrame.Angles(math.rad(90),0,0)
							end
						end)
					end
				end
				spawn(function()
					for i=1,20 do
						wait()
						Service.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(Log)
					end
				end)
			end
		end
	end
end)
NormalLand.Name = "Normal Land"
NormalLand.Parent = MainFrame
NormalLand.BackgroundColor3 = Color3.new(0, 0, 0)
NormalLand.BorderColor3 = Color3.new(0, 1, 0)
NormalLand.BorderSizePixel = 5
NormalLand.Position = UDim2.new(0.18928571, 0, 0.211009175, 0)
NormalLand.Size = UDim2.new(0, 96, 0, 38)
NormalLand.Font = Enum.Font.SciFi
NormalLand.Text = "Normal Land"
NormalLand.TextColor3 = Color3.new(0, 1, 0)
NormalLand.TextScaled = true
NormalLand.TextSize = 14
NormalLand.TextWrapped = true
NormalLand.MouseButton1Down:connect(function()
_G.TPStuff = true
while _G.TPStuff == true do
wait(5)
for i,v in pairs(game.Workspace.Properties:GetChildren()) do
    if v.Owner.Value == game.Players.LocalPlayer then
        game.ReplicatedStorage.PropertyPurchasing.ClientExpandedProperty:FireServer(v,CFrame.new(game.Players.LocalPlayer.Character["Left Leg"].Position))
    end
end
end
end)	
StopLand.Name = "StopLand"
StopLand.Parent = MainFrame
StopLand.BackgroundColor3 = Color3.new(0, 0, 0)
StopLand.BorderColor3 = Color3.new(0, 1, 0)
StopLand.BorderSizePixel = 5
StopLand.Position = UDim2.new(0.375, 0, 0.426605493, 0)
StopLand.Size = UDim2.new(0, 95, 0, 41)
StopLand.Font = Enum.Font.SciFi
StopLand.Text = "StopLand"
StopLand.TextColor3 = Color3.new(0, 1, 0)
StopLand.TextScaled = true
StopLand.TextSize = 14
StopLand.TextWrapped = true
StopLand.MouseButton1Down:connect(function()
_G.TPStuff = false
while _G.TPStuff == true do
wait(5)
for i,v in pairs(game.Workspace.Properties:GetChildren()) do
    if v.Owner.Value == game.Players.LocalPlayer then
        game.ReplicatedStorage.PropertyPurchasing.ClientExpandedProperty:FireServer(v,CFrame.new(game.Players.LocalPlayer.Character["Left Leg"].Position))
    end
end
end	
end)
WayPoint.Name = "WayPoint"
WayPoint.Parent = MainFrame
WayPoint.BackgroundColor3 = Color3.new(0, 0, 0)
WayPoint.BorderColor3 = Color3.new(0, 1, 0)
WayPoint.BorderSizePixel = 5
WayPoint.Position = UDim2.new(0.00714285765, 0, 0.206422016, 0)
WayPoint.Size = UDim2.new(0, 97, 0, 38)
WayPoint.Font = Enum.Font.SciFi
WayPoint.Text = "WayPoints"
WayPoint.TextColor3 = Color3.new(0, 1, 0)
WayPoint.TextScaled = true
WayPoint.TextSize = 14
WayPoint.TextStrokeColor3 = Color3.new(0, 1, 0)
WayPoint.TextWrapped = true
WayPoint.MouseButton1Down:connect(function()
-- Farewell Infortality.
-- Version: 2.82
-- Instances:
local ScreenGui = Instance.new("ScreenGui")
local WayPointFrame = Instance.new("Frame")
local ExitButton = Instance.new("TextButton")
local MiniMazeButton = Instance.new("TextButton")
local TopBar = Instance.new("Frame")
local EndTimes = Instance.new("TextButton")
local Cave = Instance.new("TextButton")
local Volcano = Instance.new("TextButton")
local Palm = Instance.new("TextButton")
local Swamp = Instance.new("TextButton")
local bobshack = Instance.new("TextButton")
local SkiiLodge = Instance.new("TextButton")
local WoodRus = Instance.new("TextButton")
local Cars = Instance.new("TextButton")
local LinksLogic = Instance.new("TextButton")
local FancyFurnishing = Instance.new("TextButton")
local StrangeMan = Instance.new("TextButton")
local Den = Instance.new("TextButton")
local Spawn = Instance.new("TextButton")
local FineArt = Instance.new("TextButton")
local YellowWood = Instance.new("TextButton")
local IceTree = Instance.new("TextButton")
local OpenButton = Instance.new("TextButton")
--Properties:
ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

WayPointFrame.Name = "WayPointFrame"
WayPointFrame.Parent = ScreenGui
WayPointFrame.BackgroundColor3 = Color3.new(0, 0, 0)
WayPointFrame.BorderColor3 = Color3.new(0, 1, 0)
WayPointFrame.BorderSizePixel = 5
WayPointFrame.Position = UDim2.new(0.774614453, 0, 0.0355731249, 0)
WayPointFrame.Size = UDim2.new(0, 125, 0, 469)
WayPointFrame.Active = true 
WayPointFrame.Draggable = true 

ExitButton.Name = "ExitButton"
ExitButton.Parent = WayPointFrame
ExitButton.BackgroundColor3 = Color3.new(0, 0, 0)
ExitButton.BorderColor3 = Color3.new(0, 1, 0)
ExitButton.BorderSizePixel = 2
ExitButton.Position = UDim2.new(0.744000018, 0, 0, 0)
ExitButton.Size = UDim2.new(0, 32, 0, 12)
ExitButton.Font = Enum.Font.SciFi
ExitButton.Text = "x"
ExitButton.TextColor3 = Color3.new(0, 1, 0)
ExitButton.TextScaled = true
ExitButton.TextSize = 14
ExitButton.TextWrapped = true
ExitButton.MouseButton1Click:connect(function()
	WayPointFrame.Visible = false
	end)
MiniMazeButton.Name = "MiniMazeButton"
MiniMazeButton.Parent = WayPointFrame
MiniMazeButton.BackgroundColor3 = Color3.new(0, 0, 0)
MiniMazeButton.BorderColor3 = Color3.new(0, 1, 0)
MiniMazeButton.BorderSizePixel = 2
MiniMazeButton.Position = UDim2.new(0.495999992, 0, 0, 0)
MiniMazeButton.Size = UDim2.new(0, 31, 0, 12)
MiniMazeButton.Font = Enum.Font.SciFi
MiniMazeButton.Text = "-"
MiniMazeButton.TextColor3 = Color3.new(0, 1, 0)
MiniMazeButton.TextScaled = true
MiniMazeButton.TextSize = 14
MiniMazeButton.TextWrapped = true
MiniMazeButton.MouseButton1Click:connect(function()
	WayPointFrame.Visible = false
	OpenButton.Visible = true
end)
TopBar.Name = "TopBar"
TopBar.Parent = WayPointFrame
TopBar.BackgroundColor3 = Color3.new(0, 0, 0)
TopBar.BorderColor3 = Color3.new(0, 1, 0)
TopBar.BorderSizePixel = 2
TopBar.Size = UDim2.new(0, 62, 0, 12)

EndTimes.Name = "EndTimes"
EndTimes.Parent = WayPointFrame
EndTimes.BackgroundColor3 = Color3.new(0, 0, 0)
EndTimes.BorderColor3 = Color3.new(0, 1, 0)
EndTimes.BorderSizePixel = 2
EndTimes.Position = UDim2.new(0.0560000017, 0, 0.0538404807, 0)
EndTimes.Size = UDim2.new(0, 111, 0, 24)
EndTimes.Font = Enum.Font.SciFi
EndTimes.Text = "EndTimes"
EndTimes.TextColor3 = Color3.new(0, 1, 0)
EndTimes.TextScaled = true
EndTimes.TextSize = 14
EndTimes.TextWrapped = true
EndTimes.MouseButton1Click:connect(function()
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(113, -214, -951))end
)
Cave.Name = "Cave"
Cave.Parent = WayPointFrame
Cave.BackgroundColor3 = Color3.new(0, 0, 0)
Cave.BorderColor3 = Color3.new(0, 1, 0)
Cave.BorderSizePixel = 2
Cave.Position = UDim2.new(0.0560000017, 0, 0.107635289, 0)
Cave.Size = UDim2.new(0, 111, 0, 24)
Cave.Font = Enum.Font.SciFi
Cave.Text = "Cave"
Cave.TextColor3 = Color3.new(0, 1, 0)
Cave.TextScaled = true
Cave.TextSize = 14
Cave.TextWrapped = true
Cave.MouseButton1Down:connect(function()
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(3581,-179,430))end
)
Volcano.Name = "Volcano"
Volcano.Parent = WayPointFrame
Volcano.BackgroundColor3 = Color3.new(0, 0, 0)
Volcano.BorderColor3 = Color3.new(0, 1, 0)
Volcano.BorderSizePixel = 2
Volcano.Position = UDim2.new(0.0560000017, 0, 0.162899897, 0)
Volcano.Size = UDim2.new(0, 111, 0, 24)
Volcano.Font = Enum.Font.SciFi
Volcano.Text = "Volcano"
Volcano.TextColor3 = Color3.new(0, 1, 0)
Volcano.TextScaled = true
Volcano.TextSize = 14
Volcano.TextWrapped = true
Volcano.MouseButton1Down:connect(function()
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(-1585,622,1140))end
)
Palm.Name = "Palm"
Palm.Parent = WayPointFrame
Palm.BackgroundColor3 = Color3.new(0, 0, 0)
Palm.BorderColor3 = Color3.new(0, 1, 0)
Palm.BorderSizePixel = 2
Palm.Position = UDim2.new(0.0560000017, 0, 0.216694683, 0)
Palm.Size = UDim2.new(0, 111, 0, 24)
Palm.Font = Enum.Font.SciFi
Palm.Text = "Palm"
Palm.TextColor3 = Color3.new(0, 1, 0)
Palm.TextScaled = true
Palm.TextSize = 14
Palm.TextWrapped = true
Palm.MouseButton1Click:connect(function()
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(2549, -5, -42))end
)
Swamp.Name = "Swamp"
Swamp.Parent = WayPointFrame
Swamp.BackgroundColor3 = Color3.new(0, 0, 0)
Swamp.BorderColor3 = Color3.new(0, 1, 0)
Swamp.BorderSizePixel = 2
Swamp.Position = UDim2.new(0.0560000017, 0, 0.270640463, 0)
Swamp.Size = UDim2.new(0, 111, 0, 24)
Swamp.Font = Enum.Font.SciFi
Swamp.Text = "Swamp"
Swamp.TextColor3 = Color3.new(0, 1, 0)
Swamp.TextScaled = true
Swamp.TextSize = 14
Swamp.TextWrapped = true
Swamp.MouseButton1Click:connect(function()
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(-1209,132,-801))end
)
bobshack.Name = "bobshack"
bobshack.Parent = WayPointFrame
bobshack.BackgroundColor3 = Color3.new(0, 0, 0)
bobshack.BorderColor3 = Color3.new(0, 1, 0)
bobshack.BorderSizePixel = 2
bobshack.Position = UDim2.new(0.0560000017, 0, 0.326247483, 0)
bobshack.Size = UDim2.new(0, 111, 0, 24)
bobshack.Font = Enum.Font.SciFi
bobshack.Text = "Bobshack"
bobshack.TextColor3 = Color3.new(0, 1, 0)
bobshack.TextScaled = true
bobshack.TextSize = 14
bobshack.TextWrapped = true
bobshack.MouseButton1Click:connect(function()
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(260, 8, -2542))end
)
SkiiLodge.Name = "SkiiLodge"
SkiiLodge.Parent = WayPointFrame
SkiiLodge.BackgroundColor3 = Color3.new(0, 0, 0)
SkiiLodge.BorderColor3 = Color3.new(0, 1, 0)
SkiiLodge.BorderSizePixel = 2
SkiiLodge.Position = UDim2.new(0.0560000017, 0, 0.379968107, 0)
SkiiLodge.Size = UDim2.new(0, 111, 0, 24)
SkiiLodge.Font = Enum.Font.SciFi
SkiiLodge.Text = "SkiiLodge"
SkiiLodge.TextColor3 = Color3.new(0, 1, 0)
SkiiLodge.TextScaled = true
SkiiLodge.TextSize = 14
SkiiLodge.TextWrapped = true
SkiiLodge.MouseButton1Click:connect(function()
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(1244, 62, 2306))end
)
WoodRus.Name = "WoodRus"
WoodRus.Parent = WayPointFrame
WoodRus.BackgroundColor3 = Color3.new(0, 0, 0)
WoodRus.BorderColor3 = Color3.new(0, 1, 0)
WoodRus.BorderSizePixel = 2
WoodRus.Position = UDim2.new(0.0560000017, 0, 0.435800284, 0)
WoodRus.Size = UDim2.new(0, 111, 0, 24)
WoodRus.Font = Enum.Font.SciFi
WoodRus.Text = "WoodRus"
WoodRus.TextColor3 = Color3.new(0.333333, 1, 0)
WoodRus.TextScaled = true
WoodRus.TextSize = 14
WoodRus.TextWrapped = true
WoodRus.MouseButton1Click:connect(function()
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(265,3,57))end
)
Cars.Name = "Cars"
Cars.Parent = WayPointFrame
Cars.BackgroundColor3 = Color3.new(0, 0, 0)
Cars.BorderColor3 = Color3.new(0, 1, 0)
Cars.BorderSizePixel = 2
Cars.Position = UDim2.new(0.0560000017, 0, 0.491709232, 0)
Cars.Size = UDim2.new(0, 111, 0, 24)
Cars.Font = Enum.Font.SciFi
Cars.Text = "Cars"
Cars.TextColor3 = Color3.new(0, 1, 0)
Cars.TextScaled = true
Cars.TextSize = 14
Cars.TextWrapped = true
Cars.MouseButton1Click:connect(function()
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(509, 3, -1463))end
)
LinksLogic.Name = "LinksLogic"
LinksLogic.Parent = WayPointFrame
LinksLogic.BackgroundColor3 = Color3.new(0, 0, 0)
LinksLogic.BorderColor3 = Color3.new(0, 1, 0)
LinksLogic.BorderSizePixel = 2
LinksLogic.Position = UDim2.new(0.0560000017, 0, 0.545429885, 0)
LinksLogic.Size = UDim2.new(0, 111, 0, 24)
LinksLogic.Font = Enum.Font.SciFi
LinksLogic.Text = "LinksLogic"
LinksLogic.TextColor3 = Color3.new(0, 1, 0)
LinksLogic.TextScaled = true
LinksLogic.TextSize = 14
LinksLogic.TextWrapped = true
LinksLogic.MouseButton1Click:connect(function()
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(4607,7.5,-798))end
)
FancyFurnishing.Name = "FancyFurnishing"
FancyFurnishing.Parent = WayPointFrame
FancyFurnishing.BackgroundColor3 = Color3.new(0, 0, 0)
FancyFurnishing.BorderColor3 = Color3.new(0, 1, 0)
FancyFurnishing.BorderSizePixel = 2
FancyFurnishing.Position = UDim2.new(0.0560000017, 0, 0.59899956, 0)
FancyFurnishing.Size = UDim2.new(0, 111, 0, 24)
FancyFurnishing.Font = Enum.Font.SciFi
FancyFurnishing.Text = "FancyFurnishing "
FancyFurnishing.TextColor3 = Color3.new(0, 1, 0)
FancyFurnishing.TextScaled = true
FancyFurnishing.TextSize = 14
FancyFurnishing.TextWrapped = true
FancyFurnishing.MouseButton1Click:connect(function()
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(491, 3, -1720))end
)
StrangeMan.Name = "StrangeMan"
StrangeMan.Parent = WayPointFrame
StrangeMan.BackgroundColor3 = Color3.new(0, 0, 0)
StrangeMan.BorderColor3 = Color3.new(0, 1, 0)
StrangeMan.BorderSizePixel = 2
StrangeMan.Position = UDim2.new(0.0560000017, 0, 0.654606581, 0)
StrangeMan.Size = UDim2.new(0, 111, 0, 24)
StrangeMan.Font = Enum.Font.SciFi
StrangeMan.Text = "StrangeMan"
StrangeMan.TextColor3 = Color3.new(0, 1, 0)
StrangeMan.TextScaled = true
StrangeMan.TextSize = 14
StrangeMan.TextWrapped = true
StrangeMan.MouseButton1Click:connect(function()
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(1061, 16, 1131))end
)
Den.Name = "Den"
Den.Parent = WayPointFrame
Den.BackgroundColor3 = Color3.new(0, 0, 0)
Den.BorderColor3 = Color3.new(0, 1, 0)
Den.BorderSizePixel = 2
Den.Position = UDim2.new(0.0560000017, 0, 0.708422065, 0)
Den.Size = UDim2.new(0, 111, 0, 24)
Den.Font = Enum.Font.SciFi
Den.Text = "Den"
Den.TextColor3 = Color3.new(0, 1, 0)
Den.TextScaled = true
Den.TextSize = 14
Den.TextWrapped = true
Den.MouseButton1Down:connect(function() 
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(331, 45, 1941))
end)
Spawn.Name = "Spawn"
Spawn.Parent = WayPointFrame
Spawn.BackgroundColor3 = Color3.new(0, 0, 0)
Spawn.BorderColor3 = Color3.new(0, 1, 0)
Spawn.BorderSizePixel = 2
Spawn.Position = UDim2.new(0.0560000017, 0, 0.762471676, 0)
Spawn.Size = UDim2.new(0, 111, 0, 24)
Spawn.Font = Enum.Font.SciFi
Spawn.Text = "Spawn"
Spawn.TextColor3 = Color3.new(0, 1, 0)
Spawn.TextScaled = true
Spawn.TextSize = 14
Spawn.TextWrapped = true
Spawn.MouseButton1Down:connect(function()
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(155,3,74))end
)
FineArt.Name = "FineArt"
FineArt.Parent = WayPointFrame
FineArt.BackgroundColor3 = Color3.new(0, 0, 0)
FineArt.BorderColor3 = Color3.new(0, 1, 0)
FineArt.BorderSizePixel = 2
FineArt.Position = UDim2.new(0.0560000017, 0, 0.815836132, 0)
FineArt.Size = UDim2.new(0, 111, 0, 24)
FineArt.Font = Enum.Font.SciFi
FineArt.Text = "FineArt"
FineArt.TextColor3 = Color3.new(0, 1, 0)
FineArt.TextScaled = true
FineArt.TextSize = 14
FineArt.TextWrapped = true
FineArt.MouseButton1Down:connect(function()
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(5207, -166, 719))end
)
YellowWood.Name = "YellowWood"
YellowWood.Parent = WayPointFrame
YellowWood.BackgroundColor3 = Color3.new(0, 0, 0)
YellowWood.BorderColor3 = Color3.new(0, 1, 0)
YellowWood.BorderSizePixel = 2
YellowWood.Position = UDim2.new(0.0560000017, 0, 0.870134771, 0)
YellowWood.Size = UDim2.new(0, 111, 0, 24)
YellowWood.Font = Enum.Font.SciFi
YellowWood.Text = "YellowWood"
YellowWood.TextColor3 = Color3.new(0, 1, 0)
YellowWood.TextScaled = true
YellowWood.TextSize = 14
YellowWood.TextWrapped = true
YellowWood.MouseButton1Down:connect(function()
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(-1049,-5.9 ,-934.7 ))end
)
IceTree.Name = "IceTree"
IceTree.Parent = WayPointFrame
IceTree.BackgroundColor3 = Color3.new(0, 0, 0)
IceTree.BorderColor3 = Color3.new(0, 1, 0)
IceTree.BorderSizePixel = 2
IceTree.Position = UDim2.new(0.0560000017, 0, 0.92443341, 0)
IceTree.Size = UDim2.new(0, 111, 0, 24)
IceTree.Font = Enum.Font.SciFi
IceTree.Text = "IceTree"
IceTree.TextColor3 = Color3.new(0, 1, 0)
IceTree.TextScaled = true
IceTree.TextSize = 14
IceTree.TextWrapped = true
IceTree.MouseButton1Down:connect(function()
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(1505.7,412.4 ,3253 ))end
)
OpenButton.Name = "OpenButton"
OpenButton.Parent = ScreenGui
OpenButton.BackgroundColor3 = Color3.new(0, 0, 0)
OpenButton.BorderColor3 = Color3.new(0, 1, 0)
OpenButton.BorderSizePixel = 2
OpenButton.Position = UDim2.new(0, 0, 0.398740262, 0)
OpenButton.Size = UDim2.new(0, 82, 0, 19)
OpenButton.Visible = false
OpenButton.Font = Enum.Font.SciFi
OpenButton.Text = "WayPoints"
OpenButton.TextColor3 = Color3.new(0, 1, 0)
OpenButton.TextScaled = true
OpenButton.TextSize = 14
OpenButton.TextWrapped = true
OpenButton .MouseButton1Click:connect(function()
	WayPointFrame.Visible = true 
	OpenButton.Visible = false
end)

		
end)
WayPoint_2.Name = "WayPoint"
WayPoint_2.Parent = MainFrame
WayPoint_2.BackgroundColor3 = Color3.new(0, 0, 0)
WayPoint_2.BorderColor3 = Color3.new(0, 1, 0)
WayPoint_2.BorderSizePixel = 5
WayPoint_2.Position = UDim2.new(0.18928571, 0, 0.646789014, 0)
WayPoint_2.Size = UDim2.new(0, 96, 0, 34)
WayPoint_2.Font = Enum.Font.SciFi
WayPoint_2.Text = "WayPoints"
WayPoint_2.TextColor3 = Color3.new(0, 1, 0)
WayPoint_2.TextScaled = true
WayPoint_2.TextSize = 14
WayPoint_2.TextWrapped = true
WayPoint_2.MouseButton1Down:connect(function()

end)
TpGifts.Name = "Tp Gifts"
TpGifts.Parent = MainFrame
TpGifts.BackgroundColor3 = Color3.new(0, 0, 0)
TpGifts.BorderColor3 = Color3.new(0, 1, 0)
TpGifts.BorderSizePixel = 5
TpGifts.Position = UDim2.new(0.5625, 0, 0.426605493, 0)
TpGifts.Size = UDim2.new(0, 92, 0, 41)
TpGifts.Font = Enum.Font.SciFi
TpGifts.Text = "TpGifts"
TpGifts.TextColor3 = Color3.new(0, 1, 0)
TpGifts.TextScaled = true
TpGifts.TextSize = 14
TpGifts.TextWrapped = true
TpGifts.MouseButton1Down:connect(function()
for i,v in next,workspace.PlayerModels:GetChildren() do
    if v:FindFirstChild("Main") and v.Owner.Value == game.Players.LocalPlayer then
    for q,p in pairs(v:GetChildren()) do       
        if p.Name:lower():match("box") or p.Name == "DraggableItem" then
            wait()
                v.PrimaryPart = v.Main
                game.ReplicatedStorage.Interaction.Verify:FireServer('Item owned by player',v)
                   v:SetPrimaryPartCFrame(game.Players.LocalPlayer.Character.Head.CFrame)
                 game.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(v)
        end
    end
    end
end
end)
BringUp.Name = "BringUp"
BringUp.Parent = MainFrame
BringUp.BackgroundColor3 = Color3.new(0, 0, 0)
BringUp.BorderColor3 = Color3.new(0, 1, 0)
BringUp.BorderSizePixel = 5
BringUp.Position = UDim2.new(0.375, 0, 0.844036698, 0)
BringUp.Size = UDim2.new(0, 95, 0, 29)
BringUp.Font = Enum.Font.SciFi
BringUp.Text = "BringUp"
BringUp.TextColor3 = Color3.new(0, 1, 0)
BringUp.TextScaled = true
BringUp.TextSize = 14
BringUp.TextWrapped = true
BringUp.MouseButton1Down:connect(function()
loadstring(game:GetObjects("rbxassetid://01925396229")[1].Source)()
	
end)
HailStone.Name = "HailStone"
HailStone.Parent = MainFrame
HailStone.BackgroundColor3 = Color3.new(0, 0, 0)
HailStone.BorderColor3 = Color3.new(0, 1, 0)
HailStone.BorderSizePixel = 5
HailStone.Position = UDim2.new(0.18928571, 0, 0.426605493, 0)
HailStone.Size = UDim2.new(0, 96, 0, 41)
HailStone.Font = Enum.Font.SciFi
HailStone.Text = "HailStone"
HailStone.TextColor3 = Color3.new(0, 1, 0)
HailStone.TextScaled = true
HailStone.TextSize = 14
HailStone.TextWrapped = true
HailStone.MouseButton1Down:connect(function()
-- Objects

local Hailstone = Instance.new("ScreenGui")
local OpenBtn = Instance.new("TextButton")
local Drag = Instance.new("Frame")
local AAPressQ = Instance.new("TextLabel")
local AnimWelcomeScreen = Instance.new("Frame")
local ImageLabel = Instance.new("ImageLabel")
local Main = Instance.new("Frame")
local HomeLocal = Instance.new("TextButton")
local HomeTopBar = Instance.new("TextButton")
local HomePlayers = Instance.new("TextButton")
local HomeTeleports = Instance.new("TextButton")
local HomeWood = Instance.new("TextButton")
local HomeTools = Instance.new("TextButton")
local HomeChangelog = Instance.new("TextButton")
local HomeLogo = Instance.new("ImageLabel")
local HiName = Instance.new("TextLabel")
local HomeSepBar = Instance.new("TextButton")
local X = Instance.new("TextButton")
local WoodScreen = Instance.new("Frame")
local TeleportCutWood = Instance.new("TextButton")
local SellCutWood = Instance.new("TextButton")
local TeleportEndTimesWood = Instance.new("TextButton")
local TeleportCaveCrawlerWood = Instance.new("TextButton")
local TeleportGifts = Instance.new("TextButton")
local ToolsScreen = Instance.new("Frame")
local Dupe = Instance.new("TextButton")
local Move = Instance.new("TextButton")
local GoldAxe = Instance.new("TextButton")
local LeakedItems = Instance.new("TextButton")
local TeleportTool = Instance.new("TextButton")
local GreyWood = Instance.new("TextButton")
local DupeLabel = Instance.new("TextLabel")
local TeleportsScreen = Instance.new("Frame")
local Spawn = Instance.new("TextButton")
local Den = Instance.new("TextButton")
local StrangeMan = Instance.new("TextButton")
local Swamp = Instance.new("TextButton")
local Fancy = Instance.new("TextButton")
local BoxedCars = Instance.new("TextButton")
local Dropoff = Instance.new("TextButton")
local GreenBox = Instance.new("TextButton")
local Cave = Instance.new("TextButton")
local Palm = Instance.new("TextButton")
local WoodRUs = Instance.new("TextButton")
local LinksLogic = Instance.new("TextButton")
local YourPlot = Instance.new("TextButton")
local BobsShack = Instance.new("TextButton")
local EndTimes = Instance.new("TextButton")
local Volcano = Instance.new("TextButton")
local Lodge = Instance.new("TextButton")
local Shrine = Instance.new("TextButton")
local PlayersScreen = Instance.new("Frame")
local P1 = Instance.new("TextButton")
local P2 = Instance.new("TextButton")
local P4 = Instance.new("TextButton")
local P3 = Instance.new("TextButton")
local P6 = Instance.new("TextButton")
local P5 = Instance.new("TextButton")
local TpToPlayer = Instance.new("TextButton")
local TpToPlayerBase = Instance.new("TextButton")
local PSelected = Instance.new("TextLabel")
local LocalScreen = Instance.new("Frame")
local God = Instance.new("TextButton")
local Noclip = Instance.new("TextButton")
local Walkspeed = Instance.new("TextButton")
local Jumppower = Instance.new("TextButton")
local NoclipLabel = Instance.new("TextLabel")
local WalkspeedValue = Instance.new("TextBox")
local JumppowerValue = Instance.new("TextBox")
local EtoFly = Instance.new("TextLabel")
local HomeScreen = Instance.new("Frame")
local WelcomeName = Instance.new("TextLabel")
local WelcomeMOTD = Instance.new("TextLabel")
local WelcomeAuthor = Instance.new("TextLabel")
local ChangelogScreen = Instance.new("Frame")
local Logs = Instance.new("TextLabel")
local Logs2 = Instance.new("TextLabel")
local Logs3 = Instance.new("TextLabel")
local Log1and2Div = Instance.new("TextButton")
local Log2and3Div = Instance.new("TextButton")

-- Properties

Hailstone.Name = "Hailstone"
Hailstone.Parent = game.CoreGui
Hailstone.ResetOnSpawn = false

OpenBtn.Name = "OpenBtn"
OpenBtn.Parent = Hailstone
OpenBtn.BackgroundColor3 = Color3.new(0.105882, 0.164706, 0.207843)
OpenBtn.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
OpenBtn.BorderSizePixel = 3
OpenBtn.Position = UDim2.new(0, 0, 0.826086938, 0)
OpenBtn.Size = UDim2.new(0, 79, 0, 23)
OpenBtn.Visible = false
OpenBtn.Font = Enum.Font.SourceSans
OpenBtn.Text = "Open"
OpenBtn.TextColor3 = Color3.new(0.117647, 0.501961, 0.639216)
OpenBtn.TextSize = 14
OpenBtn.TextWrapped = true

Drag.Name = "Drag"
Drag.Parent = Hailstone
Drag.Active = true
Drag.BackgroundColor3 = Color3.new(1, 1, 1)
Drag.BackgroundTransparency = 1
Drag.BorderSizePixel = 0
Drag.Draggable = true
Drag.Position = UDim2.new(0.373752683, 0, 0.267786592, 0)
Drag.Selectable = true
Drag.Size = UDim2.new(0, 451, 0, 234)

AAPressQ.Name = "AAPressQ"
AAPressQ.Parent = Hailstone
AAPressQ.BackgroundColor3 = Color3.new(1, 1, 1)
AAPressQ.BackgroundTransparency = 1
AAPressQ.BorderSizePixel = 0
AAPressQ.Position = UDim2.new(0.283759117, 0, 0.252964437, 0)
AAPressQ.Size = UDim2.new(0, 573, 0, 257)
AAPressQ.Font = Enum.Font.SourceSans
AAPressQ.Text = "Press \"Q\""
AAPressQ.TextSize = 100

AnimWelcomeScreen.Name = "AnimWelcomeScreen"
AnimWelcomeScreen.Parent = Drag
AnimWelcomeScreen.BackgroundColor3 = Color3.new(0.105882, 0.164706, 0.207843)
AnimWelcomeScreen.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
AnimWelcomeScreen.BorderSizePixel = 3
AnimWelcomeScreen.Position = UDim2.new(0.328511298, 0, -0.20692715, 0)
AnimWelcomeScreen.Size = UDim2.new(0, 209, 0, 199)
AnimWelcomeScreen.Visible = false

ImageLabel.Parent = AnimWelcomeScreen
ImageLabel.BackgroundColor3 = Color3.new(1, 1, 1)
ImageLabel.BackgroundTransparency = 1
ImageLabel.BorderSizePixel = 0
ImageLabel.Size = UDim2.new(0, 209, 0, 199)
ImageLabel.Image = "rbxassetid://1393851029"

Main.Name = "Main"
Main.Parent = Drag
Main.BackgroundColor3 = Color3.new(0.105882, 0.164706, 0.207843)
Main.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Main.BorderSizePixel = 3
Main.Position = UDim2.new(-0.00221729279, 0, 0.0128205121, 0)
Main.Size = UDim2.new(0, 450, 0, 232)
Main.Visible = false

HomeLocal.Name = "HomeLocal"
HomeLocal.Parent = Main
HomeLocal.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
HomeLocal.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
HomeLocal.BorderSizePixel = 2
HomeLocal.Position = UDim2.new(0.0244444441, 0, 0.206896558, 0)
HomeLocal.Size = UDim2.new(0, 84, 0, 21)
HomeLocal.Font = Enum.Font.SourceSans
HomeLocal.Text = "Local"
HomeLocal.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
HomeLocal.TextSize = 24
HomeLocal.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

HomeTopBar.Name = "HomeTopBar"
HomeTopBar.Parent = Main
HomeTopBar.BackgroundColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
HomeTopBar.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
HomeTopBar.Position = UDim2.new(0, 0, 0.159482777, 0)
HomeTopBar.Size = UDim2.new(0, 450, 0, 1)
HomeTopBar.Font = Enum.Font.SourceSans
HomeTopBar.Text = ""
HomeTopBar.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
HomeTopBar.TextSize = 24
HomeTopBar.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

HomePlayers.Name = "HomePlayers"
HomePlayers.Parent = Main
HomePlayers.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
HomePlayers.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
HomePlayers.BorderSizePixel = 2
HomePlayers.Position = UDim2.new(0.0244444441, 0, 0.331896544, 0)
HomePlayers.Size = UDim2.new(0, 84, 0, 21)
HomePlayers.Font = Enum.Font.SourceSans
HomePlayers.Text = "Players"
HomePlayers.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
HomePlayers.TextSize = 24
HomePlayers.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

HomeTeleports.Name = "HomeTeleports"
HomeTeleports.Parent = Main
HomeTeleports.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
HomeTeleports.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
HomeTeleports.BorderSizePixel = 2
HomeTeleports.Position = UDim2.new(0.0244444441, 0, 0.459051698, 0)
HomeTeleports.Size = UDim2.new(0, 84, 0, 21)
HomeTeleports.Font = Enum.Font.SourceSans
HomeTeleports.Text = "Teleports"
HomeTeleports.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
HomeTeleports.TextSize = 24
HomeTeleports.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

HomeWood.Name = "HomeWood"
HomeWood.Parent = Main
HomeWood.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
HomeWood.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
HomeWood.BorderSizePixel = 2
HomeWood.Position = UDim2.new(0.0244444441, 0, 0.594827592, 0)
HomeWood.Size = UDim2.new(0, 84, 0, 21)
HomeWood.Font = Enum.Font.SourceSans
HomeWood.Text = "Wood"
HomeWood.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
HomeWood.TextSize = 24
HomeWood.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

HomeTools.Name = "HomeTools"
HomeTools.Parent = Main
HomeTools.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
HomeTools.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
HomeTools.BorderSizePixel = 2
HomeTools.Position = UDim2.new(0.0244444441, 0, 0.732758641, 0)
HomeTools.Size = UDim2.new(0, 84, 0, 21)
HomeTools.Font = Enum.Font.SourceSans
HomeTools.Text = "Tools"
HomeTools.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
HomeTools.TextSize = 24
HomeTools.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

HomeChangelog.Name = "HomeChangelog"
HomeChangelog.Parent = Main
HomeChangelog.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
HomeChangelog.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
HomeChangelog.BorderSizePixel = 2
HomeChangelog.Position = UDim2.new(0.0244444441, 0, 0.875, 0)
HomeChangelog.Size = UDim2.new(0, 84, 0, 21)
HomeChangelog.Font = Enum.Font.SourceSans
HomeChangelog.Text = "Changelog"
HomeChangelog.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
HomeChangelog.TextSize = 22
HomeChangelog.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

HomeLogo.Name = "HomeLogo"
HomeLogo.Parent = Main
HomeLogo.BackgroundColor3 = Color3.new(1, 1, 1)
HomeLogo.BackgroundTransparency = 1
HomeLogo.BorderSizePixel = 0
HomeLogo.Position = UDim2.new(0.456999987, 0, -0.11896389, 0)
HomeLogo.Size = UDim2.new(0, 156, 0, 99)
HomeLogo.Image = "rbxassetid://1393851029"

HiName.Name = "HiName"
HiName.Parent = Main
HiName.BackgroundColor3 = Color3.new(1, 1, 1)
HiName.BackgroundTransparency = 1
HiName.BorderSizePixel = 0
HiName.Position = UDim2.new(0.0244444441, 0, 0.0258620698, 0)
HiName.Size = UDim2.new(0, 189, 0, 25)
HiName.Font = Enum.Font.SourceSans
HiName.Text = "Hi"
HiName.TextColor3 = Color3.new(0.117647, 0.501961, 0.639216)
HiName.TextScaled = true
HiName.TextSize = 14
HiName.TextStrokeColor3 = Color3.new(0.000153787, 0.000246059, 0.000322953)
HiName.TextStrokeTransparency = 0.64899998903275
HiName.TextWrapped = true
HiName.TextXAlignment = Enum.TextXAlignment.Left

HomeSepBar.Name = "HomeSepBar"
HomeSepBar.Parent = Main
HomeSepBar.BackgroundColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
HomeSepBar.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
HomeSepBar.Position = UDim2.new(0.24888888, 0, 0.206896558, 0)
HomeSepBar.Size = UDim2.new(0, 1, 0, 176)
HomeSepBar.Font = Enum.Font.SourceSans
HomeSepBar.Text = ""
HomeSepBar.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
HomeSepBar.TextSize = 24
HomeSepBar.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

X.Name = "X"
X.Parent = Main
X.BackgroundColor3 = Color3.new(1, 1, 1)
X.BackgroundTransparency = 1
X.BorderSizePixel = 0
X.Position = UDim2.new(0.937777758, 0, 0, 0)
X.Size = UDim2.new(0, 28, 0, 25)
X.Font = Enum.Font.SourceSans
X.Text = "X"
X.TextColor3 = Color3.new(0.117647, 0.501961, 0.639216)
X.TextScaled = true
X.TextSize = 14
X.TextWrapped = true

WoodScreen.Name = "WoodScreen"
WoodScreen.Parent = Drag
WoodScreen.BackgroundColor3 = Color3.new(0.105882, 0.164706, 0.207843)
WoodScreen.BackgroundTransparency = 1
WoodScreen.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
WoodScreen.BorderSizePixel = 0
WoodScreen.Draggable = true
WoodScreen.Position = UDim2.new(0.0164813697, 0, -0.000777035952, 0)
WoodScreen.Size = UDim2.new(0, 444, 0, 230)
WoodScreen.Visible = false

TeleportCutWood.Name = "Teleport Cut Wood"
TeleportCutWood.Parent = WoodScreen
TeleportCutWood.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
TeleportCutWood.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
TeleportCutWood.BorderSizePixel = 2
TeleportCutWood.Position = UDim2.new(0.457207203, 0, 0.226086959, 0)
TeleportCutWood.Size = UDim2.new(0, 147, 0, 21)
TeleportCutWood.Font = Enum.Font.SourceSans
TeleportCutWood.Text = "Teleport Cut Wood"
TeleportCutWood.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
TeleportCutWood.TextScaled = true
TeleportCutWood.TextSize = 24
TeleportCutWood.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
TeleportCutWood.TextWrapped = true

SellCutWood.Name = "Sell Cut Wood"
SellCutWood.Parent = WoodScreen
SellCutWood.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
SellCutWood.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
SellCutWood.BorderSizePixel = 2
SellCutWood.Position = UDim2.new(0.457207203, 0, 0.391304344, 0)
SellCutWood.Size = UDim2.new(0, 147, 0, 21)
SellCutWood.Font = Enum.Font.SourceSans
SellCutWood.Text = "Sell Cut Wood"
SellCutWood.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
SellCutWood.TextSize = 24
SellCutWood.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

TeleportEndTimesWood.Name = "Teleport End Times Wood"
TeleportEndTimesWood.Parent = WoodScreen
TeleportEndTimesWood.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
TeleportEndTimesWood.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
TeleportEndTimesWood.BorderSizePixel = 2
TeleportEndTimesWood.Position = UDim2.new(0.457207203, 0, 0.556521714, 0)
TeleportEndTimesWood.Size = UDim2.new(0, 147, 0, 21)
TeleportEndTimesWood.Font = Enum.Font.SourceSans
TeleportEndTimesWood.Text = "Teleport End Times"
TeleportEndTimesWood.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
TeleportEndTimesWood.TextScaled = true
TeleportEndTimesWood.TextSize = 24
TeleportEndTimesWood.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
TeleportEndTimesWood.TextWrapped = true

TeleportCaveCrawlerWood.Name = "Teleport Cave Crawler Wood"
TeleportCaveCrawlerWood.Parent = WoodScreen
TeleportCaveCrawlerWood.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
TeleportCaveCrawlerWood.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
TeleportCaveCrawlerWood.BorderSizePixel = 2
TeleportCaveCrawlerWood.Position = UDim2.new(0.457207203, 0, 0.70869565, 0)
TeleportCaveCrawlerWood.Size = UDim2.new(0, 147, 0, 21)
TeleportCaveCrawlerWood.Font = Enum.Font.SourceSans
TeleportCaveCrawlerWood.Text = "Teleport Cave Crawler"
TeleportCaveCrawlerWood.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
TeleportCaveCrawlerWood.TextScaled = true
TeleportCaveCrawlerWood.TextSize = 24
TeleportCaveCrawlerWood.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
TeleportCaveCrawlerWood.TextWrapped = true

TeleportGifts.Name = "Teleport Gifts"
TeleportGifts.Parent = WoodScreen
TeleportGifts.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
TeleportGifts.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
TeleportGifts.BorderSizePixel = 2
TeleportGifts.Position = UDim2.new(0.456081063, 0, 0.869565248, 0)
TeleportGifts.Size = UDim2.new(0, 147, 0, 21)
TeleportGifts.Font = Enum.Font.SourceSans
TeleportGifts.Text = "Teleport Gifts"
TeleportGifts.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
TeleportGifts.TextScaled = true
TeleportGifts.TextSize = 24
TeleportGifts.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
TeleportGifts.TextWrapped = true

ToolsScreen.Name = "ToolsScreen"
ToolsScreen.Parent = Drag
ToolsScreen.BackgroundColor3 = Color3.new(0.105882, 0.164706, 0.207843)
ToolsScreen.BackgroundTransparency = 1
ToolsScreen.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
ToolsScreen.BorderSizePixel = 0
ToolsScreen.Draggable = true
ToolsScreen.Position = UDim2.new(0.0164813697, 0, -0.000777035952, 0)
ToolsScreen.Size = UDim2.new(0, 444, 0, 230)
ToolsScreen.Visible = false

Dupe.Name = "Dupe"
Dupe.Parent = ToolsScreen
Dupe.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
Dupe.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Dupe.BorderSizePixel = 2
Dupe.Position = UDim2.new(0.457207203, 0, 0.199999988, 0)
Dupe.Size = UDim2.new(0, 147, 0, 20)
Dupe.Font = Enum.Font.SourceSans
Dupe.Text = "Duplication"
Dupe.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Dupe.TextScaled = true
Dupe.TextSize = 24
Dupe.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Dupe.TextWrapped = true

Move.Name = "Move"
Move.Parent = ToolsScreen
Move.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
Move.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Move.BorderSizePixel = 2
Move.Position = UDim2.new(0.457207203, 0, 0.347826093, 0)
Move.Size = UDim2.new(0, 147, 0, 20)
Move.Font = Enum.Font.SourceSans
Move.Text = "Hard Dragger"
Move.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Move.TextScaled = true
Move.TextSize = 24
Move.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Move.TextWrapped = true

GoldAxe.Name = "Gold Axe"
GoldAxe.Parent = ToolsScreen
GoldAxe.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
GoldAxe.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
GoldAxe.BorderSizePixel = 2
GoldAxe.Position = UDim2.new(0.457207233, 0, 0.478260875, 0)
GoldAxe.Size = UDim2.new(0, 147, 0, 20)
GoldAxe.Font = Enum.Font.SourceSans
GoldAxe.Text = "Golden Axe"
GoldAxe.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
GoldAxe.TextScaled = true
GoldAxe.TextSize = 24
GoldAxe.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
GoldAxe.TextWrapped = true

LeakedItems.Name = "Leaked Items"
LeakedItems.Parent = ToolsScreen
LeakedItems.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
LeakedItems.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
LeakedItems.BorderSizePixel = 2
LeakedItems.Position = UDim2.new(0.456081092, 0, 0.617391288, 0)
LeakedItems.Size = UDim2.new(0, 147, 0, 20)
LeakedItems.Font = Enum.Font.SourceSans
LeakedItems.Text = "Leaked Items"
LeakedItems.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
LeakedItems.TextScaled = true
LeakedItems.TextSize = 24
LeakedItems.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
LeakedItems.TextWrapped = true

TeleportTool.Name = "Teleport Tool"
TeleportTool.Parent = ToolsScreen
TeleportTool.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
TeleportTool.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
TeleportTool.BorderSizePixel = 2
TeleportTool.Position = UDim2.new(0.456081092, 0, 0.756521761, 0)
TeleportTool.Size = UDim2.new(0, 147, 0, 20)
TeleportTool.Font = Enum.Font.SourceSans
TeleportTool.Text = "Ctrl + Click TP"
TeleportTool.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
TeleportTool.TextScaled = true
TeleportTool.TextSize = 24
TeleportTool.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
TeleportTool.TextWrapped = true

GreyWood.Name = "Grey Wood"
GreyWood.Parent = ToolsScreen
GreyWood.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
GreyWood.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
GreyWood.BorderSizePixel = 2
GreyWood.Position = UDim2.new(0.456081092, 0, 0.900000036, 0)
GreyWood.Size = UDim2.new(0, 147, 0, 20)
GreyWood.Font = Enum.Font.SourceSans
GreyWood.Text = "Grey Wood"
GreyWood.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
GreyWood.TextScaled = true
GreyWood.TextSize = 24
GreyWood.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
GreyWood.TextWrapped = true

DupeLabel.Name = "DupeLabel"
DupeLabel.Parent = ToolsScreen
DupeLabel.BackgroundColor3 = Color3.new(1, 1, 1)
DupeLabel.BackgroundTransparency = 1
DupeLabel.BorderColor3 = Color3.new(0.666667, 0, 0)
DupeLabel.BorderSizePixel = 0
DupeLabel.Position = UDim2.new(0.493243247, 0, 0.286956519, 0)
DupeLabel.Size = UDim2.new(0, 115, 0, 14)
DupeLabel.Font = Enum.Font.SciFi
DupeLabel.Text = "Disabled"
DupeLabel.TextColor3 = Color3.new(0.666667, 0, 0)
DupeLabel.TextSize = 14

TeleportsScreen.Name = "TeleportsScreen"
TeleportsScreen.Parent = Drag
TeleportsScreen.BackgroundColor3 = Color3.new(0.105882, 0.164706, 0.207843)
TeleportsScreen.BackgroundTransparency = 1
TeleportsScreen.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
TeleportsScreen.BorderSizePixel = 0
TeleportsScreen.Draggable = true
TeleportsScreen.Position = UDim2.new(0.0164813697, 0, -0.000777035952, 0)
TeleportsScreen.Size = UDim2.new(0, 444, 0, 230)
TeleportsScreen.Visible = false

Spawn.Name = "Spawn"
Spawn.Parent = TeleportsScreen
Spawn.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
Spawn.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Spawn.BorderSizePixel = 2
Spawn.Position = UDim2.new(0.290540546, 0, 0.226086959, 0)
Spawn.Size = UDim2.new(0, 84, 0, 21)
Spawn.Font = Enum.Font.SourceSans
Spawn.Text = "Spawn"
Spawn.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Spawn.TextSize = 24
Spawn.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Spawn.TextWrapped = true

Den.Name = "Den"
Den.Parent = TeleportsScreen
Den.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
Den.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Den.BorderSizePixel = 2
Den.Position = UDim2.new(0.290540546, 0, 0.352173924, 0)
Den.Size = UDim2.new(0, 84, 0, 21)
Den.Font = Enum.Font.SourceSans
Den.Text = "The Den"
Den.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Den.TextSize = 24
Den.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Den.TextWrapped = true

StrangeMan.Name = "Strange Man"
StrangeMan.Parent = TeleportsScreen
StrangeMan.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
StrangeMan.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
StrangeMan.BorderSizePixel = 2
StrangeMan.Position = UDim2.new(0.290540546, 0, 0.482608676, 0)
StrangeMan.Size = UDim2.new(0, 84, 0, 21)
StrangeMan.Font = Enum.Font.SourceSans
StrangeMan.Text = "Strange Man"
StrangeMan.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
StrangeMan.TextScaled = true
StrangeMan.TextSize = 24
StrangeMan.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
StrangeMan.TextWrapped = true

Swamp.Name = "Swamp"
Swamp.Parent = TeleportsScreen
Swamp.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
Swamp.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Swamp.BorderSizePixel = 2
Swamp.Position = UDim2.new(0.290540546, 0, 0.617391288, 0)
Swamp.Size = UDim2.new(0, 84, 0, 21)
Swamp.Font = Enum.Font.SourceSans
Swamp.Text = "Swamp"
Swamp.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Swamp.TextSize = 24
Swamp.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Swamp.TextWrapped = true

Fancy.Name = "Fancy"
Fancy.Parent = TeleportsScreen
Fancy.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
Fancy.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Fancy.BorderSizePixel = 2
Fancy.Position = UDim2.new(0.290540546, 0, 0.747826099, 0)
Fancy.Size = UDim2.new(0, 84, 0, 21)
Fancy.Font = Enum.Font.SourceSans
Fancy.Text = "Fancy"
Fancy.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Fancy.TextSize = 24
Fancy.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Fancy.TextWrapped = true

BoxedCars.Name = "Boxed Cars"
BoxedCars.Parent = TeleportsScreen
BoxedCars.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
BoxedCars.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
BoxedCars.BorderSizePixel = 2
BoxedCars.Position = UDim2.new(0.290540546, 0, 0.87391305, 0)
BoxedCars.Size = UDim2.new(0, 84, 0, 21)
BoxedCars.Font = Enum.Font.SourceSans
BoxedCars.Text = "Boxed Cars"
BoxedCars.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
BoxedCars.TextScaled = true
BoxedCars.TextSize = 24
BoxedCars.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
BoxedCars.TextWrapped = true

Dropoff.Name = "Dropoff"
Dropoff.Parent = TeleportsScreen
Dropoff.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
Dropoff.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Dropoff.BorderSizePixel = 2
Dropoff.Position = UDim2.new(0.538288295, 0, 0.226086959, 0)
Dropoff.Size = UDim2.new(0, 84, 0, 21)
Dropoff.Font = Enum.Font.SourceSans
Dropoff.Text = "Dropoff"
Dropoff.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Dropoff.TextSize = 24
Dropoff.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Dropoff.TextWrapped = true

GreenBox.Name = "Green Box"
GreenBox.Parent = TeleportsScreen
GreenBox.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
GreenBox.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
GreenBox.BorderSizePixel = 2
GreenBox.Position = UDim2.new(0.538288295, 0, 0.352173924, 0)
GreenBox.Size = UDim2.new(0, 84, 0, 21)
GreenBox.Font = Enum.Font.SourceSans
GreenBox.Text = "Green Box"
GreenBox.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
GreenBox.TextScaled = true
GreenBox.TextSize = 24
GreenBox.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
GreenBox.TextWrapped = true

Cave.Name = "Cave"
Cave.Parent = TeleportsScreen
Cave.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
Cave.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Cave.BorderSizePixel = 2
Cave.Position = UDim2.new(0.538288295, 0, 0.482608676, 0)
Cave.Size = UDim2.new(0, 84, 0, 21)
Cave.Font = Enum.Font.SourceSans
Cave.Text = "Cave"
Cave.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Cave.TextSize = 24
Cave.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Cave.TextWrapped = true

Palm.Name = "Palm"
Palm.Parent = TeleportsScreen
Palm.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
Palm.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Palm.BorderSizePixel = 2
Palm.Position = UDim2.new(0.538288295, 0, 0.617391288, 0)
Palm.Size = UDim2.new(0, 84, 0, 21)
Palm.Font = Enum.Font.SourceSans
Palm.Text = "Palm"
Palm.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Palm.TextSize = 24
Palm.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Palm.TextWrapped = true

WoodRUs.Name = "Wood R Us"
WoodRUs.Parent = TeleportsScreen
WoodRUs.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
WoodRUs.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
WoodRUs.BorderSizePixel = 2
WoodRUs.Position = UDim2.new(0.538288295, 0, 0.747826099, 0)
WoodRUs.Size = UDim2.new(0, 84, 0, 21)
WoodRUs.Font = Enum.Font.SourceSans
WoodRUs.Text = "Wood R Us"
WoodRUs.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
WoodRUs.TextScaled = true
WoodRUs.TextSize = 24
WoodRUs.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
WoodRUs.TextWrapped = true

LinksLogic.Name = "Links Logic"
LinksLogic.Parent = TeleportsScreen
LinksLogic.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
LinksLogic.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
LinksLogic.BorderSizePixel = 2
LinksLogic.Position = UDim2.new(0.538288295, 0, 0.87391305, 0)
LinksLogic.Size = UDim2.new(0, 84, 0, 21)
LinksLogic.Font = Enum.Font.SourceSans
LinksLogic.Text = "Link's Logic"
LinksLogic.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
LinksLogic.TextScaled = true
LinksLogic.TextSize = 24
LinksLogic.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
LinksLogic.TextWrapped = true

YourPlot.Name = "Your Plot"
YourPlot.Parent = TeleportsScreen
YourPlot.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
YourPlot.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
YourPlot.BorderSizePixel = 2
YourPlot.Position = UDim2.new(0.77477479, 0, 0.87391305, 0)
YourPlot.Size = UDim2.new(0, 84, 0, 21)
YourPlot.Font = Enum.Font.SourceSans
YourPlot.Text = "Your Plot"
YourPlot.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
YourPlot.TextSize = 24
YourPlot.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
YourPlot.TextWrapped = true

BobsShack.Name = "Bobs Shack"
BobsShack.Parent = TeleportsScreen
BobsShack.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
BobsShack.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
BobsShack.BorderSizePixel = 2
BobsShack.Position = UDim2.new(0.77477479, 0, 0.747826099, 0)
BobsShack.Size = UDim2.new(0, 84, 0, 21)
BobsShack.Font = Enum.Font.SourceSans
BobsShack.Text = "Bob's Shack"
BobsShack.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
BobsShack.TextScaled = true
BobsShack.TextSize = 24
BobsShack.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
BobsShack.TextWrapped = true

EndTimes.Name = "End Times"
EndTimes.Parent = TeleportsScreen
EndTimes.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
EndTimes.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
EndTimes.BorderSizePixel = 2
EndTimes.Position = UDim2.new(0.77477479, 0, 0.617391288, 0)
EndTimes.Size = UDim2.new(0, 84, 0, 21)
EndTimes.Font = Enum.Font.SourceSans
EndTimes.Text = "End Times"
EndTimes.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
EndTimes.TextScaled = true
EndTimes.TextSize = 24
EndTimes.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
EndTimes.TextWrapped = true

Volcano.Name = "Volcano"
Volcano.Parent = TeleportsScreen
Volcano.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
Volcano.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Volcano.BorderSizePixel = 2
Volcano.Position = UDim2.new(0.77477479, 0, 0.482608676, 0)
Volcano.Size = UDim2.new(0, 84, 0, 21)
Volcano.Font = Enum.Font.SourceSans
Volcano.Text = "Volcano"
Volcano.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Volcano.TextSize = 24
Volcano.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Volcano.TextWrapped = true

Lodge.Name = "Lodge"
Lodge.Parent = TeleportsScreen
Lodge.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
Lodge.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Lodge.BorderSizePixel = 2
Lodge.Position = UDim2.new(0.77477479, 0, 0.352173924, 0)
Lodge.Size = UDim2.new(0, 84, 0, 21)
Lodge.Font = Enum.Font.SourceSans
Lodge.Text = "Lodge"
Lodge.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Lodge.TextSize = 24
Lodge.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Lodge.TextWrapped = true

Shrine.Name = "Shrine"
Shrine.Parent = TeleportsScreen
Shrine.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
Shrine.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Shrine.BorderSizePixel = 2
Shrine.Position = UDim2.new(0.77477479, 0, 0.226086959, 0)
Shrine.Size = UDim2.new(0, 84, 0, 21)
Shrine.Font = Enum.Font.SourceSans
Shrine.Text = "Shrine"
Shrine.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Shrine.TextSize = 24
Shrine.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Shrine.TextWrapped = true

PlayersScreen.Name = "PlayersScreen"
PlayersScreen.Parent = Drag
PlayersScreen.BackgroundColor3 = Color3.new(0.105882, 0.164706, 0.207843)
PlayersScreen.BackgroundTransparency = 1
PlayersScreen.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
PlayersScreen.BorderSizePixel = 0
PlayersScreen.Draggable = true
PlayersScreen.Position = UDim2.new(0.0164813697, 0, -0.000777035952, 0)
PlayersScreen.Size = UDim2.new(0, 444, 0, 230)
PlayersScreen.Visible = false

P1.Name = "P1"
P1.Parent = PlayersScreen
P1.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
P1.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
P1.BorderSizePixel = 2
P1.Position = UDim2.new(0.272522509, 0, 0.226086959, 0)
P1.Size = UDim2.new(0, 147, 0, 21)
P1.Font = Enum.Font.SourceSans
P1.Text = " "
P1.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
P1.TextSize = 24
P1.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

P2.Name = "P2"
P2.Parent = PlayersScreen
P2.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
P2.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
P2.BorderSizePixel = 2
P2.Position = UDim2.new(0.628378332, 0, 0.226086974, 0)
P2.Size = UDim2.new(0, 158, 0, 21)
P2.Font = Enum.Font.SourceSans
P2.Text = " "
P2.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
P2.TextSize = 24
P2.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

P4.Name = "P4"
P4.Parent = PlayersScreen
P4.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
P4.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
P4.BorderSizePixel = 2
P4.Position = UDim2.new(0.628378332, 0, 0.352173924, 0)
P4.Size = UDim2.new(0, 158, 0, 21)
P4.Font = Enum.Font.SourceSans
P4.Text = " "
P4.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
P4.TextSize = 24
P4.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

P3.Name = "P3"
P3.Parent = PlayersScreen
P3.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
P3.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
P3.BorderSizePixel = 2
P3.Position = UDim2.new(0.272522509, 0, 0.352173924, 0)
P3.Size = UDim2.new(0, 147, 0, 21)
P3.Font = Enum.Font.SourceSans
P3.Text = " "
P3.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
P3.TextSize = 24
P3.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

P6.Name = "P6"
P6.Parent = PlayersScreen
P6.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
P6.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
P6.BorderSizePixel = 2
P6.Position = UDim2.new(0.628378332, 0, 0.482608706, 0)
P6.Size = UDim2.new(0, 158, 0, 21)
P6.Font = Enum.Font.SourceSans
P6.Text = ""
P6.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
P6.TextSize = 24
P6.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

P5.Name = "P5"
P5.Parent = PlayersScreen
P5.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
P5.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
P5.BorderSizePixel = 2
P5.Position = UDim2.new(0.272522509, 0, 0.482608706, 0)
P5.Size = UDim2.new(0, 147, 0, 21)
P5.Font = Enum.Font.SourceSans
P5.Text = " "
P5.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
P5.TextSize = 24
P5.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

TpToPlayer.Name = "TpToPlayer"
TpToPlayer.Parent = PlayersScreen
TpToPlayer.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
TpToPlayer.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
TpToPlayer.BorderSizePixel = 2
TpToPlayer.Position = UDim2.new(0.405405402, 0, 0.656521738, 0)
TpToPlayer.Size = UDim2.new(0, 179, 0, 21)
TpToPlayer.Font = Enum.Font.SourceSans
TpToPlayer.Text = "Teleport To Player"
TpToPlayer.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
TpToPlayer.TextSize = 24
TpToPlayer.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

TpToPlayerBase.Name = "TpToPlayerBase"
TpToPlayerBase.Parent = PlayersScreen
TpToPlayerBase.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
TpToPlayerBase.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
TpToPlayerBase.BorderSizePixel = 2
TpToPlayerBase.Position = UDim2.new(0.405405402, 0, 0.813043475, 0)
TpToPlayerBase.Size = UDim2.new(0, 179, 0, 21)
TpToPlayerBase.Font = Enum.Font.SourceSans
TpToPlayerBase.Text = "Teleport To Base"
TpToPlayerBase.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
TpToPlayerBase.TextSize = 24
TpToPlayerBase.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

PSelected.Name = "PSelected"
PSelected.Parent = PlayersScreen
PSelected.BackgroundColor3 = Color3.new(1, 1, 1)
PSelected.BackgroundTransparency = 1
PSelected.BorderSizePixel = 0
PSelected.Position = UDim2.new(0.405405402, 0, 0.904347837, 0)
PSelected.Size = UDim2.new(0, 179, 0, 22)
PSelected.Font = Enum.Font.SourceSans
PSelected.Text = ""
PSelected.TextColor3 = Color3.new(0.117647, 0.501961, 0.639216)
PSelected.TextSize = 20

LocalScreen.Name = "LocalScreen"
LocalScreen.Parent = Drag
LocalScreen.BackgroundColor3 = Color3.new(0.105882, 0.164706, 0.207843)
LocalScreen.BackgroundTransparency = 1
LocalScreen.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
LocalScreen.BorderSizePixel = 0
LocalScreen.Draggable = true
LocalScreen.Position = UDim2.new(0.0164813697, 0, -0.000777035952, 0)
LocalScreen.Size = UDim2.new(0, 444, 0, 230)
LocalScreen.Visible = false

God.Name = "God"
God.Parent = LocalScreen
God.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
God.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
God.BorderSizePixel = 2
God.Position = UDim2.new(0.457207203, 0, 0.226086944, 0)
God.Size = UDim2.new(0, 158, 0, 21)
God.Font = Enum.Font.SourceSans
God.Text = "God"
God.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
God.TextSize = 24
God.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

Noclip.Name = "Noclip"
Noclip.Parent = LocalScreen
Noclip.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
Noclip.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Noclip.BorderSizePixel = 2
Noclip.Position = UDim2.new(0.457207203, 0, 0.352173924, 0)
Noclip.Size = UDim2.new(0, 158, 0, 21)
Noclip.Font = Enum.Font.SourceSans
Noclip.Text = "Noclip"
Noclip.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Noclip.TextSize = 24
Noclip.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

Walkspeed.Name = "Walkspeed"
Walkspeed.Parent = LocalScreen
Walkspeed.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
Walkspeed.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Walkspeed.BorderSizePixel = 2
Walkspeed.Position = UDim2.new(0.457207203, 0, 0.523913026, 0)
Walkspeed.Size = UDim2.new(0, 158, 0, 21)
Walkspeed.Font = Enum.Font.SourceSans
Walkspeed.Text = "Walkspeed"
Walkspeed.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Walkspeed.TextSize = 24
Walkspeed.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

Jumppower.Name = "Jumppower"
Jumppower.Parent = LocalScreen
Jumppower.BackgroundColor3 = Color3.new(0.117647, 0.501961, 0.639216)
Jumppower.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Jumppower.BorderSizePixel = 2
Jumppower.Position = UDim2.new(0.457207203, 0, 0.70869565, 0)
Jumppower.Size = UDim2.new(0, 158, 0, 21)
Jumppower.Font = Enum.Font.SourceSans
Jumppower.Text = "Jumppower"
Jumppower.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Jumppower.TextSize = 24
Jumppower.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

NoclipLabel.Name = "NoclipLabel"
NoclipLabel.Parent = LocalScreen
NoclipLabel.BackgroundColor3 = Color3.new(1, 1, 1)
NoclipLabel.BackgroundTransparency = 1
NoclipLabel.BorderColor3 = Color3.new(0.666667, 0, 0)
NoclipLabel.BorderSizePixel = 0
NoclipLabel.Position = UDim2.new(0.504504502, 0, 0.443478256, 0)
NoclipLabel.Size = UDim2.new(0, 115, 0, 19)
NoclipLabel.Font = Enum.Font.SciFi
NoclipLabel.Text = "Disabled"
NoclipLabel.TextColor3 = Color3.new(0.666667, 0, 0)
NoclipLabel.TextSize = 14

WalkspeedValue.Name = "WalkspeedValue"
WalkspeedValue.Parent = LocalScreen
WalkspeedValue.BackgroundColor3 = Color3.new(1, 1, 1)
WalkspeedValue.BackgroundTransparency = 1
WalkspeedValue.BorderSizePixel = 0
WalkspeedValue.Position = UDim2.new(0.457207203, 0, 0.617391288, 0)
WalkspeedValue.Size = UDim2.new(0, 158, 0, 21)
WalkspeedValue.Font = Enum.Font.SourceSans
WalkspeedValue.Text = "Walkspeed Value"
WalkspeedValue.TextColor3 = Color3.new(0.117647, 0.501961, 0.639216)
WalkspeedValue.TextSize = 14

JumppowerValue.Name = "JumppowerValue"
JumppowerValue.Parent = LocalScreen
JumppowerValue.BackgroundColor3 = Color3.new(1, 1, 1)
JumppowerValue.BackgroundTransparency = 1
JumppowerValue.BorderSizePixel = 0
JumppowerValue.Position = UDim2.new(0.457207203, 0, 0.799999952, 0)
JumppowerValue.Size = UDim2.new(0, 158, 0, 21)
JumppowerValue.Font = Enum.Font.SourceSans
JumppowerValue.Text = "Jumppower Value"
JumppowerValue.TextColor3 = Color3.new(0.117647, 0.501961, 0.639216)
JumppowerValue.TextSize = 14

EtoFly.Name = "EtoFly"
EtoFly.Parent = LocalScreen
EtoFly.BackgroundColor3 = Color3.new(1, 1, 1)
EtoFly.BackgroundTransparency = 1
EtoFly.BorderSizePixel = 0
EtoFly.Position = UDim2.new(0.409909904, 0, 0.895652175, 0)
EtoFly.Size = UDim2.new(0, 200, 0, 29)
EtoFly.Font = Enum.Font.SourceSans
EtoFly.Text = "Press \"Q\" to Fly"
EtoFly.TextColor3 = Color3.new(0.117647, 0.501961, 0.639216)
EtoFly.TextSize = 14

HomeScreen.Name = "HomeScreen"
HomeScreen.Parent = Drag
HomeScreen.BackgroundColor3 = Color3.new(1, 1, 1)
HomeScreen.BackgroundTransparency = 1
HomeScreen.BorderSizePixel = 0
HomeScreen.Position = UDim2.new(-0.208425716, 0, -0.273504287, 0)
HomeScreen.Size = UDim2.new(0, 450, 0, 232)
HomeScreen.Visible = false

WelcomeName.Name = "WelcomeName"
WelcomeName.Parent = HomeScreen
WelcomeName.BackgroundColor3 = Color3.new(1, 1, 1)
WelcomeName.BackgroundTransparency = 1
WelcomeName.BorderSizePixel = 0
WelcomeName.Position = UDim2.new(0.512882888, 0, 0.402361304, 0)
WelcomeName.Size = UDim2.new(0, 295, 0, 50)
WelcomeName.Font = Enum.Font.SourceSans
WelcomeName.Text = "Welcome"
WelcomeName.TextColor3 = Color3.new(0.117647, 0.501961, 0.639216)
WelcomeName.TextSize = 26
WelcomeName.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
WelcomeName.TextStrokeTransparency = 0.64999997615814
WelcomeName.TextWrapped = true

WelcomeMOTD.Name = "WelcomeMOTD"
WelcomeMOTD.Parent = HomeScreen
WelcomeMOTD.BackgroundColor3 = Color3.new(1, 1, 1)
WelcomeMOTD.BackgroundTransparency = 1
WelcomeMOTD.Position = UDim2.new(0.524598598, 0, 0.615812302, 0)
WelcomeMOTD.Size = UDim2.new(0, 295, 0, 122)
WelcomeMOTD.Font = Enum.Font.SourceSans
WelcomeMOTD.Text = "I heard there are a lot of wild haxors on the lose. Be careful out there."
WelcomeMOTD.TextColor3 = Color3.new(0.117647, 0.501961, 0.639216)
WelcomeMOTD.TextSize = 30
WelcomeMOTD.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
WelcomeMOTD.TextStrokeTransparency = 0.64999997615814
WelcomeMOTD.TextWrapped = true

WelcomeAuthor.Name = "WelcomeAuthor"
WelcomeAuthor.Parent = HomeScreen
WelcomeAuthor.BackgroundColor3 = Color3.new(1, 1, 1)
WelcomeAuthor.BackgroundTransparency = 1
WelcomeAuthor.BorderSizePixel = 0
WelcomeAuthor.Position = UDim2.new(0.621117353, 0, 1.14139926, 0)
WelcomeAuthor.Size = UDim2.new(0, 200, 0, 22)
WelcomeAuthor.Font = Enum.Font.SourceSans
WelcomeAuthor.Text = "By Casual#2435"
WelcomeAuthor.TextColor3 = Color3.new(0.117647, 0.501961, 0.639216)
WelcomeAuthor.TextSize = 12
WelcomeAuthor.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
WelcomeAuthor.TextStrokeTransparency = 0.64999997615814
WelcomeAuthor.TextWrapped = true

ChangelogScreen.Name = "ChangelogScreen"
ChangelogScreen.Parent = Drag
ChangelogScreen.BackgroundColor3 = Color3.new(1, 1, 1)
ChangelogScreen.BackgroundTransparency = 1
ChangelogScreen.BorderSizePixel = 0
ChangelogScreen.Position = UDim2.new(0.24833703, 0, 0.17521368, 0)
ChangelogScreen.Size = UDim2.new(0, 337, 0, 193)
ChangelogScreen.Visible = false

Logs.Name = "Logs"
Logs.Parent = ChangelogScreen
Logs.BackgroundColor3 = Color3.new(1, 1, 1)
Logs.BackgroundTransparency = 1
Logs.BorderSizePixel = 0
Logs.Position = UDim2.new(0.0207715146, 0, 0, 0)
Logs.Size = UDim2.new(0, 322, 0, 39)
Logs.Font = Enum.Font.SourceSans
Logs.Text = "-1.0 Huge Improvement on Look of Gui"
Logs.TextColor3 = Color3.new(0.117647, 0.501961, 0.639216)
Logs.TextSize = 20

Logs2.Name = "Logs2"
Logs2.Parent = ChangelogScreen
Logs2.BackgroundColor3 = Color3.new(1, 1, 1)
Logs2.BackgroundTransparency = 1
Logs2.BorderSizePixel = 0
Logs2.Position = UDim2.new(0.0296735913, 0, 0.160621762, 0)
Logs2.Size = UDim2.new(0, 322, 0, 85)
Logs2.Font = Enum.Font.SourceSans
Logs2.Text = "-1.1 Fixed bug that caused you not to be able to changewalkspeed and made you walk slow when you turned on god mode."
Logs2.TextColor3 = Color3.new(0.117647, 0.501961, 0.639216)
Logs2.TextSize = 20
Logs2.TextWrapped = true

Logs3.Name = "Logs3"
Logs3.Parent = ChangelogScreen
Logs3.BackgroundColor3 = Color3.new(1, 1, 1)
Logs3.BackgroundTransparency = 1
Logs3.BorderSizePixel = 0
Logs3.Position = UDim2.new(0.0296735913, 0, 0.46632123, 0)
Logs3.Size = UDim2.new(0, 322, 0, 85)
Logs3.Font = Enum.Font.SourceSans
Logs3.Text = "-1.2 Added 3 new features - Hard Dragger, Teleport Gifts and Flight"
Logs3.TextColor3 = Color3.new(0.117647, 0.501961, 0.639216)
Logs3.TextSize = 20
Logs3.TextWrapped = true

Log1and2Div.Name = "Log1and2Div"
Log1and2Div.Parent = ChangelogScreen
Log1and2Div.BackgroundColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Log1and2Div.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Log1and2Div.Position = UDim2.new(0.0534124635, 0, 0.196891189, 0)
Log1and2Div.Size = UDim2.new(0, 306, 0, 1)
Log1and2Div.Font = Enum.Font.SourceSans
Log1and2Div.Text = ""
Log1and2Div.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Log1and2Div.TextSize = 24
Log1and2Div.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

Log2and3Div.Name = "Log2and3Div"
Log2and3Div.Parent = ChangelogScreen
Log2and3Div.BackgroundColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Log2and3Div.BorderColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Log2and3Div.Position = UDim2.new(0.0534124635, 0, 0.569948196, 0)
Log2and3Div.Size = UDim2.new(0, 306, 0, 1)
Log2and3Div.Font = Enum.Font.SourceSans
Log2and3Div.Text = ""
Log2and3Div.TextColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)
Log2and3Div.TextSize = 24
Log2and3Div.TextStrokeColor3 = Color3.new(0.0392157, 0.0627451, 0.0823529)

--------
-- Fly
repeat wait()
    until game.Players.LocalPlayer and game.Players.LocalPlayer.Character and game.Players.LocalPlayer.Character:findFirstChild("Torso") and game.Players.LocalPlayer.Character:findFirstChild("Humanoid")
local mouse = game.Players.LocalPlayer:GetMouse()
repeat wait() until mouse
local plr = game.Players.LocalPlayer
local torso = plr.Character.Torso
local flying = true
local deb = true
local ctrl = {f = 0, b = 0, l = 0, r = 0}
local lastctrl = {f = 0, b = 0, l = 0, r = 0}
local maxspeed = 50
local speed = 0
 
function Fly()
local bg = Instance.new("BodyGyro", torso)
bg.P = 9e4
bg.maxTorque = Vector3.new(9e9, 9e9, 9e9)
bg.cframe = torso.CFrame
local bv = Instance.new("BodyVelocity", torso)
bv.velocity = Vector3.new(0,0.1,0)
bv.maxForce = Vector3.new(9e9, 9e9, 9e9)
repeat wait()
plr.Character.Humanoid.PlatformStand = true
if ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0 then
speed = speed+.5+(speed/maxspeed)
if speed > maxspeed then
speed = maxspeed
end
elseif not (ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0) and speed ~= 0 then
speed = speed-1
if speed < 0 then
speed = 0
end
end
if (ctrl.l + ctrl.r) ~= 0 or (ctrl.f + ctrl.b) ~= 0 then
bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (ctrl.f+ctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(ctrl.l+ctrl.r,(ctrl.f+ctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
lastctrl = {f = ctrl.f, b = ctrl.b, l = ctrl.l, r = ctrl.r}
elseif (ctrl.l + ctrl.r) == 0 and (ctrl.f + ctrl.b) == 0 and speed ~= 0 then
bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (lastctrl.f+lastctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(lastctrl.l+lastctrl.r,(lastctrl.f+lastctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
else
bv.velocity = Vector3.new(0,0.1,0)
end
bg.cframe = game.Workspace.CurrentCamera.CoordinateFrame * CFrame.Angles(-math.rad((ctrl.f+ctrl.b)*50*speed/maxspeed),0,0)
until not flying
ctrl = {f = 0, b = 0, l = 0, r = 0}
lastctrl = {f = 0, b = 0, l = 0, r = 0}
speed = 0
bg:Destroy()
bv:Destroy()
plr.Character.Humanoid.PlatformStand = false
end
mouse.KeyDown:connect(function(key)
if key:lower() == "q" then
if flying then flying = false
AAPressQ.Visible = false
else
flying = true
Fly()
end
elseif key:lower() == "w" then
ctrl.f = 1
elseif key:lower() == "s" then
ctrl.b = -1
elseif key:lower() == "a" then
ctrl.l = -1
elseif key:lower() == "d" then
ctrl.r = 1
end
end)
mouse.KeyUp:connect(function(key)
if key:lower() == "w" then
ctrl.f = 0
elseif key:lower() == "s" then
ctrl.b = 0
elseif key:lower() == "a" then
ctrl.l = 0
elseif key:lower() == "d" then
ctrl.r = 0
end
end)
Fly()

AnimWelcomeScreen.Visible = true
AnimWelcomeScreen:TweenSizeAndPosition(UDim2.new(0, 200, 0, 200), UDim2.new(0.5, -100, 0.5, -100), "Out", "Quad", .25)
wait(2)
ImageLabel:Destroy()
AnimWelcomeScreen:TweenSizeAndPosition(UDim2.new(0, 0, 0, 0),UDim2.new(0.5, 0, 0.5, 0), "Out", "Bounce", 0.5);wait(0.5);AnimWelcomeScreen:Destroy();
wait(2)
HomeScreen.Visible = true
Main.Visible = true


HiName.Text = "Hi "..game.Players.LocalPlayer.Name
WelcomeName.Text = "Welcome "..game.Players.LocalPlayer.Name

--Opening Tabs
 P1.MouseButton1Down:connect(function()
      PSelected.Text = P1.Text
    end)
 P2.MouseButton1Down:connect(function()
      PSelected.Text = P2.Text
    end)
 P3.MouseButton1Down:connect(function()
      PSelected.Text = P3.Text
    end)
 P4.MouseButton1Down:connect(function()
      PSelected.Text = P4.Text
    end)
 P5.MouseButton1Down:connect(function()
      PSelected.Text = P5.Text
    end)
 P6.MouseButton1Down:connect(function()
      PSelected.Text = P6.Text
    end)
    local buttons = {
     PlayersScreen.P1,
     PlayersScreen.P2,
     PlayersScreen.P3,
     PlayersScreen.P4,
     PlayersScreen.P5,
     PlayersScreen.P6
    }

for i, v in pairs(game.Players:GetChildren()) do
      buttons[i].Text = v.Name
      buttons[i].Visible = true
    end
    game.Players.PlayerRemoving:connect(function()
      for i, v in pairs(game.Players:GetChildren()) do
        buttons[i].Text = v.Name
        buttons[i].Visible = true
      end
    end)
    game.Players.PlayerAdded:connect(function()
      for i, v in pairs(game.Players:GetChildren()) do
        buttons[i].Text = v.Name
        buttons[i].Visible = true
      end
    end)

if PlayersScreen.P1.text == " " then
P1.Visible = false
end

if PlayersScreen.P2.text == " " then
P2.Visible = false
end

if PlayersScreen.P3.text == " " then
P3.Visible = false
end

if PlayersScreen.P4.text == " " then
P4.Visible = false
end

if PlayersScreen.P5.text == " " then
P5.Visible = false
end

if PlayersScreen.P6.text == "" then
P6.Visible = false
end

TpToPlayer.MouseButton1Down:connect(function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = workspace[PSelected.Text].HumanoidRootPart.CFrame
end)

TpToPlayerBase.MouseButton1Down:connect(function()
for i, v in pairs(game.Workspace.Properties:GetChildren()) do
		if v.Owner.Value == game.Players[PSelected.Text] then
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.OriginSquare.CFrame
end
end
end)

X.MouseButton1Down:connect(function()
Drag.Visible = false
OpenBtn.Visible = true
end)

OpenBtn.MouseButton1Down:connect(function()
Drag.Visible = true
OpenBtn.Visible = false
end)

HomeLocal.MouseButton1Down:connect(function()
Main.Visible = true
AnimWelcomeScreen.Visible = false
HomeScreen.Visible = false
LocalScreen.Visible = true
PlayersScreen.Visible = false
WoodScreen.Visible = false
TeleportsScreen.Visible = false
ToolsScreen.Visible = false
OpenBtn.Visible = false
ChangelogScreen.Visible = false
end)

HomePlayers.MouseButton1Down:connect(function()
Main.Visible = true
AnimWelcomeScreen.Visible = false
HomeScreen.Visible = false
LocalScreen.Visible = false
PlayersScreen.Visible = true
WoodScreen.Visible = false
TeleportsScreen.Visible = false
ToolsScreen.Visible = false
OpenBtn.Visible = false
ChangelogScreen.Visible = false
end)

HomeWood.MouseButton1Down:connect(function()
Main.Visible = true
AnimWelcomeScreen.Visible = false
HomeScreen.Visible = false
LocalScreen.Visible = false
PlayersScreen.Visible = false
WoodScreen.Visible = true
TeleportsScreen.Visible = false
ToolsScreen.Visible = false
OpenBtn.Visible = false
ChangelogScreen.Visible = false
end)

HomeTeleports.MouseButton1Down:connect(function()
Main.Visible = true
AnimWelcomeScreen.Visible = false
HomeScreen.Visible = false
LocalScreen.Visible = false
PlayersScreen.Visible = false
WoodScreen.Visible = false
TeleportsScreen.Visible = true
ToolsScreen.Visible = false
OpenBtn.Visible = false
ChangelogScreen.Visible = false
end)

HomeTools.MouseButton1Down:connect(function()
Main.Visible = true
AnimWelcomeScreen.Visible = false
HomeScreen.Visible = false
LocalScreen.Visible = false
PlayersScreen.Visible = false
WoodScreen.Visible = false
TeleportsScreen.Visible = false
ToolsScreen.Visible = true
OpenBtn.Visible = false
ChangelogScreen.Visible = false
end)

HomeChangelog.MouseButton1Down:connect(function()
Main.Visible = true
AnimWelcomeScreen.Visible = false
HomeScreen.Visible = false
LocalScreen.Visible = false
PlayersScreen.Visible = false
WoodScreen.Visible = false
TeleportsScreen.Visible = false
ToolsScreen.Visible = false
OpenBtn.Visible = false
ChangelogScreen.Visible = true
end)

--Teleports
Palm.MouseButton1Down:connect(function() 
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(2570, -5, -32))
end)

BobsShack.MouseButton1Down:connect(function() 
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(259, 8, -2542))
end)

WoodRUs.MouseButton1Down:connect(function() 
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(251, 2, 57))
end)

Volcano.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character:MoveTo(Vector3.new(-1585, 622, 1140))
end)

Swamp.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character:MoveTo(Vector3.new(-1209, 132, -801))
end)

StrangeMan.MouseButton1Down:connect(function() 
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(1061, 16, 1130))
end)

Spawn.MouseButton1Down:connect(function() 
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(155, 3, 74))
end)

Shrine.MouseButton1Down:connect(function() 
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(1606, 195, 929)) 
end)

Lodge.MouseButton1Down:connect(function() 
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(1243, 63, 2305))
end)

LinksLogic.MouseButton1Down:connect(function() 
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(4606, 7, -779))
end)

GreenBox.MouseButton1Down:connect(function() 
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(-1675, 348, 1476))
end)

Fancy.MouseButton1Down:connect(function() 
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(491, 3, -1719))
end)

EndTimes.MouseButton1Down:connect(function() 
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(113, -213, -950))
end)

Dropoff.MouseButton1Down:connect(function() 
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(314, -2, 123))
end)

Den.MouseButton1Down:connect(function() 
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(331, 45, 1941))
end)

Cave.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character:MoveTo(Vector3.new(3581, -179, 430))
end)

BoxedCars.MouseButton1Down:connect(function() 
game.Players.LocalPlayer.Character:MoveTo(Vector3.new(508, 3, -1463))
end)

YourPlot.MouseButton1Down:connect(function()
	for i, v in pairs(game.Workspace.Properties:GetChildren()) do
		if v.Owner.Value == game.Players.LocalPlayer then
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.OriginSquare.CFrame
		end
	end
end)
--------------
--LocalPlayer Commands
-- God
God.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.Humanoid.Name = "1"
	local l = game.Players.LocalPlayer.Character["1"]:Clone()
	l.Parent = game.Players.LocalPlayer.Character
	l.Name = "Humanoid"
	wait(0.1)
	game.Players.LocalPlayer.Character["1"]:Destroy()
	game.Workspace.CurrentCamera.CameraSubject = game.Players.LocalPlayer.Character
	game.Players.LocalPlayer.Character.Animate.Disabled = true
	l.Changed:Connect(function()
		if l then
			l.WalkSpeed=game.Players.LocalPlayer.Character.Humanoid.WalkSpeed
			l.JumpPower=game.Players.LocalPlayer.Character.Humanoid.JumpPower
		end
	end)
end)
-- Noclip
noclip = false
game:GetService('RunService').Stepped:connect(function()
if noclip then
game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
NoclipLabel.TextColor3 = Color3.new(0, 1, 0)
NoclipLabel.Text = "Enabled"
end
end)
Noclip.MouseButton1Down:connect(function()
noclip = not noclip
NoclipLabel.TextColor3 = Color3.new(0.7, 0, 0)
NoclipLabel.Text = "Disabled"
end)
-- Walkspeed
Walkspeed.MouseButton1Down:connect(function()
while true do
	wait()
	game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = WalkspeedValue.Text
end
end)
-- Jumppower
Jumppower.MouseButton1Down:connect(function()
while true do
	wait()
	game.Players.LocalPlayer.Character.Humanoid.JumpPower = JumppowerValue.Text
end
end)
--Players Commands
-- Teleport To Player
-- teleport To Player Base

--Wood Commands
-- Teleport Cut Wood
TeleportCutWood.MouseButton1Down:connect(function()
for _, Log in pairs(game.Workspace.LogModels:GetChildren()) do
if Log.Name:sub(1, 6) == "Loose_" and Log:findFirstChild("Owner") then
if Log.Owner.Value == game.Players.LocalPlayer then
Log:MoveTo(game.Players.LocalPlayer.Character.Torso.Position + Vector3.new(0, 15, 0))
end
end
end
end)

-- Sell Cut Wood
SellCutWood.MouseButton1Down:connect(function()
	        for _, Log in pairs(workspace.LogModels:GetChildren()) do
        if Log.Name:sub(1, 6) == "Loose_" and Log:findFirstChild("Owner") then
            if Log.Owner.Value == game.Players.LocalPlayer then
                for i,v in pairs(Log:GetChildren()) do
                    if v.Name=="WoodSection" then
                        spawn(function()
                            for i=1,10 do
                                wait()
                                v.CFrame=CFrame.new(Vector3.new(315, -0.296, 85.791))*CFrame.Angles(math.rad(90),0,0)
                            end
                        end)
                    end
                end
                spawn(function()
                    for i=1,20 do
                        wait()
                        game.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(Log)
                    end
                end)
            end
        end
    end
end)
-- Teleport End Times Wood
TeleportEndTimesWood.MouseButton1Down:connect(function()
	for i, v in pairs(game.Workspace:GetChildren()) do
if v.Name == "TreeRegion" then
for a, b in pairs(v:GetChildren()) do
tree(b, "LoneCave")
end
end
end
end)
-- Teleport Cave Crawler Wood
TeleportCaveCrawlerWood.MouseButton1Down:connect(function()
	for i, v in pairs(game.Workspace:GetChildren()) do
if v.Name == "TreeRegion" then
for a, b in pairs(v:GetChildren()) do
tree(b, "CaveCrawler")
end
end
end
end)

--Tools Commands
-- Dupe
Dupe.MouseButton1Down:connect(function()
plr = game:GetService("Players").LocalPlayer
slot = plr.CurrentSaveSlot
if Option == false then
if slot.Value == -1 then
Option = true
slot.RobloxLocked = true
DupeLabel.TextColor3 = Color3.new(0, 1, 0)
DupeLabel.Text = "Enabled"
end
else
Option = false
slot.RobloxLocked = false
DupeLabel.TextColor3 = Color3.new(0.7, 0, 0)
DupeLabel.Text = "Disabled"
end
end)
-- Move Tools
Move.MouseButton1Down:connect(function()
local player = game.Players.LocalPlayer
local Character = player.Character or player.CharacterAdded:wait()
local Humanoid = Character:WaitForChild("Humanoid")
local walkSpeed = Humanoid.WalkSpeed
game.Players.LocalPlayer.PlayerGui.ItemDraggingGUI.Dragger.Disabled = true
_G.dragRangeMin = 5
fivefour = coroutine.wrap(function()
EKey = false
QKey = false
player:GetMouse().KeyDown:connect(function(key)
	if string.lower(key) == "e" then
		EKey = true
	elseif string.lower(key) == "q" then
		QKey = true
	end
end)
player:GetMouse().KeyUp:connect(function(key)
	if string.lower(key) == "e" then
		EKey = false
	elseif string.lower(key) == "q" then
		QKey = false
	end
end)
while wait(0.1) do
	if EKey then
		F = FVal
		FVal = FVal + 1000
		ChangeForce(F+1000)
		print(F)
	end
	if QKey then
		F = FVal
		FVal = FVal - 1000
		ChangeForce(F-1000)
		print(F)
	end
end

end)
fivefour()
local dragPart = Instance.new("Part",game.Players.LocalPlayer.PlayerGui)--game.Players.LocalPlayer.PlayerGui.ItemDraggingGUI.Dragger.Dragger
dragPart.Size = Vector3.new(0.2,0.2,0.2)
dragPart.BrickColor = BrickColor.new("Really red")
player.CharacterAdded:connect(function()
	Character = player.Character
	Humanoid = Character:WaitForChild("Humanoid")
	Humanoid.Died:connect(function()
		dragPart.Parent = nil
	end)
end)

wait(1)
local dragRangeMax = 10000
local dragRangeMin = _G.dragRangeMin

local camera = workspace.CurrentCamera
local mouse = player:GetMouse()

local button1Down = false
local dragRange = dragRangeMax
FVal = 80000
local bodyPosition = Instance.new("BodyPosition", dragPart)
bodyPosition.maxForce = Vector3.new(1, 1, 1) * FVal
bodyPosition.D = 1000
bodyPosition.P = 4000
function ChangeForce(F)
if F > 0 then
F = bodyPosition.maxForce.X+F
bodyPosition.maxForce = Vector3.new(1, 1, 1) * F
else
F = bodyPosition.maxForce.X-F
bodyPosition.maxForce = Vector3.new(1, 1, 1) * F
end
end

local bodyGyro = Instance.new("BodyGyro", dragPart) 
bodyGyro.maxTorque = Vector3.new(1, 1, 1) * 200 --4000 -- * 0.000012
bodyGyro.P = 1200
bodyGyro.D = 140 --15

--bodyPosition.P = bodyPosition.P * 1/19
--bodyPosition.D = bodyPosition.D  * 1/19
--bodyGyro.P = bodyGyro.P * 1/19
--bodyGyro.D = bodyGyro.D  * 1/19

local rotateCFrame = CFrame.new()

local weld = Instance.new("Weld", dragPart)

--local interactPermission = require(game.ReplicatedStorage.Interaction.InteractionPermission)
local clientIsDragging = game.ReplicatedStorage.Interaction.ClientIsDragging

local carryAnimationTrack


--------------------------------[[ Drag Main ]]------------------------------------

local draggingPart = false

function click()
	button1Down = true

	local targetObject = game.Players.LocalPlayer:GetMouse().Target
	if not canDrag(targetObject) then
		return
	end
	
	local mouseHit = game.Players.LocalPlayer:GetMouse().Hit.p
	if (mouseHit - Character.Head.Position).magnitude > dragRangeMax then
		return
	end
	
	initializeDrag(targetObject, mouseHit)
	rotateCFrame = CFrame.new()
	
	carryAnimationTrack:Play(0.1, 1, 1)
	
	local dragIsFailing = 0 
	local dragTime = 0
	
	
	while button1Down and canDrag(targetObject) do
		local desiredPos = Character.Head.Position + (game.Players.LocalPlayer:GetMouse().Hit.p - Character.Head.Position).unit * dragRange
		
		local dragRay = Ray.new(Character.Head.Position, desiredPos - Character.Head.Position)
		local part, pos = workspace:FindPartOnRayWithIgnoreList(dragRay, {Character, dragPart, targetObject.Parent})
		
		if part then
			desiredPos = pos
		end
		
		if (camera.CoordinateFrame.p - Character.Head.Position).magnitude > 2 then
			desiredPos = desiredPos + Vector3.new(0, 1.8, 0)
		end
		
		moveDrag(desiredPos)
		bodyGyro.cframe = CFrame.new(dragPart.Position, camera.CoordinateFrame.p) * rotateCFrame
		
		local targParent = findHighestParent(targetObject) or targetObject		
		
		local attemptingToSurf  = false
		for _, check in pairs({{Ray = Ray.new((Character.HumanoidRootPart.CFrame * CFrame.new(0.7, -2.8, 0)).p, Vector3.new(0, -2, 0))}, 
							{Ray = Ray.new((Character.HumanoidRootPart.CFrame * CFrame.new(0.35, -2.8, 0)).p, Vector3.new(0, -2, 0))}, 
							{Ray = Ray.new((Character.HumanoidRootPart.CFrame * CFrame.new(0, -2.8, 0)).p, Vector3.new(0, -2, 0))},
							{Ray = Ray.new((Character.HumanoidRootPart.CFrame * CFrame.new(0.35, -2.8, 0)).p, Vector3.new(0, -2, 0))}, 
							{Ray = Ray.new((Character.HumanoidRootPart.CFrame * CFrame.new(-0.7, -2.8, 0)).p, Vector3.new(0, -2, 0))}, 
							
							{Ray = Ray.new((Character.HumanoidRootPart.CFrame * CFrame.new(0.35, -2.8, 0.6)).p, Vector3.new(0, -2, 0))}, 
							{Ray = Ray.new((Character.HumanoidRootPart.CFrame * CFrame.new(0, -2.8, 0.6)).p, Vector3.new(0, -2, 0))},
							{Ray = Ray.new((Character.HumanoidRootPart.CFrame * CFrame.new(0.35, -2.8, 0.6)).p, Vector3.new(0, -2, 0))}, 
							
							{Ray = Ray.new((Character.HumanoidRootPart.CFrame * CFrame.new(0.35, -2.8, -0.6)).p, Vector3.new(0, -2, 0))}, 
							{Ray = Ray.new((Character.HumanoidRootPart.CFrame * CFrame.new(0, -2.8, -0.6)).p, Vector3.new(0, -2, 0))},
							{Ray = Ray.new((Character.HumanoidRootPart.CFrame * CFrame.new(0.35, -2.8, -0.6)).p, Vector3.new(0, -2, 0))}, 
							
							{Ray = Ray.new((Character.HumanoidRootPart.CFrame * CFrame.new(0.5, -0.8, 0)).p, Character.HumanoidRootPart.CFrame.lookVector), State = Enum.HumanoidStateType.Climbing},
							{Ray = Ray.new((Character.HumanoidRootPart.CFrame * CFrame.new(-0.5, -0.8, 0)).p, Character.HumanoidRootPart.CFrame.lookVector), State = Enum.HumanoidStateType.Climbing},
							{Ray = Ray.new((Character.HumanoidRootPart.CFrame * CFrame.new(0.5, -1.3, 0)).p, Character.HumanoidRootPart.CFrame.lookVector), State = Enum.HumanoidStateType.Climbing},
							{Ray = Ray.new((Character.HumanoidRootPart.CFrame * CFrame.new(-0.5, -1.3, 0)).p, Character.HumanoidRootPart.CFrame.lookVector), State = Enum.HumanoidStateType.Climbing}
									
					}) do
		
			local ray = check.Ray
			local part, _ = workspace:FindPartOnRayWithIgnoreList(ray, {Character})
			local op = part
			part = part and findHighestParent(part)
			
			if part and (not check.State or Humanoid:GetState() == check.State) then
				if part == targParent then
					attemptingToSurf = true
				else
					for _, connectedPart in pairs(op:GetConnectedParts(true)) do

						if connectedPart == targetObject--[[targParent]] then
							attemptingToSurf = true
							break
						end
					end
				end

				if attemptingToSurf then
					break
				end
			end
		end
		
		
		
		
		
		local falling = Humanoid:GetState() == Enum.HumanoidStateType.Freefall or Humanoid:GetState() == Enum.HumanoidStateType.FallingDown--not part1 and not part2
		
		
		if attemptingToSurf then
			dragIsFailing = 0
		elseif falling then
			dragIsFailing = 0
		elseif (dragPart.Position - desiredPos).magnitude > 5 then
			dragIsFailing = 0
		else
			dragIsFailing = 0
		end
		if dragIsFailing > 16 then
			break
		end
		
		
		if dragTime % 10 == 0 and targParent.Parent:FindFirstChild("BedInfo") and targParent.Parent:FindFirstChild("Main") then
			game.Players.LocalPlayer.PlayerGui.ItemDraggingGUI.Parent.Scripts.VehicleControl.SetVehicleOwnership:Fire(targParent.Parent.Main)
		end
		
		clientIsDragging:FireServer(targParent.Parent)
		
		wait()
		dragTime = 0
	end
	
	carryAnimationTrack:Stop()
	
	endDrag()
end


function findHighestParent(child)
	if not child or not child.Parent or child.Parent == workspace then
		return nil
	end
	
	local ret = child.Parent:FindFirstChild("Owner") and child
	return findHighestParent(child.Parent) or ret
end



function clickEnded()
	button1Down = false
end

function holdDistanceChanged()
	dragRange = dragRangeMax--[[_G.dragRangeMin + (1 - dist) * (dragRangeMax - _G.dragRangeMin)]]
end


function canDrag(targetObject)
	
	
	if not (targetObject and not targetObject.Anchored and targetObject.Parent and Humanoid.Health > 0) then -- General conditions
		return false
	end
	
	if targetObject.Name == "LeafPart" then
		return false
	end
	
	local originTargetObject = targetObject
	targetObject = findHighestParent(targetObject) or targetObject
	
	bodyGyro.Parent = dragPart
	
	
	--[[if not (targetObject.Parent:FindFirstChild("Owner") or targetObject.Parent.Parent:FindFirstChild("Owner")) then
		return otherDraggable(targetObject, originTargetObject)
	end]]

	if targetObject.Parent:FindFirstChild("Owner") or targetObject.Parent.Parent:FindFirstChild("Owner") then
		return true
	end
	
	if targetObject.Parent:FindFirstChild("TreeClass") then -- Wood class
		return true
	end
	if targetObject.Parent:FindFirstChild("BoxItemName") then -- Shop items
		return true
	end
	if targetObject.Parent:FindFirstChild("PurchasedBoxItemName") then -- Purchased box items
		return true
	end
	if targetObject.Parent:FindFirstChild("Handle") then -- Tool items
		return true
	end
	
	return otherDraggable(targetObject, originTargetObject)
end

function otherDraggable(targetObject, originTargetObject)
	local draggable = targetObject and targetObject.Parent and targetObject.Parent:FindFirstChild("DraggableItem") or originTargetObject and originTargetObject.Parent and originTargetObject.Parent:FindFirstChild("DraggableItem")
	if draggable then -- Other stuff
		if draggable:FindFirstChild("NoRotate") then
			bodyGyro.Parent  = nil
		end
		return true
	end
end

function initializeDrag(targetObject,mouseHit)
	draggingPart = true
	mouse.TargetFilter = targetObject and findHighestParent(targetObject) and findHighestParent(targetObject).Parent or targetObject

	dragPart.CFrame = CFrame.new(mouseHit, camera.CoordinateFrame.p)

	weld.Part0 = dragPart
	weld.Part1 = targetObject
	weld.C0 =  CFrame.new(mouseHit,camera.CoordinateFrame.p):inverse() * targetObject.CFrame
	weld.Parent = dragPart
	
	dragPart.Parent = workspace
end

function endDrag()
	mouse.TargetFilter = nil
	dragPart.Parent = nil
	draggingPart = false
end

--------------------------------[[ Do Prompt ]]------------------------------------


local dragGuiState = ""
function interactLoop()
	while true do
		wait()
		
		local newState = ""
		
		local mouseHit = game.Players.LocalPlayer:GetMouse().Hit.p
		local targetObject = game.Players.LocalPlayer:GetMouse().Target
		
		
		if draggingPart then
			newState = "Dragging"
		elseif canDrag(targetObject) and not button1Down and (mouseHit - Character.Head.Position).magnitude < dragRangeMax then
			newState = "Mouseover"
		end
		
		if true then-- not (newState == dragGuiState) then
			dragGuiState = newState
			setPlatformControls()
			
			if dragGuiState == "" then
				game.Players.LocalPlayer.PlayerGui.ItemDraggingGUI.CanDrag.Visible = false
				game.Players.LocalPlayer.PlayerGui.ItemDraggingGUI.CanRotate.Visible = false
			elseif dragGuiState ==  "Mouseover" then
				game.Players.LocalPlayer.PlayerGui.ItemDraggingGUI.CanDrag.Visible = true
				game.Players.LocalPlayer.PlayerGui.ItemDraggingGUI.CanRotate.Visible = false
			elseif dragGuiState ==  "Dragging" then
				game.Players.LocalPlayer.PlayerGui.ItemDraggingGUI.CanDrag.Visible = false
				game.Players.LocalPlayer.PlayerGui.ItemDraggingGUI.CanRotate.Visible = not (bodyGyro.Parent == nil) and (not player:FindFirstChild("IsChatting") or player.IsChatting.Value < 1)
			end
		end
		
	end
end


--------------------------------[[ Drag Moving ]]------------------------------------


function moveDrag(pos)
	bodyPosition.position = pos
end
local rotateSpeedReduce = 0.036

local lastRotateTick
function crotate(amount, speed)

	if not draggingPart then
		if not player:FindFirstChild("IsChatting") or player.IsChatting.Value < 2 then
			Humanoid.WalkSpeed = walkSpeed
		end
		return
	end
	
	if Humanoid.WalkSpeed > 1 then
		walkSpeed = Humanoid.WalkSpeed
		Humanoid.WalkSpeed = 0
	end
	
	lastRotateTick = tick()
	local thisRotateTick = lastRotateTick
	
	while draggingPart and amount.magnitude > 0 and lastRotateTick == thisRotateTick do
		rotateCFrame = CFrame.Angles(0, -amount.X * rotateSpeedReduce, 0) * CFrame.Angles(amount.Y * rotateSpeedReduce, 0, 0) * rotateCFrame
		wait()
	end
	
	if amount.magnitude == 0 then
		if not player:FindFirstChild("IsChatting") or  player.IsChatting.Value < 2 then
			Humanoid.WalkSpeed = walkSpeed
		end
	end
end

--------------------------------[[ User Input ]]------------------------------------

wait(1)

carryAnimationTrack = Humanoid:LoadAnimation(game.Players.LocalPlayer.PlayerGui.ItemDraggingGUI.Dragger:WaitForChild("CarryItem"))

--input = require(game.Players.LocalPlayer.PlayerGui.ItemDraggingGUI.Parent:WaitForChild("Scripts"):WaitForChild("UserInput"))

game.Players.LocalPlayer:GetMouse().Button1Down:connect(function()
	click()
	holdDistanceChanged()
end)
game.Players.LocalPlayer:GetMouse().Button1Up:connect(function()
	clickEnded()
end)
--input.ClickBegan(click, holdDistanceChanged)
--input.ClickEnded(clickEnded)

--input.Rotate(crotate)


function setPlatformControls()
		game.Players.LocalPlayer.PlayerGui.ItemDraggingGUI.CanDrag.PlatformButton.Image = game.Players.LocalPlayer.PlayerGui.ItemDraggingGUI.CanDrag.PlatformButton.PC.Value
		game.Players.LocalPlayer.PlayerGui.ItemDraggingGUI.CanDrag.PlatformButton.KeyLabel.Text = "CLICK"
		game.Players.LocalPlayer.PlayerGui.ItemDraggingGUI.CanRotate.PlatformButton.Image = game.Players.LocalPlayer.PlayerGui.ItemDraggingGUI.CanRotate.PlatformButton.PC.Value
		game.Players.LocalPlayer.PlayerGui.ItemDraggingGUI.CanRotate.PlatformButton.KeyLabel.Text = "SHIFT + WASD"
end


interactLoop()
end)
-- Golden Axe
GoldAxe.MouseButton1Down:connect(function()

local mouse1 = game:GetService("Players").LocalPlayer:GetMouse()
mouse1.Button1Down:connect(function(key)
       Pressing=false
end)

function GetAxe()
if game.Players.LocalPlayer.Character:FindFirstChild("Tool") then
return game.Players.LocalPlayer.Character:FindFirstChild("Tool")
end
end

local HitPoints={
['GoldAxe']= 50;
['BasicHatchet']= 0.2;
['Axe1']= 0.55;
['Axe2']= 0.93;
['AxeAlphaTesters']= 1.5;
['Rukiryaxe']= 1.68;
['Axe3']= 1.45;
['AxeBetaTesters']= 1.45;
['FireAxe']= 0.6;
['SilverAxe']= 1.6;
['EndTimesAxe']= 10000000;
['AxeChicken']= 0.1;
['CandyCaneAxe']= 0;
}

local Pressing = false

local mouse1 = game:GetService("Players").LocalPlayer:GetMouse()
mouse1.Button1Down:connect(function(key)
       Pressing=true
       poop(GetAxe())
end)

local mouse1 = game:GetService("Players").LocalPlayer:GetMouse()
mouse1.Button1Down:connect(function(key)
       Pressing=false
end)

function cut(Height,Tool)
local Tree=game.Players.LocalPlayer:GetMouse().Target
game.ReplicatedStorage.Interaction.RemoteProxy:FireServer(Tree.Parent.CutEvent,{
["cuttingClass"] = "Axe",
["cooldown"] = 0,
["hitPoints"] = HitPoints[Tool.ToolName.Value],
["sectionId"] = 1,
["tool"] = Tool,
["faceVector"] = Vector3.new(-1,0,0),
["height"] = Height})
end

function poop(Tool)
   while Pressing do
       for i=1,100 do
wait()
cut(_G.SIZE,Tool)
cut(1,Tool)
end
   end
end
end)
-- Leaked Items
LeakedItems.MouseButton1Down:connect(function() 
game.ReplicatedStorage.Purchasables:Clone().Parent = game.Workspace.PlayerModels
end)

-- Ctrl + Click TP
TeleportTool.MouseButton1Down:connect(function() 
local Plr = game:GetService("Players").LocalPlayer
local Mouse = Plr:GetMouse()

Mouse.Button1Down:connect(function()
if not game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftControl) then return end
if not Mouse.Target then return end
Plr.Character:MoveTo(Mouse.Hit.p)
end)
end)
-- Grey Wood
GreyWood.MouseButton1Down:connect(function()
	for i,v in next,workspace.PlayerModels:GetChildren() do
	    if v:FindFirstChild("Type") then
	        if v.Type.Value == "Blueprint" then
	            v.Type.Value = "Structure"
	        end
	    end
	end
end)
-- Teleport Gifts
TeleportGifts.MouseButton1Down:connect(function()
	for i,v in next,workspace.PlayerModels:GetChildren() do
    if v:FindFirstChild("Main") and v.Owner.Value == game.Players.LocalPlayer then
    for q,p in pairs(v:GetChildren()) do       
        if p.Name:lower():match("box") or p.Name == "DraggableItem" then
            wait()
                v.PrimaryPart = v.Main
                game.ReplicatedStorage.Interaction.Verify:FireServer('Item owned by player',v)
                   v:SetPrimaryPartCFrame(game.Players.LocalPlayer.Character.Head.CFrame)
                 game.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(v)
        end
    end
    end
end
end)	
end)
Speed.Name = "Speed"
Speed.Parent = MainFrame
Speed.BackgroundColor3 = Color3.new(0, 0, 0)
Speed.BorderColor3 = Color3.new(0, 1, 0)
Speed.BorderSizePixel = 5
Speed.Position = UDim2.new(0.375, 0, 0.211009175, 0)
Speed.Size = UDim2.new(0, 95, 0, 38)
Speed.Font = Enum.Font.SciFi
Speed.Text = "Speed"
Speed.TextColor3 = Color3.new(0, 1, 0)
Speed.TextScaled = true
Speed.TextSize = 14
Speed.TextWrapped = true
Speed.MouseButton1Click:connect(function()while wait()do
game.Players.LocalPlayer.Character.Humanoid.WalkSpeed=200 
end 
end
)
Jpower.Name = "Jpower"
Jpower.Parent = MainFrame
Jpower.BackgroundColor3 = Color3.new(0, 0, 0)
Jpower.BorderColor3 = Color3.new(0, 1, 0)
Jpower.BorderSizePixel = 5
Jpower.Position = UDim2.new(0.5625, 0, 0.844036698, 0)
Jpower.Size = UDim2.new(0, 92, 0, 29)
Jpower.Font = Enum.Font.SciFi
Jpower.Text = "Jpower"
Jpower.TextColor3 = Color3.new(0, 1, 0)
Jpower.TextScaled = true
Jpower.TextSize = 14
Jpower.TextWrapped = true
Jpower.MouseButton1Click:connect(function()while wait()do
game.Players.LocalPlayer.Character.Humanoid.JumpPower=100 end end)

GoldAxe.Name = "GoldAxe"
GoldAxe.Parent = MainFrame
GoldAxe.BackgroundColor3 = Color3.new(0, 0, 0)
GoldAxe.BorderColor3 = Color3.new(0, 1, 0)
GoldAxe.BorderSizePixel = 5
GoldAxe.Position = UDim2.new(0.375, 0, 0.646789014, 0)
GoldAxe.Size = UDim2.new(0, 95, 0, 34)
GoldAxe.Font = Enum.Font.SciFi
GoldAxe.Text = "GoldAxe"
GoldAxe.TextColor3 = Color3.new(0, 1, 0)
GoldAxe.TextScaled = true
GoldAxe.TextSize = 14
GoldAxe.TextWrapped = true
GoldAxe.MouseButton1Down:connect(function()
-- Objects

local InfoGUI = Instance.new("ScreenGui")
local TopBar = Instance.new("Frame")
local MainFrame = Instance.new("Frame")
local Info = Instance.new("TextLabel")
local OkayB = Instance.new("TextButton")
local Credits = Instance.new("TextLabel")

-- Properties

InfoGUI.Name = "InfoGUI"
InfoGUI.Parent = game.Players.LocalPlayer.PlayerGui

TopBar.Name = "TopBar"
TopBar.Parent = InfoGUI
TopBar.BackgroundColor3 = Color3.new(0.266667, 0.247059, 0.313726)
TopBar.BorderSizePixel = 0
TopBar.Position = UDim2.new(0.5, -173, 0.5, -74)
TopBar.Size = UDim2.new(0, 347, 0, 34)

MainFrame.Name = "MainFrame"
MainFrame.Parent = TopBar
MainFrame.BackgroundColor3 = Color3.new(0.356863, 0.333333, 0.423529)
MainFrame.BorderSizePixel = 0
MainFrame.Position = UDim2.new(0, 0, 1, 0)
MainFrame.Size = UDim2.new(0, 347, 0, 114)

Info.Name = "Info"
Info.Parent = MainFrame
Info.BackgroundColor3 = Color3.new(0.443137, 0.415686, 0.52549)
Info.BorderSizePixel = 0
Info.Size = UDim2.new(0, 347, 0, 78)
Info.Font = Enum.Font.SourceSansLight
Info.Text = "All you have to do to make this work, is get any axe and spam click on a tree a few times, ANY DISTANCE!"
Info.TextColor3 = Color3.new(1, 1, 1)
Info.TextScaled = true
Info.TextSize = 14
Info.TextWrapped = true

OkayB.Name = "OkayB"
OkayB.Parent = MainFrame
OkayB.BackgroundColor3 = Color3.new(0.443137, 0.415686, 0.52549)
OkayB.BorderSizePixel = 0
OkayB.Position = UDim2.new(0.268000007, 0, 0.709999979, 0)
OkayB.Size = UDim2.new(0, 161, 0, 29)
OkayB.Font = Enum.Font.SourceSansLight
OkayB.Text = "Alright"
OkayB.TextColor3 = Color3.new(1, 1, 1)
OkayB.TextScaled = true
OkayB.TextSize = 14
OkayB.TextWrapped = true

Credits.Name = "Credits"
Credits.Parent = MainFrame
Credits.BackgroundColor3 = Color3.new(0.443137, 0.415686, 0.52549)
Credits.BackgroundTransparency = 1
Credits.BorderSizePixel = 0
Credits.Position = UDim2.new(-0.0028818443, 0, 1.11403513, 0)
Credits.Size = UDim2.new(0, 347, 0, 78)
Credits.Font = Enum.Font.SourceSansLight
Credits.Text = "GUI made by HowToBasic666/Hoofer"
Credits.TextColor3 = Color3.new(1, 1, 1)
Credits.TextScaled = true
Credits.TextSize = 14
Credits.TextWrapped = true

OkayB.MouseButton1Click:connect(function()
	InfoGUI.Enabled = false
end)

local mouse1 = game:GetService("Players").LocalPlayer:GetMouse()
mouse1.Button1Down:connect(function(key)
       Pressing=false
end)

function GetAxe()
if game.Players.LocalPlayer.Character:FindFirstChild("Tool") then
return game.Players.LocalPlayer.Character:FindFirstChild("Tool")
end
end

local HitPoints={
['GoldAxe']= 50;
['BasicHatchet']= 0.2;
['Axe1']= 0.55;
['Axe2']= 0.93;
['AxeAlphaTesters']= 1.5;
['Rukiryaxe']= 1.68;
['Axe3']= 1.45;
['AxeBetaTesters']= 1.45;
['FireAxe']= 0.6;
['SilverAxe']= 1.6;
['EndTimesAxe']= 10000000;
['AxeChicken']= 0.1;
['CandyCaneAxe']= 0;
}

local Pressing = false

local mouse1 = game:GetService("Players").LocalPlayer:GetMouse()
mouse1.Button1Down:connect(function(key)
       Pressing=true
       poop(GetAxe())
end)

local mouse1 = game:GetService("Players").LocalPlayer:GetMouse()
mouse1.Button1Down:connect(function(key)
       Pressing=false
end)

function cut(Height,Tool)
local Tree=game.Players.LocalPlayer:GetMouse().Target
game.ReplicatedStorage.Interaction.RemoteProxy:FireServer(Tree.Parent.CutEvent,{
["cuttingClass"] = "Axe",
["cooldown"] = 0,
["hitPoints"] = HitPoints[Tool.ToolName.Value],
["sectionId"] = 1,
["tool"] = Tool,
["faceVector"] = Vector3.new(-1,0,0),
["height"] = Height})
end

function poop(Tool)
   while Pressing do
       for i=1,100 do
wait()
cut(_G.SIZE,Tool)
cut(1,Tool)
end
   end
end	
end)
TextLabel.Parent = MainFrame
TextLabel.BackgroundColor3 = Color3.new(0, 0, 0)
TextLabel.BorderColor3 = Color3.new(0, 1, 0)
TextLabel.BorderSizePixel = 5
TextLabel.Position = UDim2.new(0.18928571, 0, 0, 0)
TextLabel.Size = UDim2.new(0, 448, 0, 39)
TextLabel.Font = Enum.Font.SciFi
TextLabel.Text = "LUMBER TYCOON 2 GUI"
TextLabel.TextColor3 = Color3.new(0, 1, 0)
TextLabel.TextScaled = true
TextLabel.TextSize = 14
TextLabel.TextWrapped = true
TextLabel.TextXAlignment = Enum.TextXAlignment.Left

TextLabel_2.Parent = MainFrame
TextLabel_2.BackgroundColor3 = Color3.new(0, 0, 0)
TextLabel_2.BorderColor3 = Color3.new(0, 1, 0)
TextLabel_2.BorderSizePixel = 5
TextLabel_2.Position = UDim2.new(0.744642854, 0, 0.637614667, 0)
TextLabel_2.Size = UDim2.new(0, 94, 0, 74)
TextLabel_2.Font = Enum.Font.SciFi
TextLabel_2.Text = "Gui Made By MrIpop "
TextLabel_2.TextColor3 = Color3.new(0, 1, 0)
TextLabel_2.TextScaled = true
TextLabel_2.TextSize = 14
TextLabel_2.TextWrapped = true

LT2GUD.Name = "LT2GUD"
LT2GUD.Parent = MainFrame
LT2GUD.BackgroundColor3 = Color3.new(0, 0, 0)
LT2GUD.BorderColor3 = Color3.new(0, 1, 0)
LT2GUD.BorderSizePixel = 5
LT2GUD.Position = UDim2.new(0.744642854, 0, 0.403669715, 0)
LT2GUD.Size = UDim2.new(0, 94, 0, 41)
LT2GUD.Font = Enum.Font.SciFi
LT2GUD.Text = "LT2GUD"
LT2GUD.TextColor3 = Color3.new(0, 1, 0)
LT2GUD.TextScaled = true
LT2GUD.TextSize = 14
LT2GUD.TextWrapped = true
LT2GUD.MouseButton1Down:connect(function()
local LT2 = Instance.new("ScreenGui")
local MainFrame = Instance.new("Frame")
local Close = Instance.new("TextButton")
local DupeStatus = Instance.new("TextLabel")
local Dupe = Instance.new("TextButton")
local SettingsFrame = Instance.new("Frame")
local WalkspeedLabel = Instance.new("TextLabel")
local JumpPowerLabel = Instance.new("TextLabel")
local WalkSpeed = Instance.new("TextBox")
local JumpPower = Instance.new("TextBox")
local Settings = Instance.new("TextButton")
local Greywood = Instance.new("TextButton")
local Players = Instance.new("TextButton")
local SellPlanks = Instance.new("TextButton")
local SellWood = Instance.new("TextButton")
local Teleport = Instance.new("TextButton")
local TpBox = Instance.new("TextButton")
local TpPlank = Instance.new("TextButton")
local TpWood = Instance.new("TextButton")
local PlankFrame = Instance.new("Frame")
local ProcessedWoodList = Instance.new("ScrollingFrame")
local TpAllPlanks = Instance.new("TextButton")
local PlayersFrame = Instance.new("Frame")
local Player1 = Instance.new("TextButton")
local Player2 = Instance.new("TextButton")
local Player3 = Instance.new("TextButton")
local Player4 = Instance.new("TextButton")
local Player5 = Instance.new("TextButton")
local Player6 = Instance.new("TextButton")
local PlayerTp = Instance.new("TextButton")
local TpBase = Instance.new("TextButton")
local PlayerSelect = Instance.new("TextLabel")
local PurchasedFrame = Instance.new("Frame")
local LastPurchasedList = Instance.new("ScrollingFrame")
local WaypointFrame = Instance.new("Frame")
local Waypoints = Instance.new("ScrollingFrame")
local Stranger = Instance.new("TextButton")
local BobsShack = Instance.new("TextButton")
local PlotTp = Instance.new("TextButton")
local BoxedCars = Instance.new("TextButton")
local Cave = Instance.new("TextButton")
local FancyFurnishings = Instance.new("TextButton")
local FineArtsShop = Instance.new("TextButton")
local LandStore = Instance.new("TextButton")
local LinksLogic = Instance.new("TextButton")
local PalmIsland = Instance.new("TextButton")
local SpawnPoint = Instance.new("TextButton")
local Swamp = Instance.new("TextButton")
local Volcano = Instance.new("TextButton")
local WoodRUs = Instance.new("TextButton")

LT2.Name = "LT2"
LT2.Parent = game.CoreGui

MainFrame.Name = "MainFrame"
MainFrame.Parent = LT2
MainFrame.BackgroundColor3 = Color3.new(0.203922, 0.203922, 0.203922)
MainFrame.BackgroundTransparency = 1
MainFrame.BorderSizePixel = 0
MainFrame.Position = UDim2.new(0.5, -535, 0, -33)
MainFrame.Size = UDim2.new(0, 955, 0, 30)

Close.Name = "Close"
Close.Parent = MainFrame
Close.BackgroundColor3 = Color3.new(0.129412, 0.129412, 0.129412)
Close.BorderColor3 = Color3.new(0, 0, 0)
Close.BorderSizePixel = 2
Close.Position = UDim2.new(0, 5, 0, 5)
Close.Size = UDim2.new(0, 20, 0, 20)
Close.Font = Enum.Font.Fantasy
Close.FontSize = Enum.FontSize.Size18
Close.Text = "X"
Close.TextColor3 = Color3.new(1, 0, 0)
Close.TextSize = 16
Close.TextWrapped = true

DupeStatus.Name = "DupeStatus"
DupeStatus.Parent = MainFrame
DupeStatus.BackgroundColor3 = Color3.new(0.203922, 0.203922, 0.203922)
DupeStatus.BackgroundTransparency = 1
DupeStatus.BorderColor3 = Color3.new(0, 0, 0)
DupeStatus.BorderSizePixel = 2
DupeStatus.Position = UDim2.new(0, 920, 0, 5)
DupeStatus.Size = UDim2.new(0, 30, 0, 20)
DupeStatus.ZIndex = 2
DupeStatus.Font = Enum.Font.Code
DupeStatus.FontSize = Enum.FontSize.Size18
DupeStatus.Text = "OFF"
DupeStatus.TextColor3 = Color3.new(1, 0, 0)
DupeStatus.TextSize = 16

Dupe.Name = "Dupe"
Dupe.Parent = MainFrame
Dupe.BackgroundColor3 = Color3.new(0.129412, 0.129412, 0.129412)
Dupe.BorderColor3 = Color3.new(0, 0, 0)
Dupe.BorderSizePixel = 2
Dupe.Position = UDim2.new(0, 865, 0, 5)
Dupe.Size = UDim2.new(0, 85, 0, 20)
Dupe.Font = Enum.Font.Fantasy
Dupe.FontSize = Enum.FontSize.Size18
Dupe.Text = "DUPE :         "
Dupe.TextColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
Dupe.TextSize = 15
Dupe.TextStrokeColor3 = Color3.new(1, 1, 1)
Dupe.TextWrapped = true

SettingsFrame.Name = "SettingsFrame"
SettingsFrame.Parent = MainFrame
SettingsFrame.BackgroundColor3 = Color3.new(0.27451, 0.27451, 0.27451)
SettingsFrame.Position = UDim2.new(0, 750, 0, 35)
SettingsFrame.Size = UDim2.new(0, 135, 0, 60)
SettingsFrame.Visible = false

WalkspeedLabel.Name = "WalkspeedLabel"
WalkspeedLabel.Parent = SettingsFrame
WalkspeedLabel.BackgroundColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
WalkspeedLabel.BorderColor3 = Color3.new(0, 0, 0)
WalkspeedLabel.Position = UDim2.new(0, 5, 0, 5)
WalkspeedLabel.Size = UDim2.new(0, 90, 0, 20)
WalkspeedLabel.Font = Enum.Font.Fantasy
WalkspeedLabel.FontSize = Enum.FontSize.Size14
WalkspeedLabel.Text = "Walkspeed"
WalkspeedLabel.TextColor3 = Color3.new(0, 0, 0)
WalkspeedLabel.TextSize = 14

JumpPowerLabel.Name = "JumpPowerLabel"
JumpPowerLabel.Parent = SettingsFrame
JumpPowerLabel.BackgroundColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
JumpPowerLabel.BorderColor3 = Color3.new(0, 0, 0)
JumpPowerLabel.Position = UDim2.new(0, 5, 0, 35)
JumpPowerLabel.Size = UDim2.new(0, 90, 0, 20)
JumpPowerLabel.Font = Enum.Font.Fantasy
JumpPowerLabel.FontSize = Enum.FontSize.Size14
JumpPowerLabel.Text = "Jump Power"
JumpPowerLabel.TextColor3 = Color3.new(0, 0, 0)
JumpPowerLabel.TextSize = 14

WalkSpeed.Name = "WalkSpeed"
WalkSpeed.Parent = SettingsFrame
WalkSpeed.BackgroundColor3 = Color3.new(0, 0, 0)
WalkSpeed.BorderColor3 = Color3.new(0, 0, 0)
WalkSpeed.Position = UDim2.new(0, 95, 0, 5)
WalkSpeed.Size = UDim2.new(0, 35, 0, 20)
WalkSpeed.Font = Enum.Font.Fantasy
WalkSpeed.FontSize = Enum.FontSize.Size18
WalkSpeed.Text = "16"
WalkSpeed.TextColor3 = Color3.new(1, 1, 1)
WalkSpeed.TextSize = 16

JumpPower.Name = "JumpPower"
JumpPower.Parent = SettingsFrame
JumpPower.BackgroundColor3 = Color3.new(0, 0, 0)
JumpPower.BorderColor3 = Color3.new(0, 0, 0)
JumpPower.Position = UDim2.new(0, 95, 0, 35)
JumpPower.Size = UDim2.new(0, 35, 0, 20)
JumpPower.Font = Enum.Font.Fantasy
JumpPower.FontSize = Enum.FontSize.Size18
JumpPower.Text = "50"
JumpPower.TextColor3 = Color3.new(1, 1, 1)
JumpPower.TextSize = 16

Settings.Name = "Settings"
Settings.Parent = MainFrame
Settings.BackgroundColor3 = Color3.new(0.129412, 0.129412, 0.129412)
Settings.BorderColor3 = Color3.new(0, 0, 0)
Settings.BorderSizePixel = 2
Settings.Position = UDim2.new(0, 770, 0, 5)
Settings.Size = UDim2.new(0, 90, 0, 20)
Settings.Font = Enum.Font.Fantasy
Settings.FontSize = Enum.FontSize.Size18
Settings.Text = "SETTINGS"
Settings.TextColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
Settings.TextSize = 15

Greywood.Name = "Greywood"
Greywood.Parent = MainFrame
Greywood.BackgroundColor3 = Color3.new(0.129412, 0.129412, 0.129412)
Greywood.BorderColor3 = Color3.new(0, 0, 0)
Greywood.BorderSizePixel = 2
Greywood.Position = UDim2.new(0, 420, 0, 5)
Greywood.Size = UDim2.new(0, 90, 0, 20)
Greywood.Font = Enum.Font.Fantasy
Greywood.FontSize = Enum.FontSize.Size18
Greywood.Text = "GREYWOOD"
Greywood.TextColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
Greywood.TextSize = 15

Players.Name = "Players"
Players.Parent = MainFrame
Players.BackgroundColor3 = Color3.new(0.129412, 0.129412, 0.129412)
Players.BorderColor3 = Color3.new(0, 0, 0)
Players.BorderSizePixel = 2
Players.Position = UDim2.new(0, 30, 0, 5)
Players.Size = UDim2.new(0, 105, 0, 20)
Players.Font = Enum.Font.Fantasy
Players.FontSize = Enum.FontSize.Size18
Players.Text = "TP TO PLAYERS"
Players.TextColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
Players.TextSize = 15

SellPlanks.Name = "SellPlanks"
SellPlanks.Parent = MainFrame
SellPlanks.BackgroundColor3 = Color3.new(0.129412, 0.129412, 0.129412)
SellPlanks.BorderColor3 = Color3.new(0, 0, 0)
SellPlanks.BorderSizePixel = 2
SellPlanks.Position = UDim2.new(0, 225, 0, 5)
SellPlanks.Size = UDim2.new(0, 95, 0, 20)
SellPlanks.Font = Enum.Font.Fantasy
SellPlanks.FontSize = Enum.FontSize.Size18
SellPlanks.Text = "SELL PLANKS"
SellPlanks.TextColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
SellPlanks.TextSize = 15

SellWood.Name = "SellWood"
SellWood.Parent = MainFrame
SellWood.BackgroundColor3 = Color3.new(0.129412, 0.129412, 0.129412)
SellWood.BorderColor3 = Color3.new(0, 0, 0)
SellWood.BorderSizePixel = 2
SellWood.Position = UDim2.new(0, 675, 0, 5)
SellWood.Size = UDim2.new(0, 90, 0, 20)
SellWood.Font = Enum.Font.Fantasy
SellWood.FontSize = Enum.FontSize.Size18
SellWood.Text = "SELL WOOD"
SellWood.TextColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
SellWood.TextSize = 15

Teleport.Name = "Teleport"
Teleport.Parent = MainFrame
Teleport.BackgroundColor3 = Color3.new(0.129412, 0.129412, 0.129412)
Teleport.BorderColor3 = Color3.new(0, 0, 0)
Teleport.BorderSizePixel = 2
Teleport.Position = UDim2.new(0, 325, 0, 5)
Teleport.Size = UDim2.new(0, 90, 0, 20)
Teleport.Font = Enum.Font.Fantasy
Teleport.FontSize = Enum.FontSize.Size18
Teleport.Text = "WAYPOINTS"
Teleport.TextColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
Teleport.TextSize = 15

TpBox.Name = "TpBox"
TpBox.Parent = MainFrame
TpBox.BackgroundColor3 = Color3.new(0.129412, 0.129412, 0.129412)
TpBox.BorderColor3 = Color3.new(0, 0, 0)
TpBox.BorderSizePixel = 2
TpBox.Position = UDim2.new(0, 515, 0, 5)
TpBox.Size = UDim2.new(0, 75, 0, 20)
TpBox.Font = Enum.Font.Fantasy
TpBox.FontSize = Enum.FontSize.Size18
TpBox.Text = "TP BOXES"
TpBox.TextColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
TpBox.TextSize = 15

TpPlank.Name = "TpPlank"
TpPlank.Parent = MainFrame
TpPlank.BackgroundColor3 = Color3.new(0.129412, 0.129412, 0.129412)
TpPlank.BorderColor3 = Color3.new(0, 0, 0)
TpPlank.BorderSizePixel = 2
TpPlank.Position = UDim2.new(0, 140, 0, 5)
TpPlank.Size = UDim2.new(0, 80, 0, 20)
TpPlank.Font = Enum.Font.Fantasy
TpPlank.FontSize = Enum.FontSize.Size18
TpPlank.Text = "TP PLANKS"
TpPlank.TextColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
TpPlank.TextSize = 15
TpPlank.TextStrokeColor3 = Color3.new(1, 1, 1)

TpWood.Name = "TpWood"
TpWood.Parent = MainFrame
TpWood.BackgroundColor3 = Color3.new(0.129412, 0.129412, 0.129412)
TpWood.BorderColor3 = Color3.new(0, 0, 0)
TpWood.BorderSizePixel = 2
TpWood.Position = UDim2.new(0, 595, 0, 5)
TpWood.Size = UDim2.new(0, 75, 0, 20)
TpWood.Font = Enum.Font.Fantasy
TpWood.FontSize = Enum.FontSize.Size18
TpWood.Text = "TP WOOD"
TpWood.TextColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
TpWood.TextSize = 15

PlankFrame.Name = "PlankFrame"
PlankFrame.Parent = MainFrame
PlankFrame.BackgroundColor3 = Color3.new(0.27451, 0.27451, 0.27451)
PlankFrame.BorderColor3 = Color3.new(0, 0, 0)
PlankFrame.Position = UDim2.new(0, 100, 0, 55)
PlankFrame.Size = UDim2.new(0, 165, 0, 205)
PlankFrame.Visible = false

ProcessedWoodList.Name = "ProcessedWoodList"
ProcessedWoodList.Parent = PlankFrame
ProcessedWoodList.BackgroundColor3 = Color3.new(1, 1, 1)
ProcessedWoodList.BackgroundTransparency = 1
ProcessedWoodList.BorderColor3 = Color3.new(0, 0, 0)
ProcessedWoodList.Size = UDim2.new(0, 165, 0, 205)

TpAllPlanks.Name = "TpAllPlanks"
TpAllPlanks.Parent = PlankFrame
TpAllPlanks.BackgroundColor3 = Color3.new(0, 0, 0)
TpAllPlanks.BorderColor3 = Color3.new(0, 0, 0)
TpAllPlanks.Position = UDim2.new(0, 0, 0, -20)
TpAllPlanks.Size = UDim2.new(0, 165, 0, 20)
TpAllPlanks.Font = Enum.Font.Fantasy
TpAllPlanks.FontSize = Enum.FontSize.Size18
TpAllPlanks.Text = "TP ALL PLANKS"
TpAllPlanks.TextColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
TpAllPlanks.TextSize = 15

PlayersFrame.Name = "PlayersFrame"
PlayersFrame.Parent = MainFrame
PlayersFrame.BackgroundColor3 = Color3.new(0.27451, 0.27451, 0.27451)
PlayersFrame.BorderColor3 = Color3.new(0, 0, 0)
PlayersFrame.Position = UDim2.new(0, 0, 0, 35)
PlayersFrame.Size = UDim2.new(0, 165, 0, 225)
PlayersFrame.Visible = false

Player1.Name = "Player1"
Player1.Parent = PlayersFrame
Player1.BackgroundColor3 = Color3.new(0, 0, 0)
Player1.Position = UDim2.new(0, 5, 0, 5)
Player1.Size = UDim2.new(0, 155, 0, 20)
Player1.Font = Enum.Font.Fantasy
Player1.FontSize = Enum.FontSize.Size18
Player1.Text = ""
Player1.TextColor3 = Color3.new(1, 1, 1)
Player1.TextSize = 16
Player1.TextWrapped = true

Player2.Name = "Player2"
Player2.Parent = PlayersFrame
Player2.BackgroundColor3 = Color3.new(0, 0, 0)
Player2.Position = UDim2.new(0, 5, 0, 30)
Player2.Size = UDim2.new(0, 155, 0, 20)
Player2.Font = Enum.Font.Fantasy
Player2.FontSize = Enum.FontSize.Size18
Player2.Text = ""
Player2.TextColor3 = Color3.new(1, 1, 1)
Player2.TextSize = 16
Player2.TextWrapped = true

Player3.Name = "Player3"
Player3.Parent = PlayersFrame
Player3.BackgroundColor3 = Color3.new(0, 0, 0)
Player3.Position = UDim2.new(0, 5, 0, 55)
Player3.Size = UDim2.new(0, 155, 0, 20)
Player3.Font = Enum.Font.Fantasy
Player3.FontSize = Enum.FontSize.Size18
Player3.Text = ""
Player3.TextColor3 = Color3.new(1, 1, 1)
Player3.TextSize = 16
Player3.TextWrapped = true

Player4.Name = "Player4"
Player4.Parent = PlayersFrame
Player4.BackgroundColor3 = Color3.new(0, 0, 0)
Player4.Position = UDim2.new(0, 5, 0, 80)
Player4.Size = UDim2.new(0, 155, 0, 20)
Player4.Font = Enum.Font.Fantasy
Player4.FontSize = Enum.FontSize.Size18
Player4.Text = ""
Player4.TextColor3 = Color3.new(1, 1, 1)
Player4.TextSize = 16
Player4.TextWrapped = true

Player5.Name = "Player5"
Player5.Parent = PlayersFrame
Player5.BackgroundColor3 = Color3.new(0, 0, 0)
Player5.Position = UDim2.new(0, 5, 0, 105)
Player5.Size = UDim2.new(0, 155, 0, 20)
Player5.Font = Enum.Font.Fantasy
Player5.FontSize = Enum.FontSize.Size18
Player5.Text = ""
Player5.TextColor3 = Color3.new(1, 1, 1)
Player5.TextSize = 16
Player5.TextWrapped = true

Player6.Name = "Player6"
Player6.Parent = PlayersFrame
Player6.BackgroundColor3 = Color3.new(0, 0, 0)
Player6.Position = UDim2.new(0, 5, 0, 130)
Player6.Size = UDim2.new(0, 155, 0, 20)
Player6.Font = Enum.Font.Fantasy
Player6.FontSize = Enum.FontSize.Size18
Player6.Text = ""
Player6.TextColor3 = Color3.new(1, 1, 1)
Player6.TextSize = 16
Player6.TextWrapped = true

PlayerTp.Name = "PlayerTp"
PlayerTp.Parent = PlayersFrame
PlayerTp.BackgroundColor3 = Color3.new(0, 0, 0)
PlayerTp.Position = UDim2.new(0, 5, 0, 195)
PlayerTp.Size = UDim2.new(0, 80, 0, 20)
PlayerTp.Font = Enum.Font.Fantasy
PlayerTp.FontSize = Enum.FontSize.Size18
PlayerTp.Text = "Tp to Player"
PlayerTp.TextColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
PlayerTp.TextSize = 16

TpBase.Name = "TpBase"
TpBase.Parent = PlayersFrame
TpBase.BackgroundColor3 = Color3.new(0, 0, 0)
TpBase.Position = UDim2.new(0, 90, 0, 195)
TpBase.Size = UDim2.new(0, 70, 0, 20)
TpBase.Font = Enum.Font.Fantasy
TpBase.FontSize = Enum.FontSize.Size18
TpBase.Text = "Tp to Base"
TpBase.TextColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
TpBase.TextSize = 16

PlayerSelect.Name = "PlayerSelect"
PlayerSelect.Parent = PlayersFrame
PlayerSelect.BackgroundColor3 = Color3.new(0.6, 0.6, 0.6)
PlayerSelect.BorderColor3 = Color3.new(0, 0, 0)
PlayerSelect.Position = UDim2.new(0, 10, 0, 160)
PlayerSelect.Size = UDim2.new(0, 145, 0, 20)
PlayerSelect.Font = Enum.Font.Code
PlayerSelect.FontSize = Enum.FontSize.Size18
PlayerSelect.Text = "Select Player..."
PlayerSelect.TextColor3 = Color3.new(0, 0, 0)
PlayerSelect.TextSize = 16
PlayerSelect.TextWrapped = true

PurchasedFrame.Name = "PurchasedFrame"
PurchasedFrame.Parent = MainFrame
PurchasedFrame.BackgroundColor3 = Color3.new(0.27451, 0.27451, 0.27451)
PurchasedFrame.BorderColor3 = Color3.new(0, 0, 0)
PurchasedFrame.Position = UDim2.new(0, 450, 0, 35)
PurchasedFrame.Size = UDim2.new(0, 215, 0, 225)
PurchasedFrame.Visible = false

LastPurchasedList.Name = "LastPurchasedList"
LastPurchasedList.Parent = PurchasedFrame
LastPurchasedList.BackgroundColor3 = Color3.new(1, 1, 1)
LastPurchasedList.BackgroundTransparency = 1
LastPurchasedList.BorderColor3 = Color3.new(0, 0, 0)
LastPurchasedList.Size = UDim2.new(1, 1, 0, 225)

WaypointFrame.Name = "WaypointFrame"
WaypointFrame.Parent = MainFrame
WaypointFrame.BackgroundColor3 = Color3.new(0.27451, 0.27451, 0.27451)
WaypointFrame.BorderColor3 = Color3.new(0, 0, 0)
WaypointFrame.Position = UDim2.new(0, 295, 0, 35)
WaypointFrame.Size = UDim2.new(0, 150, 0, 225)
WaypointFrame.Visible = false

Waypoints.Name = "Waypoints"
Waypoints.Parent = WaypointFrame
Waypoints.BackgroundColor3 = Color3.new(0.27451, 0.27451, 0.27451)
Waypoints.BorderColor3 = Color3.new(0, 0, 0)
Waypoints.Size = UDim2.new(0, 150, 0, 225)
Waypoints.CanvasSize = UDim2.new(0, 0, 1.89999998, 0)

Stranger.Name = "Stranger"
Stranger.Parent = Waypoints
Stranger.BackgroundColor3 = Color3.new(0, 0, 0)
Stranger.Position = UDim2.new(0, 5, 0, 330)
Stranger.Size = UDim2.new(0, 125, 0, 20)
Stranger.Font = Enum.Font.Fantasy
Stranger.FontSize = Enum.FontSize.Size18
Stranger.Text = "Stranger"
Stranger.TextColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
Stranger.TextSize = 16

BobsShack.Name = "BobsShack"
BobsShack.Parent = Waypoints
BobsShack.BackgroundColor3 = Color3.new(0, 0, 0)
BobsShack.Position = UDim2.new(0, 5, 0, 155)
BobsShack.Size = UDim2.new(0, 125, 0, 20)
BobsShack.Font = Enum.Font.Fantasy
BobsShack.FontSize = Enum.FontSize.Size18
BobsShack.Text = "Bob's Shack"
BobsShack.TextColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
BobsShack.TextSize = 16

PlotTp.Name = "PlotTp"
PlotTp.Parent = Waypoints
PlotTp.BackgroundColor3 = Color3.new(0, 0, 0)
PlotTp.Position = UDim2.new(0, 5, 0, 30)
PlotTp.Size = UDim2.new(0, 125, 0, 20)
PlotTp.Font = Enum.Font.Fantasy
PlotTp.FontSize = Enum.FontSize.Size18
PlotTp.Text = "Tp to Plot"
PlotTp.TextColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
PlotTp.TextSize = 16

BoxedCars.Name = "BoxedCars"
BoxedCars.Parent = Waypoints
BoxedCars.BackgroundColor3 = Color3.new(0, 0, 0)
BoxedCars.Position = UDim2.new(0, 5, 0, 130)
BoxedCars.Size = UDim2.new(0, 125, 0, 20)
BoxedCars.Font = Enum.Font.Fantasy
BoxedCars.FontSize = Enum.FontSize.Size18
BoxedCars.Text = "Boxed Cars"
BoxedCars.TextColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
BoxedCars.TextSize = 16

Cave.Name = "Cave"
Cave.Parent = Waypoints
Cave.BackgroundColor3 = Color3.new(0, 0, 0)
Cave.Position = UDim2.new(0, 5, 0, 230)
Cave.Size = UDim2.new(0, 125, 0, 20)
Cave.Font = Enum.Font.Fantasy
Cave.FontSize = Enum.FontSize.Size18
Cave.Text = "Cave"
Cave.TextColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
Cave.TextSize = 16

FancyFurnishings.Name = "FancyFurnishings"
FancyFurnishings.Parent = Waypoints
FancyFurnishings.BackgroundColor3 = Color3.new(0, 0, 0)
FancyFurnishings.Position = UDim2.new(0, 5, 0, 80)
FancyFurnishings.Size = UDim2.new(0, 125, 0, 20)
FancyFurnishings.Font = Enum.Font.Fantasy
FancyFurnishings.FontSize = Enum.FontSize.Size18
FancyFurnishings.Text = "Fancy Furnishings"
FancyFurnishings.TextColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
FancyFurnishings.TextSize = 16

FineArtsShop.Name = "FineArtsShop"
FineArtsShop.Parent = Waypoints
FineArtsShop.BackgroundColor3 = Color3.new(0, 0, 0)
FineArtsShop.Position = UDim2.new(0, 5, 0, 180)
FineArtsShop.Size = UDim2.new(0, 125, 0, 20)
FineArtsShop.Font = Enum.Font.Fantasy
FineArtsShop.FontSize = Enum.FontSize.Size18
FineArtsShop.Text = "Fine Arts Shop"
FineArtsShop.TextColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
FineArtsShop.TextSize = 16

LandStore.Name = "LandStore"
LandStore.Parent = Waypoints
LandStore.BackgroundColor3 = Color3.new(0, 0, 0)
LandStore.Position = UDim2.new(0, 5, 0, 205)
LandStore.Size = UDim2.new(0, 125, 0, 20)
LandStore.Font = Enum.Font.Fantasy
LandStore.FontSize = Enum.FontSize.Size18
LandStore.Text = "Land Store"
LandStore.TextColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
LandStore.TextSize = 16

LinksLogic.Name = "LinksLogic"
LinksLogic.Parent = Waypoints
LinksLogic.BackgroundColor3 = Color3.new(0, 0, 0)
LinksLogic.Position = UDim2.new(0, 5, 0, 105)
LinksLogic.Size = UDim2.new(0, 125, 0, 20)
LinksLogic.Font = Enum.Font.Fantasy
LinksLogic.FontSize = Enum.FontSize.Size18
LinksLogic.Text = "Link's Logic"
LinksLogic.TextColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
LinksLogic.TextSize = 16

PalmIsland.Name = "PalmIsland"
PalmIsland.Parent = Waypoints
PalmIsland.BackgroundColor3 = Color3.new(0, 0, 0)
PalmIsland.Position = UDim2.new(0, 5, 0, 305)
PalmIsland.Size = UDim2.new(0, 125, 0, 20)
PalmIsland.Font = Enum.Font.Fantasy
PalmIsland.FontSize = Enum.FontSize.Size18
PalmIsland.Text = "Palm Island"
PalmIsland.TextColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
PalmIsland.TextSize = 16

SpawnPoint.Name = "SpawnPoint"
SpawnPoint.Parent = Waypoints
SpawnPoint.BackgroundColor3 = Color3.new(0, 0, 0)
SpawnPoint.Position = UDim2.new(0, 5, 0, 5)
SpawnPoint.Size = UDim2.new(0, 125, 0, 20)
SpawnPoint.Font = Enum.Font.Fantasy
SpawnPoint.FontSize = Enum.FontSize.Size18
SpawnPoint.Text = "Spawn"
SpawnPoint.TextColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
SpawnPoint.TextSize = 16

Swamp.Name = "Swamp"
Swamp.Parent = Waypoints
Swamp.BackgroundColor3 = Color3.new(0, 0, 0)
Swamp.Position = UDim2.new(0, 5, 0, 280)
Swamp.Size = UDim2.new(0, 125, 0, 20)
Swamp.Font = Enum.Font.Fantasy
Swamp.FontSize = Enum.FontSize.Size18
Swamp.Text = "Swamp"
Swamp.TextColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
Swamp.TextSize = 16

Volcano.Name = "Volcano"
Volcano.Parent = Waypoints
Volcano.BackgroundColor3 = Color3.new(0, 0, 0)
Volcano.Position = UDim2.new(0, 5, 0, 255)
Volcano.Size = UDim2.new(0, 125, 0, 20)
Volcano.Font = Enum.Font.Fantasy
Volcano.FontSize = Enum.FontSize.Size18
Volcano.Text = "Volcano"
Volcano.TextColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
Volcano.TextSize = 16

WoodRUs.Name = "WoodRUs"
WoodRUs.Parent = Waypoints
WoodRUs.BackgroundColor3 = Color3.new(0, 0, 0)
WoodRUs.Position = UDim2.new(0, 5, 0, 55)
WoodRUs.Size = UDim2.new(0, 125, 0, 20)
WoodRUs.Font = Enum.Font.Fantasy
WoodRUs.FontSize = Enum.FontSize.Size18
WoodRUs.Text = "Wood R Us"
WoodRUs.TextColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
WoodRUs.TextSize = 16

	local service = setmetatable({}, {
	__index = function(t, k)
		return game:GetService(k)
	end
	})
	
	function Create(cls,props)
	local inst = Instance.new(cls)
	for i,v in pairs(props) do
		inst[i] = v
	end
	return inst
end

local WoodPlanks={}

function MakeShadow(UI,Index)
	Create("Frame",{Parent=UI,Size=UDim2.new(1,0,1,0),ZIndex=Index,Position=UDim2.new(0,1,0,1),BackgroundColor3=Color3.fromRGB(0,0,0),BorderSizePixel=0,Transparency=0.9,Name="Shadow"})
	Create("Frame",{Parent=UI,Size=UDim2.new(1,0,1,0),ZIndex=Index,Position=UDim2.new(0,2,0,2),BackgroundColor3=Color3.fromRGB(0,0,0),BorderSizePixel=0,Transparency=0.9,Name="Shadow"})
	Create("Frame",{Parent=UI,Size=UDim2.new(1,0,1,0),ZIndex=Index,Position=UDim2.new(0,3,0,3),BackgroundColor3=Color3.fromRGB(0,0,0),BorderSizePixel=0,Transparency=0.9,Name="Shadow"})
end

local ProcessedWoodList = LT2.MainFrame.PlankFrame.ProcessedWoodList
local LastPurchasedList = LT2.MainFrame.PurchasedFrame.LastPurchasedList

	local Menus = {
[Players] = PlayersFrame;
[Teleport] = WaypointFrame;
[TpBox] = PurchasedFrame;
[TpPlank] = PlankFrame;
[Settings] = SettingsFrame;
}
for button,frame in pairs(Menus) do
	button.MouseButton1Click:connect(function()
if frame.Visible then
frame.Visible = false
return
end
for k,v in pairs(Menus) do
v.Visible = v == frame
end
end)
end

Close.MouseButton1Down:connect(function()
LT2:Destroy()
end)

local Walk=16
local Jump=50

service.Players.LocalPlayer.Character.Humanoid.Changed:Connect(function()
	if service.Players.LocalPlayer.Character:FindFirstChild("Humanoid") then
		service.Players.LocalPlayer.Character.Humanoid.WalkSpeed=Walk
		service.Players.LocalPlayer.Character.Humanoid.JumpPower=Jump
	end
end)

WalkSpeed.Changed:Connect(function()
	Walk=tonumber(WalkSpeed.Text)
end)

JumpPower.Changed:Connect(function()
	Jump=tonumber(JumpPower.Text)
end)

PlotTp.MouseButton1Down:connect(function()
	for i,v in pairs(game.Workspace.Properties:GetChildren()) do
		if v.Owner.Value == game.Players.LocalPlayer then
			game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.OriginSquare.CFrame + Vector3.new(0,10,0)
		end
	end
end)

	Player1.MouseButton1Down:connect(function()
      PlayerSelect.Text = Player1.Text
    end)
    Player2.MouseButton1Down:connect(function()
      PlayerSelect.Text = Player2.Text
    end)
    Player3.MouseButton1Down:connect(function()
      PlayerSelect.Text = Player3.Text
    end)
    Player4.MouseButton1Down:connect(function()
      PlayerSelect.Text = Player4.Text
    end)
    Player5.MouseButton1Down:connect(function()
      PlayerSelect.Text = Player5.Text
    end)
    Player6.MouseButton1Down:connect(function()
      PlayerSelect.Text = Player6.Text
    end)
	
	PlayerTp.MouseButton1Down:connect(function()
      if PlayerSelect.Text == "Select a Player" then
        warn("No Player Selected")
      else
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = workspace[PlayerSelect.Text].HumanoidRootPart.CFrame
      end
    end)
    TpBase.MouseButton1Down:connect(function()
      for i, v in pairs(game.Workspace.Properties:GetChildren()) do
        if v.Owner.Value == game.Players[PlayerSelect.Text] then
          game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.OriginSquare.CFrame
        end
      end
    end)
	
	    local buttons = {
      Player1,
      Player2,
      Player3,
      Player4,
      Player5,
      Player6
    }
    for i, v in pairs(game.Players:GetChildren()) do
      buttons[i].Text = v.Name
      buttons[i].Visible = true
    end
    game.Players.PlayerRemoving:connect(function()
      for i, v in pairs(game.Players:GetChildren()) do
        buttons[i].Text = v.Name
        buttons[i].Visible = true
      end
    end)
    game.Players.PlayerAdded:connect(function()
      for i, v in pairs(game.Players:GetChildren()) do
        buttons[i].Text = v.Name
        buttons[i].Visible = true
      end
    end)

	local WayPoints = {
["Wood R Us"] = Vector3.new(265, 3, 57),
["SpawnPoint"] = Vector3.new(155, 3, 74),
["Land Store"] = Vector3.new(258, 3, -99),
["Link's Logic"] = Vector3.new(4607, 7.5, -798),
["Cave"] = Vector3.new(3581, -179, 430),
["Volcano"] = Vector3.new(-1585, 622, 1140),
["Swamp"] = Vector3.new(-1209, 132, -801),
["Palm Island"] = Vector3.new(2549, -5, -42),
["Fancy Furnishings"] = Vector3.new(491, 3, -1720),
["Boxed Cars"] = Vector3.new(509, 3, -1463),
["Fine Arts Shop"] = Vector3.new(5207, -166, 719),
["Bob's Shack"] = Vector3.new(260, 8, -2542),
["Strange Man"] = Vector3.new(1061, 16, 1131)
}

WoodRUs.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character:MoveTo(WayPoints["Wood R Us"])
end)

SpawnPoint.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character:MoveTo(WayPoints["SpawnPoint"])
end)

LandStore.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character:MoveTo(WayPoints["Land Store"])
end)

LinksLogic.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character:MoveTo(WayPoints["Link's Logic"])
end)

Cave.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character:MoveTo(WayPoints["Cave"])
end)

Volcano.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character:MoveTo(WayPoints["Volcano"])
end)

Swamp.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character:MoveTo(WayPoints["Swamp"])
end)

PalmIsland.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character:MoveTo(WayPoints["Palm Island"])
end)

FancyFurnishings.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character:MoveTo(WayPoints["Fancy Furnishings"])
end)

BoxedCars.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character:MoveTo(WayPoints["Boxed Cars"])
end)

FineArtsShop.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character:MoveTo(WayPoints["Fine Arts Shop"])
end)

BobsShack.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character:MoveTo(WayPoints["Bob's Shack"])
end)

Stranger.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character:MoveTo(WayPoints["Strange Man"])
end)

Option = false

Dupe.MouseButton1Down:connect(function()
plr = game:GetService("Players").LocalPlayer
slot = plr.CurrentSaveSlot
	if Option == false then
		if slot.Value == -1 then
Option = true
slot.RobloxLocked = true
DupeStatus.Text = "ON"
DupeStatus.TextColor3 = Color3.new(0, 0.666667, 0)
	end
	else
Option = false
slot.RobloxLocked = false
DupeStatus.Text = "OFF"
DupeStatus.TextColor3 = Color3.new(1, 0, 0)
	end
end)

Greywood.MouseButton1Click:Connect(function()
	for i,v in next,workspace.PlayerModels:GetChildren() do
        if v:FindFirstChild("Type") then
            if v.Type.Value == "Blueprint" then
                v.Type.Value = "Structure"
            end
        end
    end
end)

TpWood.MouseButton1Click:Connect(function()
	for _, Log in pairs(service.Workspace.LogModels:GetChildren()) do
		if Log.Name:sub(1, 6) == "Loose_" and Log:findFirstChild("Owner") then
			if Log.Owner.Value == service.Players.LocalPlayer then
				Log:MoveTo(service.Players.LocalPlayer.Character.HumanoidRootPart.Position + Vector3.new(0, 20, 0))
				for i=1,100 do
					service.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(Log)
				end
			end
		end
	end
end)

local inc = 0
workspace.PlayerModels.ChildAdded:Connect(function(Item)
	inc = #LastPurchasedList:GetChildren()
	if Item:FindFirstChild("Owner") and Item.Owner.Value==service.Players.LocalPlayer then
		LastPurchasedList.CanvasSize=UDim2.new(0,0,0,25*inc)
		local SellButton=Create("TextButton",{Parent=LastPurchasedList,Size=UDim2.new(1,-9,0,20),Position=UDim2.new(0,5,0,25*inc),Text=" "..Item.Name,Name=Item.Name,TextXAlignment="Left",ZIndex=3,BorderSizePixel=0})
		MakeShadow(SellButton,2)
		SellButton.MouseButton1Click:Connect(function()
			if Item:IsA("Model") then
				Item:MoveTo(service.Players.LocalPlayer.Character.HumanoidRootPart.Position)
				for i=1,100 do
					service.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(Item)
				end
			end
		end)
		inc=inc+1
	end
end)

workspace.PlayerModels.ChildRemoved:Connect(function(Item)
	inc=0
	if Item:FindFirstChild("Owner") and Item.Owner.Value==service.Players.LocalPlayer then
		if LastPurchasedList:FindFirstChild(Item.Name) then
			LastPurchasedList:FindFirstChild(Item.Name):Destroy()
			for i,v in pairs(LastPurchasedList:GetChildren()) do
				v.Position=UDim2.new(0,5,0,25*(i-1))
			end
		end
	end
end)

function UpdatePlanks()
	local inc = 0
	WoodPlanks={}
	for i,v in pairs(service.Workspace.PlayerModels:GetChildren()) do
		if v.Name=="Plank" and v.Owner.Value==service.Players.LocalPlayer then
			if v:FindFirstChild("TreeClass") and WoodPlanks[v.TreeClass.Value] then
				WoodPlanks[v.TreeClass.Value]=WoodPlanks[v.TreeClass.Value]
				WoodPlanks[v.TreeClass.Value]["Wood"][v]=v
			elseif v:FindFirstChild("TreeClass") then
				WoodPlanks[v.TreeClass.Value]={Wood={v.WoodSection}}
			end
		end
	end
end

function UpdateSellPlanks()
	local inc=0
	UpdatePlanks()
	ProcessedWoodList:ClearAllChildren()
	for i,v in pairs(WoodPlanks) do
		ProcessedWoodList.CanvasSize=UDim2.new(0,0,0,25*inc)
		local SellButton=Create("TextButton",{Parent=ProcessedWoodList,Size=UDim2.new(1,-14,0,20),Position=UDim2.new(0,5,0,35*inc),Text=" "..i,TextXAlignment="Left",ZIndex=3,BorderSizePixel=0})
		local Color = Create("Frame",{Parent=ProcessedWoodList,Size=UDim2.new(0,5,0,20),Position=UDim2.new(0,0,0,35*inc),BorderSizePixel=0,ZIndex=3,BackgroundColor3=v["Wood"].Color})
		MakeShadow(SellButton,2)
		SellButton.MouseButton1Click:Connect(function()
			for x=1,100 do
				v["Wood"].CFrame=CFrame.new(service.Players.LocalPlayer.Character.HumanoidRootPart.Position + Vector3.new(0, 20, 0))
				service.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(v["Wood"].Parent)
			end
		end)
		inc=inc+1
	end
	inc=0
end

service.Workspace.PlayerModels.ChildRemoved:Connect(function(thing)
	if thing.Owner.Value==service.Players.LocalPlayer then
		UpdateSellPlanks()
	end
end)

UpdateSellPlanks()

SellWood.MouseButton1Click:Connect(function()
	for _, Log in pairs(service.Workspace.LogModels:GetChildren()) do
		if Log.Name:sub(1, 6) == "Loose_" and Log:findFirstChild("Owner") then
			if Log.Owner.Value == service.Players.LocalPlayer then
				for i,v in pairs(Log:GetChildren()) do
					if v.Name=="WoodSection" then
						spawn(function()
							for i=1,10 do
								wait()
								v.CFrame=CFrame.new(Vector3.new(315, -0.296, 85.791))*CFrame.Angles(math.rad(90),0,0)
							end
						end)
					end
				end
				spawn(function()
					for i=1,20 do
						wait()
						service.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(Log)
					end
				end)
			end
		end
	end
end)

SellPlanks.MouseButton1Click:Connect(function()
	for _, Plank in pairs(service.Workspace.PlayerModels:GetChildren()) do
		if Plank.Name=="Plank" and Plank:findFirstChild("Owner") then
			if Plank.Owner.Value == service.Players.LocalPlayer then
				for i,v in pairs(Plank:GetChildren()) do
					if v.Name=="WoodSection" then
						spawn(function()
							for i=1,10 do
								wait()
								v.CFrame=CFrame.new(Vector3.new(315, -0.296, 85.791))*CFrame.Angles(math.rad(90),0,0)
							end
						end)
					end
				end
				spawn(function()
					for i=1,20 do
						wait()
						service.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(Plank)
					end
				end)
			end
		end
	end
end)

TpAllPlanks.MouseButton1Click:Connect(function()
	for _, Plank in pairs(service.Workspace.PlayerModels:GetChildren()) do
		if Plank.Name=="Plank" and Plank:findFirstChild("Owner") then
			if Plank.Owner.Value == service.Players.LocalPlayer then
				Plank:MoveTo(service.Players.LocalPlayer.Character.HumanoidRootPart.Position + Vector3.new(0, 20, 0))
				for i=1,100 do
					service.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(Plank)
				end
			end
		end
	end
end)

Close.MouseLeave:connect(function()
Close.BackgroundColor3 = Color3.new(0.129412, 0.129412, 0.129412)
end)
Close.MouseEnter:connect(function()
Close.BackgroundColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
end)

Dupe.MouseLeave:connect(function()
Dupe.TextColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
Dupe.BackgroundColor3 = Color3.new(0.129412, 0.129412, 0.129412)
end)
Dupe.MouseEnter:connect(function()
Dupe.TextColor3 = Color3.new(0, 0, 0)
Dupe.BackgroundColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
end)

Greywood.MouseLeave:connect(function()
Greywood.TextColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
Greywood.BackgroundColor3 = Color3.new(0.129412, 0.129412, 0.129412)
end)
Greywood.MouseEnter:connect(function()
Greywood.TextColor3 = Color3.new(0, 0, 0)
Greywood.BackgroundColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
end)

Players.MouseLeave:connect(function()
Players.TextColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
Players.BackgroundColor3 = Color3.new(0.129412, 0.129412, 0.129412)
end)
Players.MouseEnter:connect(function()
Players.TextColor3 = Color3.new(0, 0, 0)
Players.BackgroundColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
end)

SellPlanks.MouseLeave:connect(function()
SellPlanks.TextColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
SellPlanks.BackgroundColor3 = Color3.new(0.129412, 0.129412, 0.129412)
end)
SellPlanks.MouseEnter:connect(function()
SellPlanks.TextColor3 = Color3.new(0, 0, 0)
SellPlanks.BackgroundColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
end)

SellWood.MouseLeave:connect(function()
SellWood.TextColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
SellWood.BackgroundColor3 = Color3.new(0.129412, 0.129412, 0.129412)
end)
SellWood.MouseEnter:connect(function()
SellWood.TextColor3 = Color3.new(0, 0, 0)
SellWood.BackgroundColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
end)

Settings.MouseLeave:connect(function()
Settings.TextColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
Settings.BackgroundColor3 = Color3.new(0.129412, 0.129412, 0.129412)
end)
Settings.MouseEnter:connect(function()
Settings.TextColor3 = Color3.new(0, 0, 0)
Settings.BackgroundColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
end)

Teleport.MouseLeave:connect(function()
Teleport.TextColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
Teleport.BackgroundColor3 = Color3.new(0.129412, 0.129412, 0.129412)
end)
Teleport.MouseEnter:connect(function()
Teleport.TextColor3 = Color3.new(0, 0, 0)
Teleport.BackgroundColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
end)

TpBox.MouseLeave:connect(function()
TpBox.TextColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
TpBox.BackgroundColor3 = Color3.new(0.129412, 0.129412, 0.129412)
end)
TpBox.MouseEnter:connect(function()
TpBox.TextColor3 = Color3.new(0, 0, 0)
TpBox.BackgroundColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
end)

TpWood.MouseLeave:connect(function()
TpWood.TextColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
TpWood.BackgroundColor3 = Color3.new(0.129412, 0.129412, 0.129412)
end)
TpWood.MouseEnter:connect(function()
TpWood.TextColor3 = Color3.new(0, 0, 0)
TpWood.BackgroundColor3 = Color3.new(0.0705882, 0.521569, 0.529412)
end)	
end)
DupeGui.Name = "DupeGui"
DupeGui.Parent = MainFrame
DupeGui.BackgroundColor3 = Color3.new(0, 0, 0)
DupeGui.BorderColor3 = Color3.new(0, 1, 0)
DupeGui.BorderSizePixel = 5
DupeGui.Position = UDim2.new(0.744642854, 0, 0.211009175, 0)
DupeGui.Size = UDim2.new(0, 94, 0, 38)
DupeGui.Font = Enum.Font.SciFi
DupeGui.Text = "DupeGui"
DupeGui.TextColor3 = Color3.new(0, 1, 0)
DupeGui.TextScaled = true
DupeGui.TextSize = 14
DupeGui.TextWrapped = true
DupeGui.MouseButton1Down:connect(function()
Option = false
Found = false
Tool = "None"
Down = false
Mouse = game.Players.LocalPlayer:GetMouse()
 
Client = game.ReplicatedStorage.Interaction.ClientSetListPlayer
players = game.Players
for i, v in pairs(players:GetPlayers()) do
if v.Name ~= players.LocalPlayer.Name then
Client:InvokeServer(players.LocalPlayer.BlacklistFolder, v, true)
end
end
players.PlayerAdded:connect(function(plr)
Client:InvokeServer(players.LocalPlayer.BlacklistFolder, plr, true)
end)
 
function move(object)
object:MoveTo(game.Players.LocalPlayer.Character.Head.Position + Vector3.new(5, -4, 5))
object.WoodSection.Anchored = true
wait(2)
object.WoodSection.Anchored = false
end
 
function tree(object, class)
for i, v in pairs(object:GetChildren()) do
if v.Name == "TreeClass" then
if v.Value == class then
if Found == false then
move(object)
Found = true
end
end
end
end
end
 
function cut(object, class)
for i, v in pairs(object:GetChildren()) do
if v.Name == "TreeClass" then
if v.Value == class then
for a, b in pairs(object:GetChildren()) do
if b.Name == "Owner" then
for c, d in pairs(b:GetChildren()) do
if d.Name == "OwnerString" then
if d.Value == game.Players.LocalPlayer.Name then
move(object)
else
if d.Value == "" then
move(object)
end
end
end
end
end
end
end
end
end
end
 
local Text = Instance.new("TextLabel")
local Main = Instance.new("Frame")
local CF = Instance.new("ScreenGui")
local CG69 = game.CoreGui
local Tab1 = Instance.new("TextButton")
local Tab2 = Instance.new("TextButton")
local Tab3 = Instance.new("TextButton")
local TTab1 = Instance.new("Frame")
local TTab2 = Instance.new("Frame")
local TTab3 = Instance.new("Frame")
local Close = Instance.new("TextButton")
local Depart = Instance.new("TextLabel")
 
 
local place = UDim2.new(0, 0, 0, 70)
local size = UDim2.new(0, 300, 0, 100)
 
CF.Name = "GO!!"
CF.Parent = CG69
local CGG = CG69["GO!!"]
 
 
Main.Name = "Main"
Main.Parent = CF
Main.BackgroundColor3 = Color3.new(0.1, 0.6, 0.3)
Main.BorderColor3 = Color3.new(0, 0, 0)
Main.Position = UDim2.new(0, 500, 0, 500)
Main.Size = UDim2.new(0, 300, 0, 75)
Main.Visible = true
Main.Draggable = true
Main.Active = true
 
Text.Name = "Text"
Text.Parent = Main
Text.BackgroundColor3 = Color3.new(1, 1, 1)
Text.BackgroundTransparency = 1
Text.Position = UDim2.new(0.45, 0, 0, 0)
Text.Size = UDim2.new(0, 20, 0, 35)
Text.Font = Enum.Font.SourceSansBold
Text.FontSize = Enum.FontSize.Size18
Text.Text = "GUI Not in Use"
Text.TextColor3 = Color3.new(0.901961, 0.901961, 0.901961)
Text.TextSize = 18
 
Depart .Name = "Depart"
Depart .Parent = Main
Depart .BackgroundColor3 = Color3.new(1, 1, 1)
Depart .BackgroundTransparency = 1
Depart .Position = UDim2.new(0, 150, 0, 0)
Depart .Size = UDim2.new(0, 1, 0, 10)
Depart .Font = Enum.Font.SourceSansBold
Depart .FontSize = Enum.FontSize.Size18
Depart .Text = "Time To Departure: 0"
Depart .TextColor3 = Color3.new(0.901961, 0.901961, 0.901961)
Depart .TextSize = 18
 
Tab1.Name = "Basic"
Tab1.Parent = Main
Tab1.BackgroundColor3 = Color3.new(0.3, 0.6, 0.9)
Tab1.Position = UDim2.new(0, 0, 0, 35)
Tab1.Size = UDim2.new(0, 80, 0, 20)
Tab1.Font = Enum.Font.Cartoon
Tab1.FontSize = Enum.FontSize.Size14
Tab1.Text = "Basic Tab"
Tab1.TextSize = 18
 
Tab2.Name = "UTrees"
Tab2.Parent = Main
Tab2.BackgroundColor3 = Color3.new(1, 0, 0)
Tab2.Position = UDim2.new(0, 110, 0, 35)
Tab2.Size = UDim2.new(0, 80, 0, 20)
Tab2.Font = Enum.Font.Cartoon
Tab2.FontSize = Enum.FontSize.Size14
Tab2.Text = "UTrees"
Tab2.TextSize = 18
 
Tab3.Name = "CTrees"
Tab3.Parent = Main
Tab3.BackgroundColor3 = Color3.new(0.5, 0.8, 0.2)
Tab3.Position = UDim2.new(0, 220, 0, 35)
Tab3.Size = UDim2.new(0, 80, 0, 20)
Tab3.Font = Enum.Font.Cartoon
Tab3.FontSize = Enum.FontSize.Size14
Tab3.Text = "CTrees"
Tab3.TextSize = 18
 
TTab1.Name = "GunsTab"
TTab1.Parent = Main
TTab1.BackgroundColor3 = Color3.new(0, 0, 0)
TTab1.BorderColor3 = Color3.new(1, 1, 1)
TTab1.Position = place
TTab1.Size = size
TTab1.Visible = true
 
TTab2.Name = "ItemsTab"
TTab2.Parent = Main
TTab2.BackgroundColor3 = Color3.new(1, 1, 1)
TTab2.BorderColor3 = Color3.new(0, 0, 0)
TTab2.Position = place
TTab2.Size = size
TTab2.Visible = false
 
TTab3.Name = "StatsTab"
TTab3.Parent = Main
TTab3.BackgroundColor3 = Color3.new(0, 1, 0)
TTab3.BorderColor3 = Color3.new(1, 0, 1)
TTab3.Position = place
TTab3.Size = size
TTab3.Visible = false
 
Close.Name = "X"
Close.Parent = Main
Close.BackgroundColor3 = Color3.new(1, 0, 0)
Close.Position = UDim2.new(0, 275, 0, 0)
Close.Size = UDim2.new(0, 25, 0, 25)
Close.Font = Enum.Font.Cartoon
Close.FontSize = Enum.FontSize.Size14
Close.Text = "X"
Close.TextSize = 14
 
 
-- Tab 1 Buttons --
Dupe = Instance.new("TextButton")
DupeLabel = Instance.new("TextLabel")
Steal = Instance.new("TextButton")
CopyTool = Instance.new("TextButton")
DeleteTool = Instance.new("TextButton")
MoveTool = Instance.new("TextButton")
 
Dupe.Name = "Dupe"
Dupe.Parent = TTab1
Dupe.BackgroundColor3 = Color3.new(0.7, 0, 0)
Dupe.Position = UDim2.new(0, 105, 0, 54)
Dupe.Size = UDim2.new(0,85, 0, 25)
Dupe.Font = Enum.Font.Cartoon
Dupe.FontSize = Enum.FontSize.Size14
Dupe.Text = "Dupe"
Dupe.TextSize = 14
 
DupeLabel.Name = "Dupe"
DupeLabel.Parent = TTab1
DupeLabel.BackgroundColor3 = Color3.new(0.7, 0, 0)
DupeLabel.BackgroundTransparency = 1
DupeLabel.Position = UDim2.new(0, 105, 0, 74)
DupeLabel.Size = UDim2.new(0,85, 0, 25)
DupeLabel.Font = Enum.Font.Cartoon
DupeLabel.FontSize = Enum.FontSize.Size14
DupeLabel.Text = "Current save Will Save"
DupeLabel.TextColor3 = Color3.new(255, 255, 255)
DupeLabel.TextSize = 14
 
Steal.Name = "Dupe"
Steal.Parent = TTab1
Steal.BackgroundColor3 = Color3.new(1, 1, 1)
Steal.Position = UDim2.new(0, 105, 0, 31)
Steal.Size = UDim2.new(0,85, 0, 25)
Steal.Font = Enum.Font.Cartoon
Steal.FontSize = Enum.FontSize.Size14
Steal.Text = "Steal"
Steal.TextSize = 14
 
CopyTool.Name = "CopyTool"
CopyTool.Parent = TTab1
CopyTool.BackgroundColor3 = Color3.new(0.7, 0, 0)
CopyTool.Position = UDim2.new(0, 1, 0, 1)
CopyTool.Size = UDim2.new(0,85, 0, 25)
CopyTool.Font = Enum.Font.Cartoon
CopyTool.FontSize = Enum.FontSize.Size14
CopyTool.Text = "Copy"
CopyTool.TextSize = 14
 
DeleteTool.Name = "DeleteTool"
DeleteTool.Parent = TTab1
DeleteTool.BackgroundColor3 = Color3.new(0.7, 0, 0)
DeleteTool.Position = UDim2.new(0, 90, 0, 1)
DeleteTool.Size = UDim2.new(0,85, 0, 25)
DeleteTool.Font = Enum.Font.Cartoon
DeleteTool.FontSize = Enum.FontSize.Size14
DeleteTool.Text = "Delete"
DeleteTool.TextSize = 14
 
MoveTool.Name = "MoveTool"
MoveTool.Parent = TTab1
MoveTool.BackgroundColor3 = Color3.new(0.7, 0, 0)
MoveTool.Position = UDim2.new(0, 179, 0, 1)
MoveTool.Size = UDim2.new(0,85, 0, 25)
MoveTool.Font = Enum.Font.Cartoon
MoveTool.FontSize = Enum.FontSize.Size14
MoveTool.Text = "Move"
MoveTool.TextSize = 14
 
-- end --
 
 
 
-- Tab 1 Button Functions --
Dupe.MouseButton1Down:connect(function()
plr = game:GetService("Players").LocalPlayer
slot = plr.CurrentSaveSlot
if Option == false then
if slot.Value == -1 then
Option = true
slot.RobloxLocked = true
Dupe.BackgroundColor3 = Color3.new(0, 1, 0)
DupeLabel.Text = "Current save Will  Not Save"
end
else
Option = false
slot.RobloxLocked = false
Dupe.BackgroundColor3 = Color3.new(0.7, 0, 0)
DupeLabel.Text = "Current save Will Save"
end
end)
 
Steal.MouseButton1Down:connect(function()
Owner = false
for i, v in pairs(game.Workspace:GetChildren()) do
if v.Name == "Owner" then
Owner = true
end
end
 
if Owner == false then
for i, v in pairs(game.Workspace.PlayerModels:GetChildren()) do
for a, b in pairs(v:GetChildren()) do
if b.Name == "Owner" then
for c, d in pairs(b:GetChildren()) do
if d:IsA("StringValue") then
if d.Value == game.Players.LocalPlayer.Name then
object = b
end
end
end
end
end
end
 
print("Copied")
 
if object then
Owner = true
object:clone().Parent = game.Workspace
end
end
wait()
 
if Owner == true then
print("Copying")
for i, v in pairs(game.Workspace.PlayerModels:GetChildren()) do
for a, b in pairs(v:GetChildren()) do
if b.Name == "Owner" then
b:remove()
game.Workspace.Owner:clone().Parent = v
end
end
end
end
 
end)
 
CopyTool.MouseButton1Down:connect(function()
if Tool == "Copy" then
Tool = "None"
CopyTool.BackgroundColor3 = Color3.new(0.7, 0, 0)
else
Tool = "Copy"
CopyTool.BackgroundColor3 = Color3.new(0, 0.7, 0)
DeleteTool.BackgroundColor3 = Color3.new(0.7, 0, 0)
MoveTool.BackgroundColor3 = Color3.new(0.7, 0, 0)
end
end)
 
DeleteTool.MouseButton1Down:connect(function()
if Tool == "Delete" then
Tool = "Nothing"
DeleteTool.BackgroundColor3 = Color3.new(0.7, 0, 0)
else
Tool = "Delete"
CopyTool.BackgroundColor3 = Color3.new(0.7, 0, 0)
DeleteTool.BackgroundColor3 = Color3.new(0, 0.7, 0)
MoveTool.BackgroundColor3 = Color3.new(0.7, 0, 0)
end
end)
 
MoveTool.MouseButton1Down:connect(function()
if Tool == "Move" then
Tool = "Nothing"
MoveTool.BackgroundColor3 = Color3.new(0.7, 0, 0)
else
Tool = "Move"
CopyTool.BackgroundColor3 = Color3.new(0.7, 0, 0)
DeleteTool.BackgroundColor3 = Color3.new(0.7, 0, 0)
MoveTool.BackgroundColor3 = Color3.new(0, 0.7, 0)
 
end
end)
 
-- end --
 
-- Tab2 Buttons --
Birch = Instance.new("TextButton")
CaveCrawler = Instance.new("TextButton")
Cherry = Instance.new("TextButton")
Fir = Instance.new("TextButton")
Generic = Instance.new("TextButton")
GoldSwampy = Instance.new("TextButton")
GreenSwampy = Instance.new("TextButton")
Koa = Instance.new("TextButton")
LoneCave = Instance.new("TextButton")
Oak = Instance.new("TextButton")
Palm = Instance.new("TextButton")
Pine = Instance.new("TextButton")
Volcano = Instance.new("TextButton")
Walnut = Instance.new("TextButton")
 
Birch.Name = "Birch"
Birch.Parent = TTab2
Birch.BackgroundColor3 = Color3.new(0, 1, 1)
Birch.Position = UDim2.new(0, 1, 0, 1)
Birch.Size = UDim2.new(0,70, 0, 25)
Birch.Font = Enum.Font.Cartoon
Birch.FontSize = Enum.FontSize.Size14
Birch.Text = "Birch"
Birch.TextSize = 14
 
CaveCrawler.Name = "CaveCrawler"
CaveCrawler.Parent = TTab2
CaveCrawler.BackgroundColor3 = Color3.new(0, 1, 1)
CaveCrawler.Position = UDim2.new(0, 71, 0, 1)
CaveCrawler.Size = UDim2.new(0,70, 0, 25)
CaveCrawler.Font = Enum.Font.Cartoon
CaveCrawler.FontSize = Enum.FontSize.Size14
CaveCrawler.Text = "CaveCrawler"
CaveCrawler.TextSize = 14
 
Cherry.Name = "Cherry"
Cherry.Parent = TTab2
Cherry.BackgroundColor3 = Color3.new(0, 1, 1)
Cherry.Position = UDim2.new(0, 141, 0, 1)
Cherry.Size = UDim2.new(0,70, 0, 25)
Cherry.Font = Enum.Font.Cartoon
Cherry.FontSize = Enum.FontSize.Size14
Cherry.Text = "Cherry"
Cherry.TextSize = 14
 
Fir.Name = "Fir"
Fir.Parent = TTab2
Fir.BackgroundColor3 = Color3.new(0, 1, 1)
Fir.Position = UDim2.new(0, 211, 0, 1)
Fir.Size = UDim2.new(0,70, 0, 25)
Fir.Font = Enum.Font.Cartoon
Fir.FontSize = Enum.FontSize.Size14
Fir.Text = "Fir"
Fir.TextSize = 14
 
Generic.Name = "Generic"
Generic.Parent = TTab2
Generic.BackgroundColor3 = Color3.new(0, 1, 1)
Generic.Position = UDim2.new(0, 1, 0, 26)
Generic.Size = UDim2.new(0,70, 0, 25)
Generic.Font = Enum.Font.Cartoon
Generic.FontSize = Enum.FontSize.Size14
Generic.Text = "Generic"
Generic.TextSize = 14
 
GoldSwampy.Name = "GoldSwampy"
GoldSwampy.Parent = TTab2
GoldSwampy.BackgroundColor3 = Color3.new(0, 1, 1)
GoldSwampy.Position = UDim2.new(0, 71, 0, 26)
GoldSwampy.Size = UDim2.new(0,70, 0, 25)
GoldSwampy.Font = Enum.Font.Cartoon
GoldSwampy.FontSize = Enum.FontSize.Size14
GoldSwampy.Text = "Gold"
GoldSwampy.TextSize = 14
 
GreenSwampy.Name = "GreenSwampy"
GreenSwampy.Parent = TTab2
GreenSwampy.BackgroundColor3 = Color3.new(0, 1, 1)
GreenSwampy.Position = UDim2.new(0, 141, 0, 26)
GreenSwampy.Size = UDim2.new(0,70, 0, 25)
GreenSwampy.Font = Enum.Font.Cartoon
GreenSwampy.FontSize = Enum.FontSize.Size14
GreenSwampy.Text = "Green"
GreenSwampy.TextSize = 14
 
Koa.Name = "Koa"
Koa.Parent = TTab2
Koa.BackgroundColor3 = Color3.new(0, 1, 1)
Koa.Position = UDim2.new(0, 211, 0, 26)
Koa.Size = UDim2.new(0,70, 0, 25)
Koa.Font = Enum.Font.Cartoon
Koa.FontSize = Enum.FontSize.Size14
Koa.Text = "Koa"
Koa.TextSize = 14
 
LoneCave.Name = "LoneCave"
LoneCave.Parent = TTab2
LoneCave.BackgroundColor3 = Color3.new(0, 1, 1)
LoneCave.Position = UDim2.new(0, 1, 0, 51)
LoneCave.Size = UDim2.new(0,70, 0, 25)
LoneCave.Font = Enum.Font.Cartoon
LoneCave.FontSize = Enum.FontSize.Size14
LoneCave.Text = "LoneCave"
LoneCave.TextSize = 14
 
Oak.Name = "Oak"
Oak.Parent = TTab2
Oak.BackgroundColor3 = Color3.new(0, 1, 1)
Oak.Position = UDim2.new(0, 71, 0, 51)
Oak.Size = UDim2.new(0,70, 0, 25)
Oak.Font = Enum.Font.Cartoon
Oak.FontSize = Enum.FontSize.Size14
Oak.Text = "Oak"
Oak.TextSize = 14
 
Palm.Name = "Palm"
Palm.Parent = TTab2
Palm.BackgroundColor3 = Color3.new(0, 1, 1)
Palm.Position = UDim2.new(0, 141, 0, 51)
Palm.Size = UDim2.new(0,70, 0, 25)
Palm.Font = Enum.Font.Cartoon
Palm.FontSize = Enum.FontSize.Size14
Palm.Text = "Palm"
Palm.TextSize = 14
 
Pine.Name = "Pine"
Pine.Parent = TTab2
Pine.BackgroundColor3 = Color3.new(0, 1, 1)
Pine.Position = UDim2.new(0, 211, 0, 51)
Pine.Size = UDim2.new(0,70, 0, 25)
Pine.Font = Enum.Font.Cartoon
Pine.FontSize = Enum.FontSize.Size14
Pine.Text = "Pine"
Pine.TextSize = 14
 
Volcano.Name = "Volcano"
Volcano.Parent = TTab2
Volcano.BackgroundColor3 = Color3.new(0, 1, 1)
Volcano.Position = UDim2.new(0, 1, 0, 76)
Volcano.Size = UDim2.new(0,70, 0, 25)
Volcano.Font = Enum.Font.Cartoon
Volcano.FontSize = Enum.FontSize.Size14
Volcano.Text = "Volcano"
Volcano.TextSize = 14
 
Walnut.Name = "Walnut"
Walnut.Parent = TTab2
Walnut.BackgroundColor3 = Color3.new(0, 1, 1)
Walnut.Position = UDim2.new(0, 71, 0, 76)
Walnut.Size = UDim2.new(0,70, 0, 25)
Walnut.Font = Enum.Font.Cartoon
Walnut.FontSize = Enum.FontSize.Size14
Walnut.Text = "Walnut"
Walnut.TextSize = 14
 
-- end --
 
-- Tab2 Button Functions --
Birch.MouseButton1Down:connect(function()
Found = false
for i, v in pairs(game.Workspace:GetChildren()) do
if v.Name == "TreeRegion" then
for a, b in pairs(v:GetChildren()) do
tree(b, "Birch")
end
end
end
end)
 
CaveCrawler.MouseButton1Down:connect(function()
Found = false
for i, v in pairs(game.Workspace:GetChildren()) do
if v.Name == "TreeRegion" then
for a, b in pairs(v:GetChildren()) do
tree(b, "CaveCrawler")
end
end
end
end)
 
Cherry.MouseButton1Down:connect(function()
Found = false
for i, v in pairs(game.Workspace:GetChildren()) do
if v.Name == "TreeRegion" then
for a, b in pairs(v:GetChildren()) do
tree(b, "Cherry")
end
end
end
end)
 
Fir.MouseButton1Down:connect(function()
Found = false
for i, v in pairs(game.Workspace:GetChildren()) do
if v.Name == "TreeRegion" then
for a, b in pairs(v:GetChildren()) do
tree(b, "Fir")
end
end
end
end)
 
Generic.MouseButton1Down:connect(function()
Found = false
for i, v in pairs(game.Workspace:GetChildren()) do
if v.Name == "TreeRegion" then
for a, b in pairs(v:GetChildren()) do
tree(b, "Generic")
end
end
end
end)
 
GoldSwampy.MouseButton1Down:connect(function()
Found = false
for i, v in pairs(game.Workspace:GetChildren()) do
if v.Name == "TreeRegion" then
for a, b in pairs(v:GetChildren()) do
tree(b, "GoldSwampy")
end
end
end
end)
 
GreenSwampy.MouseButton1Down:connect(function()
Found = false
for i, v in pairs(game.Workspace:GetChildren()) do
if v.Name == "TreeRegion" then
for a, b in pairs(v:GetChildren()) do
tree(b, "GreenSwampy")
end
end
end
end)
 
Koa.MouseButton1Down:connect(function()
Found = false
for i, v in pairs(game.Workspace:GetChildren()) do
if v.Name == "TreeRegion" then
for a, b in pairs(v:GetChildren()) do
tree(b, "Koa")
end
end
end
end)
 
LoneCave.MouseButton1Down:connect(function()
Found = false
for i, v in pairs(game.Workspace:GetChildren()) do
if v.Name == "TreeRegion" then
for a, b in pairs(v:GetChildren()) do
tree(b, "LoneCave")
end
end
end
end)
 
Oak.MouseButton1Down:connect(function()
Found = false
for i, v in pairs(game.Workspace:GetChildren()) do
if v.Name == "TreeRegion" then
for a, b in pairs(v:GetChildren()) do
tree(b, "Oak")
end
end
end
end)
 
Palm.MouseButton1Down:connect(function()
Found = false
for i, v in pairs(game.Workspace:GetChildren()) do
if v.Name == "TreeRegion" then
for a, b in pairs(v:GetChildren()) do
tree(b, "Palm")
end
end
end
end)
 
Pine.MouseButton1Down:connect(function()
Found = false
for i, v in pairs(game.Workspace:GetChildren()) do
if v.Name == "TreeRegion" then
for a, b in pairs(v:GetChildren()) do
tree(b, "Pine")
end
end
end
end)
 
Volcano.MouseButton1Down:connect(function()
Found = false
for i, v in pairs(game.Workspace:GetChildren()) do
if v.Name == "TreeRegion" then
for a, b in pairs(v:GetChildren()) do
tree(b, "Volcano")
end
end
end
end)
 
Walnut.MouseButton1Down:connect(function()
Found = false
for i, v in pairs(game.Workspace:GetChildren()) do
if v.Name == "TreeRegion" then
for a, b in pairs(v:GetChildren()) do
tree(b, "Walnut")
end
end
end
end)
 
-- end --
 
-- Tab3 Buttons --
Birch2 = Instance.new("TextButton")
CaveCrawler2 = Instance.new("TextButton")
Cherry2 = Instance.new("TextButton")
Fir2 = Instance.new("TextButton")
Generic2 = Instance.new("TextButton")
GoldSwampy2 = Instance.new("TextButton")
GreenSwampy2 = Instance.new("TextButton")
Koa2 = Instance.new("TextButton")
LoneCave2 = Instance.new("TextButton")
Oak2 = Instance.new("TextButton")
Palm2 = Instance.new("TextButton")
Pine2 = Instance.new("TextButton")
Volcano2 = Instance.new("TextButton")
Walnut2 = Instance.new("TextButton")
 
Birch2.Name = "Birch"
Birch2.Parent = TTab3
Birch2.BackgroundColor3 = Color3.new(1, 1, 0)
Birch2.Position = UDim2.new(0, 1, 0, 1)
Birch2.Size = UDim2.new(0,70, 0, 25)
Birch2.Font = Enum.Font.Cartoon
Birch2.FontSize = Enum.FontSize.Size14
Birch2.Text = "Birch"
Birch2.TextSize = 14
 
CaveCrawler2.Name = "CaveCrawler"
CaveCrawler2.Parent = TTab3
CaveCrawler2.BackgroundColor3 = Color3.new(1, 1, 0)
CaveCrawler2.Position = UDim2.new(0, 71, 0, 1)
CaveCrawler2.Size = UDim2.new(0,70, 0, 25)
CaveCrawler2.Font = Enum.Font.Cartoon
CaveCrawler2.FontSize = Enum.FontSize.Size14
CaveCrawler2.Text = "CaveCrawler"
CaveCrawler2.TextSize = 14
 
Cherry2.Name = "Cherry"
Cherry2.Parent = TTab3
Cherry2.BackgroundColor3 = Color3.new(1, 1, 0)
Cherry2.Position = UDim2.new(0, 141, 0, 1)
Cherry2.Size = UDim2.new(0,70, 0, 25)
Cherry2.Font = Enum.Font.Cartoon
Cherry2.FontSize = Enum.FontSize.Size14
Cherry2.Text = "Cherry"
Cherry2.TextSize = 14
 
Fir2.Name = "Fir"
Fir2.Parent = TTab3
Fir2.BackgroundColor3 = Color3.new(1, 1, 0)
Fir2.Position = UDim2.new(0, 211, 0, 1)
Fir2.Size = UDim2.new(0,70, 0, 25)
Fir2.Font = Enum.Font.Cartoon
Fir2.FontSize = Enum.FontSize.Size14
Fir2.Text = "Fir"
Fir2.TextSize = 14
 
Generic2.Name = "Generic"
Generic2.Parent = TTab3
Generic2.BackgroundColor3 = Color3.new(1, 1, 0)
Generic2.Position = UDim2.new(0, 1, 0, 26)
Generic2.Size = UDim2.new(0,70, 0, 25)
Generic2.Font = Enum.Font.Cartoon
Generic2.FontSize = Enum.FontSize.Size14
Generic2.Text = "Generic"
Generic2.TextSize = 14
 
GoldSwampy2.Name = "GoldSwampy"
GoldSwampy2.Parent = TTab3
GoldSwampy2.BackgroundColor3 = Color3.new(1, 1, 0)
GoldSwampy2.Position = UDim2.new(0, 71, 0, 26)
GoldSwampy2.Size = UDim2.new(0,70, 0, 25)
GoldSwampy2.Font = Enum.Font.Cartoon
GoldSwampy2.FontSize = Enum.FontSize.Size14
GoldSwampy2.Text = "Gold"
GoldSwampy2.TextSize = 14
 
GreenSwampy2.Name = "GreenSwampy"
GreenSwampy2.Parent = TTab3
GreenSwampy2.BackgroundColor3 = Color3.new(1, 1, 0)
GreenSwampy2.Position = UDim2.new(0, 141, 0, 26)
GreenSwampy2.Size = UDim2.new(0,70, 0, 25)
GreenSwampy2.Font = Enum.Font.Cartoon
GreenSwampy2.FontSize = Enum.FontSize.Size14
GreenSwampy2.Text = "Green"
GreenSwampy2.TextSize = 14
 
Koa2.Name = "Koa"
Koa2.Parent = TTab3
Koa2.BackgroundColor3 = Color3.new(1, 1, 0)
Koa2.Position = UDim2.new(0, 211, 0, 26)
Koa2.Size = UDim2.new(0,70, 0, 25)
Koa2.Font = Enum.Font.Cartoon
Koa2.FontSize = Enum.FontSize.Size14
Koa2.Text = "Koa"
Koa2.TextSize = 14
 
LoneCave2.Name = "LoneCave"
LoneCave2.Parent = TTab3
LoneCave2.BackgroundColor3 = Color3.new(1, 1, 0)
LoneCave2.Position = UDim2.new(0, 1, 0, 51)
LoneCave2.Size = UDim2.new(0,70, 0, 25)
LoneCave2.Font = Enum.Font.Cartoon
LoneCave2.FontSize = Enum.FontSize.Size14
LoneCave2.Text = "LoneCave"
LoneCave2.TextSize = 14
 
Oak2.Name = "Oak"
Oak2.Parent = TTab3
Oak2.BackgroundColor3 = Color3.new(1, 1, 0)
Oak2.Position = UDim2.new(0, 71, 0, 51)
Oak2.Size = UDim2.new(0,70, 0, 25)
Oak2.Font = Enum.Font.Cartoon
Oak2.FontSize = Enum.FontSize.Size14
Oak2.Text = "Oak"
Oak2.TextSize = 14
 
Palm2.Name = "Palm"
Palm2.Parent = TTab3
Palm2.BackgroundColor3 = Color3.new(1, 1, 0)
Palm2.Position = UDim2.new(0, 141, 0, 51)
Palm2.Size = UDim2.new(0,70, 0, 25)
Palm2.Font = Enum.Font.Cartoon
Palm2.FontSize = Enum.FontSize.Size14
Palm2.Text = "Palm"
Palm2.TextSize = 14
 
Pine2.Name = "Pine"
Pine2.Parent = TTab3
Pine2.BackgroundColor3 = Color3.new(1, 1, 0)
Pine2.Position = UDim2.new(0, 211, 0, 51)
Pine2.Size = UDim2.new(0,70, 0, 25)
Pine2.Font = Enum.Font.Cartoon
Pine2.FontSize = Enum.FontSize.Size14
Pine2.Text = "Pine"
Pine2.TextSize = 14
 
Volcano2.Name = "Volcano"
Volcano2.Parent = TTab3
Volcano2.BackgroundColor3 = Color3.new(1, 1, 0)
Volcano2.Position = UDim2.new(0, 1, 0, 76)
Volcano2.Size = UDim2.new(0,70, 0, 25)
Volcano2.Font = Enum.Font.Cartoon
Volcano2.FontSize = Enum.FontSize.Size14
Volcano2.Text = "Volcano"
Volcano2.TextSize = 14
 
Walnut2.Name = "Walnut"
Walnut2.Parent = TTab3
Walnut2.BackgroundColor3 = Color3.new(1, 1, 0)
Walnut2.Position = UDim2.new(0, 71, 0, 76)
Walnut2.Size = UDim2.new(0,70, 0, 25)
Walnut2.Font = Enum.Font.Cartoon
Walnut2.FontSize = Enum.FontSize.Size14
Walnut2.Text = "Walnut"
Walnut2.TextSize = 14
 
-- end --
 
-- Tab3 Button Functions --
Birch2.MouseButton1Down:connect(function()
for i, v in pairs(game.Workspace.LogModels:GetChildren()) do
cut(v, "Birch")
end
end)
 
CaveCrawler2.MouseButton1Down:connect(function()
for i, v in pairs(game.Workspace.LogModels:GetChildren()) do
cut(v, "CaveCrawler")
end
end)
 
Cherry2.MouseButton1Down:connect(function()
for i, v in pairs(game.Workspace.LogModels:GetChildren()) do
cut(v, "Cherry")
end
end)
 
Fir2.MouseButton1Down:connect(function()
for i, v in pairs(game.Workspace.LogModels:GetChildren()) do
cut(v, "Fir")
end
end)
 
Generic2.MouseButton1Down:connect(function()
for i, v in pairs(game.Workspace.LogModels:GetChildren()) do
cut(v, "Generic")
end
end)
 
GoldSwampy2.MouseButton1Down:connect(function()
for i, v in pairs(game.Workspace.LogModels:GetChildren()) do
cut(v, "GoldSwampy")
end
end)
 
GreenSwampy2.MouseButton1Down:connect(function()
for i, v in pairs(game.Workspace.LogModels:GetChildren()) do
cut(v, "GreenSwampy")
end
end)
 
Koa2.MouseButton1Down:connect(function()
for i, v in pairs(game.Workspace.LogModels:GetChildren()) do
cut(v, "Koa")
end
end)
 
LoneCave2.MouseButton1Down:connect(function()
for i, v in pairs(game.Workspace.LogModels:GetChildren()) do
cut(v, "LoneCave")
end
end)
 
Oak2.MouseButton1Down:connect(function()
for i, v in pairs(game.Workspace.LogModels:GetChildren()) do
cut(v, "Oak")
end
end)
 
Palm2.MouseButton1Down:connect(function()
for i, v in pairs(game.Workspace.LogModels:GetChildren()) do
cut(v, "Palm")
end
end)
 
Pine2.MouseButton1Down:connect(function()
for i, v in pairs(game.Workspace.LogModels:GetChildren()) do
cut(v, "Pine")
end
end)
 
Volcano2.MouseButton1Down:connect(function()
for i, v in pairs(game.Workspace.LogModels:GetChildren()) do
cut(v, "Volcano")
end
end)
 
Pine2.MouseButton1Down:connect(function()
for i, v in pairs(game.Workspace.LogModels:GetChildren()) do
cut(v, "Walnut")
end
end)
 
 
-- end --
 
 
-- button function --
Tab1.MouseButton1Down:connect(function()
TTab1.Visible = true
TTab2.Visible = false
TTab3.Visible = false
 
end)
 
Tab2.MouseButton1Down:connect(function()
TTab1.Visible = false
TTab2.Visible = true
TTab3.Visible = false
end)
 
Tab3.MouseButton1Down:connect(function()
TTab1.Visible = false
TTab2.Visible = false
TTab3.Visible = true
end)
 
Close.MouseButton1Down:connect(function()
CGG:remove()
end)
 
departure = game.Workspace.Ferry.TimeToDeparture
game.Workspace.Ferry.TimeToDeparture.Changed:connect(function()
Depart.Text = "Time To Departure: ".. game.Workspace.Ferry.TimeToDeparture.Value
end)
 
Mouse.Button1Up:connect(function()
Down = false
end)
 
Mouse.Button1Down:connect(function()
Down = true
if Tool == "Copy" then
if Mouse.Target ~= nil then
Clone = Mouse.Target:clone()
Clone.Parent = game.Workspace
end
end
 
if Tool == "Delete" then
if Mouse.Target ~= nil then
Mouse.Target:remove()
end
end
 
if Tool == "Move" then
if Mouse.Target ~= nil then
MoveObject = Mouse.Target
end
end
 
wait()
if Clone ~= nil then
Clone.CanCollide = false
repeat
wait()
SubX = Clone.Size.X/2
SubY = Clone.Size.Y/2
SubZ = Clone.Size.Z/2
Clone.Position = Vector3.new(Mouse.Hit.X - SubX, Mouse.Hit.Y - SubY, Mouse.Hit.Z - SubZ)
until Down == false
Clone.CanCollide = true
Clone.Position = Clone.Position + Vector3.new(SubX, SubY, SubZ)
Clone = nil
end
 
if MoveObject ~= nil then
MoveObject.CanCollide = false
repeat
wait()
SubX = MoveObject.Size.X/2
SubY = MoveObject.Size.Y/2
SubZ = MoveObject.Size.Z/2
MoveObject.Position = Vector3.new(Mouse.Hit.X - SubX, Mouse.Hit.Y - SubY, Mouse.Hit.Z - SubZ)
until Down == false
MoveObject.CanCollide = true
MoveObject.Position =  MoveObject.Position + Vector3.new(SubX, SubY, SubZ)
MoveObject= nil
end
end)	
end)
OpenButton.Name = "OpenButton"
OpenButton.Parent = ScreenGui
OpenButton.BackgroundColor3 = Color3.new(0, 0, 0)
OpenButton.BorderColor3 = Color3.new(0, 1, 0)
OpenButton.BorderSizePixel = 2
OpenButton.Position = UDim2.new(0, 0, 0.436289668, 0)
OpenButton.Size = UDim2.new(0, 82, 0, 19)
OpenButton.Visible = false
OpenButton.Font = Enum.Font.SciFi
OpenButton.Text = "OPEN"
OpenButton.TextColor3 = Color3.new(0, 1, 0)
OpenButton.TextScaled = true
OpenButton.TextSize = 14
OpenButton.TextWrapped = true
OpenButton .MouseButton1Click:connect(function()
	MainFrame.Visible = true 
	OpenButton.Visible = false
end)
-- Scripts:
end)

TextButton_2.MouseButton1Down:Connect(function()
-- Instances:
local ColorPicker = Instance.new("ScreenGui")
local ChangeColor = Instance.new("Frame")
local CurrentColor = Instance.new("ImageButton")
local Picker = Instance.new("ScrollingFrame")
local Birch = Instance.new("ImageButton")
local DropShadow = Instance.new("Frame")
local Grey = Instance.new("ImageButton")
local DropShadow_2 = Instance.new("Frame")
local Walnut = Instance.new("ImageButton")
local DropShadow_3 = Instance.new("Frame")
local Generic = Instance.new("ImageButton")
local DropShadow_4 = Instance.new("Frame")
local Oak = Instance.new("ImageButton")
local DropShadow_5 = Instance.new("Frame")
local Pine = Instance.new("ImageButton")
local DropShadow_6 = Instance.new("Frame")
local Palm = Instance.new("ImageButton")
local DropShadow_7 = Instance.new("Frame")
local Cherry = Instance.new("ImageButton")
local DropShadow_8 = Instance.new("Frame")
local Koa = Instance.new("ImageButton")
local DropShadow_9 = Instance.new("Frame")
local Volcano = Instance.new("ImageButton")
local DropShadow_10 = Instance.new("Frame")
local GreenSwampy = Instance.new("ImageButton")
local DropShadow_11 = Instance.new("Frame")
local GoldSwampy = Instance.new("ImageButton")
local DropShadow_12 = Instance.new("Frame")
local GenericSpecial = Instance.new("ImageButton")
local DropShadow_13 = Instance.new("Frame")
local SnowGlow = Instance.new("ImageButton")
local DropShadow_14 = Instance.new("Frame")
local Frost = Instance.new("ImageButton")
local DropShadow_15 = Instance.new("Frame")
local CaveCrawler = Instance.new("ImageButton")
local DropShadow_16 = Instance.new("Frame")
local LoneCave = Instance.new("ImageButton")
local DropShadow_17 = Instance.new("Frame")
local Spooky = Instance.new("ImageButton")
local DropShadow_18 = Instance.new("Frame")
local SpookyNeon = Instance.new("ImageButton")
local DropShadow_19 = Instance.new("Frame")
--Properties:
ColorPicker.Name = "ColorPicker"
ColorPicker.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
 
ChangeColor.Name = "ChangeColor"
ChangeColor.Parent = ColorPicker
ChangeColor.BackgroundColor3 = Color3.new(0.176471, 0.254902, 0.427451)
ChangeColor.BorderColor3 = Color3.new(0, 0, 0)
ChangeColor.BorderSizePixel = 2
ChangeColor.Position = UDim2.new(0, 10, 1, -110)
ChangeColor.Size = UDim2.new(0, 100, 0, 100)
ChangeColor.ZIndex = 2
ColorPicker.Enabled = false
 
CurrentColor.Name = "CurrentColor"
CurrentColor.Parent = ChangeColor
CurrentColor.BackgroundColor3 = Color3.new(0.176471, 0.254902, 0.427451)
CurrentColor.BorderColor3 = Color3.new(0, 0, 0)
CurrentColor.BorderSizePixel = 2
CurrentColor.Position = UDim2.new(0, 10, 0, 10)
CurrentColor.Size = UDim2.new(0, 80, 0, 80)
CurrentColor.ZIndex = 2
CurrentColor.Image = "rbxassetid://2712547918"
CurrentColor.ScaleType = Enum.ScaleType.Crop
 
Picker.Name = "Picker"
Picker.Parent = ColorPicker
Picker.BackgroundColor3 = Color3.new(0.176471, 0.254902, 0.427451)
Picker.BorderColor3 = Color3.new(0, 0, 0)
Picker.BorderSizePixel = 2
Picker.Position = UDim2.new(0, 10, 1, -320)
Picker.Size = UDim2.new(0, 100, 0, 200)
Picker.CanvasPosition = Vector2.new(0, 700)
Picker.CanvasSize = UDim2.new(0, 0, 0, 900)
Picker.ScrollBarThickness = 7
Picker.VerticalScrollBarPosition = Enum.VerticalScrollBarPosition.Left
Picker.Visible = false
 
Birch.Name = "Birch"
Birch.Parent = Picker
Birch.BackgroundColor3 = Color3.new(1, 1, 1)
Birch.BorderColor3 = Color3.new(0, 0, 0)
Birch.Position = UDim2.new(0, 10, 0, 5)
Birch.Size = UDim2.new(0, 80, 0, 40)
Birch.ZIndex = 3
Birch.Image = "rbxassetid://2712547918"
Birch.ScaleType = Enum.ScaleType.Crop
 
DropShadow.Name = "DropShadow"
DropShadow.Parent = Birch
DropShadow.BackgroundColor3 = Color3.new(0, 0, 0)
DropShadow.BorderSizePixel = 0
DropShadow.Position = UDim2.new(0, 4, 0, 4)
DropShadow.Size = UDim2.new(1, 0, 1, 0)
DropShadow.ZIndex = 2
 
Grey.Name = "Grey"
Grey.Parent = Picker
Grey.BackgroundColor3 = Color3.new(1, 1, 1)
Grey.BorderColor3 = Color3.new(0, 0, 0)
Grey.Position = UDim2.new(0, 10, 0, 55)
Grey.Size = UDim2.new(0, 80, 0, 40)
Grey.ZIndex = 3
Grey.Image = "rbxassetid://924320031"
Grey.ScaleType = Enum.ScaleType.Crop
 
DropShadow_2.Name = "DropShadow"
DropShadow_2.Parent = Grey
DropShadow_2.BackgroundColor3 = Color3.new(0, 0, 0)
DropShadow_2.BorderSizePixel = 0
DropShadow_2.Position = UDim2.new(0, 4, 0, 4)
DropShadow_2.Size = UDim2.new(1, 0, 1, 0)
DropShadow_2.ZIndex = 2
 
Walnut.Name = "Walnut"
Walnut.Parent = Picker
Walnut.BackgroundColor3 = Color3.new(1, 1, 1)
Walnut.BorderColor3 = Color3.new(0, 0, 0)
Walnut.Position = UDim2.new(0, 10, 0, 105)
Walnut.Size = UDim2.new(0, 80, 0, 40)
Walnut.ZIndex = 3
Walnut.Image = "rbxassetid://2712559790"
Walnut.ScaleType = Enum.ScaleType.Crop
 
DropShadow_3.Name = "DropShadow"
DropShadow_3.Parent = Walnut
DropShadow_3.BackgroundColor3 = Color3.new(0, 0, 0)
DropShadow_3.BorderSizePixel = 0
DropShadow_3.Position = UDim2.new(0, 4, 0, 4)
DropShadow_3.Size = UDim2.new(1, 0, 1, 0)
DropShadow_3.ZIndex = 2
 
Generic.Name = "Generic"
Generic.Parent = Picker
Generic.BackgroundColor3 = Color3.new(1, 1, 1)
Generic.BorderColor3 = Color3.new(0, 0, 0)
Generic.Position = UDim2.new(0, 10, 0, 155)
Generic.Size = UDim2.new(0, 80, 0, 40)
Generic.ZIndex = 3
Generic.Image = "rbxassetid://2712568624"
Generic.ScaleType = Enum.ScaleType.Crop
 
DropShadow_4.Name = "DropShadow"
DropShadow_4.Parent = Generic
DropShadow_4.BackgroundColor3 = Color3.new(0, 0, 0)
DropShadow_4.BorderSizePixel = 0
DropShadow_4.Position = UDim2.new(0, 4, 0, 4)
DropShadow_4.Size = UDim2.new(1, 0, 1, 0)
DropShadow_4.ZIndex = 2
 
Oak.Name = "Oak"
Oak.Parent = Picker
Oak.BackgroundColor3 = Color3.new(1, 1, 1)
Oak.BorderColor3 = Color3.new(0, 0, 0)
Oak.Position = UDim2.new(0, 10, 0, 205)
Oak.Size = UDim2.new(0, 80, 0, 40)
Oak.ZIndex = 3
Oak.Image = "rbxassetid://2712579185"
Oak.ScaleType = Enum.ScaleType.Crop
 
DropShadow_5.Name = "DropShadow"
DropShadow_5.Parent = Oak
DropShadow_5.BackgroundColor3 = Color3.new(0, 0, 0)
DropShadow_5.BorderSizePixel = 0
DropShadow_5.Position = UDim2.new(0, 4, 0, 4)
DropShadow_5.Size = UDim2.new(1, 0, 1, 0)
DropShadow_5.ZIndex = 2
 
Pine.Name = "Pine"
Pine.Parent = Picker
Pine.BackgroundColor3 = Color3.new(1, 1, 1)
Pine.BorderColor3 = Color3.new(0, 0, 0)
Pine.Position = UDim2.new(0, 10, 0, 255)
Pine.Size = UDim2.new(0, 80, 0, 40)
Pine.ZIndex = 3
Pine.Image = "rbxassetid://2712591183"
Pine.ScaleType = Enum.ScaleType.Crop
 
DropShadow_6.Name = "DropShadow"
DropShadow_6.Parent = Pine
DropShadow_6.BackgroundColor3 = Color3.new(0, 0, 0)
DropShadow_6.BorderSizePixel = 0
DropShadow_6.Position = UDim2.new(0, 4, 0, 4)
DropShadow_6.Size = UDim2.new(1, 0, 1, 0)
DropShadow_6.ZIndex = 2
 
Palm.Name = "Palm"
Palm.Parent = Picker
Palm.BackgroundColor3 = Color3.new(1, 1, 1)
Palm.BorderColor3 = Color3.new(0, 0, 0)
Palm.Position = UDim2.new(0, 10, 0, 305)
Palm.Size = UDim2.new(0, 80, 0, 40)
Palm.ZIndex = 3
Palm.Image = "rbxassetid://2712597395"
Palm.ScaleType = Enum.ScaleType.Crop
 
DropShadow_7.Name = "DropShadow"
DropShadow_7.Parent = Palm
DropShadow_7.BackgroundColor3 = Color3.new(0, 0, 0)
DropShadow_7.BorderSizePixel = 0
DropShadow_7.Position = UDim2.new(0, 4, 0, 4)
DropShadow_7.Size = UDim2.new(1, 0, 1, 0)
DropShadow_7.ZIndex = 2
 
Cherry.Name = "Cherry"
Cherry.Parent = Picker
Cherry.BackgroundColor3 = Color3.new(1, 1, 1)
Cherry.BorderColor3 = Color3.new(0, 0, 0)
Cherry.Position = UDim2.new(0, 10, 0, 355)
Cherry.Size = UDim2.new(0, 80, 0, 40)
Cherry.ZIndex = 3
Cherry.Image = "rbxassetid://2712608599"
Cherry.ScaleType = Enum.ScaleType.Crop
 
DropShadow_8.Name = "DropShadow"
DropShadow_8.Parent = Cherry
DropShadow_8.BackgroundColor3 = Color3.new(0, 0, 0)
DropShadow_8.BorderSizePixel = 0
DropShadow_8.Position = UDim2.new(0, 4, 0, 4)
DropShadow_8.Size = UDim2.new(1, 0, 1, 0)
DropShadow_8.ZIndex = 2
 
Koa.Name = "Koa"
Koa.Parent = Picker
Koa.BackgroundColor3 = Color3.new(1, 1, 1)
Koa.BorderColor3 = Color3.new(0, 0, 0)
Koa.Position = UDim2.new(0, 10, 0, 355)
Koa.Size = UDim2.new(0, 80, 0, 40)
Koa.ZIndex = 3
Koa.Image = "rbxassetid://2712612798"
Koa.ScaleType = Enum.ScaleType.Crop
 
DropShadow_9.Name = "DropShadow"
DropShadow_9.Parent = Koa
DropShadow_9.BackgroundColor3 = Color3.new(0, 0, 0)
DropShadow_9.BorderSizePixel = 0
DropShadow_9.Position = UDim2.new(0, 4, 0, 4)
DropShadow_9.Size = UDim2.new(1, 0, 1, 0)
DropShadow_9.ZIndex = 2
 
Volcano.Name = "Volcano"
Volcano.Parent = Picker
Volcano.BackgroundColor3 = Color3.new(1, 1, 1)
Volcano.BorderColor3 = Color3.new(0, 0, 0)
Volcano.Position = UDim2.new(0, 10, 0, 405)
Volcano.Size = UDim2.new(0, 80, 0, 40)
Volcano.ZIndex = 3
Volcano.Image = "rbxassetid://2712618609"
Volcano.ScaleType = Enum.ScaleType.Crop
 
DropShadow_10.Name = "DropShadow"
DropShadow_10.Parent = Volcano
DropShadow_10.BackgroundColor3 = Color3.new(0, 0, 0)
DropShadow_10.BorderSizePixel = 0
DropShadow_10.Position = UDim2.new(0, 4, 0, 4)
DropShadow_10.Size = UDim2.new(1, 0, 1, 0)
DropShadow_10.ZIndex = 2
 
GreenSwampy.Name = "GreenSwampy"
GreenSwampy.Parent = Picker
GreenSwampy.BackgroundColor3 = Color3.new(1, 1, 1)
GreenSwampy.BorderColor3 = Color3.new(0, 0, 0)
GreenSwampy.Position = UDim2.new(0, 10, 0, 455)
GreenSwampy.Size = UDim2.new(0, 80, 0, 40)
GreenSwampy.ZIndex = 3
GreenSwampy.Image = "rbxassetid://2712623896"
GreenSwampy.ScaleType = Enum.ScaleType.Crop
 
DropShadow_11.Name = "DropShadow"
DropShadow_11.Parent = GreenSwampy
DropShadow_11.BackgroundColor3 = Color3.new(0, 0, 0)
DropShadow_11.BorderSizePixel = 0
DropShadow_11.Position = UDim2.new(0, 4, 0, 4)
DropShadow_11.Size = UDim2.new(1, 0, 1, 0)
DropShadow_11.ZIndex = 2
 
GoldSwampy.Name = "GoldSwampy"
GoldSwampy.Parent = Picker
GoldSwampy.BackgroundColor3 = Color3.new(1, 1, 1)
GoldSwampy.BorderColor3 = Color3.new(0, 0, 0)
GoldSwampy.Position = UDim2.new(0, 10, 0, 505)
GoldSwampy.Size = UDim2.new(0, 80, 0, 40)
GoldSwampy.ZIndex = 3
GoldSwampy.Image = "rbxassetid://2712631457"
GoldSwampy.ScaleType = Enum.ScaleType.Crop
 
DropShadow_12.Name = "DropShadow"
DropShadow_12.Parent = GoldSwampy
DropShadow_12.BackgroundColor3 = Color3.new(0, 0, 0)
DropShadow_12.BorderSizePixel = 0
DropShadow_12.Position = UDim2.new(0, 4, 0, 4)
DropShadow_12.Size = UDim2.new(1, 0, 1, 0)
DropShadow_12.ZIndex = 2
 
GenericSpecial.Name = "GenericSpecial"
GenericSpecial.Parent = Picker
GenericSpecial.BackgroundColor3 = Color3.new(1, 1, 1)
GenericSpecial.BorderColor3 = Color3.new(0, 0, 0)
GenericSpecial.Position = UDim2.new(0, 10, 0, 555)
GenericSpecial.Size = UDim2.new(0, 80, 0, 40)
GenericSpecial.ZIndex = 3
GenericSpecial.Image = "rbxassetid://2712639396"
GenericSpecial.ScaleType = Enum.ScaleType.Crop
 
DropShadow_13.Name = "DropShadow"
DropShadow_13.Parent = GenericSpecial
DropShadow_13.BackgroundColor3 = Color3.new(0, 0, 0)
DropShadow_13.BorderSizePixel = 0
DropShadow_13.Position = UDim2.new(0, 4, 0, 4)
DropShadow_13.Size = UDim2.new(1, 0, 1, 0)
DropShadow_13.ZIndex = 2
 
SnowGlow.Name = "SnowGlow"
SnowGlow.Parent = Picker
SnowGlow.BackgroundColor3 = Color3.new(1, 1, 1)
SnowGlow.BorderColor3 = Color3.new(0, 0, 0)
SnowGlow.Position = UDim2.new(0, 10, 0, 605)
SnowGlow.Size = UDim2.new(0, 80, 0, 40)
SnowGlow.ZIndex = 3
SnowGlow.Image = "rbxassetid://2712651454"
SnowGlow.ScaleType = Enum.ScaleType.Crop
 
DropShadow_14.Name = "DropShadow"
DropShadow_14.Parent = SnowGlow
DropShadow_14.BackgroundColor3 = Color3.new(0, 0, 0)
DropShadow_14.BorderSizePixel = 0
DropShadow_14.Position = UDim2.new(0, 4, 0, 4)
DropShadow_14.Size = UDim2.new(1, 0, 1, 0)
DropShadow_14.ZIndex = 2
 
Frost.Name = "Frost"
Frost.Parent = Picker
Frost.BackgroundColor3 = Color3.new(1, 1, 1)
Frost.BorderColor3 = Color3.new(0, 0, 0)
Frost.Position = UDim2.new(0, 10, 0, 655)
Frost.Size = UDim2.new(0, 80, 0, 40)
Frost.ZIndex = 3
Frost.Image = "rbxassetid://2712667804"
Frost.ScaleType = Enum.ScaleType.Crop
 
DropShadow_15.Name = "DropShadow"
DropShadow_15.Parent = Frost
DropShadow_15.BackgroundColor3 = Color3.new(0, 0, 0)
DropShadow_15.BorderSizePixel = 0
DropShadow_15.Position = UDim2.new(0, 4, 0, 4)
DropShadow_15.Size = UDim2.new(1, 0, 1, 0)
DropShadow_15.ZIndex = 2
 
CaveCrawler.Name = "CaveCrawler"
CaveCrawler.Parent = Picker
CaveCrawler.BackgroundColor3 = Color3.new(1, 1, 1)
CaveCrawler.BorderColor3 = Color3.new(0, 0, 0)
CaveCrawler.Position = UDim2.new(0, 10, 0, 705)
CaveCrawler.Size = UDim2.new(0, 80, 0, 40)
CaveCrawler.ZIndex = 3
CaveCrawler.Image = "rbxassetid://2712673980"
CaveCrawler.ScaleType = Enum.ScaleType.Crop
 
DropShadow_16.Name = "DropShadow"
DropShadow_16.Parent = CaveCrawler
DropShadow_16.BackgroundColor3 = Color3.new(0, 0, 0)
DropShadow_16.BorderSizePixel = 0
DropShadow_16.Position = UDim2.new(0, 4, 0, 4)
DropShadow_16.Size = UDim2.new(1, 0, 1, 0)
DropShadow_16.ZIndex = 2
 
LoneCave.Name = "LoneCave"
LoneCave.Parent = Picker
LoneCave.BackgroundColor3 = Color3.new(1, 1, 1)
LoneCave.BorderColor3 = Color3.new(0, 0, 0)
LoneCave.Position = UDim2.new(0, 10, 0, 755)
LoneCave.Size = UDim2.new(0, 80, 0, 40)
LoneCave.ZIndex = 3
LoneCave.Image = "rbxassetid://2712693147"
LoneCave.ScaleType = Enum.ScaleType.Crop
 
DropShadow_17.Name = "DropShadow"
DropShadow_17.Parent = LoneCave
DropShadow_17.BackgroundColor3 = Color3.new(0, 0, 0)
DropShadow_17.BorderSizePixel = 0
DropShadow_17.Position = UDim2.new(0, 4, 0, 4)
DropShadow_17.Size = UDim2.new(1, 0, 1, 0)
DropShadow_17.ZIndex = 2
 
Spooky.Name = "Spooky"
Spooky.Parent = Picker
Spooky.BackgroundColor3 = Color3.new(1, 1, 1)
Spooky.BorderColor3 = Color3.new(0, 0, 0)
Spooky.Position = UDim2.new(0, 10, 0, 805)
Spooky.Size = UDim2.new(0, 80, 0, 40)
Spooky.ZIndex = 3
Spooky.Image = "rbxassetid://2712696822"
Spooky.ScaleType = Enum.ScaleType.Crop
 
DropShadow_18.Name = "DropShadow"
DropShadow_18.Parent = Spooky
DropShadow_18.BackgroundColor3 = Color3.new(0, 0, 0)
DropShadow_18.BorderSizePixel = 0
DropShadow_18.Position = UDim2.new(0, 4, 0, 4)
DropShadow_18.Size = UDim2.new(1, 0, 1, 0)
DropShadow_18.ZIndex = 2
 
SpookyNeon.Name = "SpookyNeon"
SpookyNeon.Parent = Picker
SpookyNeon.BackgroundColor3 = Color3.new(1, 1, 1)
SpookyNeon.BorderColor3 = Color3.new(0, 0, 0)
SpookyNeon.Position = UDim2.new(0, 10, 0, 855)
SpookyNeon.Size = UDim2.new(0, 80, 0, 40)
SpookyNeon.ZIndex = 3
SpookyNeon.Image = "rbxassetid://2712700047"
SpookyNeon.ScaleType = Enum.ScaleType.Crop
 
DropShadow_19.Name = "DropShadow"
DropShadow_19.Parent = SpookyNeon
DropShadow_19.BackgroundColor3 = Color3.new(0, 0, 0)
DropShadow_19.BorderSizePixel = 0
DropShadow_19.Position = UDim2.new(0, 4, 0, 4)
DropShadow_19.Size = UDim2.new(1, 0, 1, 0)
DropShadow_19.ZIndex = 2
-- Scripts:
woodtype = "Birch"
 
local tool = Instance.new("Tool", game.Players.LocalPlayer.Backpack)
tool.RequiresHandle = false
--tool.RobloxLocked = true
tool.Name = "Paint"
tool.ToolTip = "Changes A Stucture's Wood Type"
tool.Equipped:connect(function(Mouse)
ColorPicker.Enabled = true
Mouse.Button1Down:connect(function()
if Mouse.Target.Parent:FindFirstChild("Type") or Mouse.Target.Parent:FindFirstChild("BlueprintWoodClass") then
local Cframe
if Mouse.Target.Parent:FindFirstChild("MainCFrame") then
Cframe = Mouse.Target.Parent.MainCFrame.Value
else
Cframe = Mouse.Target.Parent.PrimaryPart.CFrame
end
if Mouse.Target.Parent ~= nil then
game.ReplicatedStorage.PlaceStructure.ClientPlacedStructure:FireServer(Mouse.Target.Parent.ItemName.Value, Cframe, game.Players.LocalPlayer, woodtype, Mouse.Target.Parent, false)
end
else
--do nothing
end
end)
end)
 
tool.Unequipped:connect(function(mouse)
ColorPicker.Enabled = false
end)
 
 
Birch.MouseButton1Click:Connect(function()
CurrentColor.Image = Birch.Image
woodtype = "Birch"
end)
 
Grey.MouseButton1Click:Connect(function()
CurrentColor.Image = Grey.Image
woodtype = nil
end)
 
Walnut.MouseButton1Click:Connect(function()
CurrentColor.Image = Walnut.Image
woodtype = "Walnut"
end)
 
Generic.MouseButton1Click:Connect(function()
CurrentColor.Image = Generic.Image
woodtype = "Generic"
end)
 
Oak.MouseButton1Click:Connect(function()
CurrentColor.Image = Oak.Image
woodtype = "Oak"
end)
 
Pine.MouseButton1Click:Connect(function()
CurrentColor.Image = Pine.Image
woodtype = "Pine"
end)
 
Palm.MouseButton1Click:Connect(function()
CurrentColor.Image = Palm.Image
woodtype = "Palm"
end)
 
Koa.MouseButton1Click:Connect(function()
CurrentColor.Image = Koa.Image
woodtype = "Koa"
end)
 
Volcano.MouseButton1Click:Connect(function()
CurrentColor.Image = Volcano.Image
woodtype = "Volcano"
end)
 
GreenSwampy.MouseButton1Click:Connect(function()
CurrentColor.Image = GreenSwampy.Image
woodtype = "GreenSwampy"
end)
 
GoldSwampy.MouseButton1Click:Connect(function()
CurrentColor.Image = GoldSwampy.Image
woodtype = "GoldSwampy"
end)
 
GenericSpecial.MouseButton1Click:Connect(function()
CurrentColor.Image = GenericSpecial.Image
woodtype = "GenericSpecial"
end)
 
SnowGlow.MouseButton1Click:Connect(function()
CurrentColor.Image = SnowGlow.Image
woodtype = "SnowGlow"
end)
 
Frost.MouseButton1Click:Connect(function()
CurrentColor.Image = Frost.Image
woodtype = "Frost"
end)
 
CaveCrawler.MouseButton1Click:Connect(function()
CurrentColor.Image = CaveCrawler.Image
woodtype = "CaveCrawler"
end)
 
LoneCave.MouseButton1Click:Connect(function()
CurrentColor.Image = LoneCave.Image
woodtype = "LoneCave"
end)
 
Spooky.MouseButton1Click:Connect(function()
CurrentColor.Image = Spooky.Image
woodtype = "Spooky"
end)
 
SpookyNeon.MouseButton1Click:Connect(function()
CurrentColor.Image = SpookyNeon.Image
woodtype = "SpookyNeon"
end)
 
--bring up menu
CurrentColor.MouseButton1Click:Connect(function()
if Picker.Visible == false then
Picker.Visible = true
else
Picker.Visible = false
end
end)
end)
TextButton.MouseButton1Down:Connect(function()
for i, v in pairs(game.Workspace.PlayerModels:GetChildren()) do
if v:FindFirstChild("Owner") and v.Owner.Value ~= nil and v.Owner.Value == game.Players[game.Players.LocalPlayer.Name] and v:FindFirstChild("ItemName") and v:FindFirstChild("Type") and (v.PrimaryPart ~= nil or v:FindFirstChild("MainCFrame")) then
game.ReplicatedStorage.Interaction.DestroyStructure:FireServer(v)
end
end
end)

MainC.MouseButton1Down:Connect(function()
plr = NSP1.Text
pes = NSP2.Text
pmds = game.Workspace.PlayerModels
PlaceR = game.ReplicatedStorage.PlaceStructure.ClientPlacedBlueprint
PlaceS = game.ReplicatedStorage.PlaceStructure.ClientPlacedStructure
Property = nil
MProperty = nil
 
for i, v in pairs(game.Workspace.Properties:GetChildren()) do
if v:FindFirstChild("Owner") and v.Owner.Value ~= nil and v.Owner.Value == game.Players[plr] then
Property = v.OriginSquare
end
end
 
for i, v in pairs(game.Workspace.Properties:GetChildren()) do
if v:FindFirstChild("Owner") and v.Owner.Value ~= nil and v.Owner.Value == game.Players[pes] then
MProperty = v.OriginSquare
end
end
 
 
function copypart(mod)
if mod:FindFirstChild("MainCFrame") then
Cframe = mod.MainCFrame.Value
else
Cframe = mod.PrimaryPart.CFrame
end
X = Property.Position.X - Cframe.X
Y = Property.Position.Y - Cframe.Y
Z = Property.Position.Z - Cframe.Z
PlaceR:FireServer(mod.ItemName.Value, (CFrame.new(MProperty.Position.X, MProperty.Position.Y, MProperty.Position.Z)*CFrame.Angles(Cframe:toEulerAnglesXYZ())) - Vector3.new(X, Y, Z), game.Players.LocalPlayer)
wait()
end
 
 
 
for i, v in pairs(pmds:GetChildren()) do
if v:FindFirstChild("Owner") and v.Owner.Value ~= nil and v.Owner.Value == game.Players[plr] and v:FindFirstChild("ItemName") and v:FindFirstChild("Type") and (v.PrimaryPart ~= nil or v:FindFirstChild("MainCFrame")) then
copypart(v)
end
end
wait(.1)
if CopyBase.Text ~= nil then
    CopyBase.Visible = true
end
end)

MaxLand.MouseButton1Down:Connect(function()
for i, v in pairs(game:GetService("Workspace").Properties:GetChildren()) do
        if v:FindFirstChild("Owner") and v.Owner.Value == game.Players.LocalPlayer then
            base = v
            square = v.OriginSquare
            end
        end
    function makebase(pos)
        local Event = game:GetService("ReplicatedStorage").PropertyPurchasing.ClientExpandedProperty
        Event:FireServer(base, pos)
        end
    spos = square.Position
    makebase(CFrame.new(spos.X + 40, spos.Y, spos.Z))
    makebase(CFrame.new(spos.X - 40, spos.Y, spos.Z))
    makebase(CFrame.new(spos.X, spos.Y, spos.Z + 40))
    makebase(CFrame.new(spos.X, spos.Y, spos.Z - 40))
    makebase(CFrame.new(spos.X + 40, spos.Y, spos.Z + 40))
    makebase(CFrame.new(spos.X + 40, spos.Y, spos.Z - 40))
    makebase(CFrame.new(spos.X - 40, spos.Y, spos.Z + 40))
    makebase(CFrame.new(spos.X - 40, spos.Y, spos.Z - 40))
    makebase(CFrame.new(spos.X + 80, spos.Y, spos.Z))
    makebase(CFrame.new(spos.X - 80, spos.Y, spos.Z))
    makebase(CFrame.new(spos.X, spos.Y, spos.Z + 80))
    makebase(CFrame.new(spos.X, spos.Y, spos.Z - 80))
--Corners--
    makebase(CFrame.new(spos.X + 80, spos.Y, spos.Z + 80))
    makebase(CFrame.new(spos.X + 80, spos.Y, spos.Z - 80))
    makebase(CFrame.new(spos.X - 80, spos.Y, spos.Z + 80))
    makebase(CFrame.new(spos.X - 80, spos.Y, spos.Z - 80))
--Corners--
    makebase(CFrame.new(spos.X + 40, spos.Y, spos.Z + 80))
    makebase(CFrame.new(spos.X - 40, spos.Y, spos.Z + 80))
    makebase(CFrame.new(spos.X + 80, spos.Y, spos.Z + 40))
    makebase(CFrame.new(spos.X + 80, spos.Y, spos.Z - 40))
    makebase(CFrame.new(spos.X - 80, spos.Y, spos.Z + 40))
    makebase(CFrame.new(spos.X - 80, spos.Y, spos.Z - 40))
    makebase(CFrame.new(spos.X + 40, spos.Y, spos.Z - 80))
    makebase(CFrame.new(spos.X - 40, spos.Y, spos.Z - 80))
 
end)

FillAll.MouseButton1Down:Connect(function()
local PlayerName = NSP3.Text

local WoodName = Wood.Text

local ItsCFrame
local Remote = game.ReplicatedStorage.PlaceStructure.ClientPlacedStructure
for i,v in pairs(game.Workspace.PlayerModels:GetChildren()) do
if v:FindFirstChild("Owner") and tostring(v.Owner.Value) == PlayerName then
if v:FindFirstChild("Type") and v.Type.Value == "Blueprint" then
if v:FindFirstChild("MainCFrame") then
ItsCFrame = v.MainCFrame.Value
else
ItsCFrame = v.PrimaryPart.CFrame
end
if v ~= nil then
Remote:FireServer(v.Name, ItsCFrame, game.Players.LocalPlayer, WoodName, v, false)
end
end
end
end
end)
end)
 


 

