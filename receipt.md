# Receipt / invoice

## When to send

After successful payment or when an invoice is issued. Include amount, date, and a link to the billing portal when relevant.

## Sample HTML

```html
<p>Thanks for your payment.</p>
<ul>
  <li>Amount: {{AMOUNT}}</li>
  <li>Date: {{DATE}}</li>
</ul>
<p><a href="{{RECEIPT_URL}}">View receipt</a></p>
```

## Kits / docs

- https://notify.cx/docs/how-to-send-receipt-emails
- https://notify.cx/docs/recipe-stripe-receipt-email
