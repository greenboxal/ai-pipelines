# aip-forddb

Database access layer for AIP.

## Features

* Document-based
* Strong typed
  * Canonical schema defined by (automated) IPLD schema
* Document storage
  * Firestore
  * IPFS (coming soon)
* Indexing
  * Firebase
    * BTree+ like index
    * Used for filtering scalars
  * Milvus
    * Vector index
    * Used for embedding retrieval