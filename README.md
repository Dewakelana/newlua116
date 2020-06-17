# newlua116
Newlua116
function BP()
gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.clearResults()
gg.searchNumber("2.718519e-43F;3.7615819e-37F;2.0F;0.00999999978F::200", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults()
gg.searchNumber("2.718519e-43F;3.7615819e-37F;2.0F;0.00999999978F::200", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults()
gg.searchNumber("2.718519e-43F;3.7615819e-37F;2.0F;0.00999999978F::200", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults()
gg.searchNumber("2.718519e-43F;3.7615819e-37F;2.0F;0.00999999978F::200", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults()
gg.searchNumber("2.718519e-43F;3.7615819e-37F;2.0F;0.00999999978F::200", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.clearResults()
gg.toast("AayMax") end

function startBypass()
gg.setVisible(false)
bypassAlert = gg.alert("Batu permata tak dapat mengeluarkan kilaunya yang indah tanpa adanya gesekan demikian juga manusia tidak dapat disempurnakan tanpa adanya ujian\nBAIPAS DAN TIDAK TERGANTUNG AAY.         Mr. Aay script vip hack \n    Script By. Aay\n    Youtube : \n   ", "", "")
if bypassAlert == 2 then BP() end
end
startBypass()
HOME = 1

function HOME()
MN = gg.choice({
	" Wall Hack\n  Lobby",
	" Menu Wapon \n  In Game",
	" Menu hack2 \n  In Game ",
	" Menu hack3 \n  In Game",
	" EXIT "},nil, (os.date("-\n  Mr. Aay script vip hack\n  Script By. Aay\n  Youtube : \n  \n  : %Y/%m/%d  : %H:%M:%S\n-")))
if MN == nil then else
if MN == 1 then WH() end
if MN == 2 then MENU1() end
if MN == 3 then MENU2() end
if MN == 4 then MENU3() end
if MN == 5 then CLOSE() end
end PUBGMH = -1 end

function WH()
MN1 = gg.multiChoice({
" Wallhack",
" Wallhack Perfact",
" HDR Merah1",
" HDR Merah2",
" Yellow",
" BACK HOME ",}, nil, (os.date("-\n  Mr. Aay script vip hack\n  Script By. Aay\n  Youtube : \n  \n  : %Y/%m/%d  : %H:%M:%S\n-")))
if MN1 == nil then else
if MN1[1] == true then WH3() end
if MN1[2] == true then WH4() end
if MN1[3] == true then A1() end
if MN1[4] == true then A2() end
if MN1[5] == true then A3() end
if MN1[6] == true then HOME() end
end
PUBGMH = -1
end

function WH3()
gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.searchNumber("2.718519e-43;3.7615819e-37;2.0;0.00999999978::200", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber(2, gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("5.8013756e-42;-5.5695588e-40;2.0::100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber(2, gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("4,140D;4.7408166e21;5.6896623e-29;4.7961574e21;3.7615819e-37;2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber(2, gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("120", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("WH ")
end

function WH4()
gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.searchNumber("135,215D;4,140D;3.7615819e-37;2::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("130", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.searchNumber("194D;3.7615819e-37;2;-1;1;-127::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("130", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("WH Perfect   ")
end

function A1()
gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.searchNumber("8,196D;8,192D;8,200D::", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("7", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("Red Body Activated")
end

function A2()
gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.searchNumber( "2;1.8947657e-40;5.8013756e-42", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber( "2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(999)
gg.editAll( "120", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber( "2.718519e-43;3.7615819e-37;2;-1;1;-127", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber( "2", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(999)
gg.editAll( "120", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.searchNumber( "8200;96", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber( "8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.refineAddress( "098", -1, gg.TYPE_DWORD, gg.SIGN_EQUAL, 0, -1)
gg.getResults(999)
gg.editAll( "8199", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("   835 Activated")
end

function A3()
gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.searchNumber("256;8200;13::150", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("8200", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("6", gg.TYPE_DWORD)
gg.clearResults()
gg.toast("DEEN ARIEF")
end

function MENU1()
MN2 = gg.multiChoice({
	"  Aimbot Super [Game]",
	"  New Aimlock Super [Game]",
	"  Less Recoil [Lobby]",
	"  Auto Hedshot [Game] ",
	"  Speed Runn [Game]",
	"  Ipad View [Game]",
	"  Magic Bullet [Game] ",
	"  Black skay ",
	"  Multi Jump [Game] ",
	"  One Clik",
	" HOME ", },nil, (os.date("-\n  Mr. Aay script vip hack\n  Script By. Aay\n  Youtube : \n  \n  : %Y/%m/%d  : %H:%M:%S\n-")))
if MN2 == nil then else
if MN2[1] == true then A() end
if MN2[2] == true then B() end
if MN2[3] == true then C() end
if MN2[4] == true then D() end
if MN2[5] == true then E() end
if MN2[6] == true then F() end
if MN2[7] == true then G() end
if MN2[8] == true then H() end
if MN2[9] == true then I() end
if MN2[10] == true then J() end
if MN2[11] == true then HOME() end
end
PUBGMH = -1
end

function A()
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("360;0.0001;1478828288", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.0001", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("9999", gg.TYPE_FLOAT)
gg.toast("✅ تم التفعيل ايم بوت 100متر ✅")
end

function B()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.clearResults()
gg.searchNumber("3.5;1;200;20::999", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("3.5;1;200;20", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(300)
gg.editAll("1.0e20", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("3.5;1;0.5;200;20::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(600)
gg.editAll("999", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("-88.82363891602F;15.0F;1", gg.TYPE_FLOAT)
gg.searchNumber("1", gg.TYPE_FLOAT)
gg.getResults(2000)
gg.editAll("20000000000000", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast(" Aimlock ")
end

function C()
gg.clearResults()
gg.setRanges(32)
gg.searchNumber("1.5584387e28", 16, false, 536870912, 0, -1)
gg.searchNumber("1.5584387e28", 16, false, 536870912, 0, -1)
gg.getResults(100)
gg.editAll("0", 16)
gg.clearResults()
gg.setRanges(32)
gg.searchNumber("1D;0.05000000075F;0.10000000149F;0.55000001192F;9.5F;15.0F", 16, false, 536870912, 0, -1)
gg.searchNumber("1", 4, false, 536870912, 0, -1)
gg.getResults(800)
gg.editAll("0", 4)
gg.clearResults()
gg.toast("Less Recoil Activated")
end

function D()
gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.searchNumber("-88.66608428955;26:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("26", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(92)
gg.editAll("-89999960", gg.TYPE_FLOAT)
gg.clearResults()
gg.searchNumber("-88.73961639404;28:512", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(92)
gg.editAll("-99999960", gg.TYPE_FLOAT)
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
gg.getResults(100)
gg.editAll("245", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("150;85;45;-129;-85", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("45", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(30)
gg.editAll("999999", gg.TYPE_FLOAT)
gg.toast("AUTO HEADSHOT 95% AKTIF PLAK ")
end

function E()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("1;1;1;0.0001;20;0.0005;0.4::50", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(300)
gg.editAll("1.07", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast(" Speed Ruun ")
end

function F()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("2.8025969e-45;220;25;178;15;100", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("220", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("440", gg.TYPE_FLOAT)
gg.toast("Ipad View")
end

function G()
gg.clearResults()
gg.setRanges(gg.REGION_CODE_APP)
gg.searchNumber("0.0001;360.0;0.0;1,478,828,416.0", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.0001", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(2)
gg.editAll("999", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("MAGIC BULLET LOBBY ACTIVATED")
end

function H()
gg.clearResults()
gg.setRanges(gg.REGION_BAD)
gg.clearResults()
gg.searchNumber("100F;1F;1,008,981,770D:99", gg.TYPE_FLOAT, false)
gg.searchNumber("100", gg.TYPE_FLOAT, false)
gg.getResults(100)
gg.editAll("-90", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast(" Black Skay ")
end

function I()
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-8.795458e22;-3.693674e20;1.2382424e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1.2382424e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("-1.2382424e28", gg.TYPE_FLOAT)
gg.clearResults()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("1;-0.70710676908;0.70710670948;64;1.793662e-43;1.4012985e-45;1D;1D::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1.4012985e-45", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(9999)
gg.editAll("999", gg.TYPE_FLOAT)
gg.toast("Multi Jump ")
end

function J()
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("360;0.0001;1478828288", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("0.0001", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("9999", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast(" Aimbot Super 100M ")
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("3.5;1;200;20::999", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("-9999999999", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast(" Aimbot Sniper ")
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
gg.toast(" Aimbot Ultra ")
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("300", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("9.20161819458;23;25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("25;30.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("240", gg.TYPE_FLOAT)
gg.toast(" Auto Headshot 99% ")
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
gg.toast(" Magic Bullet 99% ")
end


function MENU2()
MN3 = gg.multiChoice({
	" super speed on",
	" super speed off",
	" ESP ",
	" ESP LONG ",
	" LESS RECOIL ",
	" ****** ",
	" ****** ",
	" ****** ",
	" ****** ",
	" ****** ",
	" ****** ",
	" ****** ",
	" ****** ",
	" ****** ",
	" ****** ",
	" ****** ",
	" HOME ",}, nil, (os.date("-\n  Mr. Aay script vip hack\n  Script By. Aay\n  Youtube : \n  \n  : %Y/%m/%d  : %H:%M:%S\n-")))
if MN3 == nil then else
if MN3[1] == true then mw1() end
if MN3[2] == true then mw2() end
if MN3[3] == true then mw3() end
if MN3[4] == true then mw4() end
if MN3[5] == true then mw5() end
if MN3[6] == true then mw6() end
if MN3[7] == true then mw7() end
if MN3[8] == true then mw8() end
if MN3[9] == true then mw9() end
if MN3[10] == true then mw10() end
if MN3[11] == true then mw11() end
if MN3[12] == true then mw12() end
if MN3[13] == true then mw13() end
if MN3[14] == true then mw14() end
if MN3[15] == true then mw15() end
if MN3[16] == true then mw16() end
if MN3[17] == true then HOME() end
end
PUBGMH = -1
end

function mw1()
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-8.795458e22;-3.693674e20;-1.2382424e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("-1.2382424e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("1.2382424e28", gg.TYPE_FLOAT)
gg.clearResults()
gg.toast("Super Speed Aktif Plak ")
end

function mw2()
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-8.795458e22;-3.693674e20;1.2382424e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1.2382424e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("-1.2382424e28", gg.TYPE_FLOAT)
end

function mw3()
gg.clearResults()
gg.setRanges(8)
gg.searchNumber("-476053504;-349478012:189", 4, false, 536870912, 0, -1)
gg.searchNumber("-476053504", 4, false, 536870912, 0, -1)
gg.getResults(100)
gg.editAll("-476053503;-476053504", 4)
gg.clearResults()
gg.setRanges(8)
gg.searchNumber("324009984;-348261320:165", 4, false, 536870912, 0, -1)
gg.searchNumber("324009984", 4, false, 536870912, 0, -1)
gg.getResults(100)
gg.editAll("324009985", 4)
gg.clearResults()
gg.setRanges(8)
gg.searchNumber("-336586203;-511702015:105", 4, false, 536870912, 0, -1)
gg.searchNumber("-511702015", 4, false, 536870912, 0, -1)
gg.getResults(100)
gg.editAll("0", 4)
gg.clearResults()
gg.setRanges(8)
gg.searchNumber("-511633406;-352273285;-511633406:809", 4, false, 536870912, 0, -1)
gg.searchNumber("-511633406", 4, false, 536870912, 0, -1)
gg.getResults(100)
gg.editAll("0", 4)
gg.clearResults()
gg.setRanges(8)
gg.searchNumber("-335545007;-511702015:85", 4, false, 536870912, 0, -1)
gg.searchNumber("-511702015", 4, false, 536870912, 0, -1)
gg.getResults(100)
gg.editAll("0", 4)
gg.clearResults()
gg.setRanges(8)
gg.searchNumber("2046820354;-336587221:9", 4, false, 536870912, 0, -1)
gg.searchNumber("2046820354", 4, false, 536870912, 0, -1)
gg.getResults(100)
gg.editAll("2046820353", 4)
gg.clearResults()
gg.setRanges(8)
gg.searchNumber("2015175168", 16, false, 536870912, 0, -1)
gg.getResults(6)
gg.editAll("0", 16)
gg.toast("Esp Circle")
end

function mw4()
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-476053504;-349478012:189", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("-476053504", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("-476053503;-476053504", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("324009984;-348261320:165", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("324009984", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("324009985", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-336586203;-511702015:105", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("-511702015", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("0", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-511633406;-352273285;-511633406:809", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("-511633406", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("0", gg.TYPE_DWORD)
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-335545007;-511702015:85", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("-511702015", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.editAll("0", gg.TYPE_DWORD)
gg.clearResults()
gg.alert("ON")
end

function mw5()
gg.alert("LESS RECOIL DONG BANG DEEN ","MANTAP")
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-1.3039565e21;-3.6907917e20;-1.3620364e28;-3.6893509e20:13", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("-1.3620364e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("0", gg.TYPE_FLOAT)
gg.clearResults()
gg.setRanges(gg.REGION_C_DATA)
gg.searchNumber("-5.8454592e27;-5.7318526e27;-1.3620364e28:9", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.refineNumber("-1.3620364e28", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(1)
gg.editAll("0", gg.TYPE_FLOAT)
gg.toast("√ DEEN ARIEF √")
gg.clearResults()
end

function mw6()

end

function mw7()

end

function mw8()

end

function mw9()

end

function mw10()

end

function mw11()

end

function mw12()

end

function mw13()

end

function mw14()

end

function mw15()

end

function mw16()

end

function mw17()

end


function MENU3()
MN4 = gg.multiChoice({
	" ****** ",
	" ****** ",
	" ****** ",
	" ****** ",
	" ****** ",
	" ****** ",
	" ****** ",
	" ****** ",
	" ****** ",
	" ****** ",
	" ****** ",
	" ****** ",
	" ****** ",
	" ****** ",
	" ****** ",
	" ****** ",
	" HOME ",},
	nil, (os.date("-\n  Mr. Aay script vip hack\n  Script By. Aay\n  Youtube : \n  \n  : %Y/%m/%d  : %H:%M:%S\n-")))
if MN4 == nil then else
if MN4[1] == true then mw1() end
if MN4[2] == true then mw2() end
if MN4[3] == true then mw3() end
if MN4[4] == true then mw4() end
if MN4[5] == true then mw5() end
if MN4[6] == true then mw6() end
if MN4[7] == true then mw7() end
if MN4[8] == true then mw8() end
if MN4[9] == true then mw9() end
if MN4[10] == true then mw10() end
if MN4[11] == true then mw11() end
if MN4[12] == true then mw12() end
if MN4[13] == true then mw13() end
if MN4[14] == true then mw14() end
if MN4[15] == true then mw15() end
if MN4[16] == true then mw16() end
if MN4[17] == true then HOME() end
end
PUBGMH = -1
end

function CLOSE()
print("Report Tetap Banned")
print("Thanks For Suport")
gg.skipRestoreState()
os.exit()
gg.setVisible(true)
end
while true do
if gg.isVisible(true)
then PUBGMH = 1
gg.setVisible(false)
end
gg.clearResults()
if PUBGMH == 1 then
HOME() end
end
L0_0 = L0_0
L0_0 = L0_0
L0_0 = L0_0
