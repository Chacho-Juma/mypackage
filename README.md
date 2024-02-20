# myPackage Library

This library was created as an example of how to publish your own Python Package.

## What you will need

This project runs on the latest version of Python. Before you can start, ensure that the latest version of python is installed.

## Building this package locally

`python setup.py sdist`

## Installing the project package from GitHub

Issue this command to install from GitHub:

`pip install git+https://github.com/Chacho-Juma/mypackage.git`

If you need to install the latest version of this package, use:

`pip install --upgrade git+https://github.com/Chacho-Juma/mypackage.git`

## Prerequisites for package functionality

This package requires numpy to be installed. Issue these commands in your notebook to install and import numpy library:

```
pip install numpy
import numpy as np
```

## Import the project package

Issue this command to import the package:

`from myPackage import master`

## Running the codes

Once the package is installed into python the following functions can be used:

## top_n(items,n)

The function takes in a list of numerical values as items and an interger n which is the number of top items to return. It will return a list of top n items in descending order.

#### Example

An argument:  
`top_n([8, 3, 2, 7, 4], 3)`

Returns:

` {[8, 7, 3]`

## How to contribute to the project

To contribute to this repository, one needs to email the owners of this repository before making any changes.

For pull request process: Update the README.md with details of changes to the interface.
You may merge the Pull Request in once you have the sign-off of the developers.

## License

[MIT](https://choosealicense.com/licenses/mit/)
