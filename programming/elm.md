# Elm

A functional language that compiles to Javascript used to build websites and web apps. It has **no** runtime errors.

It's simple to get started and you can build a complete full-stack application in one file and just a few lines. Here's a counter, for example:

```text
import Browser
import Html exposing (Html, button, div, text)
import Html.Events exposing (onClick)

main =
  Browser.sandbox { init = 0, update = update, view = view }

type Msg = Increment | Decrement

update msg model =
  case msg of
    Increment ->
      model + 1

    Decrement ->
      model - 1

view model =
  div []
    [ button [ onClick Decrement ] [ text "-" ]
    , div [] [ text (String.fromInt model) ]
    , button [ onClick Increment ] [ text "+" ]
    ]
```

## Resources

* [Official Elm Guide](https://guide.elm-lang.org)
* [Todo App Demo](https://evancz.github.io/elm-todomvc/#/)

