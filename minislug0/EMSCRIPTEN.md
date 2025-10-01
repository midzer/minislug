# Emscripten

## Build

```
emmake make
```

## Link

```
em++ -O3 -flto -fno-rtti -fno-exceptions *.o libymlib.a -o index.html -sUSE_SDL=2 -sASYNCIFY -sASYNCIFY_IGNORE_INDIRECT -sASYNCIFY_ONLY=@funcs.txt -sENVIRONMENT=web --preload-file gfx/ --preload-file lev1/ --preload-file lev2/ --preload-file lev3/ --preload-file lev4/ --preload-file lev5/ --preload-file lev6/ --preload-file lev7/ --preload-file lev8/ --preload-file lev9/ --preload-file lev10/ --preload-file lev11/ --preload-file lev12/ --preload-file lev13/ --preload-file lev14/ --preload-file lev15/ --preload-file lev16/ --preload-file lev17/ --preload-file sfx/ --closure 1 -sINITIAL_HEAP=32mb
```
