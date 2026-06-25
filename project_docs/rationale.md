# Project Rationale

This project is a proof of concept for transforming an ordinary natural-language text document into a structured, navigable labeled property graph (LPG) and wiki. The primary source for this prototype is:

Segal, A. A., & Greenspan, I. (2024). The Americanization of Israeli Conservative Civil Society: A critical community and transnational transference perspective. *Israel Studies, 29*(2), 144–169.

The goal is to test how prose can be transformed into an LPG-based structure made up of entities, relationships, metadata, and explanatory wiki pages. One advantage of an LPG over a standard network graph is that both nodes and edges can carry labeled semantic data. This makes it possible to represent not only that two things are connected, but also what kind of relationship connects them.

In this prototype, the graph uses nodes for named entities such as people, organizations, institutions, funders, publications, events, and ideas. It uses semantic edges to represent the relationships between them. This transforms the source text into a visual graph, making it easier to explore the complex ways that different types of nodes and edges interact with one another.

The wiki layer extends this idea. Each node and each edge receives a digital note card that functions like a standalone wiki page derived from the graph structure. The purpose of the wiki is to consolidate what is known about each node or edge into one readable location. The wiki pages expand on the short-form annotations that appear in the graph, turning compact graph relationships like `FUNDED_BY` into full sentences of explanatory prose. Internal links also allow readers to move between related nodes and edges through the familiar format of Wikipedia-style hyperlinks.

This prototype was developed through an AI-with-human-in-the-loop workflow (Mosqueira-Rey et al., 2023). Jacob first read and annotated the entire source document manually. AI tools then helped propose candidate nodes, edges, metadata tags, and relationship labels. Jacob Epstein reviewed these suggestions one at a time, revising and correcting them as needed through an iterative step-by-step process. Once the nodes, edges, and associated metadata were finalized, the wiki layer was developed with AI assistance and human review, producing and editing the digital note cards that explain the graph.

Jacob Epstein’s contribution is the transformation of the PDF source document into annotated data that was then extracted and used to code an LPG and wiki prototype. This includes the graph modeling, the distinction between nodes and metadata, the relationship vocabulary, the wiki layer, the internal navigation structure, and the editorial process that turned the narrative prose into an LPG.

## References

Mosqueira-Rey, E., Hernández-Pereira, E., Alonso-Ríos, D., Bobes-Bascarán, J., & Fernández-Leal, Á. (2023). Human-in-the-loop machine learning: A state of the art. *Artificial Intelligence Review, 56*(4), 3005–3054. https://doi.org/10.1007/s10462-022-10246-w

Segal, A. A., & Greenspan, I. (2024). The Americanization of Israeli Conservative Civil Society: A critical community and transnational transference perspective. *Israel Studies, 29*(2), 144–169.
