# TP-001 – Ground Battles Vehicle Physics & Core Gameplay Validation

## General Information

- **Test Plan ID:** TP-001  
- **Project:** War Thunder QA Portfolio  
- **Author:** Diogo Martins  
- **Version:** 1.0  
- **Date:** [Insert Date]  
- **Game:** War Thunder  
- **Platform:** PC (Windows)  
- **Mode:** Ground Battles (Realistic)

---

## 1. Objective

The objective of this test plan is to validate core gameplay systems in Ground Battles, focusing on vehicle physics, terrain interaction, camera systems, and combat mechanics.

Main goals:

- Identify functional defects
- Detect physics anomalies
- Validate collision behavior
- Verify gameplay stability after updates

---

## 2. Scope

### Included Systems

- Vehicle spawning
- Vehicle movement and physics
- Terrain interaction
- Collision detection
- Camera systems (Gun sight / Binoculars / Third-person)
- Projectile behavior (visual and gameplay)
- Enemy vehicle positioning

### Out of Scope

- Air Battles
- Naval Battles
- Economy systems
- Menus outside combat

---

## 3. Test Environment

- **Platform:** PC (Windows)
- **Game Mode:** Ground Battles (Realistic)
- **Build Version:** Latest available during testing
- **Network:** Stable internet connection
- **Graphics Settings:** Medium–High

---

## 4. Test Types

- Functional Testing
- Exploratory Testing
- Regression Testing
- Edge Case Testing
- Visual Validation Testing

---

## 5. Entry Criteria

Testing begins when:

- Game launches successfully
- Match loads correctly
- Vehicle selection is available
- No startup crashes occur

---

## 6. Exit Criteria

Testing is considered complete when:

- All planned test cases are executed
- Critical and major bugs are documented
- Fix verification is performed when applicable
- Evidence is collected (screenshots/videos)

---

## 7. Risk Areas

High-risk areas identified:

- Vehicle physics interactions
- Terrain clipping
- Collision box accuracy
- Projectile rendering
- Client-server synchronization (desync)

---

## 8. Test Strategy

### Structured Testing

Execution of predefined test cases covering:

- Vehicle spawning
- Movement validation
- Terrain interaction
- Combat behavior

### Exploratory Testing

Free gameplay testing focused on:

- Edge-case scenarios
- Physics anomalies
- Visual artifacts
- Unexpected gameplay interactions

---

## 9. Deliverables

This test plan will produce:

- Structured Bug Reports
- Test Cases documentation
- Fix Verification reports
- Visual evidence (screenshots)

---

## 10. Success Criteria

Testing is successful if:

- Core gameplay systems behave consistently
- Vehicles interact correctly with terrain
- No major physics-breaking issues are observed
- Bugs are reproducible and clearly documented

