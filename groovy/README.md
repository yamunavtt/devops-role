**Groovy: ** **def and variables**

**Concept:**
def declares a variable without specifying the type explicitly.

**Example:**
def name = "Jenkins"

**Runtime type:**
println name.class
→ java.lang.String

**Explicit equivalent:**
String name = "Jenkins"

**Jenkins example:**
def buildResult = currentBuild.result

**Important:**
def does not mean "no type".

Exercise:
Create variables for:
- jobName
- timeout
- dockerEnabled
- agents
- configuration map
