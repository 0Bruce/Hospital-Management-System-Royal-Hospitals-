# Hospital-Management-System-Royal-Hospitals-

Domain Description

This an application to manage the information in a Hospital. 
The description is as follows: 
The hospital has employees, patients and medicines and rooms. An employee can be of the type doctor, nurse or receptionist. 
There are no other employees other than these 3 categories. 
A doctor attends a patient and he/she is given some medicines and assigned a room. 
Each room can be assigned for none, one or two patients. 
A doctor can attend at most 350 patients per month. 
A nurse governs the rooms. Each nurse can govern at most 300 rooms per month. 
A receptionist maintains the records of each and every patient. 
Each receptionist can maintain the record of at most 450 patients per month.

Each medicine has Mname, Mquantity and Mprice.

Each employee has Eid, Esal, Ejob, Ename, Eaddress and Econtact.

Each doctor has Dspec as special attribute.

Each nurse has age as special attribute.

Each receptionist has experience as special attribute.

Each patient has Pid, Pname, Paddress, Pcontact, PDOA(if he had attended the hospital before or it will be NULL).

Each room has Roomno, Rtype and Rprice.

Each record has Recno and BillAmt.

Constraints

Each patient can be billed for at most 10 medicines.

Each patient is assigned with 1 doctor, 1 nurse and 1 room as per the hospital rules and his/her details are maintained in record.

Each doctor can attend at most 350 patients per month.

Each nurse can govern at most 300 rooms per month.

Each receptionist can maintain the record of at most 450 patients per month.

Each room can have none, one or two patients in it.

We store only the data of the current month.
