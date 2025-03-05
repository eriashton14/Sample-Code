Includes Code For Following Java Projects:


ConcatenationSequence
ConcatSequenceTest

  ConcatenationSequence takes in an array of integers that represents the lengths of indivual strings. Using dynamic programming, the code returns the cheapest concatenation sequence of those      strings.

SemanticSimilarity

  SemanticSimilarity takes in a group of sentences and two strings that are in at least one of these sentences. With this information it creates a hashmap with data on how frequently the two       strings are in a sentence together. This hashmap is then used to create a numerical representation of the similarity of the two words.

Spelling Suggestions

  Spelling Suggestions takes in a target string and an integer representing distance from the target string. Distance is determined by deletion of a letter from the target, substitution of a       letter into the target, or addition of a letter onto the target. (For example, "house" is a distance of 1 from "houses" because of the additional "s"). The program then uses a trie to return     all valid words within the given distance from the target.
  

CoinGame

  CoinGame takes in a graph and two starting points for the coins. The game is that each coin moves once per turn but they move at the same time. The game is won when the coins end up on the       same spot in the fewest turns possible. This is accomplished by finding the shortest even bath between the two coins using BFS.
