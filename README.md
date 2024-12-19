# Na Library V2 
## Library loadstring
```lua
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/AstroXTeam/Project-/refs/heads/main/V3.lua%20(1).txt"))()
```




## Window
Create a Window
```lua
local Window = Library:MakeWindow({
    Title = "AstroXHub ",
    SaveFolder = "Neption "
});Window:AddMinimizeButton({
    Button = {Image = "rbxassetid://101860525194150"},
    Corner = {CornerRadius = UDim.new(0, 10)}
})
```

## Tab
Create a Tab
```lua
local Tab = Window:MakeTab({"Tab", "rbxassetid://"})
```

## Section
Create a Section
```lua
local Section = Tab:AddSection({""})
```

## Button
Create a Button
```lua
local Button = Tab:AddButton({
  Name = "",
  Callback = function()
    Print("Press") 
  end
})

```

## Toggle
Create a Toggle
```lua
local Toggle = Tab:AddToggle({
  Name = "sus",
  Default = false,
  Callback = function()

  end
})

```

## Dropdown
Create a Dropdown
```lua
local Dropdown = Tab:AddDropdown({
  Name = "Dropdown",
  Options = {"Section"},
  Default = "", 
  MultSelect = false,
  Callback = function()

  end
})
```

## Slider
Create a Slider
```lua
Tab:AddSlider({
  Name = "Sluder",
  Min = 80,
  Max = 10000,
  Increase = 1,
  Default = 80,
  Callback = function(Value)
    
  end
})

```

## TextBox
Create Textbox
```lua
local TextBox = Tab:AddTextBox({
  Name = "TextBox",
  Description = "", 
  Default = false,
  Callback = function()

end
})

```

## Example 
Creat Example Script
```lua
```
