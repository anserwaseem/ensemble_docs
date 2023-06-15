# ListView

The ListView Widget enables the rendering of lists with dynamic and scrollable content, facilitating efficient display and navigation of large datasets within your application.

[Test in Kitchen Sink](https://studio.ensembleui.com/app/e24402cb-75e2-404c-866c-29e6c3dd7992/screen/w0Wmu9ZMP4csk7IELSx3)

## Properties

| Property          | Type    | Description                                                                                                                                                             |
| :---------------- | :------ | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| item-template     | object  | [See properties](#item-template)                                                                                                                                        |
| children          | array   | List of widgets                                                                                                                                                         |
| onItemTap         |         | Dispatch when an ListView item is selected/tapped.The event dispatches only when you tap on the item. The index of the item can be retrieved using 'selectedItemIndex'. |
| selectedItemIndex | integer | Selecting a ListView item gives the index of selected item                                                                                                              |
| styles            | object  | [See properties](#styles)                                                                                                                                               |

### item-template

| Property | Type   | Description                                                        |
| :------- | :----- | :----------------------------------------------------------------- |
| data     | string | Bind to an array of data from an API response or a variable        |
| name     | string | Set the name to reference as you iterate through the array of data |
| template |        | The widget to render for each item                                 |

### styles

| Property         | Type    | Description                                                                                                                                          |
| :--------------- | :------ | :--------------------------------------------------------------------------------------------------------------------------------------------------- |
| expanded         | boolean | If the parent is a Row or Column, this flag will stretch this widget in the appropriate direction. (e.g stretch horizontally for parent of type Row) |
| showSeparator    | boolean | Show a separator between the items (default is true).                                                                                                |
| separatorColor   |         | Set the color for the separator between items                                                                                                        |
| separatorWidth   | integer | The thickness of the separator between items                                                                                                         |
| separatorPadding |         | Padding with CSS-style value e.g. padding: 5 20 5 Default 0 0 0                                                                                      |