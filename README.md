# Card <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My NFC Menu</title>
  <style>
    body { font-family: Arial, sans-serif; text-align: center; padding: 40px; background: #f7f7f7; }
    h1 { color: #333; }
    .btn {
      display: block;
      margin: 15px auto;
      padding: 14px 20px;
      width: 220px;
      background: #007bff;
      color: #fff;
      text-decoration: none;
      border-radius: 8px;
      font-size: 18px;
      transition: 0.3s;
    }
    .btn:hover { background: #0056b3; }
  </style>
</head>
<body>
  <h1>📲 Quick Actions</h1>
  <a href="https://instagram.com/yourhandle" class="btn">📸 Instagram</a>
  <a href="tel:+911234567890" class="btn">📞 Call Me</a>
  <a href="mailto:you@example.com" class="btn">📧 Email</a>
  <a href="wifi://SSID=MyHomeWiFi;T=WPA;P=MyPassword;;" class="btn">📶 Wi-Fi Connect</a>
  <a href="https://maps.google.com/?q=Your+Location" class="btn">📍 Location</a>
</body>
</html>
