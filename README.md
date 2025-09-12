# My custom Godot fork

## TileMapLayer

This fork adds a height attribute to each cell in a TileMapLayer, which offsets the cell vertically by `-height` pixels.
Set a cells height with `set_cell_height(...)`, retrieve its height with `get_cell_height(...)`. Note: When a cell is erased, its height is reset to 0 as a side-effect.

## Image

I've also removed the warning in the first few lines of `Image.load_from_file()` because they're annoying me.
