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

<aside class="notes">
  <ul>
    <li>One important piece of syntax, which is not Angular2 specific, is JavaScript decorators</li>
    <li>These are a Stage 1 ECMAScript proposal currently, and available in TypeScript</li>
    <li>Decorators are functions that modify classes, class properties or object properties in a declarative</li>
    <li>Angular2 makes a lot of use of decorators</li>
  </ul>
</aside>
