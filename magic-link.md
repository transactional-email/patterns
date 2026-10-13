# Magic link / OTP

## When to send

Passwordless sign-in or email verification. Prefer short expiry.

## Security

- One-time tokens; invalidate on use
- Rate-limit requests per IP/email
- OTP codes: limit attempts

## Sample HTML

```html
<p>Sign in:</p>
<p><a href="{{MAGIC_URL}}">Continue</a></p>
<p>Or use code: <strong>{{OTP}}</strong></p>
```

## Kits / docs

- https://github.com/email-examples/transactional-email-examples/tree/main/magic-link-nextjs
- https://notify.cx/docs/how-to-send-magic-link-and-otp-emails
