# random-connected-graphs
To retrieve a graph:
'''
import networkx as nx
import numpy as np
import pickle

graph = nx.Graph()

pickle_file_path = "random_connected_graphs_nodes_edge_density.pkl"

with open(pickle_file_path, 'rb') as file:
  graphs = pickle.load(file)
  graph = graphs[0]
'''
