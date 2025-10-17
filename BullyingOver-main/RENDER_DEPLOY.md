# 🚀 Deploy no Render - Contra o Bullying

## 📋 Arquivos Essenciais para o Render

### ✅ Arquivos Mantidos:
- `app.py` - Aplicação principal Flask
- `requirements.txt` - Dependências Python
- `Procfile` - Comando de inicialização
- `render.yaml` - Configuração do Render
- `templates/` - Templates HTML
- `static/` - CSS, JS e imagens
- `bullying.db` - Banco de dados SQLite

### 🗑️ Arquivos Removidos:
- Todos os scripts de teste e execução local
- Arquivos de configuração desnecessários
- Documentação de setup local

## 🔧 Configuração do Render

### 1. **Build Command**: 
```
pip install -r requirements.txt
```

### 2. **Start Command**: 
```
gunicorn app:app
```

### 3. **Environment Variables**:
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

## 🎯 Pronto para Deploy!

O projeto está limpo e otimizado para o Render com todos os arquivos essenciais.

**Desenvolvido por Guilherme Navasconi e Daniel Martins**
