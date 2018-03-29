# Clibgit2
### Swift Package Manager wrapper for the libgit2 system library

## Installation
Install the library with brew
```
brew install libgit2
```
Or manually link against a different binary at build time
```
swift build -Xlinker -L/usr/local/lib/
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
