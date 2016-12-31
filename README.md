# Dgrep

dgrep is grep program for tsv or csv file.

## Installation

install it yourself as:

    $ gem install dgrep

## Usage

If there is this file

```:sample.txt
	a	b	c
d	1	2	3
e	4	5	6
f	7	8	9
```

and you want to get this output,


```
	a	b	c
d	1	2	3
```

you only do

```
$ dgrep "d" sample.txt
```

if you wan to get this outpus,

```
	a
d	1
e	4
f	7
```

you only do

```
dgrep -c "a" sample.txt
```

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/nishimoto/dgrep.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

