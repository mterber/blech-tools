# Blech Tools

This repository comprises tools in the context of the Blech language and compiler (See: http://blech-lang.org)
Currently, the following tools are available:
* `ide/` - Integrated Development Environment plugin for the Visual Studio Code (https://code.visualstudio.com/)

## Working with the repository
The sources of the Blech compiler are required for building the Blech tools. For this reason, the Blech compiler repository is added as a submodule. Consequently, you always have to clone and update recursively to make sure that the dependent sources are available and up-to-date.

### Clone
In order to initially clone this repository just run

```
git clone --recurse-submodules https://github.com/boschresearch/blech-tools.git
```

### Update
In order to update this repository with the latest changes from the remote just run
```
git pull --recurse-submodules
```

## License

Blech tools are open-sourced under the Apache-2.0 license. See the
[LICENSE](LICENSE) file for details.

For a list of other open source components included in Blech tools, see the
file [3rd-party-licenses.txt](3rd-party-licenses.txt).
