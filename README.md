skulpt-docs
===========
These files contain basic information about the python modules supported in [skulpt](https://github.com/skulpt/skulpt). Hopefully they can be used by others that incorporate skulpt into their projects. We use them for user documentation at [trinket.io](https://trinket.io). An example of our rendered documentation can be found at [https://trinket.io/docs/python](https://trinket.io/docs/python).

## Preparing to Contribute

* Create a GitHub account
* Fork this repo

## Making Changes

* Edit the JSON files
  * TODO: create trinket.io site for uploading and testing json
* If you add examples, please test them at trinket.io.
  * TODO: create trinket.io site for uploading and testing examples
* TODO: consider using a different format to make it easier to edit

## Submitting Changes

* Open a pull request

## 3rd party modules and docs

The plan is to have trinket docs added to individual 3rd party module repositories. For now, they are here.

## Supported Sections

* objectMethods (array of JSON objects)

  A list of methods available. Each method should have a name and either a docs or html section. A docs section will be displayed within a pre tag to preserve whitespace. An html section will be assumed to be completely formatted and displayed as is.

  * name (string)
  * docs (string)
  * html (string)
  * inline_example (string)

* prefixMethods (boolean)

  If true, method names will be prefixed with the module name.

* inline_example (string)

  A working example that shows the method in action.

* overview (string)

  A high-level overview of the module.

## Attribution and Thanks

Much of this documentation is derived directly from Python itself, making extensive use of [Pydoc](https://docs.python.org/2/library/pydoc.html). Without the contributions from the python community this information would not be possible.

