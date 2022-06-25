# Django-CRUD
This repository is purposely created for zuri crud task

After following all the guidelines from the task instructions,
the only modification done for the model view to avoid 404 error was -
in project_app/urls.py instead of :path("blog/", include("blog.urls", namespace="blog")) , I have     path("", include("blog.urls", namespace="blog")).
