# xml-linter
Lint any kind of XML file, can accept an XSD definition file.

![xml-linter](https://cloud.githubusercontent.com/assets/1247388/18693510/77f596c4-7fa2-11e6-92d4-ed903a6e2412.PNG)


## Usage

![xml-linter-use](https://cloud.githubusercontent.com/assets/1247388/18693553/da1b82d2-7fa2-11e6-8633-88e8559c27ae.PNG)

Some tests are available (requires `dev` dependencies):

```bash
# Invalid file
$ ./xml-linter ./vendor/symfony/translation/Tests/fixtures/invalid-xml-resources.xlf

# Valid file
$ ./xml-linter ./vendor/symfony/translation/Tests/fixtures/resources.xlf
```

Installing it as a dependency of your project will automatically move the binary ``vendors/bin`` folder.

## Contribute ?

No thanks, I keep it as simple and stupid as possible.
