# TODO

* Refactor rbtree
    * Get rid of rb_direct_walk and rb_inverted_walk - who needs theese? (see http://stackoverflow.com/q/38209652/1565238 )
    * Get rid of rb_begin_iterate / rb_iterate, keep only new interface
	* Join RBTree*Walk structures to one
    * Add is_over flags to RBTreeWalk
    * Write property tests on left-rigth and right-left walks
    * Make corresponding changes to the blog post
* Add hash table implementation based on https://github.com/afiskon/c-hash-tables + write tests