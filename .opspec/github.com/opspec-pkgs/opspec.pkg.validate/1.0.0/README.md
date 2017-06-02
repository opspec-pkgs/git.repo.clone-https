# problem statement
validates an opspec package

# example usage

> note: in examples, VERSION represents a version of the opspec.pkg.validate pkg

## install

```shell
opctl pkg install github.com/opspec-pkgs/opspec.pkg.validate#VERSION
```

## run

```
opctl run github.com/opspec-pkgs/opspec.pkg.validate#VERSION
```

## compose

```yaml
run:
  op:
    pkg: { ref: github.com/opspec-pkgs/opspec.pkg.validate#VERSION }
    inputs: { pkg }
```

