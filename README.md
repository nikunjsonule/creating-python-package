# Sample package

This is a simple example package. This is only for 1 package. If you've different multiple directory and packages then use find_packages

Ex - from setuptools import setup, find_packages

- >>     PS C:\Users\Dell\Desktop\pkg\sample_package> python setup.py sdist bdist_wheel

- >>     PS C:\Users\Dell\Desktop\pkg\sample_package> cd dist

- >>     PS C:\Users\Dell\Desktop\pkg\sample_package\dist> ls

- >>     PS C:\Users\Dell\Desktop\pkg\sample_package\dist> pip install sample_package-0.1-py3-none-any.whl
     (i.e pip install package_file_name)


# If you update package
(continuing from above)

- >>     PS C:\Users\Dell\Desktop\pkg\sample_package\dist> cd ..

- >>     PS C:\Users\Dell\Desktop\pkg\sample_package> python setup.py sdist bdist_wheel

- >>     PS C:\Users\Dell\Desktop\pkg\sample_package> cd dist

- >>     PS C:\Users\Dell\Desktop\pkg\sample_package\dist> pip install sample_package-0.2-py3-none-any.whl

# Image

![python_package](https://user-images.githubusercontent.com/48853755/181710972-38cf78ff-ec14-4c04-af9c-581e689a393a.jpg)
