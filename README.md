# VercelHostSetup

## Add This to the project urls
urlpatterns += static(settings.STATIC_URL, document_root=settings.STATIC_ROOT)

## Add This to the wsgi.py
app = application
