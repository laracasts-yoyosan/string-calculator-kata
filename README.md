# String calculator

- StringCalculator::add('2,3,4') returns 2 + 3+ 4 = 9
- StringCalculator::add('') returns 0
- StringCalculator::add delimiters can be , and \n
- StringCalculator::add('1,2,3,1000') returns 6 by ignoring numbers bigger than or equal to 1000

# Usage

```
composer install
./vendor/bin/phpspec run
```
