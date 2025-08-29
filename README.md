# 🧠 NC TaskSuite – Focused Task Manager for Developers & Pros

**Version:** `1.0.6`  
**Platform:** Windows (.NET WinForms)  
**Developer:** Noriel Calingasan  
**Release Date:** August 29, 2025

**Highlights in v1.0.6**
- **Undo/Redo support** for task add/remove actions (`Ctrl+Z` / `Ctrl+Y`)  
- Reuse of task panels on undo/redo to prevent duplication  
- Improved task handling and panel updates across tabs  
- Smooth drag-and-drop with priority task protection  
- Multi-panel selection and context menu optimizations  

---

## 📂 Repository  
Explore source code, report issues, or contribute:  
🔗 [https://github.com/norielcalingasan/NCTaskSuite](https://github.com/norielcalingasan/NCTaskSuite)

---

## 🚀 Features

### UI & Visual
- Sleek task panels with smooth redraws and improved layout  
- Rounded corners and theme-adaptive backgrounds for a modern look  
- Helpful tooltips for icons, buttons, and fields  
- Clean, polished menus with fixed scrollbar alignment  

### Task Management
- Quick task entry with bulk paste support  
- Inline editing for task titles and notes  
- Priority toggling with pin-lock behavior  
- Drag-and-drop sorting with press-and-hold support  
- Subtask management: add, check off, remove subtasks easily  
- Visual progress tracking for subtask completion percentage  
- **Undo/Redo Support – Add or remove tasks using `Ctrl+Z` / `Ctrl+Y`**  
- Task panels reused on undo/redo to preserve state and prevent duplication  

### Alarms & Due Dates
- Dynamic alarm and due date icons that update instantly  
- Alarm sound notifications with snooze and stop functionality  
- Clear icon visibility in both light and dark themes  

### Metadata & Persistence
- Rich description editor with live character count  
- Save/load tasks using `.ntask`, `.xml`, or `.txt` file formats  
- Metadata support: timestamps, GitHub links, categories, notes, and more  
- Autosave and backups to protect data  

### Productivity & Workflow
- Built-in update downloader for in-app fetching and installing updates  
- Single instance mode to prevent multiple app windows  
- Fully offline, portable (~3MB), no login required  
- Drag and drop reorder with smooth, accurate control  
- Multi-panel selection with Shift-click & ESC deselect  

### Recurring Tasks
- Supports daily recurring tasks with automatic daily reset  
- Tasks marked for daily reset clear completion status every new day  
- Future plans for more flexible recurrence patterns  

---

### Task Structure & Behavior

- Checkbox toggle for completion  
- Inline editable title  
- Priority star (★) indicator  
- Created and completed timestamps  
- Notes, category, GitHub branch and repository info  
- Alarm and due date settings  
- Drag to reorder, except pinned tasks  
- **Undo/Redo enabled for task add/remove actions**  

---

## 📦 Version Info

| Item          | Detail               |
|---------------|----------------------|
| Version       | 1.0.6                |
| Build Date    | August 29, 2025      |
| Framework     | .NET 8.0+ WinForms   |
| Architecture  | x86 / x64            |

---

## 🆚 NC TaskSuite vs Other Apps

| Feature               | **NC TaskSuite**       | Trello             | Microsoft To Do    | Notion             |
|-----------------------|-----------------------|--------------------|--------------------|--------------------|
| **Offline Mode**      | ✅ Full support        | ❌ No              | ⚠️ Partial          | ⚠️ Partial          |
| **No Account Needed** | ✅ Yes                 | ❌ No              | ❌ No              | ❌ No              |
| **Local File Ownership** | ✅ Yes              | ❌ No              | ❌ No              | ❌ No              |
| **Task Reordering**   | ✅ Drag & Pin Lock     | ⚠️ Limited         | ✅ Yes             | ✅ Yes             |
| **Undo/Redo**         | ✅ Ctrl+Z / Ctrl+Y     | ❌ No              | ❌ No              | ❌ No              |
| **App Size**          | ~3 MB (portable EXE)   | Lightweight (Web)  | ~50 MB+            | ~200 MB+ (Electron)|
| **Alarms & Reminders**| ✅ Full support        | ❌ No              | ✅ Basic           | ⚠️ Workaround       |
| **Theme Switching**   | ✅ Built-in toggle     | ⚠️ Limited         | ✅ OS-based        | ✅ Yes             |
| **Export Support**    | ✅ XML + TXT (planned) | ⚠️ Manual export   | ⚠️ Basic export    | ⚠️ Manual export   |
| **Subtasks & Notes**  | ✅ Inline editable     | ⚠️ Basic           | ✅ Checklist       | ✅ Advanced        |
| **Daily Reset Tasks** | ✅ Built-in            | ❌ No              | ❌ No              | ⚠️ Workaround       |
| **Recurring Tasks**   | ⚠️ Daily only          | ❌ No              | ✅ Yes             | ✅ Yes             |
| **Price**             | ✅ 100% Free           | ⚠️ Freemium        | ✅ Free            | ⚠️ Paid tiers      |

---

## 🖥️ Installation

1. 📥 Download latest `.zip` package  
2. 📂 Extract using 7-Zip or WinRAR  
3. ▶️ Run `NCTaskSuite.exe`  
4. 📌 Optional: Pin app to Start or Taskbar  

No installation required. Fully offline and portable.

---

## 🔒 License
NC TaskSuite is provided free for personal and educational use only.  
Users may use the software as-is but are not permitted to modify, redistribute, sell, or otherwise exploit it without explicit written permission from the developer.  
All rights reserved by Noriel Calingasan.

---

## 🔄 Save File Format (XML)

```xml
<Task>
  <Id>1</Id>
  <Text>Design database schema</Text>
  <Description></Description>
  <IsCompleted>true</IsCompleted>
  <Priority>true</Priority>
  <IsDaily>false</IsDaily>
  <IsArchived>false</IsArchived>
  <IsBillable>false</IsBillable>
  <IncludeInReport>false</IncludeInReport>
  <CreatedAt>2025-07-06T15:00:00</CreatedAt>
  <CompletedAt>2025-07-06T16:10:00</CompletedAt>
  <UpdatedAt></UpdatedAt>
  <HasDueDate>false</HasDueDate>
  <DueDate></DueDate>
  <HasAlarm>true</HasAlarm>
  <AlarmTime>2025-07-18T09:00:00</AlarmTime>
  <AlarmTriggered>false</AlarmTriggered>
  <GitLink>https://github.com/yourrepo</GitLink>
  <CommitHash></CommitHash>
  <RelatedIssueId></RelatedIssueId>
  <BranchName>main</BranchName>
  <Owner>Noriel</Owner>
  <Category>Development</Category>
  <Notes>Final structure for v1.0.6</Notes>
  <Tags></Tags>
  <EstimatedTime></EstimatedTime>
  <TimeSpent></TimeSpent>
  <!-- Example subtasks -->
  <!-- <Subtask>Define entities::true</Subtask>
  <Subtask>Draw ERD::false</Subtask> -->
</Task>
