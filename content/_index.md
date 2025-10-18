---
title: "Портфолио"
type: "home"
---

<div style="text-align: center; margin: 40px 0;">
  <button onclick="showYear(1)" style="padding: 10px 20px; margin: 5px; border: 2px solid #007bff; background: white; color: #007bff; cursor: pointer; border-radius: 5px; font-size: 16px;" class="year-btn active">1 курс</button>
  <button onclick="showYear(2)" style="padding: 10px 20px; margin: 5px; border: 2px solid #007bff; background: white; color: #007bff; cursor: pointer; border-radius: 5px; font-size: 16px;" class="year-btn">2 курс</button>
  <button onclick="showYear(3)" style="padding: 10px 20px; margin: 5px; border: 2px solid #007bff; background: white; color: #007bff; cursor: pointer; border-radius: 5px; font-size: 16px;" class="year-btn">3 курс</button>
  <button onclick="showYear(4)" style="padding: 10px 20px; margin: 5px; border: 2px solid #007bff; background: white; color: #007bff; cursor: pointer; border-radius: 5px; font-size: 16px;" class="year-btn">4 курс</button>
</div>

<div id="year1" class="year-content" style="display: block;">

### 1 курс

Материалы первого курса здесь. [Перейти на страницу 1 курса](/1st/)

</div>

<div id="year2" class="year-content" style="display: none;">

### 2 курс

Материалы второго курса здесь. [Перейти на страницу 2 курса](/2nd/)

</div>

<div id="year3" class="year-content" style="display: none;">

### 3 курс

Материалы третьего курса здесь. [Перейти на страницу 3 курса](/3rd/)

</div>

<div id="year4" class="year-content" style="display: none;">

### 4 курс

Материалы четвёртого курса здесь. [Перейти на страницу 4 курса](/4th/)

</div>

<script>
function showYear(year) {
  // Скрыть все
  for (let i = 1; i <= 4; i++) {
    document.getElementById('year' + i).style.display = 'none';
  }
  
  // Показать выбранный
  document.getElementById('year' + year).style.display = 'block';
  
  // Обновить кнопки
  document.querySelectorAll('.year-btn').forEach(btn => {
    btn.style.background = 'white';
    btn.style.color = '#007bff';
  });
  event.target.style.background = '#007bff';
  event.target.style.color = 'white';
}
</script>


# Добро пожаловать!

Это главная страница портфолио.  
Здесь собраны выполненные лабораторные и самостоятельные работы, проекты и материалы по учебным дисциплинам.

---

## Разделы портфолио

- [1 курс](/portfolio1/1st/)
- [2 курс](/portfolio1/2nd/)
- [3 курс](/portfolio1/3rd/)
- [4 курс](/portfolio1/4th/)
- [Обо мне](/portfolio1/about/)
