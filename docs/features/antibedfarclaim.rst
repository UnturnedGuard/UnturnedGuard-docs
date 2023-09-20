AntiBedFarClaim
===============

**AntiBedFarClaim** is one of the features offered by UnturnedGuard.

Overview
********

This feature does not directly ban players on its own or cancel any of their in-game actions. Instead, it monitors and reports abnormal behavior related to bed claiming in the game Unturned.

Reporting Abnormal Behavior
***************************

**AntiBedFarClaim** is designed to report when a player exceeds an abnormal distance while claiming a bed. When such an event occurs, you will receive a notification in the following channels:

Here is an example of the notification message:

.. code-block:: console

	"Player: 7656.. Exceeded abnormal bed claim distance: {distance}"


How to Respond
**************

Upon receiving a notification, it is important to assess the situation before taking any action against the player. Here are some recommended steps:

1. Consider False Positives: 

- It can be a false positive, maybe player or server has a ping increase for a while or something else.

2. Build a Moderation Team: 
   
- Having a dedicated moderation team with at least 1-2 members who understand the UnturnedGuard system is highly beneficial. Share documentation about UnturnedGuard with them and ensure they grasp the basics of handling such reports.
  
3. Analyze Player Activity: 
   
- Review the player's activity on the server. Check if they have been reported multiple times by UnturnedGuard in the past. Familiarize yourself with their SteamIDs to track their history.
  
4. Maintain Player Communication: 
   
- Engage with the players involved. Ask them to understand the situation and provide any evidence they may have. If other players have reported suspicious behavior or if you have video evidence of abnormal behavior, take these factors into account.

Configuration
*************

You can customize the behavior of the **AntiBedFarClaim** feature using the following argument:

- ``CancelAbnormalBehavior`` (true/false): Determines whether the feature should cancel abnormal player actions detected by UnturnedGuard.


RocketMod configuration (UnturnedGuard.RocketMod.configuration.xml)

.. code-block:: xml

	<Feature>
      <Name>AntiBedFarClaim</Name>
      <Enabled>true</Enabled>
      <Arguments>
        <Argument>
          <Name>CancelAbnormalBehavior</Name>
          <Value xsi:type="xsd:boolean">false</Value>
        </Argument>
      </Arguments>
    </Feature>


OpenMod configuration (config.yaml)

.. code-block:: yaml

	Features:
      - Name: "AntiBedFarClaim"
        Enabled: true
    	Arguments:
          - Name: "CancelAbnormalBehavior"
            Value: false
    