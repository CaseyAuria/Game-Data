# Game-Data
import pandas as pd

game_data = {
    'Title': [
        'Lords Of The Fallen',
        'Elden Ring',
        'Dark Souls',
        'Expedition 33',
        'Bloodborne',
        'Sekiro',
        'Lies of P',
        'Nine Sols',
        'Hollow Knight',
        'Neva'
    ],

    'Genre': [
        'Action RPG',
        'RPG',
        'RPG',
        'Indie',
        'RPG',
        'Adventure',
        'RPG',
        '2D action platformer',
        'Indie',
        'Puzzle'
    ],

    'Release Year': [
        '2023',
        '2022',
        '2011',
        '2025',
        '2015',
        '2019',
        '2023',
        '2024',
        '2017',
        '2024'
    ],

    'Developer': [
        'HexWorks',
        'Fromsoftware',
        'Fromsoftware',
        'Sandfall Interactive',
        'Fromsoftware',
        'Fromsoftware',
        'Round8 Studio',
        'Red Candle Games',
        'Team Cherry',
        'Nomada Studio'
    ],

    'Platform': [
        ['Steam', 'PS5', 'Xbox Series X'],
        ['PS4', 'PS5', 'Xbox Series X', 'Windows PC'],
        ['PS3', 'PS4', 'Xbox One', 'Xbox 360', 'PC', 'Nintendo Switch'],
        ['PS5', 'Xbox Series X', 'PC'],
        ['PS4', 'PS5', 'Xbox One'],
        ['PS4', 'Xbox One', 'Microsoft Windows'],
        ['PS4', 'PS5', 'Xbox One', 'Xbox Series X', 'Steam'],
        ['PC', 'Xbox', 'PS4', 'PS5', 'Nintendo Switch'],
        ['PC', 'PS4', 'PS5', 'Xbox One', 'Xbox Series X', 'Nintendo Switch'],
        ['PS4', 'PS5', 'Windows', 'MacOS', 'Nintendo Switch', 'Xbox Series X']
    ],

    'Combat Style': [
        'Soulslike Melee',
        'Strategic and action oriented gameplay',
        'Melee',
        'Hybrid turn-based and real time mechanics',
        'Aggressive Playstyle',
        'Skill Trees',
        'Aggressive Soulslike with precision parries',
        '2D precision with deflections',
        'Precise 2D melee with mobility and timing-based combat',
        'Combat focused on timing and emotional storytelling'
    ],

    'Difficulty Rating': [
        '3/6',
        '7/10',
        '6/4',
        '6/10',
        '8.5/10',
        '10/10',
        '8/10',
        '7.5/10',
        '8/10',
        '3/10'
    ],

    'Main Protagonist': [
        'Harkin',
        'Tarnished',
        'Chosen Undead',
        'Maelle',
        'Hunter',
        'Skilled shinobi',
        'Pinocchio',
        'Yi',
        'The Knight',
        'Neva'
    ],

    'Stats': [
        ['Strength', 'Agility', 'Endurance', 'Vitality', 'Radiance', 'Inferno'],
        ['Vigor', 'Mind', 'Endurance', 'Strength', 'Dexterity', 'Intelligence', 'Faith', 'Arcane'],
        ['Vitality', 'Attunement', 'Endurance', 'Strength', 'Dexterity', 'Intelligence', 'Faith', 'Luck'],
        ['Vitality', 'Might', 'Agility', 'Defence', 'Luck'],
        ['Strength', 'Skill', 'Arcane', 'Bloodtinge'],
        ['Attack power', 'Vitality', 'Posture', 'Sen', 'Drop Rate'],
        ['Vitality', 'Vigor', 'Capacity'],
        ['Vitality', 'Deflection Meter', 'Chi', 'Stance'],
        ['Vitality', 'Soul Meter', 'Charms'],
        ['Vitality', 'Companion Interaction', 'Agility']
    ],

    'Playable_classes': [
        ['Condemned', 'Hollowed Knight', 'Orian Preacher', 'Blackfeather Ranger', 'Dark Crusader', 'Lord', 'Putrid Child'],
        ['Hero', 'Bandit', 'Astrologer', 'Warrior', 'Prisoner', 'Confessor', 'Wretch', 'Vagabond', 'Prophet', 'Samurai', 'Heavy Knight'],
        ['Warrior', 'Knight', 'Wanderer', 'Thief', 'Bandit', 'Hunter', 'Sorcerer', 'Cleric', 'Deprived'],
        ['Gustave', 'Lune', 'Maelle', 'Sciel', 'Verso', 'Monoco'],
        ['Standard Hunter', 'Heavy Hunter', 'Sword and Heavy Attack Hunter', 'Agile Hunter'],
        ['Aggressive Deflector', 'Prosthetic User', 'Stealth Player', 'Combat Arts Focus', 'Balanced'],
        ['Path of the Sweeper', 'Path of the Bastard', 'Path of the Cricket'],
        ['Parry Focus', 'Talisman Build', 'Aggressive Rush', 'Balanced', 'Exploration Build'],
        ['Spell Bound', 'Nail Build', 'Hybrid', 'Charm Tank', 'Speedrun Build'],
        ['Alba']
    ]
}

df = pd.DataFrame(game_data)
print(df)
