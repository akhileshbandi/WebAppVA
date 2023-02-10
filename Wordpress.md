# Wordpress Self Host Cracking
## Successfully Setup the site with xampp and given zip files

<img width="720" alt="image" src="https://user-images.githubusercontent.com/40914006/211659774-16f3cc4f-d3f0-4029-b7d2-cd9ade6c599e.png">

## WPScan enumerated to reveal admin and think user
<img width="720" alt="image" src="https://user-images.githubusercontent.com/40914006/211660144-ff303cfc-77ed-4bcd-ac94-9199135b0ef1.png">


## Entered the usernames and passwords in txt for enumeration sources

<img width="720" alt="image" src="https://user-images.githubusercontent.com/40914006/211660261-478377a7-bf8e-4941-8d03-f6a5082a246c.png">

## Further credential enumeration seems to be unsuccessful due to cooldown period in login page

<img width="720" alt="image" src="https://user-images.githubusercontent.com/40914006/211660459-b9b2129d-0dfb-45dc-850c-79e30e00ca2f.png">

## User Passwords Stored in Irreversible Hashes
<img width="720" alt="image" src="https://user-images.githubusercontent.com/40914006/218029406-34aec15a-850f-4044-8c31-78e875ec79da.png">

## A time check is employed enforcing a cooldown of 10 minutes
<img width="360" alt="image" src="https://user-images.githubusercontent.com/40914006/218029460-d153ab70-5e95-48b7-b56b-f3b3cfaf660a.png">

## Script to increase time by 10min for each second to circumvent the coolodown

```bash
#!bin/bash
while:
do 
  date -s "+ 10 minutes"
  sleep 1
done
```
<img width="720" alt="image" src="https://user-images.githubusercontent.com/40914006/218029824-bf6c7fe4-6511-44ac-b4cb-746b6932e7c4.png">

## Issuing the command with more throttle
<img width="720" alt="image" src="https://user-images.githubusercontent.com/40914006/218029875-e632d5f3-cfff-4f2c-8cf0-963cd218f95c.png">


## Think user password revealed as 123
<img width="720" alt="image" src="https://user-images.githubusercontent.com/40914006/218029926-e1079424-dec1-4b1a-a919-2a29cb320849.png">


## Admin user password revealed as #1mama
![image](https://user-images.githubusercontent.com/40914006/218029974-73bc1f7d-9de8-40c6-b0ed-53e2ba705186.png)
