# Heroicons 2 icons for deno / Preact

**License** [MIT](https://opensource.org/licenses/MIT)

**Project** [https://github.com/tailwindlabs/heroicons](https://github.com/tailwindlabs/heroicons)

[See available icons here](https://react-icons.deno.dev/hi2)

## import_map.json

For a transparent usage:

```json
{
  "imports": {
    "preact":  "https://esm.sh/preact@10.22.1",
    "preact/": "https://esm.sh/preact@10.22.1/",
    "react-icons/hi2":  "https://cdn.jsdelivr.net/gh/urielch/react-icons-hi2@1.0.10/mod.ts",
    "react-icons/hi2/": "https://cdn.jsdelivr.net/gh/urielch/react-icons-hi2@1.0.10/ico/",
  }
}
```

## Import an icon without import_map by and afer loading all icons from the lib hi2

```ts
import { HiAcademicCap } from "https://deno.land/x/react_icons_hi2@1.0.10/mod.ts"
```

## import_map import an icon from all icons

```ts
import { HiAcademicCap } from "react-icons/hi2"
```

## import a single icon, downloading just one icon

```ts
import { HiAcademicCap } from "react-icons/hi2/HiAcademicCap.ts"
```

or using default export

```ts
import HiAcademicCap from "react-icons/hi2/HiAcademicCap.ts"
```

