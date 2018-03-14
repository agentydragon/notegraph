notegraph
===

NoteGraph is a versioned directed graph.

Nodes
===

Nodes are:

* Text, which may contain inline links to other nodes.
* URLs.

The state of the graph is versioned.

UI
===

Web UI would be nice.

Being able to edit text in Vim would be nice.

Wishlist
===

* Linking with Anki cards.
* Visualization of the entire graph on one page.
* Storing drawings.
* Would be nice to publish this.
* Nice editor, with suggestion of links.
* Notes are also URLs. (Semantic web.)
* Edges are typed.
* Referring to a GitHub repo's file.
* Referring to a git commit.
* Referring to a Google Keep note.
* Full-text search.

Usage ideas
===

One node - "NOTES".
It links to projects in progress plus contains some freeform text.

Journal: entities are dated and have a text.

Implementation ideas
===

* Files in Git. Git automatically stores their history.
* Text nodes are 2 files: human-readable content (.md), metadata and edges
  (.meta).
* Directory structure.

"Quick note" workflow.

A node has attached automation, depending on its type.

A node's type can be inferred.

Git: A presubmit check to check that this is a valid graph, that it parses.

Open problems
===

What about things like Pocket? What about things that keep their own history?
