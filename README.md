# changelogs
Changelogs for Paintswap apps

## Instructions

Create one file per app on the following format (latest version and changes at the top, features grouped first).

```json
[
  {
    "version": "1.1",
    "lastUpdate": "2023-09-05",
    "changes": [
      {
          "type": "feature",
          "name": "New XP column in the leaderboard table"
      },
      {
          "type": "bug",
          "name": "Fixed app crash when using decimal values"
      }
    ]
  },
  {
    "version": "1.2",
    "changes": []
  }
]
```

There is a pre-commit hook that checks the json format.

## Installation

```bash
yarn install
yarn prepare
```