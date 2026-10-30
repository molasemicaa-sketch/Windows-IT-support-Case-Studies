## Case Study 05: Application Crashing

### Problem Statement

An employee reports that an application on their Windows computer frequently crashes while in use. The application suddenly closes, freezes, or displays an error message whenever the employee attempts to perform certain tasks. This issue interrupts the employee's workflow and may result in lost progress or unsaved work. The employee needs the application to function properly to complete an important work assignment.

### Initial Questions

1. Which application is crashing, and what error message appears when the problem occurs?

2. Does the application crash immediately after opening, or does it happen while performing a specific task?

3. Did the problem begin after a recent Windows update, application update, or software installation?

4. Does the application crash for other users or only on the employee's computer?

### Possible Causes

- Corrupted application files or installation components.

- Outdated or incompatible application software.

- Insufficient system resources, such as RAM or CPU capacity.

- Conflicts with other applications, background processes, or security software.

- Outdated graphics drivers or incompatible device drivers.

- Damaged user settings, configuration files, or Windows system files.

### Troubleshooting Process

1. **Restart the application.** Close the affected application completely and open it again. If the application is unresponsive, use Task Manager by pressing `Ctrl + Shift + Esc` to end the task. Save any recoverable work before closing the application whenever possible.

2. **Restart the computer.** If the application continues to crash, restart Windows to clear temporary system issues and release resources being used by background processes. Reopen the application and check whether the problem persists.

3. **Check system resources.** Open Task Manager and inspect CPU, Memory, and Disk usage while running the application. Determine whether resource limitations or another process may be contributing to the crashes.

4. **Check for application updates.** Open the application's built-in update settings or the organization's approved software portal. Install available compatible updates according to company policy, then test the application again.

5. **Review error messages and logs.** Record the exact error message and the circumstances under which the application crashes. Open Event Viewer by entering `eventvwr.msc` in the Run dialog. Check **Windows Logs > Application** for errors recorded around the time of the crash.

6. **Repair the application.** If the application continues to fail, open **Settings > Apps > Installed apps**. Select the application and check whether a **Modify**, **Repair**, or similar option is available. Use the supported repair procedure. Avoid resetting or reinstalling the application before confirming that important files and settings are backed up.

7. **Analyze the results.** Test the application after each troubleshooting step. If it still crashes, investigate compatibility issues, problematic plugins, damaged configuration files, driver problems, or application-specific errors. Escalate the issue to IT support if administrative access or advanced diagnostics are required.

## 5. Resolution

For this example, suppose the investigation identifies corrupted application files as the main cause of the repeated crashes.

After confirming that the employee's work and important application data are protected, the technician opens Windows Settings and uses the application's built-in repair option. The repair process restores the affected application components without requiring a complete reinstallation.

The technician restarts the application and performs several tests using the functions that previously caused it to crash. The application opens successfully, responds normally, and completes the required tasks without displaying further errors.

The employee confirms that the application is working properly and resumes the work assignment.

## 6. Preventive Measures

- Keep applications updated using official or organization-approved sources.

- Save work frequently and enable automatic saving or recovery features when available.

- Ensure that the computer meets the application's minimum system requirements.

- Avoid installing unauthorized plugins, extensions, or incompatible software.

- Maintain updated Windows components and device drivers according to company policy.

- Monitor recurring application errors and document their error messages and resolutions.

- Report persistent crashes to the IT support team, particularly when multiple users experience the same issue.

### Conclusion

The case demonstrates a systematic approach to troubleshooting application crashes. By restarting the application, checking system resources, reviewing error logs, installing approved updates, and repairing damaged application files, a technician can identify potential causes and apply appropriate solutions. Regular software maintenance, proper data protection, and timely troubleshooting help improve application stability and minimize interruptions to employee productivity.
