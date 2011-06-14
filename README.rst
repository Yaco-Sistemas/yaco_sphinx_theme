Yaco Sphinx Theme
=================

This repository contains Yaco themes for Yaco related projects.
To use a theme in your Sphinx documentation, follow this guide:

1. put this directory as _themes into your docs folder.  Alternatively
   you can also use git submodules to check out the contents there
   or symlink this directory as _themes.

2. add this to your conf.py::

    sys.path.append(os.path.abspath('_themes'))
    html_theme_path = ['_themes']
    html_theme = 'yaco'
    pygments_style = 'yaco_theme_support.YacoStyle'
    html_logo = 'logo_orange.png'

The following themes exist:

- **yaco** - the generic Yaco Project documentation theme. Orange color
- **htmlslide** - A slide theme. Orange color