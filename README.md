# Flaskapp00 Cloudinary

You can install Cloudinary's module using either easy_install or pip package management tools:

```pip install cloudinary```

In pycharm you may need to do Pycharm > Preferences > Project Interpreter > Click plus > search cloudinary  > Install package

Include Cloudinary's Python classes in your code:

```python
import cloudinary
import cloudinary.uploader
import cloudinary.api
```

Put your environmen variables in a config.py file like so:
```python
CLOUDINARY_CLOUD_NAME="mycloudname"
CLOUDINARY_API_KEY="myapikey"
CLOUDINARY_API_SECRET="myapisecret"
```