# NC TaskSuite

Version: 1.0.9 Beta
Platform: Windows (.NET WinForms)
Developer: Noriel Calingasan

## Overview
NC TaskSuite is a focused task manager for solo work, private local teams, and optional shared workflows.
It is built for fast task capture, clear progress tracking, and flexible local-first data ownership.

## Repository
Source code and issues:
https://github.com/norielcalingasan/NCTaskSuite

## Features

### Task Capture & Editing
- Fast task entry with multi-line quick add support
- Prefix "-" during quick add to attach subtasks to the latest task
- Inline editing for task titles and key metadata
- Priority / pinned task handling for protected ordering
- Status-aware task tracking with completion timestamps
- Subtask checklists with live percentage progress

### Task Details & Metadata
- Rich task details form with description, notes, owner, category, tags, and status
- Git metadata fields (repository link, branch name, commit hash, issue ID)
- Created, updated, completed, due date, and alarm time fields
- Daily task toggle for repeatable checklist-style workflows

### Alarms, Due Dates & Recurrence
- Task alarms with popup reminders, snooze, and stop actions
- Due date and alarm icons that refresh as task state changes
- Daily reset support so recurring daily tasks clear completion state

### Data Ownership & Recovery
- Save and load task files in .ntask, .xml, and .txt
- Import task data and merge it into the current list
- Merge conflict resolution UI for overlapping tasks
- Autosave, temporary session recovery, and backup retention controls
- Backup manager UI for browsing, restoring, and deleting backups

### Import, Export & Reporting
- Free: CSV import/export
- Pro Monthly and Business Monthly: Markdown/JSON import/export
- Business Monthly: report export with summaries and trends

### Profiles & Personalization
- Multiple task-list profiles with create, rename, delete, and switch actions
- Profile-specific task files so different workspaces stay separate
- Theme switching with custom colors, fonts, and layout preferences on paid plans
- Responsive layout options and density tuning on paid plans

### Accessibility & Usability
- High-contrast mode support
- Improved accessible names and descriptions for screen readers
- Helpful tooltips, hints, and polished menu interactions
- Responsive task layout behavior for card/list-style use

### Workflow & Desktop Integration
- Free mode startup with optional license activation later
- Background license checking without blocking launch
- System tray support with quick-add entry points
- Single-instance protection to prevent duplicate app windows
- Built-in updater with manifest-based per-file updates

### Built-In Help Screens
- In-app About screen with current version, plan, profile, and account status
- In-app Features and Plans & Pricing screens
- License dialog quick link to Plans & Pricing
- Account menu for Google sign-in, profile updates, account switching, and logout
- Shared Tasks menu for Cloud Workspace and Local Bridge Sharing

## Plans (Summary)
- Free: local task management and basic import/export
- Pro Monthly: premium settings and Local Bridge Sharing
- Business Monthly: premium features plus Cloud Workspace support

## Version Info

| Item          | Detail               |
|---------------|----------------------|
| Version       | 1.0.9                |
| Build Date    | March 22, 2026       |
| Framework     | .NET 9.0+ WinForms   |
| Architecture  | x86 / x64            |

## NC TaskSuite vs Other Apps

| Feature                  | NC TaskSuite        | Trello       | Microsoft To Do | Notion       |
|--------------------------|---------------------|--------------|-----------------|--------------|
| Offline mode             | Full support        | No           | Partial         | Partial      |
| No account needed        | Yes                 | No           | No              | No           |
| Local file ownership     | Yes                 | No           | No              | No           |
| Task reordering          | Drag + pin lock     | Limited      | Yes             | Yes          |
| Undo/redo                | Yes                 | No           | No              | No           |
| Alarms & reminders       | Full support        | No           | Basic           | Workaround   |
| Theme switching          | Built-in toggle     | Limited      | OS-based        | Yes          |
| Export support           | CSV on Free, more on paid plans | Manual | Basic | Manual |
| Subtasks & notes         | Inline editable     | Basic        | Checklist       | Advanced     |
| Daily reset tasks        | Built-in            | No           | No              | Workaround   |
| Recurring tasks          | Daily only          | No           | Yes             | Yes          |
| App size                 | Lightweight desktop | Web          | Larger desktop  | Large desktop |

## Installation
1. Download the latest .zip package
2. Extract using 7-Zip or WinRAR
3. Run NC TaskSuite.exe
4. Optional: Pin to Start or Taskbar

No installation required. Fully offline and portable.

## License
NC TaskSuite is provided free for personal and educational use only.
Users may use the software as-is but are not permitted to modify, redistribute, sell,
or otherwise exploit it without explicit written permission from the developer.
All rights reserved by Noriel Calingasan.



