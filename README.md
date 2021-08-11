# Reusable
## A Reusable Libariry for Swift

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

A Swift mixin to use UITableViewCells, UICollectionViewCells and UIViewControllers in a type-safe way, without the need to manipulate their String-typed reuseIdentifiers. This library also supports arbitrary UIView to be loaded via a XIB using a simple call to loadFromNib()

- Type-safe UITableViewCell / UICollectionViewCell
- Type-safe XIB-based reusable views
- ✨Magic ✨

## Introduction about this lib
> This library aims to make it super-easy to create, dequeue and instantiate reusable views anywhere this pattern is used: 
			from the obvious UITableViewCell and UICollectionViewCell to 	custom UIViews, 	even supporting UIViewControllers from Storyboards.

> All of that simply by marking your classes as conforming to a protocol, without having to add any code, and creating a type-safe API with no more String-based API

## Security:
> Reusable lib is just apply for the UILayer

## Why should we use Reusable:

- Type-safe UITableViewCell / UICollectionViewCell:
    > No need for you to manipulate reuseIdentifiers Strings manually anymore!
	
    > No need to force-cast the returned UITableViewCell instance down to your MyCustomCell class either!
- Type-safe XIB-based reusable views:
    > Reusable also allows you to create reusable custom views designed in Interface Builder to reuse them in other XIBs or Storyboards, or by code. 
		   This allows you to treat those views like custom UI widgets that can be used in multiple places in your app.

- AppSize improvement:
    > Because the idea of Reusable is using the UIViewType for make the identifierString so we no need redeclared the identifierString for UITableViewCell or Storyboard  manual So the duplicate code style like setup the cell Identifier will less than when we use the normal way for initialization the UITableViewCell or something like this 
- Very easy for use:
    > All we need to to is conform the confirm protocol of reusable for UITableViewCell, UICollectonViewCell, CustomView, ….. and use the functionality of this libs
- take less duplicate code: 
    > In the another way. If we want to our app independent on this lib we can create the custom protocol like this  Libs idea. it very simple but it will our app take less duplicate code
## AppSize
- The Lib very small so the size of this lib less than [400kb] if we want to create the same idea

## Iplementation complexity
> Easy for implementation
## Installation
Reusable requires:
> [Cocoapods](https://cocoapods.org/) version: `4.0.2 +` to run on `Swift4`.

> [Cocoapods](https://cocoapods.org/) version: `4.1.0 +` to run on `Swift5`.
>`...`

Install for cocoa pods.

```sh
pod 'Reusable'
```

## License

MIT

**Free Software, Hell Yeah!**
