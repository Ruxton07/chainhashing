# Closed Address Hashing (Chaining) with hasharray

## Overview

The hasharray package provides an implementation of closed address hashing (chaining) using a hash array data structure. Closed address hashing is a way of efficiently store and retrieve key-value pairs in a hash table.

## Features

- Efficient storage and retrieval of key-value pairs using closed address hashing (chaining)
- Collision resolution through chaining, where multiple key-value pairs with the same hash value are stored in a linked list

## Installation

To use the chainhashing package, you need to have Python installed. You can install the package using pip:

```
pip install chainhashing
```

Then, simply type

```
import chainhashing
```

in your program and you're ready to go.

Message from the creator: This was my first deployed python package (aside from my practice one on TestPyPI that had no real implementation). I know there are probably many issues with this and the documentation isn't nearly as good as it should be, but hopefully people looking to use this library still find use out of it! I've run many test and my conclusion is that there are no functionality errors with this library. Any advice/change recommendations are greatly appreciated; feel free to email me at rt.kellar@gmail.com or open an issue on the GitHub page for this library, https://github.com/Ruxton07/chainhashing. Enjoy!