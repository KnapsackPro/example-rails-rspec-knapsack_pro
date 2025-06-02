# README

```
bundle install
```

# RSpec + Knapsack Pro

The RSpec `before(:suite)` hook is defined in `spec/spec_helper.rb`.

Edit `bin/knapsack_pro` to use your API token.

Run RSpec tests with Knapsack Pro:

```
bin/knapsack_pro
```

The expected output:

```
RSpec before(:suite) hook called.
.........

Finished in 0.42772 seconds (files took 0.19781 seconds to load)
9 examples, 0 failures
```

The RSpec `before(:suite)` hook is called.
