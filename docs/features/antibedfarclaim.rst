AntiBedFarClaim
===============

``AntiBedFarClaim`` is the one of the UnturnedGuard feature.

Does this feature bans the players by its own?

- No, this doesn't ban players by its own.

Does this feature cancel actions that player do?

- No, this doesn't cancel actions.

Does this feature sends a reports information?
- Yes, this feature send a report when player Exceeds a abnormal distance when claiming the Bed

You will get a message in:
- Console
- Logs
- Discord Webhook (if its enabled)


Message example:

.. code-block:: console

	"Player: 7656.. Exceeded abnormal bed claim distance: {distance}"


If you get a similar message it doesn't means that you need to run and ban this player immediately, this is what we recommend to do and which actions to do:

1. Can be A False Positive: 

- It can be a false positive, maybe player or server has a ping increase for a while or something else.

2. Hire Moderation Team: 
   
- Would be great if you have a specific moderation team (at least 1-2 member(s)), who can handle these processes, explain to moderation the nuances, drop them a link to the documentation of the UnturnedGuard, and let them understand the basics.
  
3. Analyze: 
   
- You can analyze that this player is to active as being reported by the UnturnedGuard too many times, as you probably remember their SteamIds.
  
4. Keep A Contact with players: 
   
- Ask Players to understand that this is a cheater, perhaps you already get a lot of reports by the actual players, or you have a video that shows abnormal players behavior, they kill too many players, they're in top of the server (it also useful by having some statistics on the server).

Arguments to the feature:
- CancelAbnormalBehavior (true/false): Should it cancel a abnormal behavior (player actions) that UnturnedGuard detected?


RocketMod ``UnturnedGuard.RocketMod.configuration.xml``

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


OpenMod ``config.yaml``

.. code-block:: yaml

	Features:
      - Name: "AntiBedFarClaim"
        Enabled: true
    	Arguments:
          - Name: "CancelAbnormalBehavior"
            Value: false
    