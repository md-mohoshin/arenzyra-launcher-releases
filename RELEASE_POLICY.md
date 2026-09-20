# Release policy

- Publish only independently verified, versioned artifacts from reviewed private builds.
- Keep application source, build credentials, environment files, private evidence,
  internal deployment records, and customer data out of this repository and its assets.
- Bind every artifact to its manifest by exact name, SHA-256, and byte size.
- Attach the complete asset set to a draft before publishing an immutable release.
- Never replace bytes under an existing version or move its published tag. Publish a
  new version when bytes change.
- Keep signing status explicit. An unsigned package must remain labelled unsigned.
- Keep prior supported release URLs working during a documented transition.
- Keep source builds and publication credentials in the private build environment.
- Review package contents, including dependencies, before each release. ASAR is an
  archive format; distributed desktop JavaScript remains inspectable.

