``` adblock
! adblock
bad filter
!#if !env_mobile
www.google.*###main a[href][data-sb^="/url?"]:remove-attr(data-sb)
@@||google-analytics.com/analytics*js$script,domain=~wordpress.org,redirect=google-analytics_analytics.js:5
||myanalytic.net^$3p
!#endif
```
``` scss
// scss
$primary-color: #3498db;
$font-stack: 'Arial', sans-serif;
@mixin border-radius($radius) {}
body mytag .class#id {
  font-family: $font-stack;
  margin: 0 auto;
  color: #333;
	padding: $spacing-unit * 2;
}
p
br
div
4  body
5  embed, table, tfoot, title
6  button, strong
7  details
8  datalist
10 blockquote
10 figcaption
     EMBED, ,BODY,
     BUtton)stronG
     DetAils|eMbeD
     '"FigCapTiON
        ^BUTtON
         ,,HTML.
      ,$BXX7777PPBB,,
     $J77L77777jjjjIB,

```

``` coffee
# coffeescript
sayHello = -> console.log "Hello from CoffeeScript!"
temperature = 25
numbers = [1, 2, 3, 4, 5]
```
``` cpp
//cpp
template <typename T>
bool getBit(int num, int i) {
	return ((num & (1<<i)) != 0);
}
```
``` css
/* css */
:root {
      --primary-color: #007bff;
      --spacing-unit: 16px;
    }
mytag div#id.class[attr="val"]:not(){width:0;display:block;}
```
``` diff
# diff
- text in red
+ text in green
! text in orange +e
@@ text in purple (and bold)@@
```
``` go
// go
package main
import "fmt"
func main() {
  age := 25
  fmt.Println("Hello, Go!")
}
```
``` html
<!--- HTML --->
<tagggg prop="owo">owo</tagggg>
<script> var a = 123; </script> 
```
``` ini
; ini
[project]
name = orchard rental service (with app)
target-region = "Bay Area"
legal-team = (vacant)
num = 123
```
``` js
//javascript
var a = console.log("owo"+123);
function myfun(x){x=x+1;}
myfun(2);
==== &&&& %%%% $$$$ @@@@ ####
```
```lua
--lua
thing:thingy("123")
if 1+1==2 then
  print("words")
end
==== //// &&&& %%%% $$$$ @@@@ ####
```
### markdown
``` md
> markdown
# a heading
<sup>superscript</sup> ** BOLD ** __B__ *italic* _i_
words [link]([https://github.com/](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax))
[](url). link to [a heading](#a-heading)
- George Washington
* John Adams
+ Thomas Jefferson
+ + + +
- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:
@github/support What do you think about these updates?
inline > quote?
<script id="id"> var a = "one" + 1; </script>
<style>:root { --primary-color: #007bff; --spacing-unit: 16px; }
mytag div#id.class[attr="val"]:not(){width:0;display:block;}
{--varname123} @import url layer(layer-name);</style>
```
```py
# python
i=1
def fun(x)
  print("hello")
  print(f"Iteration {i}")
import turtle
turtle.fd(1)
```
```ruby
# ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```
``` regex
regex
([A-z]{3} [\d]{2} [\d]{1,2}:[\d]{1,2}:[\d]{1,2}) ([\d]{1,3}\.[\d]{1,3}\.[\d]{1,3}\.[\d]{1,3}) (\[S\=[\d]{9}\]) (\[[A-z]ID=.{1,18}\])\s{1,3}?(\(N\s[\d]{5,20}\))?(\s+(.*))\s{1,3}?(\[Time:.*\])?
```
``` ts
// typesctipt
let message: string = "Hello, TypeScript!";
let count: number = 10;
```
``` xml
<!-- xml -->
<name>Jane Doe</name>
<email>jane.doe@example.com</email>
<phone type="mobile">123-456-7890</phone>
```
