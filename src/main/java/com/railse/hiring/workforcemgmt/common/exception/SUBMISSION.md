https://github.com/SameerNamdeo12/workforce_management_api
https://drive.google.com/file/d/1qsY4UvJcHj9lOrPU71RfGZpd4bLuX9F4/view?usp=sharing
## 🔧 Bug Fixes

### Bug 1: Task Reassignment Duplicate
- **Before:** Old task was not cancelled → duplicates
- **After:** Old task is cancelled when reassigned

### Bug 2: Cancelled Tasks Visible in Fetch
- **Before:** All tasks shown in `/fetch-by-date`, even cancelled
- **After:** Cancelled tasks are filtered out

---

## ✨ New Features

### Feature 1: Smart Daily Task View
- Shows tasks in range and old but still active

### Feature 2: Task Priority
- Added `LOW`, `MEDIUM`, `HIGH` field
- Added endpoints to update and fetch by priority

### Feature 3: Comments & Activity History
- Logged actions like creation, status/priority change
- User can add comments
- API returns all history with task details

---

## 🛠️ Tech Stack
- Java 17, Spring Boot 3.0.4, Gradle, Lombok, MapStruct
- In-memory repository (no DB required)