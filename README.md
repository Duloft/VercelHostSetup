# VercelHostSetup

## Add This to the project urls
urlpatterns += static(settings.STATIC_URL, document_root=settings.STATIC_ROOT)

## Add This to the wsgi.py
app = application

STATIC_ROOT = os.path.join(BASE_DIR, "staticfiles_build", 'static')

STATIC_ROOT = BASE_DIR/"staticfiles_build"/'static'


## staticfiles_build must not change both in the settings.py and vercel.json
### always set the config to git config user.name "git_user_name" then follow by another git command for email git config user.email "git_email"
then you commit.

