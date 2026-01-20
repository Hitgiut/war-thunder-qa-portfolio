# FIX-001 – Fix Verification: Radar lock on submerged ships

- **Date:** 2026-01-20
- **Platform:** PC Windows
- **Mode:** Naval Custom Battle
- **Build/Version:** 2.53.0.56
- **Status:** ✅ PASS (Fixed)

## Patch Note 2.53.0.56

A bug that allowed aircraft radars and radar seekers to acquire already submerged ships has been fixed.

## Test Setup

- Aircraft used: F2A ADTW
- Radar mode: TWS SEA
- Target: ship wreck after being destroyed and fully submerged

## Steps to Verify

1. Start a Naval battle (custom match).
2. Enable aircraft radar and scan for targets on the water.
3. Acquire/lock a ship while it is alive.
4. Wait until the ship is destroyed and becomes fully submerged.
5. Attempt to acquire/lock the submerged ship again.

## Expected Result

Aircraft radar seekers should NOT lock fully submerged ships.

## Actual Result

Radar did not lock targets after they were fully submerged.

## Result

✅ PASS – Fix verified (issue no longer reproducible)
