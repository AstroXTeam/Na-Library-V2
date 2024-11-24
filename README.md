# redz Library V4
## Library loadstring
```lua
local ui_link = "https://raw.githubusercontent.com/AstroXTeam/Na-Library-V2/refs/heads/main/Source.lua"
local a = loadstring(game:HttpGet(ui_link))()
```




## Window
Create a Window
```lua
local a = a:Window("AstroXHub")
```

## Notification
Create a Notification
```lua
local Notify = Library:MakeNotify({
  Title = "Notification",
  Text = "This is a Notification",
  Time = 5
})

--[[
  Notify:Wait() -- Wait for the notification to end
]]
```

## Tab
Create a Tab
```lua
local Tab = a:Tab("Tab", "rbxassetid://")
```

## Section
Create a Section
```lua
Tab:Seperator("Astro Hub")
```


## Label
Create a Text Label
```lua
Tab:Label("Hi")
```

## Button
Create a Button
```lua
Tab:Button("Print Hi", function()
   print("hi")
end)
```

## Toggle
Create a Toggle
```lua
local Toggle = Tab:AddToggle({
Tab:Toggle("Print Hi", false, function()
     print("hi")
end)
```

## Dropdown
Create a Dropdown
```lua
Main:Dropdown("Select", {"hey", "hi", "hellow"}, function()
    print("hi")
end)
```

## Slider
Create a Slider
```lua
Main:Slider("hi", 0, 100, 30, function()
    
end)
```

Create a Minimize Button
```lua
Window:AddMinimizeButton({
  Button = {
    -- Button Properties
    Image = "rbxassetid://15298567397"
  },
  UICorner = {true,
    -- Corner Properties
    CornerRadius = UDim.new(0.5, 0)
  },
  UIStroke = {false, {
    -- Stroke Properties
  }}
})
```



