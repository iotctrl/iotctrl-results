# IoTControl Results
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18806714.svg)](https://doi.org/10.5281/zenodo.18806714)

A **community-driven collection** of results from the **IoTControl** project.

This repository aggregates experimental data from control experiments run through *IoTControl*. The goal is to centralize and share results so researchers, engineers, and contributors can analyze, reproduce, or build upon them.

---

## 📂 Structure
/csv
└── … (CSV files with results data)

- **csv/**: Contains CSV-formatted result files exported from IoTControl experiments.  
- **LICENSE**: Licensed under the MIT License.

---

## 📊 Purpose & Use Cases

- **Data Sharing**: Share experimental outcome data from control-system runs.  
- **Reproducibility**: Make it easier for others to reproduce your control experiments by providing raw outputs.  
- **Analysis & Visualization**: Use CSV files here for offline data analysis, plotting, or building dashboards.  
- **Benchmarking**: Compare control strategies (PID, advanced control, etc.) using a common set of results.  

---

## 📈 How to Contribute

Contributions are *very welcome*. Here's how you can help:

1. Run an experiment in the **IoTControl** platform.  
2. Export the results as CSV.  
3. Create a pull request (PR) in this repo:  
   - Place your CSVs in a meaningful subfolder (e.g., `csv/experiment-xyz/`)  
   - Include a metadata file (optional but helpful) with context: What was the experiment? Control algorithm? Sampling rate? Hardware?  
   - Add a README or a description in your PR so others know what the results represent.  

---

## 🧪 Best Practices for Results

- Use a **consistent CSV schema**: define column names, units, and data types so that analysis is straightforward.
- Archive raw logs if possible (not just processed CSV).
- Provide **experiment metadata**: control parameters, architecture, timestamp, hardware, etc.
- Consider **versioning**: large experiments may generate many files over time — use subfolders to organize them.

---

## ⚖️ License

This project is licensed under the **MIT License** (see the [LICENSE](LICENSE) file).

---

## 💡 Vision

Over time, we want this repository to become a **public benchmark suite** for IoT + control experiments across different setups. By growing a shared library of results, we help:

- Academic researchers validating new control algorithms  
- Engineers testing performance in real-world or simulated systems  
- The IoTCtrl community to compare, learn, and improve

---

If you have ideas for improving the structure, including other file formats (e.g. JSON or Parquet), or improving metadata, please open an issue or a PR — we'd love your feedback!
