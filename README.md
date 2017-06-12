## Scope, hoisting and compartmentalization

### Answer the following:
In you own words, explain the concepts of scope, hoisting, compartmentalization.

Scope details when something is declared and when it's used. Depending on where that item is declared whether in global scope or in local scope like inside a function, shows when that item can be used.

Hoisting explains all declarations are "hoisted" to the top of the scope. The read top to bottom.

compartmentalization is when dealing with scope if a variable needs to be "redeclared" if assignment happens in both scopes.

### Provide examples for all three, below:

#### Scope:
a variable declared inside a function (local scope) cannot be used outside of that function (global scope)

#### Hoisting:
a variable can be assigned at the top of the scope, global or local, and is declared at the bottom of that scope because hoisting will move all declarations to the top.

#### Compartmentalization:
a variable that's declared and assigned in global scope will need to be redeclared if assigned inside a function if that function is calling for a different value in the function.
