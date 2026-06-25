# Data Model

This prototype uses an LPG model. The graph is made from nodes, directed edges, and metadata properties.

## Nodes

Nodes represent entities that readers may want to inspect directly. Examples include people, organizations, funders, publications, events, places, ideological formations, and source categories.

Not every meaningful descriptor becomes a node. Some concepts are clearer as metadata tags. For example, broad categories such as political field, right-wing Israeli civil society organization status, religious-nationalist circles, Israeli settler status, and American-born Israeli settler status are handled as properties or tags when they describe an entity rather than functioning as standalone graph objects.

## Edges

Edges represent relationships between two graph entities. Edge labels are written as relationship types, such as `FUNDED_BY`, `SUPPORTED_BY`, `PUBLISHED`, `ORGANIZED_BY`, `BOARD_MEMBER_OF`, `FORMER_BOARD_MEMBER_OF`, `PROMOTES`, or `USED_AS_DATA_ABOUT`.

Data-source relationships use `ABOUT` rather than `FOR`, because the source materials provide data about organizations rather than necessarily being used by those organizations.

## Metadata

Metadata supports filtering, interpretation, and readability. Metadata can describe political field, organization category, social-location tags, publication type, or other classification details. Metadata is not presented as developer commentary in reader-facing wiki prose.

## Wiki pages

Each node and edge has a wiki page. Node pages explain the role of the entity in the modeled graph. Edge pages explain what the relationship means in context. The wiki was generated from the graph structure and then revised through an AI-with-human-in-the-loop workflow (Mosqueira-Rey et al., 2023) so that pages read as narrative prose rather than raw extracted triples.

## References

Segal, A. A., & Greenspan, I. (2024). The Americanization of Israeli Conservative Civil Society: A critical community and transnational transference perspective. *Israel Studies, 29*(2), 144–169.

Mosqueira-Rey, E., Hernández-Pereira, E., Alonso-Ríos, D., Bobes-Bascarán, J., & Fernández-Leal, Á. (2023). Human-in-the-loop machine learning: A state of the art. *Artificial Intelligence Review, 56*(4), 3005–3054. https://doi.org/10.1007/s10462-022-10246-w
