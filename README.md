# promptpay-qr-js
PromptPay QR-Code Javascript Library [ <a target='_blank' href='https://diewland.github.io/promptpay-qr-js/'>demo</a> ]

### Examples
```javascript
// id card
var promptpay_text = PromptPayQR.gen_text("1234567890123");

// telephone number
var promptpay_text = PromptPayQR.gen_text("0891234567");

// specific amount
var promptpay_text = PromptPayQR.gen_text("1234567890123", 50); // by id-card 50 baht
var promptpay_text = PromptPayQR.gen_text("0891234567", 100);   // by tel-no 100 baht

// return null when account_id not match
PromptPayQR.gen_text("12345") == null; // true
```

### References
* https://www.blognone.com/node/95133
* https://www.blognone.com/node/95530
* http://www.truemoney.com/promptpay-aom
* https://www.blognone.com/node/97186
