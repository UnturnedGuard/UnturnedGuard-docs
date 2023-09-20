Ban System
==========

``BanSystem`` is the one of the plugin configuration parameter.

The ``BanSystem`` - means the ban system for the UnturnedGuard, how it will ban the players, in which way, the UnturnedGuard specific way with improved data collection or using Unturned default standard ban.

Ban system available options:

- UnturnedGuard to use a built-in ban system powered by UnturnedGuard itself.

- UnturnedVanilla to use a Unturned Vanilla ban system integration.


RocketMod ``UnturnedGuard.RocketMod.configuration.xml``

.. code-block:: xml

	<BanSystem>UnturnedGuard</BanSystem>


OpenMod ``config.yaml``

.. code-block:: yaml

	BanSystem: "UnturnedGuard"