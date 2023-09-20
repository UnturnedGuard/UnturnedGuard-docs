Guard Database Connection String
================================

``GuardDatabaseConnectionString`` is the one of the plugin configuration parameter.

Its the most important option in the UnturnedGuard, the heart of the anticheat, and depends on your own.
The ``GuardDatabaseConnectionString`` - means the string of the database connection, and very depends by ``GuardDatabaseStoreType`` also.


RocketMod Connection String Examples:

- Example for the LiteDB: {WorkingDirectory}/unturnedguard.db

- Example for the MySQL: Server=localhost;Database=UnturnedGuard;User=root;Password=;


OpenMod Connection String Examples: 

- Example for the LiteDB: "{WorkingDirectory}/unturnedguard.db"

- Example for the MySQL: "Server=localhost;Database=UnturnedGuard;User=root;Password=;"


.. warning::

    Please, don't set the different types of the Store Type, and Connection String. Follow the examples, and recommendations down.

    Bad Example:

    GuardDatabaseConnectionString is {WorkingDirectory}/unturnedguard.db
    
    GuardDatabaseStoreType is MySQL

    Good Example:

    GuardDatabaseConnectionString is Server=localhost;Database=UnturnedGuard;User=root;Password=;

    GuardDatabaseStoreType is MySQL


RocketMod ``UnturnedGuard.RocketMod.configuration.xml``

.. code-block:: xml

	<GuardDatabaseConnectionString>{WorkingDirectory}/unturnedguard.db</GuardDatabaseConnectionString>


OpenMod ``config.yaml``

.. code-block:: yaml

	GuardDatabaseConnectionString: "{WorkingDirectory}/unturnedguard.db"