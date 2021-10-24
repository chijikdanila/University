<h1> 
  University
</h1>

<div>
  Условие лабораторной: Ведомость абитуриентов, сдавших вступительные экзамены в университет, содержит: Ф.И.О. абитуриента, оценки. Определить средний балл по университету и вывести список абитуриентов, средний балл которых выше среднего балла по университету. Первыми в списке должны идти студенты, сдавшие все экзамены на 5.
</div>

<h2>
  Функционал
</h2>
<ol>
  <li>Предусмотрена возможность ввода/вывода элементов в отдельном активити (Add student button).</li>
  <li>Добавлена возможность редактирования списка, удаления отдельных позиций.</li>
  <li>Меню доступных функций показывается по долгому нажатию на элемент списка (функции редактирования и удаления элемента).</li>
  <li>Создан собственный адаптер для списка (StudentAdapter).</li>
  <li>Реализована функция открытия файла и заполнения из него полей списка с помощью парсера (Choose file button).</li>
  <li>Задание варианта (вывести список абитуриентов, средний балл которых выше среднего балла по университету) выполняется по нажатию кнопки Sort</li>
</ol>

<h2>
  Ссылки на элементы проекта
</h2>


  - [activity_main.xml](./app/src/main/res/layout/activity_main.xml)
  - [activity_add.xml](./app/src/main/res/layout/activity_add.xml) - для AddActivity
  - [activity_edit.xml](./app/src/main/res/layout/activity_edit.xml) - для EditActivity
  - [item.xml](./app/src/main/res/layout/item.xml)  - для отображения элемента списка ListView с помощью StudentAdapter
  - [MainActivity](./app/src/main/java/com/example/university/MainActivity.java)
  - [AddActivity](./app/src/main/java/com/example/university/AddActivity.java) - для добавления студента
  - [EditActivity](./app/src/main/java/com/example/university/EditActivity.java) - для редактирования студента
  - [Student](./app/src/main/java/com/example/university/Student.java)
  - [StudentAdapter](./app/src/main/java/com/example/university/StudentAdapter.java) - собственный адаптер

 ---
 
<p align="center">
  <img src="images/Menu.jpg" width="300">
  <img src="images/AddStudent.jpg" width="300">
</p>

 ---
 
<p align="center">
  <img src="images/MenuWithStudent.jpg" width="300">
  <img src="images/FunctionsMenu.jpg" width="300">
</p>
