# 🚀 Risk Management and Risk Register
### 📌 Risk ID: 101

**Risk Statement:**  
_"Geographic coordinate data format of city of Melbourne in dataset is not compatible with plugin of WordPress → The visualization of the map fails → The development progress of core functions in sprint 1 delays."_

- **Probability:** 60.0%
- **Impact:** 9
- **Exposure:** 60.0% × 9 = **5.4**
- **Mitigation Strategy:** **Mitigate**
- **Mitigation Plan:**
    - Validate the compatibility of data format at the beginning of Sprint 1.
    - Use Python to preprocess the incompatible data.
    - Test with a subset of data before full implementation.  

### 📌 Risk ID: 102

**Risk Statement:**  
_"Massive tree data import causes WordPress performance decrease→ Map loads slowly or crashes → Affect users' experience heavily."_

- **Probability:** 50.0%
- **Impact:** 7
- **Exposure:** 50.0% × 7 = **3.5**
- **Mitigation Strategy:** **Mitigate**
- **Mitigation Plan:**
  - Import tree data in batches(Use paging loading technique).
  - Use Redis to cache tree data in order to speed up the query process.

### 📌 Risk ID: 103

**Risk Statement:**  
_"Development team members are unfamiliar with WordPress → Technical debt accumulates → Spend more time on optimizing previous functions and delivery time delays."_

- **Probability:** 60.0%
- **Impact:** 5
- **Exposure:** 60.0% × 5 = **3.0**
- **Mitigation Strategy:** **Mitigate**
- **Mitigation Plan:**
  - Organise WordPress development training within the group.
  - Use standups and sprint retrospective to monitor and control flawed functions.

### 📌 Risk ID: 104

**Risk Statement:**  
_"City of Melbourne dataset update causes existing map integration failure  → Need to rework → Development time increases."_

- **Probability:** 20.0%
- **Impact:** 5
- **Exposure:** 20.0% × 5 = **1.0**
- **Mitigation Strategy:** **Avoid**
- **Mitigation Plan:**
  - Use static dataset(CSV/JSON file) instead of dynamic one(API) for development.
  - Monitor dataset updates and plan migration processes.


### 📌 Risk ID: 105

**Risk Statement:**  
_"User input invalid characters when searching  → Server returns error or crashes → User experience declines Temporarily."_

- **Probability:** 20.0%
- **Impact:** 3
- **Exposure:** 20.0% × 5 = **0.6**
- **Mitigation Strategy:** **Accept**
- **Contingency Plan:**
  - Record error logs and monitor high-frequency abnormal inputs.
  - Optimize processing logic in subsequent sprints.

---

## 📌 **Ongoing Risk Tracking**

| **Risk ID** | **Risk Statement (Summary)**                                    | **Probability (%)** | **Impact (0-10)** | **Exposure** | **Mitigation Strategy** |
|-------------|-----------------------------------------------------------------|---------------------|-------------------|--------------|---------------------|
| 101         | Incompatible data format affects the visulization of the map    | 60.0%               | 9                 | 5.4          | Mitigate 🟡         |
| 102         | Massive tree data import causes map loading slowly              | 50.0%               | 7                 | 3.5          | Mitigate 🟡            |
| 103         | Unfamiliarity with WordPress causes technical debt accumulation | 60.0%               | 5                 | 3.0          | Mitigate 🟡            |
| 104         | Dataset update causes reworking                                 | 20.0%               | 5                 | 1.0          | Avoid 🔴            |
| 105         | Invalid inputs result in error or crash                         | 20.0%               | 3                 | 0.6          | Accept 🟢             |

