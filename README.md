## Анализ и софтуерно представяне на данни за продажби

### **Описание на задачата**
Тази програма анализира данни за продажби на различни електронни устройства в световен мащаб. Използват се реалистични данни, за да се извърши статистическа обработка, визуализация и изготвяне на изводи, които подпомагат вземането на бизнес решения.

---

### **Данни**
CSV файлът съдържа следните колони:
- **`Product`**: Име на продукта (напр. "Laptop", "Smartphone").
- **`Region`**: Регион на продажбите (напр. "Europe", "Asia").
- **`Sales`**: Брой продадени единици.
- **`Price`**: Цена на единица в долари.
- **`Date`**: Дата на продажбата.

---

### **Основни функционалности**
1. **Зареждане на данните:**
   - CSV файлът се зарежда в `pandas DataFrame`.
   - Проверяват се липсващи стойности и структурата на данните.

2. **Изчисляване на ключови показатели:**
   - Средна цена на продуктите.
   - Общата стойност на продажбите (изчислява се като `Sales × Price`).
   - Средни продажби по региони и по продукти.
   - Определяне на топ-продукта и топ-региона с най-високи продажби.

3. **Визуализация:**
   - **Стълбчеста диаграма**: Общите продажби по региони.
   - **Линейна графика**: Тенденции в продажбите през времето.
   - **Кръгова диаграма**: Процентен дял на продажбите по продукти.
   - **Scatter Plot**: Връзката между цената на продуктите и техните продажби.
   - **Box Plot**: Разпределението на цените по категории продукти.

4. **Изводи:**
   - Анализира се как цената влияе на обема на продажбите.
   - Оценяват се най-продаваните продукти и региони.
   - Предлагат се препоръки за подобряване на продажбите.

---

### **Инструкции за използване**

#### **1. Изисквания**
- Python 3.7+.
- Инсталирани библиотеки:
  - `pandas`
  - `matplotlib`

#### **2. Стартиране на програмата**
1. Уверете се, че файлът `realistic_sales_data.csv` се намира в същата директория като програмата.
2. Стартирайте Python скрипта, като изпълните:
   ```bash
   python sales_analysis.py
   ```

#### **3. Резултати**
- Скриптът ще изведе ключови статистически показатели в терминала.
- Ще бъдат генерирани графики за визуализация.
- Анализът ще бъде обобщен в доклад, който може да бъде разширен с изводи.

---

### **Примерни резултати**
- **Средна цена:** $1538.17
- **Обща стойност на продажбите:** $838,674,959.65
- **Топ-продукт:** Laptop
- **Топ-регион:** Australia

---

Тази задача е разработена като обучителен проект за анализ на данни и визуализация с Python.
