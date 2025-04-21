## 📌 TASK 1: DATA CLEANING AND PREPROCESSING

### ✅ CLEANED DATA STEPS:

**STEP 1:** Removed duplicate values using `Data → Remove Duplicates`.  
> 🔹 *Result: No duplicates were found.*

**STEP 2:** Identified null and inconsistent values using filters.  
> 🔹 *Observation: The `Age` column contained a value of `-1`, which is invalid since age cannot be negative.*

**STEP 3:** Deleted the record with `Age = -1`.

**STEP 4:** Renamed column headers to make them clean and uniform (e.g., lowercase, no spaces, descriptive).

**STEP 5:** Split datetime columns into separate `Date` and `Time` parts for clarity:
- From `Scheduled_Day`, created `Scheduled_Date` and `Scheduled_Time`.
- From `Appointment_Day`, created `Appointment_Date` and `Appointment_Time`.

**STEP 6:** Removed the `Appointment_Time` column as all values were `00:00:00` (non-informative).

**STEP 7:** Converted values in binary categorical columns:

**STEP 8:** Updated data types where necessary
