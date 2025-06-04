# Test task 3205

### Frontend:

- **React** + **Ant Design** + **Vite**

### Backend:

- **Express** + **PostgreSQL** + **TypeORM**

## Запуск проекта

1. Инициализировать git-репозиторий:
   ```sh
   git init
   ```
2. Клонировать репозиторий:
   ```sh
   git clone https://github.com/Xuchaku/3205test.git
   ```
3. Перейти в папку проекта:
   ```sh
   cd ./3205test
   ```
4. Запустить контейнеры с помощью Docker:
   ```sh
   docker-compose up
   ```

## Дополнительная информация

- Убедитесь, что у вас установлен [Docker](https://www.docker.com/) и [Docker Compose](https://docs.docker.com/compose/).
- Для остановки контейнеров используйте:
  ```sh
  docker-compose down
  ```
- Если не получается запустить через Docker, установите зависимости вручную и запустите проект:

  **Для backend:**
  Добавить env файл с DB_HOST, DB_PORT, DB_USER, DB_PASSWORD, DB_NAME либо использовать переменные по умолчанию объявленные в dataSource.ts

  ```sh
  cd back
  npm install
  npm run dev
  ```

  **Для frontend:**

  ```sh
  cd front
  npm install
  npm run dev
  ```
