# SQL
SQL Portfolio
Create a Resale Shop Database and Stats

CREATE TABLE Ethical_Seconds (id INTEGER, Listing_Title TEXT, Type TEXT, Size INTEGER, Color INTEGER, Price INTEGER);

INSERT INTO Ethical_Seconds VALUES (1, 'Tommy_Hilfiger_Shoes', 'Shoes', 7, 'Blue', 10);
INSERT INTO Ethical_Seconds VALUES
(2, 'Dave_Billy_Shirt', 'Shirt', 5, 'Red', 8);
INSERT INTO Ethical_Seconds VALUES 
(3, 'Bo_Jim_Vest', 'Vest', 3, 'Yellow', 7);
INSERT INTO Ethical_Seconds VALUES 
(4, 'Tommy_Hat', 'Hat', 2, 'Red', 5);
INSERT INTO Ethical_Seconds VALUES 
(5, 'All_About', 'Dress', 3, 'Blue',20);
INSERT INTO Ethical_Seconds VALUES 
(6, 'Christmas_Santa', 'Vest', 5, 'White', 40);
INSERT INTO Ethical_Seconds VALUES 
(7, 'Antonio_Balente', 'Shoes', 5, 'Red', 5);
INSERT INTO Ethical_Seconds VALUES 
(8, 'TH_Dress', 'Dress', 7, 'Yellow', 7);
INSERT INTO Ethical_Seconds VALUES 
(9, 'Tom_Bahm', 'Shirt', 8, 'Red', 14);
INSERT INTO Ethical_Seconds VALUES 
(10, 'Rangers', 'Hat', 10, 'Green', 8);
INSERT INTO Ethical_Seconds VALUES 
(11, 'Weird_Hat', 'Hat', 4, 'Red', 10);
INSERT INTO Ethical_Seconds VALUES 
(12, 'funky_shoes', 'Shoes', 3, 'Blue', 2);
INSERT INTO Ethical_Seconds VALUES 
(13, 'Funky_Vest', 'Vest', 4, 'Black', 8);
INSERT INTO Ethical_Seconds VALUES 
(14, 'fun_shoes', 'Shoe', 5, 'Red', 24);
INSERT INTO Ethical_Seconds VALUES 
(15, 'dumb_shirt', 'Shirt', 6, 'Blue', 15);

Display the Database Ordered by Price
SELECT *
FROM Ethical_Seconds
ORDER BY price ASC;

Display Average Price of Store Items
SELECT AVG(price) AS 'Average Item Price'
FROM Ethical_Seconds;

Display Items Priced Below $10
SELECT *
FROM Ethical_Seconds
WHERE price <= 10;



