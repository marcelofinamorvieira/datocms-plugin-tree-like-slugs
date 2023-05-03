# Tree-like Slugs

A plugin that makes it so the slugs in tree-like records are passed down to the child records

Add it to the slug field you want as a field addon, the model where that slug is in must be set with a "Tree-like" presentation. From then on, all of the slugs in the tree-like configuration will inherit as a prefix the slug on the parent record.

The slug field must have the "Match a specific pattern" validation disabled! Otherwise the plugin won't be able to insert '/' in the slug.
