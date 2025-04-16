-- Password For Unlock 
Password = "111"
result = gg.prompt({"🔐Enter Your Password🔐"})
if result[1] == Password then
else
gg.alert("Script Disabled ")
os.exit()
end
-- Expiry Date Setup
local expiry_date = os.time{year=2025, month=4, day=25}
local current_date = os.time()

if current_date >= expiry_date then
    gg.alert("UCHIHA FF Script is Expired 🧾\n\nPlease Join Telegram For More Update.")
    os.execute('am start -a android.intent.action.VIEW -d "https://telegram.me/uchihaH4x"')
    os.exit()
end
--[[
===================================
   WELCOME TO MY LUA SCRIPT
===================================
]]--

gg.clearResults()
gg.setVisible(false)

-- 🔥 **Library Functions** 🔥
function BBTeam_Lib(Lib, Offset, Replaced)
    local info = gg.getTargetInfo()
    local localpack = info.nativeLibraryDir
    local t = gg.getRangesList(localpack .. '/' .. Lib)
    for _, __ in pairs(t) do
        local t = gg.getValues({{address = __.start, flags = gg.TYPE_DWORD}, {address = __.start + 0x12, flags = gg.TYPE_WORD}})
        if t[1].value == 0x464C457F then
            Offset = __['start'] + Offset
        end
        assert(Offset ~= nil, '[rwmem]: error, provided address is nil.')
        _rw = {}
        if type(Replaced) == 'number' then
            _ = ''
            for _ = 1, Replaced do
                _rw[_] = { address = (Offset - 1) + _, flags = gg.TYPE_BYTE }
            end
            for v, i in ipairs(gg.getValues(_rw)) do
                _ = _ .. string.format('%02X', i.value & 0xFF)
            end
            return _
        end
        Byte = {}
        Replaced:gsub('..', function(x)
            Byte[#Byte + 1] = x
            _rw[#Byte] = { address = (Offset - 1) + #Byte, flags = gg.TYPE_BYTE, value = x .. 'h' }
        end)
        gg.setValues(_rw)
    end
end

-- 🚀 **Feature Functions** 🚀
function speedHack()
    BBTeam_Lib("libil2cpp.so", 0x135abb4, "0100A0E31EFF2FE1")
    BBTeam_Lib("libil2cpp.so", 0x5d8c55c, "0100A0E31EFF2FE1")
    gg.toast("✅ Speed Hack Activated!")
    gg.clearResults()
end

function wallHack()
    gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber('-6.11142992e27', gg.TYPE_FLOAT)
gg.getResults(gg.getResultsCount())
gg.editAll('0', gg.TYPE_FLOAT)
gg.clearResults()
    gg.toast("Wall Hack Activated!")
end

function antennaHand()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("h BB 72 22 BC 00 00 00 00", gg.TYPE_BYTE)
    gg.refineNumber("h 00 00 00 00", gg.TYPE_BYTE, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(10)
    gg.editAll("h 00 00 20 43", gg.TYPE_BYTE)
    gg.clearResults()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("h 8D 39 65 3E 00 00 00 00", gg.TYPE_BYTE)
    gg.refineNumber("h 00 00 00 00", gg.TYPE_BYTE, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(10)
    gg.editAll("h 00 00 20 43", gg.TYPE_BYTE)
    gg.clearResults()
    gg.setRanges(gg.REGION_VIDEO | gg.REGION_BAD)
    gg.searchNumber("3.75000095367;3.75000166893;3.58931802e-29:13", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1, 0)
    gg.getResults(9)
    gg.editAll("99", gg.TYPE_FLOAT)
    gg.clearResults()
    gg.toast("RGB Antenna Activated!")
end

function awmAimbot()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.setVisible(false)
    gg.searchNumber("h CD CC CC 3D 06 00 00 00 00 00 00 00 00 00 00 00 00 00", gg.TYPE_BYTE)
    gg.getResults(100)
    gg.editAll("h CD CC CC 3D 06 00 00 00 00 00 FF FF 00 00 00 00 00 00", gg.TYPE_BYTE)
    gg.clearResults()
    gg.clearResults()
    gg.toast("SNIPER AIMBOT ON ✅")
    end

function awmFastSwitch()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("hb4 42 96 00 00 00 00 00 00 00 00 00 00 3f 00 00 80 3e 00 00 00 00 04 00 00 00 00 00 80 3f 00 00 20 41 00 00 34 42 01", gg.TYPE_BYTE)
    gg.getResults(1500.0)
    gg.editAll("hb4 42 96 00 00 00 00 00 00 00 00 00 00 3b 00 00 29 3d 00 00 00 00 04 00 00 00 00 00 80 3f 00 00 20 41 00 00 34 42 01", gg.TYPE_BYTE)
    gg.clearResults()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("h42 00 00 70 42 7f 00 00 00 00 00 00 00 00 00 00 3f 00 00 80 3e 00 00 00 00 04 00 00 00 00 00 80 3f 00 00 20 41 00 00 34 42 01", gg.TYPE_BYTE)
    gg.getResults(1500.0)
    gg.editAll("h42 00 00 3f 42 3f 00 00 00 00 00 00 00 3f 3f 3f 3b 00 00 29 3d 00 00 00 00 04 00 00 00 00 00 80 3f 00 00 20 41 00 00 34 42 01", gg.TYPE_BYTE)
    gg.clearResults()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("h00 00 00 3F 00 00 80 3E 00 00 00 00 06 00 00 00 CD CC 4C 3F 00 00 20 41 00 00 34 42 01 00 00 00 01 00 00 00 00 00 00 00 00 00 00 00 00 00 80 3F 66 66 66 3F 9A 99 99 3F", gg.TYPE_BYTE)
    gg.getResults(1500.0)
    gg.editAll("h00 00 3C 00 00 80 3C 00 00 00 00 04 06 00 00 00 CD CC 4C 3F 00 00 20 41 00 00 34 42 01 00 00 00 01 00 00 00 00 00 00 00 00 00 00 00 00 00 80 3F 66 66 66 3F 9A 99 99 3F", gg.TYPE_BYTE)
    gg.clearResults()
    gg.toast("SNIPER FAST SWITCH ON ✅")
    end

function nightMode()
    gg.setRanges(gg.REGION_ANONYMOUS | gg.REGION_CODE_APP)
gg.searchNumber("h a4 70 7d 3f 3a cd 13 3f 0a d7 23 3c bd 37 86 35 00 00 51 e3 04 10 91 15", gg.TYPE_BYTE)
gg.getResults(100)
gg.editAll("h a4 70 7d 3f 3a cd 13 3f 0a d7 23 3c 00 00 80 bf 00 20 a0 e3 04 10 91 15", gg.TYPE_BYTE)
gg.clearResults()
    gg.toast("Night Mode Activated!")
end

function magicBullet()
    gg.setRanges(32)
gg.searchNumber("h23AAA6B8460ACD70", 1)
gg.getResults(gg.getResultsCount())
gg.editAll("h23AAA6B8B2F71FA4", 1)
gg.clearResults()
gg.searchNumber("h477B5ABDAE5766BB5C1F48BA1BC0CF3B9CFB283DA2B117BDE4997F3F0400803F0000803FFEFF7F3F", 1)
gg.getResults(gg.getResultsCount())
gg.editAll("h8D07743FAE5766BB5C1F48BA1BC0CF3B9CFB283DA2B117BDE4997F3F000060410000604100006041", 1)
gg.clearResults()
gg.searchNumber("h4C7B5ABD0A5766BB1E2148BA2AC2CF3B96FB283DE8B117BDE3997F3F0400803F0100803FFCFF7F3F", 1)
gg.getResults(gg.getResultsCount())
gg.editAll("h1B0E743FAE5766BB5C1F48BA1BC0CF3B9CFB283DA2B117BDE4997F3F000060410000604100006041", 1)
gg.clearResults()
gg.searchNumber("h1000000062006F006E0065005F004C006500660074005F0057006500610070006F006E00", 1)
gg.getResults(gg.getResultsCount())
gg.editAll("h1000000062006F006E0065005F005300700069006E006500000000000000000000000000", 1)
gg.clearResults()
    gg.toast("Magic Bullet Activated!")
end

-- 🔥 **UI Setup** 🔥
emojiList = { '🔥', '💀' }

function updateEmoji(A0_22)
    emojiList[A0_22] = '[Active]'
end

while true do
    menu = gg.choice({
        '🚀 SPEED HACK ' .. emojiList[1],
        '🛡️ WALL HACK ' .. emojiList[1],
        '🎯 ANTENA HAND ' .. emojiList[1],
        '🔫 AWM AIMBOT ' .. emojiList[1],
        '🔄 AWM FAST SWITCH ' .. emojiList[1],
        '🌙 NIGHT MODE ' .. emojiList[1],
        '🔫 MagicBullet ' .. emojiList[1],
        '❌ EXIT ' .. emojiList[2],
    }, nil, '🔥UCHIHA PRO Menu 🔥')

    if menu == 1 then
        speedHack()
    elseif menu == 2 then
        wallHack()
    elseif menu == 3 then
        antennaHand()
    elseif menu == 4 then
        awmAimbot()
    elseif menu == 5 then
        awmFastSwitch()
    elseif menu == 6 then
        nightMode()
    elseif menu == 7 then
        magicBullet()
    elseif menu == 8 then
        updateEmoji(2)
        os.exit(print("✅ Done!"))
    end
end
