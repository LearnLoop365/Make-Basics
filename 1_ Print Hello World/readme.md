# Print Hello World

## with Recipe Echoing (Default)

```
foo:
	echo Hello World
```

```
make foo
```

## Suppressing Recipe Echoing per Command Using `@`
```
bar:
	@echo Hello World
```

```
make bar
```

## Suppressing All Recipe Echoing Using `-s`, `--silent`, `--quiet` Flags
```
make -s foo
```
