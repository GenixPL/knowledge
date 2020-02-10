+ `===` - strict comparison (equal value and equal type)

+ we can convert
  <pre>
  () => {
    return { a: 'A' }; 
  }
  </pre> 
  into
  <pre>
  () => ({ a: 'A' })
  </pre>
  (by wrapping a function with `()` we say that its only puropose is to return something)