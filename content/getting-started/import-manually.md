---
title: "Import manually"
description: "Each demo consists of 3 components: content, settings and widgets. Content and settings take up 85 - 95%. Hence each demo require 3 files:"
---

### Prepare necessary files

Each demo consists of 3 components: content, settings and widgets. Content and settings take up 85 - 95%. Hence each demo require 3 files:

1. `customizer.dat`
2. `content.xml`
3. `widgets.wie`

Before importing, visit the **[demo list](https://fox.withemes.com/demolist/)**, find the demo you want to import, then download 3 required files. **Note**: File names might be different, but you only need to pay attention to file extensions (*dat for customizer, *xml for content, *wie for widgets)

Visit demo list

### Step 1: Import XML content

1. Go to **Dashboard > Tools > Import > Install WordPress Importer**. After that, Run Importer.
2. Upload the `conten.xml` file, hit “**Upload file and import**”.
3. Go to **Dashboard > Appearance > Menus**, then assign menus to *Primary Menu* location and *Footer Menu* location.

### Step 2: Import Customizer settings

1. Install [Customizer Export/Import plugin](https://wordpress.org/plugins/customizer-export-import/), activate it.
2. Go to **Dashboard > Appearance > Customize > Export/Import** > Choose file `customizer.dat` you’ve prepared, then hit **Submit**. After importing, you'll see a dead screen. Don't worry, just ignore it. You can close that tab, or refresh it.

### Part 3: Import widgets

1. Install [Widget Importer & Exporter](https://wordpress.org/plugins/widget-importer-exporter/) plugin
2. Go to **Dashboard > Tools > Widget Importer & Exporter** then upload `widgets.wie` file you prepared, then hit “**Import Widgets**”.
3. You might see the error message "Specified file failed upload.." after uploading *wie file. Please go "**Back**". Then hit "copy and paste" the contents of .wie file. Open your widgets.wie file, copy & paste its content then hit **Import Widgets** again. Now it'll work.
