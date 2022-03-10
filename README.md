# Connect-4-AI

This is a two-player board game, in which the players choose a color and then take turns dropping colored discs into a seven-column, six-row vertically suspended grid. The pieces fall straight down, occupying the lowest available space within the column. The objective of the game is to be the first to form a horizontal, vertical, or diagonal line of four of one's own discs. Four in a Row is a solved game. The first player can always win by playing the right moves.

• Minimax
    Here I will implement depth-limited minimax which searches to an arbitrary depth as it's not feasible to search the entire game tree.
• Alpha-Beta Pruning 
    This will speed-up the search as the depth of the tree increases, as it allows for more efficient exploration of the minimax tree
• Expectimax
    This models probabilistic behavior of opponents that may make suboptimal decisions. For this I will have chance nodes that will replace the MIN nodes (AI-Agent2 or
    Human Player). For this implementation, consider I will only be running against an adversary which chooses actions uniformly at random, because Minimax and Alpha-       Beta algorithms assume that MAX plays against an adversary who makes optimal decisions.
