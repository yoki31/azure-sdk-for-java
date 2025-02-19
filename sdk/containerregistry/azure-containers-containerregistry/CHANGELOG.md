# Release History

## 1.0.0-beta.6 (2022-1-10)

### Breaking Changes
 - Renamed `ArtifactTagOrderBy` to `ArtifactTagOrder`.
 - Renamed `ArtifactManifestOrderBy` to `ArtifactManifestOrder`.

### Other Changes

#### Dependency Updates
- Upgraded `azure-core` to `1.23.1`
- Upgraded `azure-core-http-netty` to `1.11.2`

## 1.0.0-beta.5 (2021-11-09)
### New features
- Enabled support for the stable `2021-07-01` swagger api-version.
- Removed `getTeleportEnabled` and `setTeleportEnabled` field from `RepositoryProperties`.


## 1.0.0-beta.4 (2021-08-20)
### Breaking Changes

- Replaced `authenticationScope` property on `ContainerRegistryClientBuilder` with `audience`.
  `audience` is of type `ContainerRegistryAudience`, which allows customers to select from available audiences or provide their own audience string.
  It is a mandatory property on the builder and needs to be set to instantiate the Container Registry clients.

### Other Changes

- Updated documentation comments.

## 1.0.0-beta.3 (2021-06-08)
### New features
- Flattened the content properties to the Tag, Manifest and Repository properties.
- Enabled support for non-public clouds.
- Added expiration time for the jwt tokens.
- Added more samples and documentation.


## 1.0.0-beta.2 (2021-05-11)
### New Features
- Added helper types for ManifestArtifact and ContainerRepository.
- Restricted builder count to 1.
- Enabled support for anonymous access.
- Improved samples and readme.

## 1.0.0-beta.1 (2021-04-14)
- Initial release. Please see the README and wiki for information on the new design.
