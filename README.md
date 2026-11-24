## Установка

Заменить `/hive/bin/wd` на модифицированную версию (с бэкапом и перезапуском watchdog):

```bash
cp /hive/bin/wd /hive/bin/wd.bak.$(date +%s) && wget -qO /hive/bin/wd https://raw.githubusercontent.com/IIIMaxIII/hive_mod/main/wd && chmod +x /hive/bin/wd && systemctl restart hive-watchdog
