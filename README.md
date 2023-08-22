# Тестовое задание Neostack на позицию Frontend-разработчика

## Docker 
Для того, чтобы запустить приложение с помощью докера, необходимо ввести следующие команды:
### `docker build -t neostack_frontend_app .`
### `docker run -p 3000:3000 neostack_frontend_app.`

Откройте [http://localhost:3000](http://localhost:3000) чтобы посмотреть приложение в браузере.

## pnpm
Для того, чтобы запустить приложение с помощью pnpm, необходима версия nodejs не ниже 18 версии.
Чтобы собрать приложение необходимо установить следующие зависимости.
### `npm install -g pnpm`.
После чего, необходимо собрать проект командой.
### `pnpm install`
### `pnpm start`

Откройте [http://localhost:3000](http://localhost:3000) чтобы посмотреть приложение в браузере.
