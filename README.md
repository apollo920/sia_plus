# Sia+

## Para criar este inicio de projeto foi utilizado os seguintes comandos (conforme a documentação https://cookiecutter-django.readthedocs.io/en/latest/2-local-development/developing-locally.html)

## Instação do cookiecutter
    pip install cookiecutter

## criação do virtual env path 
    python -m venv virtual_env_path

## Ativar o venv que acabou de criar
    virtual_env_path/Scripts/Activate

## Gerar um novo projeto cookiecutter-django
    cookiecutter gh:cookiecutter/cookiecutter-django

## o cookiecutter foi configurado da seguinte forma 

    [1/27] project_name (My Awesome Project): Sia +
    [2/27] project_slug (sia_+): sia_plus
    [3/27] description (Behold My Awesome Project!): teste do cookiecutter para o projeto sia+
    [4/27] author_name (Daniel Roy Greenfeld): apollo sá
    [5/27] domain_name (example.com): sia_plus.com
    [6/27] email (apollo-sá@sia_plus.com): apollolds2@gmail.com
    [7/27] version (0.1.0): 0.1.0
    [8/27] Select open_source_license
        1 - MIT
        2 - BSD
        3 - GPLv3
        4 - Apache Software License 2.0
        5 - Not open source
        Choose from [1/2/3/4/5] (1): 5
    [9/27] Select username_type
        1 - username
        2 - email
        Choose from [1/2] (1): 2
    [10/27] timezone (UTC): utc
    [11/27] windows (n): y
    [12/27] Select editor
        1 - None
        2 - PyCharm
        3 - VS Code
        Choose from [1/2/3] (1): 3
    [13/27] use_docker (n): y
    [14/27] Select postgresql_version
        1 - 16
        2 - 15
        3 - 14
        4 - 13
        5 - 12
        Choose from [1/2/3/4/5] (1): 1
    [15/27] Select cloud_provider
        1 - AWS
        2 - GCP
        3 - Azure
        4 - None
        Choose from [1/2/3/4] (1): 1
    [16/27] Select mail_service
        1 - Mailgun
        2 - Amazon SES
        3 - Mailjet
        4 - Mandrill
        5 - Postmark
        6 - Sendgrid
        7 - Brevo
        8 - SparkPost
        9 - Other SMTP
        Choose from [1/2/3/4/5/6/7/8/9] (1): 2
    [17/27] use_async (n): n
    [18/27] use_drf (n): n
    [19/27] Select frontend_pipeline
        1 - None
        2 - Django Compressor
        3 - Gulp
        4 - Webpack
        Choose from [1/2/3/4] (1): 4
    [20/27] use_celery (n): n
    [21/27] use_mailpit (n): n
    [22/27] use_sentry (n): n
    [23/27] use_whitenoise (n): n
    [24/27] use_heroku (n): n
    [25/27] Select ci_tool
        1 - None
        2 - Travis
        3 - Gitlab
        4 - Github
        5 - Drone
        Choose from [1/2/3/4/5] (1): 1
    [26/27] keep_local_envs_in_vcs (y): y
    [27/27] debug (n): n
    [SUCCESS]: Project initialized, keep up the good work! 