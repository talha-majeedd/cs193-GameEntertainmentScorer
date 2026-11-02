# cs193-GameEntertainmentScorer
Idea:
Basically, a program that tells you how “interesting” your team is to fans/audience. It’s based on popularity, close games, higher-scoring games, and faster teams.
Trying to find an "interesting" team or game. Sometimes people watch games that aren't entertaining because they don't know much about the teams playing.

Solution:
Create a program that rates a team's "interestingness" based on your judgment. For example, you might think a team is more entertaining if 40% of its games are close and 60% are high-scoring. Then the program will find teams that fit your criteria.

Setup: It will use Java in addition to a csv of games from professional NBA games

Usage: An example is the program will ask how the user interprets an interesting team and then rate top 10 according to their criteria


Data: From the 2024-2025 season since it’s most recent full team.

Scoring will work by seeing which games had most lead changes, ties, overtime’s, etc. games will be sorted by both metrics and “points” will be assigned to those higher on metric, and then it multiplied by percentage. Teams will be grouped by most points

MVP has only organized by each metric, no normalization
