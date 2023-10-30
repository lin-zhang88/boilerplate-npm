##### version
Versions of the npm packages in the dependencies section of your package.json file follow what’s called Semantic Versioning
ex:
"package": "MAJOR.MINOR.PATCH"
"dependencies": {
	"@freecodecamp/example": "1.2.13", //@freecod..-package ; 1.2.13-major.minor.patch
}


-This means that PATCHes are bug fixes and MINORs add new features but neither of them break what worked before. Finally, MAJORs add changes that won’t work with earlier versions.