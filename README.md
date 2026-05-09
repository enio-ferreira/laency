# LAENCY — Gestão de Semijoias

Sistema web de gestão para negócios de semijoias, desenvolvido como aplicação single-page (HTML único) com Firebase Realtime Database.

---

## 🚀 Funcionalidades

- **Dashboard** — KPIs de vendas, consignações e ranking de revendedoras
- **Nova Venda** — carrinho com produtos, cupons de desconto e pagamento via InfinitePay
- **Consignação** — controle de peças consignadas por revendedora com baixa automática
- **Acerto de Contas** — cálculo de comissão progressiva e histórico de pagamentos
- **Revendedoras** — cadastro, envio de acesso via WhatsApp, metas mensais
- **Produtos** — catálogo com categorias, importação por planilha Excel
- **Estoque** — posição em tempo real com alertas de reposição
- **Cupons** — uso único, por prazo ou por produto específico
- **Relatórios** — exportação em Excel e PDF
- **Usuários** — gerenciamento com autenticação 2FA (Google Authenticator)

---

## 🛠 Tecnologias

- HTML5 + CSS3 + JavaScript (vanilla)
- Firebase Realtime Database
- XLSX.js — importação/exportação de planilhas
- OTPAuth — autenticação 2FA TOTP
- InfinitePay — link de pagamento integrado

---

## ⚙️ Configuração

### Firebase
No arquivo `index.html`, localize e preencha:

```javascript
const FIREBASE_CONFIG = {
  apiKey:        "sua-api-key",
  authDomain:    "seu-projeto.firebaseapp.com",
  databaseURL:   "https://seu-projeto-default-rtdb.firebaseio.com",
  projectId:     "seu-projeto",
};
```

### InfinitePay
```javascript
const INFINITEPAY_HANDLE = 'sua-infinitetag';
```

---

## 🔐 Credenciais padrão

| Usuário | Senha | Perfil |
|---------|-------|--------|
| `admin` | `laency2026` | Administrador |

> ⚠️ Altere a senha padrão após o primeiro acesso.

---

## 📦 Deploy

### Hostinger
1. Acesse o Gerenciador de Arquivos
2. Navegue até a pasta do subdomínio
3. Faça upload do `index.html`

### Netlify
1. Acesse [drop.netlify.app](https://drop.netlify.app)
2. Arraste o `index.html`

---

## 🔄 Atualização via GitHub

1. Faça upload do novo `index.html` neste repositório
2. No app: **⬆ Atualizar → GitHub → Verificar Atualização**
3. Clique em **Atualizar Agora** — dados preservados automaticamente

---

## 📱 Acesso

- **App:** https://app.uselaency.com
- **Repositório:** https://github.com/enio-ferreira/laency

---

## 📄 Licença

Uso privado — LAENCY © 2026
