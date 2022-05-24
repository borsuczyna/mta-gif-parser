# MTA GIF Parser
GIF parser that allows you to draw GIF images with dxDrawImage

# Syntax
```lua
gif_object = dxCreateGIF(path_to_file)
dxDrawImage(x, y, w, h, image, delay, ...)
```

# Example
```lua
local gif = dxCreateGIF("test.gif")

addEventHandler("onClientRender", root, function()
    dxDrawImage(0, 0, 100, 100, gif, 150)
end)
```

# Special thanks
Special thanks for Egor-Skriptunoff for gif parser
