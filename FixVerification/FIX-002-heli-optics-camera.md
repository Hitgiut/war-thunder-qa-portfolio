# FIX-002 – Fix Verification: Helicoper optics camera jump

- **Date:** 2026-01-20
- **Platform:** PC Windows
- **Mode:** Test Flight
- **Build/Version:** 2.53.0.56
- **Status:** ✅ PASS (Fixed)

## Patch Note 2.53.0.56

A bug that sometimes caused the camera on helicopters to move to another point when switching to the targeting optics view has been fixed.

## Test Setup

- Helicopter used: AH-64A (GR)

## Steps to Verify

1. Start a helicopter Test Flight.
2. Switch to targeting optics view (TOV) 10+ times while hovering.
3. Repeat while moving/rotating and switching TOV 10+ times.
4. Observe camera/aim behavior when re-entering TOV.

## Expected Result

Camera should remain stable and not jump to an unexpected point when switching to targeting optics view.

## Actual Result

Targeting optics birefly retained the last aim point when re-entering TOV, then smoothly synchronized to the current camera direction when we switch back to other camera.

No unexpected camera teleporting to random points was observed.

## Result

✅ PASS – Fix verified (issue no longer reproducible)

## Evidence

[Youtube Link](https://www.youtube.com/watch?v=CY4ha4e-fDY) (0:00 - 0:25 --> Testing when the helicopter is hovering; 0:25 - 1:19 --> Testing while moving and rotating)
