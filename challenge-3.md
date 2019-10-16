# Ruby Code Golf Night - Challenge #3

For the `dict/a` file:

1. Scan until you find a word where the letter z is followed by any letter, then the letter v.
2. Print the line number, a colon, and the word.
3. Continue scanning and go back to rule 1.

The contents of `dict/a` will be provided as the standard input to the program:

```ruby
ruby 3.rb < dict/a
```

The correct answer will match the output of

```
grep -n z.v dict/a
```
