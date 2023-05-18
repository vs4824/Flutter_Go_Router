# Flutter Go Router

A declarative routing package for Flutter that uses the Router API to provide a convenient, url-based API for navigating between different screens. You can define URL patterns, navigate using a URL, handle deep links, and a number of other navigation-related scenarios.

## Features

GoRouter has a number of features to make navigation straightforward:

1. Parsing path and query parameters using a template syntax (for example, "user/:id')

2. Displaying multiple screens for a destination (sub-routes)

3. Redirection support - you can re-route the user to a different URL based on application state, for example to a sign-in when the user is not authenticated

4. Support for multiple Navigators via ShellRoute - you can display an inner Navigator that displays its own pages based on the matched route. For example, to display a BottomNavigationBar that stays visible at the bottom of the screen

5. Support for both Material and Cupertino apps

6. Backwards-compatibility with Navigator API


