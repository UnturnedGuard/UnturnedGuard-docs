Guard Database Store Type
=========================

``GuardDatabaseStoreType`` is the one of the plugin configuration parameter.

Its the most important option in the UnturnedGuard, the heart of the anticheat, and depends on your own.
The ``GuardDatabaseStoreType`` - means the way how the things will be stored, in which type of the database.

Available options for the database store type:
- LiteDB
- PostgreSQL
- MySQL

.. note::

    Database Pick Recommendations:
    - Select LiteDB if you need a local Database in file to only work with your single server and you need performance.
    - Select PostgreSQL if you want a shared database for your multiple servers.
    - Select MySQL if you want a shared database for your multiple servers.

RocketMod ``UnturnedGuard.RocketMod.configuration.xml``

.. code-block:: xml

	<GuardDatabaseStoreType>LiteDB</GuardDatabaseStoreType>


OpenMod ``config.yaml``

.. code-block:: yaml

	GuardDatabaseStoreType: "LiteDB"