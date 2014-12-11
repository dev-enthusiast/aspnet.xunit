## <a href="https://github.com/xunit/xunit"><img src="https://raw.github.com/xunit/media/master/full-logo.png" title="xUnit.net KRE Runner" /></a>

This runner enables [xUnit.net](https://github.com/xunit/xunit) test to run on the [K Runtime Environment](https://github.com/aspnet/KRuntime).

### Usage

To install this package, add the following to your project.json

```JSON
{
    "dependencies": {
        "xunit.runner.kre": "1.0.0-*"
    },
    "commands": {
        "test": "xunit.runner.kre"
    }
}
```

To run tests from the command line, use the following.

```Shell
# Restore NuGet packages
kpm restore

# Run tests
k test
```
