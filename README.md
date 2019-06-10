go-libp2p-connmgr
==================

This is a modified version of `libp2p/go-libp2p-conmgr`

# Modifications:

* Provide context when constructing BasicConnMgr
* Use wait groups to synchronize goroutines and prevent leaks
* Switch logging to `uber/zap`