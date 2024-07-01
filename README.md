# Custom Drive Icon Changer

Welcome to the Custom Drive Icon Changer repository! This guide will walk you through the process of changing the icon for local disks or other drives on your Windows computer.

## Instructions

### Step 1: Prepare Your Icon

1. **Create or Obtain an Icon File:**
   - Find or create an `.ico` file that you want to use as the icon for your drive. Ensure the `.ico` file contains multiple icon sizes for compatibility.

### Step 2: Create Autorun Files

1. **Create Autorun.inf File:**
   - Open a text editor like Notepad.
   - Create a new text file named `autorun.inf` with the following content:
     ```
     [Autorun]
     icon=icon.ico
     label=Drive Label (optional)
     ```
     - Replace `icon.ico` with the actual filename of your `.ico` icon file.
     - Optionally, specify a `label` for the drive inside the `autorun.inf` file.

2. **Save the Files:**
   - Save the `autorun.inf` file and your `.ico` icon file in the root directory of the drive you want to customize (e.g., `C:\` for the local disk).

### Step 3: Make Hidden Files Visible (if needed)

1. **Show Hidden Files:**
   - In Windows Explorer, go to `View` > `Options` > `Change folder and search options`.
   - Select the `View` tab.
   - Under `Advanced settings`, select `Show hidden files, folders, and drives`.

### Step 4: Refresh Icon Cache

1. **Refresh Icon Cache:**
   - Sometimes, Windows may not immediately update the icon. You can refresh the icon cache by restarting Windows Explorer or by logging out and logging back in.

### Step 5: View the Updated Icon

1. **Check the Updated Icon:**
   - After refreshing the icon cache, the drive should now display the custom icon you specified.

## Preview

![Custom Drive Icon Preview](preview.jpg)

This image shows an example of a custom drive icon applied to a local disk.

## Support

If you encounter any issues or have questions, feel free to reach out:
- Instagram: [@erikurtti](https://instagram.com/erikurtti)
- GitHub: [ErjonKurti](https://github.com/ErjonKurti)
