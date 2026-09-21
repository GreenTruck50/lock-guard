# Lock Guard

Lock Guard is a GNOME Shell extension that strengthens the lock screen by hiding extra UI, suppressing keybindings, and warning after repeated failed unlock attempts.

It supports GNOME Shell 50 and runs in the unlock dialog session mode.

## Features

- Hides the date from the lock screen
- Hides quick settings while locked
- Disables allowed keybindings during the lock screen session
- Tracks failed login attempts
- Shows a critical security warning after 3 or more failed unlock attempts

## Why this exists

The extension hooks into the screen shield unlock flow and listens for authentication failures from the user verifier. When a user fails to unlock repeatedly, it raises a warning notification so the issue is visible even while the lock dialog is active.

## Installation

The recommended way is through [Gnome Extensions](https://extensions.gnome.org/extension/8971/lock-guard/)
