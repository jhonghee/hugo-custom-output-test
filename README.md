# hugo-custom-output-test

http://localhost:1313/configuration/7_1/azuredev/app1/eclssetup/index.properties

or with "uglyurls = true"

http://localhost:1313/configuration/7_1/azuredev/app1/eclssetup.properties

should output

```
key1=value1
key2=value2
key3=value3
key4=value4
key5=value5
```
as text/properties

W/o "uglyurls = true", you can set "baseName" to replace "index.properties" with "eclssetup.properties"

```
[outputFormats.eclssetup]
mediaType = "text/properties"
baseName = "eclssetup"
isPlainText = true
```