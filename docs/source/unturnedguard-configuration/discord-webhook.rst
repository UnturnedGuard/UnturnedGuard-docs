DiscordWebhook and DiscordWebhookEnabled
========================================

``DiscordWebhook`` is the one of the plugin configuration parameter, and work together with ``DiscordWebhookEnabled``.

The ``DiscordWebhook`` - is a URL to the your Discord Webhook channel. It means when you set this property and ``DiscordWebhookEnabled`` to ``true`` then it will gonna send a messages not only using the console and logs and your Discord channel, such as:

- Spotted Players
- Banned Players
- Requested Players by the anticheat to be banned, but, in which anticheat is not 100% ensure, and this is can be a false positive (anticheat will provide all information why player was spotted)
- And many-many more...


RocketMod ``UnturnedGuard.RocketMod.configuration.xml``

.. code-block:: xml

	<DiscordWebhook>Your Discord Webhook URL</DiscordWebhook>
	<DiscordWebhookEnabled>true</DiscordWebhookEnabled>


OpenMod ``config.yaml``

.. code-block:: yaml

	DiscordWebhook: "Your Discord Webhook URL"
	DiscordWebhookEnabled: true