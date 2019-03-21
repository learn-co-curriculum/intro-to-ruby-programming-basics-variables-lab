# Variable Assignment

## Learning Goals

- Assign a local variable

## Instructions

You will assign a local variable named `greeting` that is equal to `"Hello World"`.

You should first make sure the test suite is running correctly by running
`learn`.

Upon the first run of the test suite you should see:

```
Failures:

  1) ./variable.rb defined a local variable called greeting and set it equal to 'Hello World'
     Failure/Error: raise NameError, "local variable `#{variable}` not defined in #{file}."

     NameError:
       local variable `greeting` not defined in ./variable.rb.
     # ./spec/spec_helper.rb:14:in `rescue in get_variable_from_file'
     # ./spec/spec_helper.rb:11:in `get_variable_from_file'
     # ./spec/variable_spec.rb:5:in `block (2 levels) in <top (required)>'
     # ------------------
     # --- Caused by: ---
     # NameError:
     #   local variable `greeting' is not defined for #<Binding:0x00007fe6cf9b7e28>
     #   ./spec/spec_helper.rb:12:in `local_variable_get'

Finished in 0.00407 seconds (files took 0.47977 seconds to load)
1 example, 1 failure
```

To solve this test failure, create a local variable `greeting` in the
`variable.rb` file. Set `greeting` equal to the string `"Hello World"`. Run
`learn` to confirm you have correctly created the variable.

Once finished, run `learn submit` to submit your work.

## Resources

- [Variables][wikibook]

[wikibook]: https://en.wikibooks.org/wiki/Ruby_Programming/Syntax/Variables_and_Constants

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/ruby-variable-assignment' title='Variable Assignment'>Variable Assignment</a> on Learn.co and start learning to code for free.</p>
