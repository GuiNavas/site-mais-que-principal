# 🚀 DEPLOY NO RENDER - GUIA SIMPLES

## ⚡ PASSO A PASSO RÁPIDO

### 1️⃣ **PREPARAR GITHUB**
1. Acesse https://github.com
2. Clique "New repository"
3. Nome: `contra-o-bullying`
4. Marque "Public"
5. Clique "Create repository"
6. Faça upload de todos os arquivos da pasta `BullyingOver-main`

### 2️⃣ **CONFIGURAR RENDER**
1. Acesse https://render.com
2. Faça login
3. Clique "New +" → "Web Service"
4. Conecte com GitHub
5. Escolha o repositório `contra-o-bullying`

### 3️⃣ **CONFIGURAÇÕES**
```
Name: contra-o-bullying
Environment: Python 3
Region: Oregon (US West)
Branch: main
Root Directory: (deixe vazio)
Runtime: Python 3.12

Build Command: pip install -r requirements.txt
Start Command: gunicorn app:app

Environment Variables:
- Key: FLASK_ENV
- Value: production
```

### 4️⃣ **DEPLOY**
1. Clique "Create Web Service"
2. Aguarde o build (2-5 minutos)
3. Teste o site na URL fornecida

### 5️⃣ **TESTAR**
- **Site**: `https://SEU_SITE.onrender.com`
- **Admin**: `https://SEU_SITE.onrender.com/admin`
- **Senha**: `DanielGuilherme`

---

## ✅ ARQUIVOS NECESSÁRIOS (JÁ PRONTOS)

```
📁 Projeto/
├── app.py                    # ✅ Aplicação Flask
├── requirements.txt          # ✅ Dependências
├── Procfile                  # ✅ Comando de inicialização
├── bullying.db              # ✅ Banco de dados
├── templates/               # ✅ Templates HTML
└── static/                  # ✅ CSS, JS, Imagens
```

---

## 🔧 SE DER ERRO

### **Build Failed**
- Verifique se todas as dependências estão no `requirements.txt`
- Verifique os logs no Render Dashboard

### **Application Error**
- Verifique se o `app.py` está na raiz
- Verifique se o `Procfile` está correto

### **Static Files Not Loading**
- Verifique se os arquivos estão na pasta `static/`
- Verifique os caminhos nos templates

---

## 🎯 RESULTADO FINAL

✅ **Site 100% Responsivo**
✅ **Sistema de Denúncias**
✅ **Gráficos Dinâmicos**
✅ **Área Administrativa**
✅ **Formulário de Contato**
✅ **Números de Emergência**

**Tempo estimado**: 15-30 minutos

**Desenvolvido por Guilherme Navasconi e Daniel Martins**
