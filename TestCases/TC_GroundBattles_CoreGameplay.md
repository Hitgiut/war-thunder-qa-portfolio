# Test Cases – Ground Battles Core Gameplay Validation

## General Info

- **Project:** War Thunder QA Portfolio
- **Mode:** Ground Battles (Realistic)
- **Platform:** PC (Windows)
- **Related Test Plan:** TP-001

---

# Vehicle Spawn & Initialization

## TC-001 – Vehicle Spawn Validation

**Objective:** Verify vehicle spawns correctly.

**Steps:**
1. Enter Ground Battle.
2. Select vehicle.
3. Spawn into match.

**Expected Result:**
Vehicle spawns on valid terrain without clipping.

---

## TC-002 – Spawn Camera Initialization

**Objective:** Validate camera state after spawning.

**Steps:**
1. Spawn vehicle.
2. Observe default camera.

**Expected Result:**
Camera initializes correctly in third-person view.

---

## TC-003 – Spawn Movement Validation

**Objective:** Validate movement immediately after spawn.

**Steps:**
1. Spawn vehicle.
2. Move forward/backward.

**Expected Result:**
Vehicle responds correctly without delay.

---

# Vehicle Movement & Physics

## TC-004 – Forward Movement Physics

**Objective:** Validate forward movement on flat terrain.

**Steps:**
1. Drive forward continuously.

**Expected Result:**
Smooth movement without jitter or floating.

---

## TC-005 – Terrain Incline Interaction

**Objective:** Validate uphill/downhill physics.

**Steps:**
1. Drive up a slope.
2. Drive down.

**Expected Result:**
Vehicle follows terrain naturally.

---

## TC-006 – Collision With Objects

**Objective:** Validate collision detection.

**Steps:**
1. Drive into rock/building.

**Expected Result:**
Vehicle stops or reacts physically.

---

## TC-007 – Edge Terrain Stability

**Objective:** Validate edge-case terrain behavior.

**Steps:**
1. Drive near cliffs or uneven terrain.

**Expected Result:**
Vehicle remains grounded.

---

# Camera Systems

## TC-008 – Third-Person Camera Stability

**Objective:** Validate camera tracking.

**Steps:**
1. Rotate vehicle.
2. Move quickly.

**Expected Result:**
Camera follows smoothly.

---

## TC-009 – Gun Sight Transition

**Objective:** Validate switch to gun sight.

**Steps:**
1. Switch to gun sight view.

**Expected Result:**
View transitions without glitches.

---

## TC-010 – Binocular View Validation

**Objective:** Validate binocular camera.

**Steps:**
1. Activate binoculars.
2. Zoom in/out.

**Expected Result:**
Stable zoom and camera behavior.

---

# Combat & Projectiles

## TC-011 – Projectile Firing Validation

**Objective:** Verify projectile firing behavior.

**Steps:**
1. Fire main gun.

**Expected Result:**
Projectile launches correctly.

---

## TC-012 – Hit Registration

**Objective:** Validate hit detection.

**Steps:**
1. Shoot enemy vehicle.

**Expected Result:**
Hit registers correctly.

---

## TC-013 – Destroyed Vehicle Rendering

**Objective:** Validate destroyed vehicle visuals.

**Steps:**
1. Observe destroyed tank.

**Expected Result:**
No visual artifacts.

---

## TC-014 – Projectile Visual Persistence

**Objective:** Check projectile artifacts.

**Steps:**
1. Zoom into destroyed vehicle.

**Expected Result:**
No stuck projectile visible.

---

# Enemy Interaction

## TC-015 – Enemy Vehicle Ground Alignment

**Objective:** Validate enemy vehicle grounding.

**Steps:**
1. Observe enemy tanks moving.

**Expected Result:**
Vehicles remain on terrain.

---

## TC-016 – Enemy Path Movement

**Objective:** Validate enemy movement logic.

**Steps:**
1. Track enemy movement.

**Expected Result:**
Natural pathing without levitation.

---

# Stability & Edge Cases

## TC-017 – Alt-Tab Stability

**Objective:** Validate game stability when alt-tabbing.

**Steps:**
1. Alt-tab during match.
2. Return to game.

**Expected Result:**
Game remains stable.

---

## TC-018 – Camera Switching Stress Test

**Objective:** Validate rapid camera switching.

**Steps:**
1. Rapidly switch views.

**Expected Result:**
No visual glitches or crashes.

---

## TC-019 – Replay Camera Validation

**Objective:** Validate replay camera systems.

**Steps:**
1. Open replay.
2. Switch cameras.

**Expected Result:**
Replay functions correctly.

---

## TC-020 – Audio Consistency During Combat

**Objective:** Validate audio transitions.

**Steps:**
1. Switch between views during combat.

**Expected Result:**
Audio remains consistent without distortion.

---