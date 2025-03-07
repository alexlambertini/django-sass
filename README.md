### Development Environment SASS with Django

This repository provides an automated environment for development using Django, SCSS, and Browser Sync.

### 📦 Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/alexlambertini/django-sass.git
cd django-sass
npm install
```

### 🚀 Usage

To start the development environment, run:

```bash
npm start
```

This will:

Start the SCSS compiler (sass)
Run the Django server (python manage.py runserver)
Start browser-sync for automatic reloading

### 🔧 Dependencies

browser-sync - Browser synchronization
concurrently - Run multiple scripts simultaneously
sass - SCSS to CSS compiler
wait-on - Waits for the Django server before starting Browser Sync

### 🛠️ How to contribute

Fork this repository
Create a branch (git checkout -b my-feature)
Commit your changes (git commit -m 'My new feature')
Push to your branch (git push origin my-feature)
Open a Pull Request 🚀

### ⚙️ Django Static Files Configuration

Ensure you have the following settings in your Django settings.py file:

```bash
STATIC_URL = 'static/'

STATICFILES_DIRS = [
    os.path.join(BASE_DIR, 'static'),
]

STATIC_ROOT = os.path.join(BASE_DIR, 'staticfiles')
```

📌 Browser Sync Integration

```HTML
<script async src="http://localhost:3000/browser-sync/browser-sync-client.js"></script>
```

---

### 📌 Português

---

### Ambiente de Desenvolvimento SASS com Django

Este repositório fornece um ambiente automatizado para desenvolvimento com Django, SCSS e Browser Sync.

### 📦 Instalação

Clone o repositório e instale as dependências:

```bash
git clone https://github.com/alexlambertini/django-sass.git
cd django-sass
npm install
```

### 🚀 Uso

Para iniciar o ambiente de desenvolvimento, execute:

```bash
npm start
```

Isso irá:

Iniciar o compilador SCSS (sass)
Rodar o servidor Django (python manage.py runserver)
Rodar o browser-sync para recarregar automaticamente

### 🔧 Dependências

browser-sync - Sincronização do navegador
concurrently - Executa múltiplos scripts simultaneamente
sass - Compilador SCSS para CSS
wait-on - Aguarda o servidor Django antes de iniciar o Browser Sync

### 🛠️ Como contribuir

Fork este repositório
Crie uma branch (git checkout -b minha-feature)
Commit suas alterações (git commit -m 'Minha nova feature')
Faça push (git push origin minha-feature)
Abra um Pull Request 🚀

### ⚙️ Django Static file django

```bash
STATIC_URL = 'static/'

STATICFILES_DIRS = [
os.path.join(BASE_DIR, 'static'),
]

STATIC_ROOT = os.path.join(BASE_DIR, 'staticfiles')
```

📌 Browser Sync Intagração

```HTML
<script async src="http://localhost:3000/browser-sync/browser-sync-client.js"></script>
```
