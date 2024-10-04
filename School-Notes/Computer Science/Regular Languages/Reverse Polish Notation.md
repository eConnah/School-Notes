There are three different ways to write an arithmetic expression.
- Infix the notation used in normal mathematics:
$$a \cdot (b+c) / d$$

- Prefix (Polish Notation) the operator comes before the operands:
$$/ \cdot a + b c d$$

- Postfix (Reverse Polish Notation) the operator comes after the operands.
$$a b c + \cdot d /$$
Order of Precedence
- ~ (used for minus numbers)
- ^ (used for exponents)
- * /
- + -
- =

# Conversion Methods
## Translation by Numbering
This algorithm works by numbering operands and operators. Starting from the left allocate numbers from 1 to operators and operands as follows:
1. Number all operands.
2. If you past an operator and you now have enough operands to perform its calculation you number it too.
3. Backup to the final operator and allocate it the final number.
4. You then write everything in order of number.

## Translation by Bracketing
This method works by fully bracketing the expression and rearranging the operators inside the
brackets:
1. Add brackets to make explicit the order of precedence, including exponentiation.
2. Move the operator in each set of brackets to the end position.
3. Remove all the brackets.

## Translation by Binary Tree
This method works by building a binary tree from the infix expression and then traversing it using a post- order traversal algorithm.
1. Decompose operands into two child nodes; pay attention to precedence and brackets.
2. Choose the highest precedence operator not embedded in parentheses, as the root.
3. / has been chosen as the root in the tree below, but you could equally well choose * as it has equal precedence.