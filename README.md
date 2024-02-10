# AntiRisk RBL

The purpose of the RBL is to add common domains (either through `base` or `strict` RBLs) to a list where you wouldn't expect these domains to make use of generic services in the public domain.
E.g. if you're providing a service where users can add domains, you'd generally want to prevent domains such as google.com or facebook.com to be added as domains - the RBL is to provide the information dynamically and crowdsourced without having to maintain manual lists.

## Imported lists

We automatically import domains from the below lists:
- https://github.com/dyne/domain-list
