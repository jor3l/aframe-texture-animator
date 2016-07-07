# aframe-texture-animator
Texture Animation component for A-Frame

## Example Usage
````
<a-plane width="20" height="20" position="0 1 -15" 
                  texture-animator="htiles:4; vtiles:2; tiles:8; src:assets/sprite.png; dur:5"></a-plane>
````

## Params
- src: Sprite image to load into the mesh
- htiles: number of horizontal tiles in the sprite
- vtiles: number of vertical tiles in the sprite
- tiles: total amount of tiles
- dur: tile duration, lower values gives a faster animation
