# ticketcleaner
New home for Ticket Cleaner GLPi plugin

Currently mirrors https://forge.glpi-project.org/projects/ticketcleaner


# Release 2.0.0
Beware that this new release will not keep your existing filters. You'll have to input them again with the new interface that permits to edit them directly into GLPi.
Your former filters will be copied into a backup table that you may edit via your preferred mySQL query editor (table name is `backup_glpi_plugin_ticketcleaner_filters`).
You'll have to combine your former filters to get the new ones that will be entered into the new table, or to create new one from scratch.

This version also brings the possibility to debug your regex using the GLPi debug mode (see wiki).
 