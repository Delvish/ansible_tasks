# Запуск
```bash
ansible-playbook -i inventory.ini site.yml
```

# Выполняемые роли
- шифрует /dev/xvdf
- монтирует в /mnt/crypted
- выключаем c-state
- governor -> performance
- переименование enX0 -> net0
- вывод CPU info
