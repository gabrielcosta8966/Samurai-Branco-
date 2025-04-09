# Samurai-Branco-[
  {
    "id": 1,
    "name": "Kenshiro",
    "nickname": "Samurai Branco",
    "note": "<MainCharacter>",
    "classId": 1,
    "initialLevel": 1,
    "maxLevel": 99,
    "characterName": "Kenshiro",
    "characterIndex": 0,
    "faceName": "Kenshiro_Face",
    "faceIndex": 0,
    "equips": [1, 1, 2, 0, 0]
  }
][
  {
    "id": 1,
    "name": "Samurai",
    "note": "",
    "expParams": [30, 20, 30, 30],
    "params": {
      "mhp": [400, 1000],
      "mmp": [50, 200],
      "atk": [30, 150],
      "def": [20, 100],
      "mat": [10, 80],
      "mdf": [20, 100],
      "agi": [25, 120],
      "luk": [15, 90]
    },
    "learnings": [
      { "level": 1, "skillId": 1 },
      { "level": 5, "skillId": 2 },
      { "level": 10, "skillId": 3 },
      { "level": 25, "skillId": 4 }
    ]
  }
][
  {
    "id": 1,
    "name": "Corte Rápido",
    "description": "Um ataque veloz com a katana.",
    "iconIndex": 76,
    "scope": 1,
    "occasion": 1,
    "speed": 10,
    "successRate": 100,
    "repeats": 1,
    "tpGain": 10,
    "damage": {
      "type": 1,
      "elementId": 0,
      "formula": "a.atk * 2 - b.def",
      "variance": 20,
      "critical": true
    }
  },
  {
    "id": 2,
    "name": "Postura de Defesa",
    "description": "Aumenta a defesa por 3 turnos.",
    "iconIndex": 77,
    "scope": 0,
    "occasion": 1,
    "speed": 0,
    "successRate": 100,
    "damage": { "type": 0 },
    "effects": [
      {
        "code": 21,
        "dataId": 3,
        "value1": 1,
        "value2": 0
      }
    ]
  },
  {
    "id": 3,
    "name": "Golpe da Lua Sangrenta",
    "description": "Ataque especial aprendido após a morte do mestre.",
    "iconIndex": 78,
    "scope": 1,
    "occasion": 1,
    "tpCost": 30,
    "damage": {
      "type": 1,
      "elementId": 0,
      "formula": "a.atk * 4 - b.def",
      "variance": 10,
      "critical": true
    }
  }
][
  {
    "id": 1,
    "name": "Bandido",
    "battlerName": "Bandit",
    "params": [300, 10, 25, 15, 10, 10, 15, 10],
    "actions": [
      { "skillId": 1, "rating": 5 }
    ]
  },
  {
    "id": 2,
    "name": "Chefe Bandido - Gouzan",
    "battlerName": "BanditBoss",
    "params": [1000, 30, 50, 30, 20, 25, 30, 15],
    "actions": [
      { "skillId": 1, "rating": 5 },
      { "skillId": 3, "rating": 8 }
    ]
  }
][
  {
    "id": 1,
    "name": "Katana Básica",
    "iconIndex": 96,
    "description": "Uma katana simples.",
    "animationId": 1,
    "params": [0, 10, 0, 0, 0, 0, 0, 0]
  },
  {
    "id": 2,
    "name": "Lâmina do Mestre",
    "iconIndex": 97,
    "description": "Espada herdada do salvador.",
    "animationId": 2,
    "params": [0, 20, 0, 0, 0, 0, 5, 5]
  }
][
  {
    "id": 1,
    "name": "Quimono Branco",
    "iconIndex": 120,
    "description": "Roupa tradicional do clã de Kenshiro.",
    "etypeId": 3,
    "params": [50, 0, 0, 10, 0, 0, 10, 0]
  }
]
