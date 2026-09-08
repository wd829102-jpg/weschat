# weschat
social media
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>WesChat</title>  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
    }

    body {
      background: #f4f6f8;
      color: #111;
    }

    header {
      background: #111827;
      color: white;
      padding: 18px;
      text-align: center;
      font-size: 26px;
      font-weight: bold;
    }

    .hero {
      padding: 55px 20px;
      text-align: center;
      background: white;
    }

    .hero h1 {
      font-size: 42px;
      margin-bottom: 15px;
    }

    .hero p {
      color: #666;
      font-size: 18px;
      margin-bottom: 25px;
    }

    .buttons button {
      border: none;
      padding: 13px 22px;
      margin: 5px;
      border-radius: 8px;
      font-size: 16px;
      cursor: pointer;
    }

    .signup {
      background: #111827;
      color: white;
    }

    .login {
      background: #e5e7eb;
      color: #111;
    }

    .features {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 18px;
      padding: 30px 20px;
      max-width: 1000px;
      margin: auto;
    }

    .card {
      background: white;
      padding: 25px;
      border-radius: 14px;
      text-align: center;
      box-shadow: 0 3px 12px rgba(0,0,0,0.08);
    }

    .card h2 {
      margin-bottom: 10px;
    }

    footer {
      text-align: center;
      padding: 25px;
      color: #777;
    }
  </style></head><body>  <header>
    💬 WesChat
  </header>  <section class="hero">
    <h1>Welcome to WesChat</h1><p>
  Connect, chat and share with your people.
</p>

<div class="buttons">
  <button class="signup" onclick="alert('Sign up coming soon!')">
    Sign Up
  </button>

  <button class="login" onclick="alert('Login coming soon!')">
    Login
  </button>
</div>

  </section>  <section class="features"><div class="card">
  <h2>💬 Chat</h2>
  <p>Chat with your friends and connect instantly.</p>
</div>

<div class="card">
  <h2>👥 Groups</h2>
  <p>Create groups and talk with everyone together.</p>
</div>

<div class="card">
  <h2>👤 Profiles</h2>
  <p>Create your own profile and show your style.</p>
</div>

  </section>  <footer>
    © 2026 WesChat. All rights reserved.
  </footer></body>
</html>