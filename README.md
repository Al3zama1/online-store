# E-commerce Store

## Application Requirements

### Application User
1. User account (unique email address)
   * Account verification (verify email address)
   * User profile image
   * User details (name, email, phone, address, etc)
2. User reset password (without being logged in )
   * Password reset link should expire within 24 hours
3. User login (using email and password)
   * Token based authentication (JWT Token)
   * Refresh Token
4. Brute force attack mitigation (account lock mechanism)
   * Lock account after the 6th failed login attempt
5. Role and Permission based application access
6. Two-factor authentication (using user phone number)
   * Send verification to user's phone
