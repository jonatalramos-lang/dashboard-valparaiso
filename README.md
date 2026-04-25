# 🌳 Dashboard Valparaíso Adventure Park

Painel executivo do Valparaíso Adventure Park com visão consolidada de todas as linhas de receita.

## 🚀 Como publicar

### 1. Subir no GitHub
- Criar repositório público chamado `dashboard-valparaiso`
- Fazer upload de todos os arquivos desta pasta

### 2. Publicar na Vercel
- Entrar em [vercel.com](https://vercel.com)
- Fazer login com GitHub
- "Add New Project" → Importar o repositório
- Clicar em "Deploy" (aceitar configurações padrão)
- Pronto! URL ativa.

## 💻 Rodar localmente (opcional)

```bash
npm install
npm run dev
```

## 📊 Funcionalidades

- **Visão Executiva**: tabela histórica 2019-2026 com metas e crescimento
- **Painel A4**: versão compacta pronta pra imprimir
- **7 produtos**: Assinaturas V+, Consumo A&B, Eventos, Bilheteria Online, Bilheteria Park, Passaporte Corporativo, Acesso
- **Ranking gamificado** de consultores
- **Metas +20% YoY** com crescimento variável histórico
- **Calendários de venda e ocupação**

## 📝 Atualizar dados

Os dados estão em `src/App.jsx` nas constantes `DADOS_*` e `OVERRIDES_DIRETORIA`.

## 🛠️ Tecnologias

- React 18
- Vite
- Recharts
- Tailwind CSS
- Lucide Icons

## 📄 Licença

Uso interno — Valparaíso Adventure Park
