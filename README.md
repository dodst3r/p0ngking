# p0ngking
Игра Pong - это классическая видеоигра, в которой два игрока управляют платформами на противоположных концах экрана и отбивают мяч между собой. Целью игры является забивание очков путем отбивания мяча так, чтобы он пролетел мимо платформы противника.
#GAMEPLAY
![STARTgits](https://github.com/dodst3r/p0ngking/assets/165890625/1e8f069a-6fec-4da7-b9d3-3db7bcdd8585)
![pggamesuai](https://github.com/dodst3r/p0ngking/assets/165890625/81865528-f984-4316-9f3f-49b1a458d696)
#Технологии
Движок проекта Unity
Язык программирования C#
Среда разработки Microsoft Visual Studio
#Техническое описание проекта
УСТАНОВКА И ЗАПУСК: 1. Клонируйте репозиторий с игрой "Pong King" с помощью git clone [https](https://github.com/dodst3r/p0ngking.git
2. Откройте проект в Unity 
3. В меню Unity выберите file -> Build Settings -->> выберите вашу платформу и нажмите Build для создания исполняемого файла.
4. Вы великолепны!

#Описание скрипта BallMovement.cs
Invoke() через 2 секунды после запуска игры мяч входит в игру
StartBall() запускает мяч в начальную позицию
ResetBall() Возвращает мяч в начальную позицию
PlayerBounce() Присваивает мячу новую скорость 
OnCollisionEnter2D() Обрабатывает столкновение мяча
OnTriggerEnter2D() Увеличивает счет игрока/ai
#Описание скрипта PlayerMovement.cs
Update() Проверяет  значение IsAi
PlayerControl()  Обрабатывает  ввод  игрока
AIControl() Управляет  движением  ракетки  ИИ
FixedUpdate() устанавливает  скорость  ракетки  в  соответствии  с  направлением  движения  и  скоростью
#Контакты
Разработчик: Лобанов Андрей Дмитриевич
Электронная почта: matdrakonov9@gmail.com
