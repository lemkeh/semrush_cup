## semrush_cup
My solution to Semrush Cup hackaton

Main problem I've faced that it has too large data, so main emphasis in my solution was to minimize data usage

What've been done:

• Data preprocessing

• Feature engineering(bad enough)

• Model training
<!-- • Clustering via K-Means(I'll add file later) -->
Due to the large data usage my PC's RAM had no chance in all off objectives.


These are some of ideas still haven't been implemented:

• Use hash2vec on urls/splitted urls

• Make clustering with other models(DBSCAN and OPTICS)

• Apply UMAP

Next two are kinda doubtful (especially last one), but I'd try them:

• Split url by domain parts than use tf-idf on them

• Split url by domain and count subdomains and path's parts

