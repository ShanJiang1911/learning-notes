### [DRF Permissions](https://www.django-rest-framework.org/api-guide/permissions/)
* "class IsAuthenticatedin" in REST framework is simplest style of permission to allow or deny access
* ```exceptions.PermissionDenied``` or ```exceptions.NotAuthenticated``` exception will be raised if check fails
* ```.get_object()```: object level permissions
* Setting permission policy: put DEFAULT_PERMISSION_CLASSES in setting.py
* ```APIView``` class-based views. ```@api_view```: decorator with function based views
* API reference:
  * <code>AllowAny</code>, <code>IsAuthenticated</code>, <code>IsAdminUser</code>, <code>IsAuthenticatedOrReadOnly</code>, <code>DjangoModelPermissions</code>, <code>DjangoModelPermissionsOrAnonReadOnly</code>, <code>DjangoObjectPermissions</code>
* Third party packages
  * <code>DRF - Access Policy</code>, <code>Django Rest Framework Roles</code>, <code>Django REST Framework API Key</code>. etc

### [Classy Django REST](https://www.cdrf.co/)


### [DRF Generic Views](https://www.django-rest-framework.org/api-guide/generic-views/)



[<--Back](README.md)