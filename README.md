# facebook-check-list

| Module | Priority | Check list |
|---|---|---|
| Log in | Smoke | Check login with correct password/login |
|  | Smoke | Check that user cannot be logged in with incorrect login or password  |
|  | Smoke | Check that user cannot be logged in with empty fields |
|  | Smoke | Check that user cannot be logged in with only login |
|  | Smoke | Check case sensitivities for login and password |
|  | Critical pass | Check that user can see password by clicking on 'show password' icon |
|  | Critical pass | Check that "Forgot password" and "Create account" displayed on the form |
|  | Extendet | Check paste password using ctrl+v or context menu |
|  | Extendet | Check that password has mask |
|  | Extendet | Check auto filling login and password by second time login (if user save the data) |
| Sign up | Smoke | Check sign up possibility by filling all fields (first name, last name, email/phone number, password, birth date, sex) with correct data (according to facebook validation rules) and clicking "create account" button |
|  | Smoke | Check that user cannot be signed up by filling one of the field (first name, last name, email/phone number, password, birth date, sex) with incorrect data (according to facebook validation rules) and clicking "create account" button  |
|  | Smoke | Check that user cannot be signed up if one of the fields is not filled |
|  | Smoke | Check closing form and reset data by clicking on cross icon or refresh the page |
|  | Smoke | Check filling confirmation page with incorrect confirmation code |
|  | Smoke | Check that confirmation code received on mobile email |
|  | Smoke | Check resend function of confirmation code for email |
|  | Smoke | Check that user cannot create an account with existing phone number or email  |
|  | Smoke | Check redirect to agreements |
|  | Smoke | Check that confirmation code received on mobile phone |
|  | Smoke | Check resend function of confirmation code for mobile phone |
|  | Smoke | Check redirect to confirmation page if with successfully filling form |
|  | Critical pass | Check validation errors near the fields with incorrect data |
|  | Critical pass | Check that additional email field displayed if user enter email instead of phone number  |
|  | Critical pass | Check count (intervals) of sent confirmation codes |
|  | Extendet | Check paste password using ctrl+v or context menu |
|  | Extendet | Check that password has mask |
|  | Extendet | Check redirect to confirmation page if user successfully fill the registration form close browser tab and open facebook again  |
|  | Extendet | Check notes for for fields |
| Forgot Password | Smoke | Check reset password with by filling existing phone number |
|  | Smoke | Check reset password with by filling existing email |
|  | Smoke | Check reset password with by filling not existing phone number |
|  | Smoke | Check reset password with by filling not existing email |
|  | Smoke | Check filling incorrect code using phone number |
|  | Smoke | Check receive email with code for reset password |
|  | Smoke | Check resend code using email |
|  | Smoke | Check filling incorrect code using email |
|  | Smoke | Check receive sms with code for reset password |
|  | Smoke | Check resend code using phone number |
|  | Critical pass | Check impossibility to reset password by filling symbols |
|  | Critical pass | Check function "No more access?" |
|  | Critical pass | Check function "Is it not you?" |
|  | Critical pass | Check count (intervals) of sent code using phone number |

