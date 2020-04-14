**class:**
cellphones

**attributes**
* phone_name (string)
* update_number (integer)
* price (float)
* apps_folder { hash - keys are app_names : values are app_size float }
* hard_drive_used (float)
* hard_drive_max (float)
* hard_drive_space_left (float)

**methods**
* change_phone_name (modify phone_name from defaut)
* download_app (modify apps_folder with new app and increase hard_drive_used decrease hard_drive_space_left)
* delete_app (modify apps_folder by removing app and decrease hard_drive_used and increase hard_drive_space_left)
* install_update (modify update_number +1)
