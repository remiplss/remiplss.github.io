# Class

# Function

## `App(): *`

This component is the root of the project, it contains all the routes to the different pages

| Name | Type | Attribute | Description |
| --- | --- | --- | --- |

## `Artist(objectPattern: {"user": *, "setUser": *, "paintId": *, "isLogged": *}): *`

Display information about the artist and child components in tabs

| Name | Type | Attribute | Description |
| --- | --- | --- | --- |
| objectPattern | {"user": *, "setUser": *, "paintId": *, "isLogged": *} | nullable: undefined, default: {"user":null,"setUser":null,"paintId":null,"isLogged":null} |

## `Biography(bg: string, artist: object): *`

Artist Biography in ArtistPage

| Name | Type | Attribute | Description |
| --- | --- | --- | --- |
| bg | string |  | random image from this artist |
| artist | object |  | artist informations from api |

## `SimilarArtist(paintId: number): *`

List of similar artists

| Name | Type | Attribute | Description |
| --- | --- | --- | --- |
| paintId | number |  | artist ID |

## `Biography(user: object, setUser: object, isLogged: boolean): *`

Page to update your Biography

| Name | Type | Attribute | Description |
| --- | --- | --- | --- |
| user | object |  | user object from api |
| setUser | object |  | user setter |
| isLogged | boolean |  | test if the user is logged |

## `MenuAtelier(user: object, setUser: object, isLogged: boolean, setIsLogged: boolean): *`

Workshop side menu

| Name | Type | Attribute | Description |
| --- | --- | --- | --- |
| user | object |  | user object from api |
| setUser | object |  | user setter |
| isLogged | boolean |  | test if the user is logged |
| setIsLogged | boolean |  | isLogged setter |

## `ChatMenu(user: object, setUser: object, isLogged: boolean, boolChat: boolean, setBoolChat: boolean): *`

Chat menu with list of conversation

| Name | Type | Attribute | Description |
| --- | --- | --- | --- |
| user | object |  | user object from api |
| setUser | object |  | user setter |
| isLogged | boolean |  | test if the user is logged |
| boolChat | boolean |  | test if the chat menu is open |
| setBoolChat | boolean |  | boolChat setter |

## `ChatModal(user: object, setUser: object, isLogged: boolean): *`

Chat modal : used for chatting with someone

| Name | Type | Attribute | Description |
| --- | --- | --- | --- |
| user | object |  | user object from api |
| setUser | object |  | user setter |
| isLogged | boolean |  | test if the user is logged |

## `Activity(user: object, setUser: object): *`

This Component contain your network feed

| Name | Type | Attribute | Description |
| --- | --- | --- | --- |
| user | object |  | user object from api |
| setUser | object |  | user setter |

## `FavArtists(user: object, setUser: object): *`

This component contain your list of favorite artists

| Name | Type | Attribute | Description |
| --- | --- | --- | --- |
| user | object |  | user object from api |
| setUser | object |  | user setter |

## `Likes(user: object, setUser: object): *`

This component contain your list of likes

| Name | Type | Attribute | Description |
| --- | --- | --- | --- |
| user | object |  | user object from api |
| setUser | object |  | user setter |

## `Matching(user: object, setUser: object): *`

This component contain your list of saved matching

| Name | Type | Attribute | Description |
| --- | --- | --- | --- |
| user | object |  | user object from api |
| setUser | object |  | user setter |

## `ModalNetwork(user: object, setUser: object, boolNetWork: boolean, setBoolNetWork: boolean): *`

This component is a modal used to manage your network (add/delete friends,...)

| Name | Type | Attribute | Description |
| --- | --- | --- | --- |
| user | object |  | user object from api |
| setUser | object |  | user setter |
| boolNetWork | boolean |  | test if the network modal is open |
| setBoolNetWork | boolean |  | boolNetWork setter |

## `TabAmateurs(user: object, setUser: object, isActive: number, setIsActive: number): *`

This component order the previous components in tabs

| Name | Type | Attribute | Description |
| --- | --- | --- | --- |
| user | object |  | user object from api |
| setUser | object |  | user setter |
| isActive | number |  | tab selection |
| setIsActive | number |  | isActive setter |

## `RandomInfo(): *`

This component display random quick facts about famous color, painting, artist, style,...

| Name | Type | Attribute | Description |
| --- | --- | --- | --- |

## `SearchBar(user: object): *`

This component display 30 random paintings and allow you to make specific research with different filters

| Name | Type | Attribute | Description |
| --- | --- | --- | --- |
| user | object |  | user object from api |

## `ColorChooser(user: object, setUser: object, isLogged: boolean, color: string, setColor: string): *`

This component display a color Picker

| Name | Type | Attribute | Description |
| --- | --- | --- | --- |
| user | object |  | user object from api |
| setUser | object |  | user setter |
| isLogged | boolean |  | test if the user is logged |
| color | string |  | contain the hex code of the chosed color |
| setColor | string |  | color setter |

## `Painting(user: object, setUser: object, isLogged: boolean, paintId: number): *`

This component display informations about a specific painting

| Name | Type | Attribute | Description |
| --- | --- | --- | --- |
| user | object |  | user object from api |
| setUser | object |  | user setter |
| isLogged | boolean |  | test if the user is logged |
| paintId | number |  | selected paint Id |

## `EmojiPicker(txtArea: string, setTxtArea: string): *`

This component is an emoji Picker used to send emoji in chat

| Name | Type | Attribute | Description |
| --- | --- | --- | --- |
| txtArea | string |  | string containing your message |
| setTxtArea | string |  | txtArea setter |

## `Fav(user: object, isLogged: boolean, favPaint: object): *`

This component is used to like a painting

| Name | Type | Attribute | Description |
| --- | --- | --- | --- |
| user | object |  | user object from api |
| isLogged | boolean |  | test if the user is logged |
| favPaint | object |  | paint object to like |

## `FavAdd(user: *, paintId: *)`

| Name | Type | Attribute | Description |
| --- | --- | --- | --- |
| user | * |  |
| paintId | * |  |

## `FavRemove(user: *, paintId: *)`

| Name | Type | Attribute | Description |
| --- | --- | --- | --- |
| user | * |  |
| paintId | * |  |

## `TestFav(user: *, paintId: *, index: *, paintings: *)`

| Name | Type | Attribute | Description |
| --- | --- | --- | --- |
| user | * |  |
| paintId | * |  |
| index | * |  |
| paintings | * |  |

## `getFav(user: *, paintings: *)`

| Name | Type | Attribute | Description |
| --- | --- | --- | --- |
| user | * |  |
| paintings | * |  |

## `getFavM(user: *, paintings: *)`

| Name | Type | Attribute | Description |
| --- | --- | --- | --- |
| user | * |  |
| paintings | * |  |

## `GifPicker(objectPattern: {"props": *}): *`

This component is a Gif Picker used to send gif in chat

| Name | Type | Attribute | Description |
| --- | --- | --- | --- |
| objectPattern | {"props": *} | nullable: undefined, default: {"props":null} |

## `ListModal(user: object, isLogged: boolean, listPaint: object): *`

This component is used to add painting to a list in a grid

| Name | Type | Attribute | Description |
| --- | --- | --- | --- |
| user | object |  | user object from api |
| isLogged | boolean |  | test if the user is logged |
| listPaint | object |  | paint object to add in list |

## `ListModal2(user: object, isLogged: boolean, listPaint: object): *`

This component is used to add your paint to a list

| Name | Type | Attribute | Description |
| --- | --- | --- | --- |
| user | object |  | user object from api |
| isLogged | boolean |  | test if the user is logged |
| listPaint | object |  | paint object to add in list |

## `ModalArtist(undefined: *): *`

| Name | Type | Attribute | Description |
| --- | --- | --- | --- |
| undefined | * |  |

## `SaveMatch(user: object, isLogged: boolean, matchPaint: object): *`

This component is used to save a matching

| Name | Type | Attribute | Description |
| --- | --- | --- | --- |
| user | object |  | user object from api |
| isLogged | boolean |  | test if the user is logged |
| matchPaint | object |  | paint object to add in match |

## `SqueletteFoot(user: object): *`

website footer

| Name | Type | Attribute | Description |
| --- | --- | --- | --- |
| user | object |  | user object from api |

## `SqueletteHead(user: object, setUser: object, isLogged: boolean): *`

website header

| Name | Type | Attribute | Description |
| --- | --- | --- | --- |
| user | object |  | user object from api |
| setUser | object |  | user setter |
| isLogged | boolean |  | test if the user is logged |

## `Api(): *`

| Name | Type | Attribute | Description |
| --- | --- | --- | --- |

## `GoToTop(): *`

This function is used to scroll to the top of the page when we render a new page

| Name | Type | Attribute | Description |
| --- | --- | --- | --- |

## `ArtistDetailpage(user: object, setUser: object, isLogged: boolean, paintId: number): *`

This component display artist Page

| Name | Type | Attribute | Description |
| --- | --- | --- | --- |
| user | object |  | user object from api |
| setUser | object |  | user setter |
| isLogged | boolean |  | test if the user is logged |
| paintId | number |  | selected artist Id |

## `Atelier(user: object, setUser: object, isLogged: boolean, setIsLogged: boolean): *`

This component display workshop Page

| Name | Type | Attribute | Description |
| --- | --- | --- | --- |
| user | object |  | user object from api |
| setUser | object |  | user setter |
| isLogged | boolean |  | test if the user is logged |
| setIsLogged | boolean |  | isLogged setter |

## `CompteAmateurPage(user: object, setUser: object, isLogged: boolean, setIsLogged: boolean, isActive: number, setIsActive: number): *`

This component display the User Page

| Name | Type | Attribute | Description |
| --- | --- | --- | --- |
| user | object |  | user object from api |
| setUser | object |  | user setter |
| isLogged | boolean |  | test if the user is logged |
| setIsLogged | boolean |  | isLogged setter |
| isActive | number |  | tab selection |
| setIsActive | number |  | isActive setter |

## `ListeAmateurPage(user: object, paintId: number, isLogged: boolean): *`

This component display the List Page

| Name | Type | Attribute | Description |
| --- | --- | --- | --- |
| user | object |  | user object from api |
| paintId | number |  | list Id |
| isLogged | boolean |  | test if the user is logged |

## `MatchingColor(user: object, setUser: object, isLogged: boolean): *`

This component display the Matching Color Page

| Name | Type | Attribute | Description |
| --- | --- | --- | --- |
| user | object |  | user object from api |
| setUser | object |  | user setter |
| isLogged | boolean |  | test if the user is logged |

## `MatchingPage(user: object, setUser: object, isLogged: boolean, paintId: number): *`

This component display a Matching Page with a painting from our db

| Name | Type | Attribute | Description |
| --- | --- | --- | --- |
| user | object |  | user object from api |
| setUser | object |  | user setter |
| isLogged | boolean |  | test if the user is logged |
| paintId | number |  | paint id |

## `OpusPage(user: object, setUser: object, isLogged: boolean, paintId: number, setPaintId: number): *`

This component display a Painting full page

| Name | Type | Attribute | Description |
| --- | --- | --- | --- |
| user | object |  | user object from api |
| setUser | object |  | user setter |
| isLogged | boolean |  | test if the user is logged |
| paintId | number |  | paint id |
| setPaintId | number |  | paintId setter |

## `SignInPage(objectPattern: {"user": *, "setUser": *, "isLogged": *, "setIsLogged": *}): *`

| Name | Type | Attribute | Description |
| --- | --- | --- | --- |
| objectPattern | {"user": *, "setUser": *, "isLogged": *, "setIsLogged": *} | nullable: undefined, default: {"user":null,"setUser":null,"isLogged":null,"setIsLogged":null} |

## `UserInfo(isLogged: boolean, user: object, setUser: object): *`

This component display the User update Page

| Name | Type | Attribute | Description |
| --- | --- | --- | --- |
| isLogged | boolean |  | test if the user is logged |
| user | object |  | user object from api |
| setUser | object |  | user setter |