# Accessory

URL: https://create.roblox.com/docs/reference/engine/classes/Accessory

*    Recent releases  

1.   Classes

5.   Accoutrement

7.   Accessory

Engine Class

Accessory

An item that a Character can wear.

* * *

Summary

Properties

AccessoryType:Enum.AccessoryType

Inherited Members

5 inherited from Accoutrement

57 inherited from Instance

6 inherited from Object

The Accessory Instance is the parent Instance of all accessories (regardless of their specific accessory type). It typically has a child Handle with a child Attachment and a WrapLayer in the case of Layered Clothing.

The Accessory class is the successor to the legacy Hat system. It's cross-compatible with both the legacy R6 character system and the new R15 character system.

If you insert an Attachment into the Accessory's Handle with the same name as an Attachment in one of the character's limbs, they connect and ignore properties inherited from the Accoutrement class. Otherwise, the Accessory functions identically to a Hat.

Note: If there are two matching Attachments, the resulting Weld is a child of the Accessory's Handle. This differs from the legacy behavior of Hats where the Weld is always a child of the Head of the character.

* * *

API Reference

Properties

AccessoryType

Read Parallel

Specifies the AccessoryType of the Accessory (eg. Hat, Tshirt, Waist).

Accessory.AccessoryType:Enum.AccessoryType

Specifies the AccessoryType of the Accessory. Is AccessoryType.Unknown unless you equip the Accessory through the player spawning process or Humanoid:ApplyDescriptionAsync(). If available on the Marketplace, you can set Enum.AccessoryType to categorize the Accessory item (for example, "Hat" or "Face").

* * *

Accessory

Summary

Properties

Properties

AccessoryType

[](https://x.com/Roblox)[](https://www.facebook.com/Roblox/)[](https://www.linkedin.com/company/roblox)[](https://www.instagram.com/roblox/)[](https://www.youtube.com/@RobloxLearn)