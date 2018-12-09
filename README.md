# gameofthrones
Character Interaction Networks for the HBO Series "Game of Thrones"

These networks were created by parsing fan-generated scripts from https://genius.com/artists/Game-of-thrones.
Pairs of characters are connected by (undirected) edges weighted by the number of interactions.

There are five interaction types. Character A and Character B are connected whenever:
1. Character A speaks directly after Character B
2. Character A speaks about Character B
3. Character C speaks about Character A and Character B
4. Character A and Character B are mentioned in the same stage direction
5. Character A and Character B appear in a scene together

You can use this data to explore the dynamics of the Seven Kingdoms using network science techniques. For example,
community detection finds coherent plotlines. Centrality measures uncover the multiple ways in which characters play
important roles in the saga.

This is the data for the work presented here:

https://networkofthrones.wordpress.com by [Andrew Beveridge](https://twitter.com/mathbeveridge)

and in the scholarly essay

Andrew Beveridge and Michael Chemers, "The Game of 'The Game of Thrones': Networked Concordances and Fractal Dramaturgy",
in: Paola Brembilla and Ilaria De Pacalis (eds.), Reading Contemporary Serial Television Universes: A Narrative
Ecosystem Framework, Routledge, 2018.
