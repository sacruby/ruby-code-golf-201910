# Ruby Code Golf Night - Challenge #2

For the `dict/a` file:

1. Scan until you find a word where the third letter is z.
2. Print that word and and all following words until the fourth letter is a consonant, including that word.
3. Continue scanning and go back to rule 1.

The contents of `dict/a` will be provided as the standard input to the program:

```ruby
ruby 2.rb < dict/a
```

The correct answer:

```
adz
adze
adzer
adzooks
ae
aeacides
afzelia
aga
agabanee
aizle
aizoaceae
aizoaceous
aizoon
ajaja
anzac
anzanian
ao
aogiri
aoife
arzan
arzava
arzawa
arzrunite
arzun
as
as
asa
asaddle
```

# Hints

1. As you can see, there are some duplicate words in the input.
2. You may stop printing at one line (where fourth letter is a consonant), and start printing at the next line (where third letter is z).
