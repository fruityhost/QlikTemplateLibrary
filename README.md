# Qlik Sense Templates Repository

This repository provides reusable script sections that can help Qlik users efficiently build and manage their Qlik apps. Each script section in this repository is designed to handle common tasks such as calendar generation, variable management, security implementation, and data lookups.

These sections can be **imported directly into your Qlik Sense app** using the **Gitoqlok extension**. Simply connect Gitoqlok to Git, go to the **Import tab in Gitoqlok**, select the section you need, and add it to your Qlik app seamlessly.  

---

## **Available Script Sections**

### 1. **autoCalendar**
   This section generates a default calendar for your dataset based on date fields detected in the data model. It’s ideal for automating time-based reporting with minimal setup.

   **Features**:
   - Auto-detects date fields from the data.
   - Generates year, month, week, and day fields automatically.

---

### 2. **Calendar**
   A manually customizable calendar script for your Qlik Sense app. This allows you to define how dates are parsed and structured based on your organization’s needs.

   **Features**:
   - Custom year, month, and quarter breakdowns.
   - Support for fiscal years or non-standard calendar structures.

---

### 3. **Calendar Set Variables (Calendar.qvs)**
   This section contains pre-defined variables that control calendar behavior. It helps you manage multiple calendars efficiently by setting variables like start date, end date, and current fiscal period.

   **Features**:
   - Control over date ranges.
   - Pre-set variables to manage fiscal periods and relative date calculations.

---

### 4. **Calendar Configuration**
   Configuration options for fine-tuning the calendar script, including formatting, week start settings, and day naming conventions. This section helps ensure consistency across different calendar implementations.

   **Features**:
   - Adjust date formats and day names.
   - Control start days for weeks and fiscal periods.

---

### 5. **Section Access**
   Implements **row-level security** by restricting access to specific data based on user roles. This script ensures only authorized users can view specific portions of the data.

   **Features**:
   - Control access by users or groups (e.g., ADMIN, USER).
   - Link users with data reductions to filter the visible dataset.
   - Optional field-level hiding using the `OMIT` function.

---

### 6. **Mapping Table for Lookup Values**
   A **mapping table** helps with value transformations or lookups. This script provides a way to map input values (e.g., abbreviations, codes) to human-readable formats (e.g., "NY" to "New York").

   **Features**:
   - Simplifies data transformation using `ApplyMap()`.
   - Handles cases where input data contains inconsistent formats or codes.

---

## **How to Use with Gitoqlok**
1. Install the **Gitoqlok extension** from the Chrome Store (if not already installed).
2. Configure Git in Gitoqlok Options
3. Open your Qlik Sense app.
4. Navigate to the **Gitoqlok Import tab**.
5. Select the script section(s) you need from this repository.
6. Click **Import** to add the section to your Qlik Sense script editor.

---

Feel free to explore, modify, and enhance these templates to fit your Qlik app needs. Happy Qlik-ing! 



