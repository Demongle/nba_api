# PlayerDashPtShots

##### Endpoint URL
>[https://stats.nba.com/stats/playerdashptshots](https://stats.nba.com/stats/playerdashptshots)

##### Valid URL
>[https://stats.nba.com/stats/playerdashptshots?DateFrom=&DateTo=&GameSegment=&LastNGames=0&LeagueID=00&Location=&Month=0&OpponentTeamID=0&Outcome=&PerMode=Totals&Period=0&PlayerID=2544&Season=2017-18&SeasonSegment=&SeasonType=Regular+Season&TeamID=1610612739&VsConference=&VsDivision=](https://stats.nba.com/stats/playerdashptshots?DateFrom=&DateTo=&GameSegment=&LastNGames=0&LeagueID=00&Location=&Month=0&OpponentTeamID=0&Outcome=&PerMode=Totals&Period=0&PlayerID=2544&Season=2017-18&SeasonSegment=&SeasonType=Regular+Season&TeamID=1610612739&VsConference=&VsDivision=)

## Parameters
Parameter Name | Pattern | Required | Nullable
------------ | :-----------: | :---: | :---:
_**LastNGames**_ |  | `Y` |  | 
_**LeagueID**_ | `(00)\|(20)\|(10)` |  |  | 
_**Month**_ |  | `Y` |  | 
_**OpponentTeamID**_ |  | `Y` |  | 
_**PerMode**_ | `^(Totals)\|(PerGame)$` | `Y` |  | 
_**Period**_ |  | `Y` |  | 
_**PlayerID**_ |  | `Y` |  | 
_**Season**_ | `^\d{4}-\d{2}$` | `Y` |  | 
_**SeasonType**_ | `^(Regular Season)\|(Pre Season)\|(Playoffs)\|(All Star)$` | `Y` |  | 
_**TeamID**_ |  | `Y` |  | 
_**VsDivision**_ | `^((Atlantic)\|(Central)\|(Northwest)\|(Pacific)\|(Southeast)\|(Southwest)\|(East)\|(West))?$` | `Y` | `Y` | 
_**VsConference**_ | `^((East)\|(West))?$` | `Y` | `Y` | 
_**SeasonSegment**_ | `^((Post All-Star)\|(Pre All-Star))?$` | `Y` | `Y` | 
_**Outcome**_ | `^((W)\|(L))?$` | `Y` | `Y` | 
_**Location**_ | `^((Home)\|(Road))?$` | `Y` | `Y` | 
_**GameSegment**_ | `^((First Half)\|(Overtime)\|(Second Half))?$` | `Y` | `Y` | 
_**DateTo**_ |  | `Y` | `Y` | 
_**DateFrom**_ |  | `Y` | `Y` | 

## Data Sets
#### ClosestDefender10ftPlusShooting `closest_defender10ft_plus_shooting`
```text
['PLAYER_ID', 'PLAYER_NAME_LAST_FIRST', 'SORT_ORDER', 'GP', 'G', 'CLOSE_DEF_DIST_RANGE', 'FGA_FREQUENCY', 'FGM', 'FGA', 'FG_PCT', 'EFG_PCT', 'FG2A_FREQUENCY', 'FG2M', 'FG2A', 'FG2_PCT', 'FG3A_FREQUENCY', 'FG3M', 'FG3A', 'FG3_PCT']
```

#### ClosestDefenderShooting `closest_defender_shooting`
```text
['PLAYER_ID', 'PLAYER_NAME_LAST_FIRST', 'SORT_ORDER', 'GP', 'G', 'CLOSE_DEF_DIST_RANGE', 'FGA_FREQUENCY', 'FGM', 'FGA', 'FG_PCT', 'EFG_PCT', 'FG2A_FREQUENCY', 'FG2M', 'FG2A', 'FG2_PCT', 'FG3A_FREQUENCY', 'FG3M', 'FG3A', 'FG3_PCT']
```

#### DribbleShooting `dribble_shooting`
```text
['PLAYER_ID', 'PLAYER_NAME_LAST_FIRST', 'SORT_ORDER', 'GP', 'G', 'DRIBBLE_RANGE', 'FGA_FREQUENCY', 'FGM', 'FGA', 'FG_PCT', 'EFG_PCT', 'FG2A_FREQUENCY', 'FG2M', 'FG2A', 'FG2_PCT', 'FG3A_FREQUENCY', 'FG3M', 'FG3A', 'FG3_PCT']
```

#### GeneralShooting `general_shooting`
```text
['PLAYER_ID', 'PLAYER_NAME_LAST_FIRST', 'SORT_ORDER', 'GP', 'G', 'SHOT_TYPE', 'FGA_FREQUENCY', 'FGM', 'FGA', 'FG_PCT', 'EFG_PCT', 'FG2A_FREQUENCY', 'FG2M', 'FG2A', 'FG2_PCT', 'FG3A_FREQUENCY', 'FG3M', 'FG3A', 'FG3_PCT']
```

#### Overall `overall`
```text
['PLAYER_ID', 'PLAYER_NAME_LAST_FIRST', 'SORT_ORDER', 'GP', 'G', 'SHOT_TYPE', 'FGA_FREQUENCY', 'FGM', 'FGA', 'FG_PCT', 'EFG_PCT', 'FG2A_FREQUENCY', 'FG2M', 'FG2A', 'FG2_PCT', 'FG3A_FREQUENCY', 'FG3M', 'FG3A', 'FG3_PCT']
```

#### ShotClockShooting `shot_clock_shooting`
```text
['PLAYER_ID', 'PLAYER_NAME_LAST_FIRST', 'SORT_ORDER', 'GP', 'G', 'SHOT_CLOCK_RANGE', 'FGA_FREQUENCY', 'FGM', 'FGA', 'FG_PCT', 'EFG_PCT', 'FG2A_FREQUENCY', 'FG2M', 'FG2A', 'FG2_PCT', 'FG3A_FREQUENCY', 'FG3M', 'FG3A', 'FG3_PCT']
```

#### TouchTimeShooting `touch_time_shooting`
```text
['PLAYER_ID', 'PLAYER_NAME_LAST_FIRST', 'SORT_ORDER', 'GP', 'G', 'TOUCH_TIME_RANGE', 'FGA_FREQUENCY', 'FGM', 'FGA', 'FG_PCT', 'EFG_PCT', 'FG2A_FREQUENCY', 'FG2M', 'FG2A', 'FG2_PCT', 'FG3A_FREQUENCY', 'FG3M', 'FG3A', 'FG3_PCT']
```


## JSON
```json
{
    "data_sets": {
        "ClosestDefender10ftPlusShooting": [
            "PLAYER_ID",
            "PLAYER_NAME_LAST_FIRST",
            "SORT_ORDER",
            "GP",
            "G",
            "CLOSE_DEF_DIST_RANGE",
            "FGA_FREQUENCY",
            "FGM",
            "FGA",
            "FG_PCT",
            "EFG_PCT",
            "FG2A_FREQUENCY",
            "FG2M",
            "FG2A",
            "FG2_PCT",
            "FG3A_FREQUENCY",
            "FG3M",
            "FG3A",
            "FG3_PCT"
        ],
        "ClosestDefenderShooting": [
            "PLAYER_ID",
            "PLAYER_NAME_LAST_FIRST",
            "SORT_ORDER",
            "GP",
            "G",
            "CLOSE_DEF_DIST_RANGE",
            "FGA_FREQUENCY",
            "FGM",
            "FGA",
            "FG_PCT",
            "EFG_PCT",
            "FG2A_FREQUENCY",
            "FG2M",
            "FG2A",
            "FG2_PCT",
            "FG3A_FREQUENCY",
            "FG3M",
            "FG3A",
            "FG3_PCT"
        ],
        "DribbleShooting": [
            "PLAYER_ID",
            "PLAYER_NAME_LAST_FIRST",
            "SORT_ORDER",
            "GP",
            "G",
            "DRIBBLE_RANGE",
            "FGA_FREQUENCY",
            "FGM",
            "FGA",
            "FG_PCT",
            "EFG_PCT",
            "FG2A_FREQUENCY",
            "FG2M",
            "FG2A",
            "FG2_PCT",
            "FG3A_FREQUENCY",
            "FG3M",
            "FG3A",
            "FG3_PCT"
        ],
        "GeneralShooting": [
            "PLAYER_ID",
            "PLAYER_NAME_LAST_FIRST",
            "SORT_ORDER",
            "GP",
            "G",
            "SHOT_TYPE",
            "FGA_FREQUENCY",
            "FGM",
            "FGA",
            "FG_PCT",
            "EFG_PCT",
            "FG2A_FREQUENCY",
            "FG2M",
            "FG2A",
            "FG2_PCT",
            "FG3A_FREQUENCY",
            "FG3M",
            "FG3A",
            "FG3_PCT"
        ],
        "Overall": [
            "PLAYER_ID",
            "PLAYER_NAME_LAST_FIRST",
            "SORT_ORDER",
            "GP",
            "G",
            "SHOT_TYPE",
            "FGA_FREQUENCY",
            "FGM",
            "FGA",
            "FG_PCT",
            "EFG_PCT",
            "FG2A_FREQUENCY",
            "FG2M",
            "FG2A",
            "FG2_PCT",
            "FG3A_FREQUENCY",
            "FG3M",
            "FG3A",
            "FG3_PCT"
        ],
        "ShotClockShooting": [
            "PLAYER_ID",
            "PLAYER_NAME_LAST_FIRST",
            "SORT_ORDER",
            "GP",
            "G",
            "SHOT_CLOCK_RANGE",
            "FGA_FREQUENCY",
            "FGM",
            "FGA",
            "FG_PCT",
            "EFG_PCT",
            "FG2A_FREQUENCY",
            "FG2M",
            "FG2A",
            "FG2_PCT",
            "FG3A_FREQUENCY",
            "FG3M",
            "FG3A",
            "FG3_PCT"
        ],
        "TouchTimeShooting": [
            "PLAYER_ID",
            "PLAYER_NAME_LAST_FIRST",
            "SORT_ORDER",
            "GP",
            "G",
            "TOUCH_TIME_RANGE",
            "FGA_FREQUENCY",
            "FGM",
            "FGA",
            "FG_PCT",
            "EFG_PCT",
            "FG2A_FREQUENCY",
            "FG2M",
            "FG2A",
            "FG2_PCT",
            "FG3A_FREQUENCY",
            "FG3M",
            "FG3A",
            "FG3_PCT"
        ]
    },
    "endpoint": "PlayerDashPtShots",
    "last_validated_date": "2018-10-08",
    "nullable_parameters": [
        "DateFrom",
        "DateTo",
        "GameSegment",
        "Location",
        "Outcome",
        "SeasonSegment",
        "VsConference",
        "VsDivision"
    ],
    "parameter_patterns": {
        "DateFrom": null,
        "DateTo": null,
        "GameSegment": "^((First Half)|(Overtime)|(Second Half))?$",
        "LastNGames": null,
        "LeagueID": "(00)|(20)|(10)",
        "Location": "^((Home)|(Road))?$",
        "Month": null,
        "OpponentTeamID": null,
        "Outcome": "^((W)|(L))?$",
        "PerMode": "^(Totals)|(PerGame)$",
        "Period": null,
        "PlayerID": null,
        "Season": "^\\d{4}-\\d{2}$",
        "SeasonSegment": "^((Post All-Star)|(Pre All-Star))?$",
        "SeasonType": "^(Regular Season)|(Pre Season)|(Playoffs)|(All Star)$",
        "TeamID": null,
        "VsConference": "^((East)|(West))?$",
        "VsDivision": "^((Atlantic)|(Central)|(Northwest)|(Pacific)|(Southeast)|(Southwest)|(East)|(West))?$"
    },
    "parameters": [
        "DateFrom",
        "DateTo",
        "GameSegment",
        "LastNGames",
        "LeagueID",
        "Location",
        "Month",
        "OpponentTeamID",
        "Outcome",
        "PerMode",
        "Period",
        "PlayerID",
        "Season",
        "SeasonSegment",
        "SeasonType",
        "TeamID",
        "VsConference",
        "VsDivision"
    ],
    "required_parameters": [
        "DateFrom",
        "DateTo",
        "GameSegment",
        "LastNGames",
        "Location",
        "Month",
        "OpponentTeamID",
        "Outcome",
        "PerMode",
        "Period",
        "PlayerID",
        "Season",
        "SeasonSegment",
        "SeasonType",
        "TeamID",
        "VsConference",
        "VsDivision"
    ],
    "status": "success"
}
```

Last validated 2018-10-08