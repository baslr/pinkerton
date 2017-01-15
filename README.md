# pinkerton
ArangoDB document key / value substitution for denser document storage


Through key substitution I achieved 25 % denser packed documents. If your documents contain in the majority cattic content you can save up to 75 % space through value substitution.

Since velocypack, ArangoDBs internal document format, saves every key name and your key name may not ultrashort most of the storage is used for storing the key names.
