# 🐍 Python OOP: Operator Overloading (Less Than `<`)

## 🎯 AIM

To write a Python program that demonstrates **operator overloading** by overloading the **less than (`<`)** operator using a custom class.

---

## 🧠 ALGORITHM

1. **Create Class `A`**:
   - Define the `__init__()` method to initialize the object with a value `a`.

2. **Overload the `<` Operator**:
   - Define the `__lt__()` method with logic:
     - If `self.a < o.a`, return `"ob1 is less than ob2"`
     - Else, return `"ob2 is less than ob1"`

3. **Create Objects**:
   - Instantiate two objects `ob1` and `ob2` with values.

4. **Use `<` Operator**:
   - Use `print(ob1 < ob2)` to trigger the overloaded behavior.

---

## 💻 Program
```
class Marks(object):
    def __init__(self, x):
        self.x = x
    def __lt__(self, other):
        return self.x < other.x
obj1 = Marks(20)
obj2 = Marks(10)

print("ob2 is less than ob1" if obj2 < obj1 else "ob1 is less than ob2")
```
## Output
<img width="825" height="305" alt="image" src="https://github.com/user-attachments/assets/9f47597b-c7ca-44bb-89e9-f0f1b5274e55" />

## Result
Successfully wrote a Python program that demonstrates operator overloading by overloading the less than (<) operator using a custom class.

