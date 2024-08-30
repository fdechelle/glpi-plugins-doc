Install the Plugin
------------------

From the marketplace
^^^^^^^^^^^^^^^^^^^^


Manually
^^^^^^^^

* Uncompress the archive.
* Move the ``carbon`` directory to the ``<GLPI_ROOT>/plugins`` directory
* Navigate to the *Configuration > Plugins* page,
* Install and activate the plugin.

.. warning::

   The plugin's directory must have the same name as the plugin:

     * **Good**: `glpi/plugins/carbon`
     * **Bad**: `glpi/plugins/carbon-master`
     * **Bad**: `glpi/plugins/carbon-1.0.0`

   Only one directory must contains the plugin's files of a single plugin in the GLPI plugins directory. **Don't rename the plugin's directory for backup, move it!**
