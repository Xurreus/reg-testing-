# Bug Report List – Registration Form

## Bug 01
**Title:** Sign Up button not clickable after entering data  
**Steps:** Fill all fields correctly, click Sign Up  
**Expected:** Registration completes  
**Actual:** Button stays unresponsive  

## Bug 02
**Title:** Invalid email accepted  
**Steps:** Enter 'abc@', fill other fields correctly, click Sign Up  
**Expected:** Error: "Enter a valid email"  
**Actual:** Form allows submission  

## Bug 03
**Title:** Password mismatch message not displayed  
**Steps:** Enter different password and confirm password, click Sign Up  
**Expected:** Error: "Passwords do not match"  
**Actual:** Registration attempts to submit  

## Bug 04
**Title:** Duplicate email allowed  
**Steps:** Register twice with same email  
**Expected:** Error: "Email already in use"  
**Actual:** Second registration succeeds
