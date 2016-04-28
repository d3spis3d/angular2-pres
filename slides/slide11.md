# Decorators

- Stage 1 ECMAScript proposal
- Similar to Python decorators and Java annotations

<pre>
  <code>
  // A simple decorator
  @annotation
  class MyClass { }

  function annotation(target) {
   // Add a property on target
   target.annotated = true;
  }
  </code>
</pre>
