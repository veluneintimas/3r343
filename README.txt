# J.M.A Usinagem de Precisão — Site

## Como abrir
Abra o arquivo `index.html` no navegador.

## Estrutura
- `index.html` — estrutura do site
- `styles.css` — visual, responsividade e animações
- `script.js` — animações, galeria arrastável e formulário do WhatsApp
- `assets/logo-jma.png` — logo da J.M.A

## Como colocar os trabalhos
A seção "Trabalhos J.M.A" já está preparada como uma galeria horizontal.

Para trocar os placeholders por fotos:
1. Coloque as imagens dentro de `assets/`, por exemplo `trabalho-01.jpg`.
2. No `index.html`, localize cada `<div class="work-placeholder">`.
3. Troque o conteúdo do placeholder por:
   `<img src="assets/trabalho-01.jpg" alt="Descrição do trabalho">`
4. Se quiser, altere o nome do projeto no bloco `.work-info`.

O CSS já pode receber as fotos sem precisar refazer a estrutura.

## WhatsApp
O formulário está configurado para abrir uma conversa no número:
+55 11 98999-3311

Se o número mudar, altere a constante `phone` no `script.js`.

Contato: André — (11) 98999-3311


Serviços cadastrados no site:
- Torno CNC — capacidade até 1 metro
- Centro de Usinagem com 4º Eixo — peças complexas e alta precisão
- Torno Mecânico Convencional — até 4 metros de comprimento
- Fresadora
- Soldagem em Geral — MIG, TIG e Eletrodo
- Caldeiraria Pesada e Leve
- Projetos e Desenvolvimento de Peças
