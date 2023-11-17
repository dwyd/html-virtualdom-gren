__`VirtualDom` transmutationist for the Gren [icidasset/html-gren](https://github.com/icidasset/html-gren) package.__

```gren
import Browser
import Transmutable.Html exposing (div)
import Transmutable.Html.VirtualDom exposing (toVirtualDom)

someHtml =
  div [] []

main =
  Browser.sandbox
    { init = {}
    , view = view
    , update = \_ _ -> {}
    }

view model =
  toVirtualDom someHtml
```
