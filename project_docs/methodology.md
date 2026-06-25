# Methodology

This project transforms one primary source document into an LPG and wiki prototype. The primary source is:

Segal, A. A., & Greenspan, I. (2024). The Americanization of Israeli Conservative Civil Society: A critical community and transnational transference perspective. *Israel Studies, 29*(2), 144–169.

The workflow began by identifying candidate entities in the article, including people, organizations, funders, publications, events, ideas, places, and data sources. These became graph nodes only when they were useful as entities in the prototype. Broader descriptors, such as political fields or social-location categories, were treated as metadata tags rather than graph nodes when that made the LPG clearer.

Relationships from the article were modeled as directed LPG edges. Edge labels were written to preserve the meaning of the relationship, such as funding, organizational affiliation, publication, conference organization, translation, ideological promotion, data-source usage, or temporal role status. Where the article’s wording suggested a temporal cue, such as “former,” “served,” or “was,” the relationship was reviewed so the graph would not silently overclaim present-tense relationships.

The project was developed through an AI-with-human-in-the-loop workflow (Mosqueira-Rey et al., 2023). AI tools helped propose candidate graph structures and draft wiki prose, but Jacob Epstein reviewed and revised the outputs. Human review shaped the final decisions about what counted as a node, what should remain metadata, how relationships should be worded, which ambiguous items should be removed, and how wiki prose should read.

The wiki layer was derived from the graph. Node pages summarize what is known about an entity within the LPG, while edge pages explain the meaning of a specific relationship. Early wiki drafts were too mechanical because they translated each relationship into a separate sentence. The final version adds a prose-smoothing stage so pages read as connected narrative paragraphs rather than lists of extracted triples.

Internal wiki links were added so that when one node or edge is mentioned inside another wiki page, readers can click through to the relevant page. This turns the graph into a navigable reading environment rather than only a visual network.

## Human review and editorial criteria

The review process prioritized:

- fidelity to the primary article;
- avoiding unsupported claims;
- separating graph content from developer notes;
- distinguishing nodes from metadata tags;
- treating uncertain temporal claims cautiously;
- making wiki prose natural and non-repetitive;
- keeping attribution to the primary source clear.

## References

Segal, A. A., & Greenspan, I. (2024). The Americanization of Israeli Conservative Civil Society: A critical community and transnational transference perspective. *Israel Studies, 29*(2), 144–169.

Mosqueira-Rey, E., Hernández-Pereira, E., Alonso-Ríos, D., Bobes-Bascarán, J., & Fernández-Leal, Á. (2023). Human-in-the-loop machine learning: A state of the art. *Artificial Intelligence Review, 56*(4), 3005–3054. https://doi.org/10.1007/s10462-022-10246-w
