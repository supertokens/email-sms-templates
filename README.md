## Emails

### Email verification
- Subject: "Email verification instructions"
- File content: /email-html/email-verification.html
- Variables:
    - `${appname}`
    - `${verificationLink}`
    - `${toEmail}`

<img src="https://github.com/supertokens/email-sms-templates/raw/master/images/email-verify-email.png" style="height: 300px"/>

### Password reset
- Subject: "Password reset instructions"
- File content: /email-html/password-reset.html
- Variables:
    - `${appname}`
    - `${resetLink}`
    - `${toEmail}`

<img src="https://github.com/supertokens/email-sms-templates/raw/master/images/pass-reset-email.png" style="height: 300px"/>

### Magic link login
- Subject: "Login to your account"
- File content: /email-html/magic-link-login.html
- Variables:
    - `${appname}`
    - `${time}`
    - `${urlWithLinkCode}`
    - `${toEmail}`

<img src="https://github.com/supertokens/email-sms-templates/raw/master/images/magic-link.png" style="height: 300px"/>

### OTP login
- Subject: "Login to your account"
- File content: /email-html/otp-login.html
- Variables:
    - `${appname}`
    - `${time}`
    - `${toEmail}`
    - `${otp}`

<img src="https://github.com/supertokens/email-sms-templates/raw/master/images/otp-login.png" style="height: 300px"/>

### Magic link + OTP login
- Subject: "Login to your account"
- File content: /email-html/magic-link-otp-login.html
- Variables:
    - `${appname}`
    - `${time}`
    - `${urlWithLinkCode}`
    - `${toEmail}`
    - `${otp}`

<img src="https://github.com/supertokens/email-sms-templates/raw/master/images/otp-magic-link.png" style="height: 300px"/>

## Guide
- Outlook breaks if the width of the template crosses a specific width, according to mailchimp this dimensions of a mail template should be 600-800

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
