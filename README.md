# Amazon Web Application Testing

Test cases for the Amazon web application, focusing on signup and sign-in functionalities.

## Test Scenarios

### Signup Functionality (TS 001)
- **Description:** Check signup functionality.

| Test Case ID | Description               | Pre-requisite | Data                      | Steps                                         | Expected Output                        | Status |
|--------------|---------------------------|---------------|---------------------------|-----------------------------------------------|----------------------------------------|--------|
| TC 001       | Successful signup         | None          | Valid user details        | Navigate to signup page > Enter details > Submit | User registered, redirected to welcome |        |
| TC 002       | Signup with invalid data  | None          | Invalid user details      | Navigate to signup page > Enter invalid details > Submit | Error message displayed               |        |

### Sign-in Functionality (TS 102)
- **Description:** Check sign-in functionality.

| Test Case ID | Description               | Pre-requisite | Data                      | Steps                                         | Expected Output                        | Status |
|--------------|---------------------------|---------------|---------------------------|-----------------------------------------------|----------------------------------------|--------|
| TC 101       | Successful sign-in        | User registered | Valid credentials         | Navigate to sign-in page > Enter credentials > Submit | User signed in, redirected to dashboard |        |
| TC 102       | Sign-in with invalid data | User registered | Invalid credentials       | Navigate to sign-in page > Enter invalid credentials > Submit | Error message displayed               |        |

## Usage

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/amazon-web-app-testing.git
