put the ENTIRE "RoClothes" folder into the roblox content folder
DO NOT put all the assets of the folder into the roblox content folder



# update log v0.7.5:lerp()

- body types -
torso7 from request

- butt offset changes -
butt scale now offsets better for bigger sizes

- file detection -
10s wait time changed to 5s
now applies face & head meshes

- bug fixes -
breast clothing is ACTUALLY doublesided now (not invisible on inside view; last update didnt actually have it for some reason)







!!! OUTDATED !!!
REFER TO OTHER BUNDLES/PRESETS/CLOTHINGBUNDLES TO MAKE YOUR OWN

# How to create Bundles
go to line 7345 in the script and insert a table from there
every section is OPTIONAL and ARENT required for the bundle to function

["BUNDLE"] = {
	["Body Color"] = {
		["HeadColor3"] = Color3.fromRGB(0,0,0),
		["LeftArmColor3"] = Color3.fromRGB(0,0,0),
		["RightArmColor3"] = Color3.fromRGB(0,0,0),
		["LeftLegColor3"] = Color3.fromRGB(0,0,0),
		["RightLegColor3"] = Color3.fromRGB(0,0,0),
		["TorsoColor3"] = Color3.fromRGB(0,0,0),
	},
	["Clothes"] = { -- default roblox clothing, requires ONLY the ids
		["Shirt"] = nil,
		["Pants"] = nil
	},
	["Clothing"] = { -- preset clothes, make sure to include entire clothing name. CAPS SENSITIVE.
		"nil",
	},
	["Recolor"] = { -- preset recolors, make sure to include the clothes in ["Clothing"]. CAPS SENSITIVE.
		["nil"] = {
			["Primary"] = Color3.fromRGB(0,0,0)
			["Secondary"] = Color3.fromRGB(0,0,0)
			["Tertiary"] = Color3.fromRGB(0,0,0)
		}
	},
	["Accessory"] = { -- default roblox accessories, requires ONLY the ids
		nil,
	},
	["Override"] = false -- overrides catalog clothes with bundle clothes. good for using with Username
}
