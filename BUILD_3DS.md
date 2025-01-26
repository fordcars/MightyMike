# How to build MightyMike for 3DS

1. Clone repo
```bash
git clone --recurse-submodules https://github.com/fordcars/MightyMike
```
2. Build and install SDL2 for 3DS using [these instructions](https://wiki.libsdl.org/SDL2/README/n3ds).

3. Build PicaGL:
```bash
cd extern/Pomme/extern/picaGL
make
```

4. Build Pomme:
```bash
cd extern/Pomme
make
```

5. Build MightyMike:
```bash
make
```