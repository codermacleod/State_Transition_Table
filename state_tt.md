# State Transition Table

States:

- Homepage
- Sign-up page
- Login page
- Profile page

Events/Transitions:

- User opens the app
- User clicks on Sign-up button
- User clicks on Login button
- User inputs valid credentials
- User inputs invalid credentials
- User clicks on Profile button

Test case:

Starting state: Homepage

1. User clicks sign-up: Homepage to Sign-up page
2. User enters invalid credentials: Sign-up page to Sign-up page
3. User enters valid credentials: Sign-up page to Login page
4. User enters invalid credentials: Login page to Login page
5. User enters valid credentials: Login page to Profile page
6. User clicks Homepage: Profile page to Homepage
7. User clicks Profile page: Homepage to Profile page
8. User clicks Logout: Profile page to Login page
