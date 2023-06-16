# sql-queries

### Query for creating a table and importing excel data


####  Following Queries:

- Creating two new tables with pg admin of NBA players and seasonal stats:
- Importing data into players table

  
[<img width="683" alt="image" src="https://github.com/Jackelyneg/sql-queries/assets/81592631/128ecaa7-be2c-460d-a522-615b0172a8cf">](https://github.com/Jackelyneg/sql-queries/blob/main/Screenshot%202023-06-16%20144906.jpg)
  	
      create table players(
      player_id int,
      player_name varchar,
      height int,
      weight int,
      college varchar,
      born int,
      birth_city varchar,
      birth_state varchar )

      select * from players

-  Create and import data into seasonal stats table


      
    
      create table season_stats(  
      player_id INT,
      year DEC,
      position VARCHAR,
      age DEC,
      Tm VARCHAR,
      G VARCHAR,
  TS_Percentage DEC,
  FTr DEC,
  OWS DEC,
  DWS DEC,
  WS DEC,
  FG DEC,
  FGA DEC,
  FG_Percentage DEC,
  Two_Points DEC,
  Two_PA DEC,
  Two_Point_Percentage DEC,
  eFG_Percentage DEC,
  FT DEC,
  FTA DEC,
  FT_Percentage DEC,
  AST DEC,
  PF DEC,
  PTS DEC
);

select * from season_stats
