CREATE TABLE Patients (
    PatientID INT PRIMARY KEY,
    Name VARCHAR(50),
    PhoneNumber VARCHAR(15),
    NationalNumber VARCHAR(20),
    Disease VARCHAR(30)
);
INSERT INTO Patients (PatientID, Name, PhoneNumber, NationalNumber, Disease) VALUES
(1, 'Mohamed Helmy', '105634230', '435454656867', 'Diabetes'),
(2, 'Dina Yousef', '115566883', '45877986545', 'Hypertension'),
(3, 'Ahmed Hany', '100214638', '354324554578', 'Asthma'),
(4, 'Marwan Ali', '123456490', '45467657543', 'Tuberculosis'),
(5, 'Kareem Adel', '116937399', '35786865433', 'Cancer'),
(6, 'Adham Hazem', '1010908705', '32435456789', 'Cancer'),
(7, 'Laila Adel', '100540460', '98765432187', 'Pneumonia'),
(8, 'Yara Hany', '115778809', '23456786543', 'Epilepsy'),
(9, 'Eman Abdallah', '126779845', '876543323456', 'Malaria'),
(10, 'Alaa Elsayed', '124676875', '55582252522', 'Hepatitis'); 

CREATE TABLE Medications (
    MedicineName VARCHAR(50) PRIMARY KEY,
    Stock INT,
    ProdDate DATE,
    ExpDate DATE,
    Price INT);
INSERT INTO Medications (MedicineName, Stock, ProdDate, ExpDate, Price) VALUES
('Thiopental', 2000, '2023-01-01', '2023-01-01', 60000),
('Aspirin', 1500, '2023-05-04', '2023-05-04', 30000),
('BCG', 1160, '2023-08-18', '2023-08-18', 45000),
('Aldesleukin', 1000, '2024-08-09', '2024-08-09', 50000),
('Cisplatin', 2000, '2024-04-14', '2024-04-14', 55000),
('Metformin', NULL, NULL, NULL, NULL),
('Interferon', NULL, NULL, NULL, NULL),
('Quinine', 3000, '2022-08-29', '2022-08-29', 30000),
('Epinephrine', 4000, '2023-01-04', '2023-01-04', 80000),
('Rifampin', 1000, '2023-08-03', '2023-08-03', 20000),
('Lisinopril', 2500, '2023-08-02', '2023-08-02', 60000),
('Ribavirin', NULL, NULL, NULL, NULL),
('Tenofovir', 3500, '2022-12-12', '2022-12-12', 65000),
('Sofosbuvir', 4000, '2023-09-07', '2023-09-07', 88000),
('Carbamazepine', NULL, NULL, NULL, NULL),
('Paracetamol', 3500, '2024-05-05', '2024-05-05', 77000),
('Furosemide', 1000, '2023-05-01', '2023-05-01', 50000),
('Cetirizine', 3500, '2024-09-30', '2024-09-30', 60000),
('Diclofenac', 4000, '2024-09-21', '2024-09-21', 90000);

CREATE TABLE Visitors (
    VisitorID INT PRIMARY KEY,
    VisitDate DATE,
    VisitTime VARCHAR(10),
    NationalNum VARCHAR(20),
    PhoneNum VARCHAR(15));

INSERT INTO Visitors (VisitorID, VisitDate, VisitTime, NationalNum, PhoneNum) VALUES
(200, '2023-02-16', '2am', '30205082457981', '1210666243'),
(201, '2023-11-10', '5pm', '30003021456789', '1250306451'),
(202, '2023-01-02', '6am', '30111091234567', '1002886269'),
(203, '2023-06-23', '9pm', '29908061456923', '1256731882'),
(204, '2023-04-15', '10pm', '30207032457892', '1155896266'),
(205, '2023-06-06', '1am', '30006021456843', '1045203598'),
(206, '2023-02-17', '2pm', '30102082457942', '1258798746'),
(207, '2024-02-19', '6am', '29909011456738', '1078952655'),
(208, '2023-03-05', '11pm', '30204071457894', '1264978254'),
(209, '2024-02-03', '9pm', '30112012456789', '1198797985'),
(210, '2023-12-12', '4am', '28101234567891', '1245514597'),
(211, '2023-07-07', '5am', '29506789012345', '1548987985'),
(212, '2023-06-12', '1am', '30712345678901', '1589958787'),
(213, '2024-08-19', '3pm', '31823456789012', '1089484454');

CREATE TABLE Staff (
    StaffID INT PRIMARY KEY,
    Name VARCHAR(50),
    Job VARCHAR(30),
    PhoneNumber VARCHAR(15),
    NationalNumber VARCHAR(20),
    Salary INT);

INSERT INTO Staff (StaffID, Name, Job, PhoneNumber, NationalNumber, Salary) VALUES
(100, 'Malak Mahmoud', 'Doctor', '1017091106', '30101234567890', 50000),
(101, 'Rowida Mohamed', 'Nurse', '1020029700', '30102234567891', 25000),
(102, 'Mina Ed', 'Nurse', '1238567454', '30103234567892', 25000),
(103, 'Mostafa Fathy', 'Doctor', '1229594334', '30104234567893', 55000),
(104, 'Menna Mohamed', 'Nurse', '1278692280', '30105234567894', 25000),
(105, 'Maivel Maikel', 'Nurse', '1002800267', '30106234567895', 25000),
(106, 'Mariam Mohamed', 'Doctor', '1257973874', '30107234567896', 50000),
(107, 'Nour Heredan', 'Receptionist', '1002146375', '30108234567897', 15000),
(108, 'Ahmed Ali', 'Technician', '1012345678', '30109234567898', 20000),
(109, 'Salma Youssef', 'Pharmacist', '1234567890', '30110234567899', 35000),
(110, 'Hany Samir', 'Surgeon', '1123456789', '30111234567900', 70000),
(111, 'Yasmin Omar', 'Administrator', '1056789123', '30112234567901', 40000),
(112, 'Karim Hassan', 'Lab Technician', '10056789432', '30113234567902', 25000),
(113, 'Sarah Ahmed', 'Radiologist', '1134567812', '30114234567903', 48000),
(114, 'Omar Tarek', 'IT Specialist', '1098765432', '30115234567904', 30000);

CREATE TABLE Billings (
    Room VARCHAR(20) PRIMARY KEY,
    AppointmentDate DATE,
    DischargeDate DATE,
    Amount INT,
    Status VARCHAR(20));

INSERT INTO Billings (Room, AppointmentDate, DischargeDate, Amount, Status) VALUES
('room 1', '2023-04-27', '2023-05-01', 3000, 'paid'),
('room 2', '2023-06-03', '2023-06-12', 1000, 'paid'),
('room 3', '2023-08-05', '2023-08-19', 6000, NULL),
('room 4', '2024-01-29', '2024-02-05', 7000, NULL),
('room 5', '2024-02-04', '2024-02-15', 5500, 'paid'),
('room 6', '2024-03-07', '2024-03-11', 4500, NULL),
('room 7', '2024-04-09', '2024-04-20', 3000, 'paid'),
('room 8', '2025-04-25', '2025-05-03', 4000, NULL),
('room 9', '2024-05-10', '2024-05-17', 5000, 'paid'),
('room 10', '2024-08-12', '2024-08-25', 1200, 'paid');

