# Курс математической теории нейронных сетей
## Воронежский государственный университет, математический факультет, кафедра математического моделирования
## Как отправить задание
- Регистрируемся на github
- Кликнуть на Fork (правый верхний угол)
- install git, python=version 3.9.* (пользователям Windows советую также установить git bash для удобной работы)
- В терминале перейдите в папку где будет хранится проект
- На кнопке code в репозитории вашего проекта -> https -> скопировать
- git clone https://github.com/<your_nickname>/math_theory_nn.git
- git config --global user.email "you@example.com"
- git config --global user.name "Your Name"
- Создайте виртуальное окружение для проекта (python3 -m venv .venv), либо без него
- pip3 install --upgrade pip
- pip3 install jupyter (для активации окружения . ./.venv/bin/activate)
- pip3 install notebook
- Unix: jupyter notebook / Windows: python -m notebook
- git checkout -b <surname_name_lection> (пример: ivanov_lection_1) (Переходим на новую ветку)
- откройте блокнот по необходимой лекции
- git add * (после окончания работы)
- git commit -m 'Done exercise <name_lection>'
- git push --set-upstream origin <name_branch>
- Создайте токен на сайте по инструкции: https://docs.github.com/en/github/authenticating-to-github/keeping-your-account-and-data-secure/creating-a-personal-access-token (либо привяжите ssh key на github) 
- При отправке изменений вместо ввода пароля используйте токен
- git push origin <surname_name_lection>:<surname_name_lection>
- на сайте своего репозитория выберите в разделе branch ветку <surname_name_lection> и нажмите compare and pull request 
- выберите zudik/main
- ожидайте отметки в комментарии или в файле results.md
- git fetch - команда для получения новых изменений с репозитория
## Результаты
[Таблица с результатами](results.md)
## Ссылки на задания
[Лекция 1](https://github.com/Zudik/math_theory_nn/blob/main/exercises/lection_1_func_activate.ipynb)
## Полезные ссылки
[Обучение языку программирования Python](https://pythontutor.ru/)
