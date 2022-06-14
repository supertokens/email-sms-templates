## Emails

### Email verification
- Subject: "Email verification instructions"
- File content: /email-html/email-verification.html
- Variables:
    - `${appname}`
    - `${verificationLink}`
    - `${toEmail}`

### Password reset
- Subject: "Password reset instructions"
- File content: /email-html/password-reset.html
- Variables:
    - `${appname}`
    - `${resetLink}`
    - `${toEmail}`

### Magic link login
- Subject: "Login to your account"
- File content: /email-html/magic-link-login.html
- Variables:
    - `${appname}`
    - `${time}`
    - `${urlWithLinkCode}`
    - `${toEmail}`

### OTP login
- Subject: "Login to your account"
- File content: /email-html/otp-login.html
- Variables:
    - `${appname}`
    - `${time}`
    - `${toEmail}`
    - `${otp}`

### Magic link + OTP login
- Subject: "Login to your account"
- File content: /email-html/magic-link-otp-login.html
- Variables:
    - `${appname}`
    - `${time}`
    - `${urlWithLinkCode}`
    - `${toEmail}`
    - `${otp}`

## SMS

### Magic link login
```
Click ${magicLink} to login to ${appname}

This is valid for ${time}.
```

### OTP login
```
OTP to login is ${otp} for ${appname}

This is valid for ${time}.
```


### Magic link + OTP login
```
OTP to login is ${otp} for ${appname}

Or click ${magicLink} to login.

This is valid for ${time}.
```
