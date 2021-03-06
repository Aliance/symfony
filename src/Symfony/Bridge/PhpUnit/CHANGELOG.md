CHANGELOG
=========

4.0.0
-----

 * support for the `testLegacy` prefix in method names to mark a test as legacy
   has been dropped, use the `@group legacy` notation instead
 * support for the `Legacy` prefix in class names to mark tests as legacy has
   been dropped, use the `@group legacy` notation instead
 * support for passing an array of mocked namespaces not indexed by the mock
   feature to the constructor of the `SymfonyTestsListenerTrait` class was
   dropped

3.4.0
-----

 * added a `CoverageListener` to enhance the code coverage report

3.3.0
-----

 * using the `testLegacy` prefix in method names to mark a test as legacy is
   deprecated, use the `@group legacy` notation instead
 * using the `Legacy` prefix in class names to mark a test as legacy is deprecated,
   use the `@group legacy` notation instead

3.1.0
-----

 * passing a numerically indexed array to the constructor of the `SymfonyTestsListenerTrait`
   is deprecated, pass an array of namespaces indexed by the mocked feature instead
