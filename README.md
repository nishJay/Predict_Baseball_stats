# Predict_Baseball_stats
An attempt to predict future baseball stats given a player's historical stats. 
By the end we will have a model which can predict next season stats for a baseball player along with diagnostics to improve the model further.

We will try to predict the **WAR** metric i.e Wins Above Replacement. 
WAR measures a player's value in all facets of the game by deciphering how many more wins he is worth than a replacement level player at his same position.

The basic currency of WAR is runs. We start with runs added or lost versus an average player and then compare the average player to a replacement player.

Players Runs over Replacement = Player_runs - ReplPlayer_runs = (Player_runs - AvgPlayer_runs) + (AvgPlayer_runs - ReplPlayer_runs)

Why WAR? It quantifies each player's value in terms of a specific number of wins. And because WAR factors in a positional adjustment, its well suited for comparing players who man different defensive positions.

Basically the attempt is to predict next season WAR metrics for a player based on the current season stats.
