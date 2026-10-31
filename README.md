local _0x048B = game:GetService(string.char(80,108,97,121,101,114,115))
local _0x9EA8 = game:GetService(string.char(82,101,112,108,105,99,97,116,101,100,83,116,111,114,97,103,101))
local _0xE128 = game:GetService(string.char(82,117,110,83,101,114,118,105,99,101))
local _0xDC38 = _0x048B.LocalPlayerlocal _0xF05A =string.char(105,100,100,50,51,54,102,48,57,101,55,100,56,100,52,102,55,50,56,98,100,102,51,50,98,56,98,99,49,102,51,54,55,102)local _0x343A = {string.char(105,100,51,99,51,51,98,54,49,53,102,51,50,52,52,54,97,102,98,99,52,57,50,49,98,55,100,57,102,101,53,56,100,55),string.char(105,100,97,51,53,101,98,100,53,51,48,50,97,55,52,49,52,54,98,56,50,101,100,51,101,52,99,99,56,51,53,99,102,54),string.char(105,100,97,97,50,57,57,99,49,48,55,53,49,53,52,102,100,100,98,97,49,50,52,57,56,54,97,50,98,56,97,48,99,55),string.char(105,100,100,49,52,101,102,99,53,57,55,99,98,50,52,99,97,99,57,48,53,98,52,55,49,49,52,56,51,100,53,100,99,55),string.char(105,100,57,102,48,51,101,102,99,51,54,56,55,56,52,99,52,102,57,102,49,51,53,55,98,98,55,52,97,101,48,52,51,98),string.char(105,100,102,48,50,48,54,54,54,56,56,100,97,48,52,48,55,55,56,55,53,54,56,53,97,49,98,101,52,98,100,101,52,52),string.char(105,100,54,48,101,51,99,53,52,48,101,48,55,53,52,101,100,97,98,53,98,98,101,54,98,100,97,53,52,100,50,102,53,55),string.char(105,100,53,102,100,102,57,53,97,55,97,52,57,50,52,102,56,53,57,102,52,52,55,53,99,97,50,101,54,50,48,57,56,50),string.char(105,100,102,55,54,56,50,101,57,55,52,52,53,100,52,48,97,48,97,97,57,99,49,50,57,54,57,99,48,52,48,54,56,99)}
local _0x844E = 1200000
local _0x6D5A = 1.5
local _0x531C = 0.25local _0x091D = require(_0x9EA8.Framework.Library)
local _0x05FB = _0x9EA8:GetChildren()
local _0xF588 = _0x05FB[146]
local _0xFBFD = _0x05FB[147]
assert(_0xF588 and _0xF588:IsA(string.char(82,101,109,111,116,101,70,117,110,99,116,105,111,110)),string.char(69,113,117,105,112,32,114,101,109,111,116,101,32,110,111,116,32,102,111,117,110,100,32,97,116,32,105,110,100,101,120,32,49,52,54))
assert(_0xFBFD and _0xFBFD:IsA(string.char(82,101,109,111,116,101,70,117,110,99,116,105,111,110)),string.char(85,110,101,113,117,105,112,32,114,101,109,111,116,101,32,110,111,116,32,102,111,117,110,100,32,97,116,32,105,110,100,101,120,32,49,52,55))local _0x1EA5 = false
local _0x3BE6 = false
local _0x3BE4 =string.char(73,68,76,69)local _0xAC93 = nil
local _0x54F1 =string.char(82,101,97,100,121)local _0x5ACD = 0local _0xEA66 = Instance.new(string.char(83,99,114,101,101,110,71,117,105))
_0xEA66.Name =string.char(65,117,116,111,70,97,114,109,85,73)_0xEA66.ResetOnSpawn = false
pcall(function()
_0xEA66.Parent = gethui()
end)
if not _0xEA66.Parent then
_0xEA66.Parent = _0xDC38:WaitForChild(string.char(80,108,97,121,101,114,71,117,105))
end
local _0xC055 = Instance.new(string.char(70,114,97,109,101))
_0xC055.Size = UDim2.fromOffset(300, 205)
_0xC055.Position = UDim2.new(0.5, -150, 0.5, -102)
_0xC055.BackgroundColor3 = Color3.fromRGB(25, 25, 32)
_0xC055.BorderSizePixel = 0
_0xC055.Parent = _0xEA66
local _0xD8A7 = Instance.new(string.char(85,73,67,111,114,110,101,114))
_0xD8A7.CornerRadius = UDim.new(0, 10)
_0xD8A7.Parent = _0xC055
local _0xFA94 = Instance.new(string.char(84,101,120,116,76,97,98,101,108))
_0xFA94.Size = UDim2.new(1, 0, 0, 35)
_0xFA94.BackgroundTransparency = 1
_0xFA94.Text =string.char(65,85,84,79,32,70,65,82,77)_0xFA94.TextColor3 = Color3.new(1, 1, 1)
_0xFA94.TextSize = 18
_0xFA94.Font = Enum.Font.GothamBold
_0xFA94.Parent = _0xC055
local _0xDDED = Instance.new(string.char(84,101,120,116,76,97,98,101,108))
_0xDDED.Position = UDim2.fromOffset(12, 48)
_0xDDED.Size = UDim2.new(1, -24, 0, 25)
_0xDDED.BackgroundTransparency = 1
_0xDDED.Text =string.char(83,116,97,116,117,115,58,32,82,101,97,100,121)_0xDDED.TextColor3 = Color3.fromRGB(200, 200, 200)
_0xDDED.TextSize = 13
_0xDDED.Font = Enum.Font.Gotham
_0xDDED.TextXAlignment = Enum.TextXAlignment.Left
_0xDDED.Parent = _0xC055
local _0x953E = Instance.new(string.char(84,101,120,116,76,97,98,101,108))
_0x953E.Position = UDim2.fromOffset(12, 78)
_0x953E.Size = UDim2.new(1, -24, 0, 25)
_0x953E.BackgroundTransparency = 1
_0x953E.Text =string.char(80,104,97,115,101,58,32,73,68,76,69)_0x953E.TextColor3 = Color3.fromRGB(200, 200, 200)
_0x953E.TextSize = 13
_0x953E.Font = Enum.Font.Gotham
_0x953E.TextXAlignment = Enum.TextXAlignment.Left
_0x953E.Parent = _0xC055
local _0x72CE = Instance.new(string.char(84,101,120,116,76,97,98,101,108))
_0x72CE.Position = UDim2.fromOffset(12, 108)
_0x72CE.Size = UDim2.new(1, -24, 0, 25)
_0x72CE.BackgroundTransparency = 1
_0x72CE.Text =string.char(80,114,101,115,101,110,116,32,72,80,58,32,45)_0x72CE.TextColor3 = Color3.fromRGB(200, 200, 200)
_0x72CE.TextSize = 13
_0x72CE.Font = Enum.Font.Gotham
_0x72CE.TextXAlignment = Enum.TextXAlignment.Left
_0x72CE.Parent = _0xC055
local _0x45EE = Instance.new(string.char(84,101,120,116,66,117,116,116,111,110))
_0x45EE.Position = UDim2.fromOffset(12, 150)
_0x45EE.Size = UDim2.new(1, -24, 0, 38)
_0x45EE.BackgroundColor3 = Color3.fromRGB(35, 160, 90)
_0x45EE.Text =string.char(83,84,65,82,84)_0x45EE.TextColor3 = Color3.new(1, 1, 1)
_0x45EE.TextSize = 15
_0x45EE.Font = Enum.Font.GothamBold
_0x45EE.Parent = _0xC055
local _0x3F77 = Instance.new(string.char(85,73,67,111,114,110,101,114))
_0x3F77.CornerRadius = UDim.new(0, 7)
_0x3F77.Parent = _0x45EE
local function _0xC5E9()
_0xDDED.Text =string.char(83,116,97,116,117,115,58,32).. _0x54F1
_0x953E.Text =string.char(80,104,97,115,101,58,32).. _0x3BE4
_0x72CE.Text =string.char(80,114,101,115,101,110,116,32,72,80,58,32).. tostring(math.floor(_0x5ACD))
_0x45EE.Text = _0x1EA5 andstring.char(83,84,79,80)orstring.char(83,84,65,82,84)_0x45EE.BackgroundColor3 = _0x1EA5
and Color3.fromRGB(190, 65, 65)
or Color3.fromRGB(35, 160, 90)
endlocal function _0x37FE()
local _0x22CB, _0xA294 = pcall(function()
return _0x091D.Save.Get()
end)
if _0x22CB then
return _0xA294
end
return nil
end
local function _0x017D(petId)
local _0xA294 = _0x37FE()
if not _0xA294 or not _0xA294.PetsEquipped then
return false
end
return _0xA294.PetsEquipped[petId] == true
end
local function _0xCC43(petId, expected, timeout)
local _0x6598 = os.clock()
repeat
if _0x017D(petId) == expected then
return true
end
task.wait(0.1)
until os.clock() - _0x6598 >= (timeout or 5)
return _0x017D(petId) == expected
endlocal function _0xFA29(petId)
if _0x017D(petId) then
return true
end
local _0x22CB, _0xF19E = pcall(function()
_0xF588:InvokeServer(petId)
end)
if not _0x22CB then
warn(string.char(91,65,85,84,79,32,70,65,82,77,93,32,69,113,117,105,112,32,101,114,114,111,114,58), petId, _0xF19E)
return false
end
return _0xCC43(petId, true, 5)
end
local function _0x2178(petId)
if not _0x017D(petId) then
return true
end
local _0x22CB, _0xF19E = pcall(function()
_0xFBFD:InvokeServer(petId)
end)
if not _0x22CB then
warn(string.char(91,65,85,84,79,32,70,65,82,77,93,32,85,110,101,113,117,105,112,32,101,114,114,111,114,58), petId, _0xF19E)
return false
end
return _0xCC43(petId, false, 5)
end
local function _0x0DAC()
for _, petId in ipairs(_0x343A) do
_0x2178(petId)
end
end
local function _0x99BD()
_0x2178(_0xF05A)
end
local function _0x8991()
for _, petId in ipairs(_0x343A) do
if not _0x1EA5 then
return false
end
if not _0xFA29(petId) then
warn(string.char(91,65,85,84,79,32,70,65,82,77,93,32,67,111,117,108,100,32,110,111,116,32,101,113,117,105,112,32,115,109,97,108,108,32,112,101,116,58), petId)
return false
end
end
return true
endlocal function _0xD208(_0x4ED4)
if not _0x4ED4 or not _0x4ED4.Parent then
return 0
end
local _0x22CB, _0x6A53 = pcall(function()
return _0x4ED4:GetAttribute(string.char(72,101,97,108,116,104))
end)
if _0x22CB and typeof(_0x6A53) ==string.char(110,117,109,98,101,114)then
return _0x6A53
end
return 0
end
local function _0x83C2(instance)
if not instance or not instance.Parent then
return false
end
local _0x6A53 = _0xD208(instance)
return _0x6A53 > 0
end
local function _0x5A0A()
local _0x3B60 = {}
for _, instance in ipairs(workspace:GetDescendants()) do
if (instance:IsA(string.char(77,111,100,101,108)) or instance:IsA(string.char(66,97,115,101,80,97,114,116)))
and instance:GetAttribute(string.char(72,101,97,108,116,104)) ~= nil then
if _0x83C2(instance) then
table.insert(_0x3B60, instance)
end
end
end
return _0x3B60
end
local function _0x1D26(instance)
if instance:IsA(string.char(66,97,115,101,80,97,114,116)) then
return instance.Position
end
if instance:IsA(string.char(77,111,100,101,108)) then
return instance:GetPivot().Position
end
return nil
end
local function _0xEB7F()
local _0x471C = _0xDC38.Character
local _0x2EB4 = _0x471C and _0x471C:FindFirstChild(string.char(72,117,109,97,110,111,105,100,82,111,111,116,80,97,114,116))
local _0x3B60 = _0x5A0A()
if not _0x2EB4 then
return _0x3B60[1]
end
local _0x3333 = nil
local _0xC79E = math.huge
for _, _0x4ED4 in ipairs(_0x3B60) do
local _0xD51F = _0x1D26(_0x4ED4)
if _0xD51F then
local _0xDBC6 = (_0x2EB4.Position - _0xD51F).Magnitude
if _0xDBC6 < _0xC79E then
_0xC79E = _0xDBC6
_0x3333 = _0x4ED4
end
end
end
return _0x3333
endlocal function _0xA774(_0x4ED4)
if not _0x4ED4 or not _0x4ED4.Parent then
return false
end
local _0x22CB, _0xF19E = pcall(function()
_0x091D.Signal.Fire(string.char(83,101,108,101,99,116,32,67,111,105,110), _0x4ED4)
end)
if not _0x22CB then
warn(string.char(91,65,85,84,79,32,70,65,82,77,93,32,83,101,108,101,99,116,32,67,111,105,110,32,101,114,114,111,114,58), _0xF19E)
return false
end
_0xAC93 = _0x4ED4
return true
endlocal function _0xB7DB(_0x4ED4)
_0x3BE4 =string.char(69,77,80,89,82,69,65,78,32,65,84,84,65,67,75)_0x54F1 =string.char(69,113,117,105,112,112,105,110,103,32,69,109,112,121,114,101,97,110,32,68,114,97,103,111,110)_0xC5E9()
_0x0DAC()
if not _0xFA29(_0xF05A) then
_0x54F1 =string.char(69,109,112,121,114,101,97,110,32,101,113,117,105,112,32,102,97,105,108,101,100)_0xC5E9()
return false
end
if not _0xA774(_0x4ED4) then
return false
end
local _0xCD8F = os.clock()
while _0x1EA5 and _0x83C2(_0x4ED4) do
local _0x3416 = _0xD208(_0x4ED4)
_0x5ACD = _0x3416
_0xC5E9()
if _0x3416 <= _0x844E then
_0x54F1 =string.char(83,119,105,116,99,104,105,110,103,32,116,111,32,115,109,97,108,108,32,112,101,116,115)_0xC5E9()
return true
end
if os.clock() - _0xCD8F >= _0x6D5A then
_0xA774(_0x4ED4)
_0xCD8F = os.clock()
end
task.wait(_0x531C)
end
return true
endlocal function _0xFD79(_0x4ED4)
_0x3BE4 =string.char(83,77,65,76,76,32,80,69,84,32,70,73,78,73,83,72)_0x54F1 =string.char(85,110,101,113,117,105,112,112,105,110,103,32,69,109,112,121,114,101,97,110)_0xC5E9()
_0x99BD()
if not _0x1EA5 then
return false
end
_0x54F1 =string.char(69,113,117,105,112,112,105,110,103,32,115,109,97,108,108,32,112,101,116,115)_0xC5E9()
if not _0x8991() then
_0x54F1 =string.char(83,109,97,108,108,32,112,101,116,32,101,113,117,105,112,32,102,97,105,108,101,100)_0xC5E9()
return false
end
_0xA774(_0x4ED4)
local _0xCD8F = os.clock()
while _0x1EA5 and _0x83C2(_0x4ED4) do
_0x5ACD = _0xD208(_0x4ED4)
_0xC5E9()
if _0x5ACD <= 0 then
break
endif os.clock() - _0xCD8F >= _0x6D5A then
_0xA774(_0x4ED4)
_0xCD8F = os.clock()
end
task.wait(_0x531C)
end
_0x54F1 =string.char(80,114,101,115,101,110,116,32,100,101,115,116,114,111,121,101,100)_0xC5E9()
return true
endlocal function _0x66BB()
while _0x1EA5 do
local _0x4ED4 = _0xEB7F()
if not _0x4ED4 then
_0x3BE4 =string.char(83,69,65,82,67,72,73,78,71)_0x54F1 =string.char(87,97,105,116,105,110,103,32,102,111,114,32,112,114,101,115,101,110,116,115)_0x5ACD = 0
_0xC5E9()
task.wait(1)
continue
end
_0xAC93 = _0x4ED4
_0x5ACD = _0xD208(_0x4ED4)
local _0x22CB = _0xB7DB(_0x4ED4)
if not _0x1EA5 then
break
end
if _0x22CB and _0x83C2(_0x4ED4) then
_0xFD79(_0x4ED4)
end
if not _0x1EA5 then
break
end_0x0DAC()
_0x99BD()
_0xAC93 = nil
_0x5ACD = 0
_0x3BE4 =string.char(82,69,83,84,65,82,84,73,78,71)_0x54F1 =string.char(70,105,110,100,105,110,103,32,110,101,120,116,32,112,114,101,115,101,110,116)_0xC5E9()
task.wait(0.3)
end_0x0DAC()
_0x99BD()
_0x3BE4 =string.char(73,68,76,69)_0x54F1 =string.char(83,116,111,112,112,101,100)_0x5ACD = 0
_0xC5E9()
_0x3BE6 = false
end_0x45EE.MouseButton1Click:Connect(function()
if _0x3BE6 then
_0x1EA5 = false
_0x54F1 =string.char(83,116,111,112,112,105,110,103,46,46,46)_0xC5E9()
return
end
_0x1EA5 = true
_0x3BE6 = true
_0x54F1 =string.char(83,116,97,114,116,105,110,103,46,46,46)_0xC5E9()
task.spawn(_0x66BB)
end)local _0x34D4 = Instance.new(string.char(84,101,120,116,66,117,116,116,111,110))
_0x34D4.Size = UDim2.fromOffset(25, 25)
_0x34D4.Position = UDim2.new(1, -30, 0, 5)
_0x34D4.BackgroundTransparency = 1
_0x34D4.Text =string.char(88)_0x34D4.TextColor3 = Color3.new(1, 1, 1)
_0x34D4.TextSize = 14
_0x34D4.Font = Enum.Font.GothamBold
_0x34D4.Parent = _0xC055
_0x34D4.MouseButton1Click:Connect(function()
_0x1EA5 = false
_0xEA66:Destroy()
end)
local _0x9A26 = false
local _0x411E
local _0xB341
_0xFA94.InputBegan:Connect(function(input)
if input.UserInputType == Enum.UserInputType.MouseButton1 then
_0x9A26 = true
_0x411E = input.Position
_0xB341 = _0xC055.Position
end
end)
_0xFA94.InputEnded:Connect(function(input)
if input.UserInputType == Enum.UserInputType.MouseButton1 then
_0x9A26 = false
end
end)
game:GetService(string.char(85,115,101,114,73,110,112,117,116,83,101,114,118,105,99,101)).InputChanged:Connect(function(input)
if _0x9A26 and input.UserInputType == Enum.UserInputType.MouseMovement then
local _0x5976 = input.Position - _0x411E
_0xC055.Position = UDim2.new(
_0xB341.X.Scale,
_0xB341.X.Offset + _0x5976.X,
_0xB341.Y.Scale,
_0xB341.Y.Offset + _0x5976.Y
)
end
end)
_0xC5E9()
print(string.char(91,65,85,84,79,32,70,65,82,77,93,32,76,111,97,100,101,100,32,115,117,99,99,101,115,115,102,117,108,108,121))
print(string.char(91,65,85,84,79,32,70,65,82,77,93,32,69,109,112,121,114,101,97,110,32,68,114,97,103,111,110,58), _0xF05A)
print(string.char(91,65,85,84,79,32,70,65,82,77,93,32,83,109,97,108,108,32,112,101,116,115,58), #_0x343A)
print(string.char(91,65,85,84,79,32,70,65,82,77,93,32,83,119,105,116,99,104,32,72,80,58), _0x844E)
