
This is a fork of
https://github.com/tantivy-search/tantivy-cli

This builds the binary **tcnom**

```
cargo build
```

```
mkdir /tmp/tantivy/wiki

cp ./data/meta.json /tmp/tantivy/wiki

tcnom index --file ./data/wiki-articles-1000.json --index /tmp/tantivy/wiki
```

Or instead of using the **tcnom** binary above you can run it this way...

```
cargo run index --file ./data/wiki-articles-1000.json --index /tmp/tantivy/wiki/
```

See [the data dir](./data/Readme.md) for more details...   
See [the doc dir](./doc/README.md) for more details...
