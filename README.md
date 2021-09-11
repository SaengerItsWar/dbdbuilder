# dbdbuilder

This is the Source-Code of the DBDBuilder.net

# Example Survival Item
```javascript
function selectItemName() {
    var sItem = survItems("Item Name", ["item text", "item text"], "Item Rarity", "item text", "Item Icon", "Item Description", ["extra", "extra"], 1, "item type");
    sItem.isRedacted = false;
    return sItem;
}

//ADD
survivorItems.push(selectItemName());
```

# Example Survivor
```javascript
function selectSurvivorName() {
	var survivor  = new selectSurvivor();
	survivor.name = "Leon S. Kennedy";
	survivor.portrait = "Survivor Icon";
	return survivor;
}

//ADD
survivors.push(selectSurvivorName());
```

# Example Killer
```javascript
function selectNemesis() {
    var killer = selectKiller();
    killer.name = "In Game Killer Name";
    killer.itemOrAbility = selectAddOn("Killer Full Name", ["Killer Power Name"], "Common", "Killer Power Name", "first Power Icon", "killer", ["extra"]);
    killer.addonLink = nemesisAddons;
    killer.portrait = "Killer Icon";
    return killer;
}
//ADD
killers.push(selectKillerName());
```
# Example Offering or Favor
Killer and Survivor
```javascript
function offeringName() {
    var offering = selectOffering("Offering Name", "Offering Description", "offering Rarity", "Offerring Text", "Offering Icon",  "All");
    return offering;
}

//ADD x 2
killerOfferings.push(offeringName());
survivorOfferings.push(offeringName());
```
Survivor
```javascript
function offeringName() {
    var offering = selectOffering("Offering Name", "Offering Description", "offering Rarity", "Offerring Text", "Offering Icon", "Survivor");
    return offering;
}

//ADD x 2
survivorOfferings.push(offeringName());
```
Killer
```javascript
function offeringName() {
    var offering = selectOffering("Offering Name", "Offering Description", "offering Rarity", "Offerring Text", "Offering Icon", "Killer");
    return offering;
}

//ADD x 2
killerOfferings.push(offeringName());
```

# Example Killer Addon
```javascript
function addonName() {
    var addon = selectAddOn("Addon Name", ["Addon Description"], "Addon Rarity", "Addon Description ", "Addon Icon", "Killer Name", ["extra"]);
    return addon;
}

//ADD
killerNameAddons.push(addonName());
```

Real Killer Example

```javascript
function serratedJaws() {
    var addon = selectAddOn("Serrated Jaws", ["Traps infict heavy bleeding until the effects are healed."], "Uncommon", "Traps infict heavy bleeding until the effects are healed.", "IconAddon_serratedJaws.png", "Trapper", ["extra"]);
    return addon;
}

//ADD
trapperAddons.push(serratedJaws());
```

# Example Addons
medikit
```javascript
function addonName() {
    var addon = selectAddOn("Addon Name", ["Addon Description"], "Addon Rarity", "addon Description", "Addon Icon", "First Aid Kit", ["extra"]);
    return addon;
}

//ADD
medkitAddons.push(addonName());
```

Toolbox
```javascript
function addonnName() {
    var addon = selectAddOn("Addon Name", ["Addon Description"], "Addon Rarity", "Addon Description", "Addon Icon", "Toolbox", ["extra"]);
    return addon;
}

//ADD
toolboxAddons.push(addonName());
```

Flashlight
```javascript
function addonName() {
    var addon = selectAddOn("Addon Name", ["Addon Description"], "Addon Rarity", "Addon Description", "Addon Icon", "Flashlight", ["extra"]);
    return addon;
}

//ADD
flashlightAddons.push(addonName());
```

Key
```javascript
function addonName() {
    var addon = selectAddOn("Addon Name", ["Addon Description"], "Addon Rarity", "Addon Description", "Addon Icon", "Key", ["extra"]);
    return addon;
}

//ADD
keyAddons.push(addonName());
```

Map
```javascript
function addonName() {
    var addon = selectAddOn("Addon Name", ["Addon Description"], "Addon Rarity", "Addon Description", "Addon Icon", "Map", ["extra"]);
    return addon;
}

//ADD
mapAddons.push(addonName());
```
