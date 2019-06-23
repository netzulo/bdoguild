# bdoguild

Discord bot for Black Desert Online game and guilds organization


## Commands

  + `$configure` start wizard setup
  + `$help` show help message
  + `$list` show list of players on DB with some required columns (ID, name, class, GS)
  + `$add` Initializa Enter member wizard
    + `$1=member` this optional param allow to add some allowed member to list (*example: `$add @someName`*)

### TODOs list

+ Create minimal tables when not exist

  + new class to manage DB connections
  + new class to decide when apply create queries
  + new class to execute parametrized queries

+ Create command manager

  + new class to listen validate and parse messages from Discord server
  + new class to generate embed templates to use on messages responses
  + 