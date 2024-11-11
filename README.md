# Dental Management Platform
A user friendly platform that helps you book and Scheduled meeting with Doctors

## Prerequisites
Make sure you have the following installed on your system:
- [Git](https://git-scm.com/)
- [JDK 17](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)
- [Maven](https://maven.apache.org/) or [Gradle](https://gradle.org/)
- (Optional) An IDE like [IntelliJ IDEA](https://www.jetbrains.com/idea/), [Eclipse](https://www.eclipse.org/), or [VS Code](https://code.visualstudio.com/)

## Getting Started

### Clone the Repository
To clone the repository, run the following command:
```bash
https://github.com/Innocentsax/Dental-Management-Platform.git
```
## Building the Project
#### Maven Projects
Build the pom.xml file:

Install dependencies and build:
```bash
mvn clean install

Run the application:
mvn spring-boot:run
```

### Test DEMO

+ Sign in and Login using a well constructed password.

#### Add Clinic
<img src="https://github.com/Innocentsax/Dental-Management-Platform/blob/main/AddClinic.jpeg">

```bash
{
  "name": "John Doe",
  "address": "123 Main St, Apt 4B",
  "phoneNumber": "+1-555-123-4567",
  "email": "johndoe@example.com",
  "city": "New York",
  "state": "NY"
}

```

#### Add Doctor
<img src="https://github.com/Innocentsax/Dental-Management-Platform/blob/main/AddDoctor.jpeg">


```bash
{
  "name": "Dr. Sarah Williams",
  "address": "456 Oak Avenue, Suite 101",
  "phoneNumber": "+1-555-987-6543",
  "email": "dr.sarah.williams@dentalclinic.com",
  "city": "Los Angeles",
  "state": "CA",
  "specialties": [
    "CLEANING"
  ],
  "clinicIds": [
    1
  ]
}
```

#### Add Patients
<img src="https://github.com/Innocentsax/Dental-Management-Platform/blob/main/AddPatient.jpeg">


```bash
{
  "name": "John Doe",
  "address": "123 Main Street, Springfield, IL, 62701",
  "phoneNumber": "+1-555-123-4567",
  "dateOfBirth": "1985-07-25",
  "ssnLast4": "1234",
  "gender": "Male",
  "affiliatedClinicId": 1,
  "affiliatedDoctorId": 1
}
```
