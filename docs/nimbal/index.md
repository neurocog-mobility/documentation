# NiMBaL Toolkit

**nimbalwear** is an open source toolkit for processing data from wearable sensors.
For toolkit source visit [nimbalwear](https://github.com/nimbal/nimbalwear).

## Installation

To install the latest release of nimbalwear directly from GitHub using pip, run the following line in terminal or console:

`pip install git+https://github.com/nimbal/nimbalwear`

To install a specific release, insert M.m after the repository name to install from the branch associated with that minor release. For example:

`pip install git+https://github.com/nimbal/nimbalwear@0.21`

## Package Dependency
To include the latest release of nimbalwear as a dependency in your Python package, include the following line in `setup.py` or include the string within the list alongside your other dependencies:

```
install_requires=['nimbalwear@git+https://github.com/nimbal/nimbalwear@[version]']
```

To include a specific release, replace `[version]` with the branch associated with that minor release.
