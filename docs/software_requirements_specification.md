**_Copyright  2020 Pietro Bonetti. Permission isn't granted to use and modify this document._**

# Software Requirements

# Specification

## For

# English Course FCE

## An English e-learning course

### Prepared by:

### Pietro Bonetti, Diego Donatelli

### Cristiano Picilli, Giovanni Rizzotti & Pietro Zecchin

### 2020

## Table of Contents

**Table of Contents **

- 1. Introduction Revision History iii
   - 1.1 Purpose
   - 1. 2 Intended Audience and Reading Suggestions
   - 1. 3 Project Scope
- 2. Overall Description
   - 2.1 Product Perspective
   - 2.2 Personas
   - 2.3 Product Features
   - 2.4 User Characteristics
   - 2.5 Operating Environment
   - 2. 6 User Documentation
- 3. System Features
   - 3.1 Secure Login
- 4. External Interface Requirements
   - 4.1 User Interfaces
   - 4.4 Communications Interfaces
- 5. Other Nonfunctional Requirements
   - 5.1 Performance Requirements
   - 5.2 Security Requirements


**_Software Requirements Specification for Physician/Pharmacist Assistant Page iii_**

Revision History

**Name Date Reason For Changes Version**

Pietro Bonetti 04 /0 1 / 20 Document 0.


**_Software Requirements Specification for English Course FCE Page 1_**

## 1. Introduction

### 1.1 Purpose

The purpose of this project is to provide an online platoform to be used by teachers and students of
ITI Marconi. This platform will provide to teachers the instruments to create courses for their
students to undertake them. The courses on this online platform will allow students to get a better
learning of the subject.

### 1. 2 Intended Audience and Reading Suggestions

This SRS will be used by members of the teaching team to assist in the development of the
project.
SRS contains a detailed description of the software development and required components with
suggested feature inclusions.
The teacher team should start with the detailed description in Section 2, then proceed with the
interface requirements in Section 4 to understand the implementation requirements.

### 1. 3 Project Scope

The general scope of the project is provide a software (as a service) that will provide a better
learning experience for students and provide better teaching instruments for teachers. * The
service should be useful. * The service should be convenient and easy to use. It should require no
prior computer experience and be usable after a brief 1-minute introduction. Use of the service
should not cause frustation or confusion.

## 2. Overall Description

### 2.1 Product Perspective

Through the MOODLE online platform, a course for learning the English language was created
based on the FCE test (First Certificate of English), in which there are short lessons, exercises and
summary tests.
The course is available to the Institute's English language teachers for use in the classroom, who
will be able to have their pupils study and exercise in view of the actual exam.
Furthermore, it is possible to use another online platform, which is already connected within the
course itself, such as Piazza, to allow teachers and pupils to interact, through questions and
answers.

### 2.2 Personas

```

2.2.1 Pietro Bonetti (Scrum Master)
```

```
2 .2.2 Diego Donatelli (Team Member)
```

```
2.2.3 Cristiano Picilli (Team Member)
```

```
2.2.4 Giovanni Rizzotti (Team Member)
```

```
2 .2.5 Pietro Zecchin (Team Member)
```

### 2.3 Product Features

The product is divided into three parts, each of them is made up of a number of lessons
(modifiable), with some exercises inside. At the end of each lesson you can choose whether to
immediately perform the final quiz concerning the lesson or to proceed with the next lesson. The
teacher of the course will be able to create and modify the lessons and tests according to his
needs, he will also be able to assign a mark based on the score achieved for each pupil who
finishes the quiz.
Within the course there is a link to an online platform, such as Piazza, which will allow prior
registration to post questions and answers within a virtual class made up only of members of the
physical class using the FCE course.

### 2.4 User Characteristics

Users of the English course are all pupils and teachers of the ITI G.Marconi, who will be able to
access through their matriculation number (without leading zeroes) and their password which they
use to access the Campus, as the FCE course is all inside the latter. Instead, to access Piazza,
just click on the link within the course, as for login you will use the campus credentials.

### 2.5 Operating Environment

The project does not need a specific operating environment, it only requires the use of a web
browser.

### 2. 6 User Documentation

To accompany the delivery of the project there will be several instruction manuals to inform the
teacher in the use of the courses. The manual will include instructions for operating each of the
main features, as listed above.

## 3. System Features

The English course can only be accessed by logging in through the Campus platform previously
accessible.

### 3.1 Viewing Screen

Since there is a difference between the teacher and the student, partially different screens will
appear based on the authorizations obtained through the login.

## 4. External Interface Requirements

### 4.1 User Interfaces

The visible interfaces will change based on whether you are a teacher or a student. In the first case
you will get the opportunity to create, edit and delete lessons and tests. In the second case,
nothing can be done except to complete the activities created by the teacher.

### 4.2 Communications Interfaces

MOODLE uses a communication interface that takes advantage of emails. It is designed to send
messages in various situations.

## 5. Other Nonfunctional Requirements

### 5.1 Performance Requirements

The performance of the course depends on the quality of the internet connection you have.

### 5.2 Security Requirements

The only security requirement is to not share your password with outsiders.

## 6. Optional Requirements

The only optional requirement is to already have a Piazza account.
