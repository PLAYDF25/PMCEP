function pass()
local passwords = {
"82642",
"94625",
"70251",
"71260",
"57768",
 }
 local input = gg.prompt({
  "⚡ PMC VIP HACK PUBG MOBILE\n📶 EXCLUSIVE ONLINE VERSION\n🔧 MADE BY PLAYDF25\n\nEnter Password:",
  }, {
   nil
   }, {
    "text"
    })
    if input == nil then
     print ("If you found bugs in script - please contact PLAYDF25 in Telegram!\nLinks:\n@PLAYDF25 - Main Developer & Support")
     os.exit()
    else 
     for k, v in pairs(passwords) do
      if input[1] == v then
          return
end
     end
    print ("⚠️ Wrong Password ⚠️\nYou probably did not buy PMC VIP and you should contact the developer to purchase - please contact PLAYDF25 in Telegram!\nLinks:\n@PLAYDF25 - Main Developer & Support")
    os.exit()
   end
end

if gg.VERSION < '88.1' then
gg.alert('⚠️ Please Update\nPMC VIP GameGuardian!\n________________________\nOfficial telegram group:\nhttps://t.me/PUBG_MOBILE_CHEAT\nCreator: https://t.me/PLAYDF25', '🔴 EXIT ⛔')
print('⚠️ Please Update\nPMC VIP GameGuardian!\n________________________\nOfficial telegram group:\nhttps://t.me/PUBG_MOBILE_CHEAT\nCreator: https://t.me/PLAYDF25')
os.exit()
end

function startscript()
gg.setVisible(false)
BP = gg.alert('     ══════| PMC  VIP |══════\n     ══════|   4.9/0.4   |══════',
'🔅Start🔅',
'✴️List changes✴️') 
if BP == 1 then HOME() end
if BP == 2 then LISTC() end
end

function LISTC()
BG = gg.alert('---- PMC VIP V4.9 PATCH 0.4\n    0.2-0.4: Updating some features.\n    0.1: Adaptation for a new update and small innovations for the future, universal menu updated, updated some features.\n\nOfficial telegram group:\nhttps://t.me/PUBG_MOBILE_CHEAT\nCreator: https://t.me/PLAYDF25', 'OK') 
if BG == 1 then startscript() end
end

HOME=1
function HOME()
gg.toast('Welcome to PMC VIP')
HM = gg.choice({
   '🗃️ UNIVERSAL ONE CLICK🏷️',
   '🧾 UNIVERSAL MENU 📦',
   '⬛ WALLHACK 👁️\n      COLORS 🎨',
   '⬛ WEAPONS 🔫',
   '⬛ PLAYER 🚶',
   '⬛ VEGETATION 🍃',
   '🟧 Clear Logs ✓',
   '🔴 EXIT ⛔'
},nil, '                        ⚡PMC VIP 4.9 PT 0.4⚡\n               📱PUBG MOBILE: 0.16.0📱\n     🔧 MADE BY PLAYDF25')
if HM == 1 then UNIVERSALFFF101() end
if HM == 2 then HYYP0() end
if HM == 3 then wallhackcolorsX() end
if HM == 4 then weapons() end
if HM == 5 then player() end
if HM == 6 then vegetation() end
if HM == 7 then clearshit() end
if HM == 8 then exit() end
HOMEDM=-1
end

function clearshit()
os.remove("/mnt/shell/0/emulated/Android/data/com.pubg.krmobile/cache/GCloud.ini")
os.remove("/mnt/shell/0/emulated/Android/data/com.pubg.krmobile/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Logs")
os.remove("/storage/emulated/0/Android/data/com.pubg.krmobile/cache/GCloud.ini")
os.remove("/sdcard/Android/data/com.pubg.krmobile/cache/GCloud.ini")
os.remove("/sdcard/Android/data/com.pubg.krmobile/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Logs")
os.remove("/mnt/shell/0/emulated/Android/data/com.tencent.tmgp.pubgmhd/cache/GCloud.ini")
os.remove("/mnt/shell/0/emulated/Android/data/com.tencent.tmgp.pubgmhd/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Logs")
os.remove("/storage/emulated/0/Android/data/com.tencent.tmgp.pubgmhd/cache/GCloud.ini")
os.remove("/sdcard/Android/data/com.tencent.tmgp.pubgmhd/cache/GCloud.ini")
os.remove("/sdcard/Android/data/com.tencent.tmgp.pubgmhd/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Logs")
os.remove("/mnt/shell/0/emulated/Android/data/com.vng.pubgmobile/cache/GCloud.ini")
os.remove("/mnt/shell/0/emulated/Android/data/com.vng.pubgmobile/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Logs")
os.remove("/storage/emulated/0/Android/data/com.vng.pubgmobile/cache/GCloud.ini")
os.remove("/sdcard/Android/data/com.vng.pubgmobile/cache/GCloud.ini")
os.remove("/sdcard/Android/data/com.vng.pubgmobile/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Logs")
os.remove("/mnt/shell/0/emulated/Android/data/com.tencent.ig/cache/GCloud.ini")
os.remove("/mnt/shell/0/emulated/Android/data/com.tencent.ig/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Logs")
os.remove("/storage/emulated/0/Android/data/com.tencent.ig/cache/GCloud.ini")
os.remove("/sdcard/Android/data/com.tencent.ig/cache/GCloud.ini")
os.remove("/sdcard/Android/data/com.tencent.ig/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Logs")
os.remove("/mnt/shell/0/emulated/Android/data/com.tencent.igce/cache/GCloud.ini")
os.remove("/mnt/shell/0/emulated/Android/data/com.tencent.igce/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Logs")
os.remove("/storage/emulated/0/Android/data/com.tencent.igce/cache/GCloud.ini")
os.remove("/sdcard/Android/data/com.tencent.igce/cache/GCloud.ini")
os.remove("/sdcard/Android/data/com.tencent.igce/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Logs")
os.remove("/mnt/shell/0/emulated/Android/data/com.tencent.iglite/cache/GCloud.ini")
os.remove("/mnt/shell/0/emulated/Android/data/com.tencent.iglite/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Logs")
os.remove("/storage/emulated/0/Android/data/com.tencent.iglite/cache/GCloud.ini")
os.remove("/sdcard/Android/data/com.tencent.iglite/cache/GCloud.ini")
os.remove("/sdcard/Android/data/com.tencent.iglite/files/UE4Game/ShadowTrackerExtra/ShadowTrackerExtra/Saved/Logs")
gg.toast("√√√√√")
end

function HYYP0()
GK = gg.multiChoice({
  'Game - 🔻(skycolor+antenna+rapidfire+crosshair)\n',
  'Game - 📦(zoom+antishake+moredamage+scopes)\n',
  'Lobby - 🌿(nograss/fog+aimlock)\n',
  'Island - 🎭(norec+wh+color+bullet)\n',
  'Game - 🎭(norec+wh+color+bullet)\n',
  '🔶 BACK'
},nil, '               ☢️ Universal Menu ☣️\n           🔧 MADE BY PLAYDF25')
if GK == nil then else
if GK[1] == true then antennaSky() end
if GK[2] == true then damageIWJDJBDJDK() end
if GK[3] == true then lobbyGrassFogAim() end
if GK[4] == true then QYRNDJRKDO() end
if GK[5] == true then YYYYRNDJRKDP() end
if GK[6] == true then HOME() end
end
end

function lobbyGrassFogAim()
NFLLL()
NGAAA()
aimv29()
end

function damageIWJDJBDJDK()
zoom15xonon()
XNotSitRightX()
XNotStandFrontX()
antishakeee()
moregggddd()
end

function antennaSky()
skycolormenupro()
antennav3()
fw()
SmallCrossHair()
end

function QYRNDJRKDO()
norec9273()
wallhackcolorsX()
MB2MBM()
end

function YYYYRNDJRKDP()
wallhackcolorsX()
nor()
MB2MBM()
end

function UNIVERSALFFF101()
gg.setVisible(false)
BP = gg.alert('Functions: Bullet Mode, Anti Shake, Rapid Fire, Zoom X15, No Recoil All Weapon, No Grass Erangel, No Grass All Maps, Sky Color, Antenna\n___________________________________\nActivate the most versatile features?\n            (activate only in game)', '💠Activate💠', '🔶Back🔶') 
if BP == 1 then universalFOC() end
if BP == 2 then HOME() end
end
function universalFOC()
MB2MBM()
nor()
antishakeee()
zoom15xonon()
fw()
NGE()
njddj877()
antennav3()
skycolormenupro()
end

function weapons()
WPS = gg.multiChoice({
'🔫 No Recoil All Weapons\n             🔶(island)',
'🔫 Menu Other No Recoil\n             🔆(game)',
'🔫 Aimlock\n             🔶(lobby)',
'🔫 Bullet Mode v1\n             🔆(game)',
'🔫 Bullet Mode v2\n             🔆(game)',
'🔫 Headshot Menu\n             🔆(game)',
'🔫 Small CrossHair\n             🔆(game)',
'🔫 Anti Shake\n             🔆(game)',
'🔫 Rapid Fire\n             🔆(game)',
'🔫 Ultra Rapid Fire\n             🔆(game)',
'🔫 More Damage\n             🔆(game)',
'🔫 Quick Shot\n             🔆(game)',
'🔫 AWM, Kar98 No Recharge\n             🔆(game)',
'🔫 ESP Mode\n             🔆(game)',
'🔫 ScopeAimHack Menu\n             (game)',
'🔫 Zoom 4X\n— collimator, holographic\n             🔆(game)',
'🔫 Zoom 6X\n— collimator, holographic\n             🔆(game)',
'🔫 Zoom 8X\n— collimator, holographic\n             🔆(game)',
'🔫 Zoom 15X\n— collimator, holographic\n             🔆(game)',
'🔶 BACK'
},nil,'📁 🔫 WEAPONS')
if WPS == nil then else
if WPS[1] == true then norec9273() end
if WPS[2] == true then MBMMMMOTHER() end
if WPS[3] == true then aimv29() end
if WPS[4] == true then bulletmodev5() end
if WPS[5] == true then MB2MBM() end
if WPS[6] == true then hsmenupro() end 
if WPS[7] == true then SmallCrossHair() end
if WPS[8] == true then antishakeee() end
if WPS[9] == true then fw() end
if WPS[10] == true then kdjd8383() end
if WPS[11] == true then moregggddd() end
if WPS[12] == true then qs() end 
if WPS[13] == true then AWecharge() end
if WPS[14] == true then esp0320() end
if WPS[15] == true then ScopeAimHack() end
if WPS[16] == true then zoom4xonon() end
if WPS[17] == true then zoom6xonon() end
if WPS[18] == true then zoom8xonon() end
if WPS[19] == true then zoom15xonon() end
if WPS[20] == true then HOME() end
end
end

function player()
PY = gg.multiChoice({
'🟥 SpeedHack Menu\n☢️[risky](game)', 
'🗼 Antenna Always v1\n             🔆(game)', 
'🗼 Antenna Always v2\n             🔆(game)', 
'🗼 Antenna Always v3\n             🔆(game)', 
'🗼 Corpse Antenna\n             🔆(game)',
'🗼 Backpack Antenna\n             🔆(game)',
'👷 Jump Through Walls\n             🔆(game)',
'🦸 Multi Jump\n             🔆(game)',
'🦸 Double Jump\n             🔆(game)',
'🦸 Long Jump\n             🔆(game)',
'🦸 High Jump v1\n             🔆(game)',
'🦸 High Jump v2\n             🔆(game)',
'🌀 Speed/Fly Car Menu\n             🔆(game)',
'🚙 Fast Jeep\n             🔆(game)',
'🚙 Speedcar All Cars\n             🔆(game)',
'🚙 Underwater Jeep\n             🔆(game)',
'🚙 Flycar\n             🔆(game)',
'✈️ Fast Parachute\n             🔶(spawn)',
'🦅 High View\n             🔆(game)',
'🦅 Ipad View\n             🔆(game)',
'🦅 Wide View\n             🔆(game)',
'🦅 God View\n             🔆(game)',
'👣 No Foot\n             🔆(game)',
'👨‍🦱 Big Model Player\n             🔆(game)',
'👶 Small Model Player\n             🔆(game)',
'🤺 Quick Weapon Change\n             🔆(game)',
'🚧 Through Walls On Buggy\n             🔆(game)',
'💀 Larger Head\n             🔆(game)',
'🔶 BACK'
},nil,'📁 🚶 PLAYER')
if PY == nil then else 
if PY[1] == true then SPEEDHACKMENUP() end
if PY[2] == true then aaath5() end
if PY[3] == true then antennav2() end
if PY[4] == true then antennav3() end  
if PY[5] == true then antennacor99() end
if PY[6] == true then antennaback99() end 
if PY[7] == true then jtw() end
if PY[8] == true then mj() end
if PY[9] == true then doublejumpnodamage() end
if PY[10] == true then lj() end
if PY[11] == true then sptronghighjump() end
if PY[12] == true then longh44() end
if PY[13] == true then SPEEDMANY1() end
if PY[14] == true then fastjeepuuu() end
if PY[15] == true then SPEEDALLCAR1() end
if PY[16] == true then underwaterjeepx() end
if PY[17] == true then flycarx() end
if PY[18] == true then FFPP1() end
if PY[19] == true then hv() end
if PY[20] == true then IPADWWW() end
if PY[21] == true then IPADWWWW() end
if PY[22] == true then GODWWWWW() end
if PY[23] == true then nf() end
if PY[24] == true then bmp() end
if PY[25] == true then smp() end
if PY[26] == true then Qweaponc() end
if PY[27] == true then throughbuggy() end
if PY[28] == true then LargerH() end
if PY[29] == true then HOME() end
end
end

function vegetation()
MN5 = gg.multiChoice({
"🌱 No Fog\n             🔆(game)",
"🌱 No Fog\n             🔶(lobby)",
"🌱 No Grass\n             🔶(lobby)",
"🌱 No Grass/Trees\n             🔆(game)",
"🌱 No Grass All Maps\n             🔆(game)",
"🌱 No Grass Erangel v1\n             🔆(game)",
"🌱 No Grass Erangel v2\n             🔆(game)",
"🔶 BACK",
	  }, nil, "📁 🌿 VEGETATION")
  if MN5 == nil then
  else
  if MN5[1] == true then nofogjdjdkdk() end
  if MN5[2] == true then NFLLL() end
  if MN5[3] == true then NGAAA() end
  if MN5[4] == true then nograsstreesgghj() end
  if MN5[5] == true then njddj877() end
  if MN5[6] == true then NGEL() end
  if MN5[7] == true then NGE() end
  if MN5[8] == true then HOME() end
  end
end

function MBMMMM()
          MBM = gg.multiChoice({
  "— Bullet Mode 50% —",
  "— Bullet Mode 100% —",
  "🔶 BACK",
},nil,"📁 Bullet Mode Menu")
if MBM == nil then
else
if MBM[1] == true then MB1MBM() end
if MBM[2] == true then MB2MBM() end
if MBM[3] == true then weapons() end
end
end

function MBMMMMOTHER()
          MBM = gg.multiChoice({
  "— No Recoil All Weapons —",
  "— Less Recoil All Weapons —",
  "— No Recoil All Weapons v2 —",
  "🔶 BACK",
},nil,"📁 Other No Recoil Menu")
if MBM == nil then
else
if MBM[1] == true then norec9999() end
if MBM[2] == true then norecoil3all4() end
if MBM[3] == true then nor() end
if MBM[4] == true then weapons() end
end
end

function wallhackcolorsX()
W = gg.choice({
'📚 Sky Colors',
'🔲~Universal SnapWallhack~🔳',
'🗂️ [855 SnapDragon]',
'🗂️ [845 SnapDragon]',
'🗂️ [835-435 SnapDragon]',
'🗂️ [800-400 SnapDragon]',
'🗂️ [710 SnapDragon]',
'🗂️ [675 SnapDragon]',
'🗂️ [660 SnapDragon]',
'🔶 BACK'
},nil,'📁 WALLHACK/COLORS\n\n🔅(GAME/ISLAND)')
if W == 1 then skycolormenupro() end
if W == 2 then UNIVERSAL8SNAP() end
if W == 3 then SNAP7MENU() end
if W == 4 then SNAP6MENU() end
if W == 5 then SNAP5MENU() end
if W == 6 then SNAP4MENU() end
if W == 7 then SNAP3MENU() end
if W == 8 then SNAP2MENU() end
if W == 9 then SNAP1MENU() end
if W == 10 then HOME() end
HOMEDM=-1
end

function UNIVERSAL8SNAP()
snap1wallhack()
snap2wallhack()
snap3wallhack()
snap4wallhack()
snap5wallhack()
snap6wallhack()
snap7wallhack()
end

function SNAP1MENU()
SNAP = gg.multiChoice({
"— 660 Wallhack —",
"— 660 Color Red —",
"— 660 Color Yellow —",
"— Color Red v2 HDR —",
"— Color Red v3 —",
"🔶 BACK",
	  }, nil, "📁 MENU")
  if SNAP == nil then
  else
  if SNAP[1] == true then snap1wallhack() end
  if SNAP[2] == true then snap1colorred() end
  if SNAP[3] == true then snap1coloryellow() end
  if SNAP[4] == true then red2color() end
  if SNAP[5] == true then red3color() end
  if SNAP[6] == true then wallhackcolorsX() end
end
end
function snap1wallhack()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("135215D;4140D;3.7615819e-37;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("194D;3.7615819e-37;2;-1;1;-127", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("5.2806111e-40;6.50000333786;3.7615819e-37;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("9999", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("1.1202011e-19;1.1202015e-19;3.7615819e-37;255.0;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("9999", gg.TYPE_FLOAT)
gg.clearResults()
end
function snap1colorred()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("1.3912525e-19F;8200;96", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("8199", gg.TYPE_DWORD)
gg.clearResults()
end
function snap1coloryellow()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("1.3912525e-19F;8200;96", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("8198", gg.TYPE_DWORD)
gg.clearResults()
end

function SNAP2MENU()
SNAP = gg.multiChoice({
"— 675 Wallhack —",
"— 675 Color Red —",
"— 675 Color Yellow —",
"— Color Red v2 HDR —",
"— Color Red v3 —",
"🔶 BACK",
	  }, nil, "📁 MENU")
  if SNAP == nil then
  else
  if SNAP[1] == true then snap2wallhack() end
  if SNAP[2] == true then snap2colorred() end
  if SNAP[3] == true then snap2coloryellow() end
  if SNAP[4] == true then red2color() end
  if SNAP[5] == true then red3color() end
  if SNAP[6] == true then wallhackcolorsX() end
end
end
function snap2wallhack()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("200")
gg.getResults(20)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("930")
gg.getResults(20)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("5.2806111e-40;6.50000333786;3.7615819e-37;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("9999", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("1.1202011e-19;1.1202015e-19;3.7615819e-37;255.0;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("9999", gg.TYPE_FLOAT)
gg.clearResults()
end
function snap2colorred()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("8196D;8192D;8200D", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("8199", gg.TYPE_DWORD)
gg.clearResults()
end
function snap2coloryellow()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("8196D;8192D;8200D", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("8198", gg.TYPE_DWORD)
gg.clearResults()
end

function SNAP3MENU()
SNAP = gg.multiChoice({
"— 710 Wallhack —",
"— 710 Color Red —",
"— 710 Color Yellow —",
"— Color Red v2 HDR —",
"— Color Red v3 —",
"🔶 BACK",
	  }, nil, "📁 MENU")
  if SNAP == nil then
  else
  if SNAP[1] == true then snap3wallhack() end
  if SNAP[2] == true then snap3colorred() end
  if SNAP[3] == true then snap3coloryellow() end
  if SNAP[4] == true then red2color() end
  if SNAP[5] == true then red3color() end
  if SNAP[6] == true then wallhackcolorsX() end
end
end
function snap3wallhack()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("200")
gg.getResults(999)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("930")
gg.getResults(999)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("5.2806111e-40;6.50000333786;3.7615819e-37;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("9999", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("1.1202011e-19;1.1202015e-19;3.7615819e-37;255.0;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("9999", gg.TYPE_FLOAT)
gg.clearResults()
end
function snap3colorred()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("8196D;8192D;8200D", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("8199", gg.TYPE_DWORD)
gg.clearResults()
end
function snap3coloryellow()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("8196D;8192D;8200D", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("8198", gg.TYPE_DWORD)
gg.clearResults()
end

function SNAP4MENU()
SNAP = gg.multiChoice({
"— 800-400 Wallhack —",
"— 800-400 Color Red —",
"— 800-400 Color Yellow —",
"— Color Red v2 HDR —",
"— Color Red v3 —",
"🔶 BACK",
	  }, nil, "📁 MENU")
  if SNAP == nil then
  else
  if SNAP[1] == true then snap4wallhack() end
  if SNAP[2] == true then snap4colorred() end
  if SNAP[3] == true then snap4coloryellow() end
  if SNAP[4] == true then red2color() end
  if SNAP[5] == true then red3color() end
  if SNAP[6] == true then wallhackcolorsX() end
end
end
function snap4wallhack()
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("2.9427268e-44;2.0;3.0828566e-44;-1.0;3.2229865e-44;3.3631163e-44;3.643376e-44", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("3.1529215e-43;2.0F;3.1669345e-43F;3.1809475e-43:49", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("5.2806111e-40;6.50000333786;3.7615819e-37;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("9999", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("1.1202011e-19;1.1202015e-19;3.7615819e-37;255.0;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("9999", gg.TYPE_FLOAT)
gg.clearResults()
end
function snap4colorred()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("8204", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("E70", -1, gg.TYPE_DWORD, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("9999", gg.TYPE_DWORD)
gg.clearResults()
end
function snap4coloryellow()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("8204", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("E70", -1, gg.TYPE_DWORD, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("8564", gg.TYPE_DWORD)
gg.clearResults()
end

function SNAP5MENU()
SNAP = gg.multiChoice({
"— 835-435 Wallhack —",
"— 835-435 Color Red —",
"— 835-435 Color Yellow —",
"— Color Red v2 HDR —",
"— Color Red v3 —",
"🔶 BACK",
	  }, nil, "📁 MENU")
  if SNAP == nil then
  else
  if SNAP[1] == true then snap5wallhack() end
  if SNAP[2] == true then snap5colorred() end
  if SNAP[3] == true then snap5coloryellow() end
  if SNAP[4] == true then red2color() end
  if SNAP[5] == true then red3color() end
  if SNAP[6] == true then wallhackcolorsX() end
end
end
function snap5wallhack()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("2;1.8947657e-40;5.8013756e-42", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("2.718519e-43;3.7615819e-37;2;-1;1;-127", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("5.2806111e-40;6.50000333786;3.7615819e-37;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("9999", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("1.1202011e-19;1.1202015e-19;3.7615819e-37;255.0;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("9999", gg.TYPE_FLOAT)
gg.clearResults()
end
function snap5colorred()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("098", -1, gg.TYPE_DWORD, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("8199", gg.TYPE_DWORD)
gg.clearResults()
end
function snap5coloryellow()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("098", -1, gg.TYPE_DWORD, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("8198", gg.TYPE_DWORD)
gg.clearResults()
end

function SNAP6MENU()
SNAP = gg.multiChoice({
"— 845 Wallhack —",
"— 845 Color Blue —",
"— 845 Color Green —",
"— Color Red v2 HDR —",
"— Color Red v3 —",
"🔶 BACK",
	  }, nil, "📁 MENU")
  if SNAP == nil then
  else
  if SNAP[1] == true then snap6wallhack() end
  if SNAP[2] == true then snap6colorblue() end
  if SNAP[3] == true then snap6colorgreen() end
  if SNAP[4] == true then red2color() end
  if SNAP[5] == true then red3color() end
  if SNAP[6] == true then wallhackcolorsX() end
end
end
function snap6wallhack()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("200", -1, gg.TYPE_FLOAT, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("930", -1, gg.TYPE_FLOAT, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("5.2806111e-40;6.50000333786;3.7615819e-37;120", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("120", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("9999", gg.TYPE_FLOAT)
gg.clearResults()
end
function snap6colorblue()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("8201", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("0A0")
gg.getResults(100)
gg.editAll("8198", gg.TYPE_DWORD)
gg.clearResults()
end
function snap6colorgreen()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("8201", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("0A0")
gg.getResults(20)
gg.editAll("8199", gg.TYPE_DWORD)
gg.clearResults()
end

function SNAP7MENU()
SNAP = gg.multiChoice({
"— 855 Wallhack —",
"— 855 Color Red —",
"— 855 Color Yellow —",
"— Color Red v2 HDR —",
"— Color Red v3 —",
"🔶 BACK",
	  }, nil, "📁 MENU")
  if SNAP == nil then
  else
  if SNAP[1] == true then snap7wallhack() end
  if SNAP[2] == true then snap7colorred() end
  if SNAP[3] == true then snap7coloryellow() end
  if SNAP[4] == true then red2color() end
  if SNAP[5] == true then red3color() end
  if SNAP[6] == true then wallhackcolorsX() end
end
end
function snap7wallhack()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("95D;2;9.2194229e-41::100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("2;-1;0;1;-127;0.24022650719;0.69314718246;0.00999999978::30", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("5.2806111e-40;6.50000333786;3.7615819e-37;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("9999", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("1.1202011e-19;1.1202015e-19;3.7615819e-37;255.0;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("9999", gg.TYPE_FLOAT)
gg.clearResults()
end
function snap7colorred()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("328")
gg.getResults(20)
gg.editAll("8199", gg.TYPE_DWORD)
gg.clearResults()
end
function snap7coloryellow()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("328", -1, gg.TYPE_DWORD, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("8198", gg.TYPE_DWORD)
gg.clearResults()
end



function MB1MBM()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("88.15017700195;15", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("15", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("44", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("-88.66608428955;16", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("16", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("34", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("90.4850692749;27.25;18", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("27.25;18", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("44", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Magic Bullet 50% activated")
end

function MB2MBM()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("88.15017700195;15", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("15", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("98", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("-88.66608428955;16", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("16", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("68", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("90.4850692749;27.25;18", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("27.25;18", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("88", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Magic Bullet 100% activated")
end

function norec9999()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("1.5584387e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("1D;0.05000000075F;0.10000000149F;0.55000001192F;9.5F;15.0F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("1", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(500)
gg.editAll("0", gg.TYPE_DWORD)
gg.clearResults()
end

function antennav3()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0.98900693655~0.98900723457", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("16000", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Always Antenna v3")
end

function NGAAA()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber(":Default__MaterialExpressionLandscapeGrassOutput", gg.TYPE_BYTE, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(500)
gg.editAll("0", gg.TYPE_BYTE)
gg.clearResults()
gg.toast("No Grass activated")
end

function NFLLL()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber(":Default__ExponentialHeightFog", gg.TYPE_BYTE, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(500)
gg.editAll("0", gg.TYPE_BYTE)
gg.clearResults()
gg.toast("No Fog activated")
end

function nofogjdjdkdk()
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-2.3805679e21;-1.3620439e28;-1.3978205e24:9", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("-1.3620439e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(99)
gg.editAll("0", gg.TYPE_FLOAT)
gg.toast("No Fog")
end

function nograsstreesgghj()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("0.00390625;1;0.99900001287;2", gg.TYPE_FLOAT, false)
gg.searchNumber("1", gg.TYPE_FLOAT, false)
gg.getResults(30)
gg.editAll("0", gg.TYPE_FLOAT)
gg.toast("No Grass/Tress")
end

function red2color()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("298", -1, gg.TYPE_DWORD, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100, nil, nil, nil, nil, nil, nil, nil, nil)
gg.editAll("6", gg.TYPE_DWORD)
gg.toast("Red Color HDR activated")
end

function red3color()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("8,196D;8,192D;8,200D::", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("7", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Color Red activated")
end

function SmallCrossHair()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("2F;2F;1079446077;1.09375F;1F::17", gg.TYPE_DWORD,false, gg.SIGN_EQUAL,0,-1)
gg.refineNumber("1079446077", gg.TYPE_DWORD,false, gg.SIGN_EQUAL,0,-1)
gg.getResults(100)
gg.editAll("0", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Small CrossHair")
end

function kdjd8383()
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-3.83692277e21F;3.81276585e-21F;9.80153991e-31F;-1.11445016e28F;-2.02910209e20F",gg.TYPE_FLOAT,false,gg.SIGN_EQUAL,0,-1)
gg.searchNumber("-1.11445016e28",gg.TYPE_FLOAT,false,gg.SIGN_EQUAL,0,-1)
gg.getResults(6281913639784)
gg.editAll("0",gg.TYPE_FLOAT)
gg.clearResults()
end

function moregggddd()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("90.775703430176;0;8;15;16;18;28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("8000", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("More Damage activated")
end

function bulletmodev8()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("1F;-8.6457681e12F;15F;28F;16F;26F;8F;18F:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("15.0F;28.0F;16.0F;26.0F;8.0F;18.0F:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(500)
gg.editAll("95", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("1;20.51941871643;2.04908943176;-86.45767974854;-92.2311706543;16.0", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("16", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("100", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("9.20161819458;23;25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("240", gg.TYPE_FLOAT)
end

function norec9273()
gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("1.5584387e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("0", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("1D;0.05000000075F;0.10000000149F;0.55000001192F;9.5F;15.0F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(800)
  gg.editAll("0", gg.TYPE_DWORD)
  gg.clearResults()
  gg.setRanges(gg.REGION_C_DATA)
  gg.searchNumber("-2.786982e28;-3.7444097e28;-1.1368837e-13::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("-3.7444097e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(1)
  gg.editAll("0", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_C_DATA)
  gg.searchNumber("-2.8111605e28;-3.7444097e28;-1.1144502e28;128.0::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("-1.1144502e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(1)
  gg.editAll("0", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_C_DATA)
  gg.searchNumber("-6.1549454e27;1.8638966e-20;-1.1144502e28;0::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("-1.1144502e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(1)
  gg.editAll("0", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_C_DATA)
  gg.searchNumber("-1.238.624e28;-1.4239333e28;-1.1144502e28;-1.8331474e27;-    7.1608877e24::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("-1.1144502e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(2)
  gg.editAll("90", gg.TYPE_FLOAT)
gg.toast("No Recoil")
end

function bulletmodev7()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("1F;-8.6457681e12F;15F;28F;16F;26F;8F;18F:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("15.0F;28.0F;16.0F;26.0F;8.0F;18.0F:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(500)
gg.editAll("35", gg.TYPE_FLOAT)
gg.toast("Bullet Mode Activated")
end

function jdjkfjf8383kxjxk()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("95D;2;9.2194229e-41::100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(999)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("2;-1;0;1;-127;0.24022650719;0.69314718246;0.00999999978::30", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(999)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("8201", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("0A0")
gg.getResults(999)
gg.editAll("8198", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("8,196D;8,192D;8,200D::", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("7", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Wallhack/Red+White Color activated")
end

function esp0320()
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("720575962178125824", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(2)
gg.editAll("720575961854115840", gg.TYPE_QWORD)
gg.clearResults()
end

function dxjdj383()
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-5.73423916e27F;-1,283,514,890,394,129,918;-1,287,156,464,314,480,127;-1,283,514,886,099,101,181;-1,283,514,890,393,220,606;-1,324,311,049,571,137,023;-1,246,359,368,843,191,779:257",gg.TYPE_QWORD,false,gg.SIGN_EQUAL,0,-1)
gg.searchNumber("-5.73423916e27",gg.TYPE_FLOAT,false,gg.SIGN_EQUAL,0,-1)
gg.getResults(6281913639784)
gg.editAll("-5.73425156e27",gg.TYPE_FLOAT)
gg.clearResults()
end

function LargerH()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("7.13140678406;1.0;1.0;1.0:21", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("3", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("LARGER HEAD")
end
function GODWWWWW()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("3,266,314,240", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
local t = gg.getResults(99)
for i, v in ipairs(t) do
 t[i].value = '1,120,403,456'
 t[i].freeze = true
 t[i].freezetype = gg.FREEZE_MAY_INCREASE
 end
gg.addListItems(t)
gg.removeResults(t)
end
function CLRRAINBOW()
  gg.clearResults()
  gg.setRanges(131072)
  gg.searchNumber("4.5926155869782e-41;1.0863202718415e-19", 16, false, 536870912, 0, -1)
  gg.searchNumber("1.0863202718415e-19", 16, false, 536870912, 0, -1)
  gg.getResults(10)
  gg.editAll("1.0863202718415e-25", 16)
  gg.clearResults()
end
function CLRYELLOW()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO)
  gg.searchNumber("8200;96", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineAddress("090")
  gg.getResults(9999)
  gg.editAll("\"8198\"", gg.TYPE_DWORD)
  gg.clearResults()
  gg.toast("Yellow Color activated!")
end
function yell1129()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("8200;96", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("098", -1, gg.TYPE_DWORD, gg.SIGN_EQUAL, 0, -1)
gg.getResults(999)
gg.editAll("8198", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Color Yellow activated")
end
function CLRPURPLE()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO)
  gg.searchNumber("8,196D; 256D; 8,204D; 256D; 8,200D", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("8,200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(12)
  gg.editAll("16", gg.TYPE_DWORD)
  gg.clearResults()
  gg.toast("Body Purple Activated")
end
function CLRBLUE()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO)
  gg.searchNumber("856128", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(4)
  gg.editAll("99", gg.TYPE_DWORD)
  gg.clearResults()
  gg.searchNumber("200761;92;8204;856124;108;196610:409", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.refineNumber("8204", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  revert = gg.getResults(1000, nil, nil, nil, nil, nil, nil, nil, nil)
  gg.editAll("5555", gg.TYPE_DWORD)
end
function PINKBETA()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO)
  gg.searchNumber("32768;-2134900726;32769;-2134900725;32770;-2134900724::", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("32768;32770::", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("4", gg.TYPE_DWORD)
  gg.clearResults()
  gg.toast("Colour Smooth Pink activated!")
end
function CLRWHITE2()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO)
  gg.searchNumber("8200;96", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("8202", gg.TYPE_DWORD)
  gg.clearResults()
  gg.toast("White Body Color V2 activated")
end
function CLRDWHITE1()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO)
  gg.searchNumber("1.3912525e-19F;8200;96", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("8202", gg.TYPE_DWORD)
  gg.toast("Colour White V1 activated!")
  gg.clearResults()
end
function CLRRED3()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO)
  gg.searchNumber("1.1490647e-41;1.0863203e-19::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1.0863203e-19", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("1.0863203e-25", gg.TYPE_FLOAT)
  gg.toast("Body Color Red v3 Activated")
end

function onespmode2019p1()
gg.searchNumber("\"-1901891198734303227\"", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100, nil, nil, nil, nil, nil, nil, nil, nil)
gg.editAll("\"-1901891198902075392\"", gg.TYPE_QWORD)
gg.toast("ESP Mode activated")
end

function offespmode2019p1()
gg.searchNumber("\"-1901891198902075392\"", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100, nil, nil, nil, nil, nil, nil, nil, nil)
gg.editAll("\"-1901891198734303227\"", gg.TYPE_QWORD)
gg.toast("ESP Mode Deactivated")
end

function AntiFog()
hifumi = {
{["memory"] = gg.REGION_ANONYMOUS},
{["name"] = "Remove Fog"},
{["value"] = 100000, ["type"] = gg.TYPE_FLOAT},
{["antilogger"] = 1000, ["offset"] = 4, ["type"] = gg.TYPE_FLOAT},
{["antilogger"] = 10000, ["offset"] = -28, ["type"] = gg.TYPE_FLOAT},
}
aocchi = {
{["value"] = 1000088888888, ["offset"] = -60, ["type"] = gg.TYPE_FLOAT},
}
aoba(aocchipubg)
gg.toast("No Fog All Maps activated")
end

function aimbot50mm()
gg.clearResults()
gg.setRanges(8)
gg.setRanges(8)
gg.searchNumber("360;0.0001;1478828288", 16, false, 536870912, 0, -1)
gg.searchNumber("0.0001", 16, false, 536870912, 0, -1)
gg.getResults(100)
gg.editAll("9999", 16)
gg.toast("Aimbot v2 activated")
end

function NGTV2()
    gg.clearResults()
    gg.setRanges(gg.REGION_VIDEO)
    gg.searchNumber("0.00390625;1;0.99900001287;2",gg.TYPE_FLOAT,false)
    gg.searchNumber("1",gg.TYPE_FLOAT,false)
    gg.getResults(30)
    gg.editAll("0",gg.TYPE_FLOAT)
gg.toast("No Grass/Trees activated")
end

function BBREDDDDDD()
    gg.clearResults()
    gg.searchNumber("8200;96", 4, false, 536870912, 0, -1)
    gg.refineAddress("090")
    gg.getResults(9999)
    gg.editAll("\"8199\"", 4)
  end

function NGSH()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.clearResults()
gg.searchNumber("5126;3;67584", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("3", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("4", gg.TYPE_DWORD)
gg.toast("No Grass Sanhok activated")
end

function sjjsjdjdPPpp()
PDQ = gg.multiChoice({'— Wallhack 865 —','— Color Red 865 —','— Color Red HDR 865 —','— Fix Blink 865 —','📚 MORE COLORS','🔙 BACK'},nil,'MENU')
if PDQ == nil then else
if PDQ[1] == true then whV4() end
if PDQ[2] == true then BRED() end
if PDQ[3] == true then redhdrnew() end
if PDQ[4] == true then fixBlink2() end
if PDQ[5] == true then OTHERCOLORSMENU() end
if PDQ[6] == true then wallhackcolorsX() end
end
end

function dhhdjdjdjxjdbbd()
PDQ = gg.multiChoice({'— Wallhack 730G —','— Color Red 730G —','— Color Red HDR 730G —','— Fix Blink 730G —','📚 MORE COLORS','🔙 BACK'},nil,'MENU')
if PDQ == nil then else
if PDQ[1] == true then whV4() end
if PDQ[2] == true then BRED() end
if PDQ[3] == true then redhdrnew() end
if PDQ[4] == true then fixBlink2() end
if PDQ[5] == true then OTHERCOLORSMENU() end
if PDQ[6] == true then wallhackcolorsX() end
end
end

function NGEL()
    gg.clearResults()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber('7499628;1935766087;29541::', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1)
    gg.searchNumber('29541', gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResultCount()
    gg.getResults(1)
    gg.editAll('1886999666', gg.TYPE_DWORD)
gg.toast("No Grass Erangel activated")
end

function NGT()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("2;10000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("No Grass/Trees activated")
end

function NGE()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS)
  gg.searchNumber("8.0F;1.20000004768F;0.80000001192F;1.5F;0.80000001192F;1.5F::512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("8.0", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(300)
  gg.editAll("0", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("No Grass Erangel activated")
end

function aimbot360gg()
gg.clearResults()
gg.setRanges(32)
gg.searchNumber("3.5;1.0;0.5;0.10000000149;200.0::512", 16, false, 536870912, 0, -1)
gg.searchNumber("3.5;1.0;0.5;0.10000000149;200.0::512", 16, false, 536870912, 0, -1)
gg.getResults(100)
gg.editAll("999999", 16)
gg.clearResults()
gg.setRanges(32)
gg.searchNumber("3.5;1;0.5;200;20::", 16)
gg.getResults(200)
gg.editAll("999999999", 16)
gg.setRanges(32)
gg.searchNumber("6.0;2.0;1.0::99", 16, false, 536870912, 0, -1)
gg.searchNumber("1", 16, false, 536870912, 0, -1)
gg.getResults(100)
gg.editAll("101", 16)
gg.clearResults()
gg.setRanges(32)
gg.searchNumber("3.5;1;0.5;200;20::", 16)
gg.getResults(200)
gg.editAll("999999999", 16)
gg.clearResults()
gg.toast("Aimbot v3 activated")
end

function NGTH()
gg.clearResults()
  gg.setRanges(gg.REGION_C_BSS)
  gg.searchNumber("2048D;4D;1F;1F;1D:17", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  ex = gg.getResults(100)
  for _FORV_3_ = 1, #ex do
    ex[_FORV_3_].value = "0.07"
    ex[_FORV_3_].freeze = true
    ex[_FORV_3_].freezeType = gg.FREEZE_NORMAL
  end
  gg.addListItems(ex)
  gg.clearResults()
gg.toast("No Grass/Trees/House activated")
end

function FFPP1()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0.75;150;1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(999)
gg.editAll("30", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("0.75;150;30", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("0.75", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(999)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Fast Parachute")
end

function IPADWWW()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("2.8025969e-45;220;25;178;15;100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("220", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("440", gg.TYPE_FLOAT)
gg.toast("Ipad View activated")
end

function IPADWWWW()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("220;178;15", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("220", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(300)
gg.editAll("438", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Wide View activated")
end

function aimbot2019v2()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("3.5;1;0.5;200;20::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(600)
gg.editAll("99999", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("-88.82363891602F;15.0F;1", gg.TYPE_FLOAT)
gg.searchNumber("1", gg.TYPE_FLOAT)
gg.getResults(2000)
gg.editAll("20000000000000", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Aimbot v1 activated")
end

function aimv29()
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("360;0.0001;1478828288", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("0.0001", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("9999", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Aimlock")
end

function throughbuggy()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.clearResults()
gg.searchNumber("982622900;1956496814;1112014847;1103626239", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1956496814", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("1091567616", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Through Walls On Buggy activated")
end

function longh44()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("1;35;443;55;0.57357645035", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(500)
gg.editAll("3", gg.TYPE_FLOAT)
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("3;35;443;55;0.57357645035", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("443", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(500)
gg.editAll("2500", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0;7.0064923e-45;1;100;1;2,500,000,000.0;0.10000000149;88", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("1.7", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("High Jump v2 activated")
end

function headshotmodexxxLobby()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("-88.66608428955;26:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("26", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(5)
gg.editAll("-760", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("-88.73961639404;28:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(5)
gg.editAll("-800", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("9.201618;30.5;25", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("259", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Headshot Mode activated")
end

function Qweaponc()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0.83333331347;1;0.83333331347::321", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.83333331347", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(200)
gg.editAll("0.000001", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Quick Weapon Change activated")
end

function LYINGKKK2()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("-9.5367432e-7;-0.10621572286;-0.3004361093;0.46691286564;23.5222568512::17", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("-9.5367432e-7;23.5222568512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(21)
gg.editAll("-205;-105", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Lift Stand Aim activated")
end

function LYINGKKK1()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0.53869867324829;13.279829025269;-0.004204273223877;23.525857925415::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("-0.004204273223877", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("-330", gg.TYPE_FLOAT)
gg.toast("Lift Sit Down Aim activated")
end

function LYINGKKK0()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("18.38614463806;0.53446578979;-3.42663908005F;0.69551950693F::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResultsCount()
gg.searchNumber("18.38614463806;0.53446578979", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("240", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Lift Lying Down Aim activated")
end

function oooopppp()
gg.clearResults()
gg.setRanges(32)
gg.searchNumber("9.20161819458;23;25;30.5", 16, false, 536870912, 0, -1)
gg.searchNumber("25;30.5", 16, false, 536870912, 0, -1)
gg.getResults(10)
gg.editAll("290", 16)
gg.toast("Headshot Mode 50% activated")
end

function oo5059nor()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("1.4012985e-45;1;1;1;1;100000::100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("0.5", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("No Recoil 50% activated")
end

function norecoil3all4()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("1.5584387e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1.5584387e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("-1,082,130,432;1,084,227,584;132,608;1,065,353,216;1;0.05000000075F;8.0F;0.10000000149F;0.55000001192F::", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("0", gg.TYPE_DWORD)
gg.toast("Less Recoil activated")
end

function njddj877()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("10000;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("0", gg.TYPE_FLOAT)
gg.toast("No Grass All Maps activated")
end

function antishakeee()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0.2~0.3;53;30;1::", gg.TYPE_FLOAT)
gg.searchNumber("0.2~0.3;1::", gg.TYPE_FLOAT)
gg.getResults(200)
gg.editAll("1.4012985e-45", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Anti Shake activated")
end

function blackskyall()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("000", -1, gg.TYPE_FLOAT, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("-90", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Black Sky All Map activated")
end

function AWecharge()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("128D;-1D;1.7;0.3::100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1.7", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("0", gg.TYPE_FLOAT)
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("76000;5D;1.89999997616;0.1::50", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1.89999997616", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("91000;2.29999995232;1.8", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2.29999995232;1.8", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(15)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("AWM, Kar98 No Recharge activated")
end

function moremdamagex()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("90.775703430176;0;8;15;16;18;28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("1000", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("More Damage activated")
end

function bulletmodev5()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("25;23;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(3)
gg.editAll("180", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Bullet Mode activated")
end

function bulletmodev6()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("-88.66608428955;26:512",gg.TYPE_FLOAT,false,gg.SIGN_EQUAL,0,-1)
gg.refineNumber("26",gg.TYPE_FLOAT,false,gg.SIGN_EQUAL,0,-1)
gg.getResults(20)
gg.editAll("-460",gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("-88.73961639404;28:512",gg.TYPE_FLOAT,false,gg.SIGN_EQUAL,0,-1)
gg.refineNumber("28",gg.TYPE_FLOAT,false,gg.SIGN_EQUAL,0,-1)
gg.getResults(20)
gg.editAll("-560",gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Bullet Mode")
end

function norecoil1one()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("176293393;8F;9.5F;15F::", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("176293393", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("0", gg.TYPE_DWORD)
gg.toast("No Recoil One Weapon activated")
end

function SPEEDMANY1()
MN17 = gg.multiChoice({
"🌀Dacia V1",
"🌀Dacia V2",
"🌀UAZ V1",
"🌀UAZ V2",
"🌀UAZ [Fly]",
"🌀UAZ [Unlimited Gas]",
"🌀Buggy",
"🌀Mirado",
"🌀Pickup Truck",
"🌀Van",
"🌀Rony",
"🌀Motorcycle",
"🌀Motorcycle [Sidecar]",
"🌀Scooter",
"🌀Snowmobile",
"🌀All Vehicle",
"🔶 BACK"
	  }, nil, "📁 Speed/Fly Car Menu")
  if MN17 == nil then
  else
  if MN17[1] == true then DACIA1() end
  if MN17[2] == true then DACIA2() end
  if MN17[3] == true then UAZ1() end
  if MN17[4] == true then UAZ2() end
  if MN17[5] == true then UAZFLY() end
  if MN17[6] == true then UAZ3() end
  if MN17[7] == true then BUGGY() end
  if MN17[8] == true then MIRADO() end
  if MN17[9] == true then TRUCK() end
  if MN17[10] == true then VAN() end
  if MN17[11] == true then RONY() end
  if MN17[12] == true then MOTOR() end
  if MN17[13] == true then MOTORSIDE() end
  if MN17[14] == true then SCOOTER() end
  if MN17[15] == true then SNOWMOBILE() end
  if MN17[16] == true then ALLVEHICLE() end
  if MN17[17] == true then player() end
  end
end

function UAZ3()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0.647058857", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("-999", gg.TYPE_FLOAT)
gg.toast("Speed&Unlimited Gas UAZ activated")
end

function VAN()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0.57142859697;0.55555558205;0.91428571939::9", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.57142859697;0.55555558205::5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.57142859697;0.55555558205::5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.57142859697;0.55555558205::5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(50)
gg.editAll("30.241295", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Speed Van activated")
end

function RONY()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0.72231060266;0.38461539149;0.86677277088::9", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.72231060266;0.38461539149::5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.72231060266;0.38461539149::5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.72231060266;0.38461539149::5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(50)
gg.editAll("20.241295", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Speed Rony activated")
end

function TRUCK()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0.63636362553;0.38461539149;0.90909093618::9", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.63636362553;0.38461539149::5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.63636362553;0.38461539149::5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.63636362553;0.38461539149::5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(50)
gg.editAll("50.241295", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Speed Pickup Truck activated")
end

function MIRADO()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0.62222224474;0.43636363745;1::9", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.62222224474;0.43636363745::5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.62222224474;0.43636363745::5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.62222224474;0.43636363745::5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(50)
gg.editAll("35.241295", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Speed Mirado activated")
end

function SCOOTER()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0.34999999404;0.69999998808;1::9", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.34999999404;0.69999998808::5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.34999999404;0.69999998808::5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.34999999404;0.69999998808::5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(50)
gg.editAll("30.241295", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Speed Scooter activated")
end

function BUGGY()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0.69230771065;0.50021028519;1::9", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.69230771065;0.50021028519::5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.69230771065;0.50021028519::5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.69230771065;0.50021028519::5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(50)
gg.editAll("30.241295", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Speed Buggy activated")
end

function MOTOR()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0.37209302187;0.69999998808;1::9", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.37209302187;0.69999998808::5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.37209302187;0.69999998808::5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.37209302187;0.69999998808::5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(50)
gg.editAll("30.241295", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Speed Motorcycle activated")
end

function SNOWMOBILE()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("1;0.69999998808;1065353216D;1065353216D;0.48888888955::17", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1;0.69999998808::5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1;0.69999998808::5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1;0.69999998808::5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(50)
gg.editAll("30.241295", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Speed Snowmobile activated")
end

function MOTORSIDE()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0.34883719683;0.69999998808;1::9", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.34883719683;0.69999998808::5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.34883719683;0.69999998808::5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.34883719683;0.69999998808::5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(50)
gg.editAll("30.241295", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Speed Motorcycle [Sidecar] activated")
end

function ALLVEHICLE()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("1000;10;4D;4D;50;5;2;0.01::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.01", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.01", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.01", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(280)
gg.editAll("-0.23", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Speed All Vehicle activated")
end

function UAZFLY()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0.76000005007;0.96078431606;1;0.74509805441::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.74509805441", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(9999)
gg.editAll("99999", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("45F;15F;20F;2500F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("45", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(999)
gg.editAll("500", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Speed/Fly UAZ activated")
end

function UAZ2()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0.647058857;0.30000001192;0.94117647409::9", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.647058857;0.30000001192::5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.647058857;0.30000001192::5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.647058857;0.30000001192::5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(50)
gg.editAll("50.241295", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Speed UAZ V2 activated")
end

function UAZ1()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0.647058857;0.30000001192;0.94117647409::9", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.647058857;0.30000001192::5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.647058857;0.30000001192::5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.647058857;0.30000001192::5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(50)
gg.editAll("100.241295", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Speed UAZ V1 activated")
end

function DACIA2()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("1000;10;4D;4D;50;5;2;0.03::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.03", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.03", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.03", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(280)
gg.editAll("-0.23", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Speed Dacia V2 activated")
end

function DACIA1()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0.72727274895;0.34377467632;1::9", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.72727274895;0.34377467632::5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.72727274895;0.34377467632::5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.72727274895;0.34377467632::5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(50)
gg.editAll("65.241295", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Speed Dacia V1 activated")
end

function headshotmodex()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("-88.66608428955;26:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("26", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(2)
gg.editAll("-460", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("-88.73961639404;28:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(2)
gg.editAll("-560", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("9.201618;30.5;25;23", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("23", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("50", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("9.201618;30.5;25;0", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("25", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("150", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("9.201618;30.5;150;0", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("150", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("-88.66608428955;26:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("26", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(2)
gg.editAll("-460", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("-88.73961639404;28:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(2)
gg.editAll("-560", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("9.201618;30.5;25;0", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("25", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("180", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("9.201618;30.5;180;0", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("150", gg.TYPE_FLOAT)
gg.clearResults()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("-88.66608428955;26:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("26", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(2)
gg.editAll("-460", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("-88.73961639404;28:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(2)
gg.editAll("-560", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("9.201618;30.5;25", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("30.5;25", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("253", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_C_BSS)
gg.searchNumber("2048D;1F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("0.07", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("9.1022205e-38;0.0001;9.1025635e-38::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.0001", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("125", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("-7.1611644e24;0.0001;1.1297201e-37::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.0001", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(500)
gg.editAll("-125", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Headshot Mode activated")
end

function zoom8xonon()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("60;55;1.9618179e-44 ", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("55", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(300)
gg.editAll("15", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Zoom 8X activated")
end

function zoom4xonon()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("60;55;1.9618179e-44 ", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("55", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(300)
gg.editAll("19", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Zoom 4X activated")
end

function zoom6xonon()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("60;55;1.9618179e-44 ", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("55", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(300)
gg.editAll("17", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Zoom 6X activated")
end

function zoom15xonon()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("60;55;1.9618179e-44 ", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("55", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(300)
gg.editAll("9", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Zoom 15X activated")
end

function qs()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber(35000, gg.TYPE_FLOAT)
gg.searchNumber(35000, gg.TYPE_FLOAT)
gg.getResults(20)
gg.editAll(800000, gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Quick Shot activated")
end

function fw()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0.83333331347;1;0.83333331347::321", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.83333331347", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(200)
gg.editAll("0.000001", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Rapid Fire activated")
end

function nor()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("50;200;0.5;40.0;0.3:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.3", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("300", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("1;10000D;100000:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(200)
gg.editAll("0.001", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0.2~0.3;53;30;1::", gg.TYPE_FLOAT)
gg.searchNumber("0.2~0.3;1::", gg.TYPE_FLOAT)
gg.getResults(200)
gg.editAll("1.4012985e-45", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast('No Recoil All Weapons activated')
end

function antennacor99()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("14.79005432129",gg.TYPE_FLOAT,false,gg.SIGN_EQUAL,0,-1)
gg.searchNumber("14.79005432129",gg.TYPE_FLOAT,false,gg.SIGN_EQUAL,0,-1)
gg.getResults(30)
gg.editAll("99999",gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Corpse Antenna activated")
end

function antennaback99()
gg.clearResults()
gg.searchNumber("0.9378669858F;1.0F;0.61365610361F::55", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(850)
gg.editAll("9999", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Backpack Antenna activated")
end

function hsmenupro()
          MBM = gg.multiChoice({
  "— HeadShot 50% —",
  "— HeadShot 100% —",
  "🔶 BACK",
},nil,"📁 HeadShot Menu")
if MBM == nil then
else
if MBM[1] == true then hs50() end
if MBM[2] == true then hs100() end
if MBM[3] == true then weapons() end
end
end

function hs100()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("9.20161819458;23;25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("25", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(5)
gg.editAll("250", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("9.20161819458;23;250;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(5)
gg.editAll("305", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("HeadShot 100% activated")
end

function hs90()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("9.20161819458;23;25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("400", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("HeadShot 90% activated")
end

function hs80()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("9.20161819458;23;25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("350", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("HeadShot 80% activated")
end

function hs70()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("9.20161819458;23;25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("300", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("HeadShot 70% activated")
end

function hs60()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("9.20161819458;23;25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("250", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("HeadShot 60% activated")
end

function hs50()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("9.20161819458;23;25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("25", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(5)
gg.editAll("125", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("9.20161819458;23;125;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(5)
gg.editAll("152", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("HeadShot 50% activated")
end

function ULTRASPEEDNOLAGOCTOBER()
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-1,296,744,149,883,614,555", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(99)
gg.editAll(" -1,296,744,153,870,237,696", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-1,904,987,454,010,553,855", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(99)
gg.editAll("-1,904,987,454,002,165,247", gg.TYPE_QWORD)
gg.clearResults()
end

function FIXDAMAGED()
FD = gg.multiChoice({
  '— Fix All Weapon —',
  '— M416 —',
  '— SCAR —',
  '— M16A4 —',
  '— AKM —',
  '— KAR —',
  '— AWM —',
  '— SKS —',
  '— MINI —',
  '— M249 —',
  '— DP28 —',
  '— QBZ —',
  '— G36 —',
  '— AUG —',

  '— BERYL —',
  '— GROZA —',
  '— MUTAN —',

  '— M24 —',

  '— MK —',

  '— SLR —',
  '— QBU —',
  '🔶 BACK'
},nil, 'FIX DAMAGE MENU')
if FD == nil then else
if FD[1] == true then fixallweaponnnn() end
if FD[2] == true then M416D() end
if FD[3] == true then SCARD() end
if FD[4] == true then M16A4D() end
if FD[5] == true then AKMD() end
if FD[6] == true then KARD() end
if FD[7] == true then AWMD() end
if FD[8] == true then SKSD() end
if FD[9] == true then MINID() end
if FD[10] == true then M249D() end
if FD[11] == true then DP28D() end
if FD[12] == true then FD1() end
if FD[13] == true then FD2() end
if FD[14] == true then FD3() end
if FD[15] == true then FD4() end
if FD[16] == true then FD5() end
if FD[17] == true then FD6() end
if FD[18] == true then FD7() end
if FD[19] == true then FD8() end
if FD[20] == true then FD9() end
if FD[21] == true then FD10() end
if FD[22] == true then SPEEDHACKMENUP() end
end
end

function fixallweaponnnn()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("88000;0.08600000292", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("88000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("87000;0.09600000083", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("87000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("90000;0.07500000298", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("90000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("87000;0.09229999781", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("87000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("87000;0.86", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("87000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("94000;0.08570999652", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("94000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("71500;0.10000000149", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("71500", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("71500", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("71500", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("71500;0.07999999821", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("71500", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("78000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("78000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("91000;2.2;2.5::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("91000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("76000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("76000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("79000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("79000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("80000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("80000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("85300;0.09000000358", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("85300", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("99000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("99000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("84000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("84000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("94500", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("94500", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("91500;0.07500000298", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("91500", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("71500;0.109", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("71500", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Fix No Damage All Weapon")
end

function FD1()
    gg.clearResults()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber('87000;0.09229999781', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber('87000', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1401)
    gg.editAll('37401', gg.TYPE_FLOAT)
    gg.clearResults()

  end
  function FD2()
    gg.clearResults()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber('87000;0.86', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber('87000', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1401)
    gg.editAll('37401', gg.TYPE_FLOAT)
    gg.clearResults()

  end
  function FD3()
    gg.clearResults()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber('94000;0.08570999652', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber('94000', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1401)
    gg.editAll('37401', gg.TYPE_FLOAT)
    gg.clearResults()

  end
  function FD4()
    gg.clearResults()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber('71500', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber('71500', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1401)
    gg.editAll('37401', gg.TYPE_FLOAT)

    gg.clearResults()
  end
  function FD5()
    gg.clearResults()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber('71500;0.07999999821', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber('71500', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1401)
    gg.editAll('37401', gg.TYPE_FLOAT)
    gg.clearResults()

  end
  function FD6()
    gg.clearResults()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber('78000', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber('78000', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1401)
    gg.editAll('37401', gg.TYPE_FLOAT)

    gg.clearResults()
  end
  function FD7()
    gg.clearResults()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber('79000', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber('79000', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1401)
    gg.editAll('37401', gg.TYPE_FLOAT)

    gg.clearResults()
  end
  function FD8()
    gg.clearResults()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber('85300;0.09000000358', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber('85300', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1401)
    gg.editAll('37401', gg.TYPE_FLOAT)
    gg.clearResults()


  end
  function FD9()
    gg.clearResults()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber('84000', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber('84000', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1401)
    gg.editAll('37401', gg.TYPE_FLOAT)

    gg.clearResults()
  end
  function FD10()
    gg.clearResults()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber('94500', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber('94500', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1401)
    gg.editAll('37401', gg.TYPE_FLOAT)

    gg.clearResults()
  end

function SPEEDHACKMENUP()
SHG = gg.choice({
'— Fix Damage —',
'[ON]\n— No Lag SpeedHack Player —',
'[OFF]\n— No Lag SpeedHack Player —',
'[ON]\n— SpeedHack Game (lag) —',
'[OFF]\n— SpeedHack Game (lag) —',
'Micro Speedhack',
'🔶 BACK'
},nil,'📁 SpeedHack Menu') 
if SHG == 1 then FIXDAMAGED() end 
if SHG == 2 then speedh15on() end 
if SHG == 3 then speedh15off() end 
if SHG == 4 then GameSLIGHT() end
if SHG == 5 then GameSLIGHTF() end
if SHG == 6 then speedhacklitex() end
if SHG == 7 then HOME() end
end

function speedh15on()
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-1,296,744,149,883,614,555", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(99)
gg.editAll(" -1,296,744,153,870,237,696", gg.TYPE_QWORD)
gg.clearResults()
gg.searchNumber("-1,904,987,454,010,553,855", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(99)
gg.editAll("-1,904,987,454,002,165,247", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("1;1;1;0.0001;20;0.0005;0.4::50", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("1.07", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("1.0F;0.6;0.1;0.125F::55", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("2.90", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("50000~100000;0;1;5D~100D::13", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("50000~100000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(210)
gg.editAll("35125", gg.TYPE_FLOAT)
gg.clearResults()
end 

function speedh15off()
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-1,296,744,153,870,237,696", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(99)
gg.editAll("-1,296,744,149,883,614,555", gg.TYPE_QWORD)
gg.clearResults()
gg.searchNumber("-1,904,987,454,002,165,247", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(99)
gg.editAll("-1,904,987,454,010,553,855", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("1.07;0.0001;20;0.0005;0.4::50", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("1.07", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("1", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("2.90;0.6;0.1;0.125F::55", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("2.90", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("1", gg.TYPE_FLOAT)
gg.clearResults()
end 

function M416D()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("88000;0.08600000292", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("88000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
end
function SCARD()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("87000;0.09600000083", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("87000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
end
function M16A4D()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("90000;0.07500000298", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("90000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
end
function AKMD()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("71500;0.10000000149", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("71500", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
end
function KARD()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("76000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("76000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
end 
function AWMD()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("91000;2.2;2.5::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("91000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
end
function SKSD()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("80000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("80000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
end
function MINID()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("99000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("99000", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
end
function M249D()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("91500;0.07500000298", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("91500", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
end
function DP28D()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("71500;0.109", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("71500", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll("37401", gg.TYPE_FLOAT)
gg.clearResults()
end

function PlayerSLIGHT2()
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-1296744149883614555", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(99)
gg.editAll("-1296744153870237696", gg.TYPE_QWORD)
gg.clearResults()
gg.searchNumber("-1904987454010553855", gg.TYPE_QWORD,false, gg.SIGN_EQUAL,0,-1)
gg.getResults(99)
gg.editAll("-1904987454002165247", gg.TYPE_QWORD)
gg.clearResults()
end

function PlayerSLIGHTF2()
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-1296744153870237696", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(99)
gg.editAll("-1296744149883614555", gg.TYPE_QWORD)
gg.clearResults()
gg.searchNumber("-1904987454002165247", gg.TYPE_QWORD,false, gg.SIGN_EQUAL,0,-1)
gg.getResults(99)
gg.editAll("-1904987454010553855", gg.TYPE_QWORD)
gg.clearResults()
end

function GameSLIGHT()
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-1296744149883614555", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(99)
gg.editAll("-1296744153870237696", gg.TYPE_QWORD)
gg.clearResults()
gg.searchNumber("-1505254313802431360", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(99)
gg.editAll("-1505254313805479936", gg.TYPE_QWORD)
gg.clearResults()
end

function GameSLIGHTF()
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-1296744153870237696", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(99)
gg.editAll("-1296744149883614555", gg.TYPE_QWORD)
gg.clearResults()
gg.searchNumber("-1505254313805479936", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(99)
gg.editAll("-1505254313802431360", gg.TYPE_QWORD)
gg.clearResults()
end

function SLIGHT()
  gg.clearResults()
  gg.searchNumber("20000;750;0.0001;0.0005 ", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("0.0005", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("0.07", gg.TYPE_FLOAT)
  gg.searchNumber("1.0F;0.6;0.1;0.125F::55", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("2.55", gg.TYPE_FLOAT)
  gg.toast("Ultra Speedhack Game activated")
end

function SLIGHTF()
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS | gg.REGION_CODE_APP)
  gg.searchNumber("20000;750;0.0001;0.07 ", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("0", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_ANONYMOUS | gg.REGION_CODE_APP)
  gg.searchNumber("2.55F;0.6;0.1;0.125F::55", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("1", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("Ultra Speedhack Game Deactivated")
end

function USHON()
    gg.clearResults()
    gg.setRanges(gg.REGION_C_DATA)
    gg.searchNumber("-8.795458e22;-3.693674e20;-1.2382424e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("-1.2382424e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1)
    gg.editAll("1.2382424e28", gg.TYPE_FLOAT)
    gg.clearResults()
gg.toast("Ultra Speedhack Player activated")
  end
  
function USHOFF()
    gg.clearResults()
    gg.setRanges(gg.REGION_C_DATA)
    gg.searchNumber("-8.795458e22;-3.693674e20;1.2382424e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("1.2382424e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1)
    gg.editAll("-1.2382424e28", gg.TYPE_FLOAT)
    gg.clearResults()
gg.toast("Ultra Speedhack Player Deactivated")
  end

function underwaterjeepx() 
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("150;85;45;-129;-85", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("45", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("99998", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("1;5;4;0.001 ", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("0.001", gg.TYPE_FLOAT)
gg.toast("Underwater Jeep activated")
end

function quickparachute()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0.75;150;1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("30", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0.75;150;30", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.75", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Quick Parachute activated")
end

function aaaath8()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0.99626296759",gg.TYPE_FLOAT, false,gg.SIGN_EQUAL, 0, -1)
gg.getResultCount()
gg.getResults(50)
gg.editAll("150",gg.TYPE_FLOAT)
gg.getResults(50)
gg.clearResults()
gg.toast("Antenna Always v3 activated")
end

function aaaath9()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("88.50576019287F;87.27782440186F;1F::50",gg.TYPE_FLOAT, false,gg.SIGN_EQUAL, 0, -1)
gg.getResults(7)
gg.editAll("1.96875",gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("1.96875F;1.96875F;-100.91194152832;1F::50",gg.TYPE_FLOAT, false,gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1",gg.TYPE_FLOAT, false,gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("976",gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0.98900693655~0.98900723457;0.14786802232~0.14786840975;1.1920926e-7::9",gg.TYPE_FLOAT, false,gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.98900693655~0.98900723457",gg.TYPE_FLOAT, false,gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("16000",gg.TYPE_FLOAT)
gg.toast("Antenna Always v4 activated")
end

function sptronghighjump()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("1;35;443;55;0.57357645035", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(500)
gg.editAll("3", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("3;35;443;55;0.57357645035", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("443", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(500)
gg.editAll("2500", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("High Jump v2 activated")
end

function doublejumpnodamage()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("3;35;443;55;0.57357645035", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("443", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(500)
gg.editAll("750", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Double Jump activated")
end

function aaath5()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("88.50576019287F;87.27782440186F;-100.91194152832F;1F::13", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("88.50576019287F;87.27782440186F;1F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(6)
gg.editAll("1.96875;1.96875;999;1.96875;1.96875;999", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("88.50576019287F;87.27782440186F;-100.91194152832F;1F::13", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("88.50576019287F;87.27782440186F;1F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(6)
gg.editAll("1.96875;1.96875;999;1.96875;1.96875;999", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Always Antenna v1 activated")
end

function antennav2()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("88.50576019287F;87.27782440186F;-100.91194152832F;1F::13", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("88.50576019287F;87.27782440186F;1F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(999)
gg.editAll("1.96875;1.96875;999;1.96875;1.96875;999", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Antenna Always v2")
end

function speedhacklitex()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("1;0.0001;20;0.0005;0.4", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(999)
gg.editAll("1.055", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast('Micro SpeedHack activated')
end

function speedcarx()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("50;5;0.01", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.01", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(280)
gg.editAll("-0.23", gg.TYPE_FLOAT)
gg.toast('Speedcar activated')
end

function flycarx()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0.76000005007;0.96078431606;1;0.74509805441::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.74509805441", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(9999)
gg.editAll("99999", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("45F;15F;20F;2500F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("45", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(999)
gg.editAll("500", gg.TYPE_FLOAT)
gg.toast("Flycar activated")
end

function aaath4()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("88.50576019287F;87.27782440186F;1F::50", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(7)
gg.editAll("1.96875", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("1.96875F;1.96875F;-100.91194152832;1F::50", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("976", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0.98900693655~0.98900723457;0.14786802232~0.14786840975;1.1920926e-7::9", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResultsCount()
gg.searchNumber("0.98900693655~0.98900723457", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("16000", gg.TYPE_FLOAT)
gg.toast("Antena Always V4 activated")
end

function fastjeepuuu()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0.647058857", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("-999", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0.647058857", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("-9999", gg.TYPE_FLOAT)
gg.toast("Fast Jeep activated")
end

function jtw()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("3.5032462e-44F;10.0F;45.0F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("10", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("9999", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast('Jump Through Walls activated')
end

function mj()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("1.0F; -0.70710676908F; 0.70710670948F; 64.0F; 1.793662e-43F;1.4012985e-45F; 1D; 1D ::512", gg.TYPE_FLOAT, false)
gg.searchNumber("1.4012985e-45", gg.TYPE_FLOAT, false)
gg.getResults(30)
gg.editAll("999.0", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast('Multi Jump activated')
end

function hj()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.clearResults()
gg.searchNumber("1;35;443;0.5;55;0.57357645035", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(850)
gg.editAll("0.5", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast('High Jump v1 activated')
end

function lj()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.clearResults()
gg.searchNumber("-980.0F;0.30000001192F:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("-980", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("-550", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast('Long Jump activated')
end

function smp()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.clearResults()
gg.searchNumber("3.2;1.09375;1::9", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(200)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast('Small Model Player activated')
end

function bmp()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.clearResults()
gg.searchNumber("3.0828566e-44;88;88;1;1;1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1", gg.TYPE_FLOAT, false)
gg.getResults(50)
gg.editAll("1.28", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast('Big Model Player activated')
end

function nf()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("2D;256D;256D;0.96666663885117;256D", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("0.96666663885117", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(999)
gg.editAll("999.9949", gg.TYPE_FLOAT)
end

function NGNGNGHHH()
gg.clearResults()
gg.setRanges(gg.REGION_C_BSS)
gg.searchNumber("2048D;1F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("0.07", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("No Grass/Trees/House activated")
end

function ngnt()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("0.00390625;1;0.99900001287;2", gg.TYPE_FLOAT, false)
gg.searchNumber("1", gg.TYPE_FLOAT, false)
gg.getResults(30)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast('No Grass/Trees activated')
end

function ngs()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("8.0F;1.20000004768F;0.80000001192F;1.5F;0.80000001192F;1.5F::512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("8.0", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(300)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("4.8883906e21", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("4.8883906e21", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("4.8883906e20", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast('No Grass [Sanhok] activated')
end

function hv()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.clearResults()
gg.searchNumber("220;178;15 ", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("220", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(300)
gg.editAll("1200", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("High View activated")
end

function wwee()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("573.70306396484;0.05499718338;1::50", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("999", gg.TYPE_FLOAT)
gg.toast("Color White activated")
end

function bbee()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("573.70306396484;0.05499718338;1::50", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("-999", gg.TYPE_FLOAT)
gg.toast("Color Black activated")
end

function colorcarc()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("538968080D", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("538968080", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("-999", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Color Car activated")
end

function redchdrhdr()
gg.clearResults()
gg.searchNumber("8,196D;8,192D;8,200D::", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("7", gg.TYPE_DWORD)
gg.toast("Red HDR Body Color activated")
end

function blackland()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("3.75000119209;2;2.00000023842;2.00000047684;2.7506108284;3", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("3", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("888", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast('Black LandScape activated')
end

function cocland()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("3.75000119209;2;2.00000023842;2.00000047684;2.7506108284;3", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("3", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("9999999", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast('Coctail LandScape activated')
end

function greenc()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("32769;768;-2134900730", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("32769", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("32781", gg.TYPE_DWORD)
gg.clearResults()
gg.toast('Green Body Color activated')
end

function blacksky()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.clearResults()
gg.searchNumber('100F;1F;1,008,981,770D:99', gg.TYPE_FLOAT, false, gg.SING_EQUAL, 0, -1)
gg.searchNumber('100', gg.TYPE_FLOAT, false, gg.SING_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll('-999', gg.TYPE_FLOAT)
gg.clearResults()
gg.toast('Black Sky activated')
end

function NR100NR100NR()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber('-2.786982e28;-3.7444097e28;-1.1368837e-13::', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('-3.7444097e28', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll('0', gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber('-2.8111605e28;-3.7444097e28;-1.1144502e28;128.0::', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('-1.1144502e28', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll('0', gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber('-6.1549454e27;1.8638966e-20;-1.1144502e28;0::', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber('-1.1144502e28', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll('0', gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("20,000.0F;750.0F;0.10000000149::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL,0,-1)
gg.searchNumber("0.10000000149", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL,0,-1)
gg.getResults(100)
gg.editAll("0.00050000002", gg.TYPE_FLOAT)
end

function clearsky()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.clearResults()
gg.searchNumber('100F;1F;1,008,981,770D:99', gg.TYPE_FLOAT, false, gg.SING_EQUAL, 0, -1)
gg.searchNumber('100', gg.TYPE_FLOAT, false, gg.SING_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll('99999', gg.TYPE_FLOAT)
gg.clearResults()
gg.toast('Clear Sky activated')
end

function whitesky()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("1.5;0.16513200104", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(5)
gg.editAll("-99", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("White Sky activated")
end

function darksky()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("1.5;0.16513200104", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(5)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Dark Sky activated")
end

function aimbotaye2()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("3.5;1.0;0.5;0.10000000149;200.0::512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("3.5;1.0;0.5;0.10000000149;200.0::512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("999999", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("3.5;1;0.5;200;20::", gg.TYPE_FLOAT)
gg.getResults(200)
gg.editAll("999999999", gg.TYPE_FLOAT)
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("6.0;2.0;1.0::99", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("101", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("3.5;1;0.5;200;20::", gg.TYPE_FLOAT)
gg.getResults(200)
gg.editAll("999999999", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("AimBot")
end

function aoba(aocchipubg)
    gg.clearResults()
    gg.setRanges(hifumi[1]["memory"])
    gg.searchNumber(hifumi[3]["value"], hifumi[3]["type"])
  if gg.getResultCount() == 0 then
    gg.toast(hifumi[2]["name"] .. " is failed to active!")
  else
    gg.refineNumber(hifumi[3]["value"], hifumi[3]["type"])
    gg.refineNumber(hifumi[3]["value"], hifumi[3]["type"])
    gg.refineNumber(hifumi[3]["value"], hifumi[3]["type"])
   if gg.getResultCount() == 0 then
    gg.toast(hifumi[2]["name"] .. " is failed to active!")
   else
    sl = gg.getResults(999999)
    Aoba = gg.getResultCount()
    momijisl = 0
   if Aoba > 999999 then
     Aoba = 999999
   end
   for i = 1, Aoba
   do pdAoba = true for v = 4, #(hifumi)
   do
   if pdAoba == true then 
     pyAoba = {}
     pyAoba[1] = {}
     pyAoba[1].address = sl[i].address + hifumi[v]["offset"]
     pyAoba[1].flags = hifumi[v]["type"]
     Aobapy = gg.getValues(pyAoba)
     pdpd = hifumi[v]["antilogger"] .. ";" .. Aobapy[1].value
     Aobapd = split(pdpd, ";")
     tzAobapd = Aobapd[1]
     pyAobapd = Aobapd[2]
   if tzAobapd == pyAobapd then
     yun = true
     pdAoba = true 
   else 
     yun = false
     pdAoba = false
   end 
  end
 end
   if yun == true then
     Aobapy = sl[i].address rin(Aobapy, aocchi)
     nene = true
   end
  end
   if nene == true then 
      gg.toast(hifumi[2]["name"] .. " ACTIVATED\nDATA SET NUMBER #" .. momijisl .. " SUCCESSFUL")
   else
      gg.toast(hifumi[2]["name"] .. " is failed to active!")
   end
  end
 end
end

function ScopeAimHack()
gg.clearResults()
SHM = gg.multiChoice({  
  '— Low Sit Scope —',
  '— Sit Scope Right —',
  '— Sit Scope Left —',
  '— Sit Scope Multi —',
  '— Stand Scope Front —',
  '— Stand Scope Right —',
  '— Stand Scope Left —',
  '— Stand Scope Multi —',
  '— Down Prone Scope —',
  '— Off Menu —',
  '🔶 BACK'},
nil,'📁 ScopeAimHack Menu') 
if SHM == nil then else 
if SHM[1] == true then XNotSitLowX() end 
if SHM[2] == true then XNotSitRightX() end 
if SHM[3] == true then XNotSitLeftX() end 
if SHM[4] == true then XNotSitMultiX() end 
if SHM[5] == true then XNotStandFrontX() end 
if SHM[6] == true then XNotStandRightX() end 
if SHM[7] == true then XNotStandLeftX() end 
if SHM[8] == true then XNotStandMultiX() end 
if SHM[9] == true then XNotProneDownX() end 
if SHM[10] == true then ScopeAimHackOff() end 
if SHM[11] == true then weapons() end  
end 
end
function XNotSitLowX()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('-4767057191653227520', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber('-4767057191653227520', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber('-4767057191653227520', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll('-4767057191527907328', gg.TYPE_QWORD)
gg.clearResults()
end
function XNotSitRightX()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('4548109841269983040', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber('4548109841269983040', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber('4548109841269983040', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll('4548109841324179456', gg.TYPE_QWORD)
gg.clearResults()
end
function XNotSitLeftX()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('4548109841269983040', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber('4548109841269983040', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber('4548109841269983040', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll('4548109839176695808', gg.TYPE_QWORD)
gg.clearResults()
end
function XNotSitMultiX()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('-4586063823029802968', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber('-4586063823029802968', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber('-4586063823029802968', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll('-4586063820806029312', gg.TYPE_QWORD)
gg.clearResults()
end
function XNotStandFrontX()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('4138667321167981973', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber('4138667321167981973', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber('4138667321167981973', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll('4848124999984742400', gg.TYPE_QWORD)
gg.clearResults()
end
function XNotStandRightX()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('4548109952939150800', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber('4548109952939150800', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber('4548109952939150800', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll('4548109952993329152', gg.TYPE_QWORD)
gg.clearResults()
end
function XNotStandLeftX()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('4548109952939150800', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber('4548109952939150800', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber('4548109952939150800', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll('4548109950845845504', gg.TYPE_QWORD)
gg.clearResults()
end
function XNotStandMultiX()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('-5368290752739409920', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber('-5368290752739409920', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber('-5368290752739409920', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll('-5368290754691727360', gg.TYPE_QWORD)
gg.clearResults()
end
function XNotProneDownX()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('4304066855334325713', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber('4304066855334325713', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber('4304066855334325713', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll('4304066855360921600', gg.TYPE_QWORD)
gg.clearResults()
end
function ScopeAimHackOff()
gg.clearResults()
SHM = gg.multiChoice({  
  '— 📴Low Sit Scope —',
  '— 📴Sit Scope Right —',
  '— 📴Sit Scope Left —',
  '— 📴Sit Scope Multi —',
  '— 📴Stand Scope Front —',
  '— 📴Stand Scope Right —',
  '— 📴Stand Scope Left —',
  '— 📴Stand Scope Multi —',
  '— 📴Down Prone Scope —',
  '🔶 BACK'},
nil,'📁 ScopeAimHack Off Menu') 
if SHM == nil then else
if SHM[1] == true then XOffSitLowX() end 
if SHM[2] == true then XOffSitRightX() end 
if SHM[3] == true then XOffSitLeftX() end 
if SHM[4] == true then XOffSitMultiX() end 
if SHM[5] == true then XOffStandFrontX() end 
if SHM[6] == true then XOffStandRightX() end 
if SHM[7] == true then XOffStandLeftX() end 
if SHM[8] == true then XOffStandMultiX() end 
if SHM[9] == true then XOffProneDownX() end 
if SHM[10] == true then ScopeAimHack() end   
end 
end
function XOffSitLowX()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('-4767057191527907328', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber('-4767057191527907328', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber('-4767057191527907328', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll('-4767057191653227520', gg.TYPE_QWORD)
gg.clearResults()
end
function XOffSitRightX()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('4548109841324179456', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber('4548109841324179456', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber('4548109841324179456', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll('4548109841269983040', gg.TYPE_QWORD)
gg.clearResults()
end
function XOffSitLeftX()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('4548109839176695808', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber('4548109839176695808', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber('4548109839176695808', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll('4548109841269983040', gg.TYPE_QWORD)
gg.clearResults()
end
function XOffSitMultiX()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('-4586063820806029312', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber('-4586063820806029312', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber('-4586063820806029312', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll('-4586063823029802968', gg.TYPE_QWORD)
gg.clearResults()
end
function XOffStandFrontX()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('4848124999984742400', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber('4848124999984742400', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber('4848124999984742400', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll('4138667321167981973', gg.TYPE_QWORD)
gg.clearResults()
end
function XOffStandRightX()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('4548109952993329152', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber('4548109952993329152', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber('4548109952993329152', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll('4548109952939150800', gg.TYPE_QWORD)
gg.clearResults()
end
function XOffStandLeftX()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('4548109950845845504', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber('4548109950845845504', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber('4548109950845845504', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll('4548109952939150800', gg.TYPE_QWORD)
gg.clearResults()
end
function XOffStandMultiX()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('-5368290754691727360', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber('-5368290754691727360', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber('-5368290754691727360', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll('-5368290752739409920', gg.TYPE_QWORD)
gg.clearResults()
end
function XOffProneDownX()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber('4304066855360921600', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber('4304066855360921600', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.sleep(140)
gg.refineNumber('4304066855360921600', gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1401)
gg.editAll('4304066855334325713', gg.TYPE_QWORD)
gg.clearResults()
end
function SPEEDALLCAR1()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0.76000005007;0.96078431606;1;0.74509805441::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.74509805441", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(9999)
gg.editAll("100", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("50;5;0.01", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.01", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(280)
gg.editAll("-0.23", gg.TYPE_FLOAT)
gg.toast("Speed All Cars activate")
end

function skycolormenupro()
PDQ = gg.multiChoice({'— Clear Sky —','— White Sky —','— Black Sky —','🔙 BACK'},nil,'MENU')
if PDQ == nil then else
if PDQ[1] == true then clearsky() end 
if PDQ[2] == true then whitesky() end 
if PDQ[3] == true then blackskyall()end
if PDQ[4] == true then wallhackcolorsX() end
end
end

function exit()
gg.setVisible(true)
print('If you found bugs in script - please contact PLAYDF25 in Telegram!\nLinks:\n@PLAYDF25 - Main Developer & Support')
os.exit()
end

pass()
startscript()

while true do
 if gg.isVisible(true) then
   HOMEDM = 1
   gg.setVisible(false)
 end
 if HOMEDM == 1 then
   HOME()
 end
end

