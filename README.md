Addon for ImmersiveEngineering<br>
Lode Loader - it loads lodes!<br>
This modification provides you with a config file, that enables  any custom ore to be found and excavated by Immersive Engineering's  Core Sampler drill and Excavator. Below is an example config file and explanation of usage:
 <br><br>[<br>
  {<br>
    "unlocalized_name": "Anthracites",<br>
    "mineralChance": 80,<br>
    "failChance": 0.2,<br>
    "ores": [<br>
      "oreCoal",<br>
      "oreDiamond"<br>
    ],<br>
    "chances": [<br>
      0.99,<br>
      0.01<br>
    ],<br>
    "localized_names": {<br>
      "pl_PL": "Antracyty",<br>
      "en_US": "Anthracites"<br>
    }<br>
  },<br>
  {<br>
    "unlocalized_name": "Phosphates",<br>
    "mineralChance": 20,<br>
    "failChance": 0.2,<br>
    "ores": [<br>
      "oreApatite",<br>
      "oreSaltpeter"<br>
    ],<br>
    "chances": [<br>
      0.7,<br>
      0.3<br>
    ],<br>
    "localized_names": {<br>
      "pl_PL": "Fosforyty",<br>
      "en_US": "Phosphates"<br>
    }<br>
  }<br>
]<br>
"unlocalized_name"</b> - default name of the added lode ("desc.ImmersiveEngineering.info.this") should be written as one word, no spaces, as short as possible.
<br><b>"mineral_chance"</b> > 0, each ore lode you add here redistributes the chance to find a chunk with them proportionally
<br><b>"failChance"</b> >= 0, when digging, this is the probability of an empty "spoon" in the excavator
<br><b>"ores" and "chances"</b> - ore dictionary names of ores and the respective chance that the current excavation gives you that ore "chances" have to total 1
<br><b>"localized_names"</b> - provides translation strings for the added lodes
