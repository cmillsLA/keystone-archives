keystone-archives
=================

Added monthly archiving to Keystonejs blog.  Added a route for /blog/archive/year/month to display posts from that date range.  Automatically save the archive date when the post is created or saved.

Files modified:

/templates/views/blog.jade

/node_modules/keystone/routes/views/item.js

/routes/views/blog.js

/routes/index.js

/models/PostArchive.js



TODO: Remove archive when post is deleted.
