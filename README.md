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
```sass
@while ${1:condition} {
  ${2:code}
}
```
- [fr] @for
```sass
@for ${1:var} from ${2:start} through ${3:end} {
  ${4:code}
}
```
- [ar] @at-root
```sass
@at-root {
  ${1:code}
}
```
- [db] @debug
```sass
@debug ${1:code};
```
- [eh] @each
```sass
@each ${1:var} in ${2:list} {
  ${3:code}
}
```
- [wn] @warn
```sass
@warn ${1:code};
```
- [er] @error
```sass
@error ${1:code};
```

#### maps functions

- [mg] map-get
```sass
$get: map-get(${1:list}, ${2:value});
```

- [mr] map-remove
```sass
$remove: map-remove(${1:list}, ${2:value});
```

- [mk] map-keys
```sass
$keys: map-keys(${1:list}});
```

- [mv] map-values
```sass
$values: map-values(${1:values});
```

- [mm] map-merge
```sass
$merge: map-merge(${1:list1}, ${2:list2});
```

- [mhk] map-has-key
```sass
$has-key: map-has-key(${1:list}, ${2:value});
```
