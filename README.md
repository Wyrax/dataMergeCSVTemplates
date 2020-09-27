# dataMergeCSVTemplates
InDesign Data Merge CSV Templates with UTF-16LE encoding.

Working template for bussiness cards and posters made in Adobe InDesign.

**UTF-16LE** encoding is the same as Windows Notepad **"Unicode"** encoding.

This is important for proper displaying of **cyrillic** properties while Data Merging table data from CSV/TXT files.

## Best way to export proper file with cyrillic symbols for data merge
A) From Google Spreadsheets:
1. Copy selected range of cells to new table
2. Export as .CSV
3. Resave with UTF-16 LE (via VSC or Notepad, etc.)

B) From Excel:
1. Copy selected range of cells
2. Insert them into .TXT file (they will be TAB separated values)
3. Save with UTF-16 LE (via VSC or Notepad, etc.)

It'll became ready for cyrillic data merging in InDesign.
