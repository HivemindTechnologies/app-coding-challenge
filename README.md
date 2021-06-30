# Hivemind App Coding Challenge

Welcome to the App Coding Challenge!

In this challenge you should create a simple app that allows to search movies on [TMDB](https://www.themoviedb.org).

# Requirements

- Write the app using [Flutter](https://flutter.dev), so that it runs on both Android and iOS.
- The app should consist of two screens: `Search` and `Details`.
- The search should search for movies only, using the TMDB movie API: https://developers.themoviedb.org/3/search/search-movies
- To use the API, create an account on [TMDB](https://www.themoviedb.org) and go to `settings/API` (<https://www.themoviedb.org/settings/api>)
- The code should live in a private git repository on github. We will give you github usernames that you should invite.

## Search Screen

- The search screen should have a textfield and a search button.
- A list of search results should be displayed below the field and button.
- When the user stops typing, the search results should update automatically.
- You don't have to implement pagination. Just show the first page of the search results.
- Bonus: Implement a clear-button inside the textfield.

## Detail Screen

- Tapping on a search result should show the details in another screen.
- It should show: title, description, poster

## Hints

- If any requirements are unclear, decide for yourself what makes sense and document your assumptions.
- If you encounter any blockers, don't hesitate to reach out.
- If you're new to Flutter, here are a few libraries and tools that might help to get started quickly. Of course you decide yourself if you want to use them or not:
    - <https://flutter.dev/docs/development/ui/widgets> (Flutter widget catalog)
    - <https://flutter.dev/docs/development/ui/layout/constraints> (Understanding Flutter constraints)
    - <https://flutter.dev/docs/cookbook/design/themes> (Theming, Colors, font styles)
    - <https://app.quicktype.io/> (generate code for json en/decoding)
    - <https://pub.dev/packages/freezed> (data classes and ADTs for dart)
    - <https://pub.dev/packages/json_serializable> (JSON en/decoding for e.g. freezed)
    - <https://github.com/marcglasberg/fast_immutable_collections> (immutable collections)
    - <https://pub.dev/packages/flutter_hooks> (react-like hooks for state management)
    - <https://github.com/rrousselGit/functional_widget> (write widgets as pure functions instead of classes)
    - <https://pub.dev/packages/rxdart> (Observables for dart)
    - <https://pub.dev/packages/dartz> (Options and functional programming)
    - <https://pub.dev/packages/http> (HTTP client)

# Happy Hacking!

