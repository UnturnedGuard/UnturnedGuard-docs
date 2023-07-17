Unturned Ban Sync
=================

``UnturnedBanSync`` is the one of the plugin configuration parameter.

Its a very important synchronization with Unturned bans via /ban, /unban, due to server Administration with access to those command could make possible problems when the cheater got spotted by the UnturnedGuard but not banned yet, and the Administration /ban they via Unturned command, and this could lead to the issues when the player banned with invalid HWID, IP, etc.

.. note::

    Its recommended to stay this parameter as ``true`` in plugin configuration.

RocketMod ``UnturnedGuard.RocketMod.configuration.xml``

.. code-block:: xml

	<UnturnedBanSync>true</UnturnedBanSync>


OpenMod ``config.yaml``

.. code-block:: yaml

	UnturnedBanSync: true