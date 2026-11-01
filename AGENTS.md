# Repository Guide

## Overview
- **Type**: Single-file vanilla HTML/JS web application (`m_asc4.html`) for managing school schedules and teacher guard/supervision duties (جدول الحراسة) with Arabic RTL interface.
- **Dependencies / Tooling**: None (no package manager, build scripts, or test suite). Runs directly in the browser.
- **Key Features**: Asymmetric sessions per period (handling multi-session periods with independent guard/reserve counts and strict teacher continuity), room pinning during morning/afternoon blocks, and fast CSP constraint-based distribution.

## Key Files
- `m_asc4.html`: Main application entrypoint containing the complete UI, logic, and styles.
- `اساتذة.xlsx` / `اساتذةوزارة التربية الوطنية .xlsx`: Excel spreadsheets containing teacher data and lists.
- `template_قالب جديد فيزياء.json` / `jadwal_backup_20260327_214248.json`: JSON data templates and backups.

## Development & Testing
- No build step or test runner. Test changes by opening `m_asc4.html` in a web browser.
