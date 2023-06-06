# DataStructures

Projects done in a data structures class. 

Index of projects and their descriptions as follows:


## Project 2:
	Problem1:
		commands knowledge of interfaces and Big-O runtimes 
		
	Problem2:
		implement a Stack using java's ArrayList interface and 
		my own MyStackInterface
		
	Problem3:
		implements PalindromInterface and the code written in
		Problem2 to check if a given String is a palindrome
		

## Project 4:
	Problem1:
		read through a Java file to ensure sumbols 
			{}’s, ( )'s, [ ]'s, " "’s, and /* */ 
		are balanced utilizing   java.util.Stack
	Problem2:
		build a Queue ADT by using two stacks and implementing TwoStackQueueInterface
	
		
## Project 6:
	### Problem1:
		implement ExpressionTreeInterface to write a class which takes in a postfix expression String and run a stack-based algorithm to build an expression tree
			Provide 3 Methods:
				public int eval() - resulting integer value 
						     of the expression tree 
						     
				public String postfix() - corresponding postfix expression
				
				public String prefix()	- corresponding prefix expression
				
				public String infix() - corresponding infix expression		   
				
				public ExpressionTree(String expression) - constructor of the expression tree from the postfix String using the stack based algorithm
									     
	Problem2:
		implement BinarySearchTree in BetterBST to include the methods:
			public int height() - return the height of the BST
			
			public T imbalance() - check if tree is balanced
			
			public T smallestGreaterThan(T t) - find the smallest value in the BST that is larger than t
			
			public BinarySearchTree<T> mirror() - return a mirrored version of the BST
			
			public LinkedList<BinaryNode<T>> levelOrderTraversal - return a LinkedList<BinaryNode<T>> of a level order traversal of the binary tree
			
## Project 8:
	Problem1:
		implement a spell-checker using a hash table implementing SpellCheckerInterface referencing the dictionary words.txt
		
		public SpellChecker(String filename) - the constructor should take the file name of the dictionary
		
		public List<String> getIncorrectWords(String filename) - return a list of all words in the input file that are mispelled
		
		public Set<String> getSuggestions(String word) - return a set of all potential suggestions for mispelled word
		
	
	Problem2:
		find the k-best (largest) values in a set of data that can be infinatley large. Implement the class KBestCounter<T extends Comparable<?       super T>> implements KBest<T> using java.util.PriorityQueue.
			The methods include:
			
			public KBestCounter(int k) - the constructor takes in an int k (the amount of largest elements you want). 
			
			public void count(T x) - process the next element in the set of data in O(log k) time.
			
			public List<T> kbest() - return a sorted (smallest to largest) list of the k-largest elements in O(k log k) time
			
