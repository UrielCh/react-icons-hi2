# Heroicons 2 icons for preact

[![JSR](https://jsr.io/badges/@preact-icons/hi2)](https://jsr.io/@preact-icons/hi2)

**License** [MIT](https://opensource.org/licenses/MIT)

**Project** [https://github.com/tailwindlabs/heroicons](https://github.com/tailwindlabs/heroicons)

[See available icons here](https://react-icons.deno.dev/hi2)

## import_map.json

For a transparent usage:

```json
{
  "imports": {
    "@preact-icons/common": "jsr:@preact-icons/common@^1.0.10",
    "preact": "npm:preact@10.22.1",
    "preact/jsx-runtime": "npm:preact@10.22.1/jsx-runtime",
    "preact/hooks": "npm:preact@10.22.1/hooks",
    "react-icons/hi2": "jsr:@preact-icons/hi2@^1.0.11/mod.ts",
    "react-icons/hi2/": "jsr:@preact-icons/hi2@^1.0.11/ico/",
  }
}
```

## Import an icon without import_map by and afer loading all icons from the lib hi2

```ts
import { HiAcademicCap } from "jsr:preact-icons/hi2@1.0.11/mod.ts"
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

