# Explore-the-Tractatus
An exegetical tool for the Tractatus Logico-Philosophicus by Ludwig Wittgenstein based on D3.js

My project focused on the creation of an online edition of the Tractatus that allow the readers to explore both the connections and the contents of the proposition in a dynamic way, in a single bi-dimensional space and without the limits of the linear book edition: in other words, like a mind-map.

At first, I extracted the data in the same way Pierre Bellon has done (pbellon.github.io), creating a JSON data set of both the English Ogden’s translation and the original one in German. Later, I also used D3.js library to develop my dynamic representation.
Since I wanted the edition to display the propositions in the bi-dimensional space, I needed to put the entire content of each proposition directly in the nodes of the generated tree, together with the numbered indexes, in such a way that they do not occupy more space than needed, having in a single screen all the vertical and horizontal connections of a point of interest.

In this way the tree of the Tractatus is explorable, and indeed I have also implemented a zoom-in/zoom-out plus a drag and drop functionality that allows the reader (who eventually becomes the user) to move in the very topological representation, like in a map.
I also tried to make the user experience as smooth as possible, in such a way that the nodes are interactive and can be opened and closed when needed with a click, and the screen is centered correctly to show both the parent proposition and its whole family in a glance. The bigger the screen, the better the result, even though the zoom and drag and drop functionality also allows mobile and tablet users to appreciate the contents, maybe even more directly.
The project is open. Future improvements could concern:
 - The possibility to switch the language or to compare the translations;
 - To better calculate the distance among sibling propositions, calculating branch by branch the relative height;
 - A search function that opens all the nodes satisfied by an input query (although it’s still possible to use the browser’s search-in-page feature);
- Other needs or bug fixes that the community and the scholars can contribute to identify.
