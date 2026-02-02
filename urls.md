from django.urls import path
from blog import views

urlpatterns = [path('', views.index, hame = 'home'),]                        #path(route, view, kwargs=None, name=None)
