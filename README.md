# nautilus-crontab

open nautilus every minutes with crontab on ubuntu

### Demo

[Screencast from 2023-03-06 12-43-33.webm](https://user-images.githubusercontent.com/30729921/223029242-258b1843-1a48-4170-b94f-02c6b825b01d.webm)

### Installation

```sh
sudo apt install cron
```

```sh
crontab -e
```

```sh
* * * * * DISPLAY=:1 /usr/bin/nautilus
```

```sh
sudo service cron restart
```
