# 

```


<html>
<head>

<!-- bottom of head -->
<link id="ps_css" rel="stylesheet" type="text/css" href="https://checkout.paystand.com/v4/js/paystand.checkout.css">
</head>
<body>

<!-- 
Checkout Settings - common settings used by all checkouts
Attributes - any checkout instance attribute can be used. below are examples of the most common 
to be used here.
----------
id                    ps_checkout_settings
ps-mode               modal|embed|default[modal]
ps-height             number with units|default[700px]
ps-width              number with units|default[400px]
ps-debug              true|false|default[false]
ps-env                live|sandbox|default[live]
ps-publishableKey     publishable key|required
-->
<div
    id="ps_checkout_settings"
    ps-mode="modal"                        
    ps-height="700px"                      
    ps-width="500px"                       
    ps-debug="true"                        
    ps-env="{env}"                         
    ps-publishableKey="{publishableKey}"   
></div>

<!--
Checkout Load - automatically loads a checkout on page load and shows it
Attributes - any checkout instance attribute can be used.
----------
id                    ps_checkout_load
-->
<div
    id="ps_checkout_load"
    ps-checkoutType="payment"
></div>


<!--
Checkout Button - configure a button that will load a checkout instance on click
Attributes - any checkout instance attribute can be used.
----------
class                
    ps-button                establishes an element as a checkout button
    ps-button-style          applies default styling to the button. to avoid a flicker on page load
                             be sure to manually add paystand.checkout.css in the <head> section
-->
<button
    class="ps-button ps-button-style"
    ps-checkoutType="checkout_payment"
    ps-paymentAmount="20"
>$20</button>


<!-- bottom of body -->
<script type="text/javascript" src="https://checkout.paystand.com/v4/js/paystand.checkout.js"></script>
</body>
</html>
```



