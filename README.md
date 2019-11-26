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
if gg.VERSION > '87.4' then
gg.alert('⚠️ Please Update\nGameGuardian PMC Mod!\n________________________\nOfficial telegram group:\nhttps://t.me/PUBG_MOBILE_CHEAT\nCreator: https://t.me/PLAYDF25', '🔴 EXIT ⛔')
print('⚠️ Please Update\nGameGuardian PMC Mod!\n________________________\nOfficial telegram group:\nhttps://t.me/PUBG_MOBILE_CHEAT\nCreator: https://t.me/PLAYDF25')
os.exit()
end
if gg.VERSION < '87.4' then
gg.alert('⚠️ Please Update\nGameGuardian PMC Mod!\n________________________\nOfficial telegram group:\nhttps://t.me/PUBG_MOBILE_CHEAT\nCreator: https://t.me/PLAYDF25', '🔴 EXIT ⛔')
print('⚠️ Please Update\nGameGuardian PMC Mod!\n________________________\nOfficial telegram group:\nhttps://t.me/PUBG_MOBILE_CHEAT\nCreator: https://t.me/PLAYDF25')
os.exit()
end

function startscript()
gg.setVisible(false)
BP = gg.alert('     ══════| PMC  VIP |══════\n     ══════|   4.8/0.2   |══════',
'🔅Start🔅',
'✴️List changes✴️') 
if BP == 1 then HOME() end
if BP == 2 then LISTC() end
end

function LISTC()
BG = gg.alert('---- PMC VIP V4.8 PATCH 0.2\n    0.2: Adaptation to the new GG, minor bug fixes, added [OFF] Speedhack No Lag, Ultra Rapid Fire, Lift Scope Long Hand.\n    0.1: Cleaning of irrelevant functions, updated 5 functions in the Weapons section, added Small Crosshair, added Bullet Mode v2, added HeadShot Menu, added new No Recoil All Weapons, added new Antenna, Added new Speedhacks, and minor fixes.\n\nOfficial telegram group:\nhttps://t.me/PUBG_MOBILE_CHEAT\nCreator: https://t.me/PLAYDF25', 'OK') 
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
   '🔴 EXIT ⛔'
},nil, '                        ⚡PMC VIP 4.8 PT 0.2⚡\n               📱PUBG MOBILE: 0.15.5📱\n     🔧 MADE BY PLAYDF25')
if HM == 1 then UNIVERSALFFF101() end
if HM == 2 then HYYP0() end
if HM == 3 then wallhackcolorsX() end
if HM == 4 then weapons() end
if HM == 5 then player() end
if HM == 6 then vegetation() end
if HM == 7 then exit() end
HOMEDM=-1
end

function HYYP0()
GK = gg.multiChoice({
  '[EveryGame]\nGame - 📦(zoom+antishake)\n',
  '[EveryGame]\nGame - 🌿(nograsserangel+nograssallmaps)\n',
  '[EveryGame]\nGame - 🕳️(liftshacks+highjump+rapfire)\n',
  '[Once]\nLobby -📍(antenna+bullet)\n',
  '[Once]\nTraining/Game\n845-855 - 🎭(wh+colors+norec)\n',
  '[Once]\nTraining/Game\n435-835 - 🎭(wh+color+norec)\n',
  '[Once]\nTraining/Game\n400-425 - 🎭(wh+color+norec)\n',
  '🔶 BACK'
},nil, '               ☢️ Universal Menu ☣️\n           🔧 MADE BY PLAYDF25')
if GK == nil then else
if GK[1] == true then IWJDJBDJDK() end
if GK[2] == true then nograssall() end
if GK[3] == true then IWJSJSJSJSJ() end
if GK[4] == true then WHEIEIRRJDD() end
if GK[5] == true then QYRNDJRKDO() end
if GK[6] == true then YYYYRNDJRKDP() end
if GK[7] == true then PFBSUSRNDJRKDP() end
if GK[8] == true then HOME() end
end
end

function IWJDJBDJDK()
zoom15xonon()
antishakeee()
end
function nograssall()
NGE()
njddj877()
end
function QYRNDJRKDO()
whV4()
greencolorV1()
BRED()
norec9273()
end
function YYYYRNDJRKDP()
whV2()
redcolorV2V3()
norec9273()
end
function WHEIEIRRJDD()
aaath5()
bulletmodev5()
end
function IWJSJSJSJSJ()
sptronghighjump()
LYINGKKK1()
LYINGKKK0()
fw()
end
function PFBSUSRNDJRKDP()
whV1() 
redcolorV1() 
norec9273()
end
function UUUUU99887UUUUU()
whV1() 
whV2() 
whV4() 
end

function UNIVERSALFFF101()
gg.setVisible(false)
BP = gg.alert('Functions: Bullet Mode, Anti Shake, Rapid Fire, Zoom X15, No Recoil All Weapon, No Grass Erangel, No Grass All Maps, Aimbot, ESP Mode, More Damage\n___________________________________\nActivate the most versatile features?\n            (activate only in game)', '💠Activate💠', '🔶Back🔶') 
if BP == 1 then universalFOC() end
if BP == 2 then HOME() end
end
function universalFOC()
bulletmodev5()
norec9273()
antishakeee()
aimbotaye2()
zoom15xonon()
fw()
NGE()
njddj877()
aaath5()
moremdamagex()
esp0320()
end

function wallhackcolorsX()
W = gg.choice({
'📚 COLORS MENU',
'🔲~Universal SnapWallhack~🔳',
'🗂️ [855 SnapDragon]',
'🗂️ [845 SnapDragon]',
'🗂️ [835 SnapDragon]',
'🗂️ [820 SnapDragon]',
'🗂️ [800 SnapDragon]',
'🗂️ [710 SnapDragon]',
'🗂️ [675 SnapDragon]',
'🗂️ [660 SnapDragon]',
'🗂️ [653 SnapDragon]',
'🗂️ [636 SnapDragon]',
'🗂️ [626 SnapDragon]',
'🗂️ [625 SnapDragon]',
'🗂️ [615 SnapDragon]',
'🗂️ [450 SnapDragon]',
'🗂️ [435 SnapDragon]',
'🗂️ [425 SnapDragon]',
'🗂️ [410 SnapDragon]',
'🗂️ [400 SnapDragon]',
'🗂️ [Other Chipset Wallhacks]',
'🗂️ [Other Chipset Colors]',
'🔶 BACK'
},nil,'📁 WALLHACK/COLORS\n\n🔅(GAME/TRAINING ROOM)')
if W == 1 then OTHERCOLORSMENU() end
if W == 2 then UUUUU99887UUUUU() end
if W == 3 then KSNDMENU() end
if W == 4 then MENUAAAB() end
if W == 5 then GQMENU() end
if W == 6 then GWMENU() end
if W == 7 then GEMENU() end
if W == 8 then GRMENU() end
if W == 9 then wh675() end
if W == 10 then DMENU() end
if W == 11 then EMENU() end
if W == 12 then GTMENU() end
if W == 13 then GYMENU() end
if W == 14 then HMENU() end
if W == 15 then GUMENU() end
if W == 16 then GIMENU() end
if W == 17 then GOMENU() end
if W == 18 then LMENU() end
if W == 19 then GPMENU() end
if W == 20 then GAMENU() end
if W == 21 then OTHERWH() end
if W == 22 then OTHERCLR() end
if W == 23 then HOME() end
HOMEDM=-1
end

function weapons()
WPS = gg.multiChoice({
'🔫 No Recoil All Weapons\n             🔅(lobby)',
'🔫 Less Recoil All Weapons\n             🔅(lobby)',
'🔫 Aimlock (third person only)\n             🔅(lobby)',
'🔫 Bullet Mode v1\n             🔅(lobby)',
'🔫 Bullet Mode v2\n             🔅(lobby)',
'🔫 Headshot Menu\n             🔅(lobby)',
'🔫 No Recoil One Weapon\n             🔆(game)',
'🔫 No Recoil All Weapons v2\n             🔆(game)',
'🔫 Aimbot (third person only)\n             🔆(game)',
'🔫 Small CrossHair\n             🔆(game)',
'🔫 Anti Shake\n             🔆(game)',
'🔫 Rapid Fire\n             🔆(game)',
'🔫 Ultra Rapid Fire\n             🔆(game)',
'🔫 More Damage\n             🔆(game)',
'🔫 Quick Shot\n             🔆(game)',
'🔫 AWM, Kar98 No Recharge\n             🔆(game)',
'🔫 ESP Mode\n             🔆(game)',
'🔫 Lift Sit Down Aim\n             🔆(game)',
'🔫 Lift Stand Aim\n             🔆(game)',
'🔫 Lift Lying Down Aim\n             🔆(game)',
'🔫 Lift Scope Long Hand\n             🔆(game)',
'🔫 Zoom 4X\n— collimator, holographic\n             🔆(game)',
'🔫 Zoom 6X\n— collimator, holographic\n             🔆(game)',
'🔫 Zoom 8X\n— collimator, holographic\n             🔆(game)',
'🔫 Zoom 15X\n— collimator, holographic\n             🔆(game)',
'🔶 BACK'
},nil,'📁 🔫 WEAPONS')
if WPS == nil then else
if WPS[1] == true then norec9273() end
if WPS[2] == true then norecoil3all4() end
if WPS[3] == true then aimv29() end
if WPS[4] == true then bulletmodev5() end
if WPS[5] == true then bulletmodev6() end
if WPS[6] == true then hsmenupro() end
if WPS[7] == true then norecoil1one() end 
if WPS[8] == true then nor() end
if WPS[9] == true then aimbotaye2() end
if WPS[10] == true then SmallCrossHair() end
if WPS[11] == true then antishakeee() end
if WPS[12] == true then fw() end
if WPS[13] == true then kdjd8383() end
if WPS[14] == true then moremdamagex() end
if WPS[15] == true then qs() end 
if WPS[16] == true then AWecharge() end
if WPS[17] == true then esp0320() end
if WPS[18] == true then LYINGKKK1() end
if WPS[19] == true then LYINGKKK2() end
if WPS[20] == true then LYINGKKK0() end
if WPS[21] == true then dxjdj383() end
if WPS[22] == true then zoom4xonon() end
if WPS[23] == true then zoom6xonon() end
if WPS[24] == true then zoom8xonon() end
if WPS[25] == true then zoom15xonon() end
if WPS[26] == true then HOME() end
end
end

function player()
PY = gg.multiChoice({
'🗼 Antenna Always v1\n             🔅(lobby)', 
'🗼 Antenna Always v2\n             🔅(lobby)', 
'🏃 SpeedHack Menu\n             🔆(game)', 
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
'✈️ Fast Parachute\n             🔆(spawn)',
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
if PY[1] == true then aaath5() end
if PY[2] == true then antennav2() end
if PY[3] == true then SPEEDHACKMENUP() end  
if PY[4] == true then antennacor99() end
if PY[5] == true then antennaback99() end 
if PY[6] == true then jtw() end
if PY[7] == true then mj() end
if PY[8] == true then doublejumpnodamage() end
if PY[9] == true then lj() end
if PY[10] == true then sptronghighjump() end
if PY[11] == true then longh44() end
if PY[12] == true then SPEEDMANY1() end
if PY[13] == true then fastjeepuuu() end
if PY[14] == true then SPEEDALLCAR1() end
if PY[15] == true then underwaterjeepx() end
if PY[16] == true then flycarx() end
if PY[17] == true then FFPP1() end
if PY[18] == true then hv() end
if PY[19] == true then IPADWWW() end
if PY[20] == true then IPADWWWW() end
if PY[21] == true then GODWWWWW() end
if PY[22] == true then nf() end
if PY[23] == true then bmp() end
if PY[24] == true then smp() end
if PY[25] == true then Qweaponc() end
if PY[26] == true then throughbuggy() end
if PY[27] == true then LargerH() end
if PY[28] == true then HOME() end
end
end

function vegetation()
MN5 = gg.multiChoice({
"🌱 No Fog All Maps\n             🔆(game)",
"🌱 No Grass All Maps\n             🔆(game)",
"🌱 No Grass Erangel\n             🔅(lobby)",
"🌱 No Grass Erangel\n             🔆(game)",
"🌱 No Grass Sanhok\n             🔆(game)",
"🌱 No Grass/Trees\n             🔆(game)",
"🌱 No Grass/Trees Far\n             🔆(game)",
"🌱 No Grass/Trees/House\n             🔆(game)",
"🔶 BACK",
	  }, nil, "📁 🌿 VEGETATION")
  if MN5 == nil then
  else
  if MN5[1] == true then AntiFog() end
  if MN5[2] == true then njddj877() end
  if MN5[3] == true then NGEL() end
  if MN5[4] == true then NGE() end
  if MN5[5] == true then NGSH() end
  if MN5[6] == true then NGTV2() end
  if MN5[7] == true then NGT() end
  if MN5[8] == true then NGTH() end
  if MN5[9] == true then HOME() end
  end
end

function OTHERCOLORSMENU()
C = gg.choice({
'♎ Green Body Color',
'♈ Red Body Color',
'♒ Red/RedHDR Body Color',
'♌ Yellow Body Color',
'♐ Blue Body Color',
'♏ Blue & Green Body Color',
'⚪ White Body Color',
'⚪ White Body Color v2',
'⚫ Black Body Color',
'⚫ Black Sky All Map',
'⚪ White Sky',
'🔵 Clear Sky',
'⚫ Dark Sky',
'⚫ Black LandScape',
'♓ Coctail LandScape',
'⏹️ Color Car',
'💎 Color Rainbow Mix',
'💷 Body Purple Color',
'🧼 Color Pink',
'🛑 Color Red v3',
'🔙 BACK'
},nil,'📁 🎨 COLORS')
if C == 1 then greenc() end
if C == 2 then redc() end
if C == 3 then BRED() end 
if C == 4 then CLRYELLOW() end
if C == 5 then CLRBLUE() end
if C == 6 then blgrc() end
if C == 7 then CLRDWHITE1() end
if C == 8 then CLRWHITE2() end
if C == 9 then bbee() end
if C == 10 then blackskyall() end
if C == 11 then whitesky() end
if C == 12 then clearsky() end
if C == 13 then darksky() end
if C == 14 then blackland() end
if C == 15 then cocland() end
if C == 16 then colorcarc() end
if C == 17 then CLRRAINBOW() end
if C == 18 then CLRPURPLE() end
if C == 19 then PINKBETA() end
if C == 20 then CLRRED3() end
if C == 21 then wallhackcolorsX() end
HOMEDM=-1
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
gg.getResults(999)
gg.editAll("9999", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("AimLock")
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

function KSNDMENU()
PDQ = gg.multiChoice({'— Wallhack 855 —','— Color Red 855 —','— Color Blue 855 —','— Color Green 855 —','— Yellow Player/Red Transport 855 —','— White Player/Red Transport 855 —','— Fix Blink 855 —','📚 MORE COLORS','🔙 BACK'},nil,'MENU')
if PDQ == nil then else
if PDQ[1] == true then whV4() end
if PDQ[2] == true then BRED() end
if PDQ[3] == true then bluecolorV1() end
if PDQ[4] == true then greencolorV1() end
if PDQ[5] == true then YPRT() end
if PDQ[6] == true then WPRT() end
if PDQ[7] == true then fixBlink2() end
if PDQ[8] == true then OTHERCOLORSMENU() end
if PDQ[9] == true then wallhackcolorsX() end
end
end

function YPRT()
greencolorV1()
BRED()
end

function WPRT()
bluecolorV1()
BRED()
end

function whV4()
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
gg.toast("WallHack 855")
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

function wallhack8552019()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("5.0728552e21;1.6588347e-39;4.7223665e21;-9.1863522e-41", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("-9.1863522e-41", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(200)
gg.editAll("5444", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("4.9990705e21;1.4693806e-39;5.0544113e21;-3.4039558e-39", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("-3.4039558e-39", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(200)
gg.editAll("5444", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("5.0913042e21;1.2857096e-39;4.9068373e21;-3.5876267e-39", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("-3.5876267e-39", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(200)
gg.editAll("5444", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("5.0359611e21;9.7631267e-41;4.943728e21;-2.5223372e-44", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("-2.5223372e-44", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(200)
gg.editAll("5444", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("6.1243354e21;1.3775394e-39;5.6447206e21;-1.016216e-39", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("-1.016216e-39", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(200)
gg.editAll("5444", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("4.9252807e21;9.7631267e-41;4.9068345e21;-1.6815582e-44", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("-1.6815582e-44", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(200)
gg.editAll("5444", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("6.1243269e21;1.3775394e-39;5.6447121e21;-8.3254505e-40", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("-8.3254505e-40", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(200)
gg.editAll("5444", gg.TYPE_FLOAT)
gg.toast("Wallhack HDR 855 activated")
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

function color8552019()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("1,081,081,861;7;-2,146,435,049;8200::", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(2)
gg.editAll("27", gg.TYPE_DWORD)
gg.toast("Color hdr 855 activated")
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
gg.toast("Less Recoil")
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
gg.searchNumber("100F;1F;1,008,981,770D:99", gg.TYPE_FLOAT, false, nil, 0, -1)
gg.searchNumber("100", gg.TYPE_FLOAT, false, nil, 0, -1)
gg.getResults(100)
gg.editAll("-9999", gg.TYPE_FLOAT)
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
AJ = gg.choice({
   "— HeadShot 50% —",
   "— HeadShot 60% —",
   "— HeadShot 70% —",
   "— HeadShot 80% —",
   "— HeadShot 90% —",
   "— HeadShot 100% —",
   "🔶 BACK"
},nil,"📁 HeadShot Menu")
if AJ == 1 then hs50() end
if AJ == 2 then hs60() end
if AJ == 3 then hs70() end
if AJ == 4 then hs80() end
if AJ == 5 then hs90() end
if AJ == 6 then hs100() end
if AJ == 7 then weapons() end
end

function hs100()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("9.20161819458;23;25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("450", gg.TYPE_FLOAT)
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
gg.refineNumber("25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("200", gg.TYPE_FLOAT)
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
if FD[1] == true then M416D() end
if FD[2] == true then SCARD() end
if FD[3] == true then M16A4D() end
if FD[4] == true then AKMD() end
if FD[5] == true then KARD() end
if FD[6] == true then AWMD() end
if FD[7] == true then SKSD() end
if FD[8] == true then MINID() end
if FD[9] == true then M249D() end
if FD[10] == true then DP28D() end
if FD[11] == true then FD1() end
if FD[12] == true then FD2() end
if FD[13] == true then FD3() end
if FD[14] == true then FD4() end
if FD[15] == true then FD5() end
if FD[16] == true then FD6() end
if FD[17] == true then FD7() end
if FD[18] == true then FD8() end
if FD[19] == true then FD9() end
if FD[20] == true then FD10() end
if FD[21] == true then SPEEDHACKMENUP() end
end
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
SHG = gg.multiChoice({
'— Fix No Damage Menu —',
'[ON]\n— No Lag SpeedHack Player —',
'[OFF]\n— No Lag SpeedHack Player —',
'[ON]\n— SpeedHack Game v1 —',
'[OFF]\n— SpeedHack Game v1 —',
'[ON]\n— SpeedHack Game v2 —',
'[OFF]\n— SpeedHack Game v2 —',
'Micro Speedhack',
'🔶 BACK'
},nil,'📁 SpeedHack Menu')
if SHG == nil then else
if SHG[1] == true then FIXDAMAGED() end
if SHG[2] == true then speedh15on() end 
if SHG[3] == true then speedh15off() end 
if SHG[4] == true then SLIGHT() end
if SHG[5] == true then SLIGHTF() end 
if SHG[6] == true then GameSLIGHT() end
if SHG[7] == true then GameSLIGHTF() end
if SHG[8] == true then speedhacklitex() end
if SHG[9] == true then player() end
end
end

function speedh15on()
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-1,296,744,149,883,614,555", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(99)
gg.editAll(" -1,296,744,153,870,237,696", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber('-1,904,987,454,010,553,855', gg.TYPE_QWORD,false, gg.SIGN_EQUAL,0,-1)
gg.getResults(99)
gg.editAll('-1,904,987,454,002,165,247', gg.TYPE_QWORD)
gg.clearResults()
gg.toast("ON")
end
       
function speedh15off()
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-1,904,987,454,002,165,247", gg.TYPE_QWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(99)
gg.editAll("-1,904,987,454,010,553,855", gg.TYPE_QWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber('-1,296,744,153,870,237,696', gg.TYPE_QWORD,false, gg.SIGN_EQUAL,0,-1)
gg.getResults(99)
gg.editAll('-1,296,744,149,883,614,555', gg.TYPE_QWORD)
gg.clearResults()
gg.toast("OFF")
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

function whitec()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("8200;96", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("21", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("White Body Color activated")
end

function blgrc()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("8200;96", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("8202", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Blue/Green Body Color activated")
end

function bluec()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("8200;96", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("8201", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Blue Body Color activated")
end

function yellowc()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("8200;96", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("8198", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Yellow Body Color activated")
end

function redc()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("8200;96", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("8199", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Red Body Color activated")
end

function GQMENU()
SPP = gg.multiChoice({
'— Wallhack 835 —',
'— Color Red 835 —',
'— Color Yellow 835 —',
'— Fix Blink 835 —',
'📚 MORE COLORS',
'🔙 BACK'
},nil,'MENU')
if SPP== nil then else
if SPP[1] == true then whV2() end
if SPP[2] == true then redcolorV2V3() end
if SPP[3] == true then yellowcolorV2V3() end
if SPP[4] == true then fixBlink() end
if SPP[5] == true then OTHERCOLORSMENU() end
if SPP[6] == true then wallhackcolorsX() end
end
end

function GWMENU()
SPP = gg.multiChoice({
'— Wallhack 820 —',
'— Color Red 820 —',
'— Color Yellow 820 —',
'— Fix Blink 820 —',
'📚 MORE COLORS',
'🔙 BACK'
},nil,'MENU')
if SPP== nil then else
if SPP[1] == true then whV2() end
if SPP[2] == true then redcolorV2V3() end
if SPP[3] == true then yellowcolorV2V3() end
if SPP[4] == true then fixBlink() end
if SPP[5] == true then OTHERCOLORSMENU() end
if SPP[6] == true then wallhackcolorsX() end
end
end

function GEMENU()
SPP = gg.multiChoice({
'— Wallhack 800 —',
'— Color Red 800 —',
'— Color Yellow 800 —',
'— Fix Blink 800 —',
'📚 MORE COLORS',
'🔙 BACK'
},nil,'MENU')
if SPP == nil then else
if SPP[1] == true then whV2() end
if SPP[2] == true then redcolorV2V3() end
if SPP[3] == true then yellowcolorV2V3() end
if SPP[4] == true then fixBlink() end
if SPP[5] == true then OTHERCOLORSMENU() end
if SPP[6] == true then wallhackcolorsX() end
end
end

function GRMENU()
SPP = gg.multiChoice({
'— Wallhack 710 —',
'— Color Red 710 —',
'— Color Yellow 710 —',
'— Fix Blink 710 —',
'📚 MORE COLORS',
'🔙 BACK'
},nil,'MENU')
if SPP == nil then else
if SPP[1] == true then whV2() end
if SPP[2] == true then redcolorV2V3() end
if SPP[3] == true then yellowcolorV2V3() end
if SPP[4] == true then fixBlink() end
if SPP[5] == true then OTHERCOLORSMENU() end
if SPP[6] == true then wallhackcolorsX() end
end
end

function GTMENU()
SPP = gg.multiChoice({
'— Wallhack 636 —',
'— Color Red 636 —',
'— Color Yellow 636 —',
'— Color Green 636 —',
'— Color Blue & Green 636 —',
'— Fix Blink 636 —',
'📚 MORE COLORS',
'🔙 BACK'
},nil,'MENU')
if SPP == nil then else
if SPP[1] == true then whV2() end
if SPP[2] == true then redcolorV2V3() end
if SPP[3] == true then yellowcolorV2V3() end
if SPP[4] == true then greenc() end
if SPP[5] == true then blgrc() end
if SPP[6] == true then fixBlink() end
if SPP[7] == true then OTHERCOLORSMENU() end
if SPP[8] == true then wallhackcolorsX() end
end
end

function GYMENU()
SPP = gg.multiChoice({
'— Wallhack 626 —',
'— Color Red 626—',
'— Color Yellow 626 —',
'— Fix Blink 626 —',
'📚 MORE COLORS',
'🔙 BACK'
},nil,'MENU')
if SPP == nil then else
if SPP[1] == true then whV2() end
if SPP[2] == true then redcolorV2V3() end
if SPP[3] == true then yellowcolorV2V3() end
if SPP[4] == true then fixBlink() end
if SPP[5] == true then OTHERCOLORSMENU() end
if SPP[6] == true then wallhackcolorsX() end
end
end

function GUMENU()
SPP = gg.multiChoice({
'— Wallhack 615 —',
'— Color Red 615—',
'— Color Yellow 615 —',
'— Color Green 615 —',
'— Color Blue 615 —',
'— Fix Blink 615 —',
'📚 MORE COLORS',
'🔙 BACK'
},nil,'MENU')
if SPP == nil then else
if SPP[1] == true then whV2() end
if SPP[2] == true then redcolorV2V3() end
if SPP[3] == true then yellowcolorV2V3() end
if SPP[4] == true then Owdnfjdi() end
if SPP[5] == true then bfuaksjd() end
if SPP[6] == true then fixBlink() end
if SPP[7] == true then OTHERCOLORSMENU() end
if SPP[8] == true then wallhackcolorsX() end
end
end

function Owdnfjdi()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("8,201;8,202;538,968,081:29", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("8202", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("8", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Color 615 Green activated")
end

function qdodjddj()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("8.201D;8.202D;538.968.081D:29")
gg.searchNumber("8201;8202;538968081")
gg.getResults(5)
gg.editAll("8", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Color 615 Yellow activated")
end

function bfuaksjd()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("1D;2D;91D:25", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1;2;91", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(5)
gg.editAll("5", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Color 615 Blue activated")
end

function GIMENU()
SPP = gg.multiChoice({
'— Wallhack 450 —',
'— Color Red 450 —',
'— Color Yellow 450 —',
'— Fix Blink 450 —',
'📚 MORE COLORS',
'🔙 BACK'
},nil,'MENU')
if SPP == nil then else
if SPP[1] == true then whV2() end
if SPP[2] == true then redcolorV2V3() end
if SPP[3] == true then yellowcolorV2V3() end
if SPP[4] == true then fixBlink() end
if SPP[5] == true then OTHERCOLORSMENU() end
if SPP[6] == true then wallhackcolorsX() end
end
end

function GOMENU()
SPP = gg.multiChoice({
'— Wallhack 435 —',
'— Color Red 435 —',
'— Color Yellow 435 —',
'— Fix Blink 435 —',
'📚 MORE COLORS',
'🔙 BACK'
},nil,'MENU')
if SPP == nil then else
if SPP[1] == true then whV2() end
if SPP[2] == true then redcolorV2V3() end
if SPP[3] == true then yellowcolorV2V3() end
if SPP[4] == true then fixBlink() end
if SPP[5] == true then OTHERCOLORSMENU() end
if SPP[6] == true then wallhackcolorsX() end
end
end

function GPMENU()
SPP = gg.multiChoice({
'— Wallhack 410 —',
'— Color Red 410 —',
'— Color Yellow 410 —',
'📚 MORE COLORS',
'🔙 BACK'
},nil,'MENU')
if SPP == nil then else
if SPP[1] == true then whV1() end
if SPP[2] == true then redcolorV1() end
if SPP[3] == true then yellowcolorV1() end
if SPP[4] == true then OTHERCOLORSMENU() end
if SPP[5] == true then wallhackcolorsX() end
end
end

function GAMENU()
SPP = gg.multiChoice({
'— Wallhack 400 —',
'— Color Red 400 —',
'— Color Yellow 400 —',
'📚 MORE COLORS',
'🔙 BACK'
},nil,'MENU')
if SPP == nil then else
if SPP[1] == true then whV1() end
if SPP[2] == true then redcolorV1() end
if SPP[3] == true then yellowcolorV1() end
if SPP[4] == true then OTHERCOLORSMENU() end
if SPP[5] == true then wallhackcolorsX() end
end
end

function IWALLHACK()
gg.clearResults()
gg.setRanges(gg.REGION_C_HEAP)
gg.searchNumber("3.3631163e-44;2.0;3.5032462e-44;-1.0;3.643376e-44;3.7835059e-44;-1.0;3.9236357e-44;4.0637655e-44;1.0;-127.0:129", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("3.1809475e-43;3.1949605e-43;2.0;3.2089735e-43:53", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Wallhack 615 activated")
end

function MWALLHACK()
gg.clearResults()
gg.setRanges(gg.REGION_C_HEAP)
gg.searchNumber("3.3631163e-44;2.0;3.5032462e-44;-1.0;3.643376e-44;3.7835059e-44;-1.0;3.9236357e-44;4.0637655e-44;1.0;-127.0:129", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("3.1809475e-43;3.1949605e-43;2.0;3.2089735e-43:53", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Wallhack 410 activated")
end

function LMENU()
BDO = gg.multiChoice({
'— Wallhack 425 —',
'— Color Red 425 —',
'— Color Yellow 425 —',
'— Color Blue 425 —',
'— Color Purple 425 —',
'— Color Green 425 —',
'📚 MORE COLORS',
'🔙 BACK'
},nil,'MENU')
if BDO == nil then else
if BDO[1] == true then whV1() end
if BDO[2] == true then redcolorV1() end
if BDO[3] == true then yellowcolorV1() end
if BDO[4] == true then BBBBBLUE() end
if BDO[5] == true then CCCCPURPLE() end
if BDO[6] == true then gggggooooOO() end
if BDO[7] == true then OTHERCOLORSMENU() end
if BDO[8] == true then wallhackcolorsX() end
end
end

function gggggooooOO()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("790,580;856,128;856,130:17", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("856,128", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("856122", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("856,128;856,130;393,222:25", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("856,128", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("856122", gg.TYPE_DWORD)
gg.clearResults()
gg.searchNumber("196,610;1,280;196,608:25", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("196,608", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(2)
gg.editAll("9999", gg.TYPE_DWORD)
gg.toast("Color 425 Green activated")
end

function uuuuWALLHACK()
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("228;1,073,741,824;1,073,741,824;229;-1,082,130,432:29", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1,073,741,824", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("1,123,024,896", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("3.3631163e-44;2.0;3.5032462e-44;-1.0;3.643376e-44;3.7835059e-44;-1.0;3.9236357e-44;4.0637655e-44;1.0;-127.0:129", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Wallhack 425 activated")
end

function AAAARED()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("856128", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(4)
gg.editAll("856140", gg.TYPE_DWORD)
gg.clearResults()
gg.searchNumber("196610;1280;196608:25", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("196608", gg.TYPE_DWORD, false, nil, 0, -1)
gg.getResults(10)
gg.editAll("9999", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Color Red 425 activated")
end

function CCCCPURPLE()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("790,580;856,128;856,130:17", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("856,128", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("856138", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("856,128;856,130;393,222:25", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("856,128", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("856138", gg.TYPE_DWORD)
gg.clearResults()
gg.searchNumber("196,610;1,280;196,608:25", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("196,608", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(2)
gg.editAll("9999", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Color Purple 425 activated")
end

function BBBBBLUE()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("856128", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(4)
gg.editAll("856130", gg.TYPE_DWORD)
gg.clearResults()
gg.searchNumber("196610;1280;196608:25", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("196608", gg.TYPE_DWORD, false, nil, 0, -1)
gg.getResults(10)
gg.editAll("9999", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Color Blue 425 activated")
end

function DDDDDYELLOW()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("856128", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(4)
gg.editAll("856118", gg.TYPE_DWORD)
gg.clearResults()
gg.searchNumber("196610;1280;196608:25", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("196608", gg.TYPE_DWORD, false, nil, 0, -1)
gg.getResults(10)
gg.editAll("9999", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Yellow 425 activated")
end

function KWALLHACK()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("2;3.7615819e-37;4.814603e21;4.7408149e21", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("2;3.7615819e-37;1.3912552e-19;4.9252829e21", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("2.718519e-43F;3.7615819e-37F;2.0F;-1.0F;1.0F;-127.0F;0.00999999978F::200", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Wallhack 435 activated")
end

function JWALLHACK()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("135,215D;4,140D;3.7615819e-37;2::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("130", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("194D;3.7615819e-37;2;-1;1;-127::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("130", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("1.1202013e-19;1.1202017e-19;2::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("9999", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("2.718519e-43F;3.7615819e-37F;2.0F;0.00999999978F::200", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("150", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("5.8013756e-42F;-5.5695588e-40F;2.0F::100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("150", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("4.7961574e21;3.7615819e-37;2::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("150", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Wallhack 450 activated")
end

function HMENU()
BSK = gg.multiChoice({
'— Wallhack 625 —',
'— Color Red 625 —',
'— Color Yellow 625 —',
'— Color Green 625 —',
'— Fix Blink 625 —',
'📚 MORE COLORS',
'🔙 BACK'
},nil,'MENU')
if BSK == nil then else
if BSK[1] == true then whV2() end
if BSK[2] == true then redcolorV2V3() end
if BSK[3] == true then yellowcolorV2V3() end
if BSK[4] == true then AAAGREEN() end
if BSK[5] == true then fixBlink() end
if BSK[6] == true then OTHERCOLORSMENU() end
if BSK[7] == true then wallhackcolorsX() end
end
end

function iiiiWALLHACK()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("135,215D;4,140D;3.7615819e-37;2::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("130", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("194D;3.7615819e-37;2;-1;1;-127::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("130", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Wallhack 625 activated")
end

function GWALLHACK()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("2.718519e-43F;3.7615819e-37F;2.0F;-1.0F;1.0F;-127.0F;0.00999999978F::200", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("5.8013756e-42F;-5.5695588e-40F;2.0F::100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Wallhack 626 activated")
end

function FWALLHACK()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("2.718519e-43F;3.7615819e-37F;2.0F;-1.0F;1.0F;-127.0F;0.00999999978F::200", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber(2, gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("5.8013756e-42F;-5.5695588e-40F;2.0F::100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber(2, gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Wallhack 636 activated")
end
 
function AAAGREEN()
gg.clearResults()
gg.searchNumber("69,778D;1,669,332,992D;11D", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("11", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("32777", gg.TYPE_DWORD)
gg.toast("Color Green 625 activated")
end

function aimbotaye2()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("3.5;1;200;20::999", gg.TYPE_FLOAT,false, gg.SIGN_EQUAL,0,-1)
gg.refineNumber("3.5;1;200;20", gg.TYPE_FLOAT,false, gg.SIGN_EQUAL,0,-1)
gg.getResults(300)
gg.editAll("1.0e20", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("AimBot")
end

function ooooWALLHACK()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("2.718519e-43F;3.7615819e-37F;2.0F;0.00999999978F::200", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("5.8013756e-42F;-5.5695588e-40F;2.0F::100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Wallhack 653 activated")
end

function EMENU()
QPS = gg.multiChoice({
'— Wallhack 653 —',
'— Color Red 653 —',
'— Color Yellow 653 —',
'— Fix Blink 653 —',
'📚 MORE COLORS',
'🔙 BACK'
},nil,'MENU')
if QPS == nil then else
if QPS[1] == true then whV2() end
if QPS[2] == true then redcolorV2V3() end
if QPS[3] == true then yellowcolorV2V3() end
if QPS[4] == true then fixBlink() end
if QPS[5] == true then OTHERCOLORSMENU() end
if QPS[6] == true then wallhackcolorsX() end
end
end

function DYELLOW()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("8,192D;256D;65,540D;12D;8200D", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("6", gg.TYPE_DWORD)
gg.toast("Color 653 Yellow activated")
end

function DMENU()
BAL = gg.multiChoice({
'— Wallhack 660 —',
'— Color Red 660 —',
'— Color Yellow 660 —',
'— Color Green 660 —',
'— Color White 660 —',
'— Fix Blink 660 —',
'📚 MORE COLORS',
'🔙 BACK'
},nil,'MENU')
if BAL == nil then else
if BAL[1] == true then wh660() end
if BAL[2] == true then red660() end
if BAL[3] == true then yellow660() end
if BAL[4] == true then AAGREEN() end
if BAL[5] == true then whitec() end
if BAL[6] == true then fixBlink() end
if BAL[7] == true then OTHERCOLORSMENU() end
if BAL[8] == true then wallhackcolorsX() end
end
end

function qqqqWALLHACK()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("4,140D;4.7408166e21F;4.7223665e21;0D;0D;0D;0D;0D;0D;-0.0F;2.0F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("120",gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("2.718519e-43;2.0F;-1.0F;1.0F;-127F;0.24022650719F;-0.0", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("120",gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("4,140D;4.7408166e21F;4.7223665e21;0D;0D;0D;0D;0D;0D;-0.0F;2.0F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("120",gg.TYPE_FLOAT)
gg.toast("Iniversal Wallhack activated")
end

function AAGREEN()
gg.clearResults()
gg.searchNumber("69,778D;1,669,332,992D;11D", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("11", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("32777", gg.TYPE_DWORD)
gg.toast("Color 660 Green activated")
end

function BBRED()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("96D;8200;196,615", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("7", gg.TYPE_DWORD)
gg.toast("Color 660 Red activated")
end

function CCYELLOW()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("3,874;201,851,904;16", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("201,851,904", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("683128", gg.TYPE_DWORD)
gg.clearResults()
gg.searchNumber(" 3,846;201,851,904;16", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("201,851,904", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("683128", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Color 660 Yellow activated")
end

function CWALLHACK()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("274,677,779D;2.25000452995;2;1.6623054e-19", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(20)
gg.editAll("130", gg.TYPE_FLOAT)
gg.toast("25%")
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("218D;3.7615819e-37;2;-1;1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("130", gg.TYPE_FLOAT)
gg.toast("50%")
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("95D;2;9.2194229e-41", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(15)
gg.editAll("130", gg.TYPE_FLOAT)
gg.toast("75%")
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("206D;3.7615819e-37;2;-1;1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("130", gg.TYPE_FLOAT)
gg.toast("WallHack 710 activated")
end

function BWALLHACK()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("5.1097599e21;2.0;1.6623071e-19;3.6734297e-39;1.66433e10::17", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("2.0;-1.0;0.0;1.0;-127.0::17", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Wallhack Snap 800 activated")
end

function AWALLHACK()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("135,215D;4,140D;3.7615819e-37;2::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("130", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("194D;3.7615819e-37;2;-1;1;-127::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("130", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Wallhack 820 activated")
end

function MENUAAAB()
SPP = gg.multiChoice({
'— Wallhack 845 —',
'— Color Red 845 —',
'— Color Blue 845 —',
'— Color Green 845 —',
'— Yellow Player/Red Transport 855 —',
'— White Player/Red Transport 855 —',
'— Fix Blink 845 —',
'📚 MORE COLORS',
'🔙 BACK'
},nil,'MENU')
if SPP == nil then else
if SPP[1] == true then whV3() end
if SPP[2] == true then BRED() end
if SPP[3] == true then bluecolorV1() end
if SPP[4] == true then greencolorV1() end  
if SPP[5] == true then YPRT() end
if SPP[6] == true then WPRT() end
if SPP[7] == true then fixBlink2() end
if SPP[8] == true then OTHERCOLORSMENU() end
if SPP[9] == true then wallhackcolorsX() end
end
end

function whV3()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("200", -1, gg.TYPE_FLOAT, gg.SIGN_EQUAL, 0, -1)
gg.getResults(999)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("930", -1, gg.TYPE_FLOAT, gg.SIGN_EQUAL, 0, -1)
gg.getResults(999)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("WallHack 845")
end

function REDMAYEE()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO)
  gg.searchNumber("1,080,035,863;1,080,033,308;8,200;1,661,702,144:41", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(2)
  gg.editAll("8199", gg.TYPE_DWORD)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO)
  gg.searchNumber("1,661,566,999;96;539,246,604;8200::", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("7", gg.TYPE_DWORD)
  gg.toast("Color Red 845 activated!")
  gg.clearResults()
  gg.setVisible(false)
  gg.clearResults()
end

function CGuuuuEN()
gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO)
  gg.searchNumber("1,080,035,863;1,080,033,308;8,200;1,661,702,144:41 ", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(2)
  gg.editAll("3", gg.TYPE_DWORD)
  gg.toast("Color 845 Purple Activated!")
  gg.clearResults()
end

function CGppppEN()
gg.clearResults()
  gg.setRanges(131072)
  gg.searchNumber("8204;256;176;7;8200::", 4, false, 536870912, 0, -1)
  gg.searchNumber("8200", 4, false, 536870912, 0, -1)
  gg.getResults(20)
  gg.editAll("7", 4)
  gg.toast("Color Red 845 HDR Activated!")
  gg.clearResults()
end

function AYELLOW()
gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO)
  gg.searchNumber("1,114,128D;1,661,468,689D;8,200D;1,194,380,054D;41,943,040D", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("6", gg.TYPE_DWORD)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO)
  gg.searchNumber("96D;539,246,604D;8,200D;1,194,380,058D;1,376,273D", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("6", gg.TYPE_DWORD)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO)
  gg.searchNumber(" 1,080,035,863;1,080,033,308;8,200;1,661,702,144:41", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(2)
  gg.editAll("8198", gg.TYPE_DWORD)
  gg.clearResults()
gg.toast("Color Yellow 845 activated")
end

function BRED()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("8,196D;8,192D;8,200D::", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("7", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Color Red activated")
end

function CGREEN()
gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO)
  gg.searchNumber("69,780;147457;69707", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("147457", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(5)
  gg.editAll("9", 4)
  gg.toast("Color 845 Green activated!")
  gg.clearResults()
  gg.setVisible(false)
  gg.clearResults()
end

function whsnapwqqqq()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("95D;2;9.2194229e-41", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(15)
gg.editAll("130", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("206D;3.7615819e-37;2;-1;1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("130", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast('WallHack [SnapDragon 845] activated')
end

function whsnapq()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("135,215D;4,140D;3.7615819e-37;2::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("130", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("194D;3.7615819e-37;2;-1;1;-127::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("130", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast('WallHack [SnapDragon 450] activated')
end

function whall()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("2.718519e-43F;3.7615819e-37F;2.0F;0.00999999978F::200", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("5.8013756e-42F;-5.5695588e-40F;2.0F::100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast('WallHack V1 [All SnapDragon] activated')
end

function whallq()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("135,215D;4,140D;3.7615819e-37;2::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("130", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("194D;3.7615819e-37;2;-1;1;-127::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("130", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast('WalHack V2 [All SnapDragon] activated')
end

function whsnapt()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("2.718519e-43F;3.7615819e-37F;2.0F;-1.0F;1.0F;-127.0F;0.00999999978F::200", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("5.8013756e-42F;-5.5695588e-40F;2.0F::100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("WallHack [SnapDragon 660] activated")
end

function whsnapr()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("2.718519e-43F;3.7615819e-37F;2.0F;-1.0F;1.0F;-127.0F;0.00999999978F::200", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("5.8013756e-42F;-5.5695588e-40F;2.0F::100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("WallHack [SnapDragon 636] activated")
end

function whsnape()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("2.718519e-43F;3.7615819e-37F;2.0F;-1.0F;1.0F;-127.0F;0.00999999978F::200", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("5.8013756e-42F;-5.5695588e-40F;2.0F::100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("WallHack [SnapDragon 625] activated")
end

function whsnapw()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("2.718519e-43F;3.7615819e-37F;2.0F;0.00999999978F::200", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber(2, gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("5.8013756e-42F;-5.5695588e-40F;2.0F::100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber(2, gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("7.1746481e-43;1.0842022e-19;94.015625;7.0776718e-15;2::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(5)
gg.editAll("9999", gg.TYPE_FLOAT)
gg.toast("WallHack [SnapDragon 835] activated")
end

function whsnap()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("2.718519e-43F;3.7615819e-37F;2.0F;-1.0F;1.0F;-127.0F;0.00999999978F::200", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("5.8013756e-42F;-5.5695588e-40F;2.0F::100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast('WallHack [SnapDragon 435] activated')
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

function OTHERWH()
  MN3 = gg.multiChoice({
"✨ Wallhack Mediatek V1 [Manual]",
"✨ Wallhack Mediatek V2 [Manual]",
"✨ Wallhack Mediatek P60",
"✨ Wallhack Exynos 7420",
"✨ Wallhack Exynos 7570",
"✨ Wallhack Exynos 7870 V1",
"✨ Wallhack Exynos 7870 V2",
"✨ Wallhack Exynos 7870 V3 [Game]",
"✨ Wallhack Exynos 7870 V4",
"✨ Wallhack Exynos 7870 V5",
"✨ Wallhack Exynos 7870/8890",
"✨ Wallhack Exynos 7885 V1",
"✨ Wallhack Exynos 7885 V2",
"✨ Wallhack Exynos 8890 V1 [Lobby]",
"✨ Wallhack Exynos 8890 V2",
"✨ Wallhack Exynos 9810",
"✨ Wallhack Kirin 710 V1",
"✨ Wallhack Kirin 710 V2",
"✨ Wallhack Kirin 659",
"✨ Wallhack Kirin 980",
"🔶 BACK"
}, nil, "📁 Other Chipset Wallhack Menu")
  if MN3 == nil then
  else
  if MN3[1] == true then WHMTK() end
  if MN3[2] == true then WHMTKV2() end
  if MN3[3] == true then WHP60() end
  if MN3[4] == true then WHEXY7420() end
  if MN3[5] == true then WHEXY7570() end
  if MN3[6] == true then WHEXY7870V1() end
  if MN3[7] == true then WHEXY7870V2() end
  if MN3[8] == true then WHEXY7870V3() end
  if MN3[9] == true then WHEXY7870V4() end
  if MN3[10] == true then WHEXY7870V5() end
  if MN3[11] == true then WHEXY7870V7() end
  if MN3[12] == true then WHEXY7885() end
  if MN3[13] == true then WHEXY7885V2() end
  if MN3[14] == true then WHEXY8890() end
  if MN3[15] == true then WHEXY8890V2() end
  if MN3[16] == true then WHEXY9810() end
  if MN3[17] == true then WHKRN710V1() end
  if MN3[18] == true then WHKRN710V2() end
  if MN3[19] == true then WHKRN659() end
  if MN3[20] == true then WHKRN980() end
  if MN3[21] == true then wallhackcolorsX() 
end
end
end

  function WHKRN659()
    if w == 1 then
      WHFIX()
    else
      gg.clearList()
      gg.clearResults()
      gg.setRanges(gg.REGION_C_ALLOC)
      gg.searchNumber("4.5917748e-40;9.6272355e-38;3.1389086e-43;0.5:385", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      if gg.getResultCount() == 0 then
        gg.alert("Value Not Found")
      else
        gg.searchNumber("0.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
        _Count = gg.getResultCount()
        _A = gg.getResults(_Count)
        last_Count = _Count + 1
        w = 1
        _T = "Edit Wallhack Value"
        WHFIX()
      end
    end
  end
  function WHFIX()
    if w == 0 then
      gg.alert("Value Not Found")
    else
      gg.setVisible(false)
      _CL = {}
      for _FORV_3_ = 1, _Count do
        _CL[_FORV_3_] = " Value   " .. _FORV_3_ .. ""
      end
      _CL[last_Count] = "⬅️ [Back]"
      _C_ = gg.choice(_CL, nil, "Wallhack Kirin 659")
      for _FORV_3_ = 1, _Count do
        if _C_ == _FORV_3_ then
          for _FORV_7_, _FORV_8_ in ipairs(_A) do
            _A[_FORV_7_].freeze = false
            gg.addListItems(_A)
          end
          _A[_FORV_3_].value = 0
          _A[_FORV_3_].freeze = true
          gg.addListItems(_A)
          _FORV_3_ = _Count
        elseif K_2 == _Count + 1 then
          WA()
        end
      end
    end
    gg.setVisible(true)
  end

  function WHKRN980()
    if w == 1 then
      WHFIX()
    else
      gg.clearList()
      gg.clearResults()
      gg.setRanges(gg.REGION_C_ALLOC)
      gg.searchNumber("0.5;360.0;360.0;752.0;752.0;1.0;1.0;1.0;1.0", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      if gg.getResultCount() == 0 then
        gg.alert("Value Not Found")
      else
        gg.searchNumber("0.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
        _Count = gg.getResultCount()
        _A = gg.getResults(_Count)
        last_Count = _Count + 1
        w = 1
        _T = "Edit Wallhack Value"
        WHFIX()
      end
    end
  end
  function WHFIX()
    if w == 0 then
      gg.alert("Value Not Found")
    else
      gg.setVisible(false)
      _CL = {}
      for _FORV_3_ = 1, _Count do
        _CL[_FORV_3_] = " Value   " .. _FORV_3_ .. ""
      end
      _CL[last_Count] = "⬅️ [Back]"
      _C_ = gg.choice(_CL, nil, "Wallhack Kirin 980")
      for _FORV_3_ = 1, _Count do
        if _C_ == _FORV_3_ then
          for _FORV_7_, _FORV_8_ in ipairs(_A) do
            _A[_FORV_7_].freeze = false
            gg.addListItems(_A)
          end
          _A[_FORV_3_].value = 0
          _A[_FORV_3_].freeze = true
          gg.addListItems(_A)
          _FORV_3_ = _Count
        elseif K_2 == _Count + 1 then
          WA()
        end
      end
    end
    gg.setVisible(true)
  end

function WHEXY7870V6()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("0.5;1.0", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults()
gg.searchNumber("1.0", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults()
gg.searchNumber("0.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults()
gg.searchNumber("9.7007039e-38;1.8367379e-40;4.5917748e-40;9.6272355e-38;3.1389086e-43;1.4012985e-45;2.8025969e-45;0.5:497", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("0.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
revert = gg.getResults(1, nil, nil, nil, nil, nil, nil, nil, nil)
local t = gg.getResults(1, nil, nil, nil, nil, nil, nil, nil, nil)
for i, v in ipairs(t) do
 if v.flags == gg.TYPE_FLOAT then
  v.value = "0"
  v.freeze = true
 end
end
gg.addListItems(t)
t = nil
    gg.toast("Wallhack Exynos 7870/8890 activated")
  end

function WHKRN710V2()
    gg.clearResults()
    gg.setRanges(gg.REGION_C_ALLOC)
    gg.searchNumber("0.0F;0.0F;0.0F;0.5F;360.0F;748.0F;0.0F;0.0F;1.0F;0.0F;0.0F;0.0F;1.0F;1.0F;1.0F;0.0F::137", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.processResume()
    gg.toast(" + 1")
    gg.processResume()
    gg.refineNumber("0.0F;0.5F;360.0F;748.0F;0.0F;0.0F;1.0F;0.0F;0.0F;0.0F;1.0F;1.0F;1.0F;0.0F::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.processResume()
    gg.toast(" +2 ")
    gg.refineNumber("0.0F;0.5F;360.0F::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.processResume()
    gg.toast(" +3")
    gg.refineNumber("0.5F;360.0F::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.toast(" +4 ")
    revert = gg.getResults(100, nil, nil, nil, nil, nil, nil, nil, nil)
local t = gg.getResults(100, nil, nil, nil, nil, nil, nil, nil, nil)
for i, v in ipairs(t) do
	if v.flags == gg.TYPE_FLOAT then
		v.value = '0'
		v.freeze = true
	end
end
gg.addListItems(t)
t = nil
end

function WHKRN710V1()
    gg.clearResults()
    gg.setRanges(gg.REGION_C_ALLOC)
    gg.searchNumber("0.0F;0.0F;3.2229865e-44F;0.0F;0.0F;0.0F;0.0F;-0.0F;0.5F;-360.0F;360.0F;748.0F;-748.0F;0.0F;0.0F;1.0F;1.0F:137", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.processResume()
    gg.toast(" + 1")
    gg.processResume()
    gg.refineNumber("0.0F;-0.0F;0.5F;-360.0F;360.0F;748.0F;-748.0F;0.0F:", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.processResume()
    gg.toast(" +2 ")
    gg.refineNumber("0.0F;-0.0F;0.5F;-360.0F;360.0F:", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.processResume()
    gg.toast(" +3")
    gg.refineNumber("0.5F;-360.0F;360.0F:", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.toast(" +4 ")
    revert = gg.getResults(100, nil, nil, nil, nil, nil, nil, nil, nil)
local t = gg.getResults(100, nil, nil, nil, nil, nil, nil, nil, nil)
for i, v in ipairs(t) do
	if v.flags == gg.TYPE_FLOAT then
		v.value = '2'
		v.freeze = true
	end
end
gg.addListItems(t)
t = nil
    gg.toast("Wallhack Kirin 710 V1 activated")
  end

  function WHEXY7870V5()
    gg.clearResults()
    gg.setRanges(gg.REGION_C_ALLOC)
    gg.searchNumber("0.0F;268.0F;-480.0F;1.0F;1.0F;1.0F;1.0F;0.0F;0.0F;268.0F;480.0F;0.5F;0.5F;0.0F;0.0F;1.0F;1.0F;0.0F;0.0F;1.0F;1.0F;1.0F;1.0F;0.0F;0.0F;0.0F::421", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.processResume()
    gg.toast(" + 1")
    gg.processResume()
    gg.refineNumber("1.0F;0.0F;0.0F;268.0F;480.0F;0.5F;0.5F;0.0F;0.0F;1.0F;1.0F::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.processResume()
    gg.toast(" +2 ")
    gg.refineNumber("268.0F;480.0F;0.5F;0.5F;0.0F::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.processResume()
    gg.toast(" +3")
    gg.refineNumber("0.5F;0.5F::17", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.toast(" +4 ")
    revert = gg.getResults(100, nil, nil, nil, nil, nil, nil, nil, nil)
local t = gg.getResults(100, nil, nil, nil, nil, nil, nil, nil, nil)
for i, v in ipairs(t) do
	if v.flags == gg.TYPE_FLOAT then
		v.value = '0'
		v.freeze = true
	end
end
gg.addListItems(t)
t = nil
    gg.toast("Wallhack Exynos 7870 V5 activated")
  end

  function WHEXY9810()
    if w == 1 then
      WHFIX()
    else
      gg.clearList()
      gg.clearResults()
      gg.setRanges(gg.REGION_C_ALLOC)
      gg.searchNumber("0.5;360.0;736.0;0.5;1.0;1.0;1.0;1.0:85", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      if gg.getResultCount() == 0 then
        gg.alert("Value Not Found")
      else
        gg.searchNumber("0.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
        _Count = gg.getResultCount()
        _A = gg.getResults(_Count)
        last_Count = _Count + 1
        w = 1
        _T = "Edit Wallhack Value"
        WHFIX()
      end
    end
  end
  function WHFIX()
    if w == 0 then
      gg.alert("Value Not Found")
    else
      gg.setVisible(false)
      _CL = {}
      for _FORV_3_ = 1, _Count do
        _CL[_FORV_3_] = " Value   " .. _FORV_3_ .. ""
      end
      _CL[last_Count] = "⬅️ [Back]"
      _C_ = gg.choice(_CL, nil, "Wallhack Exynos 9810")
      for _FORV_3_ = 1, _Count do
        if _C_ == _FORV_3_ then
          for _FORV_7_, _FORV_8_ in ipairs(_A) do
            _A[_FORV_7_].freeze = false
            gg.addListItems(_A)
          end
          _A[_FORV_3_].value = 0
          _A[_FORV_3_].freeze = true
          gg.addListItems(_A)
          _FORV_3_ = _Count
        elseif K_2 == _Count + 1 then
          WA()
        end
      end
    end
    gg.setVisible(true)
  end

  function WHEXY8890V2()
    if w == 1 then
      WHFIX()
    else
      gg.clearList()
      gg.clearResults()
      gg.setRanges(gg.REGION_C_ALLOC)
      gg.searchNumber("0.5;360;640;1.0;1.0;1.0;1.0", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      if gg.getResultCount() == 0 then
        gg.alert("Value Not Found")
      else
        gg.searchNumber("0.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
        _Count = gg.getResultCount()
        _A = gg.getResults(_Count)
        last_Count = _Count + 1
        w = 1
        _T = "Edit Wallhack Value"
        WHFIX()
      end
    end
  end
  function WHFIX()
    if w == 0 then
      gg.alert("Value Not Found")
    else
      gg.setVisible(false)
      _CL = {}
      for _FORV_3_ = 1, _Count do
        _CL[_FORV_3_] = " Value   " .. _FORV_3_ .. ""
      end
      _CL[last_Count] = "⬅️ [Back]"
      _C_ = gg.choice(_CL, nil, "Wallhack Exynos 8890 V2")
      for _FORV_3_ = 1, _Count do
        if _C_ == _FORV_3_ then
          for _FORV_7_, _FORV_8_ in ipairs(_A) do
            _A[_FORV_7_].freeze = false
            gg.addListItems(_A)
          end
          _A[_FORV_3_].value = 0
          _A[_FORV_3_].freeze = true
          gg.addListItems(_A)
          _FORV_3_ = _Count
        elseif K_2 == _Count + 1 then
          WA()
        end
      end
    end
    gg.setVisible(true)
  end
  _T = "🔍 Search For Value"
  _T, w = 0
  function WHEXY7885V2()
    if w == 1 then
      WHFIX()
    else
      gg.clearList()
      gg.clearResults()
      gg.setRanges(gg.REGION_C_ALLOC)
      gg.searchNumber("0.5;360;736;1.0;1.0;1.0;1.0;1.0", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      if gg.getResultCount() == 0 then
        gg.alert("Value Not Found")
      else
        gg.searchNumber("0.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
        _Count = gg.getResultCount()
        _A = gg.getResults(_Count)
        last_Count = _Count + 1
        w = 1
        _T = "Edit Wallhack Value"
        WHFIX()
      end
    end
  end
  function WHFIX()
    if w == 0 then
      gg.alert("Value Not Found")
    else
      gg.setVisible(false)
      _CL = {}
      for _FORV_3_ = 1, _Count do
        _CL[_FORV_3_] = " Value   " .. _FORV_3_ .. ""
      end
      _CL[last_Count] = "⬅️ [Back]"
      _C_ = gg.choice(_CL, nil, "Wallhack Exynos 7885 V2")
      for _FORV_3_ = 1, _Count do
        if _C_ == _FORV_3_ then
          for _FORV_7_, _FORV_8_ in ipairs(_A) do
            _A[_FORV_7_].freeze = false
            gg.addListItems(_A)
          end
          _A[_FORV_3_].value = 0
          _A[_FORV_3_].freeze = true
          gg.addListItems(_A)
          _FORV_3_ = _Count
        elseif K_2 == _Count + 1 then
          WA()
        end
      end
    end
    gg.setVisible(true)
  end
  _T = "🔍 Search For Value"
  _T, w = 0
  function WHEXY7870V4()
    if w == 1 then
      WHFIX()
    else
      gg.clearList()
      gg.clearResults()
      gg.setRanges(gg.REGION_C_ALLOC)
      gg.searchNumber("1.0;1.0;1.0;1.0;1.0;0.5;268.0;552.0;0.5:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
      if gg.getResultCount() == 0 then
        gg.alert("Value Not Found")
      else
        gg.searchNumber("0.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
        _Count = gg.getResultCount()
        _A = gg.getResults(_Count)
        last_Count = _Count + 1
        w = 1
        _T = "Edit Wallhack Value"
        WHFIX()
      end
    end
  end
  function WHFIX()
    if w == 0 then
      gg.alert("Value Not Found")
    else
      gg.setVisible(false)
      _CL = {}
      for _FORV_3_ = 1, _Count do
        _CL[_FORV_3_] = " Value   " .. _FORV_3_ .. ""
      end
      _CL[last_Count] = "⬅️ [Back]"
      _C_ = gg.choice(_CL, nil, "Wallhack Exynos 7870")
      for _FORV_3_ = 1, _Count do
        if _C_ == _FORV_3_ then
          for _FORV_7_, _FORV_8_ in ipairs(_A) do
            _A[_FORV_7_].freeze = false
            gg.addListItems(_A)
          end
          _A[_FORV_3_].value = 0
          _A[_FORV_3_].freeze = true
          gg.addListItems(_A)
          _FORV_3_ = _Count
        elseif K_2 == _Count + 1 then
          WA()
        end
      end
    end
    gg.setVisible(true)
  end
  _T = "🔍 Search For Value"
  _T, w = 0
  
function WHEXY7570()
    gg.clearResults()
    gg.setRanges(gg.REGION_C_ALLOC)
    gg.searchNumber("360;0;0;0;-640;1;1;1;0;0;0;0;1;360;640;0.5;0;0;0;0.5;1;1;0;0;0;0;0;1;1;1;1;1,098618e-48:373", gg.TYPE_FLOAT)
    gg.searchNumber("0.5", gg.TYPE_FLOAT)
    t = gg.getResults(10)
    gg.editAll("50", gg.TYPE_FLOAT)
    t[1].value = "50"
    t[2].value = "50"
    t[3].value = "50"
    t[4].value = "50"
    t[5].value = "50"
    t[6].value = "50"
    t[1].freeze = true
    t[2].freeze = true
    t[3].freeze = true
    t[4].freeze = true
    t[5].freeze = true
    t[6].freeze = true
    print("addListItems: ", gg.addListItems(t))
    gg.toast("Wallhack Exynos 7570 activated")
end

function WHMTKV2()
    gg.clearResults()
    gg.setRanges(gg.REGION_C_ALLOC)
    gg.searchNumber("10000;0.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("0.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("0.5F;0.5F:17", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.alert("WallHack Mediatek active, please freeze after implementation")
    os.exit()
end

function WHMTK()
    gg.clearResults()
    gg.setRanges(gg.REGION_C_ALLOC)
    gg.searchNumber("4.2038954e-45;2.8025969e-44;4.2038954e-45;1.4012985e-45;2.8025969e-45;268.0;480.0;0.5:301", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("0.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.alert("Smooth picture quality into the training camp hand change, after the search is completed, change one by one to freeze <freeze interval change 1 will not flash>")
    os.exit()
end

function WHEXY8890()
    gg.clearResults()
    gg.setRanges(gg.REGION_C_ALLOC)
    gg.setRanges(gg.REGION_C_ALLOC)
    gg.searchNumber('1;1;1;1;1;1;0.5;0.5;2D;1D;5D;1D:200', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.refineNumber('0.5', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    revert = gg.getResults(100, nil, nil, nil, nil, nil, nil, nil, nil)
    for _FORV_4_, _FORV_5_ in ipairs((gg.getResults(100, nil, nil, nil, nil, nil, nil, nil, nil))) do
      if _FORV_5_.flags == gg.TYPE_FLOAT then
        _FORV_5_.value = '120'
        _FORV_5_.freeze = true
      end
    end
    gg.addListItems((gg.getResults(100, nil, nil, nil, nil, nil, nil, nil, nil)))
    gg.toast("Wallhack Exynos 8890 V1 activated")
    gg.clearResults()
end

function WHEXY7885()
    gg.clearResults()
    gg.setRanges(gg.REGION_C_ALLOC)
    gg.searchNumber('0,0;0,0;0,0;0,0;0,0;-0,0;0,5;-360,0;360,0;740,0;0,5;-740,0;0,0;0,0;0,0;0,0;0,0;1,0;1,0;0,0;0,0;0,0;0,0;0,0;1,0;1,0;1,0;1,0;0,0;0,0;0,0;1,0:133', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber('0.5', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    t = gg.getResults(10)
    gg.editAll('0', gg.TYPE_FLOAT)
    t[1].value = '0'
    t[2].value = '0.5'
    t[3].value = '0'
    t[4].value = '0.5'
    t[1].freeze = true
    t[2].freeze = true
    t[3].freeze = true
    t[4].freeze = true
    print('addListItems: ', gg.addListItems(t))
    gg.toast("Wallhack Exynos 7885 V1 activated")
end

function WHEXY7870V3()
    gg.clearResults()
    gg.setRanges(gg.REGION_C_ALLOC)
    gg.searchNumber('0.00030000001F;0.99998998642F;15,000.0F;0.00002F;1.0F;1.0F;1.0F;1.0F;1.0F;0.5F;268.0F;268.0F;480.0F;0.5F;480.0F;2D;1D;5D;1D;192D:265', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.refineNumber('0.5', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    revert = gg.getResults(100, nil, nil, nil, nil, nil, nil, nil, nil)
    for _FORV_4_, _FORV_5_ in ipairs((gg.getResults(100, nil, nil, nil, nil, nil, nil, nil, nil))) do
      if _FORV_5_.flags == gg.TYPE_FLOAT then
        _FORV_5_.value = '120'
        _FORV_5_.freeze = true
      end
    end
    gg.addListItems((gg.getResults(100, nil, nil, nil, nil, nil, nil, nil, nil)))
    gg.clearResults()
    gg.searchNumber('0.00030000001F;0.99998998642F;15,000.0F;0.00002F;1.0F;1.0F;1.0F;1.0F;1.0F;0.5F;268.0F;268.0F;480.0F;0.5F;480.0F;2D;1D;192D:265', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.refineNumber('0.5', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    revert = gg.getResults(100, nil, nil, nil, nil, nil, nil, nil, nil)
    for _FORV_5_, _FORV_6_ in ipairs((gg.getResults(100, nil, nil, nil, nil, nil, nil, nil, nil))) do
      if _FORV_6_.flags == gg.TYPE_FLOAT then
        _FORV_6_.value = '120'
        _FORV_6_.freeze = true
      end
    end
    gg.addListItems((gg.getResults(100, nil, nil, nil, nil, nil, nil, nil, nil)))
    gg.clearResults()
    gg.searchNumber('0.99998998642F;1.0F;1.0F;1.0F;1.0F;1.0F;0.5F;268.0F;268.0F;480.0F;0.5F;480.0F;2D;1D;192D:265', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.refineNumber('0.5', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    revert = gg.getResults(100, nil, nil, nil, nil, nil, nil, nil, nil)
    for _FORV_6_, _FORV_7_ in ipairs((gg.getResults(100, nil, nil, nil, nil, nil, nil, nil, nil))) do
      if _FORV_7_.flags == gg.TYPE_FLOAT then
        _FORV_7_.value = '120'
        _FORV_7_.freeze = true
      end
    end
    gg.addListItems((gg.getResults(100, nil, nil, nil, nil, nil, nil, nil, nil)))
    gg.clearResults()
    gg.searchNumber('0.99998998642F;1.0F;1.0F;1.0F;1.0F;1.0F;0.5F;268.0F;268.0F;480.0F;0.5F;480.0F;5D;1D;192D:265', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.refineNumber('0.5', gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    revert = gg.getResults(100, nil, nil, nil, nil, nil, nil, nil, nil)
    for _FORV_7_, _FORV_8_ in ipairs((gg.getResults(100, nil, nil, nil, nil, nil, nil, nil, nil))) do
      if _FORV_8_.flags == gg.TYPE_FLOAT then
        _FORV_8_.value = '120'
        _FORV_8_.freeze = true
      end
    end
    gg.addListItems((gg.getResults(100, nil, nil, nil, nil, nil, nil, nil, nil)))
    gg.toast("Wallhack Exynos 7870 V3 activated!")
    gg.clearResults()
    os.remove("/storage/emulated/0/.log.txt")
end

function WHEXY7870V2()
    gg.clearResults()
    gg.setRanges(gg.REGION_C_ALLOC)
    gg.searchNumber('0.0F;268.0F;-480.0F;1.0F;1.0F;1.0F;1.0F;0.0F;0.0F;268.0F;480.0F;0.5F;0.5F;0.0F;0.0F;1.0F;1.0F;0.0F;0.0F;1.0F;1.0F;1.0F;1.0F;0.0F;0.0F;0.0F:421', gg.TYPE_FLOAT)
    gg.searchNumber('0.5', gg.TYPE_FLOAT)
    t = gg.getResults(10)
    gg.editAll('50', gg.TYPE_FLOAT)
    t[1].value = '50'
    t[2].value = '50'
    t[3].value = '50'
    t[4].value = '50'
    t[5].value = '50'
    t[6].value = '50'
    t[1].freeze = true
    t[2].freeze = true
    t[3].freeze = true
    t[4].freeze = true
    t[5].freeze = true
    t[6].freeze = true
    print('addListItems: ', gg.addListItems(t))
    gg.toast("Wallhack Exynos 7870 V2 activated")
end

function WHEXY7870V1()
    gg.clearResults()
    gg.setRanges(gg.REGION_C_ALLOC)
    gg.searchNumber('360;0;0;0;-640;1;1;1;0;0;0;0;1;360;640;0.5;0;0;0;0.5;1;1;0;0;0;0;0;1;1;1;1;1,098618e-48:373', gg.TYPE_FLOAT)
    gg.searchNumber('0.5', gg.TYPE_FLOAT)
    t = gg.getResults(10)
    gg.editAll('50', gg.TYPE_FLOAT)
    t[1].value = '50'
    t[2].value = '50'
    t[3].value = '50'
    t[4].value = '50'
    t[5].value = '50'
    t[6].value = '50'
    t[1].freeze = true
    t[2].freeze = true
    t[3].freeze = true
    t[4].freeze = true
    t[5].freeze = true
    t[6].freeze = true
    print('addListItems: ', gg.addListItems(t))
    gg.toast("Wallhack Exynos 7870 V1 activated")
end

function WHEXY7420()
    gg.clearResults()
    gg.setRanges(gg.REGION_C_ALLOC)
    gg.searchNumber('360;0;0;0;-640;1;1;1;0;0;0;0;1;360;640;0.5;0;0;0;0.5;1;1;0;0;0;0;0;1;1;1;1;1,098618e-48:373', gg.TYPE_FLOAT)
    gg.searchNumber('0.5', gg.TYPE_FLOAT)
    t = gg.getResults(10)
    gg.editAll('50', gg.TYPE_FLOAT)
    t[1].value = '50'
    t[2].value = '50'
    t[3].value = '50'
    t[4].value = '50'
    t[5].value = '50'
    t[6].value = '50'
    t[1].freeze = true
    t[2].freeze = true
    t[3].freeze = true
    t[4].freeze = true
    t[5].freeze = true
    t[6].freeze = true
    print('addListItems: ', gg.addListItems(t))
    gg.toast("Wallhack Exynos 7420 activated")
end

function WHP60()
    gg.setRanges(gg.REGION_C_ALLOC)
    gg.searchNumber("3.8530377e-34;1.2960464e-38;1.4012985e-45;4.2038954e-45;4.2038954e-45;7.0064923e-45;4.2038954e-45;1.4012985e-45;5.1567783e-43;1.4012985e-45;2.8025969e-45;0.5:289", gg.TYPE_FLOAT, false, gg.SIGN_FUZZY_EQUAL, 0, -1)
    gg.searchNumber("0.5", gg.TYPE_FLOAT, false, gg.SIGN_FUZZY_EQUAL, 0, -1)
    var = gg.getResults(20)
    gg.editAll("2", gg.TYPE_FLOAT)
    var = gg.getResults(100)
    var[1].value = 2
    var[1].freeze = true
    var[2].value = 2
    var[2].freeze = true
    gg.addListItems(var)
    gg.clearResults()
    gg.toast('Wallhack Mediatek P60 activated')
end


function OTHERCLR()
  MN24 = gg.multiChoice({
"🎨 Universal Black Colour V1",
"🎨 Universal Black Colour V2",
"🎨 Universal White Colour V1",
"🎨 Universal White Colour V2",
"🎨 Universal Red Colour",
"🎨 Colour Mediatek Red Smooth",
"🎨 Colour Mediatek Green Smooth",
"🎨 Colour Mediatek Rainbow Smooth",
"🎨 Colour Mediatek Red HD",
"🎨 Colour Mediatek Yellow HD",
"🎨 Colour Mediatek Blue HD",
"🎨 Colour Mediatek Red HDR",
"🎨 Colour Mediatek Glow Yellow HDR",
"🎨 Colour Mediatek Glow Green HDR",
"🎨 Colour Mediatek Glow Blue HDR",
"🎨 Colour Mediatek P60 Red",
"🎨 Colour Mediatek P60 Yellow",
"🎨 Colour Mediatek P60 Blue",
"🎨 Colour Exynos Red HDR V1",
"🎨 Colour Exynos Red HDR V2",
"🎨 Colour Exynos Yellow Mix Green",
"🎨 Colour Exynos Blue",
"🎨 Colour Exynos Red V1",
"🎨 Colour Exynos Yellow V1",
"🎨 Colour Exynos Green V1",
"🎨 Colour Exynos Red V2",
"🎨 Colour Exynos Yellow V2",
"🎨 Colour Exynos Green V2",
"🎨 Colour Exynos Yellow V3",
"🎨 Colour Exynos Yellow V4",
"🎨 Colour Exynos Dark Red",
"🎨 Colour Exynos Dark Pink",
"🎨 Colour Exynos Dark Green",
"🎨 Colour Exynos Dark Blue",
"🎨 Colour Exynos Black V1",
"🎨 Colour Exynos Black V2",
"🎨 Colour Exynos White",
"🎨 Colour Exynos White Mix V1",
"🎨 Colour Exynos White Mix V2",
"🎨 Colour Exynos White Mix Pink",
"🎨 Colour Exynos White Mix Milk",
"🎨 Colour Kirin Red HDR",
"🎨 Colour Kirin Red",
"🎨 Colour Kirin Yellow",
"🎨 Colour Kirin Green",
"🎨 Colour Kirin Purple",
"🎨 Colour Kirin Black",
"🎨 Colour Kirin White",
"🔶 BACK"
}, nil, "📁 Other Chipset Colour Menu")
  if MN24 == nil then
  else
  if MN24[1] == true then BLACKV1() end
  if MN24[2] == true then BLACKV2() end
  if MN24[3] == true then WHITEV1() end
  if MN24[4] == true then WHITEV2() end
  if MN24[5] == true then UNIRED() end
  if MN24[6] == true then mtkred() end
  if MN24[7] == true then mtkgrn() end
  if MN24[8] == true then mtkrbw() end
  if MN24[9] == true then b16() end
  if MN24[10] == true then b17() end
  if MN24[11] == true then b18() end
  if MN24[12] == true then b20() end
  if MN24[13] == true then b21() end
  if MN24[14] == true then b22() end
  if MN24[15] == true then b23() end
  if MN24[16] == true then HS23() end
  if MN24[17] == true then HS24() end
  if MN24[18] == true then HS25() end
  if MN24[19] == true then RHDREXYV1() end
  if MN24[20] == true then RHDREXYV2() end
  if MN24[21] == true then YMGEXY() end
  if MN24[22] == true then BLUEEXY() end
  if MN24[23] == true then RDEXYV2() end
  if MN24[24] == true then YWEXYV2() end
  if MN24[25] == true then GRNEXY() end
  if MN24[26] == true then RDEXYV3() end
  if MN24[27] == true then YWEXYV3() end
  if MN24[28] == true then GRNEXYV2() end
  if MN24[29] == true then YWEXYV4() end
  if MN24[30] == true then YWEXYV5() end
  if MN24[31] == true then DREDEXY() end
  if MN24[32] == true then DPINKEXY() end
  if MN24[33] == true then DGRNEXY() end
  if MN24[34] == true then DBLUEEXY() end
  if MN24[35] == true then BKEXY() end
  if MN24[36] == true then BKEXYV2() end
  if MN24[37] == true then WTEXY() end
  if MN24[38] == true then WTMIXEXYV1() end
  if MN24[39] == true then WTMIXEXYV2() end
  if MN24[40] == true then WTMIXPEXY() end
  if MN24[41] == true then WTMIXMEXY() end
  if MN24[42] == true then REDHDRKRN() end
  if MN24[43] == true then REDKRN() end
  if MN24[44] == true then YLWKRN() end
  if MN24[45] == true then GRNKRN() end
  if MN24[46] == true then PLEKRN() end
  if MN24[47] == true then BKKRN() end
  if MN24[48] == true then WTKRN() end
  if MN24[49] == true then wallhackcolorsX() 
end
end
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

function WTKRN()
    gg.clearResults()
    gg.setRanges(gg.REGION_C_ALLOC)
    gg.searchNumber("40D;32D;16D;2D::37", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(100)
    gg.editAll("42", gg.TYPE_DWORD)
    gg.toast("Colour Kirin White activated")
end

function BKKRN()
    gg.clearResults()
    gg.setRanges(gg.REGION_C_ALLOC)
    gg.searchNumber("40D;32D;16D;2D::37", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(100)
    gg.editAll("39", gg.TYPE_DWORD)
    gg.toast("Colour Kirin Black activated")
end

function PLEKRN()
    gg.clearResults()
    gg.setRanges(gg.REGION_C_ALLOC)
    gg.searchNumber("40D;32D;16D;2D::37", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(100)
    gg.editAll("33", gg.TYPE_DWORD)
    gg.toast("Colour Kirin Purple activated")
end

function GRNKRN()
    gg.clearResults()
    gg.setRanges(gg.REGION_C_ALLOC)
    gg.searchNumber("40D;32D;16D;2D::37", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(100)
    gg.editAll("35", gg.TYPE_DWORD)
    gg.toast("Colour Kirin Green activated")
end

function YLWKRN()
    gg.clearResults()
    gg.setRanges(gg.REGION_C_ALLOC)
    gg.searchNumber("40D;32D;16D;2D::37", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(100)
    gg.editAll("24", gg.TYPE_DWORD)
    gg.toast("Colour Kirin Yellow activated")
end

function REDKRN()
    gg.clearResults()
    gg.setRanges(gg.REGION_C_ALLOC)
    gg.searchNumber("40D;32D;16D;2D::37", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(100)
    gg.editAll("38", gg.TYPE_DWORD)
    gg.toast("Colour Kirin Red activated")
end

function REDHDRKRN()
    gg.clearResults()
    gg.setRanges(gg.REGION_C_ALLOC)
    gg.searchNumber("40D;32D;16D;2D::37", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(100)
    gg.editAll("25", gg.TYPE_DWORD)
    gg.toast("Colour Kirin Red HDR activated")
end

function WTEXY()
    gg.setRanges(gg.REGION_C_ALLOC)
    gg.searchNumber("56;64;48::35", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("56", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(100)
    gg.editAll("67", gg.TYPE_DWORD)
    gg.toast("Colour Exynos White activated")
end

function YWEXYV5()
    gg.clearResults()
    gg.setRanges(gg.REGION_C_ALLOC)
    gg.searchNumber("56;64;48::35", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("56", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(100)
    gg.editAll("61", gg.TYPE_DWORD)
    gg.toast("Colour Exynos Yellow V4 activated")
end

function BLUEEXY()
    gg.clearResults()
    gg.setRanges(gg.REGION_C_ALLOC)
    gg.searchNumber("56;64;48::35", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("56", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(100)
    gg.editAll("53", gg.TYPE_DWORD)
    gg.toast("Colour Exynos Blue activated")
end

function WTMIXMEXY()
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("32;16;40;2::37", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("28", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("40;32;16;2::37", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("28", gg.TYPE_DWORD)
gg.toast("Colour Exynos White Mix Milk activated")
end

function WTMIXPEXY()
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("32;16;40;2::37", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("78", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("40;32;16;2::37", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("78", gg.TYPE_DWORD)
gg.toast("Colour Exynos White Mix Pink activated")
end

function WTMIXEXYV2()
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("32;16;40;2::37", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("30", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("40;32;16;2::37", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("30", gg.TYPE_DWORD)
gg.toast("Colour Exynos White Mix V2 activated")
end

function WTMIXEXYV1()
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("32;16;40;2::37", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("31", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("40;32;16;2::37", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("31", gg.TYPE_DWORD)
gg.toast("Colour Exynos White Mix V1 activated")
end

function YMGEXY()
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("32;16;40;2::37", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("36", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("40;32;16;2::37", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("36", gg.TYPE_DWORD)
gg.toast("Colour Exynos Yellow Mix Green activated")
end

function BKEXYV2()
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("32;16;40;2::37", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("87", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("40;32;16;2::37", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("87", gg.TYPE_DWORD)
gg.toast("Colour Exynos Black V2 activated")
end

function DBLUEEXY()
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("32;16;40;2::37", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("29", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("40;32;16;2::37", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("29", gg.TYPE_DWORD)
gg.toast("Colour Exynos Dark Blue activated")
end

function DPINKEXY()
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("32;16;40;2::37", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("33", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("40;32;16;2::37", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("33", gg.TYPE_DWORD)
gg.toast("Colour Exynos Dark Pink activated")
end

function DREDEXY()
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("32;16;40;2::37", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("37", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("40;32;16;2::37", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("37", gg.TYPE_DWORD)
gg.toast("Colour Exynos Dark Red activated")
end

function DGRNEXY()
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("32;16;40;2::37", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("35", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("40;32;16;2::37", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("35", gg.TYPE_DWORD)
gg.toast("Colour Exynos Dark Green activated")
end

function YWEXYV4()
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("32;16;40;2::45",gg.TYPE_DWORD,false,gg.SIGN_EQUAL,0,-1)
gg.refineNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(3)
gg.editAll("7", gg.TYPE_DWORD)
gg.toast("Colour Exynos Yellow V3 activated")
end

function RHDREXYV2()
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("32;16;40;2::37",gg.TYPE_DWORD,false,gg.SIGN_EQUAL,0,-1)
gg.refineNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(3)
gg.editAll("25", gg.TYPE_DWORD)
gg.toast("Colour Exynos Red HDR V2 activated")
end

function RHDREXYV1()
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("32;16;40;2::45",gg.TYPE_DWORD,false,gg.SIGN_EQUAL,0,-1)
gg.refineNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(3)
gg.editAll("-999", gg.TYPE_DWORD)
gg.toast("Colour Exynos Red HDR V1 activated")
end

function UNIRED()
    gg.clearResults()
    gg.setRanges(4)
    gg.searchNumber('40;32;16;2::37', 4, false, 536870912, 0, -1)
    gg.searchNumber('40', 4, false, 536870912, 0, -1)
    gg.getResults(9)
    gg.editAll('38', 4)
    gg.clearResults()
    gg.toast('Universal Red Colour activated')
end

function WHITEV2()
gg.clearResults()
gg.setRanges(32)
gg.searchNumber("573.70306396484;0.05499718338;1::50", 16, false, 536870912, 0, -1)
gg.searchNumber("1", 16, false, 536870912, 0, -1)
gg.getResults(1)
gg.editAll("999", 16)
gg.toast("Universal White Colour V2 activated")
end

function WHITEV1()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("0.05499718338;1.0", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("9999", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Universal White Colour V1 activated")
end

function BLACKV2()
gg.clearResults()
gg.setRanges(32)
gg.searchNumber("573.70306396484;0.05499718338;1", 16, false, 536870912, 0, -1)
gg.searchNumber("1.0", 16, false, 536870912, 0, -1)
gg.getResults(1200)
gg.editAll("-999", 16)
gg.clearResults()
gg.clearResults()
gg.toast("Universal Black Colour V2 activated")
end

function BLACKV1()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("573.70306396484;0.05499718338;1::50", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("-999", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Universal Black Colour V1 activated")
end

function GRNEXYV2()
gg.clearResults()
gg.setRanges(4)
gg.setRanges(4)
gg.searchNumber("40D;32D;16D;2D::53", 4, false, 536870912, 0, -1)
gg.refineNumber("40", 4, false, 536870912, 0, -1)
gg.getResults(4)
gg.editAll("35", 4)
gg.toast("Colour Exynos Green V2 activated")
gg.clearResults()
end

function YWEXYV3()
gg.clearResults()
gg.setRanges(4)
gg.setRanges(4)
gg.searchNumber("40D;32D;16D;2D::53", 4, false, 536870912, 0, -1)
gg.refineNumber("40", 4, false, 536870912, 0, -1)
gg.getResults(4)
gg.editAll("36", 4)
gg.toast("Colour Exynos Yellow V2 activated")
gg.clearResults()
end

function RDEXYV3()
gg.clearResults()
gg.setRanges(4)
gg.setRanges(4)
gg.searchNumber("40D;32D;16D;2D::53", 4, false, 536870912, 0, -1)
gg.refineNumber("40", 4, false, 536870912, 0, -1)
gg.getResults(4)
gg.editAll("38", 4)
gg.toast("Colour Exynos Red V2 activated")
gg.clearResults()
end

function BKEXY()
gg.setRanges(4)
gg.searchNumber("56;64;48::35", 4, false, 536870912, 0, -1)
gg.searchNumber("56", 4, false, 536870912, 0, -1)
gg.getResults(100)
gg.editAll("57", 4)
gg.toast("Colour Exynos Black V1 activated")
end

function GRNEXY()
gg.setRanges(4)
gg.searchNumber("56;64;48::35", 4, false, 536870912, 0, -1)
gg.searchNumber("56", 4, false, 536870912, 0, -1)
gg.getResults(100)
gg.editAll("60", 4)
gg.toast("Colour Exynos Green V1 activated")
end

function YWEXYV2()
gg.setRanges(4)
gg.searchNumber("802,824,192;48;937,041,920;40;736,370,688;32;802,824,192;48;802,824,192;16;802,824,192;2;2::", 4, false, 536870912, 0, -1)
gg.searchNumber("40", 4, false, 536870912, 0, -1)
gg.getResults(100)
gg.editAll("36", 4)
gg.clearResults()
gg.setRanges(4)
gg.searchNumber("32;16;40;2", 4, false, 536870912, 0, -1)
gg.searchNumber("40", 4, false, 536870912, 0, -1)
gg.getResults(100)
gg.editAll("36", 4)
gg.toast("Colour Exynos Yellow V1 activated")
end

function RDEXYV2()
gg.setRanges(4)
gg.searchNumber("56;64;48::35", 4, false, 536870912, 0, -1)
gg.searchNumber("56", 4, false, 536870912, 0, -1)
gg.getResults(100)
gg.editAll("58", 4)
gg.clearResults()
gg.setRanges(4)
gg.searchNumber("32;16;40;2", 4, false, 536870912, 0, -1)
gg.searchNumber("40", 4, false, 536870912, 0, -1)
gg.getResults(100)
gg.editAll("38", 4)
gg.toast("Colour Exynos Red V1 activated")
end

function mtkrbw()
gg.clearResults()
gg.setRanges(4)
gg.searchNumber("56;64;48::35", 4, false, 536870912, 0, -1)
gg.searchNumber("56", 4, false, 536870912, 0, -1)
gg.getResults(100)
gg.editAll("32", 4)
gg.toast("Colour Mediatek Rainbow Smooth activated")
gg.clearResults()
end

function mtkgrn()
gg.clearResults()
gg.setRanges(4)
gg.searchNumber("56;64;48::40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("56", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("52", gg.TYPE_DWORD)
gg.toast("Colour Mediatek Green Smooth activated")
end

function mtkred()
gg.clearResults()
gg.setRanges(4)
gg.searchNumber("56;64;48::35", 4, false, 536870912, 0, -1)
gg.searchNumber("56", 4, false, 536870912, 0, -1)
gg.getResults(100)
gg.editAll("58", 4)
gg.toast("Colour Mediatek Red Smooth activated")
gg.clearResults()
end

function b20()
  gg.clearResults()
  gg.setRanges(4)
  gg.setRanges(gg.REGION_C_ALLOC)
  gg.searchNumber("96;356;12;84;368;4;96;372;4;240;288;8;32;784;16;736,370,688;32;802,824,192;48;937,041,920;40;736,370,688;32;802,824,192;48;802,824,192;16;802,824,192::", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("38", gg.TYPE_DWORD)
  gg.toast("Colour Mediatek Red HDR activated")
  gg.clearResults()
end

function b21()
  gg.clearResults()
  gg.setRanges(4)
  gg.setRanges(gg.REGION_C_ALLOC)
  gg.searchNumber("96;356;12;84;368;4;96;372;4;240;288;8;32;784;16;736,370,688;32;802,824,192;48;937,041,920;40;736,370,688;32;802,824,192;48;802,824,192;16;802,824,192::", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("36", gg.TYPE_DWORD)
  gg.toast("Colour Mediatek Glow Yellow HDR activated")
  gg.clearResults()
end

function b22()
  gg.clearResults()
  gg.setRanges(4)
  gg.setRanges(gg.REGION_C_ALLOC)
  gg.searchNumber("96;356;12;84;368;4;96;372;4;240;288;8;32;784;16;736,370,688;32;802,824,192;48;937,041,920;40;736,370,688;32;802,824,192;48;802,824,192;16;802,824,192::", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("30", gg.TYPE_DWORD)
  gg.toast("Colour Mediatek Glow Green HDR activated")
  gg.clearResults()
end

function b23()
  gg.clearResults()
  gg.setRanges(4)
  gg.setRanges(gg.REGION_C_ALLOC)
  gg.searchNumber("96;356;12;84;368;4;96;372;4;240;288;8;32;784;16;736,370,688;32;802,824,192;48;937,041,920;40;736,370,688;32;802,824,192;48;802,824,192;16;802,824,192::", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("28", gg.TYPE_DWORD)
  gg.toast("Colour Mediatek Glow Blue HDR activated")
  gg.clearResults()
end

function b16()
  gg.clearResults()
  gg.setRanges(4)
  gg.setRanges(gg.REGION_C_ALLOC)
  gg.searchNumber("96;356;12;84;368;4;96;372;4;240;288;8;32;784;16;736,370,688;32;802,824,192;48;937,041,920;40;736,370,688;32;802,824,192;48;802,824,192;16;802,824,192::", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("38", gg.TYPE_DWORD)
  gg.toast("Colour Mediatek Red HD activated")
  gg.clearResults()
end

function b17()
  gg.clearResults()
  gg.setRanges(4)
  gg.setRanges(gg.REGION_C_ALLOC)
  gg.searchNumber("96;356;12;84;368;4;96;372;4;240;288;8;32;784;16;736,370,688;32;802,824,192;48;937,041,920;40;736,370,688;32;802,824,192;48;802,824,192;16;802,824,192::", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("36", gg.TYPE_DWORD)
  gg.toast("Colour Mediatek Yellow HD activated")
  gg.clearResults()
end

function b18()
  gg.clearResults()
  gg.setRanges(4)
  gg.setRanges(gg.REGION_C_ALLOC)
  gg.searchNumber("96;356;12;84;368;4;96;372;4;240;288;8;32;784;16;736,370,688;32;802,824,192;48;937,041,920;40;736,370,688;32;802,824,192;48;802,824,192;16;802,824,192::", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("28", gg.TYPE_DWORD)
  gg.toast("Colour Mediatek Blue HD activated")
  gg.clearResults()
end

function HS25()
	 gg.clearResults()
	 gg.setRanges(4)
	 gg.setRanges(gg.REGION_C_ALLOC)
	 gg.searchNumber("802,824,192;48;937,041,920;40;736,370,688;32;802,824,192;48;802,824,192;16;802,824,192;2;2::", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
	 gg.searchNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
	 gg.getResults(100)
	 gg.editAll("28", gg.TYPE_DWORD)
	 gg.toast("Colour Mediatek P60 Blue activated")
	 gg.clearResults()
end

function HS23()
	 gg.clearResults()
	 gg.setRanges(4)
	 gg.setRanges(gg.REGION_C_ALLOC)
	 gg.searchNumber("802,824,192;48;937,041,920;40;736,370,688;32;802,824,192;48;802,824,192;16;802,824,192;2;2::", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
	 gg.searchNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
	 gg.getResults(100)
	 gg.editAll("38", gg.TYPE_DWORD)
	 gg.toast("Colour Mediatek P60 Red activated")
	 gg.clearResults()
end

function HS24()
	 gg.clearResults()
	 gg.setRanges(4)
	 gg.setRanges(gg.REGION_C_ALLOC)
	 gg.searchNumber("802,824,192;48;937,041,920;40;736,370,688;32;802,824,192;48;802,824,192;16;802,824,192;2;2::", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
	 gg.searchNumber("40", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
	 gg.getResults(100)
	 gg.editAll("36", gg.TYPE_DWORD)
	 gg.toast("Colour Mediatek P60 Yellow activated")
	 gg.clearResults()
end

function WH615l()
  gg.clearResults()
  gg.setRanges(gg.REGION_C_HEAP)
  gg.searchNumber("3.3631163e-44;2.0;3.5032462e-44;-1.0;3.643376e-44;3.7835059e-44;-1.0;3.9236357e-44;4.0637655e-44;1.0;-127.0:129", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("3.1809475e-43;3.1949605e-43;2.0;3.2089735e-43:53", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("Wallhack 615 activated")
end
function WH625l()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO)
  gg.searchNumber("135,215D;4,140D;3.7615819e-37;2::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("130", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO)
  gg.searchNumber("194D;3.7615819e-37;2;-1;1;-127::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("130", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("WH SD 625 Activated")
end
function WH626l()
  gg.setRanges(gg.REGION_VIDEO)
  gg.searchNumber("2.718519e-43F;3.7615819e-37F;2.0F;0.00999999978F::200", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber(2, gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("130", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO)
  gg.searchNumber("5.8013756e-42F;-5.5695588e-40F;2.0F::100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber(2, gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("130", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("32769D;32770D;2.0F::200", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(9)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO)
  gg.searchNumber("1.1202013e-19;1.1202017e-19;2::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(3)
  gg.editAll("9999", gg.TYPE_FLOAT)
  gg.toast("Wallhack 626 activated!")
end
function WH636l()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO)
  gg.searchNumber("2.718519e-43F;3.7615819e-37F;2.0F;-1.0F;1.0F;-127.0F;0.00999999978F::200", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber(2, gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("5.8013756e-42F;-5.5695588e-40F;2.0F::100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber(2, gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("Wallhack 636 activated!")
end
function WH435l()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO)
  gg.searchNumber("135,215D;4,140D;3.7615819e-37;2::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("130", gg.TYPE_FLOAT)
  gg.setRanges(gg.REGION_VIDEO)
  gg.searchNumber("194D;3.7615819e-37;2;-1;1;-127::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("130", gg.TYPE_FLOAT)
end
function WH450l()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO)
  gg.searchNumber("135,215D;4,140D;3.7615819e-37;2::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("130", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO)
  gg.searchNumber("194D;3.7615819e-37;2;-1;1;-127::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("130", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.toast("Sabar Plak")
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO)
  gg.searchNumber("1.1202013e-19;1.1202017e-19;2::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(1)
  gg.editAll("9999", gg.TYPE_FLOAT)
  gg.toast("Sabar Plak Bentar Lagi Kelar")
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO)
  gg.searchNumber("2.718519e-43F;3.7615819e-37F;2.0F;0.00999999978F::200", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber(2, gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("150", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO)
  gg.searchNumber("5.8013756e-42F;-5.5695588e-40F;2.0F::100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber(2, gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("150", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO)
  gg.searchNumber("4.7961574e21;3.7615819e-37;2::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber(2, gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("150", gg.TYPE_FLOAT)
  gg.clearResults()
end
function WH653l()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO)
  gg.clearResults()
  gg.searchNumber("2.718519e-43F;3.7615819e-37F;2.0F;0.00999999978F::200", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber(2, gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("5.8013756e-42F;-5.5695588e-40F;2.0F::100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber(2, gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
end
function WH660l()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO)
  gg.searchNumber("4,140D;4.7408166e21;5.6896623e-29;4.7961574e21;3.7615819e-37;2:", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(3)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("200,866D;0.24022650719;0.69314718246;0.00999999978;1;-1;2;-127:", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(2)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("32,770D;0.01799999923;0.29907226562;-1;2:", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(4)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("50,331,648D;0.01799999923;0.29907226562;0.5869140625;0.11401367188;-1;2:", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("-1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(2)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("50,331,648D;0.04000854492;0.11999511719;-0.02749633789;-0.57177734375;-1;2:", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("-1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(1)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("266,400D;0.24022650719;0.69314718246;0.00999999978;1;-1;-127;2:", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("50,331,648D;0.04000854492;0.11999511719;-0.02749633789;-0.57177734375;-1;2:", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(2)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("4,140D;4.7408149e21;-5.5695588e-40;4.814603e21;3.7615819e-37;2:", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(20)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
end
function WH820l()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO)
  gg.searchNumber("135,215D;4,140D;3.7615819e-37;2::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("130", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO)
  gg.searchNumber("194D;3.7615819e-37;2;-1;1;-127::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(10)
  gg.editAll("130", gg.TYPE_FLOAT)
  gg.clearResults()
end
function WH835l()
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO)
  gg.searchNumber("2.718519e-43F;3.7615819e-37F;2.0F;0.00999999978F::200", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber(2, gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.searchNumber("5.8013756e-42F;-5.5695588e-40F;2.0F::100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber(2, gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(30)
  gg.editAll("120", gg.TYPE_FLOAT)
  gg.clearResults()
  gg.setRanges(gg.REGION_VIDEO)
  gg.searchNumber("7.1746481e-43;1.0842022e-19;94.015625;7.0776718e-15;2::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(5)
  gg.editAll("9999", gg.TYPE_FLOAT)
  gg.clearResults()
end

function wh6755()
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
colorV5()
gg.toast("WallHack 675")
end

function bluecolorV2()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("8201", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("0B0")
gg.getResults(999)
gg.editAll("8198", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Color Blue")
end

function greencolorV2()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("8201", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("0B0")
gg.getResults(999)
gg.editAll("8199", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Color Green")
end

function yellow660()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("1.3912525e-19F;8200;96", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(999)
gg.editAll("8198", gg.TYPE_DWORD)
gg.clearResults()
end

function red660()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("1.3912525e-19F;8200;96", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(999)
gg.editAll("8199", gg.TYPE_DWORD)
gg.clearResults()
end

function wh660()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("135215D;4140D;3.7615819e-37;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(999)
gg.editAll("130", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("194D;3.7615819e-37;2;-1;1;-127", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(999)
gg.editAll("130", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("WallHack 660")
end

function fixBlink2()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("6.50000333786;1.1202013e-19;3.7615819e-37;2::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(999)
gg.editAll("9999", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Fix Blink 845-855")
end

function fixBlink()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("5.2806111e-40;6.50000333786;3.7615819e-37;2", gg.TYPE_FLOAT,false, gg.SIGN_EQUAL,0,-1)
gg.refineNumber("2", gg.TYPE_FLOAT,false, gg.SIGN_EQUAL,0,-1)
gg.getResults(999)
gg.editAll("9999", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("1.1202011e-19;1.1202015e-19;3.7615819e-37;255.0;2", gg.TYPE_FLOAT,false, gg.SIGN_EQUAL,0,-1)
gg.refineNumber("2", gg.TYPE_FLOAT,false, gg.SIGN_EQUAL,0,-1)
gg.getResults(999)
gg.editAll("9999", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Fix Blink 430-835")
end

function bluecolorV1()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("8201", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("0A0")
gg.getResults(999)
gg.editAll("8198", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Blue Color")
end

function greencolorV1()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("8201", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("0A0")
gg.getResults(999)
gg.editAll("8199", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Green Color")
end

function redcolorV1()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("8204", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("E70", -1, gg.TYPE_DWORD, gg.SIGN_EQUAL, 0, -1)
gg.getResults(999)
gg.editAll("9999", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Red Color")
end

function yellowcolorV1()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("8204", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("E70", -1, gg.TYPE_DWORD, gg.SIGN_EQUAL, 0, -1)
gg.getResults(999)
gg.editAll("8564", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Yellow Color")
end

function redcolorV2V3()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("8200;96", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("098", -1, gg.TYPE_DWORD, gg.SIGN_EQUAL, 0, -1)
gg.getResults(999)
gg.editAll("8199", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Red Color")
end

function yellowcolorV2V3()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("8200;96", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress("098", -1, gg.TYPE_DWORD, gg.SIGN_EQUAL, 0, -1)
gg.getResults(999)
gg.editAll("8198", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Yellow Color")
end

function whV1()
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("2.9427268e-44;2.0;3.0828566e-44;-1.0;3.2229865e-44;3.3631163e-44;3.643376e-44:97", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("3.1529215e-43;2.0F;3.1669345e-43F;3.1809475e-43:49", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("WallHack 400-425")
end

function whV2()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.searchNumber("2;1.8947657e-40;5.8013756e-42", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(999)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("2.718519e-43;3.7615819e-37;2;-1;1;-127", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(999)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("WallHack 430-835")
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
