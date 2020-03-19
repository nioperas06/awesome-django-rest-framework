<h1 align="center">
	<img width="400" src="https://cdn.rawgit.com/sindresorhus/awesome/master/media/logo.svg" alt="Awesome">
</h1>

# Awesome Django REST Framework [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ![](https://img.shields.io/badge/nioperas06-approved-brightgreen.svg)

> Curated list of tools, processes and resources you need to create an awesome API with Django REST Framework!

**Let's make it the biggest resource repository for our community.**

*Please read the [contribution guidelines](contributing.md) before contributing.*

**Check out my [medium blog](https://medium.com/@nioperas06/) or say *hi* on [Twitter](https://twitter.com/jgantindev).**

## Table of Contents

- [Packages](#packages)
  - [Authentication](#authentication)
  - [Authorization](#authorization)
  - [Documentation](#documentation)
  - [Routing](#routing)
  - [Serialization](#serialization)
  - [Visualization](#visualization)
  - [Other](#other)
- [Tutorials](#tutorials)
- [Books](#books)
- [Talks](#talks)
- [Best practices](#bestpractices)
- [Common issues](#common-issues)

## Packages

  ### Authentication
  * [django-rest-passwordreset](https://github.com/anx-ckreuzberger/django-rest-passwordreset): Password reset endpoints that hook into Django Authentication system
  * [djoser](https://github.com/sunscrapers/djoser): REST implementation of Django authentication system
  * [django-rest-auth](https://github.com/Tivix/django-rest-auth/): A set of REST API endpoints to handle User Registration and Authentication tasks - ( **on pause and is currently unsupported**, [but there is a newer fork](https://github.com/jazzband/dj-rest-auth) )
  * [django-rest-registration](https://github.com/apragacz/django-rest-registration): User registration and authentication REST API, based on Django REST Framework.
  * [django-rest-framework-jwt](https://github.com/GetBlimp/django-rest-framework-jwt/): JSON Web Token Authentication support for Django REST Framework - ( **currently unmaintained**, [but there is a newer fork](https://github.com/Styria-Digital/django-rest-framework-jwt) )
  * [django-rest-framework-simplejwt](https://github.com/davesque/django-rest-framework-simplejwt): A JSON Web Token authentication plugin for the Django REST Framework
  * [django-rest-framework-social-oauth2](https://github.com/PhilipGarnero/django-rest-framework-social-oauth2): python-social-auth and oauth2 support for django-rest-framework
  * [django-oauth-toolkit](https://github.com/jazzband/django-oauth-toolkit): Django OAuth Toolkit can help you providing out of the box all the endpoints, data and logic needed to add OAuth2 capabilities to your Django projects. Django OAuth Toolkit makes extensive use of the excellent OAuthLib, so that everything is rfc-compliant.

  ### Authorization

  * [dry-rest-permissions](https://github.com/dbkaplan/dry-rest-permissions): Rules based permissions for the Django Rest Framework

  ### Documentation
  * [django-rest-swagger](https://github.com/marcgibbons/django-rest-swagger): Swagger Documentation Generator for Django REST Framework
  * [drf-yasg](https://github.com/axnsan12/drf-yasg): Alternative OpenAPI Generator for Django REST Framework with response schema support

  ### Routing

  * [drf-nested-routers](https://github.com/alanjds/drf-nested-routers): Nested Routers for Django Rest Framework

  ### Serialization
  * [django-rest-framework-recursive](https://github.com/heywbj/django-rest-framework-recursive/): Recursive Serialization for Django REST framework
  * [drf-extra-fields](https://github.com/Hipo/drf-extra-fields/): Extra fields for Django REST framework.

  ### Visualization

  * [django-rest-pandas](https://github.com/wq/django-rest-pandas): Serves up Pandas dataframes via the Django REST Framework for use in client-side (i.e. d3.js) visualizations and offline analysis (e.g. Excel)

  * [django-rest-framework-gis](https://github.com/djangonauts/django-rest-framework-gis): Geographic add-ons for Django REST Framework

  ### Other
  * [django-rest-localflavor](https://github.com/gilsondev/django-rest-localflavor/): Country-specific Django helpers, to use in Django Rest Framework
  * [django-rest-framework-json-api](https://github.com/django-json-api/django-rest-framework-json-api): Implements most of the JSON API 1.0 spec.
  * [django-rest-framework-bulk](https://github.com/miki725/django-rest-framework-bulk): Django REST Framework bulk CRUD view mixins
  * [drf-extensions](https://github.com/chibisov/drf-extensions): DRF-extensions is a collection of custom extensions for Django REST Framework

  ## Tutorials
  * [The Complete Guide to Django REST Framework and Vue JS](https://www.udemy.com/course/the-complete-guide-to-django-rest-framework-and-vue-js/?referralCode=A2FA0F6C1C4BE66A3B3E)
  * [Beginner's Guide to the Django REST Framework](https://code.tutsplus.com/tutorials/beginners-guide-to-the-django-rest-framework--cms-19786)
  * [Django Rest Framework - an Introduction](https://realpython.com/blog/python/django-rest-framework-quick-start/)
  * [Django REST Framework Tutorial](https://tests4geeks.com/django-rest-framework-tutorial/)
  * [Django REST Framework Course](https://teamtreehouse.com/library/django-rest-framework)
  * [Modern Django - Blog Series covering Django api and React frontend](http://v1k45.com/blog/modern-django-part-1-setting-up-django-and-react/)
  * [Building a RESTful API with Django REST Framework](http://agiliq.com/blog/2014/12/building-a-restful-api-with-django-rest-framework/)
  * [Getting Started with Django REST Framework and AngularJS](http://blog.kevinastone.com/getting-started-with-django-rest-framework-and-angularjs.html)
  * [End to End Web App with Django REST Framework & AngularJS](http://mourafiq.com/2013/07/01/end-to-end-web-app-with-django-angular-1.html)
  * [Start Your API - Django REST Framework Part 1](https://godjango.com/41-start-your-api-django-rest-framework-part-1/)
  * [Permissions & Authentication - Django REST Framework Part 2](https://godjango.com/43-permissions-authentication-django-rest-framework-part-2/)
  * [ViewSets and Routers - Django REST Framework Part 3](https://godjango.com/45-viewsets-and-routers-django-rest-framework-part-3/)
  * [Django REST Framework User Endpoint](http://richardtier.com/2014/02/25/django-rest-framework-user-endpoint/)
  * [Check Credentials Using Django REST Framework](http://richardtier.com/2014/03/06/110/)
  * [Creating a Production Ready API with Python and Django REST Framework – Part 1](https://www.andreagrandi.it/2016/09/28/creating-production-ready-api-python-django-rest-framework-part-1/)
  * [Creating a Production Ready API with Python and Django REST Framework – Part 2](https://www.andreagrandi.it/2016/10/01/creating-a-production-ready-api-with-python-and-django-rest-framework-part-2/)
  * [Classy Django REST Framework](http://www.cdrf.co/)

  ## Talks
  * [Fergal Walsh - Rethinking how we build HTTP APIs](https://www.youtube.com/watch?v=qTHkNkgFJeg)
  * [Samuel Fuentes - Fast product development using Django Rest Framework. #lessonslearned](https://www.youtube.com/watch?v=0hrf83ZIKw0&t=39s)
  * [Marco Montanari - Django, Django Rest Framework and Angular2: RAD on SaaS platforms](https://www.youtube.com/watch?v=DrQmYoZLGw8&t=129s)
  * [Alejandro Castillo - Django Rest Framework, one year after: tips, tools, tricks and pitfalls.](https://www.youtube.com/watch?v=0URILwS7-WI&t=18s)
  * [Rafał Nowicki - Python REST frameworks review](https://www.youtube.com/watch?v=HhKSgRvfF20&t=827s)

  ## Common issues
  * [Web API performance: profiling Django REST framework](https://www.dabapps.com/blog/api-performance-profiling-django-rest-framework/)
  * [My Experience in Serializer-Land (Django Rest Framework)](http://blog.traintracks.io/my-experience-in-serializer-land-django-rest-framework/)
  * [Optimizing slow Django REST Framework performance](http://ses4j.github.io/2015/11/23/optimizing-slow-django-rest-framework-performance/)
  * [Improve Serialization Performance in Django Rest Framework | How we reduced serialization time by 99%!](https://hakibenita.com/django-rest-framework-slow)
