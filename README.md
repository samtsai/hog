# Hog

This tool leverages `top` and `ps` to get a rough idea of what applications are using excessive memory.

<img width="307" alt="Screen Shot 2022-06-08 at 13 14 27" src="https://user-images.githubusercontent.com/459656/172677246-21ce33aa-b440-4a04-a90d-fccb5cadaa61.png">

# Try It Out

```
brew install deno
deno run --allow-run=top,ps --check https://deno.land/x/hog@0.0.4/hog.ts
```

# Installing

```
deno install --allow-run=top,ps https://deno.land/x/hog@0.0.4/hog.ts
```

or to update

```
deno install -f --allow-run=top,ps https://deno.land/x/hog@0.0.4/hog.ts
```

# Running

```
hog
```

to show PIDs for top level processes that were collapsed by name:

```
hog -p
```
