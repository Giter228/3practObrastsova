# Используем базовый образ OpenJDK
FROM openjdk:17-slim

# Устанавливаем рабочую директорию
WORKDIR /app

# Копируем файлы программы в контейнер
COPY calc.java .

# Компилируем программы
RUN javac calc.java 

# Указываем команду для запуска программы
CMD ["java", "calc"] 
