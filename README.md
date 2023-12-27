# hello (action)
Simple custom github action

returns `{h,H}ello ${person}`

`person` is optional, default is `world`

## @v1 returns `hello ${person}`
```
      - uses: dennisyau1885/hello@v1
```
```
hello world
```

```
      - uses: dennisyau1885/hello@v1
        with:
          person: 'bob'
```
```
hello bob
```

# @v2 returns `Hello ${person}`

```
      - uses: dennisyau1885/hello@v2
        with:
          person: 'baz'
```
```
Hello baz
```
