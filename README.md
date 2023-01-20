# Welcome to 166's mobile env.

Hello newcomers! As a mobile team, we have some responsibilities such as: To do everything in time or till the deadline, Follow architecture and writing clean code.

*The guidelines should be heeded and recommended to be read at least once.*

# DDD
**Current architecture**

"Domain-Driven Design (DDD) is **a software design method wherein developers construct models to understand the business requirements of a domain**."

Tutorials can be helpfull to adopt:
https://youtube.com/playlist?list=PLB6lc7nQ1n4iS5p-IezFFgqP6YvAJy84U

## Design patterns

To write clean and understandable code, design patterns need to be learned. (book advice: **gang of four design patterns**)

## Algorithms

The space and time complexity of sorting and searching algorithms need to be learned.


## App Testing

Writing code together with tests requires plenty of time and much effort. That's why for the first releases of our apps we don't apply testing such as unit tests. But if our project requires testing and the time for testing is so less compared to debugging, we have to do TDD. 

## Platform Independent code

Most of the time we will develop apps for android OS. If the company decides to switch to **iOS** in the future, it must not be that much hard for us.

## Git push

Each commit must follow feature-related code. Pushing code that is just a little piece of the feature must not follow. And meaningful commit messages are appreciated.

## Required libraries for working :

1. [DartZ](https://pub.dev/packages/dartz) - functional programming
2. [SecreenUtil](https://pub.dev/packages/flutter_screenutil) - Figma to Flutter helper
3. [auto_route](https://pub.dev/packages/auto_route) - Generate routes, tabbars, bottom navbars
4. [json_annotation](https://pub.dev/packages/json_annotation) toJson, .FromJson
5. [flutter_hooks](https://pub.dev/packages/flutter_hooks) - TextField controller, animation controller auto dispose
6. [riverpod](https://pub.dev/packages/riverpod) - Simple state management, form validation, and so on
7. [flutter_bloc](https://pub.dev/packages/flutter_bloc) **Main** State management holder
8. [dio](https://pub.dev/packages/dio) http client, dio interceptors
9. [retrofit](https://pub.dev/packages/retrofit) generate requests automatically
10. [shared_preferences](https://pub.dev/packages/shared_preferences) - For simple local storing
11. [intl](https://pub.dev/packages/intl) - Country based formatting
12. [url_launcher](https://pub.dev/packages/url_launcher) To open external apps
13. [socket_io_client](https://pub.dev/packages/socket_io_client) - node.JS socket.io connection
14. [pull_to_refresh](https://pub.dev/packages/pull_to_refresh) - pagination and refresh helper
15. [get_it](https://pub.dev/packages/get_it) dependency injection
16. [flutter_localizations](https://api.flutter.dev/flutter/flutter_localizations/flutter_localizations-library.html) - To create multi-language support
