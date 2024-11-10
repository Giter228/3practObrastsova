# Используем базовый образ OpenJDK
FROM openjdk:17-slim

# Устанавливаем рабочую директорию
WORKDIR /app

# Копируем файлы программы в контейнер
COPY game.java .

# Компилируем программы
RUN javac game.java

# Указываем команду для запуска программы
CMD ["java", "game"]
