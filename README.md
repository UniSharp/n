# Using javascript in *nix pipeline.

## Usage

```
echo 'hello world' | n '.split(" ").join(",")'

cat z.diff  | n '.match(/^\+/) && console.log(line)';
```

