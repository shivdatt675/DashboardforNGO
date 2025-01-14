# Volunteer Data Management Dashboard for NGO

![Screenshot 2025-01-14 165016](https://github.com/user-attachments/assets/0191adeb-02e9-4093-ac5b-c4cf7b0da65e)
![Screenshot 2025-01-14 165007](https://github.com/user-attachments/assets/57a75899-a61c-4bb0-8f4d-752711283e58)
![Screenshot 2025-01-14 164956](https://github.com/user-attachments/assets/5d7b5d9c-b8d7-4f99-80f6-16cc871a23da)
![Screenshot 2025-01-14 165025](https://github.com/user-attachments/assets/ac60f208-88f7-4e51-9184-ca9917e13df4)



## Project Overview

This project involves creating a **Live Excel Dashboard** to manage volunteer data for a Non-Governmental Organization (NGO). The dashboard provides a dynamic and user-friendly interface for tracking volunteer engagement, task assignments, hours contributed, and overall performance.

## Features

- **Real-Time Data Updates:** Automated data refresh to reflect the latest volunteer information.
- **Interactive Charts & Graphs:** Visual representation of volunteer statistics (e.g., participation rates, task completion).
- **Volunteer Database:** Centralized data entry for volunteer details (name, contact, role, availability).
- **Task Tracking:** Assignments and progress monitoring for each volunteer.
- **Filter & Search Functions:** Easy access to specific data using dropdowns, slicers, and search bars.
- **Performance Metrics:** KPI tracking such as hours contributed, tasks completed, and volunteer retention rates.

## Tools & Technologies Used

- **Microsoft Excel** (with Power Query and Power Pivot)
- **Pivot Tables & Pivot Charts**
- **Data Validation** for controlled data entry
- **Conditional Formatting** for visual alerts
- **Excel Macros (VBA)** *(optional for automation)*

## Project Structure

```bash
├── DataEntry.xlsx       # Raw data entry for volunteer information
├── Dashboard.xlsx       # Live dashboard with charts and metrics
├── Templates/          # Templates for data import/export
├── Reports/            # Automated reports generated from the dashboard
└── README.md           # Project documentation
```

## Installation & Setup

1. **Download the Files:** Clone the repository or download the ZIP file.
   ```bash
   git clone https://github.com/yourusername/ngo-volunteer-dashboard.git
   ```
2. **Enable Macros (if applicable):**
   - Open `Dashboard.xlsx`
   - Go to **File > Options > Trust Center > Trust Center Settings > Macro Settings**
   - Select **Enable all macros**
3. **Connect Data Sources:**
   - Open `DataEntry.xlsx` and input volunteer data.
   - Ensure the data range is linked to the dashboard via Power Query.
4. **Refresh Data:**
   - In `Dashboard.xlsx`, click **Data > Refresh All** to update the visuals.

## Usage

1. **Add New Volunteers:** Enter volunteer details in the `DataEntry.xlsx` file.
2. **Assign Tasks:** Use the task tracker to allocate responsibilities.
3. **Analyze Performance:** Review interactive charts for insights into volunteer engagement.
4. **Generate Reports:** Export reports from the dashboard for stakeholder review.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a new branch (`feature-branch`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Open a pull request

## License

This project is licensed under the MIT License.

## Contact

For queries or suggestions, contact:

- **Name:** Shivdatta Malkar

---

**Note:** This project is designed for NGOs to streamline volunteer management and improve operational efficiency.
