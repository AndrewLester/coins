# Coin Puzzle
Solving a coin puzzle

### Compilation for Web
    npm install
    grunt bundle:node_modules/webppl-viz
## The Puzzle
The coin puzzle solved by this program has a few key rules:
- Three coins are drawn from a pool of equal numbers of 1, 5, 10, and 25 cent coins.
- The pool automatically refills to the original equal amount when a coin is drawn.
- Three strings and formed with lengths corresponding to the values of the three coins.
- What is the probability that the three strings can form a triangle?
## Solution with PPL
The solution to this problem can be approximated using code and found analytically through mathematical manipulation. The probabilistic programming language WebPPL can be used to combine the analysis of math with the expressiveness of a programming language.
