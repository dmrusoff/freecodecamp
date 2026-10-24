# 🎓 freeCodeCamp Certification Projects

A consolidated monorepo of coursework, programming exercises, and certification projects completed across the [freeCodeCamp](https://www.freecodecamp.org) curriculum, covering Relational Databases, Shell Scripting, Algorithms, and Python.

---

## 📂 Project Directory

| Directory | Topic / Certification | Description | Stack |
|---|---|---|---|
| **[`bash-programs/`](./bash-programs/)** | Relational Database & Bash Scripting | Suite of interactive Bash scripts (`bingo.sh`, `countdown.sh`, `fortune.sh`, `five.sh`, `questionnair.sh`) exploring CLI I/O, control flow, loops, and terminal utilities. | `Bash` `Shell` |
| **[`celestial-bodies-database/`](./celestial-bodies-database/)** | Relational Database Certification | Full PostgreSQL database schema and dataset dump (`universe.sql`) modeling galaxies, stars, planets, and moons with relational foreign key integrity. | `PostgreSQL` `SQL` |
| **[`caesar-cipher/`](./caesar-cipher/)** | Scientific Computing with Python | Symmetric key encryption implementation that encrypts and decrypts text streams using customizable key offsets and character mapping. | `Python 3` |
| **[`expense-tracker/`](./expense-tracker/)** | Scientific Computing with Python | CLI personal finance ledger tracking daily expenses, categorized spending totals, and budget breakdowns using Python lambda functions. | `Python 3` |
| **[`luhn-algorithm/`](./luhn-algorithm/)** | Scientific Computing with Python | Implementation of the Luhn checksum formula (Mod 10) to validate credit card numbers and checksum digits. | `Python 3` |

---

## 🚀 Running the Projects

### Bash Programs
```bash
cd bash-programs
chmod +x *.sh
./bingo.sh
./countdown.sh 5
./fortune.sh
```

### Celestial Bodies Database (PostgreSQL)
```bash
# Import the universe schema and data
psql -U postgres < celestial-bodies-database/universe.sql
```

### Python Projects
```bash
# Caesar Cipher
python3 caesar-cipher/main.py

# Expense Tracker
python3 expense-tracker/main.py

# Luhn Algorithm Validator
python3 luhn-algorithm/luhn.py
```

---

<div align="center">
  <sub>Maintained by <a href="https://github.com/dmrusoff">David Rusoff</a></sub>
</div>
