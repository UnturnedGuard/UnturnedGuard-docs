SendPingMessageInDiscordWebhook
===============================

``SendPingMessageInDiscordWebhook`` is the one of the plugin configuration parameter, work together with ``DiscordWebhookEnabled``, and ``DiscordWebhook``.

The ``SendPingMessageInDiscordWebhook`` - is a option which should be set to ``true`` if you want to get a notification message into the specified Discord Webhook, to understand that webhook is work fine, but if you have a lot of servers it can be annoying that you receive like 10+ messages at the same time.

RocketMod ``UnturnedGuard.RocketMod.configuration.xml``

.. code-block:: xml

	<DiscordWebhook>Your Discord Webhook URL</DiscordWebhook>
	<DiscordWebhookEnabled>true</DiscordWebhookEnabled>
	<SendPingMessageInDiscordWebhook>true</SendPingMessageInDiscordWebhook>


OpenMod ``config.yaml``

.. code-block:: yaml

	DiscordWebhook: "Your Discord Webhook URL"
	DiscordWebhookEnabled: true
	SendPingMessageInDiscordWebhook: true