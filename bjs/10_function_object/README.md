## Практика модуль 11

<img src="https://lms.skillfactory.ru/assets/courseware/v1/21b62d5adffec54fac7047c1ed8a63e2/asset-v1:SkillFactory+PHP-2.0+2020+type@asset+block/m16_cover_practice.svg" style="height:500px ">

Создание [**генератора случайных**](https://deflion.github.io/php/bjs/10_function_object/project) пользовательских данных: ФИО, пола, даты рождения и профессии. С возможностью сбрасывать информацию.

Выбор данных происходит из заготовленных JSON значений с помощью `Math.random`.

<br>
<hr>
<br>

### 0 баллов

- [ ] Не выполнены условия на отметку 5.

### 5 баллов

- [ ] Добавлено CSS оформление.
- [x] Добавлен пол, год рождения и фамилия.
- [x] Имя и фамилия привязаны к полу. Для женских фамилий должно быть окончание на «а»: «Елена Морозова».

<hr>

### 10 баллов

- [ ] Выполнены условия на отметку 5.
- [ ] Добавлена генерация закреплённого за полом отчества в отдельном объекте, полученном от кода JSON . Не должно встречаться генерации мужского отчества в женской фамилии и имени.
- [ ] Добавлена профессия, есть её связь с полом. Например, женские имена и фамилии не могут быть слесарем, солдатом, шахтёром и так далее.

<hr>

### 15 баллов

- [ ] Выполнены условия на отметку 10.
- [ ] Добавлена генерация дня и месяца рождения. Месяц рождения написан текстом, например: «апреля», «мая».
- [ ] Ограничьте генерацию дней для месяцев, в которых встречается 28 и 30 дней.

<hr>

### 20 балла

- [ ] Выполнены условия на отметку 15.
- [ ] Добавлена кнопка, активирующая генерацию всех данных.
- [ ] Добавлена кнопка очистки данных.