Experiment – 10

Title: Creation, Storage, and Loading of Datasets using Pandas

Name: Pushpak Jagtap

PRN: 25070123148

Batch: 2025–2029

Aim
To study the process of manual dataset creation in Python and understand the methodologies for loading, exporting, and performing initial structural analysis on external data files.


Objectives
- Construct a DataFrame from raw Python dictionaries
- Explore file export formats including CSV and Excel
- Load external datasets from local and cloud directories
- Perform basic structural inspection using shape, size, and metadata attributes
- Implement data selection and filtering techniques (loc, iloc, and column-based access)
- Apply descriptive statistical functions and schema modification method
Theory
1. Manual Dataset Construction
Datasets can be created in Python using dictionaries, where keys represent column headers and values (lists) represent rows. Passing these structures into a Pandas DataFrame constructor generates a tabular representation suitable for relational operations. This is useful for dummy data or small-scale look-up tables.
2. Data Persistence (Exporting)
Once created or modified, datasets must be saved to permanent storage for reuse:
- CSV (Comma Separated Values): Lightweight, plain-text format widely supported.
- Excel (.xlsx): Binary format supporting multiple sheets and complex formatting, common in business environments.
3. Structural Inspection
Before analysis, understanding dataset structure is essential. Pandas provides:
- Shape: Tuple of (Rows, Columns).
- Size: Total number of elements (Rows × Columns).
- Info(): Displays schema, column names, non-null counts, and memory usage.
- Dtypes: Data types assigned to each column (int64, float64, object).
4. Data Retrieval and Modification
- Label-based Selection: Using column names or .loc for index labels.
- Position-based Selection: Using .iloc for integer-based indexing.
- Slicing: head() previews initial records, tail() checks trailing rows.
- Schema Modification: Add/drop columns, apply aggregate functions (min(), max()).




-Applications in Engineering
- Sensor Data Logging: Collecting and structuring real-time signals into timestamped datasets.
- Network Analysis: Loading server logs to analyze traffic patterns.
- Market Analysis: Comparing hardware prices/specifications for procurement optimization.

Conclusion
The ability to create, save, and reload datasets forms the foundation of data-driven projects. Pandas provides efficient I/O
operations and structural attributes that enable smooth transitions from raw data collection to analytical processing. Inspecting dataset shape and schema ensures clean, reliable data for further analysis.
