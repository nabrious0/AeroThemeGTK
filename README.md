# AeroThemeGTK
AeroThemeGTK is an Aero theme for libadw applications. Intended to be used with AeroThemePlasma - currently in pre-alpha stages.

### How do I use this?
Clone the reposiory, then move it's contents to your ``~/.config/gtk-4.0`` directory, then launch any libadw app.

### To get Aero Glass Blur on the window, follow the following steps:
1. Right click the window's titlebar
2. Hover over ``More Actions``
3. Select ``Configure Special Application Settings``, a new window will open

![image](https://github.com/user-attachments/assets/dc256225-889d-4057-bb1b-be98497eeb3d)

6. Take note of the ``Window class (application)`` value (copy it)

![image](https://github.com/user-attachments/assets/06d795e9-ea94-4285-9d97-aef10fec4271)

8. Open ``System Settings``, specifically Aero Glass Blur settings under ``Desktop Effects``, click ``Configure`` to open the effect's settings a new window will open up.
9. Click the ``Overrides`` tab, and paste the value you copied earlier there, and to ensure maximum compatibility, also check ``Paint windows as non-opaque (fixes artifacts for some transparent windows)``

![image](https://github.com/user-attachments/assets/ff96a051-cdab-4fec-acf9-b214501b43cc)

10. Click ``Apply`` and relaunch your app.
