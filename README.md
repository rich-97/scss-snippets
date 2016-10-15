# Scss Snippets for Atom

## install

You can install the settings by pressing `ctrl+,` opened atom, then you go to `install` and looking on packages `scss-snippets`.

Or with the command since your terminal:

```sh
apm install scss-snippets
```

### Snippets

#### control flow

- [wh] @while
```scss
@while ${1:condition} {
  ${2:code}
}
```
- [fr] @for
```scss
@for ${1:var} from ${2:start} through ${3:end} {
  ${4:code}
}
```
- [ar] @at-root
```scss
@at-root {
  ${1:code}
}
```
- [db] @debug
```scss
@debug ${1:code};
```
- [eh] @each
```scss
@each ${1:var} in ${2:list} {
  ${3:code}
}
```
- [wn] @warn
```scss
@warn ${1:code};
```
- [er] @error
```scss
@error ${1:code};
```

#### maps functions

- [mg] map-get
```scss
$get: map-get(${1:list}, ${2:value});
```

- [mr] map-remove
```scss
$remove: map-remove(${1:list}, ${2:value});
```

- [mk] map-keys
```scss
$keys: map-keys(${1:list}});
```

- [mv] map-values
```scss
$values: map-values(${1:values});
```

- [mm] map-merge
```scss
$merge: map-merge(${1:list1}, ${2:list2});
```

- [mhk] map-has-key
```scss
$has-key: map-has-key(${1:list}, ${2:value});
```
### strings functions

- [si] str-insert

```scss
$insert: str-insert(${1:string}, ${2:substring}, ${3:index});
```

- [sx] str-index
```scss
$index: str-index(${1:string}, ${2:substring});
```

- [sl] str-length
```scss
$length: str-length(${1:string});
```

- [ss] str-slice
```scss
$slice: str-slice(${1:srting}, ${2:start}, ${3:end});
```

- [tu] to-upper-case
```scss
$upper: to-upper-case(${1:string});
```

- [tl] to-lower-case
```scss
$lower: to-lower-case(${1:string});
```

### list functions

- [nth] nth
```scss
$nth: nth(${1:list}, ${2:index});
```

- [in] index
```scss
$index: index(${1:list}, ${2:value});
```

- [jo] join
```scss
$join: join(${1:list1}, ${2:list2});
```

- [ap] append
```scss
$append: append(${1:list}, ${2:value});
```

### color functions

- [dk] darken
```scss
$darken: darken(${1:color}, ${2:amount});
```

- [lt] lighten
```scss
$lighten: lighten(${1:color}, ${2:amount});
```

- [st] saturate
```scss
$saturate: saturate(${1:color}, ${2:amount});
```

- [dt] desaturate
```scss
$desaturate: desaturate(${1:color}, ${2:amount});
```
