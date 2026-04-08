<!DOCTYPE html>

<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Nitin Rawat — LinkedIn Profile</title>

<style>
  * { box-sizing: border-box; margin: 0; padding: 0; }

  body {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
    background: #f3f2ef;
    color: #000;
  }

  .container {
    max-width: 740px;
    margin: 32px auto;
    padding: 0 16px 64px;
  }

  .card {
    background: #fff;
    border-radius: 10px;
    border: 1px solid #e0e0e0;
    margin-bottom: 12px;
    overflow: hidden;
  }

  .hero-banner {
    height: 120px;
    background: linear-gradient(135deg, #0a66c2, #004182);
  }

  .hero-body {
    padding: 0 24px 20px;
    position: relative;
  }

  .avatar {
    width: 88px;
    height: 88px;
    border-radius: 50%;
    background: #0a66c2;
    border: 4px solid #fff;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 28px;
    font-weight: 700;
    color: #fff;
    margin-top: -44px;
    margin-bottom: 12px;
    cursor: pointer;
  }

  .hero-name { font-size: 22px; font-weight: 700; margin-bottom: 4px; }
  .hero-headline { font-size: 14px; color: #333; line-height: 1.5; }
  .hero-location { font-size: 13px; color: #0a66c2; margin-top: 6px; }

  .btn-row {
    display: flex;
    gap: 8px;
    margin-top: 14px;
  }

  .btn-primary {
    background: #0a66c2;
    color: #fff;
    border: none;
    padding: 8px 20px;
    border-radius: 20px;
    cursor: pointer;
  }

  .btn-secondary {
    background: #fff;
    color: #0a66c2;
    border: 1.5px solid #0a66c2;
    padding: 7px 20px;
    border-radius: 20px;
    cursor: pointer;
  }

  .section { padding: 20px 24px; }
  .section-title { font-size: 18px; font-weight: 700; margin-bottom: 16px; }

  .connect-box {
    background: #eef3f8;
    border-radius: 8px;
    padding: 16px;
  }

  .connect-text {
    font-size: 13px;
    line-height: 1.6;
  }

  .copy-btn {
    margin-top: 10px;
    background: #0a66c2;
    color: #fff;
    border: none;
    padding: 7px 16px;
    border-radius: 16px;
    cursor: pointer;
  }
</style>

</head>

<body>

<div class="container">

  <div class="card">
    <div class="hero-banner"></div>

```
<div class="hero-body">
  <div class="avatar">NR</div>
  <div class="hero-name">Nitin Rawat</div>
  <div class="hero-headline">
    Data Analyst | SQL · Python · Power BI · AWS
  </div>
  <div class="hero-location">Delhi, India</div>

  <div class="btn-row">
    <button type="button" class="btn-primary">Connect</button>
    <button type="button" class="btn-secondary">Message</button>
  </div>
</div>
```

  </div>

  <div class="card">
    <div class="section">
      <div class="section-title">Connection request message</div>

```
  <div class="connect-box">
    <div class="connect-text" id="connect-msg">
```

Hi [Name], I came across your profile and love what your team is building. I'm a Data Analyst with experience in SQL, Python, and Power BI, currently exploring new opportunities. Would be great to connect! </div>

```
    <button type="button" class="copy-btn" onclick="copyMsg()">Copy message</button>
  </div>
</div>
```

  </div>

</div>

<script>
function copyMsg() {
  const text = document.getElementById('connect-msg').innerText;

  const textarea = document.createElement("textarea");
  textarea.value = text;

  // Mobile safe
  textarea.setAttribute("readonly", "");
  textarea.style.position = "absolute";
  textarea.style.left = "-9999px";

  document.body.appendChild(textarea);
  textarea.select();

  try {
    document.execCommand("copy");

    const btn = document.querySelector('.copy-btn');
    btn.textContent = "Copied!";
    setTimeout(() => {
      btn.textContent = "Copy message";
    }, 2000);

  } catch (err) {
    alert("Copy failed. Please copy manually.");
  }

  document.body.removeChild(textarea);
}
</script>

</body>
</html>
