# Skip list

In computer science, a skip list (or skiplist) is a probabilistic data structure that allows O(log ⁡n)
average complexity for search as well as O(log ⁡n) average complexity for insertion within an ordered sequence of n elements. 

Thus it can get the best features of a sorted array (for searching) while maintaining a linked list-like structure that allows insertion, which is not possible with a static array. Fast search is made possible by maintaining a linked hierarchy of subsequences, with each successive subsequence skipping over fewer elements than the previous one. Searching starts in the sparsest subsequence until two consecutive elements have been found, one smaller and one larger than or equal to the element searched for. Via the linked hierarchy, these two elements link to elements of the next sparsest subsequence, where searching is continued until finally searching in the full sequence. The elements that are skipped over may be chosen probabilistically or deterministically, with the former being more common.

<img src='./skiplist.png'>

sources: 

https://en.wikipedia.org/wiki/Skip_list

https://brilliant.org/wiki/skip-lists/