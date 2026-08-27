<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Test Page</title>
<style>
  html, body {
    margin: 0;
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    background: linear-gradient(135deg, #0f2027, #2c5364, #8e2de2, #ff512f);
    background-size: 400% 400%;
    animation: gradientShift 8s ease infinite;
    font-family: Georgia, "Times New Roman", serif;
  }
 
  @keyframes gradientShift {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
  }
 
  .card {
    background: rgba(255, 255, 255, 0.15);
    backdrop-filter: blur(10px);
    border: 1px solid rgba(255, 255, 255, 0.3);
    border-radius: 20px;
    padding: 2.5rem 3rem;
    box-shadow: 0 8px 32px rgba(0, 0, 0, 0.25);
    max-width: 600px;
    text-align: center;
  }
 
  h1 {
    color: #fff;
    font-size: 1.8rem;
    line-height: 1.4;
    margin: 0;
    text-shadow: 0 2px 8px rgba(0, 0, 0, 0.3);
  }
 
  .emoji {
    font-size: 2.5rem;
    display: block;
    margin-bottom: 1rem;
  }
</style>
</head>
<body>
  <div class="card">
    <span class="emoji">🪐</span>
    <h1>A teaspoon of neutron star would weigh about as much as a tain.</h1>
  </div>
</body>
</html>
 
