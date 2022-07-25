## [7,5,1,8,3,6,0,9,4,2] Binary Search Tree

**[7,5,1,8,3,6,0,9,4,2]** dizisi soldan sağa doğru okunmaya başlanır. İlk sayı root seçilir. Root'tan küçük sayılar sağına, büyük sayılar sola yazılır.


```
Root: 7
							7
						   /	
						  5
```
```
							7
						   /	
						  5
						 /
						1
```
```
							7
						   / \
						  5   8
						 /
						1
						
```
```
							7
						   / \
						  5   8
						 /
						1
						 \
					      3
						
```
```
							7
						   / \
						  5   8
						 / \
						1	6
						 \
					      3
						
```
```
							7
						   / \
						  5   8
						 / \
						1	6
					   / \
					  0   3
						
```
```
							7
						   / \
						  5   8
						 / \   \
						1	6   9
					   / \
					  0   3
						
```

```
							7
						   / \
						  5   8
						 / \   \
						1	6   9
					   / \
					  0   3
						   \
							4
```

```
							7
						   / \
						  5   8
						 / \   \
						1	6   9
					   / \
					  0   3
					  	 / \
					    2	4
```
[www.patika.dev](http://www.patika.dev/)
