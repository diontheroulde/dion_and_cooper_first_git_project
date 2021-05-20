# My 4 Favorite Ruby Methods

### `Argument Error`
It is raised when the arguments are wrong and there isn't a more specific exception class.

```sh
[1, 2, 3].first(4, 5)
```

### `Array`
Is an ordered collection of objects called elements 

```sh
ary = Array.new    #=> []
Array.new(3)       #=> [nil, nil, nil]
Array.new(3, true) #=> [true, true, true]
```

### `Class`
These are first class objects in ruby
```sh
class Name
 # some code describing the class behavior
end
```


### `TypeError`
Raised when encoutering an object when it is not of the expected type.

```sh
[1, 2, 3].first("two")
```