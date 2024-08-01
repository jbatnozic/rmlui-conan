# Rmlui-conan
[Conan](https://conan.io/) recipe for [RmlUi](https://github.com/zerotier/libzt).

Latest version: `5.1`

Based on the official recipe at: https://github.com/conan-io/conan-center-index/tree/master/recipes/rmlui/4.x
(that one is lagging behind with versions)

# License
MIT (see [LICENSE](https://github.com/jbatnozic/libzt-conan/blob/master/LICENSE)).
The licence applies ONLY to the recipe files themselves (the ones in this repository), and NOT to the library being packaged (libzt).

Also see: Licence of the original recipe: https://github.com/conan-io/conan-center-index/blob/master/LICENSE

# Instructions

## Getting the package

```
conan create . --profile=<profile> --user=<user> --channel=<channel> --build=missing
```

You can choose the `user` and `channel` arbitrarily, however, for compatibility with other Conan packages created by 
me, I recommend that you use user `jbatnozic` and channel `stable`.

For `profile`, use `default` or one of your own. 

**Note:** If Conan can't resolve some of the dependencies, you need to add the remote where it can be found:
```
conan remote add conancenter https://center.conan.io
```

## Consuming the package
TODO
