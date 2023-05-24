# Monstertar

Create a large amount of random files that cannot get compressed when putting them into a tarball.

## Usage

```
monstertar --target-size=400mb --file-size=1kb <output-dir>
```

## Options
```
-t | --target-size  Target size of all generated files in mb
-f | --file-size    Size of each file in kb
```