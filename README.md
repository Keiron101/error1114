{  
  "General":{  
    "TimedPointsReward":{  
      "Enabled":true,
      "Interval":10,
      "Groups":{  
        "Default":{  
          "Amount":50
        },
        "Premiums":{  
          "Amount":100
        }
      }
    },
    "ItemsPerPage":15,
    "ShopDisplayTime":15.0,
    "ShopTextSize":1.3,
    "DbPathOverride":"",
    "DefaultKit":""
  },
  "Kits":{  
    "gear":{
      "DefaultAmount":2,
      "Price":500,
      "Description":"Starter kit (Armor and Tools)",
      "OnlyFromSpawn":false,
      "Items":[  
        {  
          "Amount":1,
          "Quality":7,
          "ForceBlueprint":false,
          "Blueprint":"Blueprint'/Game/PrimalEarth/CoreBlueprints/Weapons/PrimalItem_WeaponMetalPick.PrimalItem_WeaponMetalPick'"
        },
		{
	      "Amount":1,
		  "Quality":7,
		  "ForceBlueprint":false,
		  "Blueprint":"Blueprint'/Game/PrimalEarth/CoreBlueprints/Weapons/PrimalItem_WeaponMetalHatchet.PrimalItem_WeaponMetalHatchet'"
		},
		{
		  "Amount":1,
		  "Quality":7,
		  "ForceBlueprint":false,
		  "Blueprint":"Blueprint'/Game/PrimalEarth/CoreBlueprints/Items/Armor/Metal/PrimalItemArmor_MetalHelmet.PrimalItemArmor_MetalHelmet'"
		},
		{
		  "Amount":1,
		  "Quality":7,
		  "ForceBlueprint":false,
		  "Blueprint":"Blueprint'/Game/PrimalEarth/CoreBlueprints/Items/Armor/Metal/PrimalItemArmor_MetalShirt.PrimalItemArmor_MetalShirt'"
		},
		{
		  "Amount":1,
		  "Quality":7,
		  "ForceBlueprint":false,
		  "Blueprint":"Blueprint'/Game/PrimalEarth/CoreBlueprints/Items/Armor/Metal/PrimalItemArmor_MetalPants.PrimalItemArmor_MetalPants'"
		},
		{
		  "Amount":1,
		  "Quality":7,
		  "ForceBlueprint":false,
		  "Blueprint":"Blueprint'/Game/PrimalEarth/CoreBlueprints/Items/Armor/Metal/PrimalItemArmor_MetalGloves.PrimalItemArmor_MetalGloves'"
		},
		{
		  "Amount":1,
		  "Quality":7,
		  "ForceBlueprint":false,
		  "Blueprint":"Blueprint'/Game/PrimalEarth/CoreBlueprints/Items/Armor/Metal/PrimalItemArmor_MetalBoots.PrimalItemArmor_MetalBoots'"
		},
		{
		  "Amount":1,
		  "Quality":7,
		  "ForceBlueprint":false,
		  "Blueprint":"Blueprint'/Game/PrimalEarth/CoreBlueprints/Weapons/PrimalItem_WeaponSword.PrimalItem_WeaponSword'"
		},
		{
		  "Amount":1,
		  "Quality":7,
		  "ForceBlueprint":false,
		  "Blueprint":"Blueprint'/Game/PrimalEarth/CoreBlueprints/Weapons/PrimalItem_WeaponCrossbow.PrimalItem_WeaponCrossbow'"
		},
		{
		  "Amount":1,
		  "Quality":7,
		  "ForceBlueprint":false,
		  "Blueprint":"Blueprint'/Game/PrimalEarth/CoreBlueprints/Weapons/PrimalItem_WeaponMachinedSniper.PrimalItem_WeaponMachinedSniper'"
		},
		{
		  "Amount":1,
		  "Quality":1,
		  "ForceBlueprint":false,
		  "Blueprint":"Blueprint'/Game/PrimalEarth/CoreBlueprints/Items/WeaponAttachments/PrimalItemWeaponAttachment_Silencer.PrimalItemWeaponAttachment_Silencer'" 
		},
		{
		  "Amount":1,
		  "Quality":1,
		  "ForceBlueprint":false,
		  "Blueprint":"Blueprint'/Game/Aberration/CoreBlueprints/Items/Armor/PrimalItemArmor_Glider.PrimalItemArmor_Glider'"
		},
		{
		  "Amount":200,
		  "Quality":1,
		  "ForceBlueprint":false,
		  "Blueprint":"Blueprint'/Game/PrimalEarth/CoreBlueprints/Weapons/PrimalItemAmmo_AdvancedSniperBullet.PrimalItemAmmo_AdvancedSniperBullet'"
		},
		{
		  "Amount":100,
		  "Quality":1,
		  "ForceBlueprint":false,
		  "Blueprint":"Blueprint'/Game/PrimalEarth/CoreBlueprints/Weapons/PrimalItemAmmo_ArrowTranq.PrimalItemAmmo_ArrowTranq'"
		},
		{
		  "Amount":1,
		  "Quality":7,
		  "ForceBlueprint":false,
		  "Blueprint":"Blueprint'/Game/PrimalEarth/CoreBlueprints/Items/Armor/Saddles/PrimalItemArmor_PteroSaddle.PrimalItemArmor_PteroSaddle'"
		}
      ],
      "Dinos":[  
        {  
          "Level":100,
          "Blueprint":"Blueprint'/Game/PrimalEarth/Dinos/Ptero/Ptero_Character_BP.Ptero_Character_BP'"
        }
      ]
    },
    "vip":{  
      "DefaultAmount":1,
      "Description":"Vip kit for premiums (ptero)",
      "Permissions":"Admins,Premiums",
      "Dinos":[  
        {  
          "Level":20,
          "Neutered":true,
          "Blueprint":"Blueprint'/Game/PrimalEarth/Dinos/Ptero/Ptero_Character_BP.Ptero_Character_BP'"
        }
      ]
    },
    "base":{
      "DefaultAmount":1,
      "Price":750,
      "MinLevel":1,
      "MaxLevel":200,
      "Description":"Base Kit(Turrets, Foundations ETC",
      "Items":[  
        {  
          "Amount":15,
          "Quality":0,
          "ForceBlueprint":false,
          "Blueprint":"Blueprint'/Game/Mods/StructuresPlusMod/Misc/AutoTurretHeavy/PrimalItemStructure_AutoTurret_Heavy.PrimalItemStructure_AutoTurret_Heavy'"
        },
        {  
          "Amount":10,
          "Quality":0,
          "ForceBlueprint":false,
          "Blueprint":"Blueprint'/Game/Mods/StructuresPlusMod/Structures/Foundations/Square/Glass/PrimalItemStructure_Foundation_Glass.PrimalItemStructure_Foundation_Glass'"
        },
		{
		  "Amount":12,
		  "Quality":0,
		  "ForceBlueprint":false,
		  "Blueprint":"Blueprint'/Game/Mods/StructuresPlusMod/Structures/Walls_L/Glass/PrimalItemStructure_LargeWall_Glass.PrimalItemStructure_LargeWall_Glass'"
		},
		{
		  "Amount":1,
		  "Quality":0,
		  "ForceBlueprint":false,
		  "Blueprint":"Blueprint'/Game/Mods/StructuresPlusMod/Structures/Doorframes_Double/Glass/PrimalItemStructure_DoubleDoorframe_Glass.PrimalItemStructure_DoubleDoorframe_Glass'"
		},
		{
		  "Amount":1,
		  "Quality":0,
		  "ForceBlueprint":false,
		  "Blueprint":"Blueprint'/Game/Mods/StructuresPlusMod/Doors/Doors_Double/Glass/PrimalItemStructure_DoubleDoor_Glass.PrimalItemStructure_DoubleDoor_Glass'"
		},
		{
		  "Amount":10,
		  "Quality":0,
		  "ForceBlueprint":false,
		  "Blueprint":"Blueprint'/Game/Mods/StructuresPlusMod/Structures/Ceilings/Square/Glass/PrimalItemStructure_Ceiling_Glass.PrimalItemStructure_Ceiling_Glass'"
		},
		{
		  "Amount":10,
		  "Quality":0,
		  "ForceBlueprint":false,
		  "Blueprint":"Blueprint'/Game/Mods/StructuresPlusMod/Structures/HatchFrames_L/Metal/PrimalItemStructure_LargeHatchframe_Metal.PrimalItemStructure_LargeHatchframe_Metal'"
		},
		{
		  "Amount":1,
		  "Quality":0,
		  "ForceBlueprint":false,
		  "Blueprint":"Blueprint'/Game/Mods/BoostedFab/AutoChem/PrimalItemStructure_AutoChemBench.PrimalItemStructure_AutoChemBench"
		},
		{
		  "Amount":1,
		  "Quality":0,
		  "ForceBlueprint":false,
		  "Blueprint":"Blueprint'/Game/Mods/BoostedFab/AutoFab/PrimalItemStructure_Fabricator_Auto.PrimalItemStructure_Fabricator_Auto"
		},
		{
		  "Amount":1,
		  "Quality":0,
		  "ForceBlueprint":false,
		  "Blueprint":"Blueprint'/Game/Mods/BoostedFab/Fab/PrimalItemStructure_Fabricator_2.PrimalItemStructure_Fabricator_2"
		},
		{
		  "Amount":1,
		  "Quality":0,
		  "ForceBlueprint":false,
		  "Blueprint":"Blueprint'/Game/Mods/BoostedFab/Forge/PrimalItemStructure_IndustrialForge_2.PrimalItemStructure_IndustrialForge_2"
		},
		{
		  "Amount":1,
		  "Quality":0,
		  "ForceBlueprint":false,
		  "Blueprint":"Blueprint'/Game/Mods/BoostedFab/Smithy/PrimalItemStructure_Smithy.PrimalItemStructure_Smithy"
		},
		{
		  "Amount":1,
		  "Quality":0,
		  "ForceBlueprint":false,
		  "Blueprint":"Blueprint'/Game/Mods/StructuresPlusMod/Crafting/Station/PrimalItemStructure_SPlusCraftingStation.PrimalItemStructure_SPlusCraftingStation'"
		},
		{
		  "Amount":5000,
		  "Quality":0,
		  "ForceBlueprint":false,
		  "Blueprint":"Blueprint'/Game/PrimalEarth/CoreBlueprints/Weapons/PrimalItemAmmo_AdvancedRifleBullet.PrimalItemAmmo_AdvancedRifleBullet'"
		},
		{
		  "Amount":1000,
		  "Quality":0,
		  "ForceBlueprint":false,
		  "Blueprint":"Blueprint'/Game/PrimalEarth/CoreBlueprints/Resources/PrimalItemResource_Gasoline.PrimalItemResource_Gasoline'"
		},
		{
		  "Amount":1,
		  "Quality":0,
		  "ForceBlueprint":false,
		  "Blueprint":"Blueprint'/Game/Mods/ArkAuto/Structures/TekGenerator/PrimalItemStructure_TekGenerator_AA.PrimalItemStructure_TekGenerator_AA'"}
      ]
    }
  },
  "ShopItems":{  
    "shotgunbp":{
      "Type":"item",
      "Description":"Shotgun Blueprint",
      "Price":1500,
      "Items":[  
        {  
          "Quality":7,
          "ForceBlueprint":true,
          "Amount":1,
          "Blueprint":"Blueprint'/Game/PrimalEarth/CoreBlueprints/Weapons/PrimalItem_WeaponMachinedShotgun.PrimalItem_WeaponMachinedShotgun'"
        }
      ]
    },
    "tools":{  
      "Type":"item",
      "Description":"Tools (Metal Hatchet, Metal Pick)",
      "Price":500,
      "Items":[  
        {  
          "Quality":7,
          "ForceBlueprint":true,
          "Amount":1,
          "Blueprint":"Blueprint'/Game/PrimalEarth/CoreBlueprints/Weapons/PrimalItem_WeaponMetalHatchet.PrimalItem_WeaponMetalHatchet'"
        },
        {  
          "Quality":7,
          "ForceBlueprint":true,
          "Amount":1,
          "Blueprint":"Blueprint'/Game/PrimalEarth/CoreBlueprints/Weapons/PrimalItem_WeaponMetalPick.PrimalItem_WeaponMetalPick'"
        }
      ]
    },
	"sniperbp":{
	  "Type":"item",
	  "Description":"Fabricated Sniper Rifle Blueprint",
	  "Price":1500,
	  "Items":[
	    {
	      "Quality":7,
		  "ForceBlueprint":true,
		  "Amount":1,
		  "Blueprint":"Blueprint'/Game/PrimalEarth/CoreBlueprints/Weapons/PrimalItem_WeaponMachinedSniper.PrimalItem_WeaponMachinedSniper'"
		}
	  ]
	},
	"flakbp":{
	  "Type":"item",
	  "Description":"Suit Of Flak Blueprints",
	  "Price":2000,
	  "Items":[
	    {
	      "Quality":7,
		  "ForceBlueprint":true,
		  "Amount":1,
		  "Blueprint":"Blueprint'/Game/PrimalEarth/CoreBlueprints/Items/Armor/Metal/PrimalItemArmor_MetalHelmet.PrimalItemArmor_MetalHelmet'"
		},
		{
		  "Quality":7,
		  "ForceBlueprint":true,
		  "Amount":1,
		  "Blueprint":"Blueprint'/Game/PrimalEarth/CoreBlueprints/Items/Armor/Metal/PrimalItemArmor_MetalShirt.PrimalItemArmor_MetalShirt'"
		},
		{
		  "Quality":7,
		  "ForceBlueprint":true,
		  "Amount":1,
		  "Blueprint":"Blueprint'/Game/PrimalEarth/CoreBlueprints/Items/Armor/Metal/PrimalItemArmor_MetalPants.PrimalItemArmor_MetalPants'"
		},
		{
		  "Quality":7,
		  "ForceBlueprint":true,
		  "Amount":1,
		  "Blueprint":"Blueprint'/Game/PrimalEarth/CoreBlueprints/Items/Armor/Metal/PrimalItemArmor_MetalGloves.PrimalItemArmor_MetalGloves'"
		},
		{
		  "Quality":7,
		  "ForceBlueprint":true,
		  "Amount":1,
		  "Blueprint":"Blueprint'/Game/PrimalEarth/CoreBlueprints/Items/Armor/Metal/PrimalItemArmor_MetalBoots.PrimalItemArmor_MetalBoots'"
		}
	  ]
	},
	"riotshieldbp":{
	  "Type":"item",
	  "Description":"Riot Shield Blueprint",
	  "Price":1750,
	  "Items":[
	    {
	      "Quality":7,
		  "ForceBlueprint":true,
		  "Amount":1,
		  "Blueprint":"Blueprint'/Game/PrimalEarth/CoreBlueprints/Items/Armor/Shields/PrimalItemArmor_TransparentRiotShield.PrimalItemArmor_TransparentRiotShield'"
		}
	  ]
	},
    "whipbp":{
	  "Type":"item",
	  "Description":"Whip Blueprint",
	  "Price":1000,
	  "Items":[
	    {
	      "Quality":7,
		  "ForceBlueprint":true,
		  "Amount":1,
		  "Blueprint":"Blueprint'/Game/ScorchedEarth/WeaponWhip/PrimalItem_WeaponWhip.PrimalItem_WeaponWhip'"
		}
	  ]
	},
	"longneckbp":{
	  "Type":"item",
	  "Description":"Longneck Blueprint",
	  "Price":1000,
	  "Items":[
	    {
	      "Quality":7,
		  "ForceBlueprint":true,
		  "Amount":1,
		  "Blueprint":"Blueprint'/Game/PrimalEarth/CoreBlueprints/Weapons/PrimalItem_WeaponOneShotRifle.PrimalItem_WeaponOneShotRifle'"
		}
	  ]
	},
	"medbrew":{
	  "Type":"item",
	  "Description":"200 Medical Brews",
	  "Price":500,
	  "Items":[
	    {
		  "Quality":0,
		  "ForceBlueprint":false,
		  "Amount":200,
		  "Blueprint":"Blueprint'/Game/PrimalEarth/CoreBlueprints/Items/Consumables/PrimalItemConsumable_HealSoup.PrimalItemConsumable_HealSoup'"
		 		}
	  ]
	},
	"shadowsteak":{
	  "Type":"item",
	  "Description":"200 Shadow Steak",
	  "Price":500,
	  "Items":[
	    {
		  "Quality":0,
		  "ForceBlueprint":false,
		  "Amount":200,
		  "Blueprint":"Blueprint'/Game/PrimalEarth/CoreBlueprints/Items/Consumables/PrimalItemConsumable_Soup_ShadowSteak.PrimalItemConsumable_Soup_ShadowSteak'"
		  		}
	  ]
	},
    "paracer":{  
      "Type":"dino",
      "Description":"Racer (Paracerithium)",
      "Level":150,
      "Price":1500,
      "MinLevel":150,
      "MaxLevel":150,
      "Blueprint":"Blueprint'/Game/PrimalEarth/Dinos/Paraceratherium/Paracer_Character_BP_Aberrant.Paracer_Character_BP_Aberrant'"
    },
    "reaper":{  
      "Type":"dino",
      "Description":"Reaper",
      "Level":150,
      "Price":1250,
      "Neutered":false,
      "Blueprint":"Blueprint'/Game/Aberration/Dinos/Nameless/Xenomorph_Character_BP_Male.Xenomorph_Character_BP_Male'"
    },
    "griffin":{  
      "Type":"dino",
      "Description":"Griffin",
      "Level":150,
      "Price":1250,
      "Neutered":false,
      "Blueprint":"Blueprint'/Game/PrimalEarth/Dinos/Griffin/Griffin_Character_BP.Griffin_Character_BP'"
    },
    "stego":{  
      "Type":"dino",
      "Description":"Stego",
      "Level":150,
      "Price":1250,
      "Neutered":false,
      "Blueprint":"Blueprint'/Game/PrimalEarth/Dinos/Stego/Stego_Character_BP.Stego_Character_BP'"
    },
    "theri":{  
      "Type":"dino",
      "Description":"Theri",
      "Level":150,
      "Price":1250,
      "Neutered":false,
      "Blueprint":"Blueprint'/Game/PrimalEarth/Dinos/Therizinosaurus/Therizino_Character_BP.Therizino_Character_BP'"
    },
    "achatina":{  
      "Type":"dino",
      "Description":"Achatina",
      "Level":150,
      "Price":1250,
      "Neutered":false,
      "Blueprint":"Blueprint'/Game/PrimalEarth/Dinos/Achatina/Achatina_Character_BP.Achatina_Character_BP'" 
    },
    "anglerfish":{  
      "Type":"dino",
      "Description":"Angler Fish",
      "Level":150,
      "Price":1250,
      "Neutered":false,
      "Blueprint":"Blueprint'/Game/PrimalEarth/Dinos/Anglerfish/Angler_Character_BP.Angler_Character_BP'"
    },
    "rockgolem":{  
      "Type":"dino",
      "Description":"Rock Elemental",
      "Level":150,
      "Price":1500,
      "Neutered":false,
      "Blueprint":"Blueprint'/Game/ScorchedEarth/Dinos/RockGolem/RockGolem_Character_BP.RockGolem_Character_BP'"
    },
    "moschops":{  
      "Type":"dino",
      "Description":"Moschops",
      "Level":150,
      "Price":850,
      "Neutered":false,
      "Blueprint":"Blueprint'/Game/PrimalEarth/Dinos/Moschops/Moschops_Character_BP.Moschops_Character_BP'" 
    },
    "mantis":{  
      "Type":"dino",
      "Description":"Mantis (Farming Dino)",
      "Level":150,
      "Price":850,
      "Neutered":false,
      "Blueprint":"Blueprint'/Game/ScorchedEarth/Dinos/Mantis/Mantis_Character_BP.Mantis_Character_BP'"
  },
  "SellItems":{  
    "metal":{  
      "Type":"item",
      "Description":"100x metal",
      "Price":10,
      "Amount":100,
      "Blueprint":"Blueprint'/Game/Mods/Stack50/Resources/PrimalItemResource_Stone_Child.PrimalItemResource_Stone_Child'"
    }
  },
  "Messages":{  
    "Sender":"ArkShop",
    "BoughtItem":"<RichColor Color=\"0, 1, 0, 1\">You have successfully bought item</>",
    "BoughtDino":"<RichColor Color=\"0, 1, 0, 1\">You have successfully bought dino</>",
    "BoughtBeacon":"<RichColor Color=\"0, 1, 0, 1\">You have successfully bought beacon</>",
    "BoughtExp":"<RichColor Color=\"0, 1, 0, 1\">You have successfully bought experience</>",
    "ReceivedPoints":"<RichColor Color=\"1, 1, 0, 1\">You have received {0} points! (total: {1})</>",
    "HavePoints":"You have {0} points",
    "NoPoints":"<RichColor Color=\"1, 0, 0, 1\">You don't have enough points</>",
    "WrongId":"<RichColor Color=\"1, 0, 0, 1\">Wrong id</>",
    "NoPermissionsKit":"<RichColor Color=\"1, 0, 0, 1\">You don't have permission to use this kit</>",
    "CantBuyKit":"<RichColor Color=\"1, 0, 0, 1\">You can't buy this kit</>",
    "BoughtKit":"<RichColor Color=\"0, 1, 0, 1\">You have successfully bought {0} kit</>",
    "AvailableKits":"Available kits for you:",
    "NoKits":"No available kits",
    "KitsLeft":"You have {0} {1} kits left",
    "NoKitsLeft":"You don't have {0} kits left",
    "CantGivePoints":"<RichColor Color=\"1, 0, 0, 1\">You can't give points to yourself</>",
    "RidingDino":"<RichColor Color=\"1, 0, 0, 1\">You can't buy this item while riding a dino</>",
    "SentPoints":"<RichColor Color=\"0, 1, 0, 1\">You have successfully sent {0} points to {1}</>",
    "GotPoints":"You have received {0} points from {1}",
    "NoPlayer":"<RichColor Color=\"1, 0, 0, 1\">Player doesn't exist</>",
    "FoundMorePlayers":"<RichColor Color=\"1, 0, 0, 1\">Found more than one player with the given name</>",
    "BuyUsage":"Usage: /buy id amount",
    "ShopUsage":"Usage: /shop page",
    "KitUsage":"Usage: /kit KitName",
    "BuyKitUsage":"Usage: /BuyKit KitName amount",
    "TradeUsage":"Usage: /trade 'Player Name' amount",
    "PointsCmd":"/points",
    "TradeCmd":"/trade",
    "BuyCmd":"/buy",
    "ShopCmd":"/shop",
    "KitCmd":"/kit",
    "BuyKitCmd":"/buykit",
    "SellCmd":"/sell",
    "ShopSellCmd":"/shopsell",
    "SellUsage":"Usage: /sell id amount",
    "NotEnoughItems":"<RichColor Color=\"1, 0, 0, 1\">You don't have enough items ({0}/{1})</>",
    "SoldItems":"<RichColor Color=\"0, 1, 0, 1\">You have successfully sold items</>",
    "BadLevel":"<RichColor Color=\"1, 0, 0, 1\">Required level: {0} - {1}</>",
    "KitsListPrice":"Price: {0}",
    "KitsListFormat":"\"{0}\" - {1}. {2} left. {3}\n",
    "StoreListDino":"{0}) {1}. Level: {2}. Id: {3}. Price: {4}\n",
    "StoreListItem":"{0}) {1}. Id: {2}. Price: {3}\n",
    "StoreListFormat":"{0}",
    "OnlyOnSpawnKit":"This kit can be used only on spawn",
    "HelpCmd":"/shophelp",
    "ShopMessage":"Usage: /buy id amount",
	"HelpMessage":"This is shop help message"}
  }
}
