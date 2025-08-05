https://github.com/SameerNamdeo12/workforce_management_api
https://drive.google.com/file/d/1qsY4UvJcHj9lOrPU71RfGZpd4bLuX9F4/view?usp=sharing
## Bug Fixes

### Bug 1: Task Reassignment Duplicate
Fixed by cancelling previous tasks before creating new.

### Bug 2: Cancelled Tasks in Fetch
Fixed by filtering out `CANCELLED` tasks in fetch API.

---

## New Features

### 1. Smart Daily Task View
Returns active tasks in range and old active ones before the range.

### 2. Task Priority
Added `LOW`, `MEDIUM`, `HIGH` + update and fetch endpoints.

### 3. Task Comments & Activity History
Auto activity logging + comment support, shown in task details.

---

## Tech Stack
- Java 17
- Spring Boot 3.0.4
- Gradle
- Lombok
- MapStruct
- In-memory repository (no DB)