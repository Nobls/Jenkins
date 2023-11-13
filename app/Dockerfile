FROM node:18.4-alpine

# Создаем рабочую директорию
WORKDIR /app

# Копируем исходный код в рабочую директорию
COPY . .

# Устанавливаем зависимости
RUN npm install

# Собираем приложение
RUN npm run build

# Запускаем приложение
EXPOSE 3000
CMD ["npm", "run", "start"]