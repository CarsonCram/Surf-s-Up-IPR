# Surf-s-Up-IPR
In Progress Review for in-class project


## Scope

Surf's Up helps surfers find the best beach in the San Diego area to enjoy some extended surfing at. 

## Requirements

|Test No.|Requirements| 
|-|-|
|1|User shall make an account|
|1.1|User shall make a username|
|1.2|User shall make a password|
|1.3|User shall link email to profile|
|2|Map shall locate users position|
|2.1|Map shall locate the beachs poosition|
|2.2|Map shall be able to zoom in and out of user and beach loocations|
|2.3|Map shall provide distance to beach|
|2.4|Map shall provide SU rate to user|
|2.5|Map shall provide weather conditions at beaches|
|3|Views shall display correctly|
|3.1|Login page shall display login and surf buttons|

## Solution Design

As a surfer I need to locate the best beaches so I can ride the best waves.

## Data Design

![ERD](https://user-images.githubusercontent.com/14228329/64755943-c0452d80-d4e1-11e9-8bf0-931325a5c48c.PNG)

## UI Design

Landing Page
![1](https://user-images.githubusercontent.com/14228329/64754672-21b6cd80-d4dd-11e9-8bfd-8abe6c7716a2.png)

Initial Map Page
![2](https://user-images.githubusercontent.com/14228329/64754683-2ed3bc80-d4dd-11e9-8473-52dbe7025d86.png)

Zoomed Map Page
![3](https://user-images.githubusercontent.com/14228329/64754713-3f843280-d4dd-11e9-8f1e-ee0769f16a63.png)

## Project Plan

|PBIs|Status|
|-|-|
|Login Page design|Completed|
|Sign-in functionality|Not Started|
|Initial Map Page|WIP|
|Markers|WIP|
|Zoomed Map Page|WIP|

#### TODO
<ul>
  <li>make markers smaller</li>
  <li>create loogin functionality</li>
  <li>create zoom on marker buttonclick</li>
  <li>get rid of zoom buttons</li>
  <li>distinguish markers between beaches and user</li>
  <li>make buttons on api smaller</li>
  <li>link marker information to db</li>
  <li>dynamically grab weather information and send to db</li>
  <li>make marker info prettier</li> 
</ul>

## Project Demo

Current version of the prototype can be found above. 

## Test Report

|Test No.|Status|Requirement|Test Method|Test Procedure| 
|--|--|--|--|--|
|1  |Not Tested|User shall make an account                     |Analysis  |Make an account<br>Verify account is continuous|
|1.1|Not Tested|User shall make a username                     |Test      |Unit test|
|1.2|Not Tested|User shall make a password                     |Test      |Unit test|
|1.3|Not Tested|User shall link email to profile               |Test      |Self-test<br>Login with email<br>Send verification password to said email|
|2  |Not Tested|Map shall locate users position                |Test      |Verify location is accurate|
|2.1|Not Tested|Map shall locate the beachs poosition          |Test      |Unit test|
|2.2|Not Tested|Map shall be able to zoom in and out of user and beach locations|Demonstration|Verify map is dynamic|
|2.3|Not Tested|Map shall provide distance to beach            |Analysis  |Verify distance is correct with second source|
|2.4|Not Tested|Map shall provide SU rate to user|Inspection   |Verify rate is displayed|
|2.5|Not Tested|Map shall provide weather conditions at beaches|Inspection|Verify weather is correct with second source|
|3  |Not Tested|Views shall display correctly                  |Inspection|Verify information during developer use|
|3.1|Not Tested|Login page shall display login and surf buttons|Inspection|Verify buttons appear and function upon developer use|
