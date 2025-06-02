# 🧹 Task 1: Data Cleaning and Preprocessing – Netflix Titles Dataset

## 🔍 Objective:
Clean and preprocess the Netflix dataset to remove missing values, eliminate duplicates, and ensure consistent formatting and data types for future analysis.

---

## ✅ Cleaning Steps Performed:

1. **Removed Missing Values:**
   - Used **Find and Replace → Go To Special → Blanks** to locate empty cells.
   - Found blank values primarily in the `director`, `cast`, and `country` columns.
   - Deleted entire rows containing blank cells in these critical fields.

2. **Removed Duplicates:**
   - Used **Data → Remove Duplicates** feature in Excel.
   - Unchecked `show_id` to avoid removing entries with different IDs but identical information.
   - Confirmed all remaining records are unique based on content.

3. **Standardized Date Format:**
   - Reformatted the `date_added` column to a consistent **`dd-mm-yyyy`** format using Excel's date formatting tools.

4. **Renamed Column Headers:**
   - Changed all column names to lowercase.
   - Replaced spaces with underscores for consistency (e.g., `Date Added` → `date_added`, `Release Year` → `release_year`).

---

## 📁 Deliverables:
- `cleaned_data.csv`: Final cleaned dataset ready for analysis.
- This `README.md` file summarizing all changes made.

---

## 🛠 Tools Used:
- **Microsoft Excel** (for filtering, date formatting, and data cleanup)

---

## 📌 Notes:
- All unnecessary or incomplete records were removed for cleaner analysis.
- Data now meets standard quality checks: no nulls, no duplicates, clean formats, and uniform structure.
