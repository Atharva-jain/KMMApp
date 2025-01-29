# Alarm and Theme Switcher App

This project demonstrates an Android app using Kotlin that integrates the following features:

## Features

1. **Theme Switching**:
   - Toggle between light and dark themes using a simple switch.

2. **Alarm Functionality**:
   - Schedule alarms using `AlarmManager` with exact and idle capabilities.
   - Notifications are triggered when alarms go off.

3. **Ringtone Picker**:
   - Allows users to choose and set a ringtone.

## Permissions

The app requires:
- `SCHEDULE_EXACT_ALARM` for scheduling alarms on Android 12+.
- `SET_ALARM` for scheduling alarms on older Android versions.

## How to Run

1. Clone this repository.
2. Open the project in Android Studio.
3. Build and run the app on an Android device or emulator.
4. Test the features:
   - Use the theme switcher to toggle themes.
   - Schedule an alarm and wait for the notification.
   - Try setting a ringtone.
   - Add the widget to your home screen.

## Tech Stack
- **Language**: Kotlin
- **UI Framework**: Android XML
- **APIs Used**: AlarmManager, RingtoneManager

## Files Overview
- `MainActivity.kt`: Handles theme switching, alarm setup, and ringtone selection.
- `AlarmReceiver.kt`: A BroadcastReceiver to handle alarm triggers.
- `activity_main.xml`: Layout for the main activity.
- `widget_layout.xml`: Layout for the home screen widget.

