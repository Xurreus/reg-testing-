# Test Cases – Registration Form

| ID   | Test Case Description                  | Steps                                                                 | Expected Result |
|------|---------------------------------------|-----------------------------------------------------------------------|----------------|
| TC01 | Register with valid information        | Fill all fields with valid data, click Sign Up                        | User is registered successfully, redirected to welcome page |
| TC02 | Empty fields validation                | Click Sign Up without filling anything                                 | Error messages displayed for required fields |
| TC03 | Invalid email format                   | Enter invalid email format (e.g., abc@)                               | Error: "Enter a valid email" |
| TC04 | Password too short                     | Enter password <6 characters                                          | Error: "Password must be at least 6 characters" |
| TC05 | Password mismatch                       | Enter password and confirm password differently                        | Error: "Passwords do not match" |
| TC06 | Already registered email               | Use an email already registered                                        | Error: "Email already in use" |
| TC07 | Optional fields                         | Fill optional fields only                                             | Registration succeeds |
| TC08 | Special characters in name              | Enter symbols or numbers in full name field                            | Error or allowed depending on app rules |
