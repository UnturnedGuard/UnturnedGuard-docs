DebugMode
==========

The **DebugMode** (debug mode) configuration parameter is an essential setting offered by UnturnedGuard, designed to manage detailed information in logs.

Overview
********

**DebugMode** is specificly made for testing, it enables a additional logging in the console and other useful information for Developers of the UnturnedGuard. Don't change this option while Developers didn't asked to.

Configuration
*************

Here's how you can configure the **DebugMode** in UnturnedGuard for different mod frameworks, you have those options to enter in **DebugMode**:

- **true** (to turn on this option)
- **false** (to turn off this option)


RocketMod configuration (UnturnedGuard.RocketMod.configuration.xml)

.. code-block:: xml

	<DebugMode>false</DebugMode>


OpenMod configuration (config.yaml)

.. code-block:: yaml

	DebugMode: false