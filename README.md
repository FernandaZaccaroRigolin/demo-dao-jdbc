# demo-dao-jdbc
Demo DAO basico utilizando JDBC

***********************

=== TEST 1: findById =======
Department [id=1, name=Computers]

=== TEST 2: findAll =======
Department [id=4, name=Books]
Department [id=1, name=Computers]
Department [id=2, name=Electronics]
Department [id=3, name=Fashion]

=== TEST 3: insert =======
Inserted! New id: 5

=== TEST 4: update =======
Update completed

=== TEST 5: delete =======
Enter id for delete test: 5
Delete completed

***********************
=== TEST 1: seller findById =====
Seller [id=3, name=Alex Grey, email=alex@gmail.com, birthDate=1988-01-15, baseSalary=2200.0, department=Department [id=1, name=Food]]

=== TEST 2: seller findByDepartment =====
Seller [id=6, name=Alex Pink, email=bob@gmail.com, birthDate=1997-03-04, baseSalary=3200.0, department=Department [id=2, name=Electronics]]
Seller [id=8, name=Greg, email=greg@gmail.com, birthDate=2023-06-06, baseSalary=4000.0, department=Department [id=2, name=Electronics]]
Seller [id=9, name=Greg, email=greg@gmail.com, birthDate=2023-06-06, baseSalary=4000.0, department=Department [id=2, name=Electronics]]
Seller [id=2, name=Maria Green, email=maria@gmail.com, birthDate=1979-12-31, baseSalary=3700.0, department=Department [id=2, name=Electronics]]

=== TEST 3: seller findAll =====
Seller [id=3, name=Alex Grey, email=alex@gmail.com, birthDate=1988-01-15, baseSalary=2200.0, department=Department [id=1, name=Food]]
Seller [id=6, name=Alex Pink, email=bob@gmail.com, birthDate=1997-03-04, baseSalary=3200.0, department=Department [id=2, name=Electronics]]
Seller [id=7, name=Carl Purple, email=carl@gmail.com, birthDate=1985-04-22, baseSalary=3000.0, department=Department [id=4, name=Books]]
Seller [id=5, name=Donald Blue, email=donald@gmail.com, birthDate=2000-01-09, baseSalary=4000.0, department=Department [id=3, name=Fashion]]
Seller [id=8, name=Greg, email=greg@gmail.com, birthDate=2023-06-06, baseSalary=4000.0, department=Department [id=2, name=Electronics]]
Seller [id=9, name=Greg, email=greg@gmail.com, birthDate=2023-06-06, baseSalary=4000.0, department=Department [id=2, name=Electronics]]
Seller [id=2, name=Maria Green, email=maria@gmail.com, birthDate=1979-12-31, baseSalary=3700.0, department=Department [id=2, name=Electronics]]
Seller [id=4, name=Martha Red, email=martha@gmail.com, birthDate=1993-11-30, baseSalary=3000.0, department=Department [id=4, name=Books]]
Seller [id=1, name=Martha Waine, email=bob@gmail.com, birthDate=1998-04-21, baseSalary=1000.0, department=Department [id=1, name=Food]]

=== TEST 4: seller insert =====
Inserted! New id = null

=== TEST 5: seller update =====
Update completed

=== TEST 6: seller delete =====
Enter id for delete test: 
5
Delete completed

***********************


