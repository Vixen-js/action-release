# Vixen-JS Action Release

Github action to auto release Vixen Packages.

Example usage:
```yml
- uses: vixen-js/action-release@main
  with:
    token: ${{github.token}}
    name: My Release
    code: latest
    prerelease: true
    recreate: true
    assets: >
      myfile.txt:target.txt:text/plain
      another:one:application/json
```