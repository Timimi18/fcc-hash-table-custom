# Custom Hash Table Data Structure (freeCodeCamp Project)

A low-level computer science demonstration featuring a custom **Hash Table** data structure built completely from scratch in Python. The system overrides high-level data abstractions to showcase exactly how hashing algorithms convert dynamic string inputs into structured numerical array indexes, complete with automated nested collision resolution mapping.

This engineering lab satisfies 100% of the rigorous core metrics established by the **freeCodeCamp Python Certification** matrix.

## 🧠 Algorithmic Framework & Features
1. **Unicode Hash Engine (`hash`):** Takes any input string and maps its structural footprint down to an integrated integer hash by iterating and summing character scalar values (`ord()`).
2. **Collision Management Layer (`add`):** Maps key-value sets into unique hashed bucket indexes. If two distinct text strings generate overlapping hash keys, the engine routes them into a nested sub-dictionary bucket to avoid data overwrites.
3. **Graceful Deletion Routing (`remove`):** Safely purges record assets from internal dictionary layers without triggering active key reference crashes or syntax exceptions.
4. **O(1) Memory Lookup Array (`lookup`):** Queries individual target strings instantly by resolving their mathematical hashes first, returning exact data pairings or standard `None` parameters if vacant.

## 🛠️ Core Technical Concepts Demonstrated
* **Low-Level Data Structures:** Engineering structural associative data maps without depending on default high-level library functions.
* **Hash Collision Protocols:** Resolving algorithm bucket intersections through chaining mechanics using nested dictionary spaces.
* **Algorithmic Complexity Optimization:** Designing system procedures focusing on minimizing computational strain across retrieval passes.

## 📂 Code Layout Map
* `main.py`: The production library housing the core `HashTable` architectural engine class.
* `README.md`: Advanced configuration specs and administrative tracking document.

See also: [reanalysis of my undergraduate thesis data](https://github.com/Timimi18/yam-peel-adsorption-analysis)
