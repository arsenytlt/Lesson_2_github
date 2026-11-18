Главное правило: изменил файл → git add → git commit → git push.
Если ты хочешь изменить README.md и отправить новую версию на GitHub:
1. Открой файл README.md.
2. Добавь или измени какой-нибудь текст.
3. Сохрани файл (Cmd + S).
4. Выполни команды:
git status
git add README.md
git commit -m "Update README.md"
git push origin main