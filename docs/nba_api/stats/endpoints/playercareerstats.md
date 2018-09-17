# PlayerCareerStats

##### Endpoint URL
>[https://stats.nba.com/stats/playercareerstats](https://stats.nba.com/stats/playercareerstats)

##### Valid URL
>[https://stats.nba.com/stats/playercareerstats?LeagueID=&PerMode=Totals&PlayerID=2544](https://stats.nba.com/stats/playercareerstats?LeagueID=&PerMode=Totals&PlayerID=2544)

## Parameters
Parameter Name | Pattern | Required | Nullable
------------ | :-----------: | :---: | :---:
_**PerMode**_ | `^(Totals)|(PerGame)|(Per36)$` | `Y` |  | 
_**PlayerID**_ |  | `Y` |  | 
_**LeagueID**_ | `(00)|(20)|(10)` |  | `Y` | 

## Data Sets
#### CareerTotalsAllStarSeason `career_totals_all_star_season`
```text
['PLAYER_ID', 'LEAGUE_ID', 'Team_ID', 'GP', 'GS', 'MIN', 'FGM', 'FGA', 'FG_PCT', 'FG3M', 'FG3A', 'FG3_PCT', 'FTM', 'FTA', 'FT_PCT', 'OREB', 'DREB', 'REB', 'AST', 'STL', 'BLK', 'TOV', 'PF', 'PTS']
```

#### CareerTotalsCollegeSeason `career_totals_college_season`
```text
['PLAYER_ID', 'LEAGUE_ID', 'ORGANIZATION_ID', 'GP', 'GS', 'MIN', 'FGM', 'FGA', 'FG_PCT', 'FG3M', 'FG3A', 'FG3_PCT', 'FTM', 'FTA', 'FT_PCT', 'OREB', 'DREB', 'REB', 'AST', 'STL', 'BLK', 'TOV', 'PF', 'PTS']
```

#### CareerTotalsPostSeason `career_totals_post_season`
```text
['PLAYER_ID', 'LEAGUE_ID', 'Team_ID', 'GP', 'GS', 'MIN', 'FGM', 'FGA', 'FG_PCT', 'FG3M', 'FG3A', 'FG3_PCT', 'FTM', 'FTA', 'FT_PCT', 'OREB', 'DREB', 'REB', 'AST', 'STL', 'BLK', 'TOV', 'PF', 'PTS']
```

#### CareerTotalsRegularSeason `career_totals_regular_season`
```text
['PLAYER_ID', 'LEAGUE_ID', 'Team_ID', 'GP', 'GS', 'MIN', 'FGM', 'FGA', 'FG_PCT', 'FG3M', 'FG3A', 'FG3_PCT', 'FTM', 'FTA', 'FT_PCT', 'OREB', 'DREB', 'REB', 'AST', 'STL', 'BLK', 'TOV', 'PF', 'PTS']
```

#### SeasonRankingsPostSeason `season_rankings_post_season`
```text
['PLAYER_ID', 'SEASON_ID', 'LEAGUE_ID', 'TEAM_ID', 'TEAM_ABBREVIATION', 'PLAYER_AGE', 'GP', 'GS', 'RANK_MIN', 'RANK_FGM', 'RANK_FGA', 'RANK_FG_PCT', 'RANK_FG3M', 'RANK_FG3A', 'RANK_FG3_PCT', 'RANK_FTM', 'RANK_FTA', 'RANK_FT_PCT', 'RANK_OREB', 'RANK_DREB', 'RANK_REB', 'RANK_AST', 'RANK_STL', 'RANK_BLK', 'RANK_TOV', 'RANK_PTS', 'RANK_EFF']
```

#### SeasonRankingsRegularSeason `season_rankings_regular_season`
```text
['PLAYER_ID', 'SEASON_ID', 'LEAGUE_ID', 'TEAM_ID', 'TEAM_ABBREVIATION', 'PLAYER_AGE', 'GP', 'GS', 'RANK_MIN', 'RANK_FGM', 'RANK_FGA', 'RANK_FG_PCT', 'RANK_FG3M', 'RANK_FG3A', 'RANK_FG3_PCT', 'RANK_FTM', 'RANK_FTA', 'RANK_FT_PCT', 'RANK_OREB', 'RANK_DREB', 'RANK_REB', 'RANK_AST', 'RANK_STL', 'RANK_BLK', 'RANK_TOV', 'RANK_PTS', 'RANK_EFF']
```

#### SeasonTotalsAllStarSeason `season_totals_all_star_season`
```text
['PLAYER_ID', 'SEASON_ID', 'LEAGUE_ID', 'TEAM_ID', 'TEAM_ABBREVIATION', 'PLAYER_AGE', 'GP', 'GS', 'MIN', 'FGM', 'FGA', 'FG_PCT', 'FG3M', 'FG3A', 'FG3_PCT', 'FTM', 'FTA', 'FT_PCT', 'OREB', 'DREB', 'REB', 'AST', 'STL', 'BLK', 'TOV', 'PF', 'PTS']
```

#### SeasonTotalsCollegeSeason `season_totals_college_season`
```text
['PLAYER_ID', 'SEASON_ID', 'LEAGUE_ID', 'ORGANIZATION_ID', 'SCHOOL_NAME', 'PLAYER_AGE', 'GP', 'GS', 'MIN', 'FGM', 'FGA', 'FG_PCT', 'FG3M', 'FG3A', 'FG3_PCT', 'FTM', 'FTA', 'FT_PCT', 'OREB', 'DREB', 'REB', 'AST', 'STL', 'BLK', 'TOV', 'PF', 'PTS']
```

#### SeasonTotalsPostSeason `season_totals_post_season`
```text
['PLAYER_ID', 'SEASON_ID', 'LEAGUE_ID', 'TEAM_ID', 'TEAM_ABBREVIATION', 'PLAYER_AGE', 'GP', 'GS', 'MIN', 'FGM', 'FGA', 'FG_PCT', 'FG3M', 'FG3A', 'FG3_PCT', 'FTM', 'FTA', 'FT_PCT', 'OREB', 'DREB', 'REB', 'AST', 'STL', 'BLK', 'TOV', 'PF', 'PTS']
```

#### SeasonTotalsRegularSeason `season_totals_regular_season`
```text
['PLAYER_ID', 'SEASON_ID', 'LEAGUE_ID', 'TEAM_ID', 'TEAM_ABBREVIATION', 'PLAYER_AGE', 'GP', 'GS', 'MIN', 'FGM', 'FGA', 'FG_PCT', 'FG3M', 'FG3A', 'FG3_PCT', 'FTM', 'FTA', 'FT_PCT', 'OREB', 'DREB', 'REB', 'AST', 'STL', 'BLK', 'TOV', 'PF', 'PTS']
```


## JSON
```json
{
    "data_sets": {
        "CareerTotalsAllStarSeason": [
            "PLAYER_ID",
            "LEAGUE_ID",
            "Team_ID",
            "GP",
            "GS",
            "MIN",
            "FGM",
            "FGA",
            "FG_PCT",
            "FG3M",
            "FG3A",
            "FG3_PCT",
            "FTM",
            "FTA",
            "FT_PCT",
            "OREB",
            "DREB",
            "REB",
            "AST",
            "STL",
            "BLK",
            "TOV",
            "PF",
            "PTS"
        ],
        "CareerTotalsCollegeSeason": [
            "PLAYER_ID",
            "LEAGUE_ID",
            "ORGANIZATION_ID",
            "GP",
            "GS",
            "MIN",
            "FGM",
            "FGA",
            "FG_PCT",
            "FG3M",
            "FG3A",
            "FG3_PCT",
            "FTM",
            "FTA",
            "FT_PCT",
            "OREB",
            "DREB",
            "REB",
            "AST",
            "STL",
            "BLK",
            "TOV",
            "PF",
            "PTS"
        ],
        "CareerTotalsPostSeason": [
            "PLAYER_ID",
            "LEAGUE_ID",
            "Team_ID",
            "GP",
            "GS",
            "MIN",
            "FGM",
            "FGA",
            "FG_PCT",
            "FG3M",
            "FG3A",
            "FG3_PCT",
            "FTM",
            "FTA",
            "FT_PCT",
            "OREB",
            "DREB",
            "REB",
            "AST",
            "STL",
            "BLK",
            "TOV",
            "PF",
            "PTS"
        ],
        "CareerTotalsRegularSeason": [
            "PLAYER_ID",
            "LEAGUE_ID",
            "Team_ID",
            "GP",
            "GS",
            "MIN",
            "FGM",
            "FGA",
            "FG_PCT",
            "FG3M",
            "FG3A",
            "FG3_PCT",
            "FTM",
            "FTA",
            "FT_PCT",
            "OREB",
            "DREB",
            "REB",
            "AST",
            "STL",
            "BLK",
            "TOV",
            "PF",
            "PTS"
        ],
        "SeasonRankingsPostSeason": [
            "PLAYER_ID",
            "SEASON_ID",
            "LEAGUE_ID",
            "TEAM_ID",
            "TEAM_ABBREVIATION",
            "PLAYER_AGE",
            "GP",
            "GS",
            "RANK_MIN",
            "RANK_FGM",
            "RANK_FGA",
            "RANK_FG_PCT",
            "RANK_FG3M",
            "RANK_FG3A",
            "RANK_FG3_PCT",
            "RANK_FTM",
            "RANK_FTA",
            "RANK_FT_PCT",
            "RANK_OREB",
            "RANK_DREB",
            "RANK_REB",
            "RANK_AST",
            "RANK_STL",
            "RANK_BLK",
            "RANK_TOV",
            "RANK_PTS",
            "RANK_EFF"
        ],
        "SeasonRankingsRegularSeason": [
            "PLAYER_ID",
            "SEASON_ID",
            "LEAGUE_ID",
            "TEAM_ID",
            "TEAM_ABBREVIATION",
            "PLAYER_AGE",
            "GP",
            "GS",
            "RANK_MIN",
            "RANK_FGM",
            "RANK_FGA",
            "RANK_FG_PCT",
            "RANK_FG3M",
            "RANK_FG3A",
            "RANK_FG3_PCT",
            "RANK_FTM",
            "RANK_FTA",
            "RANK_FT_PCT",
            "RANK_OREB",
            "RANK_DREB",
            "RANK_REB",
            "RANK_AST",
            "RANK_STL",
            "RANK_BLK",
            "RANK_TOV",
            "RANK_PTS",
            "RANK_EFF"
        ],
        "SeasonTotalsAllStarSeason": [
            "PLAYER_ID",
            "SEASON_ID",
            "LEAGUE_ID",
            "TEAM_ID",
            "TEAM_ABBREVIATION",
            "PLAYER_AGE",
            "GP",
            "GS",
            "MIN",
            "FGM",
            "FGA",
            "FG_PCT",
            "FG3M",
            "FG3A",
            "FG3_PCT",
            "FTM",
            "FTA",
            "FT_PCT",
            "OREB",
            "DREB",
            "REB",
            "AST",
            "STL",
            "BLK",
            "TOV",
            "PF",
            "PTS"
        ],
        "SeasonTotalsCollegeSeason": [
            "PLAYER_ID",
            "SEASON_ID",
            "LEAGUE_ID",
            "ORGANIZATION_ID",
            "SCHOOL_NAME",
            "PLAYER_AGE",
            "GP",
            "GS",
            "MIN",
            "FGM",
            "FGA",
            "FG_PCT",
            "FG3M",
            "FG3A",
            "FG3_PCT",
            "FTM",
            "FTA",
            "FT_PCT",
            "OREB",
            "DREB",
            "REB",
            "AST",
            "STL",
            "BLK",
            "TOV",
            "PF",
            "PTS"
        ],
        "SeasonTotalsPostSeason": [
            "PLAYER_ID",
            "SEASON_ID",
            "LEAGUE_ID",
            "TEAM_ID",
            "TEAM_ABBREVIATION",
            "PLAYER_AGE",
            "GP",
            "GS",
            "MIN",
            "FGM",
            "FGA",
            "FG_PCT",
            "FG3M",
            "FG3A",
            "FG3_PCT",
            "FTM",
            "FTA",
            "FT_PCT",
            "OREB",
            "DREB",
            "REB",
            "AST",
            "STL",
            "BLK",
            "TOV",
            "PF",
            "PTS"
        ],
        "SeasonTotalsRegularSeason": [
            "PLAYER_ID",
            "SEASON_ID",
            "LEAGUE_ID",
            "TEAM_ID",
            "TEAM_ABBREVIATION",
            "PLAYER_AGE",
            "GP",
            "GS",
            "MIN",
            "FGM",
            "FGA",
            "FG_PCT",
            "FG3M",
            "FG3A",
            "FG3_PCT",
            "FTM",
            "FTA",
            "FT_PCT",
            "OREB",
            "DREB",
            "REB",
            "AST",
            "STL",
            "BLK",
            "TOV",
            "PF",
            "PTS"
        ]
    },
    "endpoint": "PlayerCareerStats",
    "nullable_parameters": [
        "LeagueID"
    ],
    "parameter_patterns": {
        "LeagueID": "(00)|(20)|(10)",
        "PerMode": "^(Totals)|(PerGame)|(Per36)$",
        "PlayerID": null
    },
    "parameters": [
        "LeagueID",
        "PerMode",
        "PlayerID"
    ],
    "required_parameters": [
        "PerMode",
        "PlayerID"
    ],
    "status": "success"
}
```

Last validated 2018-09-16