# Mapping-European-Revolutionary-Networks-1848-1989-
european-revolutionary-networks
import networkx as nx

G=nx.Graph()

G.add_edges_from([
("Paris","Berlin"),
("Berlin","Budapest"),
("Budapest","Prague")
])

print(nx.degree_centrality(G))
