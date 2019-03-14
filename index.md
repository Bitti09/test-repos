---
title: WarframeStat.us API
language_tabs:
  - '[{ http': ' HTTP }]'
toc_footers:
  - '<a href="https://warframe.com">Find out more about Warframe</a>'
includes: []
search: true
highlight_theme: darkula
headingLevel: 2

---

<h1 id="warframestat-us-api">WarframeStat.us API v1.0.0</h1>

> Scroll down for code samples, example requests and responses. Select a language for code samples from the tabs above or the mobile navigation menu.

Simple API for data from the game Warframe.

Base URLs:

* <a href="https://api.warframestat.us/">https://api.warframestat.us/</a>

* <a href="http://api.warframestat.us/">http://api.warframestat.us/</a>

Email: <a href="mailto:wf-com-dev@warframestat.us">Support</a> 
License: <a href="http://www.apache.org/licenses/LICENSE-2.0.html">Apache 2.0</a>

<h1 id="warframestat-us-api-worldstate">worldstate</h1>

Warframe Worldstate Data

<a href="https://discord.gg/jGZxH9f">Find out more</a>

## get__pc

> Code samples

`GET /pc`

*Get Warframe Worldstate Data for PC*

The full translated Warframe Worldstate

> Example responses

> 200 Response

```json
{
  "timestamp": "string",
  "news": [
    {
      "date": "string",
      "imageLink": "string",
      "eta": "string",
      "primeAccess": true,
      "stream": true,
      "translations": {
        "es": "string"
      },
      "link": "string",
      "update": true,
      "id": "string",
      "asString": "string",
      "message": "string",
      "priority": true
    }
  ],
  "events": [
    {}
  ],
  "alerts": [
    {
      "mission": {
        "reward": {
          "countedItems": [
            {
              "count": 0,
              "type": "string"
            }
          ],
          "thumbnail": "string",
          "color": 0,
          "credits": 0,
          "asString": "string",
          "items": [
            {}
          ],
          "itemString": "string"
        },
        "node": "string",
        "faction": "string",
        "maxEnemyLevel": 0,
        "minEnemyLevel": 0,
        "maxWaveNum": 0,
        "type": "string",
        "nightmare": true,
        "archwingRequired": true
      },
      "expired": true,
      "eta": "string",
      "id": "string",
      "expiry": "string",
      "activation": "string",
      "rewardTypes": [
        {}
      ]
    }
  ],
  "sortie": {
    "id": "string",
    "activation": "string",
    "expiry": "string",
    "rewardPool": "string",
    "variants": [
      {
        "node": "string",
        "boss": "string",
        "missionType": "string",
        "planet": "string",
        "modifier": "string",
        "modifierDescription": "string"
      }
    ],
    "boss": "string",
    "faction": "string",
    "expired": true,
    "eta": "string"
  },
  "syndicateMissions": [
    {
      "nodes": [
        {}
      ],
      "eta": "string",
      "jobs": [
        {}
      ],
      "syndicate": "string",
      "id": "string",
      "expiry": "string",
      "activation": "string"
    }
  ],
  "fissures": [
    {
      "node": "string",
      "expired": true,
      "eta": "string",
      "missionType": "string",
      "tier": "string",
      "tierNum": 0,
      "enemy": "string",
      "id": "string",
      "expiry": "string",
      "activation": "string"
    }
  ],
  "globalUpgrades": [
    {}
  ],
  "flashSales": [
    {
      "item": "string",
      "expired": true,
      "eta": "string",
      "discount": 0,
      "premiumOverride": 0,
      "isPopular": true,
      "expiry": "string",
      "id": "string",
      "isFeatured": true
    }
  ],
  "invasions": [
    {
      "defenderReward": {
        "countedItems": [
          {
            "count": 0,
            "type": "string"
          }
        ],
        "thumbnail": "string",
        "color": 0,
        "credits": 0,
        "asString": "string",
        "items": [
          {}
        ],
        "itemString": "string"
      },
      "attackingFaction": "string",
      "completion": 0,
      "attackerReward": {
        "countedItems": [
          {
            "count": 0,
            "type": "string"
          }
        ],
        "thumbnail": "string",
        "color": 0,
        "credits": 0,
        "asString": "string",
        "items": [
          {}
        ],
        "itemString": "string"
      },
      "count": 0,
      "completed": true,
      "requiredRuns": 0,
      "vsInfestation": true,
      "node": "string",
      "eta": "string",
      "defendingFaction": "string",
      "id": "string",
      "activation": "string",
      "rewardTypes": [
        {}
      ],
      "desc": "string"
    }
  ],
  "darkSectors": [
    {
      "defenderMOTD": "string",
      "deployerName": "string",
      "defenderDeployemntActivation": 0,
      "defenderName": "string",
      "deployerClan": "string",
      "isAlliance": true,
      "id": "string",
      "history": [
        {}
      ]
    }
  ],
  "voidTrader": {
    "id": "string",
    "activation": "string",
    "expiry": "string",
    "character": "string",
    "location": "string",
    "inventory": [
      {}
    ],
    "psId": "string",
    "active": true,
    "startString": "string",
    "endString": "string"
  },
  "dailyDeals": [
    {
      "sold": 0,
      "item": "string",
      "total": 0,
      "eta": "string",
      "originalPrice": 0,
      "salePrice": 0,
      "discount": 0,
      "expiry": "string",
      "id": "string"
    }
  ],
  "simaris": {
    "target": "string",
    "isTargetActive": true,
    "asString": "string"
  },
  "conclaveChallenges": [
    {
      "mode": "string",
      "amount": 0,
      "eta": "string",
      "expired": true,
      "endString": "string",
      "daily": true,
      "description": "string",
      "id": "string",
      "expiry": "string",
      "asString": "string",
      "category": "string",
      "rootChallenge": true
    }
  ],
  "persistentEnemies": [
    {}
  ],
  "earthCycle": {
    "id": 0,
    "expiry": "string",
    "isDay": true,
    "timeLeft": "string"
  },
  "cetusCycle": {
    "id": "string",
    "expiry": "string",
    "isDay": true,
    "timeLeft": "string",
    "isCetus": true
  },
  "constructionProgress": {
    "id": "string",
    "fomorianProgress": "string",
    "razorbackProgress": "string",
    "unknownProgress": "string"
  },
  "nightwave": {
    "id": "string",
    "activation": "string",
    "expiry": "string",
    "params": {},
    "rewardTypes": [
      "string"
    ],
    "season": 0,
    "tag": "string",
    "phase": 0,
    "possibleChallenges": [
      {
        "id": "string",
        "activation": "string",
        "expiry": "string",
        "isDaily": true,
        "isElite": true,
        "title": "string",
        "desc": "string",
        "reputation": 0
      }
    ],
    "activeChallenges": [
      {
        "id": "string",
        "activation": "string",
        "expiry": "string",
        "isDaily": true,
        "isElite": true,
        "title": "string",
        "desc": "string",
        "reputation": 0
      }
    ]
  }
}
```

<h3 id="get__pc-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[ws](#schemaws)|

<aside class="success">
This operation does not require authentication
</aside>

## get__ps4

> Code samples

`GET /ps4`

*Get Warframe Worldstate Data for PS4*

The full translated Warframe Worldstate

> Example responses

> 200 Response

```json
{
  "timestamp": "string",
  "news": [
    {
      "date": "string",
      "imageLink": "string",
      "eta": "string",
      "primeAccess": true,
      "stream": true,
      "translations": {
        "es": "string"
      },
      "link": "string",
      "update": true,
      "id": "string",
      "asString": "string",
      "message": "string",
      "priority": true
    }
  ],
  "events": [
    {}
  ],
  "alerts": [
    {
      "mission": {
        "reward": {
          "countedItems": [
            {
              "count": 0,
              "type": "string"
            }
          ],
          "thumbnail": "string",
          "color": 0,
          "credits": 0,
          "asString": "string",
          "items": [
            {}
          ],
          "itemString": "string"
        },
        "node": "string",
        "faction": "string",
        "maxEnemyLevel": 0,
        "minEnemyLevel": 0,
        "maxWaveNum": 0,
        "type": "string",
        "nightmare": true,
        "archwingRequired": true
      },
      "expired": true,
      "eta": "string",
      "id": "string",
      "expiry": "string",
      "activation": "string",
      "rewardTypes": [
        {}
      ]
    }
  ],
  "sortie": {
    "id": "string",
    "activation": "string",
    "expiry": "string",
    "rewardPool": "string",
    "variants": [
      {
        "node": "string",
        "boss": "string",
        "missionType": "string",
        "planet": "string",
        "modifier": "string",
        "modifierDescription": "string"
      }
    ],
    "boss": "string",
    "faction": "string",
    "expired": true,
    "eta": "string"
  },
  "syndicateMissions": [
    {
      "nodes": [
        {}
      ],
      "eta": "string",
      "jobs": [
        {}
      ],
      "syndicate": "string",
      "id": "string",
      "expiry": "string",
      "activation": "string"
    }
  ],
  "fissures": [
    {
      "node": "string",
      "expired": true,
      "eta": "string",
      "missionType": "string",
      "tier": "string",
      "tierNum": 0,
      "enemy": "string",
      "id": "string",
      "expiry": "string",
      "activation": "string"
    }
  ],
  "globalUpgrades": [
    {}
  ],
  "flashSales": [
    {
      "item": "string",
      "expired": true,
      "eta": "string",
      "discount": 0,
      "premiumOverride": 0,
      "isPopular": true,
      "expiry": "string",
      "id": "string",
      "isFeatured": true
    }
  ],
  "invasions": [
    {
      "defenderReward": {
        "countedItems": [
          {
            "count": 0,
            "type": "string"
          }
        ],
        "thumbnail": "string",
        "color": 0,
        "credits": 0,
        "asString": "string",
        "items": [
          {}
        ],
        "itemString": "string"
      },
      "attackingFaction": "string",
      "completion": 0,
      "attackerReward": {
        "countedItems": [
          {
            "count": 0,
            "type": "string"
          }
        ],
        "thumbnail": "string",
        "color": 0,
        "credits": 0,
        "asString": "string",
        "items": [
          {}
        ],
        "itemString": "string"
      },
      "count": 0,
      "completed": true,
      "requiredRuns": 0,
      "vsInfestation": true,
      "node": "string",
      "eta": "string",
      "defendingFaction": "string",
      "id": "string",
      "activation": "string",
      "rewardTypes": [
        {}
      ],
      "desc": "string"
    }
  ],
  "darkSectors": [
    {
      "defenderMOTD": "string",
      "deployerName": "string",
      "defenderDeployemntActivation": 0,
      "defenderName": "string",
      "deployerClan": "string",
      "isAlliance": true,
      "id": "string",
      "history": [
        {}
      ]
    }
  ],
  "voidTrader": {
    "id": "string",
    "activation": "string",
    "expiry": "string",
    "character": "string",
    "location": "string",
    "inventory": [
      {}
    ],
    "psId": "string",
    "active": true,
    "startString": "string",
    "endString": "string"
  },
  "dailyDeals": [
    {
      "sold": 0,
      "item": "string",
      "total": 0,
      "eta": "string",
      "originalPrice": 0,
      "salePrice": 0,
      "discount": 0,
      "expiry": "string",
      "id": "string"
    }
  ],
  "simaris": {
    "target": "string",
    "isTargetActive": true,
    "asString": "string"
  },
  "conclaveChallenges": [
    {
      "mode": "string",
      "amount": 0,
      "eta": "string",
      "expired": true,
      "endString": "string",
      "daily": true,
      "description": "string",
      "id": "string",
      "expiry": "string",
      "asString": "string",
      "category": "string",
      "rootChallenge": true
    }
  ],
  "persistentEnemies": [
    {}
  ],
  "earthCycle": {
    "id": 0,
    "expiry": "string",
    "isDay": true,
    "timeLeft": "string"
  },
  "cetusCycle": {
    "id": "string",
    "expiry": "string",
    "isDay": true,
    "timeLeft": "string",
    "isCetus": true
  },
  "constructionProgress": {
    "id": "string",
    "fomorianProgress": "string",
    "razorbackProgress": "string",
    "unknownProgress": "string"
  },
  "nightwave": {
    "id": "string",
    "activation": "string",
    "expiry": "string",
    "params": {},
    "rewardTypes": [
      "string"
    ],
    "season": 0,
    "tag": "string",
    "phase": 0,
    "possibleChallenges": [
      {
        "id": "string",
        "activation": "string",
        "expiry": "string",
        "isDaily": true,
        "isElite": true,
        "title": "string",
        "desc": "string",
        "reputation": 0
      }
    ],
    "activeChallenges": [
      {
        "id": "string",
        "activation": "string",
        "expiry": "string",
        "isDaily": true,
        "isElite": true,
        "title": "string",
        "desc": "string",
        "reputation": 0
      }
    ]
  }
}
```

<h3 id="get__ps4-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[ws](#schemaws)|

<aside class="success">
This operation does not require authentication
</aside>

## get__xb1

> Code samples

`GET /xb1`

*Get Warframe Worldstate Data for XB1*

The full translated Warframe Worldstate

> Example responses

> 200 Response

```json
{
  "timestamp": "string",
  "news": [
    {
      "date": "string",
      "imageLink": "string",
      "eta": "string",
      "primeAccess": true,
      "stream": true,
      "translations": {
        "es": "string"
      },
      "link": "string",
      "update": true,
      "id": "string",
      "asString": "string",
      "message": "string",
      "priority": true
    }
  ],
  "events": [
    {}
  ],
  "alerts": [
    {
      "mission": {
        "reward": {
          "countedItems": [
            {
              "count": 0,
              "type": "string"
            }
          ],
          "thumbnail": "string",
          "color": 0,
          "credits": 0,
          "asString": "string",
          "items": [
            {}
          ],
          "itemString": "string"
        },
        "node": "string",
        "faction": "string",
        "maxEnemyLevel": 0,
        "minEnemyLevel": 0,
        "maxWaveNum": 0,
        "type": "string",
        "nightmare": true,
        "archwingRequired": true
      },
      "expired": true,
      "eta": "string",
      "id": "string",
      "expiry": "string",
      "activation": "string",
      "rewardTypes": [
        {}
      ]
    }
  ],
  "sortie": {
    "id": "string",
    "activation": "string",
    "expiry": "string",
    "rewardPool": "string",
    "variants": [
      {
        "node": "string",
        "boss": "string",
        "missionType": "string",
        "planet": "string",
        "modifier": "string",
        "modifierDescription": "string"
      }
    ],
    "boss": "string",
    "faction": "string",
    "expired": true,
    "eta": "string"
  },
  "syndicateMissions": [
    {
      "nodes": [
        {}
      ],
      "eta": "string",
      "jobs": [
        {}
      ],
      "syndicate": "string",
      "id": "string",
      "expiry": "string",
      "activation": "string"
    }
  ],
  "fissures": [
    {
      "node": "string",
      "expired": true,
      "eta": "string",
      "missionType": "string",
      "tier": "string",
      "tierNum": 0,
      "enemy": "string",
      "id": "string",
      "expiry": "string",
      "activation": "string"
    }
  ],
  "globalUpgrades": [
    {}
  ],
  "flashSales": [
    {
      "item": "string",
      "expired": true,
      "eta": "string",
      "discount": 0,
      "premiumOverride": 0,
      "isPopular": true,
      "expiry": "string",
      "id": "string",
      "isFeatured": true
    }
  ],
  "invasions": [
    {
      "defenderReward": {
        "countedItems": [
          {
            "count": 0,
            "type": "string"
          }
        ],
        "thumbnail": "string",
        "color": 0,
        "credits": 0,
        "asString": "string",
        "items": [
          {}
        ],
        "itemString": "string"
      },
      "attackingFaction": "string",
      "completion": 0,
      "attackerReward": {
        "countedItems": [
          {
            "count": 0,
            "type": "string"
          }
        ],
        "thumbnail": "string",
        "color": 0,
        "credits": 0,
        "asString": "string",
        "items": [
          {}
        ],
        "itemString": "string"
      },
      "count": 0,
      "completed": true,
      "requiredRuns": 0,
      "vsInfestation": true,
      "node": "string",
      "eta": "string",
      "defendingFaction": "string",
      "id": "string",
      "activation": "string",
      "rewardTypes": [
        {}
      ],
      "desc": "string"
    }
  ],
  "darkSectors": [
    {
      "defenderMOTD": "string",
      "deployerName": "string",
      "defenderDeployemntActivation": 0,
      "defenderName": "string",
      "deployerClan": "string",
      "isAlliance": true,
      "id": "string",
      "history": [
        {}
      ]
    }
  ],
  "voidTrader": {
    "id": "string",
    "activation": "string",
    "expiry": "string",
    "character": "string",
    "location": "string",
    "inventory": [
      {}
    ],
    "psId": "string",
    "active": true,
    "startString": "string",
    "endString": "string"
  },
  "dailyDeals": [
    {
      "sold": 0,
      "item": "string",
      "total": 0,
      "eta": "string",
      "originalPrice": 0,
      "salePrice": 0,
      "discount": 0,
      "expiry": "string",
      "id": "string"
    }
  ],
  "simaris": {
    "target": "string",
    "isTargetActive": true,
    "asString": "string"
  },
  "conclaveChallenges": [
    {
      "mode": "string",
      "amount": 0,
      "eta": "string",
      "expired": true,
      "endString": "string",
      "daily": true,
      "description": "string",
      "id": "string",
      "expiry": "string",
      "asString": "string",
      "category": "string",
      "rootChallenge": true
    }
  ],
  "persistentEnemies": [
    {}
  ],
  "earthCycle": {
    "id": 0,
    "expiry": "string",
    "isDay": true,
    "timeLeft": "string"
  },
  "cetusCycle": {
    "id": "string",
    "expiry": "string",
    "isDay": true,
    "timeLeft": "string",
    "isCetus": true
  },
  "constructionProgress": {
    "id": "string",
    "fomorianProgress": "string",
    "razorbackProgress": "string",
    "unknownProgress": "string"
  },
  "nightwave": {
    "id": "string",
    "activation": "string",
    "expiry": "string",
    "params": {},
    "rewardTypes": [
      "string"
    ],
    "season": 0,
    "tag": "string",
    "phase": 0,
    "possibleChallenges": [
      {
        "id": "string",
        "activation": "string",
        "expiry": "string",
        "isDaily": true,
        "isElite": true,
        "title": "string",
        "desc": "string",
        "reputation": 0
      }
    ],
    "activeChallenges": [
      {
        "id": "string",
        "activation": "string",
        "expiry": "string",
        "isDaily": true,
        "isElite": true,
        "title": "string",
        "desc": "string",
        "reputation": 0
      }
    ]
  }
}
```

<h3 id="get__xb1-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[ws](#schemaws)|

<aside class="success">
This operation does not require authentication
</aside>

## get__swi

> Code samples

`GET /swi`

*Get Warframe Worldstate Data for Nintendo Switch*

The full translated Warframe Worldstate

> Example responses

> 200 Response

```json
{
  "timestamp": "string",
  "news": [
    {
      "date": "string",
      "imageLink": "string",
      "eta": "string",
      "primeAccess": true,
      "stream": true,
      "translations": {
        "es": "string"
      },
      "link": "string",
      "update": true,
      "id": "string",
      "asString": "string",
      "message": "string",
      "priority": true
    }
  ],
  "events": [
    {}
  ],
  "alerts": [
    {
      "mission": {
        "reward": {
          "countedItems": [
            {
              "count": 0,
              "type": "string"
            }
          ],
          "thumbnail": "string",
          "color": 0,
          "credits": 0,
          "asString": "string",
          "items": [
            {}
          ],
          "itemString": "string"
        },
        "node": "string",
        "faction": "string",
        "maxEnemyLevel": 0,
        "minEnemyLevel": 0,
        "maxWaveNum": 0,
        "type": "string",
        "nightmare": true,
        "archwingRequired": true
      },
      "expired": true,
      "eta": "string",
      "id": "string",
      "expiry": "string",
      "activation": "string",
      "rewardTypes": [
        {}
      ]
    }
  ],
  "sortie": {
    "id": "string",
    "activation": "string",
    "expiry": "string",
    "rewardPool": "string",
    "variants": [
      {
        "node": "string",
        "boss": "string",
        "missionType": "string",
        "planet": "string",
        "modifier": "string",
        "modifierDescription": "string"
      }
    ],
    "boss": "string",
    "faction": "string",
    "expired": true,
    "eta": "string"
  },
  "syndicateMissions": [
    {
      "nodes": [
        {}
      ],
      "eta": "string",
      "jobs": [
        {}
      ],
      "syndicate": "string",
      "id": "string",
      "expiry": "string",
      "activation": "string"
    }
  ],
  "fissures": [
    {
      "node": "string",
      "expired": true,
      "eta": "string",
      "missionType": "string",
      "tier": "string",
      "tierNum": 0,
      "enemy": "string",
      "id": "string",
      "expiry": "string",
      "activation": "string"
    }
  ],
  "globalUpgrades": [
    {}
  ],
  "flashSales": [
    {
      "item": "string",
      "expired": true,
      "eta": "string",
      "discount": 0,
      "premiumOverride": 0,
      "isPopular": true,
      "expiry": "string",
      "id": "string",
      "isFeatured": true
    }
  ],
  "invasions": [
    {
      "defenderReward": {
        "countedItems": [
          {
            "count": 0,
            "type": "string"
          }
        ],
        "thumbnail": "string",
        "color": 0,
        "credits": 0,
        "asString": "string",
        "items": [
          {}
        ],
        "itemString": "string"
      },
      "attackingFaction": "string",
      "completion": 0,
      "attackerReward": {
        "countedItems": [
          {
            "count": 0,
            "type": "string"
          }
        ],
        "thumbnail": "string",
        "color": 0,
        "credits": 0,
        "asString": "string",
        "items": [
          {}
        ],
        "itemString": "string"
      },
      "count": 0,
      "completed": true,
      "requiredRuns": 0,
      "vsInfestation": true,
      "node": "string",
      "eta": "string",
      "defendingFaction": "string",
      "id": "string",
      "activation": "string",
      "rewardTypes": [
        {}
      ],
      "desc": "string"
    }
  ],
  "darkSectors": [
    {
      "defenderMOTD": "string",
      "deployerName": "string",
      "defenderDeployemntActivation": 0,
      "defenderName": "string",
      "deployerClan": "string",
      "isAlliance": true,
      "id": "string",
      "history": [
        {}
      ]
    }
  ],
  "voidTrader": {
    "id": "string",
    "activation": "string",
    "expiry": "string",
    "character": "string",
    "location": "string",
    "inventory": [
      {}
    ],
    "psId": "string",
    "active": true,
    "startString": "string",
    "endString": "string"
  },
  "dailyDeals": [
    {
      "sold": 0,
      "item": "string",
      "total": 0,
      "eta": "string",
      "originalPrice": 0,
      "salePrice": 0,
      "discount": 0,
      "expiry": "string",
      "id": "string"
    }
  ],
  "simaris": {
    "target": "string",
    "isTargetActive": true,
    "asString": "string"
  },
  "conclaveChallenges": [
    {
      "mode": "string",
      "amount": 0,
      "eta": "string",
      "expired": true,
      "endString": "string",
      "daily": true,
      "description": "string",
      "id": "string",
      "expiry": "string",
      "asString": "string",
      "category": "string",
      "rootChallenge": true
    }
  ],
  "persistentEnemies": [
    {}
  ],
  "earthCycle": {
    "id": 0,
    "expiry": "string",
    "isDay": true,
    "timeLeft": "string"
  },
  "cetusCycle": {
    "id": "string",
    "expiry": "string",
    "isDay": true,
    "timeLeft": "string",
    "isCetus": true
  },
  "constructionProgress": {
    "id": "string",
    "fomorianProgress": "string",
    "razorbackProgress": "string",
    "unknownProgress": "string"
  },
  "nightwave": {
    "id": "string",
    "activation": "string",
    "expiry": "string",
    "params": {},
    "rewardTypes": [
      "string"
    ],
    "season": 0,
    "tag": "string",
    "phase": 0,
    "possibleChallenges": [
      {
        "id": "string",
        "activation": "string",
        "expiry": "string",
        "isDaily": true,
        "isElite": true,
        "title": "string",
        "desc": "string",
        "reputation": 0
      }
    ],
    "activeChallenges": [
      {
        "id": "string",
        "activation": "string",
        "expiry": "string",
        "isDaily": true,
        "isElite": true,
        "title": "string",
        "desc": "string",
        "reputation": 0
      }
    ]
  }
}
```

<h3 id="get__swi-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[ws](#schemaws)|

<aside class="success">
This operation does not require authentication
</aside>

## get__{platform}_news

> Code samples

`GET /{platform}/news`

*Current Listing of News items*

Translated News items from the worldstate

<h3 id="get__{platform}_news-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|platform|path|[platform](#schemaplatform)|true|Platform to provide data for|

#### Enumerated Values

|Parameter|Value|
|---|---|
|platform|pc|
|platform|ps4|
|platform|xb1|
|platform|swi|

> Example responses

> 200 Response

```json
[
  {
    "date": "string",
    "imageLink": "string",
    "eta": "string",
    "primeAccess": true,
    "stream": true,
    "translations": {
      "es": "string"
    },
    "link": "string",
    "update": true,
    "id": "string",
    "asString": "string",
    "message": "string",
    "priority": true
  }
]
```

<h3 id="get__{platform}_news-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[news](#schemanews)|

<aside class="success">
This operation does not require authentication
</aside>

## get__{platform}_events

> Code samples

`GET /{platform}/events`

*Listing of ongoing events*

Events, such as Fomorian Attacks are included here

<h3 id="get__{platform}_events-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|platform|path|[platform](#schemaplatform)|true|Platform to provide data for|

#### Enumerated Values

|Parameter|Value|
|---|---|
|platform|pc|
|platform|ps4|
|platform|xb1|
|platform|swi|

> Example responses

> 200 Response

```json
[
  [
    {}
  ]
]
```

<h3 id="get__{platform}_events-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|Inline|

<h3 id="get__{platform}_events-responseschema">Response Schema</h3>

Status Code **200**

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|*anonymous*|[[events](#schemaevents)]|false|none|none|

<aside class="success">
This operation does not require authentication
</aside>

## get__{platform}_alerts

> Code samples

`GET /{platform}/alerts`

*Alerts data*

Description and rewards for Alerts

<h3 id="get__{platform}_alerts-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|platform|path|[platform](#schemaplatform)|true|Platform to provide data for|

#### Enumerated Values

|Parameter|Value|
|---|---|
|platform|pc|
|platform|ps4|
|platform|xb1|
|platform|swi|

> Example responses

> 200 Response

```json
[
  {
    "mission": {
      "reward": {
        "countedItems": [
          {
            "count": 0,
            "type": "string"
          }
        ],
        "thumbnail": "string",
        "color": 0,
        "credits": 0,
        "asString": "string",
        "items": [
          {}
        ],
        "itemString": "string"
      },
      "node": "string",
      "faction": "string",
      "maxEnemyLevel": 0,
      "minEnemyLevel": 0,
      "maxWaveNum": 0,
      "type": "string",
      "nightmare": true,
      "archwingRequired": true
    },
    "expired": true,
    "eta": "string",
    "id": "string",
    "expiry": "string",
    "activation": "string",
    "rewardTypes": [
      {}
    ]
  }
]
```

<h3 id="get__{platform}_alerts-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[alert](#schemaalert)|

<aside class="success">
This operation does not require authentication
</aside>

## get__{platform}_sortie

> Code samples

`GET /{platform}/sortie`

*Current Sortie Data*

Data about the missions for the current sortie

<h3 id="get__{platform}_sortie-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|platform|path|[platform](#schemaplatform)|true|Platform to provide data for|

#### Enumerated Values

|Parameter|Value|
|---|---|
|platform|pc|
|platform|ps4|
|platform|xb1|
|platform|swi|

> Example responses

> 200 Response

```json
[
  {
    "id": "string",
    "activation": "string",
    "expiry": "string",
    "rewardPool": "string",
    "variants": [
      {
        "node": "string",
        "boss": "string",
        "missionType": "string",
        "planet": "string",
        "modifier": "string",
        "modifierDescription": "string"
      }
    ],
    "boss": "string",
    "faction": "string",
    "expired": true,
    "eta": "string"
  }
]
```

<h3 id="get__{platform}_sortie-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|Inline|

<h3 id="get__{platform}_sortie-responseschema">Response Schema</h3>

Status Code **200**

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|*anonymous*|[[sortie](#schemasortie)]|false|none|none|
|» id|string|true|none|none|
|» activation|string|true|none|none|
|» expiry|string|true|none|none|
|» rewardPool|string|true|none|none|
|» variants|[object]|true|none|none|
|»» node|string|true|none|none|
|»» boss|string|true|none|none|
|»» missionType|string|true|none|none|
|»» planet|string|true|none|none|
|»» modifier|string|true|none|none|
|»» modifierDescription|string|true|none|none|
|» boss|string|true|none|none|
|» faction|string|true|none|none|
|» expired|boolean|true|none|none|
|» eta|string|true|none|none|

<aside class="success">
This operation does not require authentication
</aside>

## get__{platform}_syndicateMissions

> Code samples

`GET /{platform}/syndicateMissions`

*Listing of Syndicate mission nodes*

Cycling through different nodes each day, these are a general listing of the nodes that each syndicate will use for the day.

<h3 id="get__{platform}_syndicatemissions-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|platform|path|[platform](#schemaplatform)|true|Platform to provide data for|

#### Enumerated Values

|Parameter|Value|
|---|---|
|platform|pc|
|platform|ps4|
|platform|xb1|
|platform|swi|

> Example responses

> 200 Response

```json
[
  [
    {
      "nodes": [
        {}
      ],
      "eta": "string",
      "jobs": [
        {}
      ],
      "syndicate": "string",
      "id": "string",
      "expiry": "string",
      "activation": "string"
    }
  ]
]
```

<h3 id="get__{platform}_syndicatemissions-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|Inline|

<h3 id="get__{platform}_syndicatemissions-responseschema">Response Schema</h3>

Status Code **200**

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|*anonymous*|[[syndicateMissions](#schemasyndicatemissions)]|false|none|none|
|» nodes|[object]|false|none|none|
|» eta|string|true|none|none|
|» jobs|[object]|false|none|none|
|» syndicate|string|true|none|none|
|» id|string|true|none|none|
|» expiry|string|true|none|none|
|» activation|string|true|none|none|

<aside class="success">
This operation does not require authentication
</aside>

## get__{platform}_fissures

> Code samples

`GET /{platform}/fissures`

*Data on current fissures*

Information about current Void Fissure missions

<h3 id="get__{platform}_fissures-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|platform|path|[platform](#schemaplatform)|true|Platform to provide data for|

#### Enumerated Values

|Parameter|Value|
|---|---|
|platform|pc|
|platform|ps4|
|platform|xb1|
|platform|swi|

> Example responses

> 200 Response

```json
[
  [
    {
      "node": "string",
      "expired": true,
      "eta": "string",
      "missionType": "string",
      "tier": "string",
      "tierNum": 0,
      "enemy": "string",
      "id": "string",
      "expiry": "string",
      "activation": "string"
    }
  ]
]
```

<h3 id="get__{platform}_fissures-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|Inline|

<h3 id="get__{platform}_fissures-responseschema">Response Schema</h3>

Status Code **200**

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|*anonymous*|[[fissures](#schemafissures)]|false|none|none|
|» node|string|true|none|none|
|» expired|boolean|true|none|none|
|» eta|string|true|none|none|
|» missionType|string|true|none|none|
|» tier|string|true|none|none|
|» tierNum|number|true|none|none|
|» enemy|string|true|none|none|
|» id|string|true|none|none|
|» expiry|string|true|none|none|
|» activation|string|true|none|none|

<aside class="success">
This operation does not require authentication
</aside>

## get__{platform}_globalUpgrades

> Code samples

`GET /{platform}/globalUpgrades`

*Current Global Upgrades*

Any current modifiers applied to all users, such as double drops.

<h3 id="get__{platform}_globalupgrades-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|platform|path|[platform](#schemaplatform)|true|Platform to provide data for|

#### Enumerated Values

|Parameter|Value|
|---|---|
|platform|pc|
|platform|ps4|
|platform|xb1|
|platform|swi|

> Example responses

> 200 Response

```json
[
  [
    {}
  ]
]
```

<h3 id="get__{platform}_globalupgrades-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|Inline|

<h3 id="get__{platform}_globalupgrades-responseschema">Response Schema</h3>

Status Code **200**

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|*anonymous*|[[globalUpgrades](#schemaglobalupgrades)]|false|none|none|

<aside class="success">
This operation does not require authentication
</aside>

## get__{platform}_flashSales

> Code samples

`GET /{platform}/flashSales`

*Current Flash Sales from Darvo*

Popular Deals, discounts, featured deals.

<h3 id="get__{platform}_flashsales-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|platform|path|[platform](#schemaplatform)|true|Platform to provide data for|

#### Enumerated Values

|Parameter|Value|
|---|---|
|platform|pc|
|platform|ps4|
|platform|xb1|
|platform|swi|

> Example responses

> 200 Response

```json
[
  {
    "item": "string",
    "expired": true,
    "eta": "string",
    "discount": 0,
    "premiumOverride": 0,
    "isPopular": true,
    "expiry": "string",
    "id": "string",
    "isFeatured": true
  }
]
```

<h3 id="get__{platform}_flashsales-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[flashSales](#schemaflashsales)|

<aside class="success">
This operation does not require authentication
</aside>

## get__{platform}_invasions

> Code samples

`GET /{platform}/invasions`

*Invasion Data*

Data on invasion missions, such as estimated completion time, rewards, etc.

<h3 id="get__{platform}_invasions-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|platform|path|[platform](#schemaplatform)|true|Platform to provide data for|

#### Enumerated Values

|Parameter|Value|
|---|---|
|platform|pc|
|platform|ps4|
|platform|xb1|
|platform|swi|

> Example responses

> 200 Response

```json
[
  [
    {
      "defenderReward": {
        "countedItems": [
          {
            "count": 0,
            "type": "string"
          }
        ],
        "thumbnail": "string",
        "color": 0,
        "credits": 0,
        "asString": "string",
        "items": [
          {}
        ],
        "itemString": "string"
      },
      "attackingFaction": "string",
      "completion": 0,
      "attackerReward": {
        "countedItems": [
          {
            "count": 0,
            "type": "string"
          }
        ],
        "thumbnail": "string",
        "color": 0,
        "credits": 0,
        "asString": "string",
        "items": [
          {}
        ],
        "itemString": "string"
      },
      "count": 0,
      "completed": true,
      "requiredRuns": 0,
      "vsInfestation": true,
      "node": "string",
      "eta": "string",
      "defendingFaction": "string",
      "id": "string",
      "activation": "string",
      "rewardTypes": [
        {}
      ],
      "desc": "string"
    }
  ]
]
```

<h3 id="get__{platform}_invasions-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|Inline|

<h3 id="get__{platform}_invasions-responseschema">Response Schema</h3>

Status Code **200**

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|*anonymous*|[[invasions](#schemainvasions)]|false|none|none|
|» defenderReward|object|false|none|none|
|»» countedItems|[object]|true|none|none|
|»»» count|number|true|none|none|
|»»» type|string|true|none|none|
|»» thumbnail|string|true|none|none|
|»» color|number|true|none|none|
|»» credits|number|true|none|none|
|»» asString|string|true|none|none|
|»» items|[object]|true|none|none|
|»» itemString|string|true|none|none|
|» attackingFaction|string|true|none|none|
|» completion|number|true|none|none|
|» attackerReward|object|false|none|none|
|»» countedItems|[object]|true|none|none|
|»»» count|number|true|none|none|
|»»» type|string|true|none|none|
|»» thumbnail|string|true|none|none|
|»» color|number|true|none|none|
|»» credits|number|true|none|none|
|»» asString|string|true|none|none|
|»» items|[object]|true|none|none|
|»» itemString|string|true|none|none|
|» count|number|true|none|none|
|» completed|boolean|true|none|none|
|» requiredRuns|number|true|none|none|
|» vsInfestation|boolean|true|none|none|
|» node|string|true|none|none|
|» eta|string|true|none|none|
|» defendingFaction|string|true|none|none|
|» id|string|true|none|none|
|» activation|string|true|none|none|
|» rewardTypes|[object]|false|none|none|
|» desc|string|true|none|none|

<aside class="success">
This operation does not require authentication
</aside>

## get__{platform}_darkSectors

> Code samples

`GET /{platform}/darkSectors`

*Dark Sector occupation and history*

Dark Sector (Rail Wars) data and history. Digital Extremes has emptied several of these.

<h3 id="get__{platform}_darksectors-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|platform|path|[platform](#schemaplatform)|true|Platform to provide data for|

#### Enumerated Values

|Parameter|Value|
|---|---|
|platform|pc|
|platform|ps4|
|platform|xb1|
|platform|swi|

> Example responses

> 200 Response

```json
[
  [
    {
      "defenderMOTD": "string",
      "deployerName": "string",
      "defenderDeployemntActivation": 0,
      "defenderName": "string",
      "deployerClan": "string",
      "isAlliance": true,
      "id": "string",
      "history": [
        {}
      ]
    }
  ]
]
```

<h3 id="get__{platform}_darksectors-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|Inline|

<h3 id="get__{platform}_darksectors-responseschema">Response Schema</h3>

Status Code **200**

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|*anonymous*|[[darkSectors](#schemadarksectors)]|false|none|none|
|» defenderMOTD|string|true|none|none|
|» deployerName|string|true|none|none|
|» defenderDeployemntActivation|number|true|none|none|
|» defenderName|string|true|none|none|
|» deployerClan|string|true|none|none|
|» isAlliance|boolean|true|none|none|
|» id|string|true|none|none|
|» history|[object]|false|none|none|

<aside class="success">
This operation does not require authentication
</aside>

## get__{platform}_voidTrader

> Code samples

`GET /{platform}/voidTrader`

*Get the current Void Trader Information*

Information on the current Void Trader offerings, or when he will arrive.

<h3 id="get__{platform}_voidtrader-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|platform|path|[platform](#schemaplatform)|true|Platform to provide data for|

#### Enumerated Values

|Parameter|Value|
|---|---|
|platform|pc|
|platform|ps4|
|platform|xb1|
|platform|swi|

> Example responses

> 200 Response

```json
{
  "id": "string",
  "activation": "string",
  "expiry": "string",
  "character": "string",
  "location": "string",
  "inventory": [
    {}
  ],
  "psId": "string",
  "active": true,
  "startString": "string",
  "endString": "string"
}
```

<h3 id="get__{platform}_voidtrader-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[voidTrader](#schemavoidtrader)|

<aside class="success">
This operation does not require authentication
</aside>

## get__{platform}_dailyDeals

> Code samples

`GET /{platform}/dailyDeals`

*Daily Deal information from Darvo*

Darvo's Daily Deal details

<h3 id="get__{platform}_dailydeals-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|platform|path|[platform](#schemaplatform)|true|Platform to provide data for|

#### Enumerated Values

|Parameter|Value|
|---|---|
|platform|pc|
|platform|ps4|
|platform|xb1|
|platform|swi|

> Example responses

> 200 Response

```json
[
  {
    "sold": 0,
    "item": "string",
    "total": 0,
    "eta": "string",
    "originalPrice": 0,
    "salePrice": 0,
    "discount": 0,
    "expiry": "string",
    "id": "string"
  }
]
```

<h3 id="get__{platform}_dailydeals-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[dailyDeals](#schemadailydeals)|

<aside class="success">
This operation does not require authentication
</aside>

## get__{platform}_simaris

> Code samples

`GET /{platform}/simaris`

*Get the current Sanctuary Status*

Status data for Simaris' Sanctuary

<h3 id="get__{platform}_simaris-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|platform|path|[platform](#schemaplatform)|true|Platform to provide data for|

#### Enumerated Values

|Parameter|Value|
|---|---|
|platform|pc|
|platform|ps4|
|platform|xb1|
|platform|swi|

> Example responses

> 200 Response

```json
{
  "target": "string",
  "isTargetActive": true,
  "asString": "string"
}
```

<h3 id="get__{platform}_simaris-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[simaris](#schemasimaris)|

<aside class="success">
This operation does not require authentication
</aside>

## get__{platform}_conclaveChallenges

> Code samples

`GET /{platform}/conclaveChallenges`

*Get Conclave Challenge Data*

Data on each day and week's conclave challenges

<h3 id="get__{platform}_conclavechallenges-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|platform|path|[platform](#schemaplatform)|true|Platform to provide data for|

#### Enumerated Values

|Parameter|Value|
|---|---|
|platform|pc|
|platform|ps4|
|platform|xb1|
|platform|swi|

> Example responses

> 200 Response

```json
[
  {
    "mode": "string",
    "amount": 0,
    "eta": "string",
    "expired": true,
    "endString": "string",
    "daily": true,
    "description": "string",
    "id": "string",
    "expiry": "string",
    "asString": "string",
    "category": "string",
    "rootChallenge": true
  }
]
```

<h3 id="get__{platform}_conclavechallenges-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[conclaveChallenges](#schemaconclavechallenges)|

<aside class="success">
This operation does not require authentication
</aside>

## get__{platform}_persistentEnemies

> Code samples

`GET /{platform}/persistentEnemies`

*Get Persistent Enemy Data*

Data about current acolytes attacking the Sol System

<h3 id="get__{platform}_persistentenemies-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|platform|path|[platform](#schemaplatform)|true|Platform to provide data for|

#### Enumerated Values

|Parameter|Value|
|---|---|
|platform|pc|
|platform|ps4|
|platform|xb1|
|platform|swi|

> Example responses

> 200 Response

```json
[
  {}
]
```

<h3 id="get__{platform}_persistentenemies-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[persistentEnemies](#schemapersistentenemies)|

<aside class="success">
This operation does not require authentication
</aside>

## get__{platform}_cetusCycle

> Code samples

`GET /{platform}/cetusCycle`

*Get Current Cetus Status*

Data on the Day/night cycle for Cetus on earth

<h3 id="get__{platform}_cetuscycle-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|platform|path|[platform](#schemaplatform)|true|Platform to provide data for|

#### Enumerated Values

|Parameter|Value|
|---|---|
|platform|pc|
|platform|ps4|
|platform|xb1|
|platform|swi|

> Example responses

> 200 Response

```json
{
  "id": "string",
  "expiry": "string",
  "isDay": true,
  "timeLeft": "string",
  "isCetus": true
}
```

<h3 id="get__{platform}_cetuscycle-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[cetusCycle](#schemacetuscycle)|

<aside class="success">
This operation does not require authentication
</aside>

## get__{platform}_constructionProgress

> Code samples

`GET /{platform}/constructionProgress`

*Get Construction Progress for Fomorians and Razorbacks*

Construction percentages for showing how far constructed the enemy fleets are.

<h3 id="get__{platform}_constructionprogress-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|platform|path|[platform](#schemaplatform)|true|Platform to provide data for|

#### Enumerated Values

|Parameter|Value|
|---|---|
|platform|pc|
|platform|ps4|
|platform|xb1|
|platform|swi|

> Example responses

> 200 Response

```json
{
  "id": "string",
  "fomorianProgress": "string",
  "razorbackProgress": "string",
  "unknownProgress": "string"
}
```

<h3 id="get__{platform}_constructionprogress-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[construction](#schemaconstruction)|

<aside class="success">
This operation does not require authentication
</aside>

## get__{platform}_earthCycle

> Code samples

`GET /{platform}/earthCycle`

*Get the current Earth rotation information*

The current Earth day/night cycle progress.

<h3 id="get__{platform}_earthcycle-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|platform|path|[platform](#schemaplatform)|true|Platform to provide data for|

#### Enumerated Values

|Parameter|Value|
|---|---|
|platform|pc|
|platform|ps4|
|platform|xb1|
|platform|swi|

> Example responses

> 200 Response

```json
{
  "id": 0,
  "expiry": "string",
  "isDay": true,
  "timeLeft": "string"
}
```

<h3 id="get__{platform}_earthcycle-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[earthCycle](#schemaearthcycle)|

<aside class="success">
This operation does not require authentication
</aside>

## get__{platform}_timestamp

> Code samples

`GET /{platform}/timestamp`

*Get the timestamp that the current worldstate was generated at.*

The time that the worldstate was last generated

<h3 id="get__{platform}_timestamp-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|platform|path|[platform](#schemaplatform)|true|Platform to provide data for|

#### Enumerated Values

|Parameter|Value|
|---|---|
|platform|pc|
|platform|ps4|
|platform|xb1|
|platform|swi|

> Example responses

> 200 Response

```json
"string"
```

<h3 id="get__{platform}_timestamp-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[timestamp](#schematimestamp)|

<aside class="success">
This operation does not require authentication
</aside>

## get__{platform}_nightwave

> Code samples

`GET /{platform}/nightwave`

*Get the current Nightwave state.*

The Current cycle and challenges of Nightwave, a battle-pass-esque rotation and challenge system

<h3 id="get__{platform}_nightwave-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|platform|path|[platform](#schemaplatform)|true|Platform to provide data for|

#### Enumerated Values

|Parameter|Value|
|---|---|
|platform|pc|
|platform|ps4|
|platform|xb1|
|platform|swi|

> Example responses

> 200 Response

```json
{
  "id": "string",
  "activation": "string",
  "expiry": "string",
  "params": {},
  "rewardTypes": [
    "string"
  ],
  "season": 0,
  "tag": "string",
  "phase": 0,
  "possibleChallenges": [
    {
      "id": "string",
      "activation": "string",
      "expiry": "string",
      "isDaily": true,
      "isElite": true,
      "title": "string",
      "desc": "string",
      "reputation": 0
    }
  ],
  "activeChallenges": [
    {
      "id": "string",
      "activation": "string",
      "expiry": "string",
      "isDaily": true,
      "isElite": true,
      "title": "string",
      "desc": "string",
      "reputation": 0
    }
  ]
}
```

<h3 id="get__{platform}_nightwave-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[nightwave](#schemanightwave)|

<aside class="success">
This operation does not require authentication
</aside>

## get__{platform}_vallisCycle

> Code samples

`GET /{platform}/vallisCycle`

*Get the current state of the Orb Vallis*

The current cycle of the Orb Vallis warm/cold cycle

<h3 id="get__{platform}_valliscycle-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|platform|path|[platform](#schemaplatform)|true|Platform to provide data for|

#### Enumerated Values

|Parameter|Value|
|---|---|
|platform|pc|
|platform|ps4|
|platform|xb1|
|platform|swi|

> Example responses

> 200 Response

```json
{
  "id": "string",
  "expiry": "string",
  "timeLeft": "string",
  "isWarm": true
}
```

<h3 id="get__{platform}_valliscycle-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[vallisCycle](#schemavalliscycle)|

<aside class="success">
This operation does not require authentication
</aside>

<h1 id="warframestat-us-api-data">data</h1>

## get__routes

> Code samples

`GET /routes`

*Get the available routes*

Routes that are available

> Example responses

> 200 Response

```json
"string"
```

<h3 id="get__routes-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[timestamp](#schematimestamp)|

<aside class="success">
This operation does not require authentication
</aside>

## get__arcanes

> Code samples

`GET /arcanes`

*Get Arcane Enhancement Data*

Available Arcane Enhancements

> Example responses

> 200 Response

```json
{
  "regex": "string",
  "name": "string",
  "effect": "string",
  "rarity": "string",
  "location": "string",
  "thumbnail": "string",
  "info": "string"
}
```

<h3 id="get__arcanes-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[arcane](#schemaarcane)|

<aside class="success">
This operation does not require authentication
</aside>

## get__conclave

> Code samples

`GET /conclave`

*Get conclave challenge data*

Data about conclave challenges

> Example responses

> 200 Response

```json
{
  "modes": {
    "PVPMODE_ALL": {
      "value": "string"
    },
    "PVPMODE_TEAMDEATHMATCH": {
      "value": "string"
    },
    "PVPMODE_NONE": {
      "value": "string"
    },
    "PVPMODE_CAPTURETHEFLAG": {
      "value": "string"
    },
    "PVPMODE_SPEEDBALL": {
      "value": "string"
    },
    "PVPMODE_DEATHMATCH": {
      "value": "string"
    }
  },
  "categories": {
    "PVPChallengeTypeCategory_DAILY_ROOT": {
      "value": "string"
    },
    "PVPChallengeTypeCategory_DAILY": {
      "value": "string"
    },
    "PVPChallengeTypeCategory_WEEKLY": {
      "value": "string"
    },
    "PVPChallengeTypeCategory_WEEKLY_ROOT": {
      "value": "string"
    },
    "PVPChallengeTypeCategory_MODEAFFECTOR": {
      "value": "string"
    }
  }
}
```

<h3 id="get__conclave-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[conclave](#schemaconclave)|

<aside class="success">
This operation does not require authentication
</aside>

## get__events

> Code samples

`GET /events`

*Get Event-specific Data*

Data about events

> Example responses

> 200 Response

```json
[
  {}
]
```

<h3 id="get__events-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[events](#schemaevents)|

<aside class="success">
This operation does not require authentication
</aside>

## get__factions

> Code samples

`GET /factions`

*Get Faction translation information.*

Strings for translating faction identifiers.

> Example responses

> 200 Response

```json
{
  "FC_GRINEER": {
    "value": "string"
  },
  "FC_CORPUS": {
    "value": "string"
  },
  "FC_INFESTATION": {
    "value": "string"
  },
  "FC_CORRUPTED": {
    "value": "string"
  },
  "FC_OROKIN": {
    "value": "string"
  }
}
```

<h3 id="get__factions-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[factions](#schemafactions)|

<aside class="success">
This operation does not require authentication
</aside>

## get__fissureModifiers

> Code samples

`GET /fissureModifiers`

*Get Fissure Modifier translation data.*

Fissure translation identifiers

> Example responses

> 200 Response

```json
{
  "VoidT1": {
    "num": 0,
    "value": "string"
  },
  "VoidT2": {
    "num": 0,
    "value": "string"
  },
  "VoidT3": {
    "num": 0,
    "value": "string"
  },
  "VoidT4": {
    "num": 0,
    "value": "string"
  }
}
```

<h3 id="get__fissuremodifiers-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[fissureModifiers](#schemafissuremodifiers)|

<aside class="success">
This operation does not require authentication
</aside>

## get__languages

> Code samples

`GET /languages`

*Get Language strings for Warframe.*

Get language strings to assist translation. (Prefer the /languages/search/:query route)

> Example responses

> 200 Response

```json
{
  "languageKey": {
    "value": "string"
  }
}
```

<h3 id="get__languages-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[languages](#schemalanguages)|

<aside class="success">
This operation does not require authentication
</aside>

## get__missionTypes

> Code samples

`GET /missionTypes`

*Get MissionType Translation Keys*

Mission Type information to aid translating identifiers

> Example responses

> 200 Response

```json
{
  "MT_EXCAVATE": {
    "value": "string"
  },
  "MT_SABOTAGE": {
    "value": "string"
  },
  "MT_MOBILE_DEFENSE": {
    "value": "string"
  },
  "MT_ASSASSINATION": {
    "value": "string"
  },
  "MT_EXTERMINATION": {
    "value": "string"
  },
  "MT_HIVE": {
    "value": "string"
  },
  "MT_DEFENSE": {
    "value": "string"
  },
  "MT_TERRITORY": {
    "value": "string"
  },
  "MT_ARENA": {
    "value": "string"
  },
  "MT_PVP": {
    "value": "string"
  },
  "MT_RESCUE": {
    "value": "string"
  },
  "MT_INTEL": {
    "value": "string"
  },
  "MT_SURVIVAL": {
    "value": "string"
  },
  "MT_CAPTURE": {
    "value": "string"
  },
  "MT_SECTOR": {
    "value": "string"
  },
  "MT_RETRIEVAL": {
    "value": "string"
  },
  "MT_ASSAULT": {
    "value": "string"
  },
  "MT_EVACUATION": {
    "value": "string"
  }
}
```

<h3 id="get__missiontypes-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[missionTypes](#schemamissiontypes)|

<aside class="success">
This operation does not require authentication
</aside>

## get__operationTypes

> Code samples

`GET /operationTypes`

*Get operation types data.*

Operation Types information to aid translating identifiers for global upgrades

> Example responses

> 200 Response

```json
{
  "MULTIPLY": {
    "value": "string"
  }
}
```

<h3 id="get__operationtypes-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[operationTypes](#schemaoperationtypes)|

<aside class="success">
This operation does not require authentication
</aside>

## get__persistentEnemy

> Code samples

`GET /persistentEnemy`

*Get Persistent Enemy translation data.*

Persistent Enemy translation information for aiding translation of identifiers.

> Example responses

> 200 Response

```json
[
  {}
]
```

<h3 id="get__persistentenemy-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[persistentEnemies](#schemapersistentenemies)|

<aside class="success">
This operation does not require authentication
</aside>

## get__solNodes

> Code samples

`GET /solNodes`

*Get Sol Node information and translation data.*

Sol Node translation information for aiding the translation of identifiers.

> Example responses

> 200 Response

```json
{
  "SolKey": {
    "enemy": "string",
    "type": "string",
    "value": "string"
  }
}
```

<h3 id="get__solnodes-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[solNode](#schemasolnode)|

<aside class="success">
This operation does not require authentication
</aside>

## get__sortie

> Code samples

`GET /sortie`

*Get Sortie translation information.*

Sortie translation information for assisting translation of identifiers.

> Example responses

> 200 Response

```json
{
  "modifierTypes": {
    "SORTIE_MODIFIER_IMPACT": "string",
    "SORTIE_MODIFIER_HAZARD_COLD": "string",
    "SORTIE_MODIFIER_SECONDARY_ONLY": "string",
    "SORTIE_MODIFIER_TOXIN": "string",
    "SORTIE_MODIFIER_ELECTRICITY": "string",
    "SORTIE_MODIFIER_HAZARD_FOG": "string",
    "SORTIE_MODIFIER_HAZARD_MAGNETIC": "string",
    "SORTIE_MODIFIER_ARMOR": "string",
    "SORTIE_MODIFIER_CORROSIVE": "string",
    "SORTIE_MODIFIER_VIRAL": "string",
    "SORTIE_MODIFIER_HAZARD_RADIATION": "string",
    "SORTIE_MODIFIER_SLASH": "string",
    "SORTIE_MODIFIER_POISON": "string",
    "SORTIE_MODIFIER_GAS": "string",
    "SORTIE_MODIFIER_MAGNETIC": "string",
    "SORTIE_MODIFIER_FIRE": "string",
    "SORTIE_MODIFIER_SNIPER_ONLY": "string",
    "SORTIE_MODIFIER_PUNCTURE": "string",
    "SORTIE_MODIFIER_EXPLOSION": "string",
    "SORTIE_MODIFIER_BOW_ONLY": "string",
    "SORTIE_MODIFIER_RADIATION": "string",
    "SORTIE_MODIFIER_SHIELDS": "string",
    "SORTIE_MODIFIER_FREEZE": "string",
    "SORTIE_MODIFIER_HAZARD_FIRE": "string",
    "SORTIE_MODIFIER_EXIMUS": "string",
    "SORTIE_MODIFIER_SHOTGUN_ONLY": "string",
    "SORTIE_MODIFIER_MELEE_ONLY": "string",
    "SORTIE_MODIFIER_RIFLE_ONLY": "string",
    "SORTIE_MODIFIER_HAZARD_ICE": "string",
    "SORTIE_MODIFIER_LOW_ENERGY": "string"
  },
  "modifierDescriptions": {
    "SORTIE_MODIFIER_IMPACT": "string",
    "SORTIE_MODIFIER_HAZARD_COLD": "string",
    "SORTIE_MODIFIER_SECONDARY_ONLY": "string",
    "SORTIE_MODIFIER_TOXIN": "string",
    "SORTIE_MODIFIER_ELECTRICITY": "string",
    "SORTIE_MODIFIER_HAZARD_FOG": "string",
    "SORTIE_MODIFIER_HAZARD_MAGNETIC": "string",
    "SORTIE_MODIFIER_ARMOR": "string",
    "SORTIE_MODIFIER_CORROSIVE": "string",
    "SORTIE_MODIFIER_VIRAL": "string",
    "SORTIE_MODIFIER_HAZARD_RADIATION": "string",
    "SORTIE_MODIFIER_SLASH": "string",
    "SORTIE_MODIFIER_POISON": "string",
    "SORTIE_MODIFIER_GAS": "string",
    "SORTIE_MODIFIER_MAGNETIC": "string",
    "SORTIE_MODIFIER_FIRE": "string",
    "SORTIE_MODIFIER_SNIPER_ONLY": "string",
    "SORTIE_MODIFIER_PUNCTURE": "string",
    "SORTIE_MODIFIER_EXPLOSION": "string",
    "SORTIE_MODIFIER_BOW_ONLY": "string",
    "SORTIE_MODIFIER_RADIATION": "string",
    "SORTIE_MODIFIER_SHIELDS": "string",
    "SORTIE_MODIFIER_FREEZE": "string",
    "SORTIE_MODIFIER_HAZARD_FIRE": "string",
    "SORTIE_MODIFIER_EXIMUS": "string",
    "SORTIE_MODIFIER_SHOTGUN_ONLY": "string",
    "SORTIE_MODIFIER_MELEE_ONLY": "string",
    "SORTIE_MODIFIER_RIFLE_ONLY": "string",
    "SORTIE_MODIFIER_HAZARD_ICE": "string",
    "SORTIE_MODIFIER_LOW_ENERGY": "string"
  },
  "bosses": {
    "SORTIE_BOSS_KELA": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_AMBULAS": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_TYL": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_ALAD": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_RUK": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_HYENA": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_KRIL": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_CORRUPTED_VOR": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_INFALAD": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_PHORID": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_JACKAL": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_RAPTOR": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_VOR": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_HEK": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_NEF": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_LEPHANTIS": {
      "faction": "string",
      "name": "string"
    }
  },
  "endStates": [
    {
      "regions": [
        {
          "missions": [
            {}
          ],
          "name": "string"
        }
      ],
      "bossName": "string"
    }
  ],
  "modifiers": [
    {}
  ]
}
```

<h3 id="get__sortie-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[sortieData](#schemasortiedata)|

<aside class="success">
This operation does not require authentication
</aside>

## get__syndicates

> Code samples

`GET /syndicates`

*Get Syndicate translation data.*

Information to assist translating syndicate identifiers.

> Example responses

> 200 Response

```json
{
  "ArbitersSyndicate": {
    "name": "string"
  },
  "CephalonSudaSyndicate": {
    "name": "string"
  },
  "NewLokaSyndicate": {
    "name": "string"
  },
  "PerrinSyndicate": {
    "name": "string"
  },
  "SteelMeridianSyndicate": {
    "name": "string"
  },
  "RedVeilSyndicate": {
    "name": "string"
  },
  "CetusSyndicate": {
    "name": "string"
  },
  "QuillsSyndicate": {
    "name": "string"
  },
  "AssassinsSyndicate": {
    "name": "string"
  },
  "EventSyndicate": {
    "name": "string"
  }
}
```

<h3 id="get__syndicates-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[syndicates](#schemasyndicates)|

<aside class="success">
This operation does not require authentication
</aside>

## get__tutorials

> Code samples

`GET /tutorials`

*Get Tutorials Data*

Tutorials data from DE

> Example responses

> 200 Response

```json
[
  {
    "regex": "string",
    "name": "string",
    "url": "string"
  }
]
```

<h3 id="get__tutorials-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[tutorials](#schematutorials)|

<aside class="success">
This operation does not require authentication
</aside>

## get__upgradeTypes

> Code samples

`GET /upgradeTypes`

*Get upgrade types data for global upgrades.*

Upgrade types for what can be changed by global modifiers, such as double credit weekends.

> Example responses

> 200 Response

```json
{
  "GAMEPLAY_KILL_XP_AMOUNT": {
    "value": "string"
  },
  "GAMEPLAY_PICKUP_AMOUNT": {
    "value": "string"
  },
  "GAMEPLAY_MONEY_REWARD_AMOUNT": {
    "value": "string"
  },
  "GAMEPLAY_MONEY_PICKUP_AMOUNT": {
    "value": "string"
  }
}
```

<h3 id="get__upgradetypes-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[upgradeTypes](#schemaupgradetypes)|

<aside class="success">
This operation does not require authentication
</aside>

## get__warframes

> Code samples

`GET /warframes`

*Get Warframe specs and data, such as polarities defenses, and profile.*

Warframe stats and general information.

> Example responses

> 200 Response

```json
[
  {
    "shield": "string",
    "polarities": [
      {}
    ],
    "prime_power": "string",
    "prime_mr": "string",
    "color": 0,
    "prime_polarities": [
      {}
    ],
    "conclave": "string",
    "description": "string",
    "prime_armor": "string",
    "speed": "string",
    "aura": "string",
    "prime_url": "string",
    "prime_health": "string",
    "power": "string",
    "prime_aura": "string",
    "info": "string",
    "thumbnail": "string",
    "mr": "string",
    "prime_shield": "string",
    "health": "string",
    "prime_speed": "string",
    "url": "string",
    "regex": "string",
    "armor": "string",
    "name": "string",
    "location": "string",
    "prime_conclave": "string"
  }
]
```

<h3 id="get__warframes-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[warframes](#schemawarframes)|

<aside class="success">
This operation does not require authentication
</aside>

## get__weapons

> Code samples

`GET /weapons`

*Get Weapon data and statistics.*

Weapon statistics.

> Example responses

> 200 Response

```json
[
  {
    "name": "string",
    "uniqueName": "string",
    "secondsPerShot": 0,
    "dmagePerShot": [
      0
    ],
    "magazineSize": 0,
    "reloadTime": 0,
    "totalDamage": 0,
    "damagePerSecond": 0,
    "trigger": "string",
    "description": "string",
    "accuracy": 0,
    "criticalChance": 0,
    "criticalMultiplier": 0,
    "procChance": 0,
    "fireRate": 0,
    "slot": 0,
    "noise": "string",
    "sentinel": true,
    "masteryReq": 0,
    "omegaAttenuation": 0,
    "type": "string",
    "buildPrice": 0,
    "buildTime": 0,
    "skipBuildTimePrice": 0,
    "buildQuantity": 0,
    "consumeOnBuild": true,
    "components": {
      "name": "string",
      "uniqueName": "string"
    },
    "imageName": "string",
    "category": "string",
    "tradable": true,
    "patchlogs": {
      "name": "string",
      "date": "string",
      "url": "string",
      "additions": "string",
      "changes": "string",
      "fixes": "string"
    },
    "ammo": 0,
    "damage": 0,
    "damageTypes": {
      "impact": 0,
      "puncture": 0,
      "slash": 0,
      "heat": 0,
      "cold": 0,
      "electric": 0,
      "toxin": 0,
      "gas": 0,
      "viral": 0,
      "corrosive": 0,
      "blast": 0,
      "magnetic": 0,
      "radiation": 0,
      "true": 0,
      "void": 0
    },
    "flight": 0,
    "polarities": "Vazarin",
    "projectile": "string",
    "tags": [
      "string"
    ],
    "vaulted": true,
    "wikiaThumbnail": "string",
    "wikiaUrl": "string",
    "disposition": 0,
    "releaseDate": "string",
    "vaultDate": "string"
  }
]
```

<h3 id="get__weapons-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[weapons](#schemaweapons)|

<aside class="success">
This operation does not require authentication
</aside>

<h1 id="warframestat-us-api-queryable">queryable</h1>

## get__arcanes_search_{query}

> Code samples

`GET /arcanes/search/{query}`

*Get Arcane Enhancement Data based on the query*

Available Arcane Enhancements

<h3 id="get__arcanes_search_{query}-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|query|path|string(utf8)|true|Keyword to search for|

> Example responses

> 200 Response

```json
{
  "regex": "string",
  "name": "string",
  "effect": "string",
  "rarity": "string",
  "location": "string",
  "thumbnail": "string",
  "info": "string"
}
```

<h3 id="get__arcanes_search_{query}-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[arcane](#schemaarcane)|

<aside class="success">
This operation does not require authentication
</aside>

## get__conclave_search_{query}

> Code samples

`GET /conclave/search/{query}`

*Get conclave challenge data based on the query*

Data about conclave challenges

<h3 id="get__conclave_search_{query}-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|query|path|string(utf8)|true|Keyword to search for|

> Example responses

> 200 Response

```json
{
  "modes": {
    "PVPMODE_ALL": {
      "value": "string"
    },
    "PVPMODE_TEAMDEATHMATCH": {
      "value": "string"
    },
    "PVPMODE_NONE": {
      "value": "string"
    },
    "PVPMODE_CAPTURETHEFLAG": {
      "value": "string"
    },
    "PVPMODE_SPEEDBALL": {
      "value": "string"
    },
    "PVPMODE_DEATHMATCH": {
      "value": "string"
    }
  },
  "categories": {
    "PVPChallengeTypeCategory_DAILY_ROOT": {
      "value": "string"
    },
    "PVPChallengeTypeCategory_DAILY": {
      "value": "string"
    },
    "PVPChallengeTypeCategory_WEEKLY": {
      "value": "string"
    },
    "PVPChallengeTypeCategory_WEEKLY_ROOT": {
      "value": "string"
    },
    "PVPChallengeTypeCategory_MODEAFFECTOR": {
      "value": "string"
    }
  }
}
```

<h3 id="get__conclave_search_{query}-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[conclave](#schemaconclave)|

<aside class="success">
This operation does not require authentication
</aside>

## get__events_search_{query}

> Code samples

`GET /events/search/{query}`

*Get Event-specific Data based on the query*

Data about events

<h3 id="get__events_search_{query}-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|query|path|string(utf8)|true|Keyword to search for|

> Example responses

> 200 Response

```json
[
  {}
]
```

<h3 id="get__events_search_{query}-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[events](#schemaevents)|

<aside class="success">
This operation does not require authentication
</aside>

## get__factions_search_{query}

> Code samples

`GET /factions/search/{query}`

*Get Faction translation information based on the query.*

Strings for translating faction identifiers.

<h3 id="get__factions_search_{query}-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|query|path|string(utf8)|true|Keyword to search for|

> Example responses

> 200 Response

```json
{
  "FC_GRINEER": {
    "value": "string"
  },
  "FC_CORPUS": {
    "value": "string"
  },
  "FC_INFESTATION": {
    "value": "string"
  },
  "FC_CORRUPTED": {
    "value": "string"
  },
  "FC_OROKIN": {
    "value": "string"
  }
}
```

<h3 id="get__factions_search_{query}-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[factions](#schemafactions)|

<aside class="success">
This operation does not require authentication
</aside>

## get__fissureModifiers_search_{query}

> Code samples

`GET /fissureModifiers/search/{query}`

*Get Fissure Modifier translation data based on the query.*

Fissure translation identifiers

<h3 id="get__fissuremodifiers_search_{query}-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|query|path|string(utf8)|true|Keyword to search for|

> Example responses

> 200 Response

```json
{
  "VoidT1": {
    "num": 0,
    "value": "string"
  },
  "VoidT2": {
    "num": 0,
    "value": "string"
  },
  "VoidT3": {
    "num": 0,
    "value": "string"
  },
  "VoidT4": {
    "num": 0,
    "value": "string"
  }
}
```

<h3 id="get__fissuremodifiers_search_{query}-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[fissureModifiers](#schemafissuremodifiers)|

<aside class="success">
This operation does not require authentication
</aside>

## get__languages_search_{query}

> Code samples

`GET /languages/search/{query}`

*Get Language strings for Warframe based on the query.*

Get language strings to assist translation.

<h3 id="get__languages_search_{query}-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|query|path|string(utf8)|true|Keyword to search for|

> Example responses

> 200 Response

```json
{
  "languageKey": {
    "value": "string"
  }
}
```

<h3 id="get__languages_search_{query}-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[languages](#schemalanguages)|

<aside class="success">
This operation does not require authentication
</aside>

## get__missionTypes_search_{query}

> Code samples

`GET /missionTypes/search/{query}`

*Get MissionType Translation Keys based on the query*

Mission Type information to aid translating identifiers

<h3 id="get__missiontypes_search_{query}-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|query|path|string(utf8)|true|Keyword to search for|

> Example responses

> 200 Response

```json
{
  "MT_EXCAVATE": {
    "value": "string"
  },
  "MT_SABOTAGE": {
    "value": "string"
  },
  "MT_MOBILE_DEFENSE": {
    "value": "string"
  },
  "MT_ASSASSINATION": {
    "value": "string"
  },
  "MT_EXTERMINATION": {
    "value": "string"
  },
  "MT_HIVE": {
    "value": "string"
  },
  "MT_DEFENSE": {
    "value": "string"
  },
  "MT_TERRITORY": {
    "value": "string"
  },
  "MT_ARENA": {
    "value": "string"
  },
  "MT_PVP": {
    "value": "string"
  },
  "MT_RESCUE": {
    "value": "string"
  },
  "MT_INTEL": {
    "value": "string"
  },
  "MT_SURVIVAL": {
    "value": "string"
  },
  "MT_CAPTURE": {
    "value": "string"
  },
  "MT_SECTOR": {
    "value": "string"
  },
  "MT_RETRIEVAL": {
    "value": "string"
  },
  "MT_ASSAULT": {
    "value": "string"
  },
  "MT_EVACUATION": {
    "value": "string"
  }
}
```

<h3 id="get__missiontypes_search_{query}-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[missionTypes](#schemamissiontypes)|

<aside class="success">
This operation does not require authentication
</aside>

## get__operationTypes_search_{query}

> Code samples

`GET /operationTypes/search/{query}`

*Get operation types data based on the query.*

Operation Types information to aid translating identifiers for global upgrades

<h3 id="get__operationtypes_search_{query}-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|query|path|string(utf8)|true|Keyword to search for|

> Example responses

> 200 Response

```json
{
  "MULTIPLY": {
    "value": "string"
  }
}
```

<h3 id="get__operationtypes_search_{query}-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[operationTypes](#schemaoperationtypes)|

<aside class="success">
This operation does not require authentication
</aside>

## get__persistentEnemy_search_{query}

> Code samples

`GET /persistentEnemy/search/{query}`

*Get Persistent Enemy translation data based on the query.*

Persistent Enemy translation information for aiding translation of identifiers.

<h3 id="get__persistentenemy_search_{query}-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|query|path|string(utf8)|true|Keyword to search for|

> Example responses

> 200 Response

```json
[
  {}
]
```

<h3 id="get__persistentenemy_search_{query}-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[persistentEnemies](#schemapersistentenemies)|

<aside class="success">
This operation does not require authentication
</aside>

## get__solNodes_search_{query}

> Code samples

`GET /solNodes/search/{query}`

*Get Sol Node information and translation data based on the query.*

Sol Node translation information for aiding the translation of identifiers.

<h3 id="get__solnodes_search_{query}-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|query|path|string(utf8)|true|Keyword to search for|

> Example responses

> 200 Response

```json
[
  {
    "nodes": [
      {
        "enemy": "string",
        "type": "string",
        "value": "string"
      }
    ],
    "keys": [
      "string"
    ]
  }
]
```

<h3 id="get__solnodes_search_{query}-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[solNodeSearch](#schemasolnodesearch)|

<aside class="success">
This operation does not require authentication
</aside>

## get__sortie_search_{query}

> Code samples

`GET /sortie/search/{query}`

*Get Sortie translation information based on the query.*

Sortie translation information for assisting translation of identifiers.

<h3 id="get__sortie_search_{query}-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|query|path|string(utf8)|true|Keyword to search for|

> Example responses

> 200 Response

```json
{
  "modifierTypes": {
    "SORTIE_MODIFIER_IMPACT": "string",
    "SORTIE_MODIFIER_HAZARD_COLD": "string",
    "SORTIE_MODIFIER_SECONDARY_ONLY": "string",
    "SORTIE_MODIFIER_TOXIN": "string",
    "SORTIE_MODIFIER_ELECTRICITY": "string",
    "SORTIE_MODIFIER_HAZARD_FOG": "string",
    "SORTIE_MODIFIER_HAZARD_MAGNETIC": "string",
    "SORTIE_MODIFIER_ARMOR": "string",
    "SORTIE_MODIFIER_CORROSIVE": "string",
    "SORTIE_MODIFIER_VIRAL": "string",
    "SORTIE_MODIFIER_HAZARD_RADIATION": "string",
    "SORTIE_MODIFIER_SLASH": "string",
    "SORTIE_MODIFIER_POISON": "string",
    "SORTIE_MODIFIER_GAS": "string",
    "SORTIE_MODIFIER_MAGNETIC": "string",
    "SORTIE_MODIFIER_FIRE": "string",
    "SORTIE_MODIFIER_SNIPER_ONLY": "string",
    "SORTIE_MODIFIER_PUNCTURE": "string",
    "SORTIE_MODIFIER_EXPLOSION": "string",
    "SORTIE_MODIFIER_BOW_ONLY": "string",
    "SORTIE_MODIFIER_RADIATION": "string",
    "SORTIE_MODIFIER_SHIELDS": "string",
    "SORTIE_MODIFIER_FREEZE": "string",
    "SORTIE_MODIFIER_HAZARD_FIRE": "string",
    "SORTIE_MODIFIER_EXIMUS": "string",
    "SORTIE_MODIFIER_SHOTGUN_ONLY": "string",
    "SORTIE_MODIFIER_MELEE_ONLY": "string",
    "SORTIE_MODIFIER_RIFLE_ONLY": "string",
    "SORTIE_MODIFIER_HAZARD_ICE": "string",
    "SORTIE_MODIFIER_LOW_ENERGY": "string"
  },
  "modifierDescriptions": {
    "SORTIE_MODIFIER_IMPACT": "string",
    "SORTIE_MODIFIER_HAZARD_COLD": "string",
    "SORTIE_MODIFIER_SECONDARY_ONLY": "string",
    "SORTIE_MODIFIER_TOXIN": "string",
    "SORTIE_MODIFIER_ELECTRICITY": "string",
    "SORTIE_MODIFIER_HAZARD_FOG": "string",
    "SORTIE_MODIFIER_HAZARD_MAGNETIC": "string",
    "SORTIE_MODIFIER_ARMOR": "string",
    "SORTIE_MODIFIER_CORROSIVE": "string",
    "SORTIE_MODIFIER_VIRAL": "string",
    "SORTIE_MODIFIER_HAZARD_RADIATION": "string",
    "SORTIE_MODIFIER_SLASH": "string",
    "SORTIE_MODIFIER_POISON": "string",
    "SORTIE_MODIFIER_GAS": "string",
    "SORTIE_MODIFIER_MAGNETIC": "string",
    "SORTIE_MODIFIER_FIRE": "string",
    "SORTIE_MODIFIER_SNIPER_ONLY": "string",
    "SORTIE_MODIFIER_PUNCTURE": "string",
    "SORTIE_MODIFIER_EXPLOSION": "string",
    "SORTIE_MODIFIER_BOW_ONLY": "string",
    "SORTIE_MODIFIER_RADIATION": "string",
    "SORTIE_MODIFIER_SHIELDS": "string",
    "SORTIE_MODIFIER_FREEZE": "string",
    "SORTIE_MODIFIER_HAZARD_FIRE": "string",
    "SORTIE_MODIFIER_EXIMUS": "string",
    "SORTIE_MODIFIER_SHOTGUN_ONLY": "string",
    "SORTIE_MODIFIER_MELEE_ONLY": "string",
    "SORTIE_MODIFIER_RIFLE_ONLY": "string",
    "SORTIE_MODIFIER_HAZARD_ICE": "string",
    "SORTIE_MODIFIER_LOW_ENERGY": "string"
  },
  "bosses": {
    "SORTIE_BOSS_KELA": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_AMBULAS": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_TYL": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_ALAD": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_RUK": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_HYENA": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_KRIL": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_CORRUPTED_VOR": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_INFALAD": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_PHORID": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_JACKAL": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_RAPTOR": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_VOR": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_HEK": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_NEF": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_LEPHANTIS": {
      "faction": "string",
      "name": "string"
    }
  },
  "endStates": [
    {
      "regions": [
        {
          "missions": [
            {}
          ],
          "name": "string"
        }
      ],
      "bossName": "string"
    }
  ],
  "modifiers": [
    {}
  ]
}
```

<h3 id="get__sortie_search_{query}-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[sortieData](#schemasortiedata)|

<aside class="success">
This operation does not require authentication
</aside>

## get__syndicates_search_{query}

> Code samples

`GET /syndicates/search/{query}`

*Get Syndicate translation data based on the query.*

Information to assist translating syndicate identifiers.

<h3 id="get__syndicates_search_{query}-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|query|path|string(utf8)|true|Keyword to search for|

> Example responses

> 200 Response

```json
{
  "ArbitersSyndicate": {
    "name": "string"
  },
  "CephalonSudaSyndicate": {
    "name": "string"
  },
  "NewLokaSyndicate": {
    "name": "string"
  },
  "PerrinSyndicate": {
    "name": "string"
  },
  "SteelMeridianSyndicate": {
    "name": "string"
  },
  "RedVeilSyndicate": {
    "name": "string"
  },
  "CetusSyndicate": {
    "name": "string"
  },
  "QuillsSyndicate": {
    "name": "string"
  },
  "AssassinsSyndicate": {
    "name": "string"
  },
  "EventSyndicate": {
    "name": "string"
  }
}
```

<h3 id="get__syndicates_search_{query}-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[syndicates](#schemasyndicates)|

<aside class="success">
This operation does not require authentication
</aside>

## get__tutorials_search_{query}

> Code samples

`GET /tutorials/search/{query}`

*Get Tutorials Data based on the query*

Tutorials data from DE

<h3 id="get__tutorials_search_{query}-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|query|path|string(utf8)|true|Keyword to search for|

> Example responses

> 200 Response

```json
[
  {
    "regex": "string",
    "name": "string",
    "url": "string"
  }
]
```

<h3 id="get__tutorials_search_{query}-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[tutorials](#schematutorials)|

<aside class="success">
This operation does not require authentication
</aside>

## get__upgradeTypes_search_{query}

> Code samples

`GET /upgradeTypes/search/{query}`

*Get upgrade types data for global upgrades based on the query.*

Upgrade types for what can be changed by global modifiers, such as double credit weekends.

<h3 id="get__upgradetypes_search_{query}-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|query|path|string(utf8)|true|Keyword to search for|

> Example responses

> 200 Response

```json
{
  "GAMEPLAY_KILL_XP_AMOUNT": {
    "value": "string"
  },
  "GAMEPLAY_PICKUP_AMOUNT": {
    "value": "string"
  },
  "GAMEPLAY_MONEY_REWARD_AMOUNT": {
    "value": "string"
  },
  "GAMEPLAY_MONEY_PICKUP_AMOUNT": {
    "value": "string"
  }
}
```

<h3 id="get__upgradetypes_search_{query}-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[upgradeTypes](#schemaupgradetypes)|

<aside class="success">
This operation does not require authentication
</aside>

## get__warframes_search_{query}

> Code samples

`GET /warframes/search/{query}`

*Get Warframe specs and data, such as polarities defenses, and profile based on the query.*

Warframe stats and general information.

<h3 id="get__warframes_search_{query}-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|query|path|string(utf8)|true|Keyword to search for|

> Example responses

> 200 Response

```json
[
  {
    "shield": "string",
    "polarities": [
      {}
    ],
    "prime_power": "string",
    "prime_mr": "string",
    "color": 0,
    "prime_polarities": [
      {}
    ],
    "conclave": "string",
    "description": "string",
    "prime_armor": "string",
    "speed": "string",
    "aura": "string",
    "prime_url": "string",
    "prime_health": "string",
    "power": "string",
    "prime_aura": "string",
    "info": "string",
    "thumbnail": "string",
    "mr": "string",
    "prime_shield": "string",
    "health": "string",
    "prime_speed": "string",
    "url": "string",
    "regex": "string",
    "armor": "string",
    "name": "string",
    "location": "string",
    "prime_conclave": "string"
  }
]
```

<h3 id="get__warframes_search_{query}-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[warframes](#schemawarframes)|

<aside class="success">
This operation does not require authentication
</aside>

## get__weapons_search_{query}

> Code samples

`GET /weapons/search/{query}`

*Get Weapon data and statistics based on the query.*

Weapon statistics.

<h3 id="get__weapons_search_{query}-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|query|path|string(utf8)|true|Keyword to search for|

> Example responses

> 200 Response

```json
[
  {
    "name": "string",
    "uniqueName": "string",
    "secondsPerShot": 0,
    "dmagePerShot": [
      0
    ],
    "magazineSize": 0,
    "reloadTime": 0,
    "totalDamage": 0,
    "damagePerSecond": 0,
    "trigger": "string",
    "description": "string",
    "accuracy": 0,
    "criticalChance": 0,
    "criticalMultiplier": 0,
    "procChance": 0,
    "fireRate": 0,
    "slot": 0,
    "noise": "string",
    "sentinel": true,
    "masteryReq": 0,
    "omegaAttenuation": 0,
    "type": "string",
    "buildPrice": 0,
    "buildTime": 0,
    "skipBuildTimePrice": 0,
    "buildQuantity": 0,
    "consumeOnBuild": true,
    "components": {
      "name": "string",
      "uniqueName": "string"
    },
    "imageName": "string",
    "category": "string",
    "tradable": true,
    "patchlogs": {
      "name": "string",
      "date": "string",
      "url": "string",
      "additions": "string",
      "changes": "string",
      "fixes": "string"
    },
    "ammo": 0,
    "damage": 0,
    "damageTypes": {
      "impact": 0,
      "puncture": 0,
      "slash": 0,
      "heat": 0,
      "cold": 0,
      "electric": 0,
      "toxin": 0,
      "gas": 0,
      "viral": 0,
      "corrosive": 0,
      "blast": 0,
      "magnetic": 0,
      "radiation": 0,
      "true": 0,
      "void": 0
    },
    "flight": 0,
    "polarities": "Vazarin",
    "projectile": "string",
    "tags": [
      "string"
    ],
    "vaulted": true,
    "wikiaThumbnail": "string",
    "wikiaUrl": "string",
    "disposition": 0,
    "releaseDate": "string",
    "vaultDate": "string"
  }
]
```

<h3 id="get__weapons_search_{query}-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[weapons](#schemaweapons)|

<aside class="success">
This operation does not require authentication
</aside>

## get__drops_search_{query}

> Code samples

`GET /drops/search/{query}`

*Get Warframe Drops data*

Percentages for Warframe drops in different areas of the game

<h3 id="get__drops_search_{query}-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|query|path|string(utf8)|true|Keyword to search for|

> Example responses

> 200 Response

```json
[
  {
    "item": "string",
    "chance": 0,
    "place": "string",
    "rarity": "string"
  }
]
```

<h3 id="get__drops_search_{query}-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[drops](#schemadrops)|

<aside class="success">
This operation does not require authentication
</aside>

## get__items_search_{query}

> Code samples

`GET /items/search/{query}`

*Get Warframe Items data*

Item information, such as name, unique name, type, and image name.

<h3 id="get__items_search_{query}-parameters">Parameters</h3>

|Name|In|Type|Required|Description|
|---|---|---|---|---|
|query|path|string(utf8)|true|Keyword to search for|

> Example responses

> 200 Response

```json
[
  {
    "name": "string",
    "uniqueName": "string"
  }
]
```

<h3 id="get__items_search_{query}-responses">Responses</h3>

|Status|Meaning|Description|Schema|
|---|---|---|---|
|200|[OK](https://tools.ietf.org/html/rfc7231#section-6.3.1)|successful operation|[items](#schemaitems)|

<aside class="success">
This operation does not require authentication
</aside>

# Schemas

<h2 id="tocSfissures">fissures</h2>

<a id="schemafissures"></a>

```json
[
  {
    "node": "string",
    "expired": true,
    "eta": "string",
    "missionType": "string",
    "tier": "string",
    "tierNum": 0,
    "enemy": "string",
    "id": "string",
    "expiry": "string",
    "activation": "string"
  }
]

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|node|string|true|none|none|
|expired|boolean|true|none|none|
|eta|string|true|none|none|
|missionType|string|true|none|none|
|tier|string|true|none|none|
|tierNum|number|true|none|none|
|enemy|string|true|none|none|
|id|string|true|none|none|
|expiry|string|true|none|none|
|activation|string|true|none|none|

<h2 id="tocSpersistentenemies">persistentEnemies</h2>

<a id="schemapersistentenemies"></a>

```json
[
  {}
]

```

### Properties

*None*

<h2 id="tocSsyndicates">syndicates</h2>

<a id="schemasyndicates"></a>

```json
{
  "ArbitersSyndicate": {
    "name": "string"
  },
  "CephalonSudaSyndicate": {
    "name": "string"
  },
  "NewLokaSyndicate": {
    "name": "string"
  },
  "PerrinSyndicate": {
    "name": "string"
  },
  "SteelMeridianSyndicate": {
    "name": "string"
  },
  "RedVeilSyndicate": {
    "name": "string"
  },
  "CetusSyndicate": {
    "name": "string"
  },
  "QuillsSyndicate": {
    "name": "string"
  },
  "AssassinsSyndicate": {
    "name": "string"
  },
  "EventSyndicate": {
    "name": "string"
  }
}

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|ArbitersSyndicate|object|true|none|none|
|» name|string|true|none|none|
|CephalonSudaSyndicate|object|true|none|none|
|» name|string|true|none|none|
|NewLokaSyndicate|object|true|none|none|
|» name|string|true|none|none|
|PerrinSyndicate|object|true|none|none|
|» name|string|true|none|none|
|SteelMeridianSyndicate|object|true|none|none|
|» name|string|true|none|none|
|RedVeilSyndicate|object|true|none|none|
|» name|string|true|none|none|
|CetusSyndicate|object|true|none|none|
|» name|string|true|none|none|
|QuillsSyndicate|object|true|none|none|
|» name|string|true|none|none|
|AssassinsSyndicate|object|true|none|none|
|» name|string|true|none|none|
|EventSyndicate|object|true|none|none|
|» name|string|true|none|none|

<h2 id="tocSnightwavechallenge">nightwaveChallenge</h2>

<a id="schemanightwavechallenge"></a>

```json
{
  "id": "string",
  "activation": "string",
  "expiry": "string",
  "isDaily": true,
  "isElite": true,
  "title": "string",
  "desc": "string",
  "reputation": 0
}

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|id|string|false|none|none|
|activation|string|false|none|none|
|expiry|string|false|none|none|
|isDaily|boolean|false|none|none|
|isElite|boolean|false|none|none|
|title|string|false|none|none|
|desc|string|false|none|none|
|reputation|number|false|none|none|

<h2 id="tocSconclave">conclave</h2>

<a id="schemaconclave"></a>

```json
{
  "modes": {
    "PVPMODE_ALL": {
      "value": "string"
    },
    "PVPMODE_TEAMDEATHMATCH": {
      "value": "string"
    },
    "PVPMODE_NONE": {
      "value": "string"
    },
    "PVPMODE_CAPTURETHEFLAG": {
      "value": "string"
    },
    "PVPMODE_SPEEDBALL": {
      "value": "string"
    },
    "PVPMODE_DEATHMATCH": {
      "value": "string"
    }
  },
  "categories": {
    "PVPChallengeTypeCategory_DAILY_ROOT": {
      "value": "string"
    },
    "PVPChallengeTypeCategory_DAILY": {
      "value": "string"
    },
    "PVPChallengeTypeCategory_WEEKLY": {
      "value": "string"
    },
    "PVPChallengeTypeCategory_WEEKLY_ROOT": {
      "value": "string"
    },
    "PVPChallengeTypeCategory_MODEAFFECTOR": {
      "value": "string"
    }
  }
}

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|modes|object|true|none|none|
|» PVPMODE_ALL|object|true|none|none|
|»» value|string|true|none|none|
|» PVPMODE_TEAMDEATHMATCH|object|true|none|none|
|»» value|string|true|none|none|
|» PVPMODE_NONE|object|true|none|none|
|»» value|string|true|none|none|
|» PVPMODE_CAPTURETHEFLAG|object|true|none|none|
|»» value|string|true|none|none|
|» PVPMODE_SPEEDBALL|object|true|none|none|
|»» value|string|true|none|none|
|» PVPMODE_DEATHMATCH|object|true|none|none|
|»» value|string|true|none|none|
|» categories|object|true|none|none|
|»» PVPChallengeTypeCategory_DAILY_ROOT|object|true|none|none|
|»»» value|string|true|none|none|
|»» PVPChallengeTypeCategory_DAILY|object|true|none|none|
|»»» value|string|true|none|none|
|»» PVPChallengeTypeCategory_WEEKLY|object|true|none|none|
|»»» value|string|true|none|none|
|»» PVPChallengeTypeCategory_WEEKLY_ROOT|object|true|none|none|
|»»» value|string|true|none|none|
|»» PVPChallengeTypeCategory_MODEAFFECTOR|object|true|none|none|
|»»» value|string|true|none|none|

<h2 id="tocSupgradetypes">upgradeTypes</h2>

<a id="schemaupgradetypes"></a>

```json
{
  "GAMEPLAY_KILL_XP_AMOUNT": {
    "value": "string"
  },
  "GAMEPLAY_PICKUP_AMOUNT": {
    "value": "string"
  },
  "GAMEPLAY_MONEY_REWARD_AMOUNT": {
    "value": "string"
  },
  "GAMEPLAY_MONEY_PICKUP_AMOUNT": {
    "value": "string"
  }
}

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|GAMEPLAY_KILL_XP_AMOUNT|object|true|none|none|
|» value|string|true|none|none|
|GAMEPLAY_PICKUP_AMOUNT|object|true|none|none|
|» value|string|true|none|none|
|GAMEPLAY_MONEY_REWARD_AMOUNT|object|true|none|none|
|» value|string|true|none|none|
|GAMEPLAY_MONEY_PICKUP_AMOUNT|object|true|none|none|
|» value|string|true|none|none|

<h2 id="tocSplatform">platform</h2>

<a id="schemaplatform"></a>

```json
"pc"

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|*anonymous*|string|false|none|none|

#### Enumerated Values

|Property|Value|
|---|---|
|*anonymous*|pc|
|*anonymous*|ps4|
|*anonymous*|xb1|
|*anonymous*|swi|

<h2 id="tocSdrops">drops</h2>

<a id="schemadrops"></a>

```json
[
  {
    "item": "string",
    "chance": 0,
    "place": "string",
    "rarity": "string"
  }
]

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|item|string|true|none|none|
|chance|number|true|none|none|
|place|string|true|none|none|
|rarity|string|true|none|none|

<h2 id="tocSalert">alert</h2>

<a id="schemaalert"></a>

```json
[
  {
    "mission": {
      "reward": {
        "countedItems": [
          {
            "count": 0,
            "type": "string"
          }
        ],
        "thumbnail": "string",
        "color": 0,
        "credits": 0,
        "asString": "string",
        "items": [
          {}
        ],
        "itemString": "string"
      },
      "node": "string",
      "faction": "string",
      "maxEnemyLevel": 0,
      "minEnemyLevel": 0,
      "maxWaveNum": 0,
      "type": "string",
      "nightmare": true,
      "archwingRequired": true
    },
    "expired": true,
    "eta": "string",
    "id": "string",
    "expiry": "string",
    "activation": "string",
    "rewardTypes": [
      {}
    ]
  }
]

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|mission|object|false|none|none|
|» reward|object|true|none|none|
|»» countedItems|[object]|true|none|none|
|»»» count|number|true|none|none|
|»»» type|string|true|none|none|
|»» thumbnail|string|true|none|none|
|»» color|number|true|none|none|
|»» credits|number|true|none|none|
|»» asString|string|true|none|none|
|»» items|[object]|true|none|none|
|»» itemString|string|true|none|none|
|» node|string|true|none|none|
|» faction|string|true|none|none|
|» maxEnemyLevel|number|true|none|none|
|» minEnemyLevel|number|true|none|none|
|» maxWaveNum|number|true|none|none|
|» type|string|true|none|none|
|» nightmare|boolean|true|none|none|
|» archwingRequired|boolean|true|none|none|
|expired|boolean|true|none|none|
|eta|string|true|none|none|
|id|string|true|none|none|
|expiry|string|true|none|none|
|activation|string|true|none|none|
|rewardTypes|[object]|false|none|none|

<h2 id="tocSsyndicatemissions">syndicateMissions</h2>

<a id="schemasyndicatemissions"></a>

```json
[
  {
    "nodes": [
      {}
    ],
    "eta": "string",
    "jobs": [
      {}
    ],
    "syndicate": "string",
    "id": "string",
    "expiry": "string",
    "activation": "string"
  }
]

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|nodes|[object]|false|none|none|
|eta|string|true|none|none|
|jobs|[object]|false|none|none|
|syndicate|string|true|none|none|
|id|string|true|none|none|
|expiry|string|true|none|none|
|activation|string|true|none|none|

<h2 id="tocSconstruction">construction</h2>

<a id="schemaconstruction"></a>

```json
{
  "id": "string",
  "fomorianProgress": "string",
  "razorbackProgress": "string",
  "unknownProgress": "string"
}

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|id|string|true|none|none|
|fomorianProgress|string|true|none|none|
|razorbackProgress|string|true|none|none|
|unknownProgress|string|true|none|none|

<h2 id="tocSvoidtrader">voidTrader</h2>

<a id="schemavoidtrader"></a>

```json
{
  "id": "string",
  "activation": "string",
  "expiry": "string",
  "character": "string",
  "location": "string",
  "inventory": [
    {}
  ],
  "psId": "string",
  "active": true,
  "startString": "string",
  "endString": "string"
}

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|id|string|true|none|none|
|activation|string|true|none|none|
|expiry|string|true|none|none|
|character|string|true|none|none|
|location|string|true|none|none|
|inventory|[object]|true|none|none|
|psId|string|true|none|none|
|active|boolean|true|none|none|
|startString|string|true|none|none|
|endString|string|true|none|none|

<h2 id="tocSsortiedata">sortieData</h2>

<a id="schemasortiedata"></a>

```json
{
  "modifierTypes": {
    "SORTIE_MODIFIER_IMPACT": "string",
    "SORTIE_MODIFIER_HAZARD_COLD": "string",
    "SORTIE_MODIFIER_SECONDARY_ONLY": "string",
    "SORTIE_MODIFIER_TOXIN": "string",
    "SORTIE_MODIFIER_ELECTRICITY": "string",
    "SORTIE_MODIFIER_HAZARD_FOG": "string",
    "SORTIE_MODIFIER_HAZARD_MAGNETIC": "string",
    "SORTIE_MODIFIER_ARMOR": "string",
    "SORTIE_MODIFIER_CORROSIVE": "string",
    "SORTIE_MODIFIER_VIRAL": "string",
    "SORTIE_MODIFIER_HAZARD_RADIATION": "string",
    "SORTIE_MODIFIER_SLASH": "string",
    "SORTIE_MODIFIER_POISON": "string",
    "SORTIE_MODIFIER_GAS": "string",
    "SORTIE_MODIFIER_MAGNETIC": "string",
    "SORTIE_MODIFIER_FIRE": "string",
    "SORTIE_MODIFIER_SNIPER_ONLY": "string",
    "SORTIE_MODIFIER_PUNCTURE": "string",
    "SORTIE_MODIFIER_EXPLOSION": "string",
    "SORTIE_MODIFIER_BOW_ONLY": "string",
    "SORTIE_MODIFIER_RADIATION": "string",
    "SORTIE_MODIFIER_SHIELDS": "string",
    "SORTIE_MODIFIER_FREEZE": "string",
    "SORTIE_MODIFIER_HAZARD_FIRE": "string",
    "SORTIE_MODIFIER_EXIMUS": "string",
    "SORTIE_MODIFIER_SHOTGUN_ONLY": "string",
    "SORTIE_MODIFIER_MELEE_ONLY": "string",
    "SORTIE_MODIFIER_RIFLE_ONLY": "string",
    "SORTIE_MODIFIER_HAZARD_ICE": "string",
    "SORTIE_MODIFIER_LOW_ENERGY": "string"
  },
  "modifierDescriptions": {
    "SORTIE_MODIFIER_IMPACT": "string",
    "SORTIE_MODIFIER_HAZARD_COLD": "string",
    "SORTIE_MODIFIER_SECONDARY_ONLY": "string",
    "SORTIE_MODIFIER_TOXIN": "string",
    "SORTIE_MODIFIER_ELECTRICITY": "string",
    "SORTIE_MODIFIER_HAZARD_FOG": "string",
    "SORTIE_MODIFIER_HAZARD_MAGNETIC": "string",
    "SORTIE_MODIFIER_ARMOR": "string",
    "SORTIE_MODIFIER_CORROSIVE": "string",
    "SORTIE_MODIFIER_VIRAL": "string",
    "SORTIE_MODIFIER_HAZARD_RADIATION": "string",
    "SORTIE_MODIFIER_SLASH": "string",
    "SORTIE_MODIFIER_POISON": "string",
    "SORTIE_MODIFIER_GAS": "string",
    "SORTIE_MODIFIER_MAGNETIC": "string",
    "SORTIE_MODIFIER_FIRE": "string",
    "SORTIE_MODIFIER_SNIPER_ONLY": "string",
    "SORTIE_MODIFIER_PUNCTURE": "string",
    "SORTIE_MODIFIER_EXPLOSION": "string",
    "SORTIE_MODIFIER_BOW_ONLY": "string",
    "SORTIE_MODIFIER_RADIATION": "string",
    "SORTIE_MODIFIER_SHIELDS": "string",
    "SORTIE_MODIFIER_FREEZE": "string",
    "SORTIE_MODIFIER_HAZARD_FIRE": "string",
    "SORTIE_MODIFIER_EXIMUS": "string",
    "SORTIE_MODIFIER_SHOTGUN_ONLY": "string",
    "SORTIE_MODIFIER_MELEE_ONLY": "string",
    "SORTIE_MODIFIER_RIFLE_ONLY": "string",
    "SORTIE_MODIFIER_HAZARD_ICE": "string",
    "SORTIE_MODIFIER_LOW_ENERGY": "string"
  },
  "bosses": {
    "SORTIE_BOSS_KELA": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_AMBULAS": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_TYL": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_ALAD": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_RUK": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_HYENA": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_KRIL": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_CORRUPTED_VOR": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_INFALAD": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_PHORID": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_JACKAL": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_RAPTOR": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_VOR": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_HEK": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_NEF": {
      "faction": "string",
      "name": "string"
    },
    "SORTIE_BOSS_LEPHANTIS": {
      "faction": "string",
      "name": "string"
    }
  },
  "endStates": [
    {
      "regions": [
        {
          "missions": [
            {}
          ],
          "name": "string"
        }
      ],
      "bossName": "string"
    }
  ],
  "modifiers": [
    {}
  ]
}

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|modifierTypes|object|true|none|none|
|» SORTIE_MODIFIER_IMPACT|string|true|none|none|
|» SORTIE_MODIFIER_HAZARD_COLD|string|true|none|none|
|» SORTIE_MODIFIER_SECONDARY_ONLY|string|true|none|none|
|» SORTIE_MODIFIER_TOXIN|string|true|none|none|
|» SORTIE_MODIFIER_ELECTRICITY|string|true|none|none|
|» SORTIE_MODIFIER_HAZARD_FOG|string|true|none|none|
|» SORTIE_MODIFIER_HAZARD_MAGNETIC|string|true|none|none|
|» SORTIE_MODIFIER_ARMOR|string|true|none|none|
|» SORTIE_MODIFIER_CORROSIVE|string|true|none|none|
|» SORTIE_MODIFIER_VIRAL|string|true|none|none|
|» SORTIE_MODIFIER_HAZARD_RADIATION|string|true|none|none|
|» SORTIE_MODIFIER_SLASH|string|true|none|none|
|» SORTIE_MODIFIER_POISON|string|true|none|none|
|» SORTIE_MODIFIER_GAS|string|true|none|none|
|» SORTIE_MODIFIER_MAGNETIC|string|true|none|none|
|» SORTIE_MODIFIER_FIRE|string|true|none|none|
|» SORTIE_MODIFIER_SNIPER_ONLY|string|true|none|none|
|» SORTIE_MODIFIER_PUNCTURE|string|true|none|none|
|» SORTIE_MODIFIER_EXPLOSION|string|true|none|none|
|» SORTIE_MODIFIER_BOW_ONLY|string|true|none|none|
|» SORTIE_MODIFIER_RADIATION|string|true|none|none|
|» SORTIE_MODIFIER_SHIELDS|string|true|none|none|
|» SORTIE_MODIFIER_FREEZE|string|true|none|none|
|» SORTIE_MODIFIER_HAZARD_FIRE|string|true|none|none|
|» SORTIE_MODIFIER_EXIMUS|string|true|none|none|
|» SORTIE_MODIFIER_SHOTGUN_ONLY|string|true|none|none|
|» SORTIE_MODIFIER_MELEE_ONLY|string|true|none|none|
|» SORTIE_MODIFIER_RIFLE_ONLY|string|true|none|none|
|» SORTIE_MODIFIER_HAZARD_ICE|string|true|none|none|
|» SORTIE_MODIFIER_LOW_ENERGY|string|true|none|none|
|modifierDescriptions|object|true|none|none|
|» SORTIE_MODIFIER_IMPACT|string|true|none|none|
|» SORTIE_MODIFIER_HAZARD_COLD|string|true|none|none|
|» SORTIE_MODIFIER_SECONDARY_ONLY|string|true|none|none|
|» SORTIE_MODIFIER_TOXIN|string|true|none|none|
|» SORTIE_MODIFIER_ELECTRICITY|string|true|none|none|
|» SORTIE_MODIFIER_HAZARD_FOG|string|true|none|none|
|» SORTIE_MODIFIER_HAZARD_MAGNETIC|string|true|none|none|
|» SORTIE_MODIFIER_ARMOR|string|true|none|none|
|» SORTIE_MODIFIER_CORROSIVE|string|true|none|none|
|» SORTIE_MODIFIER_VIRAL|string|true|none|none|
|» SORTIE_MODIFIER_HAZARD_RADIATION|string|true|none|none|
|» SORTIE_MODIFIER_SLASH|string|true|none|none|
|» SORTIE_MODIFIER_POISON|string|true|none|none|
|» SORTIE_MODIFIER_GAS|string|true|none|none|
|» SORTIE_MODIFIER_MAGNETIC|string|true|none|none|
|» SORTIE_MODIFIER_FIRE|string|true|none|none|
|» SORTIE_MODIFIER_SNIPER_ONLY|string|true|none|none|
|» SORTIE_MODIFIER_PUNCTURE|string|true|none|none|
|» SORTIE_MODIFIER_EXPLOSION|string|true|none|none|
|» SORTIE_MODIFIER_BOW_ONLY|string|true|none|none|
|» SORTIE_MODIFIER_RADIATION|string|true|none|none|
|» SORTIE_MODIFIER_SHIELDS|string|true|none|none|
|» SORTIE_MODIFIER_FREEZE|string|true|none|none|
|» SORTIE_MODIFIER_HAZARD_FIRE|string|true|none|none|
|» SORTIE_MODIFIER_EXIMUS|string|true|none|none|
|» SORTIE_MODIFIER_SHOTGUN_ONLY|string|true|none|none|
|» SORTIE_MODIFIER_MELEE_ONLY|string|true|none|none|
|» SORTIE_MODIFIER_RIFLE_ONLY|string|true|none|none|
|» SORTIE_MODIFIER_HAZARD_ICE|string|true|none|none|
|» SORTIE_MODIFIER_LOW_ENERGY|string|true|none|none|
|bosses|object|true|none|none|
|» SORTIE_BOSS_KELA|object|true|none|none|
|»» faction|string|true|none|none|
|»» name|string|true|none|none|
|» SORTIE_BOSS_AMBULAS|object|true|none|none|
|»» faction|string|true|none|none|
|»» name|string|true|none|none|
|» SORTIE_BOSS_TYL|object|true|none|none|
|»» faction|string|true|none|none|
|»» name|string|true|none|none|
|» SORTIE_BOSS_ALAD|object|true|none|none|
|»» faction|string|true|none|none|
|»» name|string|true|none|none|
|» SORTIE_BOSS_RUK|object|true|none|none|
|»» faction|string|true|none|none|
|»» name|string|true|none|none|
|» SORTIE_BOSS_HYENA|object|true|none|none|
|»» faction|string|true|none|none|
|»» name|string|true|none|none|
|» SORTIE_BOSS_KRIL|object|true|none|none|
|»» faction|string|true|none|none|
|»» name|string|true|none|none|
|» SORTIE_BOSS_CORRUPTED_VOR|object|true|none|none|
|»» faction|string|true|none|none|
|»» name|string|true|none|none|
|» SORTIE_BOSS_INFALAD|object|true|none|none|
|»» faction|string|true|none|none|
|»» name|string|true|none|none|
|» SORTIE_BOSS_PHORID|object|true|none|none|
|»» faction|string|true|none|none|
|»» name|string|true|none|none|
|» SORTIE_BOSS_JACKAL|object|true|none|none|
|»» faction|string|true|none|none|
|»» name|string|true|none|none|
|» SORTIE_BOSS_RAPTOR|object|true|none|none|
|»» faction|string|true|none|none|
|»» name|string|true|none|none|
|» SORTIE_BOSS_VOR|object|true|none|none|
|»» faction|string|true|none|none|
|»» name|string|true|none|none|
|» SORTIE_BOSS_HEK|object|true|none|none|
|»» faction|string|true|none|none|
|»» name|string|true|none|none|
|» SORTIE_BOSS_NEF|object|true|none|none|
|»» faction|string|true|none|none|
|»» name|string|true|none|none|
|» SORTIE_BOSS_LEPHANTIS|object|true|none|none|
|»» faction|string|true|none|none|
|»» name|string|true|none|none|
|» endStates|[object]|true|none|none|
|»» regions|[object]|false|none|none|
|»»» missions|[object]|false|none|none|
|»»» name|string|true|none|none|
|»» bossName|string|true|none|none|
|» modifiers|[object]|true|none|none|

<h2 id="tocScetuscycle">cetusCycle</h2>

<a id="schemacetuscycle"></a>

```json
{
  "id": "string",
  "expiry": "string",
  "isDay": true,
  "timeLeft": "string",
  "isCetus": true
}

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|id|string|true|none|none|
|expiry|string|true|none|none|
|isDay|boolean|true|none|none|
|timeLeft|string|true|none|none|
|isCetus|boolean|true|none|none|

<h2 id="tocSws">ws</h2>

<a id="schemaws"></a>

```json
{
  "timestamp": "string",
  "news": [
    {
      "date": "string",
      "imageLink": "string",
      "eta": "string",
      "primeAccess": true,
      "stream": true,
      "translations": {
        "es": "string"
      },
      "link": "string",
      "update": true,
      "id": "string",
      "asString": "string",
      "message": "string",
      "priority": true
    }
  ],
  "events": [
    {}
  ],
  "alerts": [
    {
      "mission": {
        "reward": {
          "countedItems": [
            {
              "count": 0,
              "type": "string"
            }
          ],
          "thumbnail": "string",
          "color": 0,
          "credits": 0,
          "asString": "string",
          "items": [
            {}
          ],
          "itemString": "string"
        },
        "node": "string",
        "faction": "string",
        "maxEnemyLevel": 0,
        "minEnemyLevel": 0,
        "maxWaveNum": 0,
        "type": "string",
        "nightmare": true,
        "archwingRequired": true
      },
      "expired": true,
      "eta": "string",
      "id": "string",
      "expiry": "string",
      "activation": "string",
      "rewardTypes": [
        {}
      ]
    }
  ],
  "sortie": {
    "id": "string",
    "activation": "string",
    "expiry": "string",
    "rewardPool": "string",
    "variants": [
      {
        "node": "string",
        "boss": "string",
        "missionType": "string",
        "planet": "string",
        "modifier": "string",
        "modifierDescription": "string"
      }
    ],
    "boss": "string",
    "faction": "string",
    "expired": true,
    "eta": "string"
  },
  "syndicateMissions": [
    {
      "nodes": [
        {}
      ],
      "eta": "string",
      "jobs": [
        {}
      ],
      "syndicate": "string",
      "id": "string",
      "expiry": "string",
      "activation": "string"
    }
  ],
  "fissures": [
    {
      "node": "string",
      "expired": true,
      "eta": "string",
      "missionType": "string",
      "tier": "string",
      "tierNum": 0,
      "enemy": "string",
      "id": "string",
      "expiry": "string",
      "activation": "string"
    }
  ],
  "globalUpgrades": [
    {}
  ],
  "flashSales": [
    {
      "item": "string",
      "expired": true,
      "eta": "string",
      "discount": 0,
      "premiumOverride": 0,
      "isPopular": true,
      "expiry": "string",
      "id": "string",
      "isFeatured": true
    }
  ],
  "invasions": [
    {
      "defenderReward": {
        "countedItems": [
          {
            "count": 0,
            "type": "string"
          }
        ],
        "thumbnail": "string",
        "color": 0,
        "credits": 0,
        "asString": "string",
        "items": [
          {}
        ],
        "itemString": "string"
      },
      "attackingFaction": "string",
      "completion": 0,
      "attackerReward": {
        "countedItems": [
          {
            "count": 0,
            "type": "string"
          }
        ],
        "thumbnail": "string",
        "color": 0,
        "credits": 0,
        "asString": "string",
        "items": [
          {}
        ],
        "itemString": "string"
      },
      "count": 0,
      "completed": true,
      "requiredRuns": 0,
      "vsInfestation": true,
      "node": "string",
      "eta": "string",
      "defendingFaction": "string",
      "id": "string",
      "activation": "string",
      "rewardTypes": [
        {}
      ],
      "desc": "string"
    }
  ],
  "darkSectors": [
    {
      "defenderMOTD": "string",
      "deployerName": "string",
      "defenderDeployemntActivation": 0,
      "defenderName": "string",
      "deployerClan": "string",
      "isAlliance": true,
      "id": "string",
      "history": [
        {}
      ]
    }
  ],
  "voidTrader": {
    "id": "string",
    "activation": "string",
    "expiry": "string",
    "character": "string",
    "location": "string",
    "inventory": [
      {}
    ],
    "psId": "string",
    "active": true,
    "startString": "string",
    "endString": "string"
  },
  "dailyDeals": [
    {
      "sold": 0,
      "item": "string",
      "total": 0,
      "eta": "string",
      "originalPrice": 0,
      "salePrice": 0,
      "discount": 0,
      "expiry": "string",
      "id": "string"
    }
  ],
  "simaris": {
    "target": "string",
    "isTargetActive": true,
    "asString": "string"
  },
  "conclaveChallenges": [
    {
      "mode": "string",
      "amount": 0,
      "eta": "string",
      "expired": true,
      "endString": "string",
      "daily": true,
      "description": "string",
      "id": "string",
      "expiry": "string",
      "asString": "string",
      "category": "string",
      "rootChallenge": true
    }
  ],
  "persistentEnemies": [
    {}
  ],
  "earthCycle": {
    "id": 0,
    "expiry": "string",
    "isDay": true,
    "timeLeft": "string"
  },
  "cetusCycle": {
    "id": "string",
    "expiry": "string",
    "isDay": true,
    "timeLeft": "string",
    "isCetus": true
  },
  "constructionProgress": {
    "id": "string",
    "fomorianProgress": "string",
    "razorbackProgress": "string",
    "unknownProgress": "string"
  },
  "nightwave": {
    "id": "string",
    "activation": "string",
    "expiry": "string",
    "params": {},
    "rewardTypes": [
      "string"
    ],
    "season": 0,
    "tag": "string",
    "phase": 0,
    "possibleChallenges": [
      {
        "id": "string",
        "activation": "string",
        "expiry": "string",
        "isDaily": true,
        "isElite": true,
        "title": "string",
        "desc": "string",
        "reputation": 0
      }
    ],
    "activeChallenges": [
      {
        "id": "string",
        "activation": "string",
        "expiry": "string",
        "isDaily": true,
        "isElite": true,
        "title": "string",
        "desc": "string",
        "reputation": 0
      }
    ]
  }
}

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|timestamp|[timestamp](#schematimestamp)|true|none|none|
|news|[news](#schemanews)|true|none|none|
|events|[events](#schemaevents)|true|none|none|
|alerts|[alert](#schemaalert)|true|none|none|
|sortie|[sortie](#schemasortie)|true|none|none|
|syndicateMissions|[syndicateMissions](#schemasyndicatemissions)|true|none|none|
|fissures|[fissures](#schemafissures)|true|none|none|
|globalUpgrades|[globalUpgrades](#schemaglobalupgrades)|true|none|none|
|flashSales|[flashSales](#schemaflashsales)|true|none|none|
|invasions|[invasions](#schemainvasions)|true|none|none|
|darkSectors|[darkSectors](#schemadarksectors)|true|none|none|
|voidTrader|[voidTrader](#schemavoidtrader)|true|none|none|
|dailyDeals|[dailyDeals](#schemadailydeals)|true|none|none|
|simaris|[simaris](#schemasimaris)|true|none|none|
|conclaveChallenges|[conclaveChallenges](#schemaconclavechallenges)|true|none|none|
|persistentEnemies|[persistentEnemies](#schemapersistentenemies)|true|none|none|
|earthCycle|[earthCycle](#schemaearthcycle)|true|none|none|
|cetusCycle|[cetusCycle](#schemacetuscycle)|true|none|none|
|constructionProgress|[construction](#schemaconstruction)|true|none|none|
|nightwave|[nightwave](#schemanightwave)|false|none|none|

<h2 id="tocSearthcycle">earthCycle</h2>

<a id="schemaearthcycle"></a>

```json
{
  "id": 0,
  "expiry": "string",
  "isDay": true,
  "timeLeft": "string"
}

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|id|number|true|none|none|
|expiry|string|true|none|none|
|isDay|boolean|true|none|none|
|timeLeft|string|true|none|none|

<h2 id="tocSevents">events</h2>

<a id="schemaevents"></a>

```json
[
  {}
]

```

### Properties

*None*

<h2 id="tocSdarksectors">darkSectors</h2>

<a id="schemadarksectors"></a>

```json
[
  {
    "defenderMOTD": "string",
    "deployerName": "string",
    "defenderDeployemntActivation": 0,
    "defenderName": "string",
    "deployerClan": "string",
    "isAlliance": true,
    "id": "string",
    "history": [
      {}
    ]
  }
]

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|defenderMOTD|string|true|none|none|
|deployerName|string|true|none|none|
|defenderDeployemntActivation|number|true|none|none|
|defenderName|string|true|none|none|
|deployerClan|string|true|none|none|
|isAlliance|boolean|true|none|none|
|id|string|true|none|none|
|history|[object]|false|none|none|

<h2 id="tocSsolnode">solNode</h2>

<a id="schemasolnode"></a>

```json
{
  "SolKey": {
    "enemy": "string",
    "type": "string",
    "value": "string"
  }
}

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|SolKey|object|false|none|none|
|» enemy|string|true|none|none|
|» type|string|true|none|none|
|» value|string|true|none|none|

<h2 id="tocStimestamp">timestamp</h2>

<a id="schematimestamp"></a>

```json
"string"

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|*anonymous*|string|false|none|none|

<h2 id="tocSnews">news</h2>

<a id="schemanews"></a>

```json
[
  {
    "date": "string",
    "imageLink": "string",
    "eta": "string",
    "primeAccess": true,
    "stream": true,
    "translations": {
      "es": "string"
    },
    "link": "string",
    "update": true,
    "id": "string",
    "asString": "string",
    "message": "string",
    "priority": true
  }
]

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|date|string|true|none|none|
|imageLink|string|true|none|none|
|eta|string|true|none|none|
|primeAccess|boolean|true|none|none|
|stream|boolean|true|none|none|
|translations|object|false|none|none|
|» es|string|true|none|none|
|link|string|true|none|none|
|update|boolean|true|none|none|
|id|string|true|none|none|
|asString|string|true|none|none|
|message|string|true|none|none|
|priority|boolean|true|none|none|

<h2 id="tocSvalliscycle">vallisCycle</h2>

<a id="schemavalliscycle"></a>

```json
{
  "id": "string",
  "expiry": "string",
  "timeLeft": "string",
  "isWarm": true
}

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|id|string|true|none|none|
|expiry|string|true|none|none|
|timeLeft|string|true|none|none|
|isWarm|boolean|true|none|none|

<h2 id="tocSlanguages">languages</h2>

<a id="schemalanguages"></a>

```json
{
  "languageKey": {
    "value": "string"
  }
}

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|languageKey|object|false|none|none|
|» value|string|true|none|none|

<h2 id="tocSwarframes">warframes</h2>

<a id="schemawarframes"></a>

```json
[
  {
    "shield": "string",
    "polarities": [
      {}
    ],
    "prime_power": "string",
    "prime_mr": "string",
    "color": 0,
    "prime_polarities": [
      {}
    ],
    "conclave": "string",
    "description": "string",
    "prime_armor": "string",
    "speed": "string",
    "aura": "string",
    "prime_url": "string",
    "prime_health": "string",
    "power": "string",
    "prime_aura": "string",
    "info": "string",
    "thumbnail": "string",
    "mr": "string",
    "prime_shield": "string",
    "health": "string",
    "prime_speed": "string",
    "url": "string",
    "regex": "string",
    "armor": "string",
    "name": "string",
    "location": "string",
    "prime_conclave": "string"
  }
]

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|shield|string|true|none|none|
|polarities|[object]|true|none|none|
|prime_power|string|false|none|none|
|prime_mr|string|false|none|none|
|color|number|true|none|none|
|prime_polarities|[object]|false|none|none|
|conclave|string|true|none|none|
|description|string|true|none|none|
|prime_armor|string|false|none|none|
|speed|string|true|none|none|
|aura|string|true|none|none|
|prime_url|string|false|none|none|
|prime_health|string|false|none|none|
|power|string|true|none|none|
|prime_aura|string|false|none|none|
|info|string|true|none|none|
|thumbnail|string|true|none|none|
|mr|string|true|none|none|
|prime_shield|string|false|none|none|
|health|string|true|none|none|
|prime_speed|string|false|none|none|
|url|string|true|none|none|
|regex|string|true|none|none|
|armor|string|true|none|none|
|name|string|true|none|none|
|location|string|true|none|none|
|prime_conclave|string|false|none|none|

<h2 id="tocSmissiontypes">missionTypes</h2>

<a id="schemamissiontypes"></a>

```json
{
  "MT_EXCAVATE": {
    "value": "string"
  },
  "MT_SABOTAGE": {
    "value": "string"
  },
  "MT_MOBILE_DEFENSE": {
    "value": "string"
  },
  "MT_ASSASSINATION": {
    "value": "string"
  },
  "MT_EXTERMINATION": {
    "value": "string"
  },
  "MT_HIVE": {
    "value": "string"
  },
  "MT_DEFENSE": {
    "value": "string"
  },
  "MT_TERRITORY": {
    "value": "string"
  },
  "MT_ARENA": {
    "value": "string"
  },
  "MT_PVP": {
    "value": "string"
  },
  "MT_RESCUE": {
    "value": "string"
  },
  "MT_INTEL": {
    "value": "string"
  },
  "MT_SURVIVAL": {
    "value": "string"
  },
  "MT_CAPTURE": {
    "value": "string"
  },
  "MT_SECTOR": {
    "value": "string"
  },
  "MT_RETRIEVAL": {
    "value": "string"
  },
  "MT_ASSAULT": {
    "value": "string"
  },
  "MT_EVACUATION": {
    "value": "string"
  }
}

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|MT_EXCAVATE|object|true|none|none|
|» value|string|true|none|none|
|MT_SABOTAGE|object|true|none|none|
|» value|string|true|none|none|
|MT_MOBILE_DEFENSE|object|true|none|none|
|» value|string|true|none|none|
|MT_ASSASSINATION|object|true|none|none|
|» value|string|true|none|none|
|MT_EXTERMINATION|object|true|none|none|
|» value|string|true|none|none|
|MT_HIVE|object|true|none|none|
|» value|string|true|none|none|
|MT_DEFENSE|object|true|none|none|
|» value|string|true|none|none|
|MT_TERRITORY|object|true|none|none|
|» value|string|true|none|none|
|MT_ARENA|object|true|none|none|
|» value|string|true|none|none|
|MT_PVP|object|true|none|none|
|» value|string|true|none|none|
|MT_RESCUE|object|true|none|none|
|» value|string|true|none|none|
|MT_INTEL|object|true|none|none|
|» value|string|true|none|none|
|MT_SURVIVAL|object|true|none|none|
|» value|string|true|none|none|
|MT_CAPTURE|object|true|none|none|
|» value|string|true|none|none|
|MT_SECTOR|object|true|none|none|
|» value|string|true|none|none|
|MT_RETRIEVAL|object|true|none|none|
|» value|string|true|none|none|
|MT_ASSAULT|object|true|none|none|
|» value|string|true|none|none|
|MT_EVACUATION|object|true|none|none|
|» value|string|true|none|none|

<h2 id="tocSconclavechallenges">conclaveChallenges</h2>

<a id="schemaconclavechallenges"></a>

```json
[
  {
    "mode": "string",
    "amount": 0,
    "eta": "string",
    "expired": true,
    "endString": "string",
    "daily": true,
    "description": "string",
    "id": "string",
    "expiry": "string",
    "asString": "string",
    "category": "string",
    "rootChallenge": true
  }
]

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|mode|string|true|none|none|
|amount|number|true|none|none|
|eta|string|true|none|none|
|expired|boolean|true|none|none|
|endString|string|true|none|none|
|daily|boolean|true|none|none|
|description|string|true|none|none|
|id|string|true|none|none|
|expiry|string|true|none|none|
|asString|string|true|none|none|
|category|string|true|none|none|
|rootChallenge|boolean|true|none|none|

<h2 id="tocSnightwave">nightwave</h2>

<a id="schemanightwave"></a>

```json
{
  "id": "string",
  "activation": "string",
  "expiry": "string",
  "params": {},
  "rewardTypes": [
    "string"
  ],
  "season": 0,
  "tag": "string",
  "phase": 0,
  "possibleChallenges": [
    {
      "id": "string",
      "activation": "string",
      "expiry": "string",
      "isDaily": true,
      "isElite": true,
      "title": "string",
      "desc": "string",
      "reputation": 0
    }
  ],
  "activeChallenges": [
    {
      "id": "string",
      "activation": "string",
      "expiry": "string",
      "isDaily": true,
      "isElite": true,
      "title": "string",
      "desc": "string",
      "reputation": 0
    }
  ]
}

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|id|string|false|none|none|
|activation|string|false|none|none|
|expiry|string|false|none|none|
|params|object|false|none|none|
|rewardTypes|[string]|false|none|none|
|season|number|false|none|none|
|tag|string|false|none|none|
|phase|number|false|none|none|
|possibleChallenges|[[nightwaveChallenge](#schemanightwavechallenge)]|false|none|none|
|activeChallenges|[[nightwaveChallenge](#schemanightwavechallenge)]|false|none|none|

<h2 id="tocSglobalupgrades">globalUpgrades</h2>

<a id="schemaglobalupgrades"></a>

```json
[
  {}
]

```

### Properties

*None*

<h2 id="tocSfissuremodifiers">fissureModifiers</h2>

<a id="schemafissuremodifiers"></a>

```json
{
  "VoidT1": {
    "num": 0,
    "value": "string"
  },
  "VoidT2": {
    "num": 0,
    "value": "string"
  },
  "VoidT3": {
    "num": 0,
    "value": "string"
  },
  "VoidT4": {
    "num": 0,
    "value": "string"
  }
}

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|VoidT1|object|true|none|none|
|» num|number|true|none|none|
|» value|string|true|none|none|
|VoidT2|object|true|none|none|
|» num|number|true|none|none|
|» value|string|true|none|none|
|VoidT3|object|true|none|none|
|» num|number|true|none|none|
|» value|string|true|none|none|
|VoidT4|object|true|none|none|
|» num|number|true|none|none|
|» value|string|true|none|none|

<h2 id="tocSflashsales">flashSales</h2>

<a id="schemaflashsales"></a>

```json
[
  {
    "item": "string",
    "expired": true,
    "eta": "string",
    "discount": 0,
    "premiumOverride": 0,
    "isPopular": true,
    "expiry": "string",
    "id": "string",
    "isFeatured": true
  }
]

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|item|string|true|none|none|
|expired|boolean|true|none|none|
|eta|string|true|none|none|
|discount|number|true|none|none|
|premiumOverride|number|true|none|none|
|isPopular|boolean|true|none|none|
|expiry|string|true|none|none|
|id|string|true|none|none|
|isFeatured|boolean|true|none|none|

<h2 id="tocSdailydeals">dailyDeals</h2>

<a id="schemadailydeals"></a>

```json
[
  {
    "sold": 0,
    "item": "string",
    "total": 0,
    "eta": "string",
    "originalPrice": 0,
    "salePrice": 0,
    "discount": 0,
    "expiry": "string",
    "id": "string"
  }
]

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|sold|number|true|none|none|
|item|string|true|none|none|
|total|number|true|none|none|
|eta|string|true|none|none|
|originalPrice|number|true|none|none|
|salePrice|number|true|none|none|
|discount|number|true|none|none|
|expiry|string|true|none|none|
|id|string|true|none|none|

<h2 id="tocSsolnodesearch">solNodeSearch</h2>

<a id="schemasolnodesearch"></a>

```json
[
  {
    "nodes": [
      {
        "enemy": "string",
        "type": "string",
        "value": "string"
      }
    ],
    "keys": [
      "string"
    ]
  }
]

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|nodes|[object]|true|none|none|
|» enemy|string|true|none|none|
|» type|string|true|none|none|
|» value|string|true|none|none|
|keys|[string]|true|none|none|

<h2 id="tocSoperationtypes">operationTypes</h2>

<a id="schemaoperationtypes"></a>

```json
{
  "MULTIPLY": {
    "value": "string"
  }
}

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|MULTIPLY|object|true|none|none|
|» value|string|true|none|none|

<h2 id="tocSfactions">factions</h2>

<a id="schemafactions"></a>

```json
{
  "FC_GRINEER": {
    "value": "string"
  },
  "FC_CORPUS": {
    "value": "string"
  },
  "FC_INFESTATION": {
    "value": "string"
  },
  "FC_CORRUPTED": {
    "value": "string"
  },
  "FC_OROKIN": {
    "value": "string"
  }
}

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|FC_GRINEER|object|true|none|none|
|» value|string|true|none|none|
|FC_CORPUS|object|true|none|none|
|» value|string|true|none|none|
|FC_INFESTATION|object|true|none|none|
|» value|string|true|none|none|
|FC_CORRUPTED|object|true|none|none|
|» value|string|true|none|none|
|FC_OROKIN|object|true|none|none|
|» value|string|true|none|none|

<h2 id="tocSinvasions">invasions</h2>

<a id="schemainvasions"></a>

```json
[
  {
    "defenderReward": {
      "countedItems": [
        {
          "count": 0,
          "type": "string"
        }
      ],
      "thumbnail": "string",
      "color": 0,
      "credits": 0,
      "asString": "string",
      "items": [
        {}
      ],
      "itemString": "string"
    },
    "attackingFaction": "string",
    "completion": 0,
    "attackerReward": {
      "countedItems": [
        {
          "count": 0,
          "type": "string"
        }
      ],
      "thumbnail": "string",
      "color": 0,
      "credits": 0,
      "asString": "string",
      "items": [
        {}
      ],
      "itemString": "string"
    },
    "count": 0,
    "completed": true,
    "requiredRuns": 0,
    "vsInfestation": true,
    "node": "string",
    "eta": "string",
    "defendingFaction": "string",
    "id": "string",
    "activation": "string",
    "rewardTypes": [
      {}
    ],
    "desc": "string"
  }
]

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|defenderReward|object|false|none|none|
|» countedItems|[object]|true|none|none|
|»» count|number|true|none|none|
|»» type|string|true|none|none|
|» thumbnail|string|true|none|none|
|» color|number|true|none|none|
|» credits|number|true|none|none|
|» asString|string|true|none|none|
|» items|[object]|true|none|none|
|» itemString|string|true|none|none|
|attackingFaction|string|true|none|none|
|completion|number|true|none|none|
|attackerReward|object|false|none|none|
|» countedItems|[object]|true|none|none|
|»» count|number|true|none|none|
|»» type|string|true|none|none|
|» thumbnail|string|true|none|none|
|» color|number|true|none|none|
|» credits|number|true|none|none|
|» asString|string|true|none|none|
|» items|[object]|true|none|none|
|» itemString|string|true|none|none|
|count|number|true|none|none|
|completed|boolean|true|none|none|
|requiredRuns|number|true|none|none|
|vsInfestation|boolean|true|none|none|
|node|string|true|none|none|
|eta|string|true|none|none|
|defendingFaction|string|true|none|none|
|id|string|true|none|none|
|activation|string|true|none|none|
|rewardTypes|[object]|false|none|none|
|desc|string|true|none|none|

<h2 id="tocStutorials">tutorials</h2>

<a id="schematutorials"></a>

```json
[
  {
    "regex": "string",
    "name": "string",
    "url": "string"
  }
]

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|regex|string|true|none|none|
|name|string|true|none|none|
|url|string|true|none|none|

<h2 id="tocSsortie">sortie</h2>

<a id="schemasortie"></a>

```json
{
  "id": "string",
  "activation": "string",
  "expiry": "string",
  "rewardPool": "string",
  "variants": [
    {
      "node": "string",
      "boss": "string",
      "missionType": "string",
      "planet": "string",
      "modifier": "string",
      "modifierDescription": "string"
    }
  ],
  "boss": "string",
  "faction": "string",
  "expired": true,
  "eta": "string"
}

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|id|string|true|none|none|
|activation|string|true|none|none|
|expiry|string|true|none|none|
|rewardPool|string|true|none|none|
|variants|[object]|true|none|none|
|» node|string|true|none|none|
|» boss|string|true|none|none|
|» missionType|string|true|none|none|
|» planet|string|true|none|none|
|» modifier|string|true|none|none|
|» modifierDescription|string|true|none|none|
|boss|string|true|none|none|
|faction|string|true|none|none|
|expired|boolean|true|none|none|
|eta|string|true|none|none|

<h2 id="tocSsimaris">simaris</h2>

<a id="schemasimaris"></a>

```json
{
  "target": "string",
  "isTargetActive": true,
  "asString": "string"
}

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|target|string|true|none|none|
|isTargetActive|boolean|true|none|none|
|asString|string|true|none|none|

<h2 id="tocSarcane">arcane</h2>

<a id="schemaarcane"></a>

```json
{
  "regex": "string",
  "name": "string",
  "effect": "string",
  "rarity": "string",
  "location": "string",
  "thumbnail": "string",
  "info": "string"
}

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|regex|string|true|none|none|
|name|string|true|none|none|
|effect|string|true|none|none|
|rarity|string|true|none|none|
|location|string|true|none|none|
|thumbnail|string|true|none|none|
|info|string|true|none|none|

<h2 id="tocSprimaryweapon">primaryWeapon</h2>

<a id="schemaprimaryweapon"></a>

```json
{
  "name": "string",
  "uniqueName": "string",
  "secondsPerShot": 0,
  "dmagePerShot": [
    0
  ],
  "magazineSize": 0,
  "reloadTime": 0,
  "totalDamage": 0,
  "damagePerSecond": 0,
  "trigger": "string",
  "description": "string",
  "accuracy": 0,
  "criticalChance": 0,
  "criticalMultiplier": 0,
  "procChance": 0,
  "fireRate": 0,
  "slot": 0,
  "noise": "string",
  "sentinel": true,
  "masteryReq": 0,
  "omegaAttenuation": 0,
  "type": "string",
  "buildPrice": 0,
  "buildTime": 0,
  "skipBuildTimePrice": 0,
  "buildQuantity": 0,
  "consumeOnBuild": true,
  "components": {
    "name": "string",
    "uniqueName": "string"
  },
  "imageName": "string",
  "category": "string",
  "tradable": true,
  "patchlogs": {
    "name": "string",
    "date": "string",
    "url": "string",
    "additions": "string",
    "changes": "string",
    "fixes": "string"
  },
  "ammo": 0,
  "damage": 0,
  "damageTypes": {
    "impact": 0,
    "puncture": 0,
    "slash": 0,
    "heat": 0,
    "cold": 0,
    "electric": 0,
    "toxin": 0,
    "gas": 0,
    "viral": 0,
    "corrosive": 0,
    "blast": 0,
    "magnetic": 0,
    "radiation": 0,
    "true": 0,
    "void": 0
  },
  "flight": 0,
  "polarities": "Vazarin",
  "projectile": "string",
  "tags": [
    "string"
  ],
  "vaulted": true,
  "wikiaThumbnail": "string",
  "wikiaUrl": "string",
  "disposition": 0,
  "releaseDate": "string",
  "vaultDate": "string"
}

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|name|string|false|none|none|
|uniqueName|string|false|none|none|
|secondsPerShot|number|false|none|none|
|dmagePerShot|[number]|false|none|none|
|magazineSize|number|false|none|none|
|reloadTime|number|false|none|none|
|totalDamage|number|false|none|none|
|damagePerSecond|number|false|none|none|
|trigger|string|false|none|none|
|description|string|false|none|none|
|accuracy|number|false|none|none|
|criticalChance|number|false|none|none|
|criticalMultiplier|number|false|none|none|
|procChance|number|false|none|none|
|fireRate|number|false|none|none|
|slot|number|false|none|none|
|noise|string|false|none|none|
|sentinel|boolean|false|none|none|
|masteryReq|number|false|none|none|
|omegaAttenuation|number|false|none|none|
|type|string|false|none|none|
|buildPrice|number|false|none|none|
|buildTime|number|false|none|none|
|skipBuildTimePrice|number|false|none|none|
|buildQuantity|number|false|none|none|
|consumeOnBuild|boolean|false|none|none|
|components|[item](#schemaitem)|false|none|none|
|imageName|string|false|none|none|
|category|string|false|none|none|
|tradable|boolean|false|none|none|
|patchlogs|[patchlog](#schemapatchlog)|false|none|none|
|ammo|number|false|none|none|
|damage|number|false|none|none|
|damageTypes|object|false|none|none|
|» impact|number|false|none|none|
|» puncture|number|false|none|none|
|» slash|number|false|none|none|
|» heat|number|false|none|none|
|» cold|number|false|none|none|
|» electric|number|false|none|none|
|» toxin|number|false|none|none|
|» gas|number|false|none|none|
|» viral|number|false|none|none|
|» corrosive|number|false|none|none|
|» blast|number|false|none|none|
|» magnetic|number|false|none|none|
|» radiation|number|false|none|none|
|» true|number|false|none|none|
|» void|number|false|none|none|
|flight|number|false|none|none|
|polarities|[polarity](#schemapolarity)|false|none|none|
|projectile|string|false|none|none|
|tags|[string]|false|none|none|
|vaulted|boolean|false|none|none|
|wikiaThumbnail|string|false|none|none|
|wikiaUrl|string|false|none|none|
|disposition|number|false|none|none|
|releaseDate|string|false|none|none|
|vaultDate|string|false|none|none|

<h2 id="tocSsecondaryweapon">secondaryWeapon</h2>

<a id="schemasecondaryweapon"></a>

```json
{
  "name": "string",
  "uniqueName": "string",
  "secondsPerShot": 0,
  "dmagePerShot": [
    0
  ],
  "magazineSize": 0,
  "reloadTime": 0,
  "totalDamage": 0,
  "damagePerSecond": 0,
  "trigger": "string",
  "description": "string",
  "accuracy": 0,
  "criticalChance": 0,
  "criticalMultiplier": 0,
  "procChance": 0,
  "fireRate": 0,
  "slot": 0,
  "noise": "string",
  "sentinel": true,
  "masteryReq": 0,
  "omegaAttenuation": 0,
  "type": "string",
  "buildPrice": 0,
  "buildTime": 0,
  "skipBuildTimePrice": 0,
  "buildQuantity": 0,
  "consumeOnBuild": true,
  "components": {
    "name": "string",
    "uniqueName": "string"
  },
  "imageName": "string",
  "category": "string",
  "tradable": true,
  "patchlogs": {
    "name": "string",
    "date": "string",
    "url": "string",
    "additions": "string",
    "changes": "string",
    "fixes": "string"
  },
  "ammo": 0,
  "damage": 0,
  "damageTypes": {
    "impact": 0,
    "puncture": 0,
    "slash": 0,
    "heat": 0,
    "cold": 0,
    "electric": 0,
    "toxin": 0,
    "gas": 0,
    "viral": 0,
    "corrosive": 0,
    "blast": 0,
    "magnetic": 0,
    "radiation": 0,
    "true": 0,
    "void": 0
  },
  "flight": 0,
  "polarities": "Vazarin",
  "projectile": "string",
  "tags": [
    "string"
  ],
  "vaulted": true,
  "wikiaThumbnail": "string",
  "wikiaUrl": "string",
  "disposition": 0,
  "releaseDate": "string",
  "vaultDate": "string"
}

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|name|string|false|none|none|
|uniqueName|string|false|none|none|
|secondsPerShot|number|false|none|none|
|dmagePerShot|[number]|false|none|none|
|magazineSize|number|false|none|none|
|reloadTime|number|false|none|none|
|totalDamage|number|false|none|none|
|damagePerSecond|number|false|none|none|
|trigger|string|false|none|none|
|description|string|false|none|none|
|accuracy|number|false|none|none|
|criticalChance|number|false|none|none|
|criticalMultiplier|number|false|none|none|
|procChance|number|false|none|none|
|fireRate|number|false|none|none|
|slot|number|false|none|none|
|noise|string|false|none|none|
|sentinel|boolean|false|none|none|
|masteryReq|number|false|none|none|
|omegaAttenuation|number|false|none|none|
|type|string|false|none|none|
|buildPrice|number|false|none|none|
|buildTime|number|false|none|none|
|skipBuildTimePrice|number|false|none|none|
|buildQuantity|number|false|none|none|
|consumeOnBuild|boolean|false|none|none|
|components|[item](#schemaitem)|false|none|none|
|imageName|string|false|none|none|
|category|string|false|none|none|
|tradable|boolean|false|none|none|
|patchlogs|[patchlog](#schemapatchlog)|false|none|none|
|ammo|number|false|none|none|
|damage|number|false|none|none|
|damageTypes|object|false|none|none|
|» impact|number|false|none|none|
|» puncture|number|false|none|none|
|» slash|number|false|none|none|
|» heat|number|false|none|none|
|» cold|number|false|none|none|
|» electric|number|false|none|none|
|» toxin|number|false|none|none|
|» gas|number|false|none|none|
|» viral|number|false|none|none|
|» corrosive|number|false|none|none|
|» blast|number|false|none|none|
|» magnetic|number|false|none|none|
|» radiation|number|false|none|none|
|» true|number|false|none|none|
|» void|number|false|none|none|
|flight|number|false|none|none|
|polarities|[polarity](#schemapolarity)|false|none|none|
|projectile|string|false|none|none|
|tags|[string]|false|none|none|
|vaulted|boolean|false|none|none|
|wikiaThumbnail|string|false|none|none|
|wikiaUrl|string|false|none|none|
|disposition|number|false|none|none|
|releaseDate|string|false|none|none|
|vaultDate|string|false|none|none|

<h2 id="tocSmeleeweapon">meleeWeapon</h2>

<a id="schemameleeweapon"></a>

```json
{
  "name": "string",
  "uniqueName": "string",
  "secondsPerShot": 0,
  "totalDamage": 0,
  "damagePerSecond": 0,
  "trigger": "string",
  "description": "string",
  "accuracy": 0,
  "criticalChance": 0,
  "criticalMultiplier": 0,
  "procChance": 0,
  "fireRate": 0,
  "chargeAttack": 0,
  "spinAttack": 0,
  "leapAttack": 0,
  "wallAttack": 0,
  "slot": 0,
  "noise": "string",
  "sentinel": true,
  "masteryReq": 0,
  "omegaAttenuation": 0,
  "type": "string",
  "buildPrice": 0,
  "buildTime": 0,
  "skipBuildTimePrice": 0,
  "buildQuantity": 0,
  "consumeOnBuild": true,
  "components": {
    "name": "string",
    "uniqueName": "string"
  },
  "imageName": "string",
  "category": "string",
  "tradable": true,
  "patchlogs": {
    "name": "string",
    "date": "string",
    "url": "string",
    "additions": "string",
    "changes": "string",
    "fixes": "string"
  },
  "ammo": 0,
  "damage": 0,
  "damageTypes": {
    "impact": 0,
    "puncture": 0,
    "slash": 0,
    "heat": 0,
    "cold": 0,
    "electric": 0,
    "toxin": 0,
    "gas": 0,
    "viral": 0,
    "corrosive": 0,
    "blast": 0,
    "magnetic": 0,
    "radiation": 0,
    "true": 0,
    "void": 0
  },
  "flight": 0,
  "polarities": "Vazarin",
  "projectile": "string",
  "tags": [
    "string"
  ],
  "vaulted": true,
  "wikiaThumbnail": "string",
  "wikiaUrl": "string",
  "disposition": 0,
  "releaseDate": "string",
  "vaultDate": "string"
}

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|name|string|false|none|none|
|uniqueName|string|false|none|none|
|secondsPerShot|number|false|none|none|
|totalDamage|number|false|none|none|
|damagePerSecond|number|false|none|none|
|trigger|string|false|none|none|
|description|string|false|none|none|
|accuracy|number|false|none|none|
|criticalChance|number|false|none|none|
|criticalMultiplier|number|false|none|none|
|procChance|number|false|none|none|
|fireRate|number|false|none|none|
|chargeAttack|number|false|none|none|
|spinAttack|number|false|none|none|
|leapAttack|number|false|none|none|
|wallAttack|number|false|none|none|
|slot|number|false|none|none|
|noise|string|false|none|none|
|sentinel|boolean|false|none|none|
|masteryReq|number|false|none|none|
|omegaAttenuation|number|false|none|none|
|type|string|false|none|none|
|buildPrice|number|false|none|none|
|buildTime|number|false|none|none|
|skipBuildTimePrice|number|false|none|none|
|buildQuantity|number|false|none|none|
|consumeOnBuild|boolean|false|none|none|
|components|[item](#schemaitem)|false|none|none|
|imageName|string|false|none|none|
|category|string|false|none|none|
|tradable|boolean|false|none|none|
|patchlogs|[patchlog](#schemapatchlog)|false|none|none|
|ammo|number|false|none|none|
|damage|number|false|none|none|
|damageTypes|object|false|none|none|
|» impact|number|false|none|none|
|» puncture|number|false|none|none|
|» slash|number|false|none|none|
|» heat|number|false|none|none|
|» cold|number|false|none|none|
|» electric|number|false|none|none|
|» toxin|number|false|none|none|
|» gas|number|false|none|none|
|» viral|number|false|none|none|
|» corrosive|number|false|none|none|
|» blast|number|false|none|none|
|» magnetic|number|false|none|none|
|» radiation|number|false|none|none|
|» true|number|false|none|none|
|» void|number|false|none|none|
|flight|number|false|none|none|
|polarities|[polarity](#schemapolarity)|false|none|none|
|projectile|string|false|none|none|
|tags|[string]|false|none|none|
|vaulted|boolean|false|none|none|
|wikiaThumbnail|string|false|none|none|
|wikiaUrl|string|false|none|none|
|disposition|number|false|none|none|
|releaseDate|string|false|none|none|
|vaultDate|string|false|none|none|

<h2 id="tocSpolarity">polarity</h2>

<a id="schemapolarity"></a>

```json
"Vazarin"

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|*anonymous*|string|false|none|none|

#### Enumerated Values

|Property|Value|
|---|---|
|*anonymous*|Vazarin|
|*anonymous*|Madurai|
|*anonymous*|Naramon|
|*anonymous*|Zenurik|
|*anonymous*|Unairu|
|*anonymous*|Penjaga|
|*anonymous*|Unbra|

<h2 id="tocSpatchlog">patchlog</h2>

<a id="schemapatchlog"></a>

```json
{
  "name": "string",
  "date": "string",
  "url": "string",
  "additions": "string",
  "changes": "string",
  "fixes": "string"
}

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|name|string|false|none|none|
|date|string|false|none|none|
|url|string|false|none|none|
|additions|string|false|none|none|
|changes|string|false|none|none|
|fixes|string|false|none|none|

<h2 id="tocSweapons">weapons</h2>

<a id="schemaweapons"></a>

```json
[
  {
    "name": "string",
    "uniqueName": "string",
    "secondsPerShot": 0,
    "dmagePerShot": [
      0
    ],
    "magazineSize": 0,
    "reloadTime": 0,
    "totalDamage": 0,
    "damagePerSecond": 0,
    "trigger": "string",
    "description": "string",
    "accuracy": 0,
    "criticalChance": 0,
    "criticalMultiplier": 0,
    "procChance": 0,
    "fireRate": 0,
    "slot": 0,
    "noise": "string",
    "sentinel": true,
    "masteryReq": 0,
    "omegaAttenuation": 0,
    "type": "string",
    "buildPrice": 0,
    "buildTime": 0,
    "skipBuildTimePrice": 0,
    "buildQuantity": 0,
    "consumeOnBuild": true,
    "components": {
      "name": "string",
      "uniqueName": "string"
    },
    "imageName": "string",
    "category": "string",
    "tradable": true,
    "patchlogs": {
      "name": "string",
      "date": "string",
      "url": "string",
      "additions": "string",
      "changes": "string",
      "fixes": "string"
    },
    "ammo": 0,
    "damage": 0,
    "damageTypes": {
      "impact": 0,
      "puncture": 0,
      "slash": 0,
      "heat": 0,
      "cold": 0,
      "electric": 0,
      "toxin": 0,
      "gas": 0,
      "viral": 0,
      "corrosive": 0,
      "blast": 0,
      "magnetic": 0,
      "radiation": 0,
      "true": 0,
      "void": 0
    },
    "flight": 0,
    "polarities": "Vazarin",
    "projectile": "string",
    "tags": [
      "string"
    ],
    "vaulted": true,
    "wikiaThumbnail": "string",
    "wikiaUrl": "string",
    "disposition": 0,
    "releaseDate": "string",
    "vaultDate": "string"
  }
]

```

### Properties

*oneOf*

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|*anonymous*|[primaryWeapon](#schemaprimaryweapon)|false|none|none|

*xor*

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|*anonymous*|[secondaryWeapon](#schemasecondaryweapon)|false|none|none|

*xor*

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|*anonymous*|[meleeWeapon](#schemameleeweapon)|false|none|none|

<h2 id="tocSitems">items</h2>

<a id="schemaitems"></a>

```json
[
  {
    "name": "string",
    "uniqueName": "string"
  }
]

```

*An item from Warframe*

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|*anonymous*|[[item](#schemaitem)]|false|none|An item from Warframe|

<h2 id="tocSitem">item</h2>

<a id="schemaitem"></a>

```json
{
  "name": "string",
  "uniqueName": "string"
}

```

### Properties

|Name|Type|Required|Restrictions|Description|
|---|---|---|---|---|
|name|string|false|none|none|
|uniqueName|string|false|none|none|

