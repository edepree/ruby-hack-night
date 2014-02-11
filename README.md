ruby-hack-night
===============

# decoder_ring.rb
##### Ruby v1.9.3
##### A solution for the puzzle at http://www.puzzlenode.com/puzzles/12-secret-messages

The input file will contain an encrypted keyword and and encrypted message. The keyword is a common English word encrypted with a Caesar cipher. Your job will be to figure out what that keyword is and then use it to unravel the secret message by writing a Vigenère cipher decryption program.

The output file should contain the decrypted secret message.

# english_numerals.rb
##### Ruby v1.9.3
##### From [Best of Ruby Quiz](http://pragprog.com/book/fr_quiz/best-of-ruby-quiz)

Create Ruby code to translate a number to its English-language form:
* 7 == seven
* 42 == forty-two
* 2001 == two thousand and one
* 1999 == one thousand nine hundred and ninety-nine

# countdown.rb
##### Ruby v1.9.3
##### From [Best of Ruby Quiz](http://pragprog.com/book/fr_quiz/best-of-ruby-quiz)

According to Brian Candler in the Ruby Quiz book, Countdown is a British quiz show that asks contestants to solve an arithmetic problem.  We'll write a program to solve it.

#### Rules:

* Input is a list of six numbers, one from [25, 50, 75, 100] and five from (1..10) that the player may choose.
* A random target number in the range (100..999) is provided by a program.
* The contestant has 30 seconds to provide a series of arithmetic operations (+, -, *, /) on the six smaller numbers that result in the target, or at least as close as possible to the target.

#### Example:

* List of numbers 100, 5, 5, 2, 6, and 8.
* Target 522.

###### Solutions:

* (5 * 100) + ((5 + 6) * 2)
* (100 + 6) * 5 - 8

# phone_quiz.rb
##### Ruby v1.9.3
##### From [Best of Ruby Quiz](http://pragprog.com/book/fr_quiz/best-of-ruby-quiz)

Companies like to list their phone numbers using the letters printed on telephones. This makes the number easier to remember for customers. A famous example is 1-800-PICK-UPS. This quiz is to write a program that shows the user possible matches for a list of provided phone numbers.

#### Example:

If your program is input the following number: 873.7829, one possible line of output is this: USE.RUBY