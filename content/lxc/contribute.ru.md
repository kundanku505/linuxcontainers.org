# Исходный код
Текущая разрабатываемая версия LXC может быть склонирована с Github:

    git clone git://github.com/lxc/lxc

Также доступны архивы TAR с исходным кодом различных стабильных релизов
на странице [загрузок](/lxc/downloads/).

Патчи, посланные в upstream на рассмотрение должны базироваться на текущем дереве git  
а не на стабильных релизах, если только ошибка не затрагивает стабильный релиз.

# Процесс приема патчей
Каждый посланный патч должен быть signed off его автором.

Это просто сделать с помощью : `git commit -s`

или если вы забыли "-s" в предыдущем коммите : `git commit --amend -s`

## Способ со списком рассылки электронной почты
Вы можете вносить вклад в LXC отправляя патчи или наборы патчей напрямую
в [список рассылки lxc-devel](https://lists.linuxcontainers.org/listinfo/lxc-devel).

Вы можете использовать `git format-patch` для создания годящегося к отправке патча.

Избегайте "копирования/вставки" в почтовые клиенты, так как они могут испортить отступы и переносы строк (узнайте про `git send-email` или `git imap-send`).

## Способ с пулл-реквестом
Форкните репозиторий, создайте ветку, закоммитьте свою работу (with -s !), и пушните ее.

А затем следуйте [помощи github's](https://help.github.com/articles/creating-a-pull-request/).