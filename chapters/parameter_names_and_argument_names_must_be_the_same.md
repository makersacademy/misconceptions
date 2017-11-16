# Parameter names and Argument names must be the same

Play with the following examples: changing the names of the parameters and the arguments.

As always, try to have a hypothesis for what will happen before you make a change.

#### Ruby Example

```eval-ruby
def greet(name)
  return "Hi " + name
end

# Should this work?
name = "Mary"
greet(name)

# Should this work?
first_name = "Mary"
greet(first_name)
```

#### JavaScript Example

```eval-js
function greet(name) {
  return "Hi " + name;
};

// Should this work?
var name = "Mary";
greet(name);


// Should this work?
var firstName = "Mary";
greet(firstName);
```