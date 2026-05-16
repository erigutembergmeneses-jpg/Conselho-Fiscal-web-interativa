# 🌐 Ecossistema Digital — Conselho Fiscal: Com Domínio das Contas

Este repositório contém os ficheiros da *Landing Page* interativa e minimalista que serve como o **Portal de Recursos e Bastidores** do livro **"Conselho Fiscal: Com domínio das contas"** (2ª Edição, 2026), de autoria de **Erigutemberg Meneses**. 

A página foi especialmente concebida para ser acedida através do **QR Code** posicionado na capa/contracapa do livro físico, transformando a obra tradicional numa experiência multimédia fluida, rápida e com alto impacto visual para telemóveis.

---

## 🚀 Características do Projeto

* **Design Minimalista & Premium:** Cores sóbrias (Preto Absoluto e Dourado) que refletem o rigor contábil e a seriedade jurídica da obra.
* **Otimização Mobile-First (Estilo Carrd.co):** Layout responsivo estruturado numa única coluna estreita, ideal para carregamento instantâneo via redes móveis (3G/4G/5G) em livrarias ou assembleias.
* **Engenharia Sonora:** Incorporação de um reprodutor de áudio nativo e minimalista para a transmissão do prefácio ou de uma mensagem direta do autor aos leitores.
* **Rotas por Perfil Profissional:** Segmentação de conteúdo focada em Conselheiros Fiscais, Síndicos, Advogados, Contadores e Auditores.
* **Central de Recursos:** Pontos de ancoragem para *downloads* diretos de ferramentas, minutas de atas e tabelas de conformidade legal.

---

## 📂 Estrutura do Ficheiro

* `index.html`: Ficheiro único e totalmente autónomo contendo a estrutura semântica (HTML5) e toda a estilização visual (CSS3 embutido). Sem dependências externas de *frameworks* pesados ou JavaScript complexo, garantindo segurança e latência zero.

---

## 🛠️ Como Implementar (Passo a Passo no GitHub Pages)

Para colocar esta ferramenta online e acessível a qualquer pessoa gratuitamente através do QR Code:

1.  **Criar o Repositório:** Crie um repositório público na sua conta do GitHub (ex: `conselho-fiscal-livro`).
2.  **Carregar o Ficheiro:** Suba o ficheiro `index.html` gerado para a raiz deste repositório.
3.  **Ativar o GitHub Pages:**
    * No menu superior do repositório, clique em **Settings** (Definições).
    * Na barra lateral esquerda, aceda a **Pages**.
    * Em *Build and deployment*, defina a Source como **Deploy from a branch**.
    * Selecione a *branch* `main` (ou `master`) e a pasta `/ (root)`. Clique em **Save**.
4.  **Obter a URL Pública:** Após cerca de 1 a 2 minutos, o GitHub fornecerá o link público do seu portal (ex: `https://o-seu-utilizador.github.io/conselho-fiscal-livro/`).

---

## 🎯 Configuração do QR Code na Capa

1.  Copie a URL pública gerada pelo GitHub Pages.
2.  Utilize um gerador de **QR Code Dinâmico** (permite alterar o link de destino no futuro se mudar de servidor, sem inutilizar a capa impressa).
3.  Insira o código gerado em alta resolução no ficheiro de paginação e *design* da capa do livro.

---

## 📝 Atualizações das Amostras Técnicas

Para ligar os botões aos seus ficheiros PDF reais, minutas em Word ou tabelas (como o *Anexo 21: Roteiro Prático de Fiscalização*), basta editar as seguintes linhas no ficheiro `index.html`:

```html
<a href="[https://link-do-seu-documento.pdf](https://link-do-seu-documento.pdf)" target="_blank" class="btn">
    📋 Roteiro Prático de Fiscalização (Anexo 21)
    <span class="btn-icon">→</span>
</a>
