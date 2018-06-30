# multi-edges

Description:
Provide modification which allow networkx to draw multiple edges between nodes

Requirement:
install matplotlib and networkx packages

Installing:

copy-past the patches2 file in your matplotlib package (C:\Users\Utilisateur\Anaconda3\Lib\site-packages\matplotlib or wherever it is)
copy-past the edges file in the directory where you want to run your python program and import it

you can now use the draw_networkx_multi_edges and play with the rad argument to draw your graph with multiple edges as seen in the example 1

example 2 is just another example of more complicated graph draw with this function

Caveat: work only if the parameter arrows is set to true in draw_networkx_multi_edges (default settings)
