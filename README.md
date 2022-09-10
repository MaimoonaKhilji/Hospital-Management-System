# Hospital-Management-System
### Database Project in MS-Access

Explanation of Enhanced ERD Model of Project:
<pre>
	The below EERD is of Hospital Management System. From EERD, it is concluded that in Hospitals, There are receptionist and 
  doctors. Receptionist can be one or many, they are responsible for recording the data of many patients. So there One to Many 
  relationship between receptionist and patients. The relation between Hospital and Doctors is one to many because one hospital 
  has many doctors. The Relation between Doctors and Patients is many to many because many patients take appointments of many 
  doctors. In other words, one patient can take appointment of one or many doctors. 
(For example: A patient with skin infection and bones disease visit hospital and take appointments of Dermatologist and Orthopedic
on the same day. Similarly, a doctor can check many patients)
	A patient has one or many patient history records. 
(For example, a person who is doing his treatment from hospital from several months may have different history based on months.) 
</pre>

![image](https://user-images.githubusercontent.com/64362437/189481479-2a717ee9-bbdc-4442-9dda-9a599b949647.png)




##### ERD TO Relation

![image](https://user-images.githubusercontent.com/64362437/189481308-40d4b0bf-df2c-45d5-bc71-6d08a4559611.png)


##### MS-ACCESS
<pre>
In MS-Access, I have created following tables that will store the records of hospitals, doctors, patients, and the receptionists.
Queries are created for selecting the data from multiple columns in a single column of Report. 
</pre>

•	Tables and Queries

![image](https://user-images.githubusercontent.com/64362437/189481558-f7a14317-a1af-4a0d-b645-020d9b606bf2.png)



•	Forms


![image](https://user-images.githubusercontent.com/64362437/189481567-fa7b7ad3-4d8a-4f8c-80f2-d905c84eb446.png)


•	Reports

Reports are created to make it user friendly application where:
<ul>
<li>Users can see the details of hospitals, doctors, and patients</li>
<li>Users can enter the details like Receptionist can record the details</li>
<li>Users can update the details.</li>
<li>Users can book an appointment.</li>


![image](https://user-images.githubusercontent.com/64362437/189481582-61d30f94-8b6d-4965-ba6c-8af3bc779194.png)



•	Relationship

![image](https://user-images.githubusercontent.com/64362437/189481611-1ec0c7f4-9930-411f-85a5-91441a1770d5.png)



## Hospital Management System

##### Welcome Page 

When user will open the database, there will be a welcome screen. These encircle options are buttons that will lead you to the specific Reports.


![image](https://user-images.githubusercontent.com/64362437/189481620-8ebcc73d-f547-451d-8969-79b10ac6c502.png)


Functionalities of Buttons on Welcome Page:
<ul>
<li>Click on Hospital, will open Hospital Report. </li>
<li>Click on All Doctor, will open Doctors Report.</li>
<li>Click on Patients, will open Patients Report.</li>
<li>Click on Receptionist, will open Receptionist Report.</li>
</ul>


##### Hospital Page
By clicking on Hospital button on welcome page, Hospital Report will be open.

![image](https://user-images.githubusercontent.com/64362437/189481641-66db5aea-1b6b-4133-9111-c074cade96e5.png)


Functionalities of Buttons:
<ul>
<li>Back button will lead you to welcome page again.</li>
<li>Click for Entering Other Hospitals Data button will open a Hospital form, where user can enter the details of other hospitals and can update the data of these hospitals.</li>
<li>Click for Appointment button will open Appointment form, where user can book an appointment. </li>
</ul>

##### Doctor’s Page
By clicking on All Doctors button on welcome page, Doctors Report will be open.

![image](https://user-images.githubusercontent.com/64362437/189481663-20df30e0-909e-409e-86dc-cb30751a21e8.png)



Functionalities of Buttons:
<ul>
<li>Back button will lead you to welcome page again.</li>
<li>Cardiac Hospital button will open a Cardiac hospital Report.</li>
<li>Children’s Hospital button will open a Children’s hospital Report.</li>
<li>Women’s Hospital button will open a Women’s hospital Report.</li>
<li>Psychiatric Hospital button will open a Psychiatrics’ hospital Report.</li>
<li>Cancer Treatment Hospital button will open a Cancer Treatment hospital Report.</li>
</ul>


##### Children’s Page
By clicking on Children’s Hospital button on Doctors page, Children’s Page will be open.

![image](https://user-images.githubusercontent.com/64362437/189481671-4bd70426-8b26-4900-a93f-5740a2e86fd6.png)


Functionalities of Buttons:
<ul>
<li>	Back button will lead you to Doctors page again.</li>
<li>	Click for Appointment button will open Appointment form, where user can book an appointment. </li>
</ul>
Note:
	All the Doctors pages same.





##### Patients Page

By clicking on Patients button on Welcome page, Patients Page will be open.

![image](https://user-images.githubusercontent.com/64362437/189481681-44388b0b-90fb-4825-9595-ba4a6b3dfc27.png)



Functionalities of Buttons:
<ul>
<li>	Back button will lead you to Welcome page again. </li>	
<li>	Patient Entry button will open a page for entry of patients.</li>
<li> Patient History button will show the details of patients and will provide the function to update it.</li>
</ul


##### Receptionist Page

By clicking on Receptionist button on Welcome page, Receptionist Page will be open.



![image](https://user-images.githubusercontent.com/64362437/189481696-00f6243c-bae6-439a-befb-f4b93a4ceda9.png)


Functionalities of Buttons:
<ul>
<li>	Back button will lead you to welcome page again. </li>
<li>	Receptionist button will open a page for entry of Receptionist.</li>
<li>	Patient Record button will open a page of the recorded data pf patients recorded by receptionist.</li>
</ul>
