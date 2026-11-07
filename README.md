# Employee Management System

A single-file Python program for managing simple employee records in memory, built as a 2023 coursework team project.

## What it does

The program presents a text menu and works with employee records that each hold a name, employee ID (code), designation, years of experience, and age. It supports:

- **Build Table (1)** — create the table by entering a batch of employee records (maximum 20 entries)
- **Insert New Entry (2)** — add one more employee record, if the table is not full
- **Delete Entry (3)** — delete a record by employee ID
- **Search a Record (4)** — look up and display a record by employee ID
- **Exit (5)** — quit the program

Records are held in memory only for the duration of the run; nothing is saved to disk.

## How to run

The program source is in the file named `source code` (it has no `.py` extension).

You can run it directly with Python 3 by passing that path:

```bash
python3 "source code"
```

Or copy it to a `.py` file first and run that copy instead:

```bash
cp "source code" employee_management.py
python3 employee_management.py
```

When it starts, the program shows the menu described above; type the number of an option and press Enter.

## Project context

- 2023 coursework team project
- Single-file Python program; no external dependencies
- Team, as credited in the header of the source file: Tanmoy Kalita, Prabhash Nandan, and Kundan Kumar

## License

No license is included. This is multi-author coursework, so no single license has been applied here.
