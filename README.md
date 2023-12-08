# Git commands
Стратегии ветвления в Git
Git Flow
main/master/stable - long-term (только для проверенного, оттестированного кода - “священный грааль”)
develop/current - long-term (для тестирования, текущая разработка)
login/bugfix1/payments - short-term
GitHub Flow
main/master/stable - long-term
login/bugfix1/payments - short-term
Базовые команды по работе с ветками в Git
git branch просмотр веток
git branch -avv подробный вывод
выйти из просмотра - q
git branch новая_ветка создать ветку
git branch новая_ветка старая_ветка
git checkout ветка переключиться на ветку
git checkout - переключиться на предыдущую ветку
ПЕРЕКЛЮЧАТЬСЯ НЕОБХОДИМО С “ЧИСТЫМ СТАТУСОМ”
git checkout -b новая_ветка создать и переключиться
git checkout -b новая_ветка старая_ветка
git branch -D ветка удалить ветку (локально)
git merge название_ветки слияние веток
git push origin --delete ветка удалить ветку (дистанционную)
git branch -m новое_название переименовать ветку (локально)
