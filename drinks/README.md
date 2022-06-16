## Drinks
Add These To Your qb-core/Shared/Items.Lua

## Credit to Contributors
 - LemonzPCMR
 - MrFuRoX @ [Project Boosted](https://github.com/Project-Boosted)
 - [IDRP](https://github.com/idrp/qb-uwu)

 - ***ItzThatGUY***#2082 [NatasWillDoIt](https://github.com/NatasWillDoIt)

----------  Drinks  ----------  Drinks  ----------  Drinks  ----------  Drinks  ----------
```lua
-- UWU CATCAFE
    ["uwububbleteablueberry"] = {["name"] = "uwububbleteablueberry", ["label"] = "Berry Blue B-T", ["weight"] = 200, ["type"] = "item", ["image"] = "uwububbleteablueberry.png", ["unique"] = false, ["useable"] = true, ["shouldClose"] = true, ["combinable"] = nil, ["description"] = "Lavender Tea with Blueberry Boba."}, 
    ["uwububbletearose"] = {["name"] = "uwububbletearose", ["label"] = "Rosey B-T", ["weight"] = 200, ["type"] = "item", ["image"] = "uwububbletearose.png", ["unique"] = false, ["useable"] = true, ["shouldClose"] = true, ["combinable"] = nil, ["description"] = "Sakura Rose Tea with Vanilla Boba."}, 
    ["uwububbleteamint"] = {["name"] = "uwububbleteamint", ["label"] = "Minty B-T", ["weight"] = 200, ["type"] = "item", ["image"] = "uwububbleteamint.png", ["unique"] = false, ["useable"] = true, ["shouldClose"] = true, ["combinable"] = nil, ["description"] = "Matcha Tea with Mint Boba."}, 
    ['uwumatchatea'] = {    ['name'] = "uwumatchatea",    ['label'] = "uwumatchatea",    ['weight'] = 100,    ['decay'] = "0.4",['type'] = "item",    ['image'] = "uwumatchatea.png",    ['created'] = "nil",    ['unique'] = false,    ['usable'] = false,    ['shouldClose'] = false,    ['description'] = "Matcha Tea",    ['combinable'] = nil  },
    ['uwumisosoup'] = {    ['name'] = "uwumisosoup",    ['label'] = "uwumisosoup",    ['weight'] = 100,    ['decay'] = "0.4",['type'] = "item",    ['image'] = "uwumisosoup.png",    ['created'] = "nil",    ['unique'] = false,    ['usable'] = false,    ['shouldClose'] = false,    ['description'] = "Matcha Soup",    ['combinable'] = nil  },

---  Soft Drinks  
  ["burger-milkshake"] = {    ['name'] = "burger-milkshake",    ['label'] = "burgershot Milkshake",    ['weight'] = 100,    ['decay'] = "0.4",['type'] = "item",    ['image'] = "burger-milkshake.png",    ['created'] = "nil",    ['unique'] = false,    ['usable'] = false,    ['shouldClose'] = false,    ['description'] = "yummy milkshake",    ['combinable'] = nil  },
  ['ccookie'] = {    ['name'] = "ccookie",    ['label'] = "C Cookie",    ['weight'] = 100,    ['decay'] = "0.4",['type'] = "item",    ['image'] = "ccookie.png",    ['created'] = "nil",    ['unique'] = false,    ['usable'] = false,    ['shouldClose'] = false,    ['description'] = "yummy",    ['combinable'] = nil  },
  ['cranberry'] = {    ['name'] = "cranberry",    ['label'] = "Cranberry Juice",    ['weight'] = 100,    ['decay'] = "0.4",['type'] = "item",    ['image'] = "cranberry.png",    ['created'] = "nil",    ['unique'] = false,    ['usable'] = false,    ['shouldClose'] = false,    ['description'] = "yummy",    ['combinable'] = nil  },
  ['water'] = {    ['name'] = "water",    ['label'] = "water",    ['weight'] = 100,    ['decay'] = "0.4",['type'] = "item",    ['image'] = "water.png",    ['created'] = "nil",    ['unique'] = false,    ['usable'] = false,    ['shouldClose'] = true,    ['description'] = "yummy",    ['combinable'] = nil  },
  ['water_bottle'] = {    ['name'] = "water_bottle",    ['label'] = "water_bottle",    ['weight'] = 100,    ['decay'] = "0.4",['type'] = "item",    ['image'] = "water_bottle.png",    ['created'] = "nil",    ['unique'] = false,    ['usable'] = false,    ['shouldClose'] = false,    ['description'] = "yummy",    ['combinable'] = nil  },
  ['watercup'] = {    ['name'] = "watercup",    ['label'] = "watercup",    ['weight'] = 100,    ['decay'] = "0.2",['type'] = "item",    ['image'] = "watercup.png",    ['created'] = "nil",    ['unique'] = false,    ['usable'] = false,    ['shouldClose'] = false,    ['description'] = "yummy",    ['combinable'] = nil  },

---Alcoholic
  ['amaretto'] = {    ['name'] = "amaretto",    ['label'] = "Amaretto",    ['weight'] = 100,    ['decay'] = "0.4",['type'] = "item",    ['image'] = "amaretto.png",    ['created'] = "nil",    ['unique'] = false,    ['usable'] = false,    ['shouldClose'] = false,    ['description'] = "yummy stiff drink",    ['combinable'] = nil  },
  ['amarone'] = {    ['name'] = "amarone",    ['label'] = "Amarone",    ['weight'] = 100,    ['decay'] = "0.4",['type'] = "item",    ['image'] = "amarone.png",    ['created'] = "nil",    ['unique'] = false,    ['usable'] = false,    ['shouldClose'] = false,    ['description'] = "yummy stiff drink",    ['combinable'] = nil  },
  ['ambeer'] = {    ['name'] = "ambeer",    ['label'] = "Ambeer",    ['weight'] = 100,    ['decay'] = "0.4",['type'] = "item",    ['image'] = "ambeer.png",    ['created'] = "nil",    ['unique'] = false,    ['usable'] = false,    ['shouldClose'] = false,    ['description'] = "yummy stiff drink",    ['combinable'] = nil  },
  ['b52'] = {    ['name'] = "b52",    ['label'] = "b52",    ['weight'] = 100,    ['decay'] = "0.4",['type'] = "item",    ['image'] = "b52.png",    ['created'] = "nil",    ['unique'] = false,    ['usable'] = false,    ['shouldClose'] = false,    ['description'] = "yummy stiff drink",    ['combinable'] = nil  },
  ['barbera'] = {    ['name'] = "barbera",    ['label'] = "barbera",    ['weight'] = 100,    ['decay'] = "0.4",['type'] = "item",    ['image'] = "barbera.png",    ['created'] = "nil",    ['unique'] = false,    ['usable'] = false,    ['shouldClose'] = false,    ['description'] = "yummy stiff drink",    ['combinable'] = nil  },
  ['beer'] = {    ['name'] = "beer",    ['label'] = "beer",    ['weight'] = 100,    ['decay'] = "0.4",['type'] = "item",    ['image'] = "beer.png",    ['created'] = "nil",    ['unique'] = false,    ['usable'] = false,    ['shouldClose'] = false,    ['description'] = "yummy stiff drink",    ['combinable'] = nil  },
  ['beer'] = {    ['name'] = "beer",    ['label'] = "beer",    ['weight'] = 100,    ['decay'] = "0.4",['type'] = "item",    ['image'] = "beer.png",    ['created'] = "nil",    ['unique'] = false,    ['usable'] = false,    ['shouldClose'] = false,    ['description'] = "yummy stiff drink",    ['combinable'] = nil  },
  ['bkamikaze'] = {    ['name'] = "bkamikaze",    ['label'] = "B Kamikaze",    ['weight'] = 100,    ['decay'] = "0.4",['type'] = "item",    ['image'] = "bkamikaze.png",    ['created'] = "nil",    ['unique'] = false,    ['usable'] = false,    ['shouldClose'] = false,    ['description'] = "yummy stiff drink",    ['combinable'] = nil  },
  ['blarneys'] = {    ['name'] = "blarneys",    ['label'] = "blarneys",    ['weight'] = 100,    ['decay'] = "0.4",['type'] = "item",    ['image'] = "blarneys.png",    ['created'] = "nil",    ['unique'] = false,    ['usable'] = false,    ['shouldClose'] = false,    ['description'] = "yummy stiff drink",    ['combinable'] = nil  },
  ['Blue_and_White_stripes_bottle'] = {    ['name'] = "Blue_and_White_stripes_bottle",    ['label'] = "Blue and White stripes bottle",    ['weight'] = 100,    ['decay'] = "0.4",['type'] = "item",    ['image'] = "Blue_and_White_stripes_bottle.png",    ['created'] = "nil",    ['unique'] = false,    ['usable'] = false,    ['shouldClose'] = false,    ['description'] = "yummy stiff drink",    ['combinable'] = nil  },
  ['brussian'] = {    ['name'] = "brussian",    ['label'] = "brussian",    ['weight'] = 100,    ['decay'] = "0.4",['type'] = "item",    ['image'] = "brussian.png",    ['created'] = "nil",    ['unique'] = false,    ['usable'] = false,    ['shouldClose'] = false,    ['description'] = "yummy stiff drink",    ['combinable'] = nil  },
  ['cappucc'] = {    ['name'] = "cappucc",    ['label'] = "Cappucc",    ['weight'] = 100,    ['decay'] = "0.4",['type'] = "item",    ['image'] = "cappucc.png",    ['created'] = "nil",    ['unique'] = false,    ['usable'] = false,    ['shouldClose'] = false,    ['description'] = "yummy stiff drink",    ['combinable'] = nil  },






```