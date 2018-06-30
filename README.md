D0=16:D1=5:D2=4:D3=0:D4=2:D5=14:D6=12:D7=13:D8=15:D9=3:D10=1
neo.setup d1,54
neo.pixel 0,10,10,10

for t = 0 to 300
neo.pixel rnd(54),rnd(100),rnd(10),rnd(10)
pause 20
gosub fadeout
next t


for p = 0 to 20
for t = 0 to 50
gosub scrolld
neo.pixel 0,neo.getpixel(0)
next t
for t = 0 to 50
gosub scrollu
neo.pixel 0,neo.getpixel(0)
next t
next p

scrollu:
neo.pixel 0,neo.getpixel(1),1
neo.pixel 1,neo.getpixel(2),1
neo.pixel 2,neo.getpixel(3),1
neo.pixel 3,neo.getpixel(4),1
neo.pixel 4,neo.getpixel(5),1
neo.pixel 5,neo.getpixel(6),1
neo.pixel 6,neo.getpixel(7),1
neo.pixel 7,neo.getpixel(8),1
neo.pixel 8,neo.getpixel(9),1
neo.pixel 9,neo.getpixel(10),1
neo.pixel 10,neo.getpixel(11),1
neo.pixel 11,neo.getpixel(12),1
neo.pixel 12,neo.getpixel(13),1
neo.pixel 13,neo.getpixel(14),1
neo.pixel 14,neo.getpixel(15),1
neo.pixel 15,neo.getpixel(16),1
neo.pixel 16,neo.getpixel(17),1
neo.pixel 17,neo.getpixel(18),1
neo.pixel 18,neo.getpixel(19),1
neo.pixel 19,neo.getpixel(20),1
neo.pixel 20,neo.getpixel(21),1
neo.pixel 21,neo.getpixel(22),1
neo.pixel 22,neo.getpixel(23),1
neo.pixel 23,neo.getpixel(24),1
neo.pixel 24,neo.getpixel(25),1
neo.pixel 25,neo.getpixel(26),1
neo.pixel 26,neo.getpixel(27),1
neo.pixel 27,neo.getpixel(28),1
neo.pixel 28,neo.getpixel(29),1
neo.pixel 29,neo.getpixel(30),1
neo.pixel 30,neo.getpixel(31),1
neo.pixel 31,neo.getpixel(32),1
neo.pixel 32,neo.getpixel(33),1
neo.pixel 33,neo.getpixel(34),1
neo.pixel 34,neo.getpixel(35),1
neo.pixel 35,neo.getpixel(36),1
neo.pixel 36,neo.getpixel(37),1
neo.pixel 37,neo.getpixel(38),1
neo.pixel 38,neo.getpixel(39),1
neo.pixel 39,neo.getpixel(40),1
neo.pixel 40,neo.getpixel(41),1
neo.pixel 41,neo.getpixel(42),1
neo.pixel 42,neo.getpixel(43),1
neo.pixel 43,neo.getpixel(44),1
neo.pixel 44,neo.getpixel(45),1
neo.pixel 45,neo.getpixel(46),1
neo.pixel 46,neo.getpixel(47),1
neo.pixel 47,neo.getpixel(48),1
neo.pixel 48,neo.getpixel(49),1
neo.pixel 49,neo.getpixel(50),1
neo.pixel 50,neo.getpixel(51),1
neo.pixel 51,neo.getpixel(52),1
neo.pixel 52,neo.getpixel(53),1
neo.pixel 53,neo.getpixel(54),1
neo.pixel 54,0,1
return

end


scrolld:
neo.pixel 54,neo.getpixel(53),1
neo.pixel 53,neo.getpixel(52),1
neo.pixel 52,neo.getpixel(51),1
neo.pixel 51,neo.getpixel(50),1
neo.pixel 50,neo.getpixel(49),1
neo.pixel 49,neo.getpixel(48),1
neo.pixel 48,neo.getpixel(47),1
neo.pixel 47,neo.getpixel(46),1
neo.pixel 46,neo.getpixel(45),1
neo.pixel 45,neo.getpixel(44),1
neo.pixel 44,neo.getpixel(43),1
neo.pixel 43,neo.getpixel(42),1
neo.pixel 42,neo.getpixel(41),1
neo.pixel 41,neo.getpixel(40),1
neo.pixel 40,neo.getpixel(39),1
neo.pixel 39,neo.getpixel(38),1
neo.pixel 38,neo.getpixel(37),1
neo.pixel 37,neo.getpixel(36),1
neo.pixel 36,neo.getpixel(35),1
neo.pixel 35,neo.getpixel(34),1
neo.pixel 34,neo.getpixel(33),1
neo.pixel 33,neo.getpixel(32),1
neo.pixel 32,neo.getpixel(31),1
neo.pixel 31,neo.getpixel(30),1
neo.pixel 30,neo.getpixel(29),1
neo.pixel 29,neo.getpixel(28),1
neo.pixel 28,neo.getpixel(27),1
neo.pixel 27,neo.getpixel(26),1
neo.pixel 26,neo.getpixel(25),1
neo.pixel 25,neo.getpixel(24),1
neo.pixel 24,neo.getpixel(23),1
neo.pixel 23,neo.getpixel(22),1
neo.pixel 22,neo.getpixel(21),1
neo.pixel 21,neo.getpixel(20),1
neo.pixel 20,neo.getpixel(19),1
neo.pixel 19,neo.getpixel(18),1
neo.pixel 18,neo.getpixel(17),1
neo.pixel 17,neo.getpixel(16),1
neo.pixel 16,neo.getpixel(15),1
neo.pixel 15,neo.getpixel(14),1
neo.pixel 14,neo.getpixel(13),1
neo.pixel 13,neo.getpixel(12),1
neo.pixel 12,neo.getpixel(11),1
neo.pixel 11,neo.getpixel(10),1
neo.pixel 10,neo.getpixel(9),1
neo.pixel 9,neo.getpixel(8),1
neo.pixel 8,neo.getpixel(7),1
neo.pixel 7,neo.getpixel(6),1
neo.pixel 6,neo.getpixel(5),1
neo.pixel 5,neo.getpixel(4),1
neo.pixel 4,neo.getpixel(3),1
neo.pixel 3,neo.getpixel(2),1
neo.pixel 2,neo.getpixel(1),1
neo.pixel 1,neo.getpixel(0),1
neo.pixel 0,0,1
return

fadeout:
for zz= 0 to 54
pc = neo.getpixel(zz)
pb=(pc and 255)*0.8:pc =pc /256:pg = (pc and 255)*0.8:pr = (pc /255)*0.8
neo.pixel zz,pr,pg,pb,1
next zz
return
