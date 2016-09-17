from importlib import import_module

from django.apps import AppConfig as BaseAppConfig


class AppConfig(BaseAppConfig):

    name = "smart_lighting"

    def ready(self):
        import_module("smart_lighting.receivers")
