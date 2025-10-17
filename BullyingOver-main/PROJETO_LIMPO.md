# 🧹 PROJETO LIMPO PARA RENDER

## ✅ Arquivos Mantidos (Essenciais)

### 📁 Estrutura Principal
```
BullyingOver-main/
├── app.py                    # Aplicação Flask principal
├── requirements.txt          # Dependências Python
├── Procfile                  # Comando de inicialização
├── render.yaml              # Configuração do Render
├── bullying.db              # Banco de dados SQLite
├── README.md                # Documentação
├── DEPLOY_RENDER.md         # Guia de deploy
├── RENDER_DEPLOY.md         # Instruções para Render
└── PROJETO_LIMPO.md         # Este arquivo
```

### 📁 Templates (HTML)
```
templates/
├── base.html                # Template base
├── index.html               # Página inicial
├── sobre.html               # Página sobre
├── denuncia.html            # Sistema de denúncias
├── estatisticas.html        # Gráficos e dados
├── contato.html             # Formulário de contato
└── admin.html               # Área administrativa
```

### 📁 Static (CSS, JS, Imagens)
```
static/
├── css/
│   ├── bootstrap.min.css    # Bootstrap CSS
│   └── style.css            # Estilos customizados
├── js/
│   └── bootstrap.bundle.min.js # Bootstrap JS
└── img/
    ├── logo.png             # Logo do projeto
    └── stop.png             # Ícone de parada
```

## 🗑️ Arquivos Removidos (Desnecessários)

### ❌ Scripts de Teste e Execução Local
- `test_python.py`
- `fix_and_run.py`
- `SOLUCAO_DEFINITIVA.py`
- `run_local.py`
- `app_simple.py`

### ❌ Scripts de Instalação Local
- `start_local.bat`
- `start_local.sh`
- `install_and_run.bat`
- `EXECUTAR_AGORA.bat`

### ❌ Documentação Local
- `SETUP_LOCAL.md`
- `COMO_RODAR.md`
- `COMO_EXECUTAR.txt`

### ❌ Pasta Desnecessária
- `bullyin-main/` (pasta vazia)

## 🚀 Configuração para Render

### 📋 Build Command
```bash
pip install -r requirements.txt
```

### 📋 Start Command
```bash
gunicorn app:app
```

### 📋 Environment Variables
- `FLASK_ENV=production`
- `PORT=10000` (automático)

## 📦 Dependências (requirements.txt)
```
Flask==2.3.3
matplotlib==3.7.2
Werkzeug==2.3.7
gunicorn==21.2.0
Pillow==10.0.1
numpy==1.24.3
```

## 🌐 Funcionalidades Implementadas

- ✅ **Site 100% Responsivo** (Mobile, Tablet, Desktop)
- ✅ **Sistema de Denúncias** com opção anônima
- ✅ **Gráficos Dinâmicos** (Barras e Pizza)
- ✅ **Área Administrativa** completa
- ✅ **Formulário de Contato** integrado
- ✅ **Números de Emergência** (Polícia 190, CVV 188)
- ✅ **Design Moderno** e acessível

## 🔐 Acesso Administrativo

- **URL**: `/admin`
- **Senha**: `DanielGuilherme`

## 📱 Páginas Disponíveis

- `/` - Início
- `/sobre` - Sobre o projeto
- `/denuncia` - Sistema de denúncias
- `/estatisticas` - Gráficos e dados
- `/contato` - Formulário de contato
- `/admin` - Área administrativa

## 🎯 Status do Projeto

✅ **PROJETO LIMPO E PRONTO PARA DEPLOY NO RENDER!**

Todos os arquivos desnecessários foram removidos, mantendo apenas o essencial para funcionar no Render.

**Desenvolvido por Guilherme Navasconi e Daniel Martins**
