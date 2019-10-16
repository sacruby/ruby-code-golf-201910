# Ruby Code Golf Night - Challenge #1

In the `dict` folder are a bunch of files with words in them.  You need to count the number of words in all files. A "word" in this case is any sequence of alphanumeric characters separated by whitespace.

The files will be provided as arguments to your program:

```ruby
ruby 1.rb dict/*
```

The correct answer should match:

```
cat dict/* | wc -w
```

Hint: While it looks like there is one word per line, that is not always the case.
