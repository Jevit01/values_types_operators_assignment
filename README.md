# Values, Types & Operators Exercises

1. What are the types of the following expressions and what do they evaluate to, and why?
* `17`
\\number, because its only a number
* `1 + 2 * 3 + 4`
\\expression, evaluates to 11 a number, because its a math expression
* `800 / 80 / 8`
\\expression, evaluates to 1.25 a number, because its a math expression
* `400 > 200`
\\boolean, evaluates to true, because you are using a comparison operator
* `1 !== 1`
\\boolean, evaluates to false, because you are using a comparison operator
* `true || false`
\\boolean, evaluates to true, because its a logical operator
* `true && false`
\\boolean, evaluates to false,
because its a logical operator
* `20 % 6`
\\expression, evaluates to 2 a number, because its a math expression
* `'a' + 'b'`
\\string, evaluates to ab, because you are adding two letters that each surrounded by ''

2. What will the following return?
* `typeof 4`
\\number
*  `typeof 'hello'`
\\string
*  `typeof true`
\\boolean
* `2 === 1 || 3 === 4`
\\false

3. Create a truth table for the expression A || B.

For reference, here is a truth table for the expression A && B:

``` js
|   A   |   B   | A || B |
| true  | true  | true   |
| false | true  | true   |
| true  | false | true   |
| false | false | false  |

|   A   |   B   | A & B | 
| true  | true  | true  |
| false | true  | false |
| true  | false | false |
| false | false | false |

```
4. Create a truth table for the expression !A && !B.

For reference, here is a truth table for the expression A && !B:

``` js
| !A   | !B   | !A && !B |
| true | true |   true   |
| true | false|  false   |
| false| true |  false   |
| false| false|  false   |


|   A   |   B   |   !B   | A & B |
| true  | true  | false  | false |
| false | true  | false  | false |
| true  | false | true   | true  |
| false | false |  true  | false |

```
5. Write a step-by-step evaluation for the following expression (remember order of operations): `2 + 3 * 2 + 1`.
\\2 + 3 * 2 + 1
\\2 + 6 + 1
\\8 + 1
\\9

  For reference, here is a exp of a step-by-step evaluation:
  ```js
  1 + 2 + 3 + 4
      3 + 3 + 4
          6 + 4
              10
  ```

 6. Write a step-by-step evaluation for the following expression (remember order of operations): `4 / 2 + 8 / 4`.
 \\4 / 2 + 8 / 4
 \\2 + 2
 \\4

 7. Write a step-by-step evaluation for the following expression: `'ca' + 'ter' + 'pi' + 'llar'`.
 \\ 'ca' + 'tar' + 'pi' + 'llar'
 \\ 'catar' + 'pi' + 'llar'
 \\ 'catarpi' + 'llar'
 \\ 'catarpillar'
 8. Write a step-by-step evaluation for the following expression: `2 * 4 === 8 && 'car' + 'pool' === 'carpool'`.
 \\ 2 * 4 === 8 && 'car' + 'pool' === 'carpool'
 \\ 8 === 8 && 'car' + 'pool' === 'carpool'
 \\ 8 === 8 && 'carpool' === 'carpool'
 \\ true
