# Discourse restrict user status
This component restricts the ability of Discourse users to set user status to select groups, including forum staff, superusers, etc. If you have not yet enabled the user status plugin, just install this themem component and configure it's settings.  Then go to admin-settings and enable the "enable user status" setting.

If you have already enabled the user status plugin and let users fill their user status, then you will either need remove and to re-install the plugin from in rails or do a rails rake task on user statuses to reset them all to default blank setting (backup first anytime you do rails commmands!).
