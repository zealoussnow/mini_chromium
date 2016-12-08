# Build mini Chromium

## 1.Get the gyp build tool

```sh
git clone https://github.com/zealoussnow/gyp.git
```

## 2.Enter the directory of mini_chromium, generate Makefile

```sh
cd mini_chromium
../gyp/gyp --depth=. mini_chromium.gyp
```

## 3.Make the target
