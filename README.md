## Комплит инстал гайд
0. скачать данный репозиторий
1. установить [ноду](https://nodejs.org/)
2. установить (настроить и запустить) [Lavalink](https://github.com/freyacodes/Lavalink#server-configuration)
3. установить зависимости через `npm i` в папке проекта

**Раздел [Настройка](#настройка) обязателен к посещению**

## Настройка
### env
Переименуйте файл **`.env.example`** в **`.env`** (если не видите файл, возможно, стоит включить отображение скрытых файлов проводнике)

Теперь про параметры:
 * DS_TOKEN - [токен вашего дискорд бота](https://discord.com/developers/docs/intro#bots-and-apps)
 * DS_PREFIX - то с чего начинается любая команда (например, в команде `!play song` **!** - префикс)
 * VK_TOKEN - см. [Получение вк токена](#получение-вк-токена)
 * LAVA_HOST, LAVA_PASS, LAVA_PORT - соответственно хост, пароль и порт вашего лавалинк сервера

### Получение вк токена
Получить токен можно по [ссылке](https://oauth.vk.com/authorize?client_id=6121396&scope=offline&redirect_uri=https://oauth.vk.com/blank.html&display=page&response_type=token&revoke=1&redirect_uri=close.html), как авторизируетесь в ссылке найдите параметр `access_token`

**Токен этот никому не передавать ради вашей же безопасности**

*Токен бессрочный*

P.S.
Если интересно как это работает, то вот: [ссылка1](https://vk.com/dev/access_token), [ссылка2](https://vk.com/dev/permissions)

## Запуск
`npm run start` в папке проекта

**ЭТО ЗАПУСК БОТА, ЛАВАЛИНК НУЖНО ЗАПУСКАТЬ ОТДЕЛЬНО**
