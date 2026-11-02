# Источники и лицензии

Все ресурсы бесплатные, с открытыми лицензиями. Файлы лежат в `public/assets/`.

## Небо (HDRI)

| Файл | Название | Автор | Источник | Лицензия |
|---|---|---|---|---|
| `hdri/rogland_clear_night_2k.hdr` | Rogland Clear Night | Greg Zaal | [Poly Haven](https://polyhaven.com/a/rogland_clear_night) | [CC0](https://creativecommons.org/publicdomain/zero/1.0/) |

Панорама снята ночью в Рогаланне (Норвегия): звёздное небо над фьордами.

## 3D-модели

| Папка/файл | Название | Автор | Источник | Лицензия |
|---|---|---|---|---|
| `models/Barbarian.glb` | KayKit Character Pack: Adventurers 1.0, персонаж Barbarian (с анимациями Idle, Cheer и др.) | Kay Lousberg ([kaylousberg.com](https://www.kaylousberg.com)) | [GitHub KayKit](https://github.com/KayKit-Game-Assets/KayKit-Character-Pack-Adventures-1.0), [itch.io](https://kaylousberg.itch.io/kaykit-adventurers) | [CC0](https://creativecommons.org/publicdomain/zero/1.0/), текст лицензии в `models/KAYKIT_LICENSE.txt` |
| `models/stone_fire_pit/` | Stone Fire Pit | Sebastian Platen | [Poly Haven](https://polyhaven.com/a/stone_fire_pit) | CC0 |
| `models/tree_stump_01/` | Tree Stump 01 | Rob Tuytel | [Poly Haven](https://polyhaven.com/a/tree_stump_01) | CC0 |
| `models/rock_moss_set_01/` | Rock Moss Set 01 | Kless Gyzen | [Poly Haven](https://polyhaven.com/a/rock_moss_set_01) | CC0 |

У персонажа KayKit в коде спрятан рогатый шлем, кружка и двуручный топор. Шлем без рогов, борода и меховой воротник сделаны в коде (`src/scene/vikings.js`).

## Текстуры

| Файл | Название | Автор | Источник | Лицензия |
|---|---|---|---|---|
| `textures/forrest_ground_01_*.jpg` | Forest Ground 01 | Rob Tuytel | [Poly Haven](https://polyhaven.com/a/forrest_ground_01) | CC0 |
| `textures/old_planks_02_diff_1k.jpg` | Old Planks 02 | Rob Tuytel | [Poly Haven](https://polyhaven.com/a/old_planks_02) | CC0 |
| `textures/thatch_roof_angled_diff_1k.jpg` | Thatch Roof Angled | Rob Tuytel, Dimitrios Savva | [Poly Haven](https://polyhaven.com/a/thatch_roof_angled) | CC0 |
| `textures/waternormals.jpg` | Карта нормалей воды из примеров three.js | авторы three.js | [three.js на GitHub](https://github.com/mrdoob/three.js/blob/r170/examples/textures/waternormals.jpg) | [MIT](https://github.com/mrdoob/three.js/blob/dev/LICENSE) |

## Сделано в коде

Горы, вода, длинный дом, драккар, ели, северное сияние, туман, огонь и искры построены процедурно в `src/scene/`.

## Шрифты и библиотеки

- [Cinzel](https://fonts.google.com/specimen/Cinzel), [Cormorant SC](https://fonts.google.com/specimen/Cormorant+SC), [Noto Sans Runic](https://fonts.google.com/noto/specimen/Noto+Sans+Runic), [PT Sans](https://fonts.google.com/specimen/PT+Sans): Google Fonts, лицензия SIL Open Font License 1.1.
- [three.js](https://threejs.org) (MIT), [Vite](https://vitejs.dev) (MIT).

## Свои модели

Если вы положите в `public/assets/models/custom/` модели со Sketchfab или анимации из Mixamo, допишите сюда название, автора, ссылку и лицензию каждой. Для CC-BY это обязательно.
