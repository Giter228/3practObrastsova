# Используем базовый образ Dart
FROM dart:stable

# Устанавливаем рабочую директорию
WORKDIR /app

# Копируем файлы программы в контейнер
COPY calc.dart .

# Компилируем программу Dart (опционально)
RUN dart compile exe calc.dart -o calc

# Указываем команду для запуска программы
CMD ["./calc"]