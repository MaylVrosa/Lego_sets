# 🚀 LEGO Star Wars: Licensed Set Analysis

This project analyzes the impact of the **Star Wars** partnership on LEGO's licensed sets over time.

It answers two key business questions for the LEGO partnerships team:

1. **What percentage of all licensed sets ever released were Star Wars themed?**
2. **In which year was the highest number of Star Wars sets released?**

---

## 📁 Dataset Information

This analysis uses two CSV files:

- `lego_sets.csv`: Metadata about LEGO sets, including name, year, number of parts, and parent theme.
- `parent_themes.csv`: Lists parent theme names and whether they are licensed.

| Column Name        | Description                                            |
|--------------------|--------------------------------------------------------|
| `set_num`          | Unique ID for each LEGO set                           |
| `name`             | Name of the set                                        |
| `year`             | Year the set was released                              |
| `num_parts`        | Number of parts in the set                             |
| `theme_name`       | Sub-theme of the set                                   |
| `parent_theme`     | Main theme the set belongs to                          |
| `is_licensed`      | Boolean (from `parent_themes.csv`): Is this theme licensed? |

---

## 📊 Key Results

| Variable    | Description                                                        |
|-------------|--------------------------------------------------------------------|
| `the_force` | Percentage of licensed LEGO sets that are **Star Wars** themed     |
| `new_era`   | Year with the most **Star Wars** sets released                     |

Example output:
```python
the_force = 51
new_era = 2014
