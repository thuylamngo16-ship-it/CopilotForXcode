<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Em xin lỗi chị 2 💖</title>
<style>
body {
  background: radial-gradient(circle at center, #ffe6f2, #ffcce0, #ff99c2);
  overflow: hidden;
  height: 100vh;
  margin: 0;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  font-family: 'Poppins', sans-serif;
}
button {
  background: linear-gradient(45deg, #ff6ec7, #ff3cac);
  border: none;
  color: white;
  padding: 14px 28px;
  border-radius: 50px;
  font-size: 20px;
  font-weight: bold;
  box-shadow: 0 0 20px rgba(255, 102, 204, 0.6);
  cursor: pointer;
  transition: transform 0.2s;
}
button:hover {
  transform: scale(1.1);
}
.sparkle {
  position: absolute;
  font-size: 28px;
  animation: rise 3s ease-out forwards;
  color: #fff;
  text-shadow: 0 0 10px #fff, 0 0 20px #ff66cc, 0 0 30px #ff3399;
}
@keyframes rise {
  0% { transform: translateY(0) scale(1); opacity: 1; }
  100% { transform: translateY(-250px) scale(0.5); opacity: 0; }
}
</style>
</head>
<body>
<button onclick="showMessage()">Nhấn vô nè 💫</button>

<script>
function showMessage() {
  for (let i = 0; i < 15; i++) {
    const s = document.createElement('div');
    s.className = 'sparkle';
    s.innerText = 'Em xin lỗi chị 2 💖';
    s.style.left = Math.random() * window.innerWidth + 'px';
    s.style.top = window.innerHeight - 50 + 'px';
    document.body.appendChild(s);
    setTimeout(() => s.remove(), 3000);
  }
}
</script>
</body>
</html>
