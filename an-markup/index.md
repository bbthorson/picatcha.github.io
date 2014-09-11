#AdsNative Markup Language

Note: tags follow strict syntax meaning: if any space or comma is off it will throw an error.


##Ad Content Information

###{{ post_title() }}

Example:

`{{ post_title(a=false, h="h2", h_class="large_title", h_style="color:#fff;") }}`

will be rendered as:

`<h2 class="large_title" style="color:#fff;">Native Ad Title</h2>`

| Name | Type  | Default | Description |
| --- | --- | --- | --- |
| class | String | `null` | Class applied to the `<a>` tag |
| style | CSS | `null` | CSS styling applied to the `<a>` tag |
| a | Boolean | `true` | Hyperlinks the element |
| h | String | `null` | Specify the h element of the title |
| h_class | String | `null` | Class applied to the h element of the title |
| h_style | CSS | `null` | Specify the h element of the title |


###{{ post_summary() }}

| Name | Type  | Default | Description |
| --- | --- | --- | --- |
| class | String | `null` | Class applied to the element tag |
| style | CSS | `null` | CSS styling applied to the element tag |
| tagName | String | `null` | Specifies the element tag, otherwise injected as raw test |



###{{ feature_image() }}

| Name | Type  | Default | Description |
| --- | --- | --- | --- |
| class | String | `null` | Class applied to the `<img>` tag |
| style | CSS | `null` | CSS styling applied to the `<img>` tag |
| a | Boolean | `false` | Hyperlinks the element |
| a_class | String | `null` | Class assigned to the hyperlink |
| a_style | CSS | `null` | CSS styling applied to the hyperlink |


##Brand Information

###{{ brand_image() }}

| Name | Type  | Default | Description |
| --- | --- | --- | --- |
| class | String | `null` | Class applied to the `<img>` tag |
| style | CSS | `null` | CSS styling applied to the `<img>` tag |
| a | Boolean | `false` | Hyperlinks the element |
| a_class | String | `null` | Class assigned to the hyperlink |
| a_style | CSS | `null` | CSS styling applied to the hyperlink |
| width | String | `null` | Specifies the width of the brand image |
| height | String | `null` | Specifies the height of the brand image |


###{{ post_author() }}

| Name | Type  | Default | Description |
| --- | --- | --- | --- |
| class | String | `null` | Class applied to the element tag |
| style | CSS | `null` | CSS styling applied to the element tag |
| tagName | String | `null` | Specifies the element tag, otherwise injected as raw test |
| a | Boolean | `false` | Hyperlinks the element |
| a_class | String | `null` | Class assigned to the hyperlink |
| a_style | CSS | `null` | CSS styling applied to the hyperlink |
| prefix | Boolean | `true` | Add prefix such as 'Promoted by' and then brand name |


##Post Click behavior

###{{ post_url() }}

| Name | Type  | Default | Description |
| --- | --- | --- | --- |
| a | Boolean | `true` | Hyperlinks the element |
