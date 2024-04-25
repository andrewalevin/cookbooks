

# python-pypi


### Bash Commands

```bash

python3 -m pip install --upgrade build

python3 -m build

twine upload dist/*


# Upload Existing

twine upload --skip-existing dist/*


```






### Test Python

```bash

python3 -m pip install --upgrade twine

python3 -m twine upload --repository testpypi dist/*

```






### Code

```python

require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html

```































