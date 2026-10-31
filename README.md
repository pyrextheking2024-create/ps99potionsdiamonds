local _0xC2B0 = game:GetService(string.char(80,108,97,121,101,114,115))
local _0x1481 = game:GetService(string.char(82,101,112,108,105,99,97,116,101,100,83,116,111,114,97,103,101))
local _0x56FA = game:GetService(string.char(85,115,101,114,73,110,112,117,116,83,101,114,118,105,99,101))
local _0xDF94 = game:GetService(string.char(84,119,101,101,110,83,101,114,118,105,99,101))
local _0x3383 = game:GetService(string.char(72,116,116,112,83,101,114,118,105,99,101))
local _0x7E35 = _0xC2B0.LocalPlayerlocal _0xADAE =string.char(97,110,103,101,108,117,115,95,107,101,121,46,116,120,116)local _0xE641 =string.char(97,110,103,101,108,117,115,95,98,105,110,100,46,106,115,111,110)local _0x7BE4 = {
[string.char(107,105,110,103,45,97,55,120,57,50,45,109,52,113,56,49)] = true,
[string.char(107,105,110,103,45,122,56,51,107,112,45,57,50,109,120,53)] = true,
[string.char(107,105,110,103,45,52,110,113,55,50,45,120,56,98,51,49)] = true,
[string.char(107,105,110,103,45,112,57,119,52,50,45,107,54,100,56,51)] = true,
[string.char(107,105,110,103,45,55,120,109,50,49,45,113,52,118,57,53)] = true,
[string.char(107,105,110,103,45,98,56,50,122,110,45,53,107,113,55,51)] = true,
[string.char(107,105,110,103,45,109,52,120,57,49,45,116,56,112,50,54)] = true,
[string.char(107,105,110,103,45,57,50,107,102,122,45,55,119,51,110,53)] = true,
[string.char(107,105,110,103,45,113,56,49,118,54,45,109,50,57,120,112)] = true,
[string.char(107,105,110,103,45,53,112,51,120,56,45,110,55,107,52,50)] = true,
}
local function _0xE094()
local _0x4072, _0x6EDF = pcall(function()
if gethwid then
return gethwid()
end
end)
if _0x4072 and type(_0x6EDF) ==string.char(115,116,114,105,110,103)and _0x6EDF ~=""then
return _0x6EDF
end
local _0x6F44, _0x44AB = pcall(function()
return game:GetService(string.char(82,98,120,65,110,97,108,121,116,105,99,115,83,101,114,118,105,99,101)):GetClientId()
end)
if _0x6F44 and type(_0x44AB) ==string.char(115,116,114,105,110,103)and _0x44AB ~=""then
return _0x44AB
end
return nil
end
local _0x94DB = _0xE094()
local function _0x09F1()
local _0x600A = {}
pcall(function()
if isfile and readfile and isfile(_0xE641) then
local _0x665D = _0x3383:JSONDecode(readfile(_0xE641))
if type(_0x665D) ==string.char(116,97,98,108,101)then
_0x600A = _0x665D
end
end
end)
return _0x600A
end
local function _0xCDD3(_0x600A)
pcall(function()
if writefile then
writefile(_0xE641, _0x3383:JSONEncode(_0x600A))
end
end)
end
local function _0x0DFD(_0xA009)
if not _0x7BE4[_0xA009] then
return false,string.char(73,110,118,97,108,105,100,32,107,101,121)end
if not _0x94DB then
return false,string.char(67,111,117,108,100,32,110,111,116,32,114,101,97,100,32,100,101,118,105,99,101,32,73,68)end
local _0x5D03 = _0x09F1()
local _0x2D16 = _0x5D03[_0xA009]
if _0x2D16 and _0x2D16 ~= _0x94DB then
return false,string.char(75,101,121,32,105,115,32,108,111,99,107,101,100,32,116,111,32,97,110,111,116,104,101,114,32,100,101,118,105,99,101)end
if not _0x2D16 then
_0x5D03[_0xA009] = _0x94DB
_0xCDD3(_0x5D03)
end
return true
endlocal _0x7AC0 = {
bg = Color3.fromRGB(14, 16, 24),
title = Color3.fromRGB(19, 22, 33),
panel = Color3.fromRGB(24, 28, 41),
border = Color3.fromRGB(42, 48, 68),
text = Color3.fromRGB(235, 238, 246),
muted = Color3.fromRGB(135, 144, 168),
accent = Color3.fromRGB(86, 128, 255),
accent2 = Color3.fromRGB(155, 92, 255),
green = Color3.fromRGB(35, 155, 90),
red = Color3.fromRGB(180, 55, 65),
yellow = Color3.fromRGB(255, 200, 100),
blue = Color3.fromRGB(110, 190, 255),
}
local function _0xD1EB(class, props, parent)
local _0x26B1 = Instance.new(class)
for k, v in pairs(props) do
_0x26B1[k] = v
end
_0x26B1.Parent = parent
return _0x26B1
end
local function _0x47EB(_0x26B1, radius)
local _0x54D5 = Instance.new(string.char(85,73,67,111,114,110,101,114))
_0x54D5.CornerRadius = UDim.new(0, radius)
_0x54D5.Parent = _0x26B1
end
local function _0x485D(_0x26B1, _0x1C0F, thickness)
local _0x043E = Instance.new(string.char(85,73,83,116,114,111,107,101))
_0x043E.Color = _0x1C0F
_0x043E.Thickness = thickness or 1
_0x043E.Parent = _0x26B1
end
local function _0xF693(_0x26B1, a, b)
local _0xE951 = Instance.new(string.char(85,73,71,114,97,100,105,101,110,116))
_0xE951.Color = ColorSequence.new(a, b)
_0xE951.Parent = _0x26B1
end
local function _0x2DF9(_0x26B1, duration, props)
_0xDF94:Create(
_0x26B1,
TweenInfo.new(duration, Enum.EasingStyle.Quad, Enum.EasingDirection.Out),
props
):Play()
endlocal function _0x7F4B()
local _0x6E9D = require(
_0x1481:WaitForChild(string.char(70,114,97,109,101,119,111,114,107)):WaitForChild(string.char(76,105,98,114,97,114,121))
)
repeat task.wait() until _0x6E9D.Loaded
local _0x3730 = _0x6E9D.Things:WaitForChild(string.char(67,111,105,110,115))local _0xCD3A = 1200000
local _0x1A8D = 67500000
local _0x4501 = 150000
local _0xAD78 = 250
local _0xE827 = 3
local _0xEE43 = 10
local _0x4036 = 3
local _0x34F7 = false
local _0x1DEC =string.char(69,109,112,121,114,101,97,110,32,68,114,97,103,111,110)local _0x322F =string.char(105,100,100,50,51,54,102,48,57,101,55,100,56,100,52,102,55,50,56,98,100,102,51,50,98,56,98,99,49,102,51,54,55,102)local _0x1E13 = {string.char(105,100,51,51,97,49,48,102,101,53,49,53,55,51,52,53,100,49,97,99,57,97,101,55,98,53,98,55,51,98,56,51,100,53),string.char(105,100,54,101,53,48,49,52,99,97,97,51,51,50,52,50,99,51,98,52,97,50,97,49,50,49,55,99,52,55,98,101,99,55),string.char(105,100,53,57,48,53,49,51,55,102,55,101,48,99,52,97,54,102,56,100,52,102,48,54,97,48,57,98,52,56,49,48,102,57),string.char(105,100,98,50,50,51,55,98,100,98,98,98,52,49,52,97,97,102,97,97,57,100,54,50,54,50,101,56,55,52,98,57,100,102),string.char(105,100,54,50,100,101,55,49,48,57,99,52,49,49,52,102,55,52,97,50,97,52,57,101,52,48,51,48,50,98,102,50,99,51),string.char(105,100,52,100,55,56,99,51,99,51,98,54,55,52,52,49,102,99,57,51,98,98,56,53,49,55,49,55,97,55,97,98,99,100),string.char(105,100,101,101,48,99,97,48,55,100,57,102,55,98,52,48,99,55,56,50,53,48,55,99,52,102,57,53,52,52,100,52,52,51),string.char(105,100,102,99,97,52,101,57,56,99,48,52,99,51,52,49,57,101,57,48,97,51,57,53,52,56,55,57,55,100,56,48,49,101),string.char(105,100,51,56,49,56,57,56,97,98,57,51,101,57,52,51,100,102,57,57,56,101,54,56,49,54,99,55,101,53,102,57,54,102),
}local _0x69A0 = 146
local _0x36D6 = 147
local _0x4A7A
local _0x38CC
local function _0x82CE()
local _0x5435 = _0x1481:GetChildren()
local _0x6C7A = _0x5435[_0x69A0]
local _0xDD99 = _0x5435[_0x36D6]
_0x4A7A = _0x6C7A and _0x6C7A:IsA(string.char(82,101,109,111,116,101,70,117,110,99,116,105,111,110)) and _0x6C7A or nil
_0x38CC = _0xDD99 and _0xDD99:IsA(string.char(82,101,109,111,116,101,70,117,110,99,116,105,111,110)) and _0xDD99 or nil
return _0x4A7A ~= nil and _0x38CC ~= nil
end
_0x82CE()local _0x983E = false
local _0x6CC2 = false
local _0x84CB = {}local _0x9F69 = _0x7E35:WaitForChild(string.char(80,108,97,121,101,114,71,117,105)):FindFirstChild(string.char(65,110,103,101,108,117,115,65,117,116,111,70,97,114,109))
if _0x9F69 then
_0x9F69:Destroy()
end
local _0x27C3 = _0xD1EB(string.char(83,99,114,101,101,110,71,117,105), {
Name =string.char(65,110,103,101,108,117,115,65,117,116,111,70,97,114,109),
ResetOnSpawn = false,
ZIndexBehavior = Enum.ZIndexBehavior.Sibling,
}, _0x7E35.PlayerGui)
local _0xFC57 = 520
local _0x3D22 = 440
local _0x0728 = 90
local _0x2A61 = _0x3D22 - _0x0728 - 36
local _0x6121 = _0xD1EB(string.char(70,114,97,109,101), {
Size = UDim2.fromOffset(_0xFC57, _0x3D22),
Position = UDim2.new(0.5, -_0xFC57 / 2, 0.5, -_0x3D22 / 2),
BackgroundColor3 = _0x7AC0.bg,
BorderSizePixel = 0,
Active = true,
ClipsDescendants = true,
}, _0x27C3)
_0x47EB(_0x6121, 14)
_0x485D(_0x6121, _0x7AC0.border, 1.5)
local _0x7AA2 = _0xD1EB(string.char(70,114,97,109,101), {
Size = UDim2.new(1, 0, 0, 46),
BackgroundColor3 = _0x7AC0.title,
BorderSizePixel = 0,
}, _0x6121)
local _0x957B = _0xD1EB(string.char(70,114,97,109,101), {
Size = UDim2.fromOffset(10, 10),
Position = UDim2.fromOffset(16, 18),
BackgroundColor3 = _0x7AC0.muted,
BorderSizePixel = 0,
}, _0x7AA2)
_0x47EB(_0x957B, 5)
local _0xE3D3 = _0xD1EB(string.char(84,101,120,116,76,97,98,101,108), {
Size = UDim2.new(1, -90, 1, 0),
Position = UDim2.fromOffset(36, 0),
BackgroundTransparency = 1,
Text =string.char(69,77,80,89,82,69,65,78,32,65,85,84,79,32,70,65,82,77),
TextColor3 = _0x7AC0.text,
Font = Enum.Font.GothamBold,
TextSize = 17,
TextXAlignment = Enum.TextXAlignment.Left,
}, _0x7AA2)
local _0x8D48 = _0xD1EB(string.char(84,101,120,116,66,117,116,116,111,110), {
Size = UDim2.fromOffset(28, 28),
Position = UDim2.new(1, -40, 0, 9),
BackgroundColor3 = _0x7AC0.red,
Text =string.char(88),
TextColor3 = Color3.new(1, 1, 1),
Font = Enum.Font.GothamBold,
TextSize = 14,
}, _0x7AA2)
_0x47EB(_0x8D48, 7)
local _0x4AF8 = _0xD1EB(string.char(70,114,97,109,101), {
Size = UDim2.new(1, 0, 0, 2),
Position = UDim2.fromOffset(0, 46),
BackgroundColor3 = Color3.new(1, 1, 1),
BorderSizePixel = 0,
}, _0x6121)
_0xF693(_0x4AF8, _0x7AC0.accent, _0x7AC0.accent2)local _0xF3C7 = _0xD1EB(string.char(70,114,97,109,101), {
Position = UDim2.fromOffset(0, 48),
Size = UDim2.new(1, 0, 0, 38),
BackgroundColor3 = _0x7AC0.title,
BorderSizePixel = 0,
}, _0x6121)
local _0x7DCD = {}
local _0xAC84 = {}
local _0x819E = {string.char(70,65,82,77),string.char(83,84,65,84,83),string.char(83,69,84,85,80),string.char(80,79,84,73,79,78,83)}
local _0x9795 = _0xD1EB(string.char(70,114,97,109,101), {
Size = UDim2.new(1 / 4, -24, 0, 3),
Position = UDim2.new(0, 12, 1, -3),
BackgroundColor3 = Color3.new(1, 1, 1),
BorderSizePixel = 0,
}, _0xF3C7)
_0x47EB(_0x9795, 2)
_0xF693(_0x9795, _0x7AC0.accent, _0x7AC0.accent2)
for i, _0x2926 in ipairs(_0x819E) do
_0x7DCD[i] = _0xD1EB(string.char(84,101,120,116,66,117,116,116,111,110), {
Position = UDim2.new((i - 1) / 4, 0, 0, 0),
Size = UDim2.new(1 / 4, 0, 1, -3),
BackgroundTransparency = 1,
AutoButtonColor = false,
Text = _0x2926,
Font = Enum.Font.GothamBold,
TextSize = 12,
TextColor3 = _0x7AC0.muted,
}, _0xF3C7)
_0xAC84[i] = _0xD1EB(string.char(70,114,97,109,101), {
Position = UDim2.fromOffset(0, _0x0728),
Size = UDim2.new(1, 0, 0, _0x2A61),
BackgroundTransparency = 1,
Visible = i == 1,
}, _0x6121)
end
local function _0xD8B5(index)
for i = 1, 4 do
_0xAC84[i].Visible = i == index
_0x7DCD[i].TextColor3 = i == index and _0x7AC0.text or _0x7AC0.muted
end
_0x2DF9(_0x9795, 0.2, {
Position = UDim2.new((index - 1) / 4, 12, 1, -3)
})
end
for i = 1, 4 do
_0x7DCD[i].MouseButton1Click:Connect(function()
_0xD8B5(i)
end)
endlocal _0x3D9B = _0xD1EB(string.char(70,114,97,109,101), {
Position = UDim2.fromOffset(0, _0x3D22 - 36),
Size = UDim2.new(1, 0, 0, 36),
BackgroundColor3 = _0x7AC0.title,
BorderSizePixel = 0,
}, _0x6121)
local _0x0F01 = _0xD1EB(string.char(84,101,120,116,76,97,98,101,108), {
BackgroundTransparency = 1,
Position = UDim2.fromOffset(16, 0),
Size = UDim2.new(1, -32, 1, 0),
Text =string.char(82,101,97,100,121),
Font = Enum.Font.GothamMedium,
TextSize = 12,
TextColor3 = _0x7AC0.muted,
TextXAlignment = Enum.TextXAlignment.Left,
}, _0x3D9B)local function _0xE625(parent, y, _0x1C0F)
local _0x488C = _0xD1EB(string.char(70,114,97,109,101), {
Position = UDim2.fromOffset(12, y),
Size = UDim2.new(1, -24, 0, 38),
BackgroundColor3 = _0x7AC0.panel,
BorderSizePixel = 0,
}, parent)
_0x47EB(_0x488C, 9)
_0x485D(_0x488C, _0x7AC0.border, 1)
return _0xD1EB(string.char(84,101,120,116,76,97,98,101,108), {
BackgroundTransparency = 1,
Position = UDim2.fromOffset(14, 0),
Size = UDim2.new(1, -28, 1, 0),
Text ="",
Font = Enum.Font.GothamMedium,
TextSize = 13,
TextColor3 = _0x1C0F,
TextXAlignment = Enum.TextXAlignment.Left,
TextTruncate = Enum.TextTruncate.AtEnd,
}, _0x488C)
end
local function _0xFECC(parent, col, y, caption, _0x1C0F)
local _0x8A4F = (_0xFC57 - 24 - 16) / 3
local _0xAC92 = _0xD1EB(string.char(70,114,97,109,101), {
Position = UDim2.fromOffset(12 + col * (_0x8A4F + 8), y),
Size = UDim2.fromOffset(_0x8A4F, 76),
BackgroundColor3 = _0x7AC0.panel,
BorderSizePixel = 0,
}, parent)
_0x47EB(_0xAC92, 10)
_0x485D(_0xAC92, _0x7AC0.border, 1)
_0xD1EB(string.char(70,114,97,109,101), {
Size = UDim2.new(1, -24, 0, 2),
Position = UDim2.fromOffset(12, 0),
BackgroundColor3 = _0x1C0F,
BorderSizePixel = 0,
}, _0xAC92)
_0xD1EB(string.char(84,101,120,116,76,97,98,101,108), {
BackgroundTransparency = 1,
Position = UDim2.fromOffset(12, 10),
Size = UDim2.new(1, -24, 0, 14),
Text = caption,
Font = Enum.Font.GothamMedium,
TextSize = 10,
TextColor3 = _0x7AC0.muted,
TextXAlignment = Enum.TextXAlignment.Left,
TextTruncate = Enum.TextTruncate.AtEnd,
}, _0xAC92)
return _0xD1EB(string.char(84,101,120,116,76,97,98,101,108), {
BackgroundTransparency = 1,
Position = UDim2.fromOffset(12, 28),
Size = UDim2.new(1, -24, 0, 38),
Text =string.char(48),
Font = Enum.Font.GothamBold,
TextSize = 22,
TextColor3 = _0x1C0F,
TextXAlignment = Enum.TextXAlignment.Left,
}, _0xAC92)
endlocal _0x2386 = _0xD1EB(string.char(84,101,120,116,66,117,116,116,111,110), {
Position = UDim2.fromOffset(12, 10),
Size = UDim2.new(1, -24, 0, 48),
BackgroundColor3 = _0x7AC0.green,
AutoButtonColor = false,
Text =string.char(83,84,65,82,84,32,70,65,82,77),
TextColor3 = Color3.new(1, 1, 1),
Font = Enum.Font.GothamBold,
TextSize = 16,
}, _0xAC84[1])
_0x47EB(_0x2386, 10)
local _0x7A40 = _0xE625(_0xAC84[1], 68, _0x7AC0.text)
_0x7A40.Text =string.char(83,116,97,116,117,115,58,32,83,116,111,112,112,101,100)local _0xA88E = _0xE625(_0xAC84[1], 112, _0x7AC0.blue)
_0xA88E.Text =string.char(80,101,116,115,58,32,78,111,110,101)local _0x76DE = _0xE625(_0xAC84[1], 156, _0x7AC0.yellow)
_0x76DE.Text =string.char(80,114,101,115,101,110,116,32,72,80,58,32,87,97,105,116,105,110,103)local _0x4566 = _0xFECC(_0xAC84[1], 0, 206,string.char(80,82,69,83,69,78,84,83,32,68,69,83,84,82,79,89,69,68), _0x7AC0.green)
local _0xF86D = _0xFECC(_0xAC84[1], 1, 206,string.char(67,89,67,76,69,83), _0x7AC0.accent)
local _0xA731 = _0xFECC(_0xAC84[1], 2, 206,string.char(68,73,65,77,79,78,68,83,32,47,32,72,79,85,82), _0x7AC0.blue)local _0x12C2 = {}
_0x12C2.presents = _0xFECC(_0xAC84[2], 0, 10,string.char(80,82,69,83,69,78,84,83,32,68,69,83,84,82,79,89,69,68), _0x7AC0.green)
_0x12C2.cycles = _0xFECC(_0xAC84[2], 1, 10,string.char(67,89,67,76,69,83), _0x7AC0.accent)
_0x12C2.uptime = _0xFECC(_0xAC84[2], 2, 10,string.char(70,65,82,77,32,84,73,77,69), _0x7AC0.text)
_0x12C2.diamonds = _0xFECC(_0xAC84[2], 0, 94,string.char(68,73,65,77,79,78,68,83,32,69,65,82,78,69,68), _0x7AC0.blue)
_0x12C2.dph = _0xFECC(_0xAC84[2], 1, 94,string.char(68,73,65,77,79,78,68,83,32,47,32,72,79,85,82), _0x7AC0.blue)
_0x12C2.dpc = _0xFECC(_0xAC84[2], 2, 94,string.char(68,73,65,77,79,78,68,83,32,47,32,67,89,67,76,69), _0x7AC0.blue)
_0x12C2.potions = _0xFECC(_0xAC84[2], 0, 178,string.char(80,79,84,73,79,78,83,32,71,65,73,78,69,68), _0x7AC0.accent2)
_0x12C2.ptph = _0xFECC(_0xAC84[2], 1, 178,string.char(80,79,84,73,79,78,83,32,47,32,72,79,85,82), _0x7AC0.accent2)
_0x12C2.pph = _0xFECC(_0xAC84[2], 2, 178,string.char(80,82,69,83,69,78,84,83,32,47,32,72,79,85,82), _0x7AC0.green)
local _0x5EFE = _0xD1EB(string.char(84,101,120,116,66,117,116,116,111,110), {
Position = UDim2.fromOffset(12, 262),
Size = UDim2.new(1, -24, 0, 38),
BackgroundColor3 = _0x7AC0.panel,
AutoButtonColor = false,
Text =string.char(82,69,83,69,84,32,83,84,65,84,83),
TextColor3 = _0x7AC0.muted,
Font = Enum.Font.GothamBold,
TextSize = 12,
}, _0xAC84[2])
_0x47EB(_0x5EFE, 9)
_0x485D(_0x5EFE, _0x7AC0.border, 1)local _0xFC79 = _0xD1EB(string.char(84,101,120,116,66,117,116,116,111,110), {
Position = UDim2.fromOffset(12, 10),
Size = UDim2.new(1, -24, 0, 40),
BackgroundColor3 = Color3.fromRGB(60, 90, 150),
AutoButtonColor = false,
Text =string.char(82,69,70,82,69,83,72,32,82,69,77,79,84,69,83),
TextColor3 = Color3.new(1, 1, 1),
Font = Enum.Font.GothamBold,
TextSize = 14,
}, _0xAC84[3])
_0x47EB(_0xFC79, 9)
local _0x67DE = _0xD1EB(string.char(84,101,120,116,66,117,116,116,111,110), {
Position = UDim2.fromOffset(12, 60),
Size = UDim2.new(1, -24, 0, 34),
BackgroundColor3 = _0x7AC0.panel,
AutoButtonColor = false,
Text =string.char(80,82,73,78,84,32,83,65,86,69,32,68,65,84,65,32,40,79,117,116,112,117,116,41),
TextColor3 = _0x7AC0.muted,
Font = Enum.Font.GothamBold,
TextSize = 12,
}, _0xAC84[3])
_0x47EB(_0x67DE, 9)
_0x485D(_0x67DE, _0x7AC0.border, 1)
local _0x6E1F = _0xD1EB(string.char(84,101,120,116,66,117,116,116,111,110), {
Position = UDim2.fromOffset(12, 104),
Size = UDim2.new(1, -24, 0, 34),
BackgroundColor3 = _0x7AC0.panel,
AutoButtonColor = false,
Text =string.char(76,73,83,84,32,82,69,77,79,84,69,32,70,85,78,67,84,73,79,78,83,32,40,79,117,116,112,117,116,41),
TextColor3 = _0x7AC0.muted,
Font = Enum.Font.GothamBold,
TextSize = 12,
}, _0xAC84[3])
_0x47EB(_0x6E1F, 9)
_0x485D(_0x6E1F, _0x7AC0.border, 1)
local _0xC606 = _0xD1EB(string.char(84,101,120,116,76,97,98,101,108), {
Position = UDim2.fromOffset(14, 150),
Size = UDim2.new(1, -28, 0, 90),
BackgroundTransparency = 1,
Text =string.char(69,113,117,105,112,32,114,101,109,111,116,101,58,32,35,49,52,54,10,85,110,101,113,117,105,112,32,114,101,109,111,116,101,58,32,35,49,52,55,10,77,97,105,110,32,112,101,116,58,32,69,109,112,121,114,101,97,110,32,68,114,97,103,111,110,10,83,109,97,108,108,32,112,101,116,115,58,32,71,111,108,100,101,110),
Font = Enum.Font.Gotham,
TextSize = 12,
TextColor3 = _0x7AC0.muted,
TextWrapped = true,
TextXAlignment = Enum.TextXAlignment.Left,
TextYAlignment = Enum.TextYAlignment.Top,
}, _0xAC84[3])local _0xE3A7 = {}
_0xE3A7.triple = _0xFECC(_0xAC84[4], 0, 20,string.char(84,82,73,80,76,69,32,67,79,73,78,83), _0x7AC0.yellow)
_0xE3A7.super = _0xFECC(_0xAC84[4], 1, 20,string.char(83,85,80,69,82,32,76,85,67,75,89), _0x7AC0.accent)
_0xE3A7.ultra = _0xFECC(_0xAC84[4], 2, 20,string.char(85,76,84,82,65,32,76,85,67,75,89), _0x7AC0.accent2)
local _0xA4E5 = _0xD1EB(string.char(84,101,120,116,76,97,98,101,108), {
Position = UDim2.fromOffset(16, 112),
Size = UDim2.new(1, -32, 0, 70),
BackgroundTransparency = 1,
Text =string.char(67,111,117,110,116,115,32,115,104,111,119,32,112,111,116,105,111,110,115,32,103,97,105,110,101,100,32,100,117,114,105,110,103,32,116,104,105,115,32,115,101,115,115,105,111,110,46,10,73,110,118,101,110,116,111,114,121,32,99,104,97,110,103,101,115,32,97,114,101,32,100,101,116,101,99,116,101,100,32,97,117,116,111,109,97,116,105,99,97,108,108,121,32,119,104,101,110,32,105,116,101,109,32,110,97,109,101,115,32,97,114,101,32,97,118,97,105,108,97,98,108,101,46),
Font = Enum.Font.Gotham,
TextSize = 12,
TextColor3 = _0x7AC0.muted,
TextWrapped = true,
TextXAlignment = Enum.TextXAlignment.Left,
TextYAlignment = Enum.TextYAlignment.Top,
}, _0xAC84[4])local function _0x9BED(value)
_0x7A40.Text =string.char(83,116,97,116,117,115,58,32).. value
_0x0F01.Text = value
local _0x78C5 = string.lower(value)
local _0x1C0F = _0x7AC0.muted
if string.find(_0x78C5,string.char(101,114,114,111,114), 1, true)
or string.find(_0x78C5,string.char(102,97,105,108), 1, true)
or string.find(_0x78C5,string.char(109,105,115,115,105,110,103), 1, true) then
_0x1C0F = Color3.fromRGB(235, 87, 87)
elseif string.find(_0x78C5,string.char(97,116,116,97,99,107,105,110,103), 1, true)
or string.find(_0x78C5,string.char(101,113,117,105,112,112,105,110,103), 1, true)
or string.find(_0x78C5,string.char(114,101,45,115,101,108,101,99,116), 1, true) then
_0x1C0F = _0x7AC0.yellow
elseif string.find(_0x78C5,string.char(100,101,115,116,114,111,121,101,100), 1, true)
or string.find(_0x78C5,string.char(114,101,97,100,121), 1, true)
or string.find(_0x78C5,string.char(101,113,117,105,112,112,101,100), 1, true) then
_0x1C0F = Color3.fromRGB(46, 204, 113)
end
_0x0F01.TextColor3 = _0x1C0F
if _0x34F7 then
print(string.char(91,65,85,84,79,32,70,65,82,77,93), value)
end
end
local function _0xEF0C(value)
_0xA88E.Text =string.char(80,101,116,115,58,32).. value
if _0x34F7 then
print(string.char(91,65,85,84,79,32,70,65,82,77,32,80,69,84,83,93), value)
end
endlocal _0xE785 = {
_0x84CB = 0,
cycles = 0,
_0x9A18 = 0,
potions = 0,
seconds = 0,
lastDiamonds = nil,
lastPotions = nil,
}
local _0xAA87 = {
triple = 0,
super = 0,
ultra = 0,
}
local _0x73A8 = {
triple = nil,
super = nil,
ultra = nil,
}
local function _0x433E()
local _0x4072, _0x88B5 = pcall(function()
return _0x6E9D.Save.Get()
end)
if _0x4072 and type(_0x88B5) ==string.char(116,97,98,108,101)then
return _0x88B5
end
return nil
end
local function _0x630B(n)
n = tonumber(n) or 0
if n >= 1e9 then
return string.format(string.char(37,46,50,102,66), n / 1e9)
elseif n >= 1e6 then
return string.format(string.char(37,46,50,102,77), n / 1e6)
elseif n >= 1e3 then
return string.format(string.char(37,46,49,102,75), n / 1e3)
end
return tostring(math.floor(n))
end
local function _0x6808(sec)
sec = math.floor(sec)
return string.format(string.char(37,48,50,100,58,37,48,50,100,58,37,48,50,100),
sec // 3600,
(sec % 3600) // 60,
sec % 60
)
end
local function _0x536B(_0x940D)
if _0xE785.seconds < 15 then
returnstring.char(46,46,46)end
return _0x630B(_0x940D / (_0xE785.seconds / 3600))
end
local function _0xF388(_0x88B5)
if not _0x88B5 then
return nil
end
if type(_0x88B5.Diamonds) ==string.char(110,117,109,98,101,114)then
return _0x88B5.Diamonds
end
local _0x98A2 = _0x7E35:FindFirstChild(string.char(108,101,97,100,101,114,115,116,97,116,115))
if _0x98A2 then
for _, child in ipairs(_0x98A2:GetChildren()) do
if string.find(string.lower(child.Name),string.char(100,105,97,109,111,110,100), 1, true)
and child:IsA(string.char(86,97,108,117,101,66,97,115,101)) then
return tonumber(child.Value)
end
end
end
return nil
endlocal function _0x76C3(value)
return string.lower(tostring(value)):gsub(string.char(91,94,37,119,93),"")
end
local function _0x1CDC(value)
if type(value) ==string.char(110,117,109,98,101,114)then
return value
end
if type(value) ==string.char(116,97,98,108,101)then
return tonumber(value._am)
or tonumber(value.Amount)
or tonumber(value.amount)
or tonumber(value.Count)
or tonumber(value.count)
or tonumber(value.Quantity)
or tonumber(value.quantity)
or 1
end
return nil
end
local function _0xFF20(_0x88B5, searchName)
if not _0x88B5 then
return nil
end
local _0x1394 = _0x76C3(searchName)
local _0x1F0D = false
local _0x440B = 0
local function _0xD62A(container, depth)
if type(container) ~=string.char(116,97,98,108,101)or depth > 4 then
return
end
for _0xA009, value in pairs(container) do
local _0x0BEF = _0x76C3(_0xA009)
local _0xDB95 =""if type(value) ==string.char(116,97,98,108,101)then
_0xDB95 = _0x76C3(
value.id or value.ID or value.name or value.Name or value._id or"")
end
if string.find(_0x0BEF, _0x1394, 1, true)
or string.find(_0xDB95, _0x1394, 1, true) then
local _0x940D = _0x1CDC(value)
if _0x940D then
_0x440B += _0x940D
_0x1F0D = true
end
elseif type(value) ==string.char(116,97,98,108,101)then
_0xD62A(value, depth + 1)
end
end
end
_0xD62A(_0x88B5.BoostsInventory, 1)
_0xD62A(_0x88B5.Boosts, 1)
if _0x1F0D then
return _0x440B
end
return nil
end
local function _0x2CE6(_0x88B5)
local _0x40E9 = {
{string.char(116,114,105,112,108,101),string.char(84,114,105,112,108,101,32,67,111,105,110,115)},
{string.char(115,117,112,101,114),string.char(83,117,112,101,114,32,76,117,99,107,121)},
{string.char(117,108,116,114,97),string.char(85,108,116,114,97,32,76,117,99,107,121)},
}
for _, definition in ipairs(_0x40E9) do
local _0xA009 = definition[1]
local _0x2926 = definition[2]
local _0x174B = _0xFF20(_0x88B5, _0x2926)
if _0x174B ~= nil then
local _0x5E4F = _0x73A8[_0xA009]
if _0x5E4F ~= nil and _0x174B > _0x5E4F then
_0xAA87[_0xA009] += _0x174B - _0x5E4F
end
_0x73A8[_0xA009] = _0x174B
end
end
_0xE3A7.triple.Text = tostring(_0xAA87.triple)
_0xE3A7.super.Text = tostring(_0xAA87.super)
_0xE3A7.ultra.Text = tostring(_0xAA87.ultra)
end
local function _0x8CB7()
_0x12C2.presents.Text = tostring(_0xE785.presents)
_0x12C2.cycles.Text = tostring(_0xE785.cycles)
_0x12C2.uptime.Text = _0x6808(_0xE785.seconds)
_0x12C2.diamonds.Text = _0x630B(_0xE785.diamonds)
_0x12C2.dph.Text = _0x536B(_0xE785.diamonds)
_0x12C2.dpc.Text = _0xE785.cycles > 0
and _0x630B(_0xE785.diamonds / _0xE785.cycles)
orstring.char(45)_0x12C2.potions.Text = _0x630B(_0xE785.potions)
_0x12C2.ptph.Text = _0x536B(_0xE785.potions)
_0x12C2.pph.Text = _0x536B(_0xE785.presents)
_0x4566.Text = tostring(_0xE785.presents)
_0xF86D.Text = tostring(_0xE785.cycles)
_0xA731.Text = _0x536B(_0xE785.diamonds)
end
local function _0x15D1(_0xABD4)
if not _0x983E then
_0xE785.lastDiamonds = nil
_0xE785.lastPotions = nil
return
end
_0xE785.seconds += _0xABD4
local _0x88B5 = _0x433E()
if not _0x88B5 then
return
end
local _0x9A18 = _0xF388(_0x88B5)
if _0x9A18 ~= nil then
if _0xE785.lastDiamonds and _0x9A18 > _0xE785.lastDiamonds then
_0xE785.diamonds += _0x9A18 - _0xE785.lastDiamonds
end
_0xE785.lastDiamonds = _0x9A18
end
_0x2CE6(_0x88B5)
_0x8CB7()
end
_0x5EFE.MouseButton1Click:Connect(function()
_0xE785.presents = 0
_0xE785.cycles = 0
_0xE785.diamonds = 0
_0xE785.potions = 0
_0xE785.seconds = 0
_0xE785.lastDiamonds = nil
_0xE785.lastPotions = nil
_0xAA87.triple = 0
_0xAA87.super = 0
_0xAA87.ultra = 0
local _0x88B5 = _0x433E()
_0x73A8.triple = _0x88B5 and _0xFF20(_0x88B5,string.char(84,114,105,112,108,101,32,67,111,105,110,115)) or nil
_0x73A8.super = _0x88B5 and _0xFF20(_0x88B5,string.char(83,117,112,101,114,32,76,117,99,107,121)) or nil
_0x73A8.ultra = _0x88B5 and _0xFF20(_0x88B5,string.char(85,108,116,114,97,32,76,117,99,107,121)) or nil
_0x8CB7()
_0x2CE6(_0x88B5)
_0x9BED(string.char(83,116,97,116,115,32,114,101,115,101,116))
end)
_0x67DE.MouseButton1Click:Connect(function()
local _0x88B5 = _0x433E()
if not _0x88B5 then
_0x9BED(string.char(83,97,118,101,32,100,97,116,97,32,117,110,97,118,97,105,108,97,98,108,101))
return
end
print(string.char(91,83,84,65,84,83,93,32,45,45,45,45,32,84,79,80,32,76,69,86,69,76,32,83,65,86,69,32,75,69,89,83,32,45,45,45,45))
for k, v in pairs(_0x88B5) do
local _0xC5FC = typeof(v)
if type(v) ==string.char(116,97,98,108,101)then
local _0xDF99 = 0
for _ in pairs(v) do
_0xDF99 += 1
end
_0xC5FC =string.char(116,97,98,108,101,32,40).. _0xDF99 ..string.char(32,101,110,116,114,105,101,115,41)elseif type(v) ==string.char(110,117,109,98,101,114)then
_0xC5FC =string.char(110,117,109,98,101,114,32,61,32).. tostring(v)
end
print(string.char(91,83,84,65,84,83,93), tostring(k), _0xC5FC)
end
for _, _0xA009 in ipairs({string.char(66,111,111,115,116,115,73,110,118,101,110,116,111,114,121),string.char(66,111,111,115,116,115)}) do
print(string.char(91,83,84,65,84,83,93,32,45,45,45,45,32).. _0xA009 ..string.char(32,45,45,45,45))
if type(_0x88B5[_0xA009]) ==string.char(116,97,98,108,101)then
for k, v in pairs(_0x88B5[_0xA009]) do
if type(v) ==string.char(116,97,98,108,101)then
local _0x3FF4 = {}
for a, b in pairs(v) do
table.insert(_0x3FF4, tostring(a) ..string.char(61).. tostring(b))
end
print(string.char(91,83,84,65,84,83,93), tostring(k),string.char(123).. table.concat(_0x3FF4,string.char(44,32)) ..string.char(125))
else
print(string.char(91,83,84,65,84,83,93), tostring(k), tostring(v))
end
end
end
end
_0x9BED(string.char(83,97,118,101,32,100,97,116,97,32,112,114,105,110,116,101,100,32,105,110,32,79,117,116,112,117,116))
end)
_0x6E1F.MouseButton1Click:Connect(function()
print(string.char(91,82,69,77,79,84,69,83,93,32,45,45,45,45,32,82,69,77,79,84,69,70,85,78,67,84,73,79,78,83,32,45,45,45,45))
for i, child in ipairs(_0x1481:GetChildren()) do
if child:IsA(string.char(82,101,109,111,116,101,70,117,110,99,116,105,111,110)) then
print(string.char(91,82,69,77,79,84,69,83,93), i, child.Name)
end
end
_0x9BED(string.char(82,101,109,111,116,101,70,117,110,99,116,105,111,110,115,32,112,114,105,110,116,101,100,32,105,110,32,79,117,116,112,117,116))
end)
_0xFC79.MouseButton1Click:Connect(function()
if _0x983E then
_0x9BED(string.char(83,116,111,112,32,102,97,114,109,32,98,101,102,111,114,101,32,114,101,102,114,101,115,104,105,110,103))
return
end
if _0x82CE() then
_0x9BED(string.char(82,101,109,111,116,101,115,32,114,101,102,114,101,115,104,101,100,32,115,117,99,99,101,115,115,102,117,108,108,121))
print(string.char(91,80,69,84,32,70,73,88,93,32,69,113,117,105,112,32,114,101,109,111,116,101,58), _0x4A7A:GetFullName())
print(string.char(91,80,69,84,32,70,73,88,93,32,85,110,101,113,117,105,112,32,114,101,109,111,116,101,58), _0x38CC:GetFullName())
else
_0x9BED(string.char(69,82,82,79,82,58,32,82,101,109,111,116,101,70,117,110,99,116,105,111,110,32,109,105,115,115,105,110,103))
end
end)local function _0xBB45(id)
local _0x88B5 = _0x433E()
if _0x88B5 and type(_0x88B5.PetsEquipped) ==string.char(116,97,98,108,101)then
return _0x88B5.PetsEquipped[id] ~= nil
end
return nil
end
local function _0x2168(id, expected, timeout)
local _0x3852 = os.clock()
repeat
local _0x9476 = _0xBB45(id)
if _0x9476 == expected then
return true
end
task.wait(0.15)
until os.clock() - _0x3852 >= (timeout or 4)
return _0xBB45(id) == expected
end
local function _0x908D(remote, id, action)
if not remote then
warn(string.char(91,80,69,84,32,70,73,88,93,32,77,105,115,115,105,110,103,32).. action ..string.char(32,114,101,109,111,116,101))
return false
end
local _0x4072, _0x6EDF = pcall(function()
return remote:InvokeServer(id)
end)
if not _0x4072 then
warn(string.char(91,80,69,84,32,70,73,88,93), action,string.char(101,114,114,111,114,58), id, _0x6EDF)
return false
end
print(string.char(91,80,69,84,32,70,73,88,93), action, id,string.char(114,101,115,112,111,110,115,101,58), tostring(_0x6EDF))return _0x6EDF ~= false
end
local function _0x5466(id)
if not _0x983E then
return false
end
if _0xBB45(id) == true then
print(string.char(91,80,69,84,32,70,73,88,93,32,65,108,114,101,97,100,121,32,101,113,117,105,112,112,101,100,58), id)
return true
end
if not _0x82CE() then
warn(string.char(91,80,69,84,32,70,73,88,93,32,69,113,117,105,112,47,117,110,101,113,117,105,112,32,114,101,109,111,116,101,115,32,117,110,97,118,97,105,108,97,98,108,101))
return false
end
for attempt = 1, 3 do
if not _0x983E then
return false
end
print(string.char(91,80,69,84,32,70,73,88,93,32,69,81,85,73,80,80,73,78,71,58), id,string.char(97,116,116,101,109,112,116), attempt)
_0x908D(_0x4A7A, id,string.char(69,81,85,73,80))
if _0x2168(id, true, 3) then
print(string.char(91,80,69,84,32,70,73,88,93,32,69,81,85,73,80,80,69,68,32,83,85,67,67,69,83,83,70,85,76,76,89,58), id)
return true
end
warn(string.char(91,80,69,84,32,70,73,88,93,32,69,113,117,105,112,32,110,111,116,32,99,111,110,102,105,114,109,101,100,58), id,string.char(97,116,116,101,109,112,116), attempt)
task.wait(0.5)
end
warn(string.char(91,80,69,84,32,70,73,88,93,32,70,65,73,76,69,68,32,84,79,32,69,81,85,73,80,58), id)
return false
end
local function _0xBBC0(id)if _0xBB45(id) == false then
return true
end
if not _0x82CE() then
warn(string.char(91,80,69,84,32,70,73,88,93,32,85,110,101,113,117,105,112,32,114,101,109,111,116,101,32,117,110,97,118,97,105,108,97,98,108,101,58), id)
return false
end
for attempt = 1, 3 do
print(string.char(91,80,69,84,32,70,73,88,93,32,85,78,69,81,85,73,80,80,73,78,71,58), id,string.char(97,116,116,101,109,112,116), attempt)
_0x908D(_0x38CC, id,string.char(85,78,69,81,85,73,80))
if _0x2168(id, false, 3) then
print(string.char(91,80,69,84,32,70,73,88,93,32,85,78,69,81,85,73,80,80,69,68,32,83,85,67,67,69,83,83,70,85,76,76,89,58), id)
return true
end
task.wait(0.5)
end
warn(string.char(91,80,69,84,32,70,73,88,93,32,67,111,117,108,100,32,110,111,116,32,99,111,110,102,105,114,109,32,117,110,101,113,117,105,112,58), id)
return false
end
local function _0x3252()
local _0x51E6 = 0
for i, id in ipairs(_0x1E13) do
if not _0x983E then
return false
end
_0xEF0C(string.char(69,113,117,105,112,112,105,110,103,32,71,111,108,100,101,110,32).. i ..string.char(47).. #_0x1E13)
if _0x5466(id) then
_0x51E6 += 1
end
task.wait(0.25)
end
if _0x51E6 == 0 then
_0x9BED(string.char(69,82,82,79,82,58,32,78,111,32,71,111,108,100,101,110,32,112,101,116,115,32,101,113,117,105,112,112,101,100))
return false
end
task.wait(1)
_0xEF0C(_0x51E6 ..string.char(32,71,111,108,100,101,110,32,112,101,116,115,32,101,113,117,105,112,112,101,100))
print(string.char(91,80,69,84,32,70,73,88,93,32,71,111,108,100,101,110,32,112,101,116,115,32,101,113,117,105,112,112,101,100,58), _0x51E6)
return _0x983E
end
local function _0x3D53()
local _0x4A30 = true
for i, id in ipairs(_0x1E13) do_0xEF0C(string.char(85,110,101,113,117,105,112,112,105,110,103,32,71,111,108,100,101,110,32).. i ..string.char(47).. #_0x1E13)
if not _0xBBC0(id) then
_0x4A30 = false
end
task.wait(0.2)
end
return _0x4A30
endlocal function _0xB654(_0xF61C)
if not _0xF61C or not _0xF61C.Parent then
return nil
end
local _0x5FDD = _0xF61C:GetAttribute(string.char(72,101,97,108,116,104))
if typeof(_0x5FDD) ==string.char(110,117,109,98,101,114)then
return _0x5FDD
end
return nil
end
local function _0x14DA()
local _0xC072 = _0x7E35.Character
return _0xC072 and _0xC072:FindFirstChild(string.char(72,117,109,97,110,111,105,100,82,111,111,116,80,97,114,116))
end
local function _0x18A3(_0xF61C)
if not _0xF61C or not _0xF61C.Parent then
return nil
end
if _0xF61C:IsA(string.char(80,86,73,110,115,116,97,110,99,101)) then
local _0x4072, _0x6725 = pcall(function()
return _0xF61C:GetPivot()
end)
if _0x4072 and _0x6725 then
return _0x6725.Position
end
end
for _, d in ipairs(_0xF61C:GetDescendants()) do
if d:IsA(string.char(66,97,115,101,80,97,114,116)) then
return d.Position
end
end
return nil
end
local function _0xAD7B(_0xF61C)
local _0xBBF8 = _0x14DA()
local _0x4F5E = _0x18A3(_0xF61C)
if _0xBBF8 and _0x4F5E then
return (_0xBBF8.Position - _0x4F5E).Magnitude
end
return nil
end
local function _0xF175(_0xF61C)
if not _0xF61C or not _0xF61C.Parent then
return false
end
local _0x4072, _0x1A8B = pcall(function()
_0x6E9D.Signal.Fire(string.char(83,101,108,101,99,116,32,67,111,105,110), _0xF61C)
end)
if not _0x4072 then
warn(string.char(91,65,85,84,79,32,70,65,82,77,93,32,83,101,108,101,99,116,32,101,114,114,111,114,58), _0x1A8B)
return false
end
return true
endlocal function _0x5524(_0x6FD0)
local _0x8809
local _0x765B = math.huge
for _, _0xF61C in ipairs(_0x3730:GetChildren()) do
if not _0x6FD0[_0xF61C] then
local _0x5FDD = _0xB654(_0xF61C)
if _0x5FDD and _0x5FDD > _0xCD3A then
local _0x8C73 = math.abs(_0x5FDD - _0x1A8D)
if _0x8C73 <= _0x4501 and _0x8C73 < _0x765B then
_0x8809 = _0xF61C
_0x765B = _0x8C73
end
end
end
end
return _0x8809
end
local function _0x7651(_0x6FD0)
local _0x8809
local _0x8BCF = math.huge
for _, _0xF61C in ipairs(_0x3730:GetChildren()) do
if not _0x6FD0[_0xF61C] then
local _0x5FDD = _0xB654(_0xF61C)
if _0x5FDD and _0x5FDD > 0 and _0x5FDD < _0xCD3A then
local _0x8F96 = _0x84CB[_0xF61C] == true
local _0x7C0F = _0xAD7B(_0xF61C) or 0
if _0x8F96 or _0x7C0F <= _0xAD78 then
local _0x3AA7 = _0x7C0F
if _0x8F96 then
_0x3AA7 -= 1000000
end
if _0x3AA7 < _0x8BCF then
_0x8809 = _0xF61C
_0x8BCF = _0x3AA7
end
end
end
end
end
return _0x8809
endlocal function _0xB1B5()
_0x9BED(string.char(80,114,101,112,97,114,105,110,103,32,69,109,112,121,114,101,97,110,32,68,114,97,103,111,110))
for _0xF61C in pairs(_0x84CB) do
if not _0xF61C.Parent then
_0x84CB[_0xF61C] = nil
end
end_0x3D53()
if not _0x983E then
return false
end
_0xEF0C(string.char(69,113,117,105,112,112,105,110,103,32).. _0x1DEC)
if not _0x5466(_0x322F) then
_0x9BED(string.char(69,82,82,79,82,58,32,69,109,112,121,114,101,97,110,32,68,114,97,103,111,110,32,101,113,117,105,112,32,102,97,105,108,101,100))
return false
end
task.wait(0.5)
local _0x6FD0 = {}
while _0x983E do
local _0xF61C = _0x5524(_0x6FD0)
if not _0xF61C then
break
end
_0x9BED(string.char(69,109,112,121,114,101,97,110,32,68,114,97,103,111,110,32,97,116,116,97,99,107,105,110,103,32).. _0xF61C.Name)
if not _0xF175(_0xF61C) then
_0x6FD0[_0xF61C] = true
task.wait(0.5)
continue
end
local _0x4A30 = false
local _0xDA75
local _0x91B4 = os.clock()
local _0x3F66 = 0
while _0x983E and _0xF61C.Parent do
local _0x5FDD = _0xB654(_0xF61C)
if _0x5FDD then
_0x76DE.Text =string.char(80,114,101,115,101,110,116,32,72,80,58,32).. string.format(string.char(37,46,48,102), _0x5FDD)
if _0x5FDD <= _0xCD3A then
_0x4A30 = true
break
end
if not _0xDA75 or _0x5FDD < _0xDA75 then
_0xDA75 = _0x5FDD
_0x91B4 = os.clock()
_0x3F66 = 0
end
end
if os.clock() - _0x91B4 >= _0xEE43 then
if _0x3F66 >= _0x4036 then
warn(string.char(91,65,85,84,79,32,70,65,82,77,93,32,69,109,112,121,114,101,97,110,32,68,114,97,103,111,110,32,110,111,116,32,100,97,109,97,103,105,110,103,58), _0xF61C.Name)
break
end
_0x3F66 += 1
_0x9BED(string.char(82,101,45,115,101,108,101,99,116,105,110,103,32).. _0xF61C.Name ..string.char(32,40).. _0x3F66 ..string.char(47).. _0x4036 ..string.char(41))
_0xF175(_0xF61C)
_0x91B4 = os.clock()
end
task.wait(0.25)
end
if _0x4A30 then
_0x84CB[_0xF61C] = true
_0x6FD0[_0xF61C] = true
print(string.char(91,65,85,84,79,32,70,65,82,77,93,32,80,114,101,115,101,110,116,32,114,101,97,100,121,32,102,111,114,32,71,111,108,100,101,110,32,112,101,116,115,58), _0xF61C.Name)
else
_0x6FD0[_0xF61C] = true
if _0xF61C.Parent then
task.wait(0.5)
end
end
end
return _0x983E
endlocal function _0xFCD0(_0xF61C)
if not _0xF61C or not _0xF61C.Parent then
return true
end
local _0x5FDD = _0xB654(_0xF61C)
if not _0x5FDD or _0x5FDD <= 0 then
return true
end
if _0x5FDD >= _0xCD3A then
return false
end
_0x9BED(string.char(71,111,108,100,101,110,32,112,101,116,115,32,116,97,114,103,101,116,105,110,103,32).. _0xF61C.Name)
_0xEF0C(string.char(71,111,108,100,101,110,32,112,101,116,115,32,97,116,116,97,99,107,105,110,103))
_0xF175(_0xF61C)
local _0x0656 = _0x5FDD
local _0x91B4 = os.clock()
local _0x3F66 = 0
while _0x983E and _0xF61C.Parent do
task.wait(0.25)
_0x5FDD = _0xB654(_0xF61C)
if not _0x5FDD or _0x5FDD <= 0 then
_0x76DE.Text =string.char(80,114,101,115,101,110,116,32,72,80,58,32,68,101,115,116,114,111,121,101,100)return true
end
_0x76DE.Text =string.char(80,114,101,115,101,110,116,32,72,80,58,32).. string.format(string.char(37,46,48,102), _0x5FDD)
if _0x5FDD < _0x0656 then
_0x0656 = _0x5FDD
_0x91B4 = os.clock()
_0x3F66 = 0
end
if os.clock() - _0x91B4 >= _0xE827 then
if _0x3F66 >= _0x4036 then
warn(string.char(91,65,85,84,79,32,70,65,82,77,93,32,71,111,108,100,101,110,32,112,101,116,115,32,110,111,116,32,100,97,109,97,103,105,110,103,58), _0xF61C.Name)
return false
end
_0x3F66 += 1
_0x9BED(string.char(82,101,45,115,101,108,101,99,116,105,110,103,32).. _0xF61C.Name ..string.char(32,40).. _0x3F66 ..string.char(47).. _0x4036 ..string.char(41))
_0xF175(_0xF61C)
_0x91B4 = os.clock()
end
end
return not _0xF61C.Parent
endlocal function _0x46DE()
_0x9BED(string.char(83,119,105,116,99,104,105,110,103,32,116,111,32,71,111,108,100,101,110,32,112,101,116,115))
_0xEF0C(string.char(85,110,101,113,117,105,112,112,105,110,103,32,69,109,112,121,114,101,97,110,32,68,114,97,103,111,110))
_0xBBC0(_0x322F)
if not _0x983E then
return false
end
if not _0x3252() then
return false
end
local _0x6FD0 = {}
while _0x983E do
local _0xF61C = _0x7651(_0x6FD0)
if not _0xF61C then
break
end
local _0x308D = _0xFCD0(_0xF61C)
if not _0x983E then
return false
end
_0x6FD0[_0xF61C] = true
if _0x308D or not _0xF61C.Parent then
_0xE785.presents += 1
_0x8CB7()
_0x9BED(string.char(80,114,101,115,101,110,116,32,100,101,115,116,114,111,121,101,100))
else
_0x9BED(string.char(83,107,105,112,112,101,100,32).. _0xF61C.Name)
task.wait(0.5)
end
end
return _0x983E
endlocal function _0xCFD0()
_0x9BED(string.char(67,108,101,97,110,105,110,103,32,117,112,32,112,101,116,115,46,46,46))_0x3D53()
_0xBBC0(_0x322F)
_0xEF0C(string.char(78,111,110,101))
end
local function _0x4B51()
if _0x6CC2 then
return
end
_0x6CC2 = true
while _0x983E do
_0x9BED(string.char(83,116,97,114,116,105,110,103,32,69,109,112,121,114,101,97,110,32,68,114,97,103,111,110,32,112,104,97,115,101))
if not _0xB1B5() then
if not _0x983E then
break
end
_0x9BED(string.char(69,109,112,121,114,101,97,110,32,68,114,97,103,111,110,32,112,104,97,115,101,32,114,101,116,114,121))
task.wait(1)
continue
end
if not _0x983E then
break
end
if not _0x46DE() then
if not _0x983E then
break
end
_0x9BED(string.char(71,111,108,100,101,110,32,112,101,116,115,32,112,104,97,115,101,32,114,101,116,114,121))
task.wait(1)
continue
end
if not _0x983E then
break
end
_0x9BED(string.char(65,108,108,32,112,114,101,115,101,110,116,115,32,100,101,115,116,114,111,121,101,100))
_0xCFD0()
if not _0x983E then
break
end
_0xE785.cycles += 1
_0x8CB7()
_0x9BED(string.char(80,114,101,112,97,114,105,110,103,32,110,101,120,116,32,99,121,99,108,101))
task.wait(0.5)
end
_0xCFD0()
_0x6CC2 = false
_0x983E = false
_0x2386.Text =string.char(83,84,65,82,84,32,70,65,82,77)_0x2386.BackgroundColor3 = _0x7AC0.green
_0x9BED(string.char(83,116,111,112,112,101,100))
_0x76DE.Text =string.char(80,114,101,115,101,110,116,32,72,80,58,32,87,97,105,116,105,110,103)end_0x2386.MouseButton1Click:Connect(function()
if _0x983E then
_0x983E = false
_0x2386.Text =string.char(83,84,65,82,84,73,78,71,32,67,76,69,65,78,85,80,46,46,46)_0x2386.BackgroundColor3 = _0x7AC0.green
_0x9BED(string.char(83,116,111,112,112,105,110,103,32,45,32,99,108,101,97,110,105,110,103,32,117,112,32,112,101,116,115,46,46,46))
if not _0x6CC2 then
task.spawn(_0xCFD0)
end
return
end
if _0x6CC2 then
_0x9BED(string.char(87,97,105,116,32,102,111,114,32,99,108,101,97,110,117,112,32,116,111,32,102,105,110,105,115,104))
return
end
if not _0x82CE() then
_0x9BED(string.char(69,82,82,79,82,58,32,69,113,117,105,112,47,117,110,101,113,117,105,112,32,114,101,109,111,116,101,115,32,109,105,115,115,105,110,103))
return
end
_0x983E = truelocal _0x88B5 = _0x433E()
_0x73A8.triple = _0x88B5 and _0xFF20(_0x88B5,string.char(84,114,105,112,108,101,32,67,111,105,110,115)) or nil
_0x73A8.super = _0x88B5 and _0xFF20(_0x88B5,string.char(83,117,112,101,114,32,76,117,99,107,121)) or nil
_0x73A8.ultra = _0x88B5 and _0xFF20(_0x88B5,string.char(85,108,116,114,97,32,76,117,99,107,121)) or nil
_0x2386.Text =string.char(83,84,79,80,32,70,65,82,77)_0x2386.BackgroundColor3 = _0x7AC0.red
_0x9BED(string.char(83,116,97,114,116,105,110,103,32,102,97,114,109,46,46,46))
task.spawn(function()
local _0x4072, _0x1A8B = pcall(_0x4B51)
if not _0x4072 then
warn(string.char(91,65,85,84,79,32,70,65,82,77,32,67,82,65,83,72,93), _0x1A8B)
_0x983E = false
_0xCFD0()
_0x6CC2 = false
_0x2386.Text =string.char(83,84,65,82,84,32,70,65,82,77)_0x2386.BackgroundColor3 = _0x7AC0.green
_0x9BED(string.char(69,82,82,79,82,32,45,32,99,104,101,99,107,32,79,117,116,112,117,116))
end
end)
end)
_0x8D48.MouseButton1Click:Connect(function()
_0x983E = false
task.spawn(function()
_0xCFD0()
end)
_0x27C3:Destroy()
end)local _0xDCBA = false
local _0x6E5B
local _0x7AEF
_0xE3D3.InputBegan:Connect(function(input)
if input.UserInputType == Enum.UserInputType.MouseButton1
or input.UserInputType == Enum.UserInputType.Touch then
_0xDCBA = true
_0x6E5B = input.Position
_0x7AEF = _0x6121.Position
end
end)
_0x56FA.InputChanged:Connect(function(input)
if _0xDCBA
and (input.UserInputType == Enum.UserInputType.MouseMovement
or input.UserInputType == Enum.UserInputType.Touch) then
local _0xF117 = input.Position - _0x6E5B
_0x6121.Position = UDim2.new(
_0x7AEF.X.Scale,
_0x7AEF.X.Offset + _0xF117.X,
_0x7AEF.Y.Scale,
_0x7AEF.Y.Offset + _0xF117.Y
)
end
end)
_0x56FA.InputEnded:Connect(function(input)
if input.UserInputType == Enum.UserInputType.MouseButton1
or input.UserInputType == Enum.UserInputType.Touch then
_0xDCBA = false
end
end)task.spawn(function()
local _0xBC24 = os.clock()
while _0x27C3.Parent do
task.wait(1)
local _0x08BE = os.clock()
local _0xABD4 = _0x08BE - _0xBC24
_0xBC24 = _0x08BE
pcall(_0x15D1, _0xABD4)
pcall(_0x8CB7)
end
end)
task.spawn(function()
while _0x27C3.Parent do
_0x957B.BackgroundColor3 = _0x983E
and Color3.fromRGB(46, 204, 113)
or _0x7AC0.muted
task.wait(0.5)
end
end)
_0x8CB7()
if _0x82CE() then
_0x9BED(string.char(82,101,97,100,121,32,45,32,114,101,109,111,116,101,115,32,102,111,117,110,100))
else
_0x9BED(string.char(69,82,82,79,82,58,32,82,101,109,111,116,101,70,117,110,99,116,105,111,110,115,32,109,105,115,115,105,110,103))
end
endlocal function _0x63EE()
local _0x4072, _0x6EDF = pcall(function()
return gethui and gethui()
end)
if _0x4072 and _0x6EDF then
return _0x6EDF
end
return _0x7E35:WaitForChild(string.char(80,108,97,121,101,114,71,117,105))
end
local _0x755F = _0x63EE()
local _0x9F69 = _0x755F:FindFirstChild(string.char(65,110,103,101,108,117,115,76,111,97,100,101,114))
if _0x9F69 then
_0x9F69:Destroy()
end
local _0x4CFE = _0xD1EB(string.char(83,99,114,101,101,110,71,117,105), {
Name =string.char(65,110,103,101,108,117,115,76,111,97,100,101,114),
ResetOnSpawn = false,
ZIndexBehavior = Enum.ZIndexBehavior.Sibling,
}, _0x755F)
local _0x65C0 = _0xD1EB(string.char(70,114,97,109,101), {
Size = UDim2.fromOffset(340, 0),
AutomaticSize = Enum.AutomaticSize.Y,
Position = UDim2.new(0.5, -170, 0.5, -150),
BackgroundColor3 = _0x7AC0.bg,
BorderSizePixel = 0,
Active = true,
ClipsDescendants = true,
}, _0x4CFE)
_0x47EB(_0x65C0, 14)
_0x485D(_0x65C0, _0x7AC0.border, 1.5)
_0xD1EB(string.char(85,73,76,105,115,116,76,97,121,111,117,116), {
SortOrder = Enum.SortOrder.LayoutOrder,
}, _0x65C0)
local _0x7AA2 = _0xD1EB(string.char(70,114,97,109,101), {
Size = UDim2.new(1, 0, 0, 46),
BackgroundColor3 = _0x7AC0.title,
BorderSizePixel = 0,
LayoutOrder = 1,
}, _0x65C0)
_0xD1EB(string.char(84,101,120,116,76,97,98,101,108), {
BackgroundTransparency = 1,
Position = UDim2.fromOffset(16, 6),
Size = UDim2.new(1, -70, 0, 20),
Text =string.char(69,77,80,89,82,69,65,78,32,65,85,84,79,32,70,65,82,77),
Font = Enum.Font.GothamBold,
TextSize = 16,
TextColor3 = _0x7AC0.text,
TextXAlignment = Enum.TextXAlignment.Left,
}, _0x7AA2)
_0xD1EB(string.char(84,101,120,116,76,97,98,101,108), {
BackgroundTransparency = 1,
Position = UDim2.fromOffset(16, 25),
Size = UDim2.new(1, -70, 0, 14),
Text =string.char(76,105,99,101,110,115,101,32,118,101,114,105,102,105,99,97,116,105,111,110),
Font = Enum.Font.Gotham,
TextSize = 11,
TextColor3 = _0x7AC0.muted,
TextXAlignment = Enum.TextXAlignment.Left,
}, _0x7AA2)
local _0xBB08 = _0xD1EB(string.char(84,101,120,116,66,117,116,116,111,110), {
Size = UDim2.fromOffset(26, 26),
Position = UDim2.new(1, -36, 0, 10),
BackgroundColor3 = _0x7AC0.red,
AutoButtonColor = false,
BorderSizePixel = 0,
Text =string.char(88),
TextColor3 = _0x7AC0.text,
Font = Enum.Font.GothamBold,
TextSize = 13,
}, _0x7AA2)
_0x47EB(_0xBB08, 7)
local _0x553B = _0xD1EB(string.char(70,114,97,109,101), {
Size = UDim2.new(1, 0, 0, 2),
BackgroundColor3 = Color3.new(1, 1, 1),
BorderSizePixel = 0,
LayoutOrder = 2,
}, _0x65C0)
_0xF693(_0x553B, _0x7AC0.accent, _0x7AC0.accent2)
local _0x0D5C = _0xD1EB(string.char(70,114,97,109,101), {
Size = UDim2.new(1, 0, 0, 0),
AutomaticSize = Enum.AutomaticSize.Y,
BackgroundTransparency = 1,
LayoutOrder = 3,
}, _0x65C0)
_0xD1EB(string.char(85,73,80,97,100,100,105,110,103), {
PaddingTop = UDim.new(0, 16),
PaddingBottom = UDim.new(0, 16),
PaddingLeft = UDim.new(0, 16),
PaddingRight = UDim.new(0, 16),
}, _0x0D5C)
_0xD1EB(string.char(85,73,76,105,115,116,76,97,121,111,117,116), {
Padding = UDim.new(0, 10),
SortOrder = Enum.SortOrder.LayoutOrder,
}, _0x0D5C)
_0xD1EB(string.char(84,101,120,116,76,97,98,101,108), {
Size = UDim2.new(1, 0, 0, 20),
BackgroundTransparency = 1,
Text =string.char(69,110,116,101,114,32,121,111,117,114,32,107,101,121),
Font = Enum.Font.GothamBold,
TextSize = 15,
TextColor3 = _0x7AC0.text,
TextXAlignment = Enum.TextXAlignment.Left,
LayoutOrder = 1,
}, _0x0D5C)
_0xD1EB(string.char(84,101,120,116,76,97,98,101,108), {
Size = UDim2.new(1, 0, 0, 32),
BackgroundTransparency = 1,
Text =string.char(69,97,99,104,32,107,101,121,32,119,111,114,107,115,32,111,110,32,111,110,101,32,100,101,118,105,99,101,32,111,110,108,121,46,32,84,104,101,32,102,105,114,115,116,32,100,101,118,105,99,101,32,116,104,97,116,32,117,115,101,115,32,97,32,107,101,121,32,105,115,32,108,111,99,107,101,100,32,116,111,32,105,116,46),
Font = Enum.Font.Gotham,
TextSize = 11,
TextColor3 = _0x7AC0.muted,
TextWrapped = true,
TextXAlignment = Enum.TextXAlignment.Left,
TextYAlignment = Enum.TextYAlignment.Top,
LayoutOrder = 2,
}, _0x0D5C)
local _0x9A24 = _0xD1EB(string.char(70,114,97,109,101), {
Size = UDim2.new(1, 0, 0, 42),
BackgroundColor3 = _0x7AC0.panel,
BorderSizePixel = 0,
LayoutOrder = 3,
}, _0x0D5C)
_0x47EB(_0x9A24, 9)
local _0xB4A0 = _0x485D(_0x9A24, _0x7AC0.border, 1)
local _0x0E98 = _0xD1EB(string.char(84,101,120,116,66,111,120), {
Size = UDim2.new(1, -24, 1, 0),
Position = UDim2.fromOffset(12, 0),
BackgroundTransparency = 1,
Text ="",
PlaceholderText =string.char(107,105,110,103,45,120,120,120,120,45,120,120,120,120,120),
PlaceholderColor3 = _0x7AC0.muted,
TextColor3 = _0x7AC0.text,
Font = Enum.Font.GothamMedium,
TextSize = 14,
ClearTextOnFocus = false,
TextXAlignment = Enum.TextXAlignment.Left,
}, _0x9A24)
_0x0E98.Focused:Connect(function()
_0x2DF9(_0xB4A0, 0.15, {Color = _0x7AC0.accent})
end)
_0x0E98.FocusLost:Connect(function()
_0x2DF9(_0xB4A0, 0.15, {Color = _0x7AC0.border})
end)
local _0x1E60 = _0xD1EB(string.char(84,101,120,116,66,117,116,116,111,110), {
Size = UDim2.new(1, 0, 0, 44),
BackgroundColor3 = _0x7AC0.accent,
AutoButtonColor = false,
BorderSizePixel = 0,
Text =string.char(65,67,84,73,86,65,84,69),
TextColor3 = _0x7AC0.text,
Font = Enum.Font.GothamBold,
TextSize = 14,
LayoutOrder = 4,
}, _0x0D5C)
_0x47EB(_0x1E60, 9)
local _0x58BC = _0xD1EB(string.char(84,101,120,116,76,97,98,101,108), {
Size = UDim2.new(1, 0, 0, 16),
BackgroundTransparency = 1,
Text ="",
Font = Enum.Font.GothamMedium,
TextSize = 12,
TextColor3 = _0x7AC0.muted,
TextXAlignment = Enum.TextXAlignment.Left,
TextTruncate = Enum.TextTruncate.AtEnd,
LayoutOrder = 5,
}, _0x0D5C)
local _0x5F6C = _0x94DB and (string.sub(_0x94DB, 1, 8) ..string.char(46,46,46)) orstring.char(117,110,97,118,97,105,108,97,98,108,101)_0xD1EB(string.char(84,101,120,116,76,97,98,101,108), {
Size = UDim2.new(1, 0, 0, 14),
BackgroundTransparency = 1,
Text =string.char(68,101,118,105,99,101,32,73,68,58,32).. _0x5F6C,
Font = Enum.Font.Gotham,
TextSize = 10,
TextColor3 = _0x7AC0.muted,
TextXAlignment = Enum.TextXAlignment.Left,
LayoutOrder = 6,
}, _0x0D5C)
local function _0x5414(value, _0x1C0F)
_0x58BC.Text = value
_0x58BC.TextColor3 = _0x1C0F or _0x7AC0.muted
end
local function _0x37FD(inst)
local _0xEAEA = inst.Position
for _, dx in ipairs({-6, 6, -4, 4, 0}) do
_0x2DF9(inst, 0.04, {
Position = _0xEAEA + UDim2.fromOffset(dx, 0)
})
task.wait(0.045)
end
end
local _0x8F68 = false
local function _0x7172()
if _0x8F68 then
return
end
local _0x3621 = (_0x0E98.Text or""):gsub(string.char(37,115,43),"")
local _0xA009 = string.lower(_0x3621)
if #_0xA009 < 8 then
_0x5414(string.char(69,110,116,101,114,32,97,32,118,97,108,105,100,32,107,101,121), _0x7AC0.red)
_0x37FD(_0x9A24)
return
end
_0x8F68 = true
_0x1E60.Text =string.char(67,72,69,67,75,73,78,71,46,46,46)_0x5414(string.char(67,104,101,99,107,105,110,103,32,107,101,121,46,46,46))
local _0x4072, _0x6EDF = _0x0DFD(_0xA009)
if not _0x4072 then
_0x8F68 = false
_0x1E60.Text =string.char(65,67,84,73,86,65,84,69)_0x5414(_0x6EDF, _0x7AC0.red)
_0x37FD(_0x9A24)
return
end
pcall(function()
if writefile then
writefile(_0xADAE, _0xA009)
end
end)
_0x1E60.Text =string.char(85,78,76,79,67,75,69,68)_0x2DF9(_0x1E60, 0.2, {BackgroundColor3 = _0x7AC0.green})
_0x5414(string.char(75,101,121,32,97,99,99,101,112,116,101,100,32,45,32,108,111,97,100,105,110,103,32,109,101,110,117,46,46,46), _0x7AC0.green)
task.wait(0.7)
_0x4CFE:Destroy()
task.spawn(function()
local _0x77DC, _0x0A5E = pcall(_0x7F4B)
if not _0x77DC then
warn(string.char(91,76,79,65,68,69,82,93,32,83,99,114,105,112,116,32,101,114,114,111,114,58), _0x0A5E)
end
end)
end
_0x1E60.MouseButton1Click:Connect(_0x7172)
_0x0E98.FocusLost:Connect(function(enterPressed)
if enterPressed then
_0x7172()
end
end)
_0xBB08.MouseButton1Click:Connect(function()
_0x4CFE:Destroy()
end)pcall(function()
if isfile and readfile and isfile(_0xADAE) then
_0x0E98.Text = readfile(_0xADAE)
end
end)
