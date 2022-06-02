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
${AppName} - Login to your account

Click on this link: ${magicLink}

This is valid for ${time}.
```

### OTP login
```
${AppName} - Login to your account

Your OTP to login: ${OTP}

This is valid for ${time}.
```


### Magic link + OTP login
```
${AppName} - Login to your account

Your OTP to login: ${OTP}

OR

Click on this link: ${magicLink}

This is valid for ${time}.
```