- 👋 Hi, I’m @kR1SH1337
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
kR1SH1337/kR1SH1337 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
# Исходная строка
sample_string = "Twinkle, twinkle, little star, How I wonder what you are! Up above the world so high, Like a diamond in the sky. Twinkle, twinkle, little star, How I wonder what you are"

# Разбиваем строку на строки по точке и пробелу
lines = sample_string.split('. ')

# Инициализируем уровень отступа
indentation = 0

# Перебираем строки и выводим их с соответствующими отступами
for line in lines:
    if line.startswith("Twinkle"):
        print(line)
    else:
        print("    " * indentation + line)
    indentation += 1
