V14 FILTER-EVERYWHERE FIX

Validation now lives inside start() itself, so no UI path can bypass it.
A visible V14 marker was added to the footer so you can confirm GitHub Pages
is actually serving the newest file.

Test after upload:
Ass -> blocked
asshole -> blocked
bitch -> blocked
F U C K -> blocked
sh1t -> blocked
Cassidy -> allowed
