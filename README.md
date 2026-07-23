# example-package

  An example Grayscale package demonstrating the correct structure for
  community packages. Use this as a template when creating your own.

  ## What This Shows

  - Required file header with all fields
  - `#doc` attribute on every function
  - Flat structure (no subdirectories)
  - No `main()` function
  - Semver git tag (e.g: `v0.1.0`)

  ## See Also

  - The central packages registry: [Grayscale Packages](https://github.com/grayscale-lang/packages)

  After that's committed, tag the repo:
  
  ```bash
  git tag v0.1.0
  git push origin v0.1.0
  ```
