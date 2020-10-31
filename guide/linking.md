# Linking

To link to another zettel, you can use regular Markdown links, or use the
special Wiki-link syntax by putting the [[id]] inside `[[..]]`:

```
This is a zettel file, which links to another zettel:

* [[ef3dke98]]

You can also use regular Markdown links:

* [My zettel](ef3dke98.md)
```

In [[web]], neuron will automatically display the title of the
linked zettel when using the wiki-link syntax.

## Branching links

Neuron supports branching links, which can be created using `[[[..]]]`:

```
This is a zettel file, which links (branches off) to another zettel:

* [[[ef3dke98]]]
```

The 3-bracket syntax creates a special link (called a folgezettel) to the
specified zettel. When a zettel has a folgezettel relationship to another
zettel, it is said to "branch of" to the other zettel. Folgezetel relationships
define the [[folgezettel-heterarchy]] of your zettel graph. 

Branching links affect the linked zettel's [[5e41fd32]] where the linking
zettel is displayed.

## Advanced linking

* [[[link-query]]]
