# 💰 Venda do Dia - Mercearia do Fábio

Este projeto foi desenvolvido como parte do **PEX V (Projeto de Extensão)** da faculdade Descomplica. O objetivo é fornecer uma solução simples, rápida e gratuita para o controle de vendas diárias de pequenos comércios, como a Mercearia do Fábio.

A aplicação é um **site estático** (apenas HTML, CSS e JavaScript) que funciona 100% no navegador, sem a necessidade de servidor ou banco de dados. Os dados são salvos localmente no dispositivo (usando `localStorage`).

## 🔗 Acesso ao Projeto

O projeto está hospedado gratuitamente no GitHub Pages e pode ser acessado diretamente por qualquer dispositivo (celular, tablet ou computador):

**URL do Site:** [https://arturnery.github.io/projeto-PEXV-faculdade-descomplica/](https://arturnery.github.io/projeto-PEXV-faculdade-descomplica/)

## ✨ Funcionalidades

*   **Controle em Uma Única Tela:** Toda a operação é feita em uma única página, otimizada para uso em celular.
*   **Registro Rápido de Vendas:** Botões grandes e coloridos para registrar vendas por tipo de pagamento: **DINHEIRO**, **CARTÃO** e **FIADO**.
*   **Cálculo Automático:** Selecionando um produto pré-cadastrado e a quantidade, o valor total é calculado automaticamente.
*   **Exclusão de Vendas:** Possibilidade de excluir uma venda registrada (botão **"X"** ao lado do item) em caso de erro.
*   **Relatório Diário:** Exibição em tempo real do **Total do Dia** e dos totais separados por forma de pagamento.
*   **Backup via WhatsApp:** Botão **"ENVIAR WHATS"** que gera um relatório completo do dia e abre o WhatsApp para envio.
*   **Limpeza Diária:** Botão **"LIMPAR DIA"** para zerar as vendas do dia, pronto para o dia seguinte.

## 🛠️ Tecnologia Utilizada

*   **HTML5:** Estrutura da página.
*   **CSS3:** Estilização e layout responsivo.
*   **JavaScript (Puro):** Lógica de controle, cálculo e persistência de dados.
*   **`localStorage`:** Utilizado como "banco de dados" local para salvar as vendas no próprio navegador.

## 📱 Como Usar (Recomendado para o Celular)

Para que o site funcione como um aplicativo no celular:

1.  Acesse a **URL do Site** no navegador do celular.
2.  No menu do navegador (geralmente os três pontos ou o ícone de compartilhamento), selecione a opção **"Adicionar à Tela Inicial"** (ou "Instalar Aplicativo").
3.  Um ícone será criado na tela inicial, permitindo o acesso rápido com um toque.

**⚠️ Atenção:** Os dados são salvos apenas no dispositivo. É **fundamental** usar o botão **"ENVIAR WHATS"** ao final do dia para garantir o backup do relatório.

## 🧑‍💻 Desenvolvimento

O código principal está no arquivo `index.html`.

Para clonar o projeto e fazer modificações:

```bash
git clone https://github.com/arturnery/projeto-PEXV-faculdade-descomplica.git
cd projeto-PEXV-faculdade-descomplica
```

Para alterar a lista de produtos, edite o array `const PRODUTOS` dentro da tag `<script>` no arquivo `index.html`.
