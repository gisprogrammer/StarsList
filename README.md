# StarsList - Oracle APEX Plugin

StarsList is a plugin for Oracle APEX that allows displaying a list of items as a label and a rating (stars) from 0 to 5. It can be used, for example, to rate skills in a CV or other rating systems.

https://ttjqq4ypwecymi3-barberapp.adb.eu-frankfurt-1.oraclecloudapps.com/ords/r/mc/plugins/starslist

## Features
- Displays values as stars (from 0 to 5)
- Customizable styles and colors
- Supports APEX Dynamic Actions
- Easy integration with Oracle database

## Installation
1. Download the `starslist_plugin.sql` file from the repository.
2. Log in to your Oracle APEX environment.
3. Navigate to **Shared Components** → **Plug-ins**.
4. Click "Import" and select the `starslist_plugin.sql` file.
5. Follow the installation wizard instructions.

## Usage
1. Add a new **StarsList** item to an APEX page.
2. Configure the data source (e.g., a table column containing ratings from 0 to 5).
3. Customize the style and interactions using the item properties.

## Example SQL
If you want to display skill ratings from the `skills` table, you can use the following query:

```sql
SELECT skill_name, rating FROM skills;
```

## Screenshots
![StarsList](https://github.com/user-attachments/assets/d0f3814b-c219-438e-9b59-da5ef32429a5)


## License
This project is licensed under the **GNU General Public License v3.0**.

## Support & Contact
If you have any questions or suggestions, please reach out via GitHub Issues or submit a pull request.

---
© 2025 StarsList - Oracle APEX Plugin

Apex plugin 
