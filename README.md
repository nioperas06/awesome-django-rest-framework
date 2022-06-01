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
  - [Logging](#logging)
  - [Filtering](#filtering)
  - [Pagination](#pagination)
  - [Renderers and Parsers](#renderers-and-parsers)
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
  * [dj-rest-auth](https://github.com/jazzband/dj-rest-auth): A set of REST API endpoints to handle User Registration and Authentication tasks
  * [django-rest-registration](https://github.com/apragacz/django-rest-registration): User registration and authentication REST API, based on Django REST Framework.
  * [django-rest-framework-simplejwt](https://github.com/davesque/django-rest-framework-simplejwt): A JSON Web Token authentication plugin for the Django REST Framework
  * [django-rest-framework-social-oauth2](https://github.com/PhilipGarnero/django-rest-framework-social-oauth2): python-social-auth and oauth2 support for django-rest-framework
  * [django-oauth-toolkit](https://github.com/jazzband/django-oauth-toolkit): Django OAuth Toolkit can help you providing out of the box all the endpoints, data and logic needed to add OAuth2 capabilities to your Django projects. Django OAuth Toolkit makes extensive use of the excellent OAuthLib, so that everything is rfc-compliant.
  * [django-rest-durin](https://django-rest-durin.readthedocs.io/en/latest/index.html) provides token auth for multiple Web/CLI/Mobile API clients via one interface but allows different token configuration for each client (For example, permissions and token expiration time can be different per API client).
  * [djangorest-routes](https://github.com/israelabraham/djangorest-routes): Djangorest Routes is an authentication library strongly built in Python that serves the purpose of quick bootstrapping a project's authentication infrastructure.

  ### Authorization

  * [dry-rest-permissions](https://github.com/dbkaplan/dry-rest-permissions): Rules based permissions.
  * [drf-access-policy](https://github.com/rsinger86/drf-access-policy): Declarative access policies/permissions modeled after AWS' IAM policies.
  * [djangorestframework-api-key](https://github.com/florimondmanca/djangorestframework-api-key): API key permissions.
  * [djangorestframework-composed-permissions](https://github.com/niwinz/djangorestframework-composed-permissions): A simple way to define complex permissions.
  * [rest_condition](https://github.com/caxap/rest_condition): Complex permissions flow.
  * [django-rest-framework-roles](https://github.com/computer-lab/django-rest-framework-roles): Parameterizes Django REST Framework methods over user-defined roles.
  * [django-rest-framework-role-filters](https://github.com/allisson/django-rest-framework-role-filters): Simple role filtering.
  * [drf-psq](https://github.com/drf-psq/drf-psq): The simplest and most general way to manage action-based permissions, serializers, and querysets dependent on permission-based rules.

  ### Documentation
  * [drf-yasg](https://github.com/axnsan12/drf-yasg): Alternative OpenAPI Generator for Django REST Framework with response schema support
  * [drf-spectacular](https://github.com/tfranzel/drf-spectacular): Sane and flexible OpenAPI 3.0 schema generation for Django REST framework
  * [drf-openapi-tester](https://github.com/snok/drf-openapi-tester): Test drf test responses against OpenAPI/Swagger documentation.
  
  ### Routing

  * [drf-nested-routers](https://github.com/alanjds/drf-nested-routers): Nested Routers for Django Rest Framework

  ### Serialization
  * [django-rest-framework-recursive](https://github.com/heywbj/django-rest-framework-recursive/): Recursive Serialization for Django REST framework
  * [drf-extra-fields](https://github.com/Hipo/drf-extra-fields/): Extra fields for Django REST framework.
  * [drf-flex-fields](https://github.com/rsinger86/drf-flex-fields): Dynamically set fields and expand nested resources in Django REST Framework serializers. 
  * [drf-writable-nested](https://github.com/beda-software/drf-writable-nested): Writable nested model serializer for Django REST Framework 

  ### Visualization

  * [django-rest-pandas](https://github.com/wq/django-rest-pandas): Serves up Pandas dataframes via the Django REST Framework for use in client-side (i.e. d3.js) visualizations and offline analysis (e.g. Excel)
  * [django-rest-framework-gis](https://github.com/djangonauts/django-rest-framework-gis): Geographic add-ons for Django REST Framework
  * [drf-renderer-xlsx](https://github.com/wharton/drf-renderer-xlsx): Allows you to create XLSX for Django REST Framework

  ### Logging

  * [drf-api-tracking](https://github.com/lingster/drf-api-tracking): Provides a Django model and DRF view mixin that work together to log Django Rest Framework requests to the database.
  * [django-requestlogs](https://github.com/Raekkeri/django-requestlogs): Package providing middleware and other helpers for audit logging.

  ### Filtering
  
  * [django-rest-framework-filters](https://github.com/philipn/django-rest-framework-filters): Better filtering.
  * [django-rest-framework-word-search-filter](https://github.com/trollknurr/django-rest-framework-word-search-filter): Full word search filter backend for Django REST Framework. DB backend independent.
  * [django-url-filter](https://github.com/miki725/django-url-filter): Django URL Filter provides a safe way to filter data via human-friendly URLs.
  * [drf-url-filters](https://github.com/manjitkumar/drf-url-filters): A django app to apply filters on drf querysets using query params with validations using voluptuous.

  ### Pagination

  * [drf-proxy-pagination](https://github.com/tuffnatty/drf-proxy-pagination): Pagination class for Django REST Framework to choose pagination class by query parameter
  * [django-rest-framework-link-header-pagination](https://github.com/tbeadle/django-rest-framework-link-header-pagination): Provide pagination for django-rest-framework using a "Link" HTTP header

  ### Renderers and Parsers

  * [django-rest-framework-yaml](https://github.com/jpadilla/django-rest-framework-yaml): YAML support for Django REST Framework.
  * [django-rest-framework-xml](https://github.com/jpadilla/django-rest-framework-xml): XML support for Django REST Framework.
  * [django-rest-framework-jsonp](https://github.com/jpadilla/django-rest-framework-jsonp): JSONP support for Django REST Framework.
  * [drf-excel](https://github.com/wharton/drf-excel): An XLSX spreadsheet renderer for Django REST Framework.
  * [django-rest-framework-csv](https://github.com/mjumbewu/django-rest-framework-csv): CSV Tools for Django REST Framework.
  * [drf-ujson-renderer](https://github.com/gizmag/drf-ujson-renderer): Django Rest Framework renderer using ujson.
  * [djangorestframework-camel-case](https://github.com/vbabiy/djangorestframework-camel-case): Camel case JSON support for Django REST framework.
  * [django-rest-pandas](https://github.com/wq/django-rest-pandas): Serves up Pandas dataframes via the Django REST Framework for use in client-side (i.e. d3.js) visualizations and offline analysis (e.g. Excel).
  * [rest-framework-latex](https://github.com/mypebble/rest-framework-latex): A LaTeX renderer for Django REST Framework.

  ### Other
  * [django-rest-localflavor](https://github.com/gilsondev/django-rest-localflavor/): Country-specific Django helpers, to use in Django Rest Framework
  * [django-rest-framework-json-api](https://github.com/django-json-api/django-rest-framework-json-api): Implements most of the JSON API 1.0 spec.
  * [drf-extensions](https://github.com/chibisov/drf-extensions): DRF-extensions is a collection of custom extensions for Django REST Framework
  * [drf-generators](https://github.com/Brobin/drf-generators): Generate Views, Serializers, and Urls for your Django Rest Framework application.
  * [django-restql](https://github.com/yezyilomo/django-restql): Turn your API made with Django REST Framework(DRF) into a GraphQL like API. 
  * [django-rest-tsg](https://github.com/jinkanhq/django-rest-tsg): A TypeScript code generator for DRF serializers, enums and dataclasses.
  * [django-rest-cli](https://github.com/py-universe/django-rest-cli): A CRUD endpoints generator and flexible cookiecutter for rapid REST APIs dev.

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
  * [Permissions in Django REST Framework](https://testdriven.io/blog/drf-permissions/)
  * [Built-in Permission Classes in Django REST Framework](https://testdriven.io/blog/built-in-permission-classes-drf/)
  * [Effectively Using Django REST Framework Serializers](https://testdriven.io/blog/drf-serializers/)

  ## Books
  * [Django for APIs: Build web APIs with Python and Django](https://djangoforapis.com/)
  
  ## Courses
  * [Test-Driven Development with Django, Django REST Framework, and Docker](https://testdriven.io/courses/tdd-django/)
  
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
