# Mail - WoW 1.12 addOn

An extension to the Blizzard mail interface which
- **Automatically opens mail, very rapidly**
- **Mails multiple items at once, very rapidly**
- **Autocompletes recipient names**

**\<Right Click>** on inbox items to loot the gold, loot the item and destroy the letter, in that order, if any.<br/>
**\<Right Click>** or **\<Left Drag>** to add inventory items to the attachments.<br/>
**\<Right Click>** to add inventory items to the trade frame.

Note that due to limitations of the 1.12 API, behind the scenes, the items must be sent in separate mails.<br/>
CoD can still be applied to multiple items, but all items will have the same price, so this is most useful when selling multiple of the same item.<br>
Sending money along with multiple items will only attach money to the **first mail** to avoid draining all your gold by mistake.<br>

Also note that CoD is always ignored when opening, both automatically as well as by **\<Right Click>**.

![Alt text](http://i.imgur.com/H0MUmXd.png)

![Alt text](http://i.imgur.com/ZDyfMIK.png)

## Fork changes

* Can now do mass CoD mails
* Added page numbers to inbox from EinBaum: https://github.com/shirsig/Mail/commit/1f003118f0caa00f0fc0ffbef92fcb95c447a832
