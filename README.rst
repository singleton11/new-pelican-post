New Pelican Post
################

A cookiecutter for new pelican post boilerplate::

    $ cookiecutter https://github.com/singleton11/new-pelican-post -f
    content_folder [content]:
    title [New Post]: @ operator in python 3.5
    created [2016-12-17 22-19-48]:
    tags [python, django]: python, syntax sugar, operators
    category [django]:
    slug [@_operator_in_python_3.5]:
    authors [Anton Prokhorov]:
    $

-f flag is necessary because in pelican blog we already have content folder, to avoid error about existence of folder

``content_folder`` variable is needed for point where your content folder located.

This will generate a file with following content

**@_operator_in_python_3.5.rst**::

    @ operator in python 3.5
    ########################

    :date: 2016-12-17 22-19-48
    :modified: 2016-12-17 22-19-48
    :tags: python, syntax sugar, operators
    :category: django
    :slug: @_operator_in_python_3.5
    :authors: Anton Prokhorov
    :summary: Summary
