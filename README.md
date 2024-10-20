### Inicializar el proyecto

- Crear entorno virtual (Primero se debe instalar venv si no se tiene)

```bash
  python -m venv <name>
```

- Encender entorno virtual

```bash
  // Windows (si no funciona probar activate.bat)
  <name>\Scripts\activate
  // Linux
  source <name>/bin/activate
```

- Instalar las dependecias

```bash
  pip install -r requirements.txt
```

- Correr el proyecto

```bash
  python manage.py runserver
```
