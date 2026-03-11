[![Formação Rocketseat](https://img.shields.io/badge/Forma%C3%A7%C3%A3o-Rocketseat-8257e5?style=for-the-badge&logo=rocketseat)](https://www.rocketseat.com.br/)

---

# Estrelas do Amanhã | Interface de Matrícula

Este projeto é um estudo aprofundado de **CSS Moderno** e **HTML Semântico**, focado na criação de formulários complexos com alta fidelidade visual. O objetivo foi construir uma interface de matrícula escolar robusta, utilizando apenas recursos nativos para prover feedback visual e interatividade.

## Arquitetura e Conceitos Aplicados

### 1. HTML5 Semântico e Acessibilidade

A estrutura foi pensada para ser lida logicamente por navegadores e tecnologias assistivas:

* **Organização por Contexto:** Uso rigoroso de `fieldset` e `legend` para agrupar dados relacionados (criança, responsável, endereço).
* **Controle de Formulário:** Implementação de `label` vinculados corretamente aos IDs, garantindo uma área de clique otimizada.
* **Divisão de Layout:** Separação clara entre o conteúdo principal (`main`) e a área institucional (`aside`).

### 2. CSS Avançado e Seletores Modernos

O grande diferencial deste projeto está no uso de seletores de última geração que reduzem a dependência de bibliotecas externas:

* **Pseudo-classe `:has()`:** Utilizada para estilizar o container pai com base no estado do filho (ex: mudar a borda do card quando o `radio` interno está marcado).
* **Pseudo-classe `:focus-within`:** Aplicada em wrappers de input para criar efeitos de foco sofisticados e aninhados.
* **Validação via CSS:** Uso de `:invalid` e `:required` para disparar mensagens de erro e estados visuais (bordas vermelhas) sem auxílio de scripts.
* **Custom Properties (Design Tokens):** Centralização de cores e tipografia no `:root`, permitindo uma manutenção simplificada e escalabilidade do tema.

### 3. Técnicas de Layout

* **Double-Column Layout:** Implementação de um grid principal que divide a tela em `51.25%` e `48.75%`, mantendo a harmonia visual entre o formulário e a área lateral.
* **Componentização via @import:** Organização do CSS em arquivos menores (`fields`, `button`, `radio`, `layout`), facilitando a leitura e organização do código.
* **Custom Radio/Checkbox:** Ocultação dos inputs nativos para a criação de interfaces personalizadas (cards de esporte e botões de turno) mantendo a funcionalidade original.


### PREVIEW

**Design e assets:** **[Ilana Mallak | Product Design da Rocketseat](https://www.linkedin.com/in/ilanamallak/)**

<img width="2560" height="5108" alt="image" src="https://github.com/user-attachments/assets/ea36574f-6d9c-4a41-9bdf-938294405ec7" />

## Variáveis de estilização
```css
:root {
    --font-family: "Poppins", sans-serif;
    --text: 400 1rem/1.5 var(--font-family);
    --text-sm: 400 0.875rem/1.4 var(--font-family);

    --text-primary:#292524;
    --text-secondary:#57534E;
    --text-tertiary:#8F8881;
    --text-highlight:#E43A12;
    --brand-light:#F67841;
    --brand-mid:#F3541C;
    --brand-dark:#E43A12;
    --surface-primary:#FFFFFF;
    --surface-secondary:#FEE7D6;
    --surface-disabled:#E7E5E4;
    --stroke-default:#D6D3D1;
    --stroke-highlight:#F3541C;
    --semantic-error:#DC2626;
}

```

Este projeto foi desenvolvido para fins de estudo.

Feito com 💜 pela **[Rocketseat](https://www.rocketseat.com.br/)**.
