Correct answer **d) will not compile due to failed type inference**

* Declaration and use-site variances are opposite, this is correct
  * see [Kotlin docs](https://kotlinlang.org/docs/reference/generics.html) for the explanation  
* `Hipster()` cannot be called because T cannot be inferred
  * Unline Java, Kotlin doesn't allow not inferred type parameters to be Any/Object
  