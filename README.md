# JSON Telemetry Format Unifier 🛠️

This project is part of the Deloitte Technology Job Simulation on Forage.

## 📌 Objective
To unify two different telemetry data formats into a single standardized JSON structure for a real-time machine status dashboard.

## 🚀 Features
- Parses two input formats: flat and nested
- Detects the format automatically
- Converts ISO timestamps to milliseconds
- Produces consistent output structure
- Built-in unit tests using Python’s `unittest`

## 📂 Files
- `main.py` – Python script containing transformation functions
- `data-1.json` – Input Format 1
- `data-2.json` – Input Format 2
- `data-result.json` – Expected Output Format

## 🧪 Run the Test
```bash
python main.py
