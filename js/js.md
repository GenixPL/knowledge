+ `===` - strict comparison (equal value and equal type)

+ we can convert `() => { return { a: 'A' }; }` into `() => ({ a: 'A' })` (by wrapping a function with `()` we say that its only puropose is to return something)