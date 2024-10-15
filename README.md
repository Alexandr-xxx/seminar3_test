# Создали удаленный репозиторий seminar3_test

# Тестируем работу по синхронизации изменений в локальном и удаленном репозитории:

1. Добавили текс в локальном репозитории (на компьютере), для проверки изменений в удаленном репозитории (на GitHub).
Мы увидим изменения на GitHab только после выполнения команды (git push) на компьютере.

2. Добавили текс в удаленном репозитории (на GitHub), для проверки изменений в локальном репозитории (на компьютере).
Мы увидим изменения только после выполнения команды (git pull) на компьютере.

3. Добавили текс в локальном репозитории (на компьютере), для проверки изменений / проверки слияния удаленного и локального репозитория. При условии, что мы также внесем изменения в удаленном репозитории (на GitHub) и команды (push и pull) выполним после изменений в обоих репозитариях (локальном и удаленном).

*(Добавили текс в удаленном репозитории (на GitHubе), для проверки изменений / проверки слияния удаленного и локального репозитория. При условии, что мы также внесли изменения в локальном репозитории (на компьютере) и команды (push и pull) выполним после изменений в обоих репозитариях (локальном и удаленном).)* 
> Этот текст (выделен курсивом) был добавлен в удаленном репозитории (на GitHab).

4. Создали новую ветку (main_edits).
> Текст под пунктом 4 написан в локальном репозитории.

5. Псоле выполнения команды (push) ветка **main_edits** осталась в удаленном репозитории (хотя в локальном репозитории мы её удалили).
Эту ветку можно удалить непосредственно в GitHub (в личном кабинете) или в при помощи команды (git push origin --delete main_edits)

Еще раз создаем конфликт (текст написан в GitHab).
Снова создаем конфликт (текст написан в локальном репозитории)
