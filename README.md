# Problem statement
clones a git repo via https transport

# Example usage

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
op:
   pkg: { ref: github.com/opspec-pkgs/git.clone-https#VERSION }
   inputs: 
      username:
      password:
      url:
   outputs:
      repo:
```

# Support

join us on [![Slack](https://opspec-slackin.herokuapp.com/badge.svg)](https://opspec-slackin.herokuapp.com/)
or [open an issue](https://github.com/opspec-pkgs/git.clone-https/issues)
