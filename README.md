# MG4
## Devlog
The `FloatAnimation` script changes the direction of movement every `_switchSpeed` seconds and moves the GameObject in that direction according to `_moveSpeed`. It initializes the timer in the `Start()` method and then keeps track of and resets the timer using the `_timer` variable in the `Update()` method. The direction is either up or down, so it is controlled and switched by the `_up` variable. The `Update()` method also handles the movement of the GameObject based on `_up`.

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [City 3D models](https://assetstore.unity.com/packages/3d/environments/simplepoly-city-low-poly-assets-58899)
- [Bite sound effect](https://freesound.org/people/Jofae/sounds/353067/)