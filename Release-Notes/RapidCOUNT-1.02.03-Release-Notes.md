# RapidCOUNT v1.02.03 Release Notes

**Release Date:** July 6th 2026

_This release improves reliability of quantity entry, focus handling, and timestamp accuracy during physical counts._

## Bug Fixes

### Count Entry Windows No Longer Dismiss Accidentally

Prompt for Quantity, Grid, and Serial entry windows can no longer be closed by tapping outside them, and swiping a window down now cancels it without saving.

* Confirming an entry is done only with the Done button, so counts are recorded in the order they are entered and stay in sequence on RapidPhysicalCount.com.

### Quantity Field Now Receives Focus Automatically

When Prompt for Quantity is enabled, the quantity field now correctly receives keyboard focus as soon as it opens after adding an item, instead of leaving focus on the item lookup field behind it.

### Correct Timestamp Now Shown on Quantity Entry

The quantity-entry window now shows the actual date and time the item was scanned instead of a placeholder date of 01/01/0001.

<img width="443" height="651" alt="image" src="https://github.com/user-attachments/assets/cf263ad5-065e-4732-a20a-e30c1a5868c8" />
