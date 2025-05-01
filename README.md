# interactive-task
«Қазақ тілі сабағында жаңа сөздер арқылы ауызекі тілде сөйлеу дағдысын қалыптастыру»
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Интерактивное задание</title>
</head>
<body>
  <h1>Сколько будет 6 × 7?</h1>
  <input type="text" id="answer">
  <button onclick="checkAnswer()">Проверить</button>
  <p id="result"></p>

  <script>
    function checkAnswer() {
      const ans = document.getElementById('answer').value;
      const result = document.getElementById('result');
      if (ans == 42) {
        result.textContent = 'Правильно!';
        result.style.color = 'green';
      } else {
        result.textContent = 'Неправильно, попробуй ещё раз.';
        result.style.color = 'red';
      }
    }
  </script>
</body>
</html>
