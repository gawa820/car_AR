# Car Discovery - vehicle switching version

## What changed

- Added `select.html` for store-side vehicle selection.
- Added `carDiscoveryEnabledCarIds_v1` localStorage setting.
- `index.html` now has a `車種選択` button.
- `app.js` loads all cars from `cars.json`, then activates only selected cars.
- AR target entities are generated automatically when future cars are added to `cars.json`.

## How to use

1. Open `select.html`.
2. Check the vehicles you want to show in this store/event.
3. Press `この車種で保存`.
4. Return to `index.html`.

If no selection is saved, all vehicles are shown.

## Important

`targets.mind` is not included in this package because it was not in the uploaded files.
Place your generated `targets.mind` in the project root next to `index.html`.

For future vehicle additions, keep `cars.json` `targetIndex` aligned with the order used when generating `targets.mind`.
