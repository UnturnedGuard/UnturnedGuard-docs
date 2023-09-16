Does UnturnedGuard is updating automatically or how it works?
=========================

Indeed, by default, UnturnedGuard has Moderation2 support, to enable the integration you need to configure your plugin configuration, by default it's disabled, and set to false.

Open-up your file configuration of the plugin, and set the ``Moderation2Integration`` to true, this would look like this:

RocketMod ``UnturnedGuard.RocketMod.configuration.xml``

.. code-block:: xml

	<Moderation2Integration>true</Moderation2Integration>


OpenMod ``config.yaml``

.. code-block:: yaml

	Moderation2Integration: true


Done! Reload your plugin or restart the server, and don't forget to save the configuration file.