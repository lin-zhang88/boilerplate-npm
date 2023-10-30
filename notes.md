##### version
Versions of the npm packages in the dependencies section of your package.json file follow what’s called Semantic Versioning
ex:
"package": "MAJOR.MINOR.PATCH"
"dependencies": {
	"@freecodecamp/example": "1.2.13", //@freecod..-package ; 1.2.13-major.minor.patch
}
This means that PATCHes are bug fixes and MINORs add new features but neither of them break what worked before. Finally, MAJORs add changes that won’t work with earlier versions.
-----
To allow an npm dependency to update to the latest PATCH version, you can prefix the dependency’s version with the tilde (~) character. Here's an example of how to allow updates to any 1.3.x version.
ex:
"package": "~1.3.8"
----
Use the Caret-Character to Use the Latest Minor Version of a Dependency
ex:
"package": "^1.3.8"
If you were to use the caret (^) as a version prefix instead, npm would be allowed to update to any 1.x.x version.