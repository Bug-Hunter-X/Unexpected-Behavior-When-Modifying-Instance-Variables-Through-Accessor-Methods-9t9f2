# Ruby: Unexpected Instance Variable Modification

This example showcases a common error in Ruby where attempts to modify instance variables through accessor methods without an explicit setter fail silently.

The `bug.rb` file demonstrates the issue. The `MyClass` has a getter (`value`) but no setter. Assigning a value to `my_object.value` does not modify the internal `@value` instance variable.