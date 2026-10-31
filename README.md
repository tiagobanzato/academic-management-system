# Academic Management System in Python

Academic project built in Python for the **Computational Reasoning** course of the Systems Analysis and Development degree.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![JSON](https://img.shields.io/badge/Persistence-JSON-orange?style=flat)
![Status](https://img.shields.io/badge/Status-Completed-green?style=flat)

---

## About the project

A terminal-based Academic Management System (SGA) that manages **5 complete modules** with data persisted in JSON files. Data is loaded automatically on startup and saved after every operation.

---

## Modules

| Module | Available operations |
|--------|----------------------|
| Students | Create, List, Update, Delete |
| Subjects | Create, List, Update, Delete |
| Teachers | Create, List, Update, Delete |
| Classes | Create, List, Update, Delete |
| Enrolments | Create, List, Delete |

---

## Technical features

- **Full CRUD** in 4 of the 5 modules
- **JSON persistence**: data saved automatically after every operation
- **Automatic loading** on startup
- **Input validation** with `try/except` for invalid codes
- **Duplicate checks** before creating new records
- **Nested menu navigation** using `while` loops
- **Modular design**: each module has its own separate functions

---

## Project structure

```
sistema-gestao/
├── main.py            # Main code with all menus and functions
├── estudantes.json    # Students data
├── disciplinas.json   # Subjects data
├── professores.json   # Teachers data
├── turmas.json        # Classes data
└── matriculas.json    # Enrolments data
```

---

## Running locally

```bash
python main.py
```

Navigate the menu by typing the number of each option. The interface is in Portuguese.

---

## Tech stack

- **Python**: main language
- **JSON**: data persistence (`json.dump` / `json.load`)
- **File handling**: reading and writing with `open()`
- **Exception handling**: `try/except` for invalid input

---

## Author

**Tiago Banzato**  
Software developer · Dublin, Ireland

[![GitHub](https://img.shields.io/badge/GitHub-tiagobanzato-black?logo=github)](https://github.com/tiagobanzato)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-banzato-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/banzato)
