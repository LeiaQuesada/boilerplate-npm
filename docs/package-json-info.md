# package.json info

Semantic Versioning System:
"package": "MAJOR.MINOR.PATCH"
- The MAJOR version should increment when you make incompatible API changes. 
- The MINOR version should increment when you add functionality in a backwards-compatible manner. 
- The PATCH version should increment when you make backwards-compatible bug fixes. 
- This means that PATCHes are bug fixes and MINORs add new features but neither of them break what worked before. Finally, MAJORs add changes that won’t work with earlier versions.

Use of a Tilde-Character(~) will always use the latest patch version of a dependency.
- To allow an npm dependency to update to the latest PATCH version, you can prefix the dependency’s version with the tilde (~) character. 