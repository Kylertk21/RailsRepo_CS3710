ruby on rails documentation: https://guides.rubyonrails.org/v7.1/

## USS 1: As a student, I want to create a profile with basic information, So I can manage my personal details in the system

 System should allow the creation of a student with: **first name**, **last name**, **email**, **grad date** *all fields required*

 If required field is missing student should see: **error message** and **record should not be saved**

`rails generate scaffold <name> <fieldname>:<datatype>`

recommend: `rails generate scaffold Student first_name:string last_name:string school_email:string grad_date:date`
___

## USS 2: AS the MSU CS Admin, I want to ensure students enter school email that is unique and in the correct format, so that no two students can use the same email address

 System should validate: **school_email field unique**, **error message when duplicate emails**, **error message when invalid email format entered**, **error message when email already exists** *system should NOT save when errors are encountered* 

 Optional: **follow format name@msudenver.edu**

___

## USS 3: As a student, I want to upload a profile picture, so that I can personalize my profile

 System should: **allow student to upload profile picture using active storage**, **picture should be displayed on profile page**, **default image when no picture uploaded**

___

## Steps for Module are in this link: https://docs.google.com/document/d/1pHRImSS6Z26shCdsn5NRig4NQUWmoFZbDiC2qfmlxzk/edit?usp=sharing
