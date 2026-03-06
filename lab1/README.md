## A Hospital Management System maintains information about Doctor and Patient.
Create a class Doctor with the following attributes:
doctorId (int)
doctorName (String)
specialization (String)
Create a class Patient with the following attributes:
patientId (int)
patientName (String)
assignedDoctor (Doctor)
(Here, Patient has an association relationship with Doctor)
In the Patient class:
Write a method assignDoctor(Doctor d) that accepts a Doctor object as a method parameter
and assigns it to the patient.
Write a method generateDoctorInfo() that returns a Doctor object.
Create a class Hospital that contains a method:
admitPatient(Patient p) which accepts a Patient object as a parameter and prints the patient
details along with the assigned doctor’s information.
In the main() method:
Create at least one Doctor object.
Create a Patient object and assign a doctor using assignDoctor().
Pass the Patient object to the admitPatient() method.

### 📌 Main Topics:
●​ Class & Object
●​ Association Relationship (Patient has-a Doctor)
●​ Constructor
●​ Method
●​ Method Parameter Passing (Object as Parameter)
●​ Encapsulation
●​ Object Returning from Method
