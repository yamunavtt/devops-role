Groovy: **def and variables**

Concept:
def declares a variable without specifying the type explicitly.

Example:
def name = "Jenkins"

Runtime type:
println name.class
→ java.lang.String

Explicit equivalent:
String name = "Jenkins"

Jenkins example:
def buildResult = currentBuild.result
currentBuild
→ Jenkins global object representing the current Pipeline build

currentBuild.result
→ Overall build result
→ SUCCESS / FAILURE / UNSTABLE / ABORTED / null

Example:
def result = currentBuild.result ?: 'SUCCESS'

Important:
def does not mean "no type".

Exercise:
Create variables for:
- jobName
- timeout
- dockerEnabled
- agents
- configuration map
