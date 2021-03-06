# Samuel Wegner's Portfolio
This document contains a sampling of software development projects to which I have contributed.

## Data Structures
### [string-trie-java](https://github.com/samuelwegner/string-trie-java)
This project contains a Java class (StringTrie) implementing a [trie](https://en.wikipedia.org/wiki/Trie) data structure for storing strings, as well as a menu-based console application for manipulating StringTrie objects. I developed this project as an exercise in using pointers to create a linked structure. Tries interest me due to their high performance with large data sets, although their relatively large memory footprint limits their practical use cases. In the future, I want to explore the [DAFSA](https://en.wikipedia.org/wiki/Deterministic_acyclic_finite_state_automaton) and [HAMT](https://en.wikipedia.org/wiki/Hash_array_mapped_trie) data structures as alternatives with similar perfomance and better space efficiency.

### [binary-search-tree-java](https://github.com/samuelwegner/binary-search-tree-java)
This project contains a Java class (BST) implementing a [binary search tree](https://en.wikipedia.org/wiki/Binary_search_tree) data structure for storing generic elements. I developed this as an exercise in navigating and reorganizing a linked structure. The current implementation is usable, although in the future I want to expand it to implement a [red-black tree](https://en.wikipedia.org/wiki/Red%E2%80%93black_tree) that will self-balance at the cost of reduced efficiency during insertion and deletion operations.

## Games
### [tic-tac-toe-3d](https://github.com/samuelwegner/tic-tac-toe-3d)
This project contains the server-side code for a 3-dimensional tic-tac-toe game based on PHP/JSON Web services. This was my first significant project implementing custom Web services and using PHP, so it was a great learning experience in both of those areas. I was working with another student who developed the client-side application based on HTML/CSS/JavaScript, although their code is not included here. After working together to design an API for game's client-server communication, we were then able to work independently and concurrently to implement our own components, perform integration testing, and implement fixes before the project deadline.

### [Tales of Maj'Eyal](https://git.net-core.org/u/Effigy)
Tales of Maj'Eyal (ToME) is an open-source [roguelike](https://en.wikipedia.org/wiki/Roguelike) game written in Lua and C, developed by [Netcore Games](https://te4.org/). I have contributed several bug fixes and enhancements to this project; see my activity log on the linked [GitLab page](https://git.net-core.org/u/Effigy) for details. Working on ToME required that I learn a new programming language (Lua), become familiar with a mature codebase, and collaborate with other developers in the community. I also learned to use the Git forking workflow for open-source development.
