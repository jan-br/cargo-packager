# @rooms-solutions/packager-resource-resolver

Resource resolver for apps that was packaged by [`@rooms-solutions/packager`](https://www.npmjs.com/package/@rooms-solutions/packager).

It resolves the root path which contains resources, which was set using the `resources` field of [cargo packager configuration](https://docs.rs/cargo-packager/latest/cargo_packager/config/struct.Config.html).

## Get the resource path

```ts
import {
  resourcesDir,
  PackageFormat,
} from "@rooms-solutions/packager-resource-resolver";

const dir = resourcesDir(PackageFormat.Nsis);
```

## Licenses

MIT or MIT/Apache 2.0 where applicable.
