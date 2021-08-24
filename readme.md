## Projeto e-diaristas

### Instalando o projeto

#### Clonar o projeto

`git clone https://github.com/daniellopes/Testes.git`

#### Instalar as dependencias

`pip install -r requirements.txt`

#### Alterar configuracoes do BD no arquivo `settings.py`

```
DATABASES = {
    "default": {
        "ENGINE": "django.db.backends.mysql",
        "NAME": "nome_do_banco_de_dados",
        "HOST": "host_do_banco_de_dados",
        "PORT": porta_do_banco_de_dados,
        "USER": "usuario_do_banco_de_dados",
        "PASSWORD": "senha_do_banco_de_dados",
    }
}
```

#### Migrar banco de dados

`python manage.py migrate`

#### Iniciar o servidor

`python manage.py runserver`
