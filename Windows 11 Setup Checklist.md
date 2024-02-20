# Windows 11 Setup Checklist

## System Settings
- [ ] Change display scaling if necessary  
  Adjust the size of text, apps, and other items on your screen by going to Settings > System > Display and modifying the scaling percentage.

- [ ] Customize desktop background and theme  
  Personalize your desktop by right-clicking on the desktop, selecting "Personalize," and choosing your preferred background image and theme settings.

- [ ] Adjust power settings (e.g., sleep mode, screen timeout)  
  Customize power options to suit your usage patterns and preferences by navigating to Settings > System > Power & sleep.

- [ ] Configure system updates preferences  
  Manage how Windows updates are installed and scheduled by going to Settings > Windows Update > Advanced options.

- [ ] Set up system restore points  
  Create restore points to revert your system to a previous state if needed by searching for "Create a restore point" in the Start menu and following the prompts.

- [ ] Customize taskbar and Start menu layout  
  Right-click on the taskbar and select "Taskbar settings" to customize the taskbar's behavior and appearance. For the Start menu, right-click on the Start button and choose "Settings" to personalize its layout.

- [ ] Enable or disable animations and visual effects  
  Adjust visual effects and animations to improve performance or enhance visual appeal by searching for "Performance Options" in the Start menu and modifying settings under the Visual Effects tab.

- [ ] Configure default apps for file types and protocols  
  Set your preferred applications for opening specific file types and handling different protocols by going to Settings > Apps > Default apps.

## Security and Privacy
- [ ] Enable Windows Defender antivirus and firewall  
  Ensure your system is protected against malware and other threats by activating Windows Defender antivirus and firewall through Settings > Update & Security > Windows Security.

- [ ] Configure Windows Security settings  
  Review and adjust Windows Security settings to customize antivirus, firewall, and other security features according to your needs.

- [ ] Review and adjust privacy settings (e.g., telemetry, app permissions)  
  Navigate to Settings > Privacy to review and adjust privacy settings related to app permissions, diagnostic data, and other privacy concerns.

- [ ] Set up BitLocker or other disk encryption if desired  
  Encrypt your disk drives to protect sensitive data from unauthorized access by searching for "BitLocker" in the Start menu and following the instructions to set it up.

- [ ] Enable Secure Boot if supported by hardware  
  Secure Boot helps prevent unauthorized operating systems and bootloaders from loading during the startup process. Check your system's BIOS or UEFI firmware settings to enable Secure Boot if supported.

## Productivity and Accessibility
- [ ] Install necessary productivity software (e.g., Microsoft Office, web browsers)  
  Install essential productivity software to fulfill your work and personal needs. Visit the official websites of respective software or use Microsoft Store to download and install apps.

- [ ] Customize keyboard shortcuts and input settings  
  Tailor keyboard shortcuts and input settings to improve efficiency and accessibility. Navigate to Settings > Devices > Typing and explore options for keyboard, touch keyboard, and other input devices.

- [ ] Set up virtual desktops if needed  
  Utilize virtual desktops to organize and manage multiple tasks or projects efficiently. Press Win + Tab to open Task View, then click "New desktop" to create additional desktops.

- [ ] Configure accessibility options (e.g., magnifier, narrator)  
  Enhance accessibility by adjusting settings such as magnifier, narrator, and high contrast mode. Explore accessibility options in Settings > Accessibility.

## Additional Tweaks
- [ ] Disable unnecessary startup programs  
  Improve system startup time and performance by disabling unnecessary programs from launching at startup. Open Task Manager (Ctrl + Shift + Esc), navigate to the Startup tab, and disable unwanted programs.

- [ ] Adjust notification settings  
  Customize notification behavior and manage app notifications by going to Settings > System > Notifications & actions.

- [ ] Customize file explorer options (e.g., show file extensions, change default view)  
  Personalize File Explorer settings to suit your preferences and workflow. Open File Explorer, go to View tab, and click on Options to access Folder Options and customize settings.

- [ ] Install and configure third-party software (e.g., media players, image editors)  
  Install additional software based on your specific needs and preferences. Visit official websites or trusted sources to download and install desired applications.

- [ ] Optimize disk and system performance (e.g., disk cleanup, defragmentation)  
  Maintain system performance by periodically performing disk cleanup, defragmentation, and other optimization tasks. Search for "Disk Cleanup" and "Defragment and Optimize Drives" in the Start menu to access these utilities.

- [ ] Backup important files and folders  
  Protect your data against loss or corruption by creating regular backups. Use built-in Windows Backup and Restore feature or third-party backup solutions to schedule backups of important files and folders.

- [ ] Set up system-wide search indexing preferences  
  Customize search indexing options to include or exclude specific locations and file types from search results. Go to Settings > Search > Searching Windows and customize indexing settings as needed.

## Troubleshooting and Support
- [ ] Create recovery media or USB drive  
  Prepare recovery media or USB drive to troubleshoot and repair your system in case of emergencies. Search for "Create a recovery drive" in the Start menu and follow the instructions to create recovery media.

- [ ] Familiarize yourself with Windows 11 troubleshooting tools  
  Learn about built-in troubleshooting tools and resources available in Windows 11 to diagnose and resolve common issues. Explore settings, control panel, and online support resources for troubleshooting guidance.

- [ ] Join relevant online communities or forums for support  
  Connect with other Windows users and experts in online communities or forums to seek help, share experiences, and find solutions to Windows-related problems.

- [ ] Check for driver updates and compatibility issues with hardware  
  Ensure your hardware components are compatible with Windows 11 and update device drivers to the latest versions for optimal performance and stability. Visit manufacturer websites or use Windows Update to check for driver updates.

## Additional Resources
- [Windows 11 Tips and Tricks](https://support.microsoft.com/en-us/windows/windows-11-tips-and-tricks-6f206c15-2537-4f10-8663-16180916e09c)
- [Windows 11 Community Forum](https://answers.microsoft.com/en-us/windows/forum/windows_11)

## Additional tweaks
- [ ] Disable lock screen console timeout  
  Prevent the lock screen from timing out and dimming by modifying the console lock display off timeout setting in the registry. Navigate to `HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\7516b95f-f776-4464-8c53-06167f40cc99\8EC4B3A5-6868-48c2-BE75-4F3044BE88A7` and change the Attributes value to 2.

- [ ] Customize Windows Explorer Quick Access  
  Customize the Quick Access section in Windows Explorer to show frequently accessed folders or remove unwanted items. Open File Explorer, go to View tab, click on Options, and customize Quick Access settings under General tab.

- [ ] Enable God Mode  
  Create a folder with the following name to access a centralized location for various system settings and options: `GodMode.{ED7BA470-8E54-465E-825C-99712043E01C}`. This folder provides access to a wide range of settings and controls.

- [ ] Disable Cortana or customize its behavior  
  Disable Cortana if you don't use it or customize its behavior and permissions by going to Settings > Cortana & Search and adjusting settings as needed.

- [ ] Customize Taskbar button grouping  
  Adjust Taskbar button grouping settings to combine or separate icons based on your preferences. Right-click on the Taskbar, go to Taskbar settings, and modify settings under Combine taskbar buttons.

## Registry Tweaks
- [ ] Disable Windows 11 animations  
  Improve system performance and responsiveness by disabling animations. Navigate to `HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\VisualEffects` and set the DWORD value for VisualFXSetting to 2.

- [ ] Disable automatic restart after Windows updates  
  Prevent Windows from automatically restarting after installing updates. Navigate to `HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\WindowsUpdate\AU` and create a new DWORD value named NoAutoRebootWithLoggedOnUsers, setting its value data to 1.

- [ ] Disable Windows Error Reporting  
  Disable the Windows Error Reporting service to prevent Windows from sending error reports to Microsoft. Navigate to `HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\Windows Error Reporting` and create a new DWORD value named Disabled, setting its value data to 1.

- [ ] Enable verbose status messages during startup  
  Display detailed information about the startup process to diagnose boot issues. Navigate to `HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\System` and create a new DWORD value named VerboseStatus, setting its value data to 1.

- [ ] Disable automatic driver updates  
  Prevent Windows from automatically installing driver updates through Windows Update. Navigate to `HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\DriverSearching` and set the DWORD value for SearchOrderConfig to 0.

- [ ] Disable automatic maintenance tasks  
  Disable automatic maintenance tasks to prevent background processes from interfering with system performance. Navigate to `HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Schedule\Maintenance` and set the DWORD value for MaintenanceDisabled to 1.