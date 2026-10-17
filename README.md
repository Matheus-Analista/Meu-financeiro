# 💜 Meu Financeiro - Gestão Familiar & Open Finance

Plataforma moderna, segura e completa para **gestão financeira familiar**, integrando contas bancárias compartilhadas, análise inteligente de despesas com IA, controle de saúde familiar, metas financeiras conjuntas e personalização de perfil em alta definição.

---

## 🔐 Acesso e Segurança do Sistema

O sistema conta com tela de bloqueio e autenticação protegida por senha de acesso local:

- **Senha Padrão de Acesso:** `2709`
- **Recursos de Segurança:**
  - Bloqueio automático de sessão com tela de autenticação;
  - Teclado virtual numérico integrado e suporte a digitação física;
  - Opção de lembrar sessão no dispositivo;
  - Botão de bloqueio instantâneo disponível no cabeçalho e na barra lateral.

---

## 🚀 Principais Funcionalidades

1. **Dashboard Financeiro Consolidado:**
   - Saldo geral consolidado do casal (Matheus & Stéfanny);
   - Gráficos dinâmicos de receitas, despesas e fluxo mensal;
   - Alertas inteligentes de faturas e compromissos.

2. **Gestão de Contas Bancárias (Titular & Parceira):**
   - Contas individuais e conjuntas (Nubank, Inter, Itaú, Bradesco, Pan, Caixa);
   - Integração com extratos bancários reais e Open Finance (Pluggy);
   - Leitura de comprovantes e documentos em PDF/imagens.

3. **Análise Financeira com IA (Google Gemini):**
   - Diagnóstico automático de gastos por categorias;
   - Dicas personalizadas de economia e investimentos para a família.

4. **Metas & Sonhos Familiares:**
   - Acompanhamento de progresso com depósitos, prazos e prioridades;
   - Metas individuais e compartilhadas com badges visuais.

5. **Gestão Médica & Saúde Familiar:**
   - Controle de despesas com medicamentos e consultas por membro da família;
   - Histórico de compras em farmácias com fotos individuais de cada dependente.

6. **Fotos de Perfil com Recorte 1:1 de Precisão:**
   - Ajuste em proporção **1:1 quadrada** com guias de regra dos terços e avatar circular;
   - **Bloqueio rígido de bordas:** a imagem não ultrapassa os limites do enquadramento;
   - Persistência permanente via **IndexedDB** e **LocalStorage**, garantindo que as fotos nunca se percam ao recarregar.

---

## 🛠️ Tecnologias Utilizadas

- **Frontend:** [React 19](https://react.dev/), [TypeScript](https://www.typescriptlang.org/), [Vite](https://vitejs.dev/)
- **Estilização:** CSS Moderno com Design Tokens, Glassmorphism e Tema Claro/Escuro
- **Gráficos:** [Recharts](https://recharts.org/)
- **Ícones:** [Lucide React](https://lucide.dev/)
- **Armazenamento Local:** IndexedDB + LocalStorage para persistência de fotos e preferências
- **Backend & Storage:** [Supabase](https://supabase.com/)
- **Open Finance:** [Pluggy](https://pluggy.ai/)

---

## 📦 Como Executar o Projeto Localmente

### Pré-requisitos
- [Node.js](https://nodejs.org/) (versão 18 ou superior)
- `npm` ou `yarn`

### Passo a Passo

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/SEU_USUARIO/sistema-meu-financeiro.git
   cd sistema-meu-financeiro
   ```

2. **Instale as dependências:**
   ```bash
   npm install
   ```

3. **Configure as variáveis de ambiente:**
   Copie o arquivo `.env.example` para `.env`:
   ```bash
   cp .env.example .env
   ```

4. **Inicie o servidor de desenvolvimento:**
   ```bash
   npm run dev
   ```
   O sistema estará disponível em: `http://localhost:5173/`

5. **Acesse o sistema:**
   Digite a senha **`2709`** para entrar no painel principal.

---

## 🌐 Publicação no GitHub Pages (Sem Subpastas)

O projeto está totalmente configurado para rodar no **GitHub Pages** sem depender de pastas internas:

- Os arquivos finais estão compilados diretamente na raiz do repositório:
  - `index.html`
  - `index.js`
  - `index.css`
  - `favicon.svg`
  - `.nojekyll`
- Todos os links são relativos (`./index.js`, `./index.css`), garantindo funcionamento em qualquer subdomínio do GitHub (`https://seu-usuario.github.io/nome-do-repo/`).

### Como ativar no seu GitHub:
1. Suba os arquivos para o seu repositório no GitHub.
2. Acesse **Settings** > **Pages**.
3. Em **Build and deployment**:
   - **Source:** selecione `Deploy from a branch`.
   - **Branch:** selecione `main` (ou `master`) e a pasta `/ (root)` (ou `/docs`).
4. Clique em **Save**. O GitHub publicará seu sistema com acesso protegido pela senha **`2709`**!

---

## 🛡️ Licença e Privacidade

Projeto para uso pessoal e familiar. Dados sensíveis e chaves de API estão protegidos pelo `.gitignore` e não devem ser versionados publicamente no GitHub.
