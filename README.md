# problem statement
removes files & dirs ignored by git

# example usage

> note: in examples, VERSION represents a version of the git.clone-https pkg

## install

```shell
opctl pkg install github.com/opspec-pkgs/git.clone-https#VERSION
```

## run

```
opctl run github.com/opspec-pkgs/git.clone-https#VERSION
```

## compose

```yaml
name: dummy
inputs:
  srcDir:
    dir:
      default: .
  opts:
    string:
      default: -ffXd -e !.idea/ # use custom clean opts
run:
  op:
    pkg: { ref: github.com/opspec-pkgs/git.clone-https#VERSION }
    inputs: { username, password,  }
    outputs: { srcDir }
```
