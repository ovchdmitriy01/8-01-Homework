# Домашнее задание к занятию «Git»

### Задание 1

**Что нужно сделать:**

1. Зарегистрируйте аккаунт на [GitHub](https://github.com/).

<a href="https://ibb.co/v4d7v92"><img src="https://i.ibb.co/v4d7v92/8-1-1-1.png" alt="8-1-1-1" border="0"></a>

2. Создайте публичный репозиторий. Обязательно поставьте галочку в поле «Initialize this repository with a README».

<a href="https://ibb.co/SVmW6LP"><img src="https://i.ibb.co/SVmW6LP/8-1-1-2.png" alt="8-1-1-2" border="0"></a>

3. Склонируйте репозиторий, используя https протокол `git clone ...`.

<a href="https://ibb.co/7n6xFvz"><img src="https://i.ibb.co/7n6xFvz/8-1-1-3.png" alt="8-1-1-3" border="0"></a>

4. Перейдите в каталог с клоном репозитория.

<a href="https://ibb.co/JvcqJdR"><img src="https://i.ibb.co/JvcqJdR/8-1-1-4.png" alt="8-1-1-4" border="0"></a>

5. Произведите первоначальную настройку Git, указав своё настоящее имя и email: `git config --global user.name` и `git config --global user.email johndoe@example.com`.

<a href="https://ibb.co/zQkQHfH"><img src="https://i.ibb.co/zQkQHfH/8-1-1-5.png" alt="8-1-1-5" border="0"></a>

6. Выполните команду `git status` и запомните результат.

<a href="https://ibb.co/Y73xYcM"><img src="https://i.ibb.co/Y73xYcM/8-1-1-6.png" alt="8-1-1-6" border="0"></a>

7. Отредактируйте файл README.md любым удобным способом, переведя файл в состояние Modified.

<a href="https://ibb.co/vL4VmRZ"><img src="https://i.ibb.co/vL4VmRZ/8-1-1-7.png" alt="8-1-1-7" border="0"></a>

8. Ещё раз выполните `git status` и продолжайте проверять вывод этой команды после каждого следующего шага.

<a href="https://ibb.co/4RRSS67"><img src="https://i.ibb.co/4RRSS67/8-1-1-8.png" alt="8-1-1-8" border="0"></a>

9. Посмотрите изменения в файле README.md, выполнив команды `git diff` и `git diff --staged`.

<a href="https://ibb.co/QfbNBtN"><img src="https://i.ibb.co/QfbNBtN/8-1-1-9.png" alt="8-1-1-9" border="0"></a>

10. Переведите файл в состояние staged или, как говорят, добавьте файл в коммит, командой `git add README.md`.

<a href="https://ibb.co/nRCMgYP"><img src="https://i.ibb.co/nRCMgYP/8-1-1-10.png" alt="8-1-1-10" border="0"></a>

11. Ещё раз выполните команды `git diff` и `git diff --staged`.

<a href="https://ibb.co/J71CKLn"><img src="https://i.ibb.co/J71CKLn/8-1-1-11.png" alt="8-1-1-11" border="0"></a>

12. Теперь можно сделать коммит `git commit -m 'First commit'`.

<a href="https://ibb.co/mRkFCHh"><img src="https://i.ibb.co/mRkFCHh/8-1-1-12.png" alt="8-1-1-12" border="0"></a>

13. Сделайте `git push origin master`.

<a href="https://ibb.co/VwwjdH9"><img src="https://i.ibb.co/VwwjdH9/8-1-1-13.png" alt="8-1-1-13" border="0"></a>
<a href="https://ibb.co/ZMGt391"><img src="https://i.ibb.co/ZMGt391/8-1-1-14.png" alt="8-1-1-14" border="0"></a>
<a href="https://ibb.co/dg1n1rV"><img src="https://i.ibb.co/dg1n1rV/8-1-1-15.png" alt="8-1-1-15" border="0"></a>

В качестве ответа добавьте ссылку на этот коммит в ваш md-файл с решением.

[Ссылка](https://github.com/ovchdmitriy01/my-first-github/commit/4f47f31b23942488aadddd47f3bbcf8feb596ed5)

---

### Задание 2

**Что нужно сделать:**

1. Создайте файл .gitignore (обратите внимание на точку в начале файла) и проверьте его статус сразу после создания.

<a href="https://ibb.co/DknYmYS"><img src="https://i.ibb.co/DknYmYS/8-1-2-1.png" alt="8-1-2-1" border="0"></a>

2. Добавьте файл .gitignore в следующий коммит `git add...`.

<a href="https://ibb.co/p4J0L7M"><img src="https://i.ibb.co/p4J0L7M/8-1-2-2.png" alt="8-1-2-2" border="0"></a>

3. Напишите правила в этом файле, чтобы игнорировать любые файлы `.pyc`, а также все файлы в директории `cache`.

<a href="https://ibb.co/JksDNxz"><img src="https://i.ibb.co/JksDNxz/8-1-2-3.png" alt="8-1-2-3" border="0"></a>


4. Сделайте коммит и пуш.

<a href="https://ibb.co/PQh4T9x"><img src="https://i.ibb.co/PQh4T9x/8-1-2-4.png" alt="8-1-2-4" border="0"></a>
<a href="https://ibb.co/JKM5b8g"><img src="https://i.ibb.co/JKM5b8g/8-1-2-4-1.png" alt="8-1-2-4-1" border="0"></a>

В качестве ответа добавьте ссылку на этот коммит в ваш md-файл с решением.

[Ссылка](https://github.com/ovchdmitriy01/my-first-github/commit/191d2f8bd0d3434896686ea907193d3ec03f0eda)


### Задание 3

**Что нужно сделать:**

1. Создайте новую ветку dev и переключитесь на неё.

<a href="https://ibb.co/wgptjxn"><img src="https://i.ibb.co/wgptjxn/8-1-3-1.png" alt="8-1-3-1" border="0"></a>

2. Создайте файл test.sh с произвольным содержимым.

<a href="https://ibb.co/fMbj1FK"><img src="https://i.ibb.co/fMbj1FK/8-1-3-2.png" alt="8-1-3-2" border="0"></a>
<a href="https://ibb.co/B6hdcV9"><img src="https://i.ibb.co/B6hdcV9/8-1-3-2-1.png" alt="8-1-3-2-1" border="0"></a>

3. Сделайте несколько коммитов и пушей, имитируя активную работу над этим файлом.

<a href="https://ibb.co/tLVSzwv"><img src="https://i.ibb.co/tLVSzwv/8-1-3-3.png" alt="8-1-3-3" border="0"></a>

   4. Сделайте мердж этой ветки в основную. Сначала нужно переключиться на неё, а потом вызывать `git merge`.

<a href="https://ibb.co/LhFKDTh"><img src="https://i.ibb.co/LhFKDTh/8-1-3-4.png" alt="8-1-3-4" border="0"></a>

5. Сделайте коммит и пуш.

<a href="https://ibb.co/CBbkyCM"><img src="https://i.ibb.co/CBbkyCM/8-1-3-5.png" alt="8-1-3-5" border="0"></a>
<a href="https://ibb.co/2ccJJ18"><img src="https://i.ibb.co/2ccJJ18/8-1-3-5-1.png" alt="8-1-3-5-1" border="0"></a>
<a href="https://ibb.co/MPbLXbs"><img src="https://i.ibb.co/MPbLXbs/8-1-3-5-2.png" alt="8-1-3-5-2" border="0"></a>

[Ссылка](https://github.com/ovchdmitriy01/my-first-github2/network)


---
