# Como Hospedar o Site Gratuitamente no GitHub Pages

Este guia explica como colocar seu site online usando o GitHub Pages (100% gratuito).

## Pré-requisitos
- Conta no GitHub (gratuita): https://github.com/signup

## Passo a Passo

### 1. Criar Conta no GitHub (se não tiver)
1. Acesse https://github.com/signup
2. Crie uma conta gratuita

### 2. Criar um Novo Repositório
1. Clique no botão **"+"** no canto superior direito
2. Selecione **"New repository"**
3. Configure:
   - **Repository name**: `rastreador-precos-br` (ou o nome que preferir)
   - **Description**: `Site oficial do Rastreador de Preços BR`
   - Marque **"Public"**
   - Marque **"Add a README file"**
4. Clique em **"Create repository"**

### 3. Fazer Upload dos Arquivos
1. No repositório criado, clique em **"Add file"** > **"Upload files"**
2. Arraste todos os arquivos da pasta `website`:
   - `index.html`
   - `style.css`
   - `privacy.html`
   - `terms.html`
   - `logo.png`
   - `screenshot.png` (você precisa criar - veja abaixo)
3. Em "Commit changes", escreva: `Adicionar arquivos do site`
4. Clique em **"Commit changes"**

### 4. Ativar o GitHub Pages
1. Vá em **Settings** (Configurações) do repositório
2. No menu lateral, clique em **"Pages"**
3. Em "Source", selecione:
   - Branch: **main**
   - Folder: **/ (root)**
4. Clique em **"Save"**
5. Aguarde alguns minutos (geralmente 1-5 minutos)
6. Seu site estará disponível em: `https://SEU_USUARIO.github.io/rastreador-precos-br`

### 5. (Opcional) Usar Domínio Personalizado
Se quiser um domínio próprio (ex: rastreadorprecos.com.br):

1. **Comprar domínio** (opções baratas ~R$30/ano):
   - Registro.br (domínios .com.br)
   - Namecheap
   - GoDaddy

2. **Configurar DNS** do domínio:
   - Adicione um registro CNAME apontando para `SEU_USUARIO.github.io`

3. **No GitHub Pages**:
   - Em Settings > Pages > Custom domain
   - Digite seu domínio
   - Marque "Enforce HTTPS"

## O que Você Precisa Adicionar

### Screenshot da Extensão
1. Abra a extensão no Chrome
2. Tire um print da tela (Windows: `Win + Shift + S`)
3. Salve como `screenshot.png` na pasta website
4. Faça upload para o GitHub

### Favicon (Opcional)
1. Use o site https://favicon.io/
2. Faça upload do seu logo
3. Baixe o favicon gerado
4. Adicione ao repositório

## Verificando se Está Funcionando

Após alguns minutos, acesse:
- `https://SEU_USUARIO.github.io/rastreador-precos-br`

Se aparecer o site, está tudo funcionando!

## Para o Stripe

Quando for cadastrar no Stripe, use a URL do seu site:
- Se usar GitHub Pages: `https://SEU_USUARIO.github.io/rastreador-precos-br`
- Se usar domínio próprio: `https://seudominio.com.br`

O Stripe vai verificar se:
1. O site está acessível (sem senha)
2. O nome do negócio aparece no site
3. Tem política de privacidade e termos de uso

## Suporte

Se tiver dúvidas, entre em contato: rastreadorprecosbr@gmail.com
