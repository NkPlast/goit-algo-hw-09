
### Порівняння ефективності алгоритмів

**Жадібний алгоритм:**

- **Часова складність:** O(n), де n — кількість типів монет.
- **Просторова складність:** O(1), оскільки зберігається лише словник результатів.
- **Ефективність:** Швидкий і простий, працює добре при стандартних номіналах монет і коли жадібний вибір оптимальний. Однак, не завжди забезпечує мінімальну кількість монет для нестандартних номіналів.

**Алгоритм динамічного програмування:**

- **Часова складність:** O(n * amount), де n — кількість типів монет, а amount — цільова сума.
- **Просторова складність:** O(amount), через використання масивів dp та coin_used.
- **Ефективність:** Більш обчислювально інтенсивний, але гарантує мінімальну кількість монет для будь-якого набору номіналів. Підходить для випадків з нестандартними номіналами або коли критично важливо отримати оптимальне рішення.


### Висновок

Для великих сум і стандартних наборів монет жадібний алгоритм зазвичай достатній і працює швидше. Однак, для довільних наборів номіналів монет підхід динамічного програмування є більш надійним, забезпечуючи мінімальну кількість монет, хоча і за більш високої обчислювальної вартості.
