# testNG
TestNG related examples - my collections

# Advantages of using testNG
TestNG is designed/ intended to cover all categories of testing like unit, useful, end-to-end, reconciliation, and so forth...
Following are few points to mention:<br>
* <b>Annotations:</b><br>
   1. @BeforeTest<br>
   2. @AfterTest<br>
   3. @Test:<br>
   4. Priority - @Test(priority = 0), @Test(priority = 1).  Lower priority will run first i.e., 0
   5. Group - @Test(groups = { "fast" }), @Test(groups = { "slow" }) - A test can belong to multiple groups
   6. Data Driven - @DataProvider

* <b>Threads</b><br>
   Run your tests in arbitrarily big thread pools with various policies available (all methods in their own thread, one thread per test class, etc...).
   Test that your code is multithread safe.
* Flexible test configuration.
* Support for parameters.
* Powerful execution model (no more TestSuite).
* Supported by a variety of tools and plug-ins (Eclipse, IDEA, Maven, etc...).
* Embeds BeanShell for further flexibility.
* Default JDK functions for runtime and logging (no dependencies).
* Dependent methods for application server testing.
* No need to extend a class or implement an interface.
