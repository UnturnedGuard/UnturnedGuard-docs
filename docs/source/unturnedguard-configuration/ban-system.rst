BanSystem
==========

The **BanSystem** (ban system) configuration parameter is an essential setting offered by UnturnedGuard, designed to control how player bans are managed within the plugin.

Overview
********

**BanSystem** determines the specific ban system that UnturnedGuard will employ to restrict players. It dictates the methodology and data collection approach used for player bans. You have two primary options for configuring the ban system:

1. **UnturnedGuard** (Default Built-in BanSystem): This option enables UnturnedGuard to utilize its own integrated ban system, which comes with enhanced data collection capabilities for a more robust ban management process.
2. **UnturnedVanilla** (Unturned Standard BanSystem): By selecting this option, UnturnedGuard will integrate with Unturned's default standard ban system, adhering to the standard ban procedures provided by Unturned itself.

Configuration
*************

Here's how you can configure the **BanSystem** in UnturnedGuard for different mod frameworks, you have those options to enter in **BanSystem**:

- **UnturnedGuard**
- **UnturnedVanilla**


RocketMod configuration (UnturnedGuard.RocketMod.configuration.xml)

.. code-block:: xml

	<BanSystem>UnturnedGuard</BanSystem>


OpenMod configuration (config.yaml)

.. code-block:: yaml

	BanSystem: "UnturnedGuard"


Choose the appropriate **BanSystem** option based on your requirements and the level of control you need over player bans within your Unturned server.