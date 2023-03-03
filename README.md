![image](https://user-images.githubusercontent.com/82112471/175300046-5835dcc8-475f-46b5-bc2b-2b1fdc6fd760.png)
### Project Sloth UI
A single resource made up of several smaller, UI-related scripts for use in your server, accessible via client-side exports. Documentation and previews of each are provided below. We will continue to add to this collection in the future.

![image](https://user-images.githubusercontent.com/82112471/175300175-6d6f926f-b3e2-42d3-b564-2e52e737d6c2.png)

## Circle Minigame

```
exports['ps-ui']:Circle(function(success)
    if success then
        print("success")
	else
		print("fail")
	end
end, 2, 20) -- NumberOfCircles, MS
```
![image](https://user-images.githubusercontent.com/70592880/174923967-49718d68-a71d-4df7-8664-a210bee0d1a5.png)

## Number Maze
```
exports['ps-ui']:Maze(function(success)
    if success then
        print("success")
	else
		print("fail")
	end
end, 20) -- Hack Time Limit
```
![image](https://user-images.githubusercontent.com/7463741/170586240-fa92a1fc-aac0-48bb-938f-f6f03a63511f.png)

## VAR
```
exports['ps-ui']:VarHack(function(success)
    if success then
        print("success")
	else
		print("fail")
	end
 end, 2, 3) -- Number of Blocks, Time (seconds)
 ```
 ![image](https://user-images.githubusercontent.com/7463741/170586620-51c8648d-1f2c-4ff5-a8d0-755c82b34d58.png)
 
 ## Thermite
 ```
exports['ps-ui']:Thermite(function(success)
    if success then
        print("success")
	else
		print("fail")
	end
end, 10, 5, 3) -- Time, Gridsize (5, 6, 7, 8, 9, 10), IncorrectBlocks
 ```
 ![image](https://user-images.githubusercontent.com/7463741/170587067-4c27bf6e-8f5b-4bff-a739-d688be3450fe.png)

## Scrambler
```
exports['ps-ui']:Scrambler(function(success)
    if success then
        print("success")
	else
		print("fail")
	end
end, "numeric", 30, 0) -- Type (alphabet, numeric, alphanumeric, greek, braille, runes), Time (Seconds), Mirrored (0: Normal, 1: Normal + Mirrored 2: Mirrored only )
```
![image](https://user-images.githubusercontent.com/7463741/170587319-2109661a-8baf-48ff-b4bb-cd18fc10ec73.png)

## Display Text
```
exports['ps-ui']:DisplayText("Example Text", "primary") -- Colors: primary, error, success, warning, info, mint
exports['ps-ui']:HideText()
```
![image](https://user-images.githubusercontent.com/7463741/170587380-0629b5fc-80d6-4c2a-85c1-4e5426167197.png)

## Status UI
```
exports['ps-ui']:StatusShow("Area Dominance", {
  "Gang: Ballas",
  "Influence: %100",
})
exports['ps-ui']:StatusUpdate("Area Dominance", {
  "Gang: Ballas",
  "Influence: %99",
})
exports['ps-ui']:StatusHide()
```
![image](https://user-images.githubusercontent.com/7463741/170587637-57217095-29ab-460e-9933-123fb0500e12.png)

## Menus
```
exports['ps-ui']:CreateMenu({
        {
            header = "header1",
            text = "text1",
            icon = "fa-solid fa-circle",
            color = "red",
            event = "event:one",
            args = {
                1,
                "two",
                "3",
            },
            server = false,
            
        },
        {
            header = "header2",
            text = "text3",
            icon = "fa-solid fa-circle",
            color = "blue",
            event = "event:two",
            args = {
                1,
                "two",
                "3",
            },
            server = false,
        },
        {
            header = "header3",
            text = "text3",
            icon = "fa-solid fa-circle",
            color = "green",
            event = "event:three",
            args = {
                1,
                "two",
                "3",
            },
            server = true,
        },
        {
            header = "header4",
            text = "text4",
            event = "event:four",
            args = {
                1,
                "two",
                "3",
            },
        },
    })
```
![image](https://user-images.githubusercontent.com/7463741/170587722-4dca53b1-c2b2-43a9-990e-37bafb202a7e.png)

## Input

```
local input = exports['ps-ui']:Input({
        title = "Test",
        inputs = {
            {
                type = "text",
                placeholder = "test2"
            },
            {
                type = "password",
                placeholder = "password"
            },
            {
                type = "number",
                placeholder = "666"
            },
        }
    })
```
![image](https://user-images.githubusercontent.com/7463741/170587795-236d2826-c510-4622-9580-dc2cd3bf1902.png)

## Show Image

```
exports['ps-ui']:ShowImage("https://user-images.githubusercontent.com/91661118/168956591-43462c40-e7c2-41af-8282-b2d9b6716771.png")
```
![image](https://user-images.githubusercontent.com/70592880/173483722-53c40c11-faf0-42d8-98b2-ec97d99c3a39.png)

## Notify

```
exports['ps-ui']:Notify(text, texttype, length)
```

![image](https://user-images.githubusercontent.com/91788613/202788087-43911c2b-0a36-4f3a-9641-a4e13b36034e.png)

CREDITS: 
- https://github.com/sharkiller/nopixel_minigame
- https://github.com/iLLeniumStudios/is-statushud
- https://github.com/tnj-development/tnj-notify

![Limeys](https://user-images.githubusercontent.com/99845881/222841933-e00d1fbf-d800-46d9-b6dd-1c33a5127828.png)
![beanmachinemenu](https://user-images.githubusercontent.com/99845881/218348724-56fd4ca0-8821-45a1-a636-899b69f63400.png)
![cyberbarmenu](https://user-images.githubusercontent.com/99845881/217463124-bb440da1-cf41-4508-bbf0-dac24787ce07.png)
![pizzathismenu](https://user-images.githubusercontent.com/99845881/217463126-a65f6a53-fcdf-483b-8694-286a4b2ad104.png)
![uwucafemenu2](https://user-images.githubusercontent.com/99845881/217463151-584c8e90-7cc1-4da7-bebd-48375903add0.png)
![uwumenucafe1](https://user-images.githubusercontent.com/99845881/217463152-e43d9fdf-2f9a-44ed-b1d1-03e229e1fbd7.png)
![vanillamenu](https://user-images.githubusercontent.com/99845881/217463155-fdf19a04-fcbd-4128-a9fa-4789acb7fbd6.png)
![upnatommenu](https://user-images.githubusercontent.com/99845881/217463101-463b4ca4-d1d0-4a0c-a483-b03a566eac91.png)
![burgershotmenu](https://user-images.githubusercontent.com/99845881/217463104-8454fc20-ee9a-420b-b9fa-4355114f9299.png)
