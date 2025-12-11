# decidim-network-parser
Python notebooks for cleaning, parsing, and visualizing Decidim open data as networks.


---

## Decidim open data & network parser

¡Parse, model, and visualize networks from Decidim open data! You can find examples of sample original and parsed datasets [here](./data/).

1. **Import and merge CSV files** from the [open data module](https://meta.decidim.org/open-data) of any Decidim instance (currently ). Get a single data frame with some additional cleaned columns (time, type, process_name).
2. **Parse weighted user2process relationships** by how tracking many times a single user interacted with a process (via comments). Get nodes and edges tables.
3. **Visualize and explore the network graph** with the [Cosmograph Python plugin](https://pypi.org/project/cosmograph/).
4. *(WIP) Calculate the communities with Louvain Method*, using [networkx](https://networkx.org/en/). *Still a work in progress.