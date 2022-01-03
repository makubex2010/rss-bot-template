# rss-bot
使用 heroku 部屬的 RSS 機器人。 使用源代碼來自於 indes/flowerss-bot。

將 rss-bot 分叉（fork）到自己的帳戶下。將您的配置添加到 config.yml.sample，並把名稱修改成 config.yml，如果您不知道其他配置的作用，請不要動它們。

![image](https://user-images.githubusercontent.com/67411136/128676810-c80a8e98-33f5-49e5-9ca2-2d84add6f563.png)

請使用 ClearDB MySQL (for heroku) 來保存 RSS 配置。 在config.yml中的mysql下添加。

示例： CLEARDB_DATABASE_URL

mysql://"mysql-user":"mysql-password"@"mysql-host"/mysql-database"

mysql-port 的默認端口號是 3306。

![image](https://user-images.githubusercontent.com/67411136/128677426-d72339f5-d271-42cb-9339-fbaea60ed91f.png)

## heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/makubex2010/rss-bot)
  
## 來源
- [indes](https://github.com/indes) for [flowerss-bot](https://github.com/indes/flowerss-bot)
