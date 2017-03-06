#Stormpath is Joining Okta
We are incredibly excited to announce that [Stormpath is joining forces with Okta](https://stormpath.com/blog/stormpaths-new-path?utm_source=github&utm_medium=readme&utm-campaign=okta-announcement). Please visit [the Migration FAQs](https://stormpath.com/oktaplusstormpath?utm_source=github&utm_medium=readme&utm-campaign=okta-announcement) for a detailed look at what this means for Stormpath users.

We're available to answer all questions at [support@stormpath.com](mailto:support@stormpath.com).


# AngularJS + Spring Boot + Stormpath Example, Part 2

This project is an example application for a typical [AngularJS](http://angularjs.org/) webapp with a [Spring Boot](https://projects.spring.io/spring-boot/) backend.

You can read about how this application was created on [the Stormpath blog](https://stormpath.com/blog/angularjs-spring-boot-tips). Feel free to copy any code in this project for your own use in accordance with the [MIT license](LICENSE).

Through this project's commit logs, it shows you how to:

1. [Make Browsersync work with AngularJS's HTML5 mode](https://github.com/stormpath/stormpath-angularjs-access-control-cors-example/commit/0dc3549e2a70d978fb551556bfe205f0907ea5af)
2. [Limit access to states and hide links with Stormpath's AngularJS SDK](https://github.com/stormpath/stormpath-angularjs-access-control-cors-example/commit/fe8e1853c7771829748ab967dad3c5266c94b317)
3. [Easy CORS configuration for Spring Boot](https://github.com/stormpath/stormpath-angularjs-access-control-cors-example/commit/d7ad3cc8648626e8f9b8aa4bb40e19cda3a7dd67)

**Prerequisites**: Java 8, Node.js, Maven, Gulp.js, a [Stormpath Account](https://api.stormpath.com/register), and an `apiKey.properties` file in `~/stormpath/`.

To run the Spring Boot backend, execute `mvn spring-boot:run`.

To run the AngularJS frontend, execute `npm install && gulp`. 
