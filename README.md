__`VirtualDom` transmutationist for the Gren [icidasset/html-gren](https://github.com/icidasset/html-gren) package.__

```gren
import Transmutable.Html exposing (div)
import Transmutable.Html.VirtualDom exposing (toVirtualDom)

someHtml =
  div [] []

main =
  toVirtualDom someHtml
```
