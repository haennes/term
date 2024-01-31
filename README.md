# what

[Typst](https://github.com/typst/typst) template for emulating terminal screenshots

# how

## input

```typst
#import "term.typ": term

#term(
  content: [`$ ls
term.typ`],
)
```

## output

<img src="./examples/raw/raw.svg" width="50%">

# why

- no need to take screenshots
- no need to store screenshots
- vector graphics instead of raster

# how (in-depth)

## download the template

```
curl https://raw.githubusercontent.com/qo/term/main/term.typ --output term.typ
```

## import it wherever you want it

```typst
#import "term.typ": term
```

## pass the content parameter to the `term` function

# examples

more examples can be found in `examples` directory
