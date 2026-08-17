CREATE TABLE student_marksheet (
    enrollment_no VARCHAR(20) PRIMARY KEY,
    student_name VARCHAR(50),
    branch VARCHAR(20),
    semester INT,
    maths INT,
    physics INT,
    chemistry INT,
    programming INT,
    electronics INT,
    total INT,
    percentage DECIMAL(5,2)
);

INSERT INTO student_marksheet
(enrollment_no, student_name, branch, semester, maths, physics, chemistry, programming, electronics, total, percentage)
VALUES
('ENR001', 'Amit', 'CSE', 2, 85, 80, 78, 92, 88, 423, 84.60),
('ENR002', 'Rahul', 'ECE', 2, 90, 85, 82, 88, 95, 440, 88.00),
('ENR003', 'Priya', 'IT', 2, 88, 91, 85, 94, 90, 448, 89.60),
('ENR004', 'Rohit', 'CSE', 2, 76, 72, 80, 85, 78, 391, 78.20),
('ENR005', 'Neha', 'ECE', 2, 95, 92, 89, 96, 94, 466, 93.20),
('ENR006', 'Arjun', 'CSE', 2, 82, 79, 75, 88, 85, 409, 81.80),
('ENR007', 'Sneha', 'IT', 2, 91, 87, 90, 93, 89, 450, 90.00),
('ENR008', 'Vikas', 'ECE', 2, 78, 80, 76, 82, 85, 401, 80.20),
('ENR009', 'Pooja', 'CSE', 2, 89, 86, 84, 91, 88, 438, 87.60),
('ENR010', 'Karan', 'IT', 2, 84, 81, 79, 87, 90, 421, 84.20);

SELECT * FROM student_marksheet;
