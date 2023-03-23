Template for the Read the Docs tutorial
=======================================

This GitHub template includes fictional Python library
with some basic Sphinx docs.

Read the tutorial here:

https://docs.readthedocs.io/en/stable/tutorial/


Navigation
==========

This is the most important part of a documentation theme. If you like
the general look of the theme, please make sure that it is possible to
easily navigate through this sample documentation.

Ideally, the pages listed below should also be reachable via links
somewhere else on this page (like the sidebar, or a topbar). If they are
not, then this theme might need additional configuration to provide the
sort of site navigation that's necessary for "real" documentation.

.. toctree::
    :caption: This is a caption
    :titlesonly:

    placeholder-one
    placeholder-two
    really-long-title
    long-page
    External Link <https://www.sphinx-doc.org>

.. toctree::
    :hidden:
    :caption: Additional "hidden" Pages

    placeholder-three
    placeholder-four
    Sphinx Theme Gallery <https://sphinx-themes.org>

Some pages like :doc:`placeholder-three` are declared in a "hidden"
toctree, and thus would not be visible above. However, they are still a
part of the overall site hierarchy and some themes may choose to present
them to the user in the site navigation.

-----

.. [1] If you hit an error while building documentation with a new theme,
    it is likely due to some theme-specific configuration in the ``conf.py``
    file of that documentation. These are usually ``html_sidebars``,
    ``html_theme_path`` or ``html_theme_config``. Unsetting those will likely
    allow the build to proceed.
