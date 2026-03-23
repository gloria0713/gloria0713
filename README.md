<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Personal Page</title>

  <!-- 字体 -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600&display=swap" rel="stylesheet">

  <style>
    :root {
      --bg: #f6f7fb;
      --text: #2e2e2e;
      --muted: #777;
    }
    * { box-sizing: border-box; }
  body::before {
  content: "";
  position: fixed;
  inset: 0;
  background:
    radial-gradient(circle at 20% 30%, rgba(170, 200, 255, 0.35), transparent 40%),
    radial-gradient(circle at 80% 20%, rgba(255, 190, 220, 0.35), transparent 40%),
    radial-gradient(circle at 50% 80%, rgba(200, 255, 220, 0.35), transparent 40%);
  filter: blur(60px);
  animation: floatLights 20s ease-in-out infinite;
  z-index: -1;
}
@keyframes floatLights {
  0% { transform: translateY(0px); }
