# MKR 1
## Варіант 29
### Запуск застосунку
Виконати команду з даної папки:
```bash
dotnet run --project App
```
Вхідний файл `INPUT.TXT` знаходиться в даній папці

Вихідний файл `OUTPUT.TXT` записується в дану папці

### Запуск тестів
Виконати команду з даної папки:
```bash
dotnet test Tests
```
Для виведення проміжних результатів:
```bash
dotnet test --logger "console;verbosity=detailed" Tests
```