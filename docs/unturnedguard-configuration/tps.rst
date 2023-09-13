TPS
===

``TPS`` is the one of the plugin configuration parameter.

The ``TPS`` - this option is very useful and has many folks, it handles micro-lags on your server, and if it lower that specified then most of the features will stop their work for a while.


.. warning::

    If you started getting a lot of logs in console about TPS that this is low, etc. We recommend to disable the logging of the TPS, by setting the ``ReportAnomalyTPS`` to ``false``.


RocketMod ``UnturnedGuard.RocketMod.configuration.xml``

.. code-block:: xml

    <ReportAnomalyTPS>true</ReportAnomalyTPS>
	<TPS>47</TPS>


OpenMod ``config.yaml``

.. code-block:: yaml

	ReportAnomalyTPS: true,
    TPS: 47