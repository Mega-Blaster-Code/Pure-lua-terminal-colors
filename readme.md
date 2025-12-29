```lua
local color8 = require("color8")

for r=0, 255, 32 do
  for g=0, 255, 32 do
    for b=0, 255, 32 do
      color8.fcolor(r, g, b)
      io.stdout:write("█")
    end
  end
end  
```
### Result
<img width="1026" height="65" alt="image" src="https://github.com/user-attachments/assets/0333b3d2-44f0-4cdc-92ca-bfe6fabf3a74" />
