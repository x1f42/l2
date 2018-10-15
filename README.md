L2 is a data structures library.  Featured are BST and B-tree backed sequences,
BST, B-tree and trie associative tables, etc.

The BST (binary search tree) backed sequences are all purpose lists, allowing
for sequential and random access.  The complexity for most operations is
log(N), including reading, inserting and deleting, random or sequential.  The
lists are built on top AVL self balancing BSTs.  The programming interface
allows for static and dynamic lists specific operations, but also for BST
specific operations (operations such as searching and sorting).

The B-tree sequences are significantly faster than the BST ones.  They work for
fixed (and the smaller the better) size data.

The B-tree associative tables are similarly lot faster than the BST ones.  And
they do have a much reduced memory foot print.

More than a dozen string associative tables are included.  Most of them are
built on tries, the remaining on critical bit trees and b-trees.

*** Portability ***

The library should be fairly portable to common 32bit or 64bit UNIX systems.

*** Authors ***

Ciprian Niculescu
