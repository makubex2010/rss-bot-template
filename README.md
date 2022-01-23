## RSS-BOT

使用 heroku 部屬的 RSS 機器人。 [核心程式](https://github.com/makubex2010/flowerss-bot)

## Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/makubex2010/RSS-BOT)

## 部屬教學

1.將 RSS-BOT 分叉（fork）到自己的帳戶下。

2.Heroku部屬後再到你Heroku APP裡的Deploy，連接你的Github Fork
![image](https://user-images.githubusercontent.com/67411136/148095858-bdb10898-75a0-46ff-898d-51d7b056c450.png)

3.開啟Automatic Deploys，在Deploy Barnch，等他跑完
![image](https://user-images.githubusercontent.com/67411136/148096028-f7d0f397-ac5b-4aa8-9cbd-ae0cb3d18ee9.png)

4.將你的配置添加到 config.yml.sample，並把名稱修改成 config.yml，如果你不知道其他配置的作用，請不要動它們。

![image](https://user-images.githubusercontent.com/67411136/128676810-c80a8e98-33f5-49e5-9ca2-2d84add6f563.png)

5.請使用 JawsDB MySQL (for heroku) 來保存 RSS 配置。 在config.yml中的mysql下添加。

JAWSDB網址在Settings

![image](https://user-images.githubusercontent.com/67411136/148096408-eddec06b-cb73-47fc-86bf-e57e309cbd18.png)

Reveal Config Vars點開就會看到了

## 示例： JAWSDB_URL

mysql://"mysql-user":"mysql-password"@"mysql-host"/"mysql-database"

mysql-port 的默認端口號是 3306。

![image](https://user-images.githubusercontent.com/67411136/128677426-d72339f5-d271-42cb-9339-fbaea60ed91f.png)
