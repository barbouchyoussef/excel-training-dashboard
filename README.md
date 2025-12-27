# 📊 Training Management & Monitoring System – Excel Dashboard

### Demo 
Check the `assets/demo/` folder for:
- **[▶️ demo.webm](assets/demo/demo.webm)** - Full system demonstration video
- Example datasets
- Usage tutorials
- Template files for quick start


## 📋 Project Overview
A comprehensive Excel-based training management system designed to track employee training activities, providers, durations, completion status, and performance ratings. This tool helps HR departments efficiently plan, monitor, and evaluate training programs across the organization.

---

## 🎯 Key Features

### 🔄 Automated Employee Data Lookup
- **VLOOKUP integration** automatically pulls employee details (Name, First Name, Department) from the employee directory
- Real-time data synchronization ensures consistency across all records

### 📋 Centralized Training Database
- Track all training sessions with details including:
  - Training topic (20+ different courses)
  - Service provider (8 different providers)
  - Duration in hours
  - Completion date
  - Performance rating (1-5 scale)
  - Status (Planned/Completed)

### 📊 Interactive Dashboard
- **Department-wise training hours** - Visual breakdown by department
- **Top trainees ranking** - Identify most trained employees
- **Provider performance analysis** - Average ratings by training provider

### 🗂️ Data Validation & Integrity
- Dropdown lists for standardized data entry
- Predefined lists for training topics and providers
- Consistent formatting across all sheets

---

## 📁 File Structure
 assets/
├── screenshots/
│ ├── Employee_List.png # Full employee directory
│ ├── Training_Tracker_Detailed.png # Main training database with VLOOKUP
│ ├── Training_Dashboard_By_Year.png # Annual training summary
│ ├── Pivot_Tables_Summary.png # Department/provider analysis
│ └── Status_Codes_Legend.png # Status and code definitions
├── demo/ # Demo video
└── excel_filetraining management and monitoring.xlsx/ # Excel workbook version



**Excel Workbook Sheets:**
| Sheet Name | Description |
|------------|-------------|
| **`bdd`** | Main training database with all records |
| **`listes`** | Reference tables for dropdown lists |
| **`RH`** | Employee directory with personal details |
| **`tableau de bord`** | Interactive dashboard with summaries |

---

## 📸 Screenshots

### 1. **Main Training Database (bdd sheet)**
![Training Tracker](assets/screenshots/Training_Tracker_Detailed.png)
*Main training database with VLOOKUP formulas for employee data retrieval*

### 2. **Employee Directory (RH sheet)**
![Employee List](assets/screenshots/Employee_List.png)
*Complete employee directory used for data lookup in the training database*

### 3. **Annual Training Dashboard**
![Annual Dashboard](assets/screenshots/Training_Dashboard_By_Year.png)
*Year-over-year training analysis and tracking (2017-2020)*

### 4. **Pivot Table Summaries**
![Pivot Tables](assets/screenshots/Pivot_Tables_Summary.png)
*Department-wise training hours and provider performance analysis*

### 5. **Training Status Legend**
![Status Codes](assets/screenshots/Status_Codes_Legend.png)
*Training status definitions and codes used throughout the system*

---

## 📈 Key Insights & Analytics

### Department Training Hours (Top 3)
| Department | Total Hours | Percentage |
|------------|-------------|------------|
| Commercial | 1,624 hours | 31.1% |
| Fabrication | 1,099 hours | 21.0% |
| Technique | 647.5 hours | 12.4% |

### Provider Performance Rankings
1. **Yellow** - 4.16/5 ⭐⭐⭐⭐⭐
2. **Grey** - 3.98/5 ⭐⭐⭐⭐
3. **Black** - 3.16/5 ⭐⭐⭐

### Most Trained Employees
- **019-BM** - 140 training hours
- **084-DP** - 136.5 training hours  
- **023-BJ** - 129.5 training hours

---

## 🚀 How to Use This System

### Adding New Training Records
1. Go to the `bdd` sheet
2. Insert a new row at the bottom
3. Enter the employee ID (`Matricule`)
4. Select training details from dropdown menus
5. Save the record

### Updating Employee Information
1. Navigate to the `RH` sheet
2. Add/update employee details
3. Changes automatically reflect in the training database

### Viewing Reports
1. Check the `tableau de bord` sheet for:
   - Department summaries
   - Employee rankings
   - Provider performance


---

## 🛠️ Technical Implementation

### Formulas Used
- **VLOOKUP**: `=RECHERCHEV([@Matricule];Tableau5;2;0)` - Employee data retrieval
- **SUMIFS**: Department-wise calculations
- **AVERAGE**: Provider performance ratings
- **Structured References**: Table-based formulas

### Data Validation
- Dropdown lists from `listes` sheet
- Date format validation
- Numeric range validation for ratings (1-5)

### Dashboard Features
- PivotTables for dynamic analysis
- Automatic calculations
- Color-coded sections for better readability
- Interactive filtering by year, department, and status

---

## 🔄 Maintenance & Updates

### Regular Updates Required
1. Add new training records after each session
2. Update employee directory when hiring/terminating
3. Review and add new training topics as needed

### Quality Checks
- Verify VLOOKUP formulas after adding new employees
- Check data validation ranges periodically
- Validate dashboard calculations quarterly

### Backup Recommendations
1. Save weekly backups in `assets/excel_files/` with date stamps
2. Maintain version history of major changes
3. Archive completed training years separately

---


