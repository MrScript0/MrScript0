-- This GUI made by ! 👑 مستر سكربتات 👑 
-- Instances:
 
local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local TextButton = Instance.new("TextLabel")
local idk = Instance.new("TextButton")
local idk1 = Instance.new("TextButton")
local idk2 = Instance.new("TextButton")
local idk3 = Instance.new("TextButton")
local idk4 = Instance.new("TextButton")
local idk5 = Instance.new("TextButton")
local idk6 = Instance.new("TextButton")
local idk7 = Instance.new("TextButton")
local idk8 = Instance.new("TextButton")
local idk9 = Instance.new("TextButton")
local idk12 = Instance.new("TextButton")
local idk13 = Instance.new("TextButton")
local idk14 = Instance.new("TextButton")
local close = Instance.new("TextButton")
 
--Properties:
 
ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ResetOnSpawn = false
 
Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(183, 101, 255)
Frame.Position = UDim2.new(0.369825214, 0, 0.423832893, 0)
Frame.Size = UDim2.new(0, 350, 0, 250)
Frame.Active = true
Frame.Draggable = true
 
 
TextButton.Parent = Frame
TextButton.BackgroundColor3 = Color3.fromRGB(125, 102, 255)
TextButton.Position = UDim2.new(0.01, 0, 0.00832893, 0)
TextButton.Size = UDim2.new(0, 303, 0, 35)
TextButton.Font = Enum.Font.Cartoon
TextButton.Text = "👑 مستر سكربتات 👑"
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextSize = 40.000
 
idk.Parent = Frame
idk.BackgroundColor3 = Color3.fromRGB(125, 102, 255)
idk.Position = UDim2.new(0.01, 0, 0.2, 0)
idk.Size = UDim2.new(0, 94, 0, 35)
idk.Font = Enum.Font.Cartoon
idk.Text = "👑✈️ طيران ✈️👑"
idk.TextColor3 = Color3.fromRGB(0, 0, 0)
idk.TextSize = 20.000
idk.MouseButton1Down:connect(function()
loadstring(game:HttpGet("https://pastebin.com/raw/TinK2zh7"))()
end)
 
idk1.Parent = Frame
idk1.BackgroundColor3 = Color3.fromRGB(125, 102, 255)
idk1.Position = UDim2.new(0.01, 0, 0.4, 0)
idk1.Size = UDim2.new(0, 94, 0, 35)
idk1.Font = Enum.Font.Cartoon
idk1.Text = "👑👻اختفاء👑👻"
idk1.TextColor3 = Color3.fromRGB(0, 0, 0)
idk1.TextSize = 20.000
idk1.MouseButton1Down:connect(function()
loadstring(game:HttpGet('https://pastebin.com/raw/AYtzGEPb'))()
end)
 
idk2.Parent = Frame
idk2.BackgroundColor3 = Color3.fromRGB(125, 102, 255)
idk2.Position = UDim2.new(0.34, 0, 0.4, 0)
idk2.Size = UDim2.new(0, 94, 0, 35)
idk2.Font = Enum.Font.Cartoon
idk2.Text = "👑💃 رقصات 💃👑"
idk2.TextColor3 = Color3.fromRGB(0, 0, 0)
idk2.TextSize = 20.00
idk2.MouseButton1Down:connect(function()
loadstring(game:HttpGet("https://pastebin.com/raw/eCpipCTH"))()
end)
 
idk3.Parent = Frame
idk3.BackgroundColor3 = Color3.fromRGB(125, 102, 255)
idk3.Position = UDim2.new(0.34, 0, 0.2, 0)
idk3.Size = UDim2.new(0, 94, 0, 35)
idk3.Font = Enum.Font.Cartoon
idk3.Text = "👑🔐 ادمن 🔐👑"
idk3.TextColor3 = Color3.fromRGB(0, 0, 0)
idk3.TextSize = 20.000
idk3.MouseButton1Down:connect(function()
defaultsettings = {
	prefix = ';';
	StayOpen = false;
	keepIY = true;
	logsEnabled = false;
	jLogsEnabled = false;
	aliases = {};
	binds = {};
	WayPoints = {};
	PluginsTable = {};
}
 
defaults = game:GetService("HttpService"):JSONEncode(defaultsettings)
 
writefile("IY_FE.iy",defaults)
 
 
loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
end)
 
idk4.Parent = F
idk4.BackgroundColor3 = Color3.fromRGB(125, 102, 255)
idk4.Position = UDim2.new(0.69, 0, 0.2, 0)
idk4.Size = UDim2.new(0, 94, 0, 35)
idk4.Font = Enum.Font.Cartoon
idk4.Text = "👑🚶‍♂️مشيات🚶‍♂️👑"
idk4.TextColor3 = Color3.fromRGB(0, 0, 0)
idk4.TextSize = 20.000
idk4.MouseButton1Down:connect(function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/GamingScripter/Animation-Hub/main/Animation%20Gui", true))()
end)
 
idk5.Parent = Frame
idk5.BackgroundColor3 = Color3.fromRGB(125, 102, 255)
idk5.Position = UDim2.new(0.69, 0, 0.4, 0)
idk5.Size = UDim2.new(0, 94, 0, 35)
idk5.Font = Enum.Font.Cartoon
idk5.Text = "👑🦉 ايم بوت 🦉👑"
idk5.TextColor3 = Color3.fromRGB(0, 0, 0)
idk5.TextSize = 20.000
idk5.MouseButton1Down:connect(function()
loadstring(game:HttpGet("https://pastebin.com/raw/1Gp9c57U"))()
end)
 
idk6.Parent = Frame
idk6.BackgroundColor3 = Color3.fromRGB(125, 102, 255)
idk6.Position = UDim2.new(0.69, 0, 0.8, 0)
idk6.Size = UDim2.new(0, 94, 0, 35)
idk6.Font = Enum.Font.Cartoon
idk6.Text = "👑☠️hitbox👑☠️"
idk6.TextColor3 = Color3.fromRGB(0, 0, 0)
idk6.TextSize = 20.000
idk6.MouseButton1Down:connect(function() 
_G.HeadSize = 10
_G.Disabled = true
 
game:GetService('RunService').RenderStepped:connect(function()
if _G.Disabled then
for i,v in next, game:GetService('Players'):GetPlayers() do
if v.Name ~= game:GetService('Players').LocalPlayer.Name then
pcall(function()
v.Character.HumanoidRootPart.Size = Vector3.new(_G.HeadSize,_G.HeadSize,_G.HeadSize)
v.Character.HumanoidRootPart.Transparency = 0.7
v.Character.HumanoidRootPart.BrickColor = BrickColor.new("Really blue")
v.Character.HumanoidRootPart.Material = "Neon"
v.Character.HumanoidRootPart.CanCollide = false
end)
end
end
end
end)
end)
 
idk7.Parent = Frame
idk7.BackgroundColor3 = Color3.fromRGB(125, 102, 255)
idk7.Position = UDim2.new(0.01, 0, 0.6, 0)
idk7.Size = UDim2.new(0, 94, 0, 35)
idk7.Font = Enum.Font.Cartoon
idk7.Text = "👑🏍️سرعه👑🏍️"
idk7.TextColor3 = Color3.fromRGB(0, 0, 0)
idk7.TextSize = 20.000
idk7.MouseButton1Down:connect(function()
loadstring(game:HttpGet("https://pastebin.com/raw/0m52kRnj"))() 
end)
 
idk8.Parent = Frame
idk8.BackgroundColor3 = Color3.fromRGB(125, 102, 255)
idk8.Position = UDim2.new(0.34, 0, 0.6, 0)
idk8.Size = UDim2.new(0, 94, 0, 35)
idk8.Font = Enum.Font.Cartoon
idk8.Text = "👑🚶‍♂️مشيات 👑🚶‍♂️"
idk8.TextColor3 = Color3.fromRGB(0, 0, 0)
idk8.TextSize = 20.000
idk8.MouseButton1Down:connect(function()
loadstring(game:HttpGet("https://pastebin.com/raw/QSD1J3Ww"))()
end)
 
 
idk12.Parent = Frame
idk12.BackgroundColor3 = Color3.fromRGB(125, 102, 255)
idk12.Position = UDim2.new(0.69, 0, 0.6, 0)
idk12.Size = UDim2.new(0, 94, 0, 35)
idk12.Font = Enum.Font.Cartoon
idk12.Text = "👑💎Esp👑💎"
idk12.TextColor3 = Color3.fromRGB(0, 0, 0)
idk12.TextSize = 20.000
idk12.MouseButton1Down:connect(function()
local FillColor = Color3.fromRGB(175,25,255)
local DepthMode = "AlwaysOnTop"
local FillTransparency = 0.5
local OutlineColor = Color3.fromRGB(255,255,255)
local OutlineTransparency = 0
 
local CoreGui = game:FindService("CoreGui")
local Players = game:FindService("Players")
local lp = Players.LocalPlayer
local connections = {}
 
local Storage = Instance.new("Folder")
Storage.Parent = CoreGui
Storage.Name = "Highlight_Storage"
 
local function Highlight(plr)
    local Highlight = Instance.new("Highlight")
    Highlight.Name = plr.Name
    Highlight.FillColor = FillColor
    Highlight.DepthMode = DepthMode
    Highlight.FillTransparency = FillTransparency
    Highlight.OutlineColor = OutlineColor
    Highlight.OutlineTransparency = 0
    Highlight.Parent = Storage
 
    local plrchar = plr.Character
    if plrchar then
        Highlight.Adornee = plrchar
    end
 
    connections[plr] = plr.CharacterAdded:Connect(function(char)
        Highlight.Adornee = char
    end)
end
 
Players.PlayerAdded:Connect(Highlight)
for i,v in next, Players:GetPlayers() do
    Highlight(v)
end
 
Players.PlayerRemoving:Connect(function(plr)
    local plrname = plr.Name
    if Storage[plrname] then
        Storage[plrname]:Destroy()
    end
    if connections[plr] then
        connections[plr]:Disconnect()
    end
end)
end)
 
idk13.Parent = Frame
idk13.BackgroundColor3 = Color3.fromRGB(125, 102, 255)
idk13.Position = UDim2.new(0.34, 0, 0.8, 0)
idk13.Size = UDim2.new(0, 94, 0, 35)
idk13.Font = Enum.Font.Cartoon
idk13.Text = "👑🚶مشي فلهواء🚶👑"
idk13.TextColor3 = Color3.fromRGB(0, 0, 0)
idk13.TextSize = 20.000
idk13.MouseButton1Down:connect(function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/GhostPlayer352/Test4/main/Float'))()
end)
 
idk14.Parent = Frame
idk14.BackgroundColor3 = Color3.fromRGB(125, 102, 255)
idk14.Position = UDim2.new(0.01, 0, 0.8, 0)
idk14.Size = UDim2.new(0, 94, 0, 35)
idk14.Font = Enum.Font.Cartoon
idk14.Text = "👑🛂مراقبة الناس👑🛂"
idk14.TextColor3 = Color3.fromRGB(0, 0, 0)
idk14.TextSize = 20.000
idk14.MouseButton1Down:connect(function()
loadstring(game:HttpGet('https://pastebin.com/raw/wyvdb7gr'))()
end)
 
idk9.Parent = Frame
idk9.BackgroundColor3 = Color3.fromRGB(125, 102, 255)
idk9.Position = UDim2.new(0.69, 0, 0.2, 0)
idk9.Size = UDim2.new(0, 94, 0, 35)
idk9.Font = Enum.Font.Cartoon
idk9.Text = "👑🔥 سبام 🔥👑"
idk9.TextColor3 = Color3.fromRGB(0, 0, 0)
idk9.TextSize = 20.000
idk9.MouseButton1Down:connect(function()
 
-- Made By Finn/Cheez/Dark!
 
local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local Frame_2 = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local TextBox = Instance.new("TextBox")
local UICorner_2 = Instance.new("UICorner")
local TextButton = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local UICorner_4 = Instance.new("UICorner")
 
--Properties:
 
ScreenGui.Parent = game.CoreGui
 
Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
Frame.Position = UDim2.new(0.293939382, 0, 0.35603714, 0)
Frame.Size = UDim2.new(0, 223, 0, 141)
Frame.Active = true
 
Frame_2.Parent = Frame
Frame_2.BackgroundColor3 = Color3.fromRGB(47, 49, 59)
Frame_2.Position = UDim2.new(0.0358744413, 0, 0.0496453904, 0)
Frame_2.Size = UDim2.new(0, 208, 0, 126)
 
UICorner.Parent = Frame_2
 
TextBox.Parent = Frame_2
TextBox.BackgroundColor3 = Color3.fromRGB(31, 31, 40)
TextBox.Position = UDim2.new(0.0538115874, 0, 0.112630695, 0)
TextBox.Size = UDim2.new(0, 187, 0, 47)
TextBox.Font = Enum.Font.GothamBold
TextBox.PlaceholderColor3 = Color3.fromRGB(178, 178, 178)
TextBox.PlaceholderText = "Chat Goes Here!"
TextBox.Text = ""
TextBox.TextColor3 = Color3.fromRGB(178, 178, 178)
TextBox.TextSize = 18.000
TextBox.TextWrapped = true
 
UICorner_2.Parent = TextBox
 
TextButton.Parent = Frame_2
TextButton.BackgroundColor3 = Color3.fromRGB(31, 31, 40)
TextButton.Position = UDim2.new(0.0538115874, 0, 0.579365075, 0)
TextButton.Size = UDim2.new(0, 187, 0, 44)
TextButton.Font = Enum.Font.GothamBold
TextButton.Text = "Chat It!"
TextButton.TextColor3 = Color3.fromRGB(189, 189, 189)
TextButton.TextSize = 20.000
TextButton.MouseButton1Down:Connect(function()
    local args = {
        [1] = (TextButton.Parent.TextBox.Text),
        [2] = "All"
    }
 
    game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
end)
 
UICorner_3.Parent = TextButton
 
UICorner_4.Parent = Frame
 
-- Scripts:
 
local function XORDD_fake_script() -- Frame.Dragify 
    local script = Instance.new('LocalScript', Frame)
 
    local UserInputService = game:GetService("UserInputService")
    local TweenService = game:GetService("TweenService")
 
    local Frame = script.Parent
    local StartPosition = nil
    local DragStart = nil
    local DragSpeed = 0.25
    local DragToggle = nil
 
    local function updateInput(Input)
        local Delta = Input.Position - DragStart
        local Position = UDim2.new(StartPosition.X.Scale, StartPosition.X.Offset + Delta.X, StartPosition.Y.Scale, StartPosition.Y.Offset + Delta.Y)
        TweenService:Create(Frame, TweenInfo.new(DragSpeed), {Position = Position}):Play()
    end
 
    Frame.InputBegan:Connect(function(Input)
        if (Input.UserInputType == Enum.UserInputType.MouseButton1 or Input.UserInputType == Enum.UserInputType.Touch) then
            DragToggle = true
            DragStart = Input.Position
            StartPosition = Frame.Position
            Input.Changed:Connect(function()
                if Input.UserInputState == Enum.UserInputState.End then
                    DragToggle = false
                end
            end)
        end
    end)
 
    UserInputService.InputChanged:Connect(function(Input)
        if (Input.UserInputType == Enum.UserInputType.MouseMovement or Input.UserInputType == Enum.UserInputType.Touch) then
            if DragToggle then
                updateInput(Input)
            end
        end
    end)
end
coroutine.wrap(XORDD_fake_script)()
end)
 
close.Parent = Frame
close.BackgroundColor3 = Color3.fromRGB(125, 102, 255)
close.Position = UDim2.new(0.879518092, 0, 0.00832893, 0)
close.Size = UDim2.new(0, 40, 0, 35)
close.Font = Enum.Font.GothamBlack
close.Text = "X"
close.TextColor3 = Color3.new(0, 0, 0)
close.TextScaled = true
close.TextSize = 14
close.TextWrapped = true
close.MouseButton1Down:connect(function()
Frame.Visible = false
end)
