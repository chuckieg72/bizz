<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>BIZZ Payment Portal</title>
<style>
body {
font-family: Arial, sans-serif;
background: #f9f9f9;
padding: 40px;
text-align: center;
}

h1 {
color: #333;
}

.payment-box {
background: white;
border-radius: 10px;
padding: 30px;
max-width: 500px;
margin: 40px auto;
box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

label {
display: block;
text-align: left;
margin: 15px 0 5px;
font-weight: bold;
}

input[type="text"], input[type="number"] {
width: 100%;
padding: 10px;
margin-bottom: 20px;
border-radius: 5px;
border: 1px solid #ccc;
font-size: 16px;
}

.button {
display: block;
margin-top: 15px;
padding: 12px;
width: 100%;
border: none;
border-radius: 5px;
font-size: 16px;
cursor: pointer;
background-color: #007BFF;
color: white;
}

.crypto {
background-color: #6f42c1;
}

.footer {
margin-top: 40px;
font-size: 14px;
color: #777;
}

.footer a {
color: #007BFF;
text-decoration: none;
}
</style>
</head>
<body>
<h1>BIZZ Payment Portal</h1>
<div class="payment-box">
<form>
<label for="username">Account or Username</label>
<input type="text" id="username" name="username" required />

<label for="amount">Payment Amount ($)</label>
<input type="number" id="amount" name="amount" required min="1" step="any" />

<a class="button" href="https://buy.stripe.com/test_YOUR_STRIPE_LINK" target="_blank">Pay with Stripe</a>
<a class="button crypto" href="https://your-crypto-link.com" target="_blank">Pay with Crypto</a>
</form>
</div>

<div class="footer">
<a href="#">Privacy Policy</a>
</div>
</body>
</html>


