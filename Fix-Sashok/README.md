Fix-Sashok  
==========
Модифицированная и улучшенная версия лаунчера для игры Minecraft от Sashok724  
  
### Структура клиента
* clients/assets/ ресурс файлы. При режиме zip clients/assets.zip
* clients/name/config.zip конфиги модов и ресурскаки, расспаковывается в корень папки клиента.
* clients/name/bin/ jar файлы клиента (можно использовать подпапки типа bin/libraries/)
* clients/name/mods/ файлы модов (можно использовать подпапки)
* clients/name/coremods/ файлы модов ядра (используется только устаревшими версиями minecraft). Оставить пустой, если не требуется.
* clients/name/natives/ нативы для lwjgl.

Ссылки для авторизации 1.7.2-1.8.1 указываем в классе YggdrasilMinecraftSessionService.class
"https://sessionserver.mojang.com/session/minecraft/" -> "http://minecraft/site/"
"https://sessionserver.mojang.com/session/minecraft/join" -> "http://minecraft/site/j.php"
"https://sessionserver.mojang.com/session/minecraft/hasJoined" -> "http://minecraft/site/h.php"
"https://sessionserver.mojang.com/session/minecraft/profile/" -> "http://minecraft/site/s.php?user="