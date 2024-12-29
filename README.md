_G.Key = "Free [Key]"  -- Set the correct key

local Keycheck = _G.Key  -- Fetch the key from the global variable

if Keycheck == "Free [Key]" then


--//---//----//---//---//----//---//---//----//---//---//----//---//---//----//
--// XXX Hub by XXX --//

wait(0.1)
warn("Script : Fish [FREE]")
wait(0.1)
warn("Anti AFK Actived")
wait(0.1)
warn("Thank to " .. game.Players.LocalPlayer.Name)



--//---//----//---//---//----//---//---//----//---//---//----//---//---//----//
--//---//----//---//---//----//---//---//----//---//---//----//---//---//----//
--// AutoLevelFarm--//


_G.index = false -- กำหนดค่าเริ่มต้นให้ _G.index เป็น false
_G.indexV2 = false 
_G.Tool1 = false -- Flag to control the loop
_G.Autoprompt = false


task.spawn(function()
    -- เช็คว่าค่า _G.index เป็น true หรือไม่ ถ้าเป็น true จะเริ่มทำงาน
    while true do
        task.wait(0.1)  -- รอเวลานิดหน่อยก่อนทำงานต่อ
        if _G.index then
           local positions = {
    Vector3.new(2435, 130, -730),
    Vector3.new(2445, 128, -720),
    Vector3.new(2446, 128, -732),
    Vector3.new(2447, 128, -712),
    Vector3.new(2449, 132, -703),
    Vector3.new(2453, 128, -693),
    Vector3.new(2453, 128, -686),
    Vector3.new(2453, 129, -678),
    Vector3.new(2461, 129, -678),
    Vector3.new(2474, 130, -682),
    Vector3.new(2481, 130, -681),
    Vector3.new(2463, 129, -660),
    Vector3.new(2469, 128, -662),
    Vector3.new(2473, 130, -656),
    Vector3.new(2484, 130, -656),
    Vector3.new(2484, 128, -664),
    Vector3.new(2492, 130, -656),
    Vector3.new(2500, 128, -664),
    Vector3.new(2500, 130, -656),
    Vector3.new(2514, 128, -663),
    Vector3.new(2514, 130, -657),
    Vector3.new(2532, 131, -616),
    Vector3.new(2539, 131, -619),
    Vector3.new(2544, 130, -623),
    Vector3.new(2542, 131, -636),
    Vector3.new(2535, 133, -638),
    Vector3.new(2529, 133, -640),
    Vector3.new(2545, 128, -644),
    Vector3.new(2546, 128, -651),
    Vector3.new(2550, 129, -658),
    Vector3.new(2560, 130, -690),
    Vector3.new(2567, 130, -693),
    Vector3.new(2574, 134, -698),
    Vector3.new(2581, 131, -696),
    Vector3.new(2588, 130, -696),
    Vector3.new(2598, 133, -690),
    Vector3.new(2612, 130, -684),
    Vector3.new(2620, 129, -685),
    Vector3.new(2627, 129, -685),
    Vector3.new(2633, 129, -684),
    Vector3.new(2640, 129, -684),
    Vector3.new(2647, 130, -680),
    Vector3.new(2647, 128, -688),
    Vector3.new(2654, 128, -686),
    Vector3.new(2654, 130, -679),
    Vector3.new(2660, 134, -688),
    Vector3.new(2663, 130, -694),
    Vector3.new(2664, 130, -678),
    Vector3.new(2671, 130, -678),
    Vector3.new(2672, 128, -685),
    Vector3.new(2678, 130, -684),
    Vector3.new(2685, 130, -684),
    Vector3.new(2692, 130, -684),
    Vector3.new(2698, 130, -683),
    Vector3.new(2705, 130, -682),
    Vector3.new(2712, 130, -681),
    Vector3.new(2719, 130, -681),
    Vector3.new(2726, 130, -687),
    Vector3.new(2731, 133, -694),
    Vector3.new(2733, 130, -685),
    Vector3.new(2546, 130, -726),
    Vector3.new(2539, 130, -728),
    Vector3.new(2532, 130, -728),
    Vector3.new(2525, 130, -727),
    Vector3.new(2505, 131, -720),
    Vector3.new(2499, 131, -720),
    Vector3.new(2468, 130, -733),
    Vector3.new(2476, 130, -735),
    Vector3.new(2482, 130, -735),
    Vector3.new(2432, 130, -730),
    Vector3.new(2440, 129, -731),
    Vector3.new(2447, 128, -733),
    Vector3.new(2448, 128, -726),
    Vector3.new(2446, 128, -718),
    Vector3.new(2429, 128, -784),
    Vector3.new(2434, 128, -803),
    Vector3.new(2453, 131, -770),
    Vector3.new(2484, 131, -798),
    Vector3.new(2491, 131, -798),
    Vector3.new(2498, 131, -798),
    Vector3.new(2506, 131, -799),
    Vector3.new(2514, 131, -799),
    Vector3.new(2523, 131, -799),
    Vector3.new(2528, 131, -799),
    Vector3.new(2531, 132, -809),
    Vector3.new(2538, 130, -776),
    Vector3.new(2545, 129, -767),
    Vector3.new(2549, 130, -786),
    Vector3.new(2556, 130, -785),
    Vector3.new(2563, 131, -784),
    Vector3.new(2557, 130, -765),
    Vector3.new(2568, 131, -791),
    Vector3.new(2573, 131, -798),
    Vector3.new(2578, 131, -805),
    Vector3.new(2561, 130, -821),
    Vector3.new(2624, 131, -729),
    Vector3.new(2620, 132, -737),
    Vector3.new(2618, 128, -746),
    Vector3.new(2618, 128, -756),
    Vector3.new(2618, 128, -764),
    Vector3.new(2618, 128, -771),
    Vector3.new(2618, 128, -779),
    Vector3.new(2618, 128, -788),
    Vector3.new(2632, 130, -702),
    Vector3.new(2631, 130, -708),
    Vector3.new(2631, 130, -715),
    Vector3.new(2638, 132, -716),
    Vector3.new(2645, 130, -717),
    Vector3.new(2652, 130, -711),
    Vector3.new(2659, 131, -717),
    Vector3.new(2667, 130, -717),
    Vector3.new(2674, 131, -710),
    Vector3.new(2644, 129, -804),
    Vector3.new(2643, 128, -812),
    Vector3.new(2652, 129, -808),
    Vector3.new(2651, 128, -815),
    Vector3.new(2658, 129, -809),
    Vector3.new(2657, 128, -816),
    Vector3.new(2665, 129, -810),
    Vector3.new(2665, 128, -817),
    Vector3.new(2672, 129, -811),
    Vector3.new(2672, 128, -818),
    Vector3.new(2679, 129, -812),
    Vector3.new(2678, 128, -819),
    Vector3.new(2685, 129, -813),
    Vector3.new(2685, 128, -819),
    Vector3.new(2692, 129, -811),
    Vector3.new(2699, 129, -811),
    Vector3.new(2707, 129, -813)
    
    
}

            local deployTarget = CFrame.new(354.9398193359375, 131.8998565673828, 198.7338104248047, 
                                            -0.07539307326078415, 0, 0.9971538782119751, 
                                            0, 1, -0, 
                                            -0.9971538782119751, 0, -0.07539307326078415)

            -- ลูปผ่านแต่ละตำแหน่งและการปล่อย Crab Cage
            for index, position in ipairs(positions) do
                -- ตรวจสอบว่า _G.index เป็น false หรือไม่ ถ้าเป็น false จะหยุดลูป
                if not _G.index then
                    break
                end

                -- ย้ายตัวละครไปยังตำแหน่ง
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(position)
                
                -- ปล่อย Crab Cage
                local crabCage = game.Players.LocalPlayer.Character:FindFirstChild("Crab Cage")
                if crabCage and crabCage:FindFirstChild("Deploy") then
                    crabCage.Deploy:FireServer(deployTarget)

                end
                
                -- รอเวลาเล็กน้อยก่อนที่จะไปตำแหน่งถัดไป
                wait(0.3)
                
                -- ตรวจสอบว่าถึงตำแหน่งสุดท้ายแล้วหรือยัง
                if index == #positions then
                    _G.index = false
                   _G.indexV2 = true
                end
            end
        end
    end
end)
task.spawn(function()
    while true do
        task.wait(0.1)
        if _G.indexV2 then
 local targets = {
    {Vector3.new(2728, 133, -717), math.rad(170)},
    {Vector3.new(2720, 133, -719), math.rad(170)},
    {Vector3.new(2713, 133, -721), math.rad(170)},
    {Vector3.new(2705, 133, -722), math.rad(170)},
    {Vector3.new(2693, 132, -726), math.rad(150)},
    {Vector3.new(2687, 132, -729), math.rad(150)},
    {Vector3.new(2680, 132, -732), math.rad(150)},
    {Vector3.new(2665, 133, -741), math.rad(150)},
    {Vector3.new(2659, 133, -744), math.rad(150)},
    {Vector3.new(2653, 133, -748), math.rad(150)},
    {Vector3.new(2636, 130, -751), math.rad(170)},
    {Vector3.new(2633, 130, -755), math.rad(110)},
    {Vector3.new(2632, 130, -762), math.rad(110)},
    {Vector3.new(2632, 130, -767), math.rad(90)},
    {Vector3.new(2632, 130, -774), math.rad(90)},
    {Vector3.new(2632, 130, -782), math.rad(90)},
    {Vector3.new(2637, 133, -800), math.rad(100)},
    {Vector3.new(2636, 134, -807), math.rad(100)},
    {Vector3.new(2635, 135, -814), math.rad(100)},
    {Vector3.new(2634, 135, -821), math.rad(100)},
    {Vector3.new(2618, 131, -828), math.rad(190)},
    {Vector3.new(2611, 131, -828), math.rad(190)},
    {Vector3.new(2605, 131, -827), math.rad(190)},
    {Vector3.new(2598, 131, -830), math.rad(190)},
    {Vector3.new(2591, 131, -830), math.rad(190)},
    {Vector3.new(2584, 131, -829), math.rad(170)},
    {Vector3.new(2585, 131, -836), math.rad(80)},
    {Vector3.new(2586, 131, -843), math.rad(80)},
    {Vector3.new(2587, 131, -850), math.rad(80)},
    {Vector3.new(2589, 131, -858), math.rad(80)},
    {Vector3.new(2591, 131, -864), math.rad(80)},
    {Vector3.new(2592, 131, -871), math.rad(80)},
    {Vector3.new(2593, 131, -878), math.rad(80)},
    {Vector3.new(2595, 131, -886), math.rad(80)},
    {Vector3.new(2598, 131, -892), math.rad(80)},
    {Vector3.new(2600, 131, -899), math.rad(80)},
    {Vector3.new(2602, 130, -905), math.rad(0)},
    {Vector3.new(2608, 130, -913), math.rad(0)},
    {Vector3.new(2617, 131, -900), math.rad(10)},
    {Vector3.new(2623, 131, -901), math.rad(10)},
    {Vector3.new(2630, 131, -902), math.rad(10)}
}

            local deployTarget = CFrame.new(357.0093, 132, 201.9552, -0.084, 0, 0.996, 0, 1, 0, -0.996, 0, -0.084)

            for indexV2, target in ipairs(targets) do
                if not _G.indexV2 then break end

                -- สร้าง CFrame ใหม่จากตำแหน่งและการหมุน
                local targetCFrame = CFrame.new(target[1]) * CFrame.Angles(0, target[2], 0)

                -- ย้ายตัวละครไปยังตำแหน่งและหมุน
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = targetCFrame

                -- ปล่อย Crab Cage
                local crabCage = game.Players.LocalPlayer.Character:FindFirstChild("Crab Cage")
                if crabCage and crabCage:FindFirstChild("Deploy") then
                    crabCage.Deploy:FireServer(deployTarget)
                end

                task.wait(0.3)

                if indexV2 == #targets then
                    _G.indexV2 = false
                    _G.worldPivot = true
                end
            end
        end
    end
end)


_G.worldPivot = false
local isProcessing = false  -- ตัวแปรที่ใช้ในการตรวจสอบว่าโค้ดกำลังทำงานอยู่หรือไม่

local function startWorldPivot()
    -- ตรวจสอบว่าโค้ดกำลังทำงานอยู่หรือไม่
    if isProcessing then
        return  -- ถ้ามีการทำงานอยู่แล้วจะไม่เริ่มใหม่
    end

    isProcessing = true  -- ตั้งสถานะว่าเริ่มทำงานแล้ว

    while _G.worldPivot do
        task.wait(0.1)  -- Adding a small delay for efficiency

        local foundCrabCage = false

        -- Loop through crabcages
        for i = 1, 1000 do
            -- ตรวจสอบว่า _G.worldPivot ถูกตั้งเป็น false หรือไม่
            if not _G.worldPivot then
                isProcessing = false  -- การทำงานเสร็จสิ้นแล้ว
                return  -- ออกจากฟังก์ชันและหยุดการทำงานทันที
            end

            local crabcage = workspace.active.crabcages:GetChildren()[i]

            if crabcage and crabcage:IsA("Model") then
                -- If the model does not have PrimaryPart
                local part = crabcage:FindFirstChild("PrimaryPart") or crabcage:FindFirstChildOfClass("Part")
                if part then
                    -- Wait 1 second before moving to the next position
                    wait(0.1)

                    -- Teleport to the position of part
                    local worldPivotPosition = part.Position
                    game.Players.LocalPlayer.Character:SetPrimaryPartCFrame(CFrame.new(worldPivotPosition))
                    foundCrabCage = true
                end
            end
        end

        -- If no crabcages are found, print "Win"
        if not foundCrabCage then
            _G.index = true
            _G.worldPivot = false
        end
    end

    isProcessing = false  -- การทำงานเสร็จสิ้นแล้ว
end

-- ฟังก์ชันที่ใช้ในการเริ่มทำงาน
local function checkWorldPivot()
    if _G.worldPivot and not isProcessing then
        task.spawn(startWorldPivot)  -- เริ่มต้นการทำงานใหม่ถ้าไม่มีการทำงานอยู่
    end
end

-- เริ่มทำงานทันทีเมื่อ _G.worldPivot ถูกตั้งเป็น true
checkWorldPivot()

-- ใช้ RunService เพื่อให้ตรวจสอบตลอดเวลา
game:GetService("RunService").Heartbeat:Connect(function()
    checkWorldPivot()
end)








-- This script will run as long as _G.Tool is true, and it will start working when _G.Tool is set to true
task.spawn(function()
    while true do
        -- If _G.Tool is true, start the loop to equip the "Crab Cage"
        if _G.Tool1 then
            local player = game.Players.LocalPlayer
            local backpack = player.Backpack

            -- Check if the "Crab Cage" exists in the backpack
            local crabCage = backpack:FindFirstChild("Crab Cage")

            if crabCage then
                -- Equip the "Crab Cage" item
                player.Character:WaitForChild("Humanoid"):EquipTool(crabCage)
            else
                print("Crab Cage not found in backpack.")
            end
        end

        -- Short delay before the next loop iteration to prevent freezing
        task.wait(0)
    end
end)

if not _G.Autoprompt then
    _G.Autoprompt = false  -- กำหนดค่าเริ่มต้นให้เป็น false
end

task.spawn(function()
    while true do  -- ลูปแบบต่อเนื่อง
        task.wait(0)  -- หยุดรอสั้นๆ เพื่อหลีกเลี่ยงการแฮงค์

        if _G.Autoprompt then
            -- จำลองการกดและปล่อยปุ่ม "E"
            game:GetService('VirtualInputManager'):SendKeyEvent(true, Enum.KeyCode.E, false, game)
            task.wait(0)
            game:GetService('VirtualInputManager'):SendKeyEvent(false, Enum.KeyCode.E, false, game)

            -- ดึง Crabcages ทั้งหมดใน collection
            local crabcages = workspace.active.crabcages:GetChildren()

            -- ลูปไปที่ Crabcages (ไม่เกิน 1000 อัน)
            for i = 1, math.min(1000, #crabcages) do
                local crabcage = crabcages[i]  -- เข้าถึง Crabcage ที่ตำแหน่ง i
                if crabcage then
                    local prompt = crabcage:FindFirstChild("Prompt")  -- หา Prompt ใน Crabcage
                    if prompt then
                        prompt.HoldDuration = 0  -- ตั้ง HoldDuration เป็น 0
                        prompt.MaxActivationDistance = 100  -- ตั้ง MaxActivationDistance เป็น 100
                    end
                end
            end
        end
    end
end)




---//---//----//---//---//----//---//---//----//---//---//----//---//---//----//
local Fluent = loadstring(game:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()
local SaveManager = loadstring(game:HttpGet("https://raw.githubusercontent.com/dawid-scripts/Fluent/master/Addons/SaveManager.lua"))()
local InterfaceManager = loadstring(game:HttpGet("https://raw.githubusercontent.com/dawid-scripts/Fluent/master/Addons/InterfaceManager.lua"))()

local Window = Fluent:CreateWindow({
    Title = "XXX hub [FREE]",
    SubTitle = "by 999",
    TabWidth = 160,
    Size = UDim2.fromOffset(555, 355),
    Acrylic = true, -- The blur may be detectable, setting this to false disables blur entirely
    Theme = "Dark",
    MinimizeKey = Enum.KeyCode.LeftControl -- Used when theres no MinimizeKeybind
})

--Fluent provides Lucide Icons https://lucide.dev/icons/ for the tabs, icons are optional
local Tabs = {
    AutoFishing = Window:AddTab({ Title = "Auto Fishing", Icon = "home" }),
     Farm = Window:AddTab({ Title = "Farm", Icon = "gem" }),
     Players = Window:AddTab({ Title = "Players", Icon = "user" }),
     Miscellaneous = Window:AddTab({ Title = "Miscellaneous", Icon = "align-justify" }),
    Settings = Window:AddTab({ Title = "Settings", Icon = "settings" })
}

  local section = Tabs.AutoFishing:AddSection("Fishing Bot")
  local section = Tabs.Farm:AddSection("Level Farm")
  local section = Tabs.Players:AddSection("Movement")
  local section = Tabs.Miscellaneous:AddSection("Misc")

local Options = Fluent.Options

do
local Toggle = Tabs.AutoFishing:AddToggle("MyToggle", {
    Title = "Auto Fishing", 
    Default = false, 
    Description = "Automatically fish for you."  -- Adding description to the toggle
})

Toggle:OnChanged(function()
    _G.Tool1234 = Toggle.Value

    if _G.Tool1234  then
        task.spawn(function()
            while _G.Tool1234  do
                task.wait(0)  -- Added a small delay to reduce unnecessary checks


          local player = game:GetService("Players").LocalPlayer
local backpack = player.Backpack

-- Check for tools in the player's backpack
for _, item in pairs(backpack:GetChildren()) do
    if item:IsA("Tool") and string.find(item.Name, "Rod") then
        -- Ensure the item is not "Crab Cage" before equipping
        if item.Name ~= "Crab Cage" then
            local humanoid = player.Character:WaitForChild("Humanoid")
            humanoid:EquipTool(item)  -- Equip the rod item
            break  -- Stop searching after finding the first match
        end
    end
end

-- Check for tools in the player's character (not workspace.D3B3XxX)
local rodItem = nil
for _, item in pairs(player.Character:GetChildren()) do
    if item:IsA("Tool") and string.find(item.Name, "Rod") then
        -- Ensure the item is not "Crab Cage" before equipping
        if item.Name ~= "Crab Cage" then
            rodItem = item  -- Found the rod in the character, not the "Crab Cage"
            break  -- Stop searching after finding the first match
        end
    end
end

-- If a "Rod" item is found in the player's character, trigger the cast event
if rodItem then
    local events = rodItem:FindFirstChild("events")
    if events and events:FindFirstChild("cast") then
        -- Fire the cast event with arguments
        local args = {
            [1] = 99999999999999,
            [2] = 1
        }
        events.cast:FireServer(unpack(args))
    end
end

task.wait(0)  -- Add delay to prevent overloading the server

            end
        end)
    end
end)

            end
local Toggle = Tabs.AutoFishing:AddToggle("MyToggle", {
    Title = "Auto Use Bait", 
    Default = false, 
    Description = "Automatically use vait when fishing."  -- Adding description to the toggle
})
    Toggle:OnChanged(function()
 
    end)
    

      local MultiDropdown = Tabs.AutoFishing:AddDropdown("MultiDropdown", {
        Title = "Select Bait",
        Description = "",
        Values = {"Magnet", "Worm", "Peppermint Worm", "Coal", "Squid", "Shrimp", "Insect", "Give", "Night Shrimp", "Deep Coral", "Super Flakes", "Swaweed", "Instant", "Shark Head", "Fish Head", "Weird Algae", "Garbage",  "Holly Berry", "Rapid Catcher", "Minnow", "Coral", "Flakes", "Aurora Bait", "Bagel", "Truffle Worm"},
        Multi = true,
        Default = {"seven", "twelve"},
    })

    MultiDropdown:SetValue({
        three = true,
        five = true,
        seven = false
    })

    MultiDropdown:OnChanged(function(Value)
        local Values = {}
        for Value, State in next, Value do
            table.insert(Values, Value)
        end
    end)

local Toggle = Tabs.AutoFishing:AddToggle("MyToggle", {
    Title = "Auto FastShake", 
    Default = false, 
    Description = "Automatically FastShake the rod."
})

Toggle:OnChanged(function(se)
    _G.FastShake = se
if not _G.FastShake then
    _G.FastShake = false
end

-- ฟังก์ชันหลักที่ทำงานตลอดเวลา
task.spawn(function()
    while true do
        task.wait(0)  -- หยุดรอสั้นๆ เพื่อหลีกเลี่ยงการแฮงค์

        -- ถ้าค่า _G.FastShake เป็น true ให้ทำงาน
        if _G.FastShake then
            -- ลูปเพื่อจำลองการคลิกปุ่ม 10,000 ครั้ง
            for i = 1, 3 do
                -- เลือกผู้เล่นและ GUI ที่เกี่ยวข้อง
                local player = game.Players.LocalPlayer
                local GUI = player:WaitForChild("PlayerGui")
                local shakeui = GUI:WaitForChild("shakeui")
                local VirtualInputManager = game:GetService("VirtualInputManager")
                local button = shakeui.safezone:FindFirstChild("button")

                -- ถ้าปุ่มอยู่และเป็น ImageButton, จำลองการคลิก
                if button and button:IsA("ImageButton") then
                    -- เลือกปุ่มและจำลองการคลิก
                    game:GetService("GuiService").SelectedCoreObject = button
                    VirtualInputManager:SendKeyEvent(true, Enum.KeyCode.Return, false, game)
                    VirtualInputManager:SendKeyEvent(false, Enum.KeyCode.Return, false, game)
                end
            end
        end
    end
end)
end)


local Toggle = Tabs.AutoFishing:AddToggle("MyToggle", {
    Title = "Auto Shake", 
    Default = true, 
    Description = "Automatically Shake the rod."
})

Toggle:OnChanged(function(value)
    _G.Autoshake = value


if not _G.Autoshake then
    _G.Autoshake = false
end

-- ฟังก์ชันหลักที่ทำงานตลอดเวลา
task.spawn(function()
    while true do
        task.wait(0)  -- หยุดรอสั้นๆ เพื่อหลีกเลี่ยงการแฮงค์

        -- ถ้าค่า _G.FastShake เป็น true ให้ทำงาน
        if _G.Autoshake then
            -- ลูปเพื่อจำลองการคลิกปุ่ม 10,000 ครั้ง
                    local player = game.Players.LocalPlayer
                    local GUI = player:WaitForChild("PlayerGui")
                    local shakeui = GUI:WaitForChild("shakeui")
                    local VirtualInputManager = game:GetService("VirtualInputManager")

                    -- Locate the button and interact with it
                    local button = shakeui.safezone:FindFirstChild("button")
                    if button and button:IsA("ImageButton") and button.Visible then
                        game:GetService("GuiService").SelectedCoreObject = button
                        VirtualInputManager:SendKeyEvent(true, Enum.KeyCode.Return, false, game)
                        VirtualInputManager:SendKeyEvent(false, Enum.KeyCode.Return, false, game)
                    end
                end
            end
        end)
    end)
    






local Toggle = Tabs.AutoFishing:AddToggle("MyToggle", {
    Title = "Auto Reel", 
    Default = false, 
    Description = "Automatically finish the fishinf process."  -- Adding description to the toggle
})
    Toggle:OnChanged(function()
_G.AutoReel1 = Toggle.Value
_G.AutoReel2 = Toggle.Value

   if _G.AutoReel1 then
            task.spawn(function()
                while _G.AutoReel1 do
                    task.wait(0)
                    local reelfinished = game:GetService("ReplicatedStorage"):WaitForChild("events"):WaitForChild("reelfinished")
                    local LocalPlayer = game.Players.LocalPlayer

                    for _, v in pairs(LocalPlayer.PlayerGui:GetChildren()) do
                        if v:IsA("ScreenGui") and v.Name == "reel" then
                            if v:FindFirstChild("bar") then
                                reelfinished:FireServer(100, true)
                            end
                        end
                    end
                end
            end)
        end

        -- Auto Reel 2 logic
        if _G.AutoReel2 then
            task.spawn(function()
                while _G.AutoReel2 do
                    task.wait(0)
                    local reelfinished = game:GetService("ReplicatedStorage").Link.events.reelfinished
                    local LocalPlayer = game.Players.LocalPlayer

                    for _, v in pairs(LocalPlayer.PlayerGui:GetChildren()) do
                        if v:IsA("ScreenGui") and v.Name == "reel" then
                            if v:FindFirstChild("bar") then
                                reelfinished:FireServer(100, true)
                            end
                        end
                    end
                end
            end)
        end
    end)
    
local Toggle = Tabs.AutoFishing:AddToggle("MyToggle", {
    Title = "AutoReelSafe", 
    Default = true, 
    Description = "Automatically finish the fishinf process [Safe]."  -- Adding description to the toggle
})

Toggle:OnChanged(function()
    _G.AutoReel3 = Toggle.Value
    
    if _G.AutoReel3 then
        task.spawn(function()
            while _G.AutoReel3 do
                task.wait(0)  -- Adding a slight delay to prevent overloading the system
                
                local player = game:GetService("Players").LocalPlayer
                local playerGui = player:FindFirstChild("PlayerGui")
                
                -- Check if playerGui, reel, bar, and playerbar exist
                if playerGui and playerGui:FindFirstChild("reel") and 
                   playerGui.reel:FindFirstChild("bar") and 
                   playerGui.reel.bar:FindFirstChild("playerbar") then
                   
                    local playerBar = playerGui.reel.bar.playerbar
                    local fish = playerGui.reel.bar:FindFirstChild("fish")
                    
                    -- Check if fish exists before changing the position
                    if fish then
                        playerBar.Position = fish.Position
                    end
                end
            end
        end)
    end
end)

  local section = Tabs.AutoFishing:AddSection("Fishing Positions")

local Toggle = Tabs.AutoFishing:AddToggle("MyToggle", {
    Title = "Teleport To positio", 
    Default = false, 
    Description = "Automatically teleport while fishing to your fishing positio."  -- Adding description to the toggle
})

local shouldStop = false
local targetPosition = Vector3.new(0, 0, 0)  -- กำหนดตำแหน่งเริ่มต้น

Toggle:OnChanged(function(state)
    local player = game.Players.LocalPlayer
    local character = player.Character or player.CharacterAdded:Wait()
    local humanoidRootPart = character:WaitForChild("HumanoidRootPart")

    if state then  -- ถ้า Toggle เปิด
        shouldStop = false  -- ตั้งค่าให้ไม่หยุด
        -- วาบไปยังตำแหน่งนั้นอย่างต่อเนื่อง
        while not shouldStop do
            humanoidRootPart.CFrame = CFrame.new(targetPosition)
            wait(0)  -- รอ 0.1 วินาทีเพื่อวาบต่อเนื่อง
        end
    else  -- ถ้า Toggle ปิด
        shouldStop = true  -- หยุดลูป
    end
end)
Tabs.AutoFishing:AddButton({
    Title = "Set Fishing Position",
    Description = "Set your new fishing position",
    Callback = function()
        local player = game.Players.LocalPlayer
        local position = player.Character.HumanoidRootPart.Position

        -- คัดลอกแค่ตำแหน่ง x, y, z
        local x, y, z = position.X, position.Y, position.Z
        local positionString = x .. ", " .. y .. ", " .. z

        -- คัดลอกข้อความไปที่คลิปบอร์ด
        setclipboard(positionString)

        -- นำค่าตำแหน่งที่คัดลอกไปใช้ใน targetPosition
        targetPosition = Vector3.new(x, y, z)

        print("Position copied to clipboard: " .. positionString)
    end
})

-- สร้าง Paragraph


-- สร้าง Toggle
local Toggle = Tabs.Farm:AddToggle("MyToggle", {
    Title = "AutoLevelFarm", 
    Default = false, 
    Description = "Auto Level Farm."
})
local ScreenGui -- ตัวแปรที่จะเก็บ UI

Toggle:OnChanged(function(state)
    -- เปิดหรือปิดการทำงานตามค่าของ state
    _G.index = state
    _G.Tool1 = state
    _G.Autoprompt = state
    _G.worldPivot = state
    _G.indexV2 = state
    _G.indexV2 = false

    if state then
        -- เริ่มการทำงานของแต่ละฟังก์ชัน
        task.spawn(function()
            while _G.index do
                task.wait(0.1)
                -- โค้ดสำหรับการจัดการ `_G.index`

            end
        end)

        task.spawn(function()
            while _G.indexV2 do 
                task.wait(0.1)
                -- โค้ดสำหรับการจัดการ `_G.indexV2`

            end
        end)

        task.spawn(function()
            while _G.Tool1 do 
                task.wait(0.1)
                -- โค้ดสำหรับการจัดการ `_G.ToolCrab`

            end
        end)

        task.spawn(function()
            while _G.Autoprompt do
                task.wait(0.1)
                -- โค้ดสำหรับการจัดการ `_G.Autoprompt`

            end
        end)

        task.spawn(function()
            while _G.worldPivot do
                task.wait(0.1)
                -- โค้ดสำหรับการจัดการ `_G.worldPivot`

            end
        end)

        -- สร้าง UI เมื่อ Toggle เปิด
        ScreenGui = Instance.new("ScreenGui")
        ScreenGui.Parent = game.Players.LocalPlayer.PlayerGui

        -- สร้าง Frame
        local Frame = Instance.new("Frame")
        Frame.Size = UDim2.new(0, 400, 0, 200)  -- ขนาดของกรอบ
        Frame.Position = UDim2.new(0.5, -200, 0.5, -100)  -- ตำแหน่งของกรอบ
        Frame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)  -- สีพื้นหลัง
        Frame.BackgroundTransparency = 1  -- ความโปร่งใส
        Frame.Parent = ScreenGui

        -- เพิ่ม UICorner เพื่อทำมุมโค้งให้กับ Frame
        local UICorner = Instance.new("UICorner")
        UICorner.CornerRadius = UDim.new(0, 15)  -- มุมโค้ง
        UICorner.Parent = Frame

        -- สร้าง TextLabel ที่แสดงตัวอักษร  
        local TextLabel = Instance.new("TextLabel")
        TextLabel.Size = UDim2.new(0, 200, 0, 50)  -- ขนาดของข้อความ
        TextLabel.Position = UDim2.new(0.5, -100, 0, 0)  -- ตำแหน่งของข้อความ (อยู่ด้านบนสุด)
        TextLabel.BackgroundTransparency = 1  -- ทำให้พื้นหลังโปร่งใส
        TextLabel.Text = "🟢 star : Level Farm"  -- ข้อความที่จะแสดง (ตัวอักษร)
        TextLabel.TextColor3 = Color3.fromRGB(255, 0, 0)  -- สีข้อความ
        TextLabel.TextSize = 20  -- ขนาดข้อความที่เล็กลง
        TextLabel.Parent = Frame

    else  -- ถ้า Toggle ปิด
        -- ลบ UI ถ้า Toggle ปิด
        if ScreenGui then
            ScreenGui:Destroy()  -- ลบ ScreenGui ถ้ามี
            ScreenGui = nil  -- รีเซ็ตตัวแปร ScreenGui
        end

    end

    -- เริ่มทำงานการฟาร์ม เมื่อ Toggle เปิด
    if _G.Farm then
        task.spawn(function()
            while _G.Farm do
                task.wait(1)  -- เพิ่มเวลาหน่วงเพื่อให้ไม่กระทบกับประสิทธิภาพ
                -- ฟังก์ชันที่คุณต้องการให้ทำงานเมื่อ Toggle เปิด
                print("...กำลังฟาร์ม")
            end
        end)
    end
end)
local Toggle = Tabs.Farm:AddToggle("MyToggle", {
    Title = "BuyCrab", 
    Default = false, 
    Description = "Auto Buy Crab."
})

-- Add a toggle to the Farm tab
Toggle:OnChanged(function(state)
    _G.BuyCrab = state
    if state then
        -- Start the auto-buy process
        task.spawn(function()
            while _G.BuyCrab do
                task.wait(0) -- Prevent overwhelming the system
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2526, 136, -893) 

                -- Simulate pressing the 'E' key
                game:service('VirtualInputManager'):SendKeyEvent(true, "E", false, game)
                game:service('VirtualInputManager'):SendKeyEvent(false, "E", false, game)
                
                -- Check for the 'prompt' GUI element
                local playerGui = game:GetService("Players").LocalPlayer.PlayerGui
                if playerGui:FindFirstChild("over") and playerGui.over:FindFirstChild("prompt") then
                    local prompt = playerGui.over.prompt
                    if prompt:FindFirstChild("confirm") then
                        -- Trigger the confirmation button
                        for _, connection in pairs(getconnections(prompt.confirm.MouseButton1Click)) do
                            if connection.Function then
                                connection.Function()
                            end
                        end
                    end
                end
            end
        end)
    end
end)




-- Add a toggle to the Farm tab
local Toggle = Tabs.Players:AddToggle("MyToggle", {
    Title = "Walk Speed", 
    Default = true, 
    Default = false, 
    Description = "You can run at high speed."
})

Toggle:OnChanged(function(State)
    if State then
        _G.WalkSpeed = true
    else
        local player = game.Players.LocalPlayer
        local humanoid = player.Character and player.Character:FindFirstChild("Humanoid")
        
        -- รีเซ็ต WalkSpeed เป็น 16 เมื่อปิด
        if humanoid then
            humanoid.WalkSpeed = 16
        end
        _G.WalkSpeed = false
    end
end)


-- Set _G.WalkSpeed to true to allow modifying the WalkSpeed
_G.WalkSpeed = true  -- ตั้งค่าเริ่มต้นเป็น true

-- Create Slider for adjusting WalkSpeed
local Slider = Tabs.Players:AddSlider("Slider", {
    Title = "WalkSpeed Slider",
    Description = "Adjust running speed.",
    Default = 16,  -- Default WalkSpeed (Roblox default is 16)
    Min = 1,
    Max = 200,  -- Maximum WalkSpeed (adjustable)
    Rounding = 1,
    Callback = function(Value)
        -- ตรวจสอบว่า _G.WalkSpeed เป็น true ก่อนจะอัปเดต WalkSpeed
        if _G.WalkSpeed then
            local player = game.Players.LocalPlayer
            local humanoid = player.Character and player.Character:FindFirstChild("Humanoid")
            
            -- อัปเดต WalkSpeed หาก humanoid มีอยู่
            if humanoid then
                humanoid.WalkSpeed = Value
            end
        end
    end
})

Slider:OnChanged(function(Value)
    -- Optionally log or do something else when the slider value changes
    -- print("Slider Value: " .. Value)
end)

local Toggle = Tabs.Players:AddToggle("MyToggle", {
    Title = "Walk Speed", 
    Default = true, 
    Default = false, 
    Description = "You can jump power."
})

Toggle:OnChanged(function(State)
    if State then
        _G.JumpPower = true
    else
        local player = game.Players.LocalPlayer
        local humanoid = player.Character and player.Character:FindFirstChild("Humanoid")
        
        -- รีเซ็ต WalkSpeed เป็น 16 เมื่อปิด
        if humanoid then
            humanoid.JumpPower = 16
        end
        _G.JumpPower = false
    end
end)


_G.JumpPower = true

local Slider = Tabs.Players:AddSlider("Slider", {
    Title = "Jump Power",
    Description = "Adjust jump power.",
    Default = 50,  -- ค่าเริ่มต้นของ JumpPower
    Min = 1,
    Max = 500,  -- ความสูงการกระโดดสูงสุด
    Rounding = 1,
    Callback = function(Value)
        -- ตรวจสอบว่า _G.JumpPower เป็น true ก่อนจะอัปเดต JumpPower
        if _G.JumpPower then
            local player = game.Players.LocalPlayer
            local humanoid = player.Character and player.Character:FindFirstChild("Humanoid")
            
            -- อัปเดต JumpPower หาก humanoid มีอยู่
            if humanoid then
                humanoid.JumpPower = Value
            end
        end
    end
})
Tabs.Settings:AddButton({
    Title = "delete Lighting",
    Description = "Can I delete Lighting",
    Callback = function()
        Window:Dialog({
            Title = "Title",
            Content = "This is a dialog",


        })
    end
})

local Toggle = Tabs.Miscellaneous:AddToggle("MyToggle", {
    Title = "Auto Sell", 
    Default = true, 
    Default = false, 
    Description = "You can auto sell hand."
})

    Toggle:OnChanged(function(ez)

    _G.Sell  = ez

if not _G.Sell then
    _G.Sell = false  -- กำหนดค่าเริ่มต้นให้เป็น false
end

task.spawn(function()
    while true do  -- ลูปแบบต่อเนื่อง
        task.wait(0)  -- หยุดรอสั้นๆ เพื่อหลีกเลี่ยงการแฮงค์

        if _G.Sell then

game:GetService("ReplicatedStorage"):WaitForChild("events"):WaitForChild("Sell"):InvokeServer()



end
end
end)


    end)
    local Toggle = Tabs.Miscellaneous:AddToggle("MyToggle", {
    Title = "Auto Sell all", 
    Default = true, 
    Default = false, 
    Description = "You can auto sell all."
})

    Toggle:OnChanged(function(ez1)

    _G.Sell1  = ez1

if not _G.Sell1 then
    _G.Sell1 = false  -- กำหนดค่าเริ่มต้นให้เป็น false
end

task.spawn(function()
    while true do  -- ลูปแบบต่อเนื่อง
        task.wait(0)  -- หยุดรอสั้นๆ เพื่อหลีกเลี่ยงการแฮงค์

        if _G.Sell1 then

game:GetService("ReplicatedStorage"):WaitForChild("events"):WaitForChild("SellAll"):InvokeServer()



end
end
end)


    end)


-- กำหนดค่าเริ่มต้นให้ _G.FastShake เป็น false ถ้ายังไม่ได้ตั้งค่า
else
    game.Players.LocalPlayer:Kick("Invalid key! (Error code: 267)")  -- If key is incorrect, kick the player
end
