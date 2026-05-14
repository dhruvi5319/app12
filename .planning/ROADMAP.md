# Roadmap: Simple Task Tracker

## Overview

Starting from a blank slate, this roadmap delivers a working single-user task tracker in two phases. Phase 1 builds the interactive UI where users can create and view tasks. Phase 2 wires in local storage so nothing is lost on page refresh. Together they satisfy all v1 requirements and deliver the core value: users can quickly capture and track tasks so nothing falls through the cracks.

## Phases

**Phase Numbering:**
- Integer phases (1, 2, 3): Planned milestone work
- Decimal phases (2.1, 2.2): Urgent insertions (marked with INSERTED)

Decimal phases appear between their surrounding integers in numeric order.

- [ ] **Phase 1: Core UI** - Scaffold the app and deliver task creation + list view as a working interface
- [ ] **Phase 2: Persistence** - Wire local storage so tasks survive page refreshes

## Phase Details

### Phase 1: Core UI
**Goal**: Users can create tasks and see them listed in a working app
**Depends on**: Nothing (first phase)
**Requirements**: TASK-01, ORG-01
**Success Criteria** (what must be TRUE):
  1. User can open the app in a browser and see a task input field
  2. User can type a task title and submit it to add the task
  3. All added tasks appear in a list on screen immediately after creation
  4. The UI is usable without errors from first load
**Plans**: 2 plans

Plans:
- [ ] 01-01-PLAN.md — Scaffold HTML/CSS/JS app shell + Playwright test infrastructure
- [ ] 01-02-PLAN.md — Task creation logic, list rendering, and E2E Playwright tests

### Phase 2: Persistence
**Goal**: Tasks are retained across page refreshes without any user action
**Depends on**: Phase 1
**Requirements**: PERS-01
**Success Criteria** (what must be TRUE):
  1. Tasks added in Phase 1 are still visible after a full browser page refresh
  2. Tasks survive closing and reopening the browser tab
  3. No tasks are lost between sessions on the same device/browser
**Plans**: 1 plan

Plans:
- [ ] 02-01-PLAN.md — Wire localStorage into app.js + Playwright persistence tests

## Progress

**Execution Order:**
Phases execute in numeric order: 1 → 2

| Phase | Plans Complete | Status | Completed |
|-------|----------------|--------|-----------|
| 1. Core UI | 0/2 | Not started | - |
| 2. Persistence | 0/1 | Not started | - |
