# test_work_HN
Для установки приложения:
1. Установите приложение "posts" в свой проект Джанго.
2. Зависимости указаны в файле requirements.txt
3. В файле *your_django_project_directory/urls.py добавьте в список 'urlpatterns' строку - "path('', include('posts.urls')),".
4. В файле *your_django_project_directory/settings.py дбавьте в список 'INSTALLED_APPS' строки -'rest_framework',
    'posts',
5. Проведите миграции бд
