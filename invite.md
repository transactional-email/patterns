# Team invite

## When to send

An existing member invites a teammate. Link should create/join membership after auth.

## Security

- Invite tokens scoped to email + workspace
- Expire unused invites
- Allow invite revocation

## Sample HTML

```html
<p>{{INVITER}} invited you to {{WORKSPACE}}.</p>
<p><a href="{{INVITE_URL}}">Accept invite</a></p>
```

## Docs

- https://notify.cx/use-cases/invite
