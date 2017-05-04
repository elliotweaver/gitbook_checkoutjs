**Auto load**

```
<html>
<head>
</head>
<body>

<!-- load checkout on page load -->
<div id="ps_checkout_load" ps-checkoutType="payment"></div>

<!-- common settings -->
<script
    id="ps_checkout_settings"
    type="text/javascript"
    src="https://checkout.paystand.com/v4/js/paystand.checkout.js"
    ps-mode="modal"
    ps-height="700px"
    ps-width="500px"
    ps-debug="true"
    ps-env="{env}"
    ps-publishableKey="{publishableKey}"
></script>

</body>
</html>
```

**Buttons**

```
<html>
<head>
</head>
<body>

<!-- $20 payment -->
<button 
    class="ps-button ps-button-style"
    ps-checkoutType="payment"
    ps-paymentAmount="20"
>$20</div>

<!-- Save a payment method -->
<button 
    class="ps-button ps-button-style"
    ps-checkoutType="token"
>Save payment method</div>

<!-- common settings -->
<script
    id="ps_checkout_settings"
    type="text/javascript"
    src="https://checkout.paystand.com/v4/js/paystand.checkout.js"
    ps-mode="modal"
    ps-height="700px"
    ps-width="500px"
    ps-debug="true"
    ps-env="{env}"
    ps-publishableKey="{publishableKey}"
></script>

</body>
</html>
```

Auto

