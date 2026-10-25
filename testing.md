# CIT 240 Project - Test Documentation

## 1. Overview
This document outlines the testing checklist and verification logs for the CIT 240 project repository. It tracks functional checks across feature branches, pull requests, and documentation files (`README.md`, `team.md`).

## 2. Test Environment
- **Branch Tested:** `main` (post-merge of PR #2: `feature/team-profile`)
- **Repository Baseline:** Initial CIT 240 setup

---

## 3. Verification Checklist

| Test Item | Target File / Feature | Expected Result | Status | Verified By |
| :--- | :--- | :--- | :--- | :--- |
| **TC-01** | `README.md` | File renders properly, contains project intro & setup instructions | [x] Passed | Lorence-22 |
| **TC-02** | `team.md` | Lists all team member profiles and roles accurately | [x] Passed | ibiezajomary-stack |
| **TC-03** | PR #2 Merge | Changes from `feature/team-profile` integrated cleanly into `main` | [x] Passed | escoteliezel-cloud |
| **TC-04** | Markdown Linting | Clean formatting, working links, and valid headers across `.md` files | [ ] Pending | |
| **TC-05** | Repository Structure | All required course deliverables present for CIT 240 | [ ] In Progress | |

---

## 4. Contributors & Testing Roles

- **Mary Charlyn Gonzales** — Project Setup & Baseline Structure
- **Lorence-22** — Initial `README.md` Documentation
- **escoteliezel-cloud** — PR Review & Merge Verification (`feature/team-profile`)

---

## 5. Test Logs & Notes

- **2026-10-21:**
  - Initial repository setup verified (`74402fe`).
  - Added base files: `team.md` (`5fed8b3`) and `README.md` (`719c5c9`).
  - Updated member profile details in `team.md` (`33d9d84`).
- **2026-10-22:**
  - Merged PR #2 from `m-c-g81925/feature/team-profile` (`991ff19`).
  - Confirmed all profile updates are visible on the `main` branch.
