# Array vs Linked List

| Parameter			| Array		    | Linked List	| Better for parameter|
| ------------- 	| ------------- | ------------- | ------------- |
| Cost of accesing an element | Constant time O(1) | Average case O(n) | Array |
|					|				|				|				|
|  					|  				| 				| 				|
| Memory requirements | Fixed size | No unused memory | Depends on size of the list	| 
|| Memory may not be available as one large block| Extra memory for pointer variables | Memory fragmentation - Linked list is better :one:|
|  					|  				| 				| 				|
|  					|  				| 				| 				|
| Cost of inserting an element 		|  				| 				| 				|
| a) at beginning	| O(n)			| O(1)			| Linked list	|
| b) at end			| O(1) - if not full and O(n) - if full	| O(n)	| Array |
| c) at Kth position | O(n)         | O(n) | |
|  					|  				| 				| 				|
|  					|  				| 				| 				|
| Cost of deleting is the same as inserting for the three scenarios | | |




:one: Sometimes we may get many small units of memory, but we may not get one large block.




