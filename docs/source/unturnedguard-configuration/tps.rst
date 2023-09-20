TPS
===

``TPS`` is the one of the plugin configuration parameter.

The ``TPS`` - this option is very useful and has many folks, it handles micro-lags on your server, and if it lower that specified then most of the features will stop their work for a while. 
In simple words, its so similar to ``FPS`` when it lowers on the server - everything is lagging.


.. warning::

    If you started getting a lot of logs in console about TPS that this is low, etc. We recommend to disable the logging of the TPS, by setting the ``ReportAnomalyTPS`` to ``false``.
    The TPS is very unique per every server and should be configured by playing with TPS, because your server could have high demand but actually its fine for you standard work of your server.


RocketMod ``UnturnedGuard.RocketMod.configuration.xml``

.. code-block:: xml

    <ReportAnomalyTPS>true</ReportAnomalyTPS>
	<TPS>47</TPS>


OpenMod ``config.yaml``

.. code-block:: yaml

	ReportAnomalyTPS: true
	TPS: 47