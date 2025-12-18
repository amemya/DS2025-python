# DS2025 Python

This repository contains the course materials for the **2025 Fundamentals of Data Science** course.

## Course Overview

This course provides a foundation in data science using Python. It covers essential tools and concepts, starting from the basics of Python programming and Jupyter Notebooks to data analysis and visualization.

## Content

The repository includes:
- **Lecture Notebooks**: Step-by-step guides and examples for each lecture (e.g., `DS_Lecture_0x.ipynb`).
  - Topics include Jupyter Notebook basics, Python fundamentals (variables, types, logic), and data science libraries.
- **Assignments**: Practice problems and assignments (e.g., `Assignment_*.ipynb`).
- **Data**: Datasets used for analysis are located in the `student/` directory (e.g., Student Performance Data Set).

## Requirements

- **Python**: >= 3.10
- **Package Manager**: [uv](https://github.com/astral-sh/uv)

### Dependencies
Major Python libraries used in this project:
- `pandas`
- `matplotlib`
- `ipykernel`

## Setup & Usage

This project uses `uv` for dependency management.

1.  **Clone the repository**:
    ```bash
    git clone <repository_url>
    cd DS2025-python
    ```

2.  **Install dependencies**:
    ```bash
    uv sync
    ```

3.  **Run Jupyter Notebook**:
    You can launch Jupyter Lab or Notebook within the virtual environment:
    ```bash
    uv run -- jupyter lab
    ```
    Or activate the virtual environment first:
    ```bash
    source .venv/bin/activate  # On macOS/Linux
    jupyter lab
    ```

## License

Please refer to the course guidelines for usage and distribution rights.
