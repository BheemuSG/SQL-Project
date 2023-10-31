# SQL-Project
#Indian Squad For ICC World Cup 2023.

SQL> create table Indian_Squad_WC2023
(
Name_of_the_Player varchar(30),
Jersey_No Number(3), 
Role Varchar(18)
);

SQL> insert into Indian_Squad_WC2023 values('Rohit Sharma', 45, 'Batter' );
SQL> insert into Indian_Squad_WC2023 values('Virat Kohli', 18, 'Batter' );
SQL> insert into Indian_Squad_WC2023 values('Suryakumar Yadav', 69, 'Batter' );
SQL> insert into Indian_Squad_WC2023 values('Shubman Gill', 77, 'Batter' );
SQL> insert into Indian_Squad_WC2023 values('Shreyas Iyer', 96, 'Batter' );
SQL> insert into Indian_Squad_WC2023 values('Hardik Pandya', 33, 'Batting Allrounder' );
SQL> insert into Indian_Squad_WC2023 values('Ravindra Jadeja', 8, 'Bowling Allrounder' );
SQL> insert into Indian_Squad_WC2023 values('Ravichandran Ashwin', 99, 'Bowling Allrounder');
SQL> insert into Indian_Squad_WC2023 values('KL Rahul', 1, 'WK-Batter');
SQL> insert into Indian_Squad_WC2023 values('Ishan Kishan', 32, 'WK-Batter');
SQL> insert into Indian_Squad_WC2023 values('Jasprit Bumrah', 93, 'Bowler');
SQL> insert into Indian_Squad_WC2023 values('Shardul Thakur', 54, 'Bowler');
SQL> insert into Indian_Squad_WC2023 values('Mohammed Shami', 11, 'Bowler');
SQL> insert into Indian_Squad_WC2023 values('Mohammed Siraj', 13, 'Bowler');
SQL> insert into Indian_Squad_WC2023 values('Kuldeep Yadav', 23, 'Bowler');
SQL> update Indian_Squad_WC2023 set Name_of_The_Player='Rohit Sharma(C)' where Jersey_No=45;
SQL> update Indian_Squad_WC2023 set Name_of_The_Player='Hardik Pandya(VC)' where Jersey_No=33;
SQL>Commit;

#Rohit Sharma Batting Career
SQL> create table RohitSharma_Batting
(
Format varchar(5),
No_of_Matches Number(3),
No_of_Innings Number(3),
Not_Out Number(2),
Runs Number(5),
Highest_Score Number(3),
Ball_Faced Number(5)
);

SQL> insert into RohitSharma_Batting values('Test', 52, 88, 9, 3677, 212, 6534);
SQL> insert into RohitSharma_Batting values('ODI', 256, 248, 36, 10423, 264, 11403);
SQL> insert into RohitSharma_Batting values('T20I', 148, 140, 15, 3853, 118, 2767);
SQL> insert into RohitSharma_Batting values('IPL', 243, 238, 28, 6211, 109, 4776);


#Rohit Sharma Bowling Career
SQL> create table RohitSharma_Bowling
(
Format varchar(5),
No_of_Matches Number(3),
No_of_Innings Number(3),
Balls Number(5),
Runs Number(5),
Wickets Number(3),
BBI varchar(5),
BBM varchar(5)
);

SQL> insert into RohitSharma_Bowling values('Test', 52, 16, 383, 224, 2, '1/26', '1/35');
SQL> insert into RohitSharma_Bowling values('ODI', 256, 38, 593, 515, 8, '2/27', '2/27');
SQL> insert into RohitSharma_Bowling values('T20I', 148, 9, 68, 113, 1, '1/22', '1/22');
SQL> insert into RohitSharma_Bowling values('IPL', 243, 32, 339, 453, 15, '4/6', '4/6');

#Virat Kohli Batting Career
SQL> create table ViratKohli_Batting
(
Format varchar(5),
No_of_Matches Number(3),
No_of_Innings Number(3),
Not_Out Number(2),
Runs Number(5),
Highest_Score Number(3),
Ball_Faced Number(5)
);

SQL> insert into ViratKohli_Batting values('Test', 111, 187, 11, 8676, 254, 15708);
SQL> insert into ViratKohli_Batting values('ODI', 286, 274, 43, 23437, 183, 14341);
SQL> insert into ViratKohli_Batting values('T20I', 115, 107, 31, 4008, 122, 2905);
SQL> insert into ViratKohli_Batting values('IPL', 237, 229, 34, 7263, 113, 5586);

#Virat Kohli Bowling Career
SQL> create table ViratKohli_Bowling
(
Format varchar(5),
No_of_Matches Number(3),
No_of_Innings Number(3),
Balls Number(5),
Runs Number(5),
Wickets Number(3),
BBI varchar(5),
BBM varchar(5)
);

SQL> insert into ViratKohli_Bowling values('Test', 111, 11, 175, 84, 0, '0/0', '0/0');
SQL> insert into ViratKohli_Bowling values('ODI', 286, 49, 644, 667, 4, '1/15', '1/15');
SQL> insert into ViratKohli_Bowling values('T20I', 115, 13, 152, 204, 4, '1/13', '1/13');
SQL> insert into ViratKohli_Bowling values('IPL', 237, 26, 251, 368, 4, '2/25', '2/25');

#Surya Kuamr Yadav Batting Career
SQL> create table SuryakumarYadav_Batting
(
Format varchar(5),
No_of_Matches Number(3),
No_of_Innings Number(3),
Not_Out Number(2),
Runs Number(5),
Highest_Score Number(3),
Ball_Faced Number(5)
);

SQL> insert into SuryakumarYadav_Batting values('Test', 1, 1, 0, 8, 8, 20);
SQL> insert into SuryakumarYadav_Batting values('ODI', 31, 29, 4, 669, 72, 635);
SQL> insert into SuryakumarYadav_Batting values('T20I', 53, 50, 10, 1841, 117, 1066);
SQL> insert into SuryakumarYadav_Batting values('IPL', 139, 124, 22, 3249, 103, 2267);

#Surya Kuamr Yadav Bowling Career
SQL> create table SuryakumarYadav_Bowling
(
Format varchar(5),
No_of_Matches Number(3),
No_of_Innings Number(3),
Balls Number(5),
Runs Number(5),
Wickets Number(3),
BBI varchar(5),
BBM varchar(5)
);

SQL> insert into SuryakumarYadav_Bowling (Format, No_of_Matches) values('Test', 1);
SQL> insert into SuryakumarYadav_Bowling (Format, No_of_Matches) values('ODI', 31);
SQL> insert into SuryakumarYadav_Bowling (Format, No_of_Matches) values('T20I', 53);
SQL> insert into SuryakumarYadav_Bowling values('IPL', 139, 1, 6, 8, 0, '0/8', '0/8');

#Shubman Gill Batting Career
SQL> create table ShubmanGill_Batting 
(
Format varchar(5),
No_of_Matches Number(3),
No_of_Innings Number(3),
Not_Out Number(2),
Runs Number(5),
Highest_Score Number(3),
Ball_Faced Number(5)
);

SQL> insert into ShubmanGill_Batting values('Test', 18, 133, 3, 966, 128, 1638);
SQL> insert into ShubmanGill_Batting values('ODI', 38, 38, 4, 2012, 208, 1961);
SQL> insert into ShubmanGill_Batting values('T20I', 11, 11, 1, 304, 126, 207);
SQL> insert into ShubmanGill_Batting values('IPL', 91, 88, 14, 2790, 129, 2081);

#Shubman Gill Bowling Career
SQL> create table ShubmanGill_Bowling
(
Format varchar(5),
No_of_Matches Number(3),
No_of_Innings Number(3),
Balls Number(5),
Runs Number(5),
Wickets Number(3),
BBI varchar(5),
BBM varchar(5)
);

SQL> insert into ShubmanGill_Bowling values('Test', 18, 1, 7, 1, 0, '0/1', '0/1');
SQL> insert into ShubmanGill_Bowling (Format, No_of_Matches) values('ODI', 38);
SQL> insert into ShubmanGill_Bowling (Format, No_of_Matches) values('T20I', 11);
SQL> insert into ShubmanGill_Bowling (Format, No_of_Matches)  values('IPL', 91);


#Shreyas Iyer Batting Career
SQL> create table ShreyasIyer_Batting
(
Format varchar(5),
No_of_Matches Number(3),
No_of_Innings Number(3),
Not_Out Number(2),
Runs Number(5),
Highest_Score Number(3),
Ball_Faced Number(5)
);

SQL> insert into ShreyasIyer_Batting values('Test', 10, 16, 1, 666, 105, 1012);
SQL> insert into ShreyasIyer_Batting values('ODI', 52, 47, 5, 1931, 113, 1982);
SQL> insert into ShreyasIyer_Batting values('T20I', 49, 45, 11, 1043, 74, 767);
SQL> insert into ShreyasIyer_Batting values('IPL', 101, 101, 13, 2776, 96, 2214);

#Shreyas Iyer Bowling Career
SQL> create table ShreyasIyer_Bowling
(
Format varchar(5),
No_of_Matches Number(3),
No_of_Innings Number(3),
Balls Number(5),
Runs Number(5),
Wickets Number(3),
BBI varchar(5),
BBM varchar(5)
);

SQL> insert into ShreyasIyer_Bowling values('Test', 10, 1, 6, 2, 0, '0/2', '0/2');
SQL> insert into ShreyasIyer_Bowling values('ODI', 52, 5, 37, 39, 0, '0/1', '0/1');
SQL> insert into ShreyasIyer_Bowling values('T20I', 49, 1, 2, 2, 0, '0/2', '0/2');
SQL> insert into ShreyasIyer_Bowling values('IPL', 101, 1, 6, 7, 0, '0/7', '0/7');

#Hardik Pandya Batting Career
SQL> create table HardikPandya_Batting 
(
Format varchar(5),
No_of_Matches Number(3),
No_of_Innings Number(3),
Not_Out Number(2),
Runs Number(5),
Highest_Score Number(3),
Ball_Faced Number(5)
);

SQL> insert into HardikPandya_Batting values('Test', 11, 18, 1, 532, 108, 720);
SQL> insert into HardikPandya_Batting values('ODI', 86, 61, 9, 1769, 92, 1603);
SQL> insert into HardikPandya_Batting values('T20I', 92, 71, 18, 1348, 71, 964);
SQL> insert into HardikPandya_Batting values('IPL', 123, 115, 39, 2309, 91, 1583);

#Hardik Pandya Bowling Career
SQL> create table HardikPandya_Bowling 
(
Format varchar(5),
No_of_Matches Number(3),
No_of_Innings Number(3),
Balls Number(5),
Runs Number(5),
Wickets Number(3),
BBI varchar(5),
BBM varchar(5)
);

SQL> insert into HardikPandya_Bowling values('Test', 11, 19, 937, 528, 17, '5/28', '6/50');
SQL> insert into HardikPandya_Bowling values('ODI', 86, 80, 3199, 2960, 84, '4/24', '4/24');
SQL> insert into HardikPandya_Bowling values('T20I', 92, 81, 1433, 1950, 73, '4/16', '4/16');
SQL> insert into HardikPandya_Bowling values('IPL', 123, 81, 1202, 1763, 53, '3/17', '3/17');

#Ravindra Jadeja Batting Career
SQL> create table RavindraJadeja_Batting 
(
Format varchar(5),
No_of_Matches Number(3),
No_of_Innings Number(3),
Not_Out Number(2),
Runs Number(5),
Highest_Score Number(3),
Ball_Faced Number(5)
);

SQL> insert into RavindraJadeja_Batting values('Test', 67, 98, 21, 2804, 175, 4915);
SQL> insert into RavindraJadeja_Batting values('ODI', 191, 128, 46, 2675, 87, 3166);
SQL> insert into RavindraJadeja_Batting values('T20I', 64, 34, 15, 457, 46, 367);
SQL> insert into RavindraJadeja_Batting values('IPL', 226, 173, 71, 2692, 62, 2093);

#Ravindra Jadeja Bowling Career
SQL> create table RavindraJadeja_Bowling
(
Format varchar(5),
No_of_Matches Number(3),
No_of_Innings Number(3),
Balls Number(5),
Runs Number(5),
Wickets Number(3),
BBI varchar(5),
BBM varchar(5)
);

#Changing BBM datatype size.
SQL> Alter table RavindraJadeja_Bowling modify BBM varchar(6);
SQL> insert into RavindraJadeja_Bowling values('Test', 67, 128, 16354, 6620, 275, '7/42', '10/110');
SQL> insert into RavindraJadeja_Bowling values('ODI', 191, 183, 9476, 7728, 211, '5/36', '5/36');
SQL> insert into RavindraJadeja_Bowling values('T20I', 64, 62, 1237, 1453, 51, '3/15', '3/15');
SQL> insert into RavindraJadeja_Bowling values('IPL', 226, 197, 3547, 4495, 152, '5/16', '5/16');

#Ravichandran Ashwin Batting Career
SQL> create table RavichandranAshwin_Batting 
(
Format varchar(5),
No_of_Matches Number(3),
No_of_Innings Number(3),
Not_Out Number(2),
Runs Number(5),
Highest_Score Number(3),
Ball_Faced Number(5)
);

SQL> insert into RavichandranAshwin_Batting values('Test', 94, 132, 15, 3185, 124, 5832);
SQL> insert into RavichandranAshwin_Batting values('ODI', 116, 63, 20, 707, 65, 813);
SQL> insert into RavichandranAshwin_Batting values('T20I', 65, 19, 12, 184, 31, 160);
SQL> insert into RavichandranAshwin_Batting values('IPL', 197, 85, 31, 714, 50, 601);

#Ravichandran Ashwin Bowling Career
SQL> create table RavichandranAshwin_Bowling 
(
Format varchar(5),
No_of_Matches Number(3),
No_of_Innings Number(3),
Balls Number(5),
Runs Number(5),
Wickets Number(3),
BBI varchar(5),
BBM varchar(5)
);

#Changing BBM datatype size.
SQL> Alter table RavichandranAshwin_Bowling modify BBM varchar(6);
SQL> insert into RavichandranAshwin_Bowling values('Test', 94, 178, 25113, 11569, 489, '7/59', '13/140');
SQL> insert into RavichandranAshwin_Bowling values('ODI', 116, 114, 6303, 5180, 156, '4/25', '4/25');
SQL> insert into RavichandranAshwin_Bowling values('T20I', 65, 65, 1452, 1672, 72, '4/8', '4/8');
SQL> insert into RavichandranAshwin_Bowling values('IPL', 197, 194, 4194, 4902, 171, '4/34', '4/34');

#KL Rahul Batting Career
SQL> create table KLRahul_Batting 
(
Format varchar(5),
No_of_Matches Number(3),
No_of_Innings Number(3),
Not_Out Number(2),
Runs Number(5),
Highest_Score Number(3),
Ball_Faced Number(5)
);

SQL> insert into KLRahul_Batting values('Test', 47, 81, 2, 2642, 199, 5116);
SQL> insert into KLRahul_Batting values('ODI', 67, 63, 13, 2507, 112, 2885);
SQL> insert into KLRahul_Batting values('T20I', 72, 68, 8, 2265, 110, 1628);
SQL> insert into KLRahul_Batting values('IPL', 118, 109, 20, 4163, 132, 3097);

#KL Rahul Bowling Career
SQL> create table KLRahul_Bowling
(
Format varchar(5),
No_of_Matches Number(3),
No_of_Innings Number(3),
Balls Number(5),
Runs Number(5),
Wickets Number(3),
BBI varchar(5),
BBM varchar(5)
);

SQL> insert into KLRahul_Bowling (Format, No_of_Matches) values('Test', 47);
SQL> insert into KLRahul_Bowling (Format, No_of_Matches) values('ODI', 67);
SQL> insert into KLRahul_Bowling (Format, No_of_Matches) values('T20I', 72);
SQL> insert into KLRahul_Bowling (Format, No_of_Matches) values('IPL', 197);

#Ishan Kishan Batting Career
SQL> create table IshanKishan_Batting
(
Format varchar(5),
No_of_Matches Number(3),
No_of_Innings Number(3),
Not_Out Number(2),
Runs Number(5),
Highest_Score Number(3),
Ball_Faced Number(5)
);

SQL> insert into IshanKishan_Batting values('Test', 2, 3, 2, 78, 52, 91);
SQL> insert into IshanKishan_Batting values('ODI', 27, 24, 2, 933, 210, 913);
SQL> insert into IshanKishan_Batting values('T20I', 29, 29, 1, 686, 89, 564);
SQL> insert into IshanKishan_Batting values('IPL', 91, 85, 6, 2324, 99, 1731);

#Ishan Kishan Bowling Career
SQL> create table IshanKishan_Bowling
(
Format varchar(5),
No_of_Matches Number(3),
No_of_Innings Number(3),
Balls Number(5),
Runs Number(5),
Wickets Number(3),
BBI varchar(5),
BBM varchar(5)
);

SQL> insert into IshanKishan_Bowling (Format, No_of_Matches) values('Test', 2);
SQL> insert into IshanKishan_Bowling (Format, No_of_Matches) values('ODI', 27);
SQL> insert into IshanKishan_Bowling (Format, No_of_Matches) values('T20I', 29);
SQL> insert into IshanKishan_Bowling (Format, No_of_Matches) values('IPL', 91);

#Jasprit Bumrah Batting Career
SQL> create table JaspritBumrah_Batting 
(
Format varchar(5),
No_of_Matches Number(3),
No_of_Innings Number(3),
Not_Out Number(2),
Runs Number(5),
Highest_Score Number(3),
Ball_Faced Number(5)
);

SQL> insert into JaspritBumrah_Batting values('Test', 30, 46, 17, 212, 34, 455);
SQL> insert into JaspritBumrah_Batting values('ODI', 84, 24, 13, 89, 16, 155);
SQL> insert into JaspritBumrah_Batting values('T20I', 62, 7, 5, 8, 7, 13);
SQL> insert into JaspritBumrah_Batting values('IPL', 120, 26, 19, 56, 16, 66);

#Jasprit Bumrah Bowling Career
SQL> create table JaspritBumrah_Bowling 
(
Format varchar(5),
No_of_Matches Number(3),
No_of_Innings Number(3),
Balls Number(5),
Runs Number(5),
Wickets Number(3),
BBI varchar(5),
BBM varchar(5)
);

SQL> insert into JaspritBumrah_Bowling values('Test', 30, 58, 6268, 2815, 128, '6/27', '9/86');
SQL> insert into JaspritBumrah_Bowling values('ODI', 84, 83, 4329, 3326, 142, '6/19', '6/19');
SQL> insert into JaspritBumrah_Bowling values('T20I', 62, 61, 1331, 1455, 74, '3/11', '3/11');
SQL> insert into JaspritBumrah_Bowling values('IPL', 120, 120, 2742, 3380, 145, '5/10', '5/10');

#Shardul Thakur Batting Career
SQL> create table ShardulThakur_Batting 
(
Format varchar(5),
No_of_Matches Number(3),
No_of_Innings Number(3),
Not_Out Number(2),
Runs Number(5),
Highest_Score Number(3),
Ball_Faced Number(5)
);

SQL> insert into ShardulThakur_Batting values('Test', 10, 16, 1, 305, 67, 481);
SQL> insert into ShardulThakur_Batting values('ODI', 47, 25, 6, 329, 50, 313);
SQL> insert into ShardulThakur_Batting values('T20I', 25, 6, 3, 69, 22, 38);
SQL> insert into ShardulThakur_Batting values('IPL', 86, 34, 10, 286, 68, 204);

#Shardul Thakur Bowling Career
SQL> create table ShardulThakur_Bowling 
(
Format varchar(5),
No_of_Matches Number(3),
No_of_Innings Number(3),
Balls Number(5),
Runs Number(5),
Wickets Number(3),
BBI varchar(5),
BBM varchar(5)
);

SQL> insert into ShardulThakur_Bowling values('Test', 10, 18, 1335, 779, 30, '7/61', '8/108');
SQL> insert into ShardulThakur_Bowling values('ODI', 47, 46, 1940, 2014, 65, '4/37', '4/37');
SQL> insert into ShardulThakur_Bowling values('T20I', 25, 24, 506, 772, 33, '4/27', '4/27');
SQL> insert into ShardulThakur_Bowling values('IPL', 86, 83, 1676, 2560, 89, '4/36', '4/36');

#Mohammed Shami Batting Career
SQL> create table MohammedShami_Batting 
(
Format varchar(5),
No_of_Matches Number(3),
No_of_Innings Number(3),
Not_Out Number(2),
Runs Number(5),
Highest_Score Number(3),
Ball_Faced Number(5)
);

SQL> insert into MohammedShami_Batting values('Test', 64, 89, 26, 750, 56, 1005);
SQL> insert into MohammedShami_Batting values('ODI', 96, 46, 20, 212, 25, 251);
SQL> insert into MohammedShami_Batting values('T20I', 23, 3, 2, 0, 0, 2);
SQL> insert into MohammedShami_Batting values('IPL', 110, 25, 12, 74, 21, 79);


#Mohammed Shami Bowling Career
SQL> create table MohammedShami_Bowling 
(
Format varchar(5),
No_of_Matches Number(3),
No_of_Innings Number(3),
Balls Number(5),
Runs Number(5),
Wickets Number(3),
BBI varchar(5),
BBM varchar(5)
);

SQL> insert into MohammedShami_Bowling values('Test', 64, 122, 11515, 6346, 229, '6/56', '9/118');
SQL> insert into MohammedShami_Bowling values('ODI', 96, 95, 4789, 4431, 179, '5/51', '5/51');
SQL> insert into MohammedShami_Bowling values('T20I', 23, 23, 477, 711, 24, '3/15', '3/15');
SQL> insert into MohammedShami_Bowling values('IPL', 110, 110, 2426, 3411, 127, '4/11', '4/11');

#Mohammed Siraj Batting Career
SQL> create table MohammedSiraj_Batting 
(
Format varchar(5),
No_of_Matches Number(3),
No_of_Innings Number(3),
Not_Out Number(2),
Runs Number(5),
Highest_Score Number(3),
Ball_Faced Number(5)
);

SQL> insert into MohammedSiraj_Batting values('Test', 21, 28, 11, 80, 16, 190);
SQL> insert into MohammedSiraj_Batting values('ODI', 35, 13, 7, 37, 9, 92);
SQL> insert into MohammedSiraj_Batting values('T20I', 8, 1, 0, 5, 5, 7);
SQL> insert into MohammedSiraj_Batting values('IPL', 79, 22, 14, 97, 14, 111);

#Mohammed Siraj Bowling Career
SQL> create table MohammedSiraj_Bowling 
(
Format varchar(5),
No_of_Matches Number(3),
No_of_Innings Number(3),
Balls Number(5),
Runs Number(5),
Wickets Number(3),
BBI varchar(5),
BBM varchar(5)
);

SQL> insert into MohammedSiraj_Bowling values('Test', 21, 39, 3275, 1784, 59, '5/60', '8/126');
SQL> insert into MohammedSiraj_Bowling values('ODI', 35, 34, 1591, 1339, 60, '6/21', '6/21');
SQL> insert into MohammedSiraj_Bowling values('T20I', 8, 8, 192, 294, 11, '4/17', '4/17');
SQL> insert into MohammedSiraj_Bowling values('IPL', 79, 79, 1634, 2326, 78, '4/21', '4/21');

#Kuldeep Yadav Batting Career
SQL> create table KuldeepYadav_Batting 
(
Format varchar(5),
No_of_Matches Number(3),
No_of_Innings Number(3),
Not_Out Number(2),
Runs Number(5),
Highest_Score Number(3),
Ball_Faced Number(5)
);

SQL> insert into KuldeepYadav_Batting values('Test', 8, 9, 0, 94, 40, 299);
SQL> insert into KuldeepYadav_Batting values('ODI', 96, 35, 18, 179, 19, 315);
SQL> insert into KuldeepYadav_Batting values('T20I', 32, 7, 3, 46, 23, 59);
SQL> insert into KuldeepYadav_Batting values('IPL', 73, 28, 19, 136, 16, 175);

#Kuldeep Yadav Bowling Career
SQL> create table KuldeepYadav_Bowling 
(
Format varchar(5),
No_of_Matches Number(3),
No_of_Innings Number(3),
Balls Number(5),
Runs Number(5),
Wickets Number(3),
BBI varchar(5),
BBM varchar(5)
);
SQL> insert into KuldeepYadav_Bowling values('Test', 8, 14, 1279, 733, 34, '5/40', '8/113');
SQL> insert into KuldeepYadav_Bowling values('ODI', 93, 93, 4903, 4156, 162, '6/25', '6/25');
SQL> insert into KuldeepYadav_Bowling values('T20I', 32, 31, 687, 758, 52, '5/24', '5/24');
SQL> insert into KuldeepYadav_Bowling values('IPL', 73, 71, 1488, 2016, 71, '4/14', '4/14');
SQL>Commit;

#Updating date 
SQL> update RohitSharma_Batting set No_of_Matches=257, No_of_Innings=249, Runs=10510, Ball_Faced=11504 where Format='ODI';
SQL> update RohitSharma_Bowling set No_of_Matches=257 where Format='ODI';
SQL> update ShubmanGill_Batting set No_of_Matches=39, No_of_Innings=39, Runs=2021, Ball_Faced=1974 where Format='ODI';
SQL> update ShubmanGill_Bowling set No_of_Matches=39 where Format='ODI';
SQL> update ViratKohli_Batting set No_of_Matches=287, No_of_Innings=275, Runs=13437, Ball_Faced=14350 where Format='ODI';
SQL> update ViratKohli_Bowling set No_of_Matches=287 where Format='ODI';
SQL> update ShreyasIyer_Batting set No_of_Matches=53, No_of_Innings=48, Runs=1935, Ball_Faced=1998 where Format='ODI';
SQL> update ShreyasIyer_Bowling set No_of_Matches=53 where Format='ODI';
SQL> update KLRahul_Batting set No_of_Matches=67, No_of_Innings=63, Runs=2507, Ball_Faced=2885 where Format='ODI';
SQL> update KLRahul_Bowling set No_of_Matches=67 where Format='ODI';
SQL> update SuryakumarYadav_Batting set No_of_Matches=32, No_of_Innings=30, Runs=718, Ball_Faced=682 where Format='ODI';
SQL> update SuryakumarYadav_Bowling set No_of_Matches=32 where Format='ODI';
SQL> update RavindraJadeja_Batting set No_of_Matches=192, No_of_Innings=129, Runs=2683, Ball_Faced=3179 where Format='ODI';
SQL> update RavindraJadeja_Bowling set No_of_Matches=192, No_of_Innings=184, Balls=9518, Runs=7744, Wickets=212 where Format='ODI';
SQL> update MohammedShami_Batting set No_of_Matches=96, No_of_Innings=46, Runs=212, Ball_Faced=251 where Format='ODI';
SQL> update MohammedShami_Bowling set No_of_Matches=96, No_of_Innings=95, Balls=4794, Runs=4437, Wickets=180 where Format='ODI';
SQL> update JaspritBumrah_Batting set No_of_Matches=84, No_of_Innings=24, Runs=89, Ball_Faced=155 where Format='ODI';
SQL> update JaspritBumrah_Bowling set No_of_Matches=84, No_of_Innings=83, Balls=4352, Runs=3347, Wickets=143 where Format='ODI';
SQL> update KuldeepYadav_Batting set No_of_Matches=96, No_of_Innings=35, Runs=179, Ball_Faced=315 where Format='ODI';
SQL> update KuldeepYadav_Bowling set No_of_Matches=96, No_of_Innings=93, Balls=4903, Runs=4156, Wickets=162 where Format='ODI';
SQL> update MohammedSiraj_Batting set No_of_Matches=36 where Format='ODI';
SQL> update MohammedSiraj_Bowling set No_of_Matches=36, No_of_Innings=35, Balls=1627, Runs=1372 where Format='ODI';
SQL>Commit;

# Batting average of Batters
SQL> select (Runs/(No_of_Innings-Not_Out)) as Batting_Average from RohitSharma_Batting;
SQL> select (Runs/(No_of_Innings-Not_Out)) as Batting_Average from ShubmanGill_Batting;
SQL> select (Runs/(No_of_Innings-Not_Out)) as Batting_Average from ViratKohil_Batting;
SQL> select (Runs/(No_of_Innings-Not_Out)) as Batting_Average from ShreyasIyer_Batting;
SQL> select (Runs/(No_of_Innings-Not_Out)) as Batting_Average from KLRahul_Batting;
SQL> select (Runs/(No_of_Innings-Not_Out)) as Batting_Average from SuryakumarYadav_Batting;
SQL> select (Runs/(No_of_Innings-Not_Out)) as Batting_Average from RavindraJadeja_Batting;
SQL> select (Runs/(No_of_Innings-Not_Out)) as Batting_Average from IshanKishan_Batting;
SQL> select (Runs/(No_of_Innings-Not_Out)) as Batting_Average from HardikPandya_Batting;
SQL> select (Runs/(No_of_Innings-Not_Out)) as Batting_Average from RavichandranAshwin_Batting;

# Batting Strike Rate of Batters
SQL> select ((Runs/Ball_Faced)*100) as Strike_Rate from RohitSharma_Batting;
SQL> select ((Runs/Ball_Faced)*100) as Strike_Rate from ShubmanGill_Batting;
SQL> select ((Runs/Ball_Faced)*100) as Strike_Rate from ViratKohil_Batting;
SQL> select ((Runs/Ball_Faced)*100) as Strike_Rate from ShreyasIyer_Batting;
SQL> select ((Runs/Ball_Faced)*100) as Strike_Rate from KLRahul_Batting;
SQL> select ((Runs/Ball_Faced)*100) as Strike_Rate from SuryakumarYadav_Batting;
SQL> select ((Runs/Ball_Faced)*100) as Strike_Rate from RavindraJadeja_Batting;
SQL> select ((Runs/Ball_Faced)*100) as Strike_Rate from HardikPandya_Batting;
SQL> select ((Runs/Ball_Faced)*100) as Strike_Rate from IshanKishan_Batting;
SQL> select ((Runs/Ball_Faced)*100) as Strike_Rate from RavichandranAshwin_Batting;

# Bowling average of Bowler.
SQL> select (Runs/Wickets) as Bowling_Average from JaspritBumrah_Bowling;
SQL> select (Runs/Wickets) as Bowling_Average from MohammedShami_Bowling;
SQL> select (Runs/Wickets) as Bowling_Average from MohammedSiraj_Bowling;
SQL> select (Runs/Wickets) as Bowling_Average from KuldeepYadav_Bowling;
SQL> select (Runs/Wickets) as Bowling_Average from RavindraJadeja_Bowling;
SQL> select (Runs/Wickets) as Bowling_Average from RavichandranAshwin_Bowling;
SQL> select (Runs/Wickets) as Bowling_Average from HardikPandya_Bowling;
SQL> select (Runs/Wickets) as Bowling_Average from ShardulThakur_Bowling;

# Bowling Economic of Bowler.
SQL> select (Runs/(Balls/6)) as Bowling_Average from JaspritBumrah_Bowling;
SQL> select (Runs/(Balls/6)) as Bowling_Average from MohammedShami_Bowling;
SQL> select (Runs/(Balls/6)) as Bowling_Average from MohammedSiraj_Bowling;
SQL> select (Runs/(Balls/6)) as Bowling_Average from KuldeepYadav_Bowling;
SQL> select (Runs/(Balls/6)) as Bowling_Average from RavindraJadeja_Bowling;
SQL> select (Runs/(Balls/6)) as Bowling_Average from RavichandranAshwin_Bowling;
SQL> select (Runs/(Balls/6)) as Bowling_Average from HardikPandya_Bowling;
SQL> select (Runs/(Balls/6)) as Bowling_Average from ShardulThakur_Bowling;

#Total Runs of Batter.
SQL> select ((Runs/Ball_Faced)*100) as Strike_Rate from RohitSharma_Batting;

