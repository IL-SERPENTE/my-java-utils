[![Build Status](https://snap-ci.com/ashwanthkumar/my-java-utils/branch/master/build_image)](https://snap-ci.com/ashwanthkumar/my-java-utils/branch/master)

# my-java-utils
Set of Java utils that I take along with my OSS java projects. Most of them are influenced from [Scala](http://scala-lang.org/) world and [Guava](https://github.com/google/guava) library. Library has zero external dependencies. If you find some implementations can be better, please do let me know.

## Features
### List
- Lists#map
- Lists#filter
- Lists#foldL
- Lists#find
- Lists#mkString
- Lists#Nil
- Lists#concat
- Lists#flatten

### Set
- Sets#copy
- Sets#isEmpty
- Sets#nonEmpty

### Iterable
- Iterables#exists
- Iterables#forall
- Iterables#head
- Iterables#headOption
- Iterables#isEmpty
- Iterables#nonEmpty
- Iterables#toMap
- Iterables#foreach

### Maps
- Maps#of
- Maps#builder

### Lang
- Option / Some / None
- Tuple2 / Tuple3
- Function
- Predicate

### Functions
- Functions#identity

### StringUtils
- StringUtils#isNotEmpty
- StringUtils#isEmpty
- StringUtils#startsWith
- StringUtils#size

### IO
- IO#fromFile
- IO#linesFromFile

## Dependencies

For Maven,
```xml
<dependency>
  <groupId>in.ashwanthkumar</groupId>
  <artifactId>my-java-utils</artifactId>
  <version>0.0.7</version>
</dependency>
```

For SBT,
```
libraryDependencies += "in.ashwanthkumar" % "my-java-utils" % "0.0.7"
```

## License
http://www.apache.org/licenses/LICENSE-2.0
