Authentication and Authorization

What is Authentication?

Definition:
Authentication is the process of verifying who a user is.

Purpose:
Confirms the identity of a user.

Example:
Logging in with a username and password.

Real World Use:
Websites check your credentials before granting access.

---

What is Authorization?

Definition:
Authorization determines what a user is allowed to do.

Purpose:
Controls access to resources and actions.

Example:

User:
Can view files.

Administrator:
Can view, edit, and delete files.

Real World Use:
Different users have different permissions.

---

Authentication vs Authorization

Authentication:
Who are you?

Authorization:
What can you do?

Example:

Step 1:
Login with username and password.

Authentication successful.

Step 2:
Website checks your permissions.

Authorization successful.

---

Login Process

Example:

1. User enters username.
2. User enters password.
3. Server verifies credentials.
4. User receives access.

Purpose:
Allows legitimate users to access services.

---

Passwords

Definition:
A secret value known only to the user.

Purpose:
Protects user accounts.

Good Password Example:

MyStrongPassword2026!

Bad Password Example:

123456
password
admin

---

Password Hashing

Definition:
A hash converts a password into a fixed-length value.

Purpose:
Protects stored passwords.

Example:

Password:

password123

Hash:

482c811da5d5b4bc6d497ffa98491e38

Note:
Systems should store hashes instead of plain-text passwords.

---

Session

Definition:
A session keeps track of a logged-in user.

Purpose:
Allows users to stay authenticated.

Example:

1. User logs in.
2. Server creates a session.
3. User continues using the website.

Real World Use:
Online banking and social media.

---

Session ID

Definition:
A unique identifier assigned to a session.

Purpose:
Links requests to a logged-in user.

Example:

SessionID=abc123xyz

---

Cookies

Definition:
Small pieces of data stored by the browser.

Purpose:
Store session information and preferences.

Example:

Cookie: SessionID=abc123xyz

Real World Use:
Keeps users logged in.

---

Multi-Factor Authentication (MFA)

Definition:
Requires more than one method of verification.

Examples:

- Password
- Mobile app code
- Hardware token
- Fingerprint

Purpose:
Provides additional security.

Real World Use:
Banking and corporate accounts.

---

Common Authentication Factors

Something You Know:
Password or PIN.

Something You Have:
Phone or security token.

Something You Are:
Fingerprint or face recognition.

---

Account Lockout

Definition:
Temporarily disables an account after multiple failed login attempts.

Purpose:
Helps prevent password guessing.

Example:

5 failed logins → account locked.

---

Why Authentication Matters?

Authentication helps:

- Protect user accounts
- Prevent unauthorized access
- Secure sensitive information
- Improve overall security

Authentication is one of the most important concepts in web security.

---

Quick Summary

Authentication
Verifies identity.

Authorization
Controls permissions.

Password
Secret used for login.

Hash
Protected representation of a password.

Session
Tracks logged-in users.

Session ID
Unique session identifier.

Cookie
Stores session information.

MFA
Multiple verification methods.

Account Lockout
Protection against repeated login failures.
