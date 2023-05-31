# Heroicons 2 icons for deno / Preact

**License** [MIT](https://opensource.org/licenses/MIT)

**Project** [https://github.com/tailwindlabs/heroicons](https://github.com/tailwindlabs/heroicons)

[See available icons here](https://react-icons.github.io/react-icons/icons?name=hi2)

## import_map.json

For a transparent usage:

```json
{
  "imports": {
    "preact":  "https://esm.sh/preact@10.15.1",
    "preact/": "https://esm.sh/preact@10.15.1/",
    "react-icons/hi2":  "https://cdn.jsdelivr.net/gh/urielch/react-icons-hi2@1.0.1/mod.ts",
    "react-icons/hi2/": "https://cdn.jsdelivr.net/gh/urielch/react-icons-hi2/ico/",
  }
}
```

## Direct import sample

```ts
import { HiAcademicCap } from "https://deno.land/x/react_icons_hi2@1.0.1/mod.ts"
```

## import_map import sample

```ts
import { HiAcademicCap } from "react-icons/hi2"
```

## minimal import

```ts
import { HiAcademicCap } from "react-icons/hi2/HiAcademicCap.ts"
```

## minimal import using default export

```ts
import HiAcademicCap from "react-icons/hi2/HiAcademicCap.ts"
```

