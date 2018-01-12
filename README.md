# No Show Medical Appointment Project
A person makes a doctor appointment, receives all the instructions and it’s a no-show.

### Who/What to blame?

### What is a no-show?
Basically, it’s a non-attending person who neither uses nor cancels their reservation.

### The problem is…
People have no idea of the scale of this problem.
A recent survey concluded that as many as 42% of patients skip their appointments.
            
### “An appointment missed by you is an appointment missed by two.”

A missed appointment is more than just a missed opportunity. When a patient doesn’t show up on time, it also affects people who could’ve been treated instead of that patient.

Visitors, doctors, and even hospital administration…they’re all affected.

### Finding Reasons
### Different Surveys using different datasets came up with some influencing factors :
Financial Reasons

Discouraged by long Hospital wait time 

Poor Medical Literacy

Anxiety

Transportation

### The data we had
Gender & Age

Signs of Hypertension, Diabetes & Alcoholism

Appointment date and the date of Scheduling

Medical Insurance 

SMS Notification

![data](https://user-images.githubusercontent.com/35349226/34854017-0bfba464-f705-11e7-95e3-1a866f55cc07.png)

![image](https://user-images.githubusercontent.com/35349226/34854062-5b0b6328-f705-11e7-9e1c-92913b7d920e.png)


### Data Struggles
Irrelevant Columns – Patient & Appointment ID

Date & Time Stamps – Always an issue!!

Outliers in Age – 0, negative and above 100

Junk Rows – Handicap Row values

Appointment & Schedule data Difference- Is it Relevant?

Bias Data – 80:20 Show : No-Show

Balancing the data

### Clean it UP!!!
Remove Patient ID, Appointment ID columns

Cleaning up date columns

Extracting date month and year from appointment and schedule day columns

Calculate difference between Scheduled and Appointment dates

Creating Balanced Data

removing negative values and values >1

Convert columns to factors

## Real World Data Set is not your friend!

Bias in Distribution
85,000 v/s 21,000 Rows

![image](https://user-images.githubusercontent.com/35349226/34854140-d52365c0-f705-11e7-9ac1-cfe6c16773c9.png)




            
