<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>SHHi – Secure SSH GUI Client</title>
  <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Outfit', sans-serif;
      background: #0e0e0e;
      color: #f1f1f1;
    }

    header {
      padding: 40px 20px;
      text-align: center;
      background: linear-gradient(135deg, #12c2e9, #c471ed, #f64f59);
      color: white;
    }

    header h1 {
      font-size: 3em;
      margin: 0;
    }

    header p {
      font-size: 1.3em;
      margin-top: 10px;
    }

    section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
    }

    .features {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 20px;
    }

    .feature {
      background: #1a1a1a;
      padding: 20px;
      border-radius: 12px;
      border: 1px solid #333;
    }

    .feature h3 {
      margin-top: 0;
      color: #33ccff;
    }

    .cta {
      text-align: center;
      margin-top: 50px;
    }

    .btn {
      display: inline-block;
      background: #33ccff;
      color: black;
      font-weight: bold;
      padding: 14px 28px;
      text-decoration: none;
      border-radius: 8px;
      transition: 0.2s ease;
    }

    .btn:hover {
      background: #1ec9ff;
    }

    footer {
      text-align: center;
      padding: 20px;
      color: #666;
    }

    @media (max-width: 700px) {
      .features {
        grid-template-columns: 1fr;
      }

      header h1 {
        font-size: 2.2em;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>SHHi</h1>
    <p>A sleek SSH terminal for connecting to your Raspberry Pi securely and easily</p>
  </header>

  <section>
    <h2>Features</h2>
    <div class="features">
      <div class="feature">
        <h3>🖥️ Real Terminal Interface</h3>
        <p>Run commands like <code>ls</code>, <code>cat</code>, <code>top</code>, and get real-time output from your Pi.</p>
      </div>
      <div class="feature">
        <h3>🔐 Secure Connection</h3>
        <p>Connect safely to your Pi using SSH credentials. Key-based authentication support coming soon.</p>
      </div>
      <div class="feature">
        <h3>📡 Remote Access</h3>
        <p>Connect over different networks — works great with port forwarding, VPNs, or tools like Ngrok.</p>
      </div>
      <div class="feature">
        <h3>🧠 Built with Python</h3>
        <p>Uses CustomTkinter and Paramiko under the hood, for performance and flexibility.</p>
      </div>
    </div>

    <div class="cta">
        <a href="https://drive.google.com/uc?export=download&id=1bds3pAJBQPKNcz1ltq7KuEga8LQV9fIe" class="btn" target="_blank" rel="noopener noreferrer">Download SHHi</a>
    </div>
  </section>

  <footer>
    © 2025 SHHi. Built with 💻 by Caca
  </footer>

</body>
</html>
