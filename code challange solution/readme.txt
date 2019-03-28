1) First unzip the ms3 project.

2) To run this program create table X 

3) CREATE TABLE `x` (
  `A` varchar(45) DEFAULT NULL,
  `B` varchar(45) DEFAULT NULL,
  `C` varchar(45) DEFAULT NULL,
  `D` varchar(45) DEFAULT NULL,
  `E` varchar(10000) DEFAULT NULL,
  `F` varchar(45) DEFAULT NULL,
  `G` varchar(45) DEFAULT NULL,
  `H` varchar(45) DEFAULT NULL,
  `I` varchar(45) DEFAULT NULL,
  `J` varchar(45) DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_0900_ai_ci

4) It will add bad data inside E:\\baddata.csv

5) It will generate log information into log file which is generated inside E:\\ms3Interview.log

6) Uncomment good file section. So you can get good data inside E:\\good.csv