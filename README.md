# subgraph
subgraphs for querying tokens 


 - subgraphs are deployed from the cli using the <strong>graph</strong> module 
 - initialzie subgraph: 
   -  graph init --from-contract  <contract address> --network <your_network>  \ --contract-name <token_name> --index-events
  
 - subgraph configs: 
  - subgraph.yaml: yaml file contains subG manifest   --- <strong>subgraph config</strong> 
    - schema.graphql: graphQL schema - def data stored for subG + how to query via GQL
    - assemblyScript mappings: asmScpt translates event data in ETH to entities def in schema (mappings.ts) 
    - subgraph.yaml: a YAML file containing the subgraph manifest

 
