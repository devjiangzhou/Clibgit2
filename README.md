# Clibgit2
### Swift Package Manager wrapper for the libgit2 system library

## Installation
```
brew install libgit2
```

## Inclusion as dependency
**Note: there is no need to include a dependency on the individual targets**

In Package.swift
```
dependencies: [
	.package(url: "git@github.com:stonehouse/Clibgit2.git", .branc("master")
]
```
In individual files
```
import Clibgit2
```
