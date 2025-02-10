# Battle-City-Snap

## Build snap

1. Install snap
```bash
sudo apt update
sudo apt install snapcraft
```
2. Clone repository
```bash 
git clone git@github.com:LiteSoftware/Battle-City-Snap.git
```
3. Build snap package

```bash
cd Battle-City-Snap
snapcraft
```

4. Run snap package

### devmode: 
```bash
sudo snap install --devmode --dangerous <your_snap_file>.snap
```

### strict mode:
```bash
sudo snap install --dangerous <your_snap_file>.snap
```

5. Отправьте Snap в Store
Опубликуйте Snap в Store:

5.1 Загрузите ваш Snap в Store:

```bash
snapcraft upload battle-city-3_<version>_amd64.snap
```


5.2 Укажите канал (например, stable, candidate, beta, edge):

```bash
snapcraft release battle-city-3 <revision> stable
```


<revision> — номер версии, присвоенный Snap Store после загрузки (посмотреть его можно в интерфейсе Snapcraft или с помощью команды snapcraft status battle-city-3).
6. Ожидайте проверки
Snap пройдет автоматическую проверку на соответствие требованиям Store. Если все пройдет успешно, ваш Snap станет доступным для пользователей.
