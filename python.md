# 1 задание

<img width="831" height="606" alt="image" src="https://github.com/user-attachments/assets/f6da3802-a408-4d9b-b5ab-b566463346e5" />


Шаблон:
```python
import json

data_string = input().strip()

# ВАШ КОД ЗДЕСЬ
```

---

# 2 задание

<img width="857" height="626" alt="image" src="https://github.com/user-attachments/assets/1cad1bef-84e9-4de4-9ba7-657eb37b8c95" />


Шаблон:
```python
def predict_users(current_users, months):
    # ВАШ КОД ЗДЕСЬ

users = int(input())
m = int(input())
print(predict_users(users, m))
```

---

# 3 задание

<img width="834" height="754" alt="image" src="https://github.com/user-attachments/assets/2d8cff77-2b59-4f5d-9c09-6ccd2532ff9f" />


Шаблон:
```python
sales_dict = {}
while True:
    line = input().strip()
    if line == "END":
        break
   
    # ВАШ КОД ЗДЕСЬ
   
for key in sorted(sales_dict.keys()):
    print(f"Магазин: {key[0]}, Регион: {key[1]} - Выручка: {sales_dict[key]}")
```

---

# 4 задание

<img width="820" height="951" alt="image" src="https://github.com/user-attachments/assets/da633491-80c6-46a3-9278-22463d7bdf7f" />


Шаблон:
```python
class Employee:
    def __init__(self, name, salary):
        self.name = name
        self.salary = salary

    def get_payout(self):
        return self.salary

class Manager(Employee):
    # ВАШ КОД ЗДЕСЬ

name = input().strip()
salary = float(input())
bonus = float(input())

m = Manager(name, salary, bonus)
print(f"К выплате менеджеру {m.name}: {m.get_payout()}")
```

---

# 5 задание

<img width="888" height="714" alt="image" src="https://github.com/user-attachments/assets/bdfaddab-c54b-4ff6-903e-0d274acd57be" />


Шаблон:
```python
class Report:
    def __init__(self, title, pages):
        self.title = title
        self.pages = pages

    # ВАШ КОД ЗДЕСЬ

t = input().strip()
p = int(input())
doc = Report(t, p)

print("STR:", str(doc))
print("REPR:", repr(doc))
```

---

# 6 задание

<img width="817" height="740" alt="image" src="https://github.com/user-attachments/assets/d98df971-2289-4b6f-b903-2b35f58795e8" />


Шаблон:
```python
campaigns = [
    ("Promo_A", 1000, 1.5),
    ("Promo_B", 500, 2.0),
    ("Promo_C", 1500, 1.5),
    ("Promo_D", 800, 2.0)
]

# ВАШ КОД ЗДЕСЬ

for c in campaigns:
    print(c[0])
```

---

# 7 задание

<img width="820" height="656" alt="image" src="https://github.com/user-attachments/assets/02b35214-8ec8-4a87-903e-20f1caf4a2c0" />


Шаблон:
```python
def calculate_final_price(base_price, *args, **kwargs):
    # ВАШ КОД ЗДЕСЬ
    
price = float(input()) 
percents_input = input().strip()
percents = [float(x) for x in percents_input.split(',')] if percents_input else [] 
print(f"Итог: {calculate_final_price(price, *percents, promo=500, cashback=200):.2f}")
```

---

# 8 задание

<img width="829" height="603" alt="image" src="https://github.com/user-attachments/assets/8abed70e-dd11-403f-b407-a23d6ef16c23" />


Шаблон:
```python
blacklist_input = input().strip().split(',')
transactions_input = input().strip().split(',')

# ВАШ КОД ЗДЕСЬ

print(f"Заблокировано транзакций: {blocked_count}")
```

---

# 9 задание

<img width="867" height="631" alt="image" src="https://github.com/user-attachments/assets/47543bc0-f4d7-4c09-98bc-be695533bf44" />


Шаблон:
```python
def predict_users(current_users, months):
    # ВАШ КОД ЗДЕСЬ

users = int(input())
m = int(input())

# ВАШ КОД ЗДЕСЬ
```
