# My first website

Primeiro exercício estático HTML/CSS com três páginas de streams e links de tecnologias.

[English](README.md)

## Ideia e processo

Código revisado em 01/10/2026. Walkthrough educacional baseado em material do Code Institute. Não foram encontrados planejamento datado, wireframes ou diário pessoal de design nos arquivos revisados. Registro do exercício, não história original de produto.

## Arquitetura e design

index.html aponta para recursos HTML5/CSS3 e imagens externas Wikimedia. stream-two.html/stream-three.html contêm títulos/texto curto. css/style.css define navegação escura, cards com float e dimensões de imagens; referencia Oswald sem carregar a fonte. Sem aplicação JavaScript, API ou banco na estrutura revisada.

## Preview local

```bash
python3 -m http.server 8000
```

Abra `http://localhost:8000/`. Fontes/ícones/imagens externas precisam de rede. Preview não executado nesta atualização; deploy público atual não confirmado.

## Testes e limites

Suíte automatizada não encontrada na listagem revisada da raiz. Testes de navegador/manuais não executados. Três páginas têm link CSS sem > final; primeiro card usa lass em vez de class. Valide HTML antes de confiar no layout. Confira navegação, imagens externas, telas estreitas, foco e segurança de links em nova aba. Logos/imagens externas mantêm seus direitos.

## Capturas

Nenhuma captura de aplicação verificada ou adicionada. Arquivos futuros datados em `docs/assets/` devem mostrar estados reais desktop/mobile, sem dados pessoais de formulário. Só adicione links após arquivos existirem, sem inventar estado funcional.

## Créditos e licença

Material de curso/template Code Institute, bibliotecas e assets mantêm direitos originais. Nenhuma licença nova. README original mantido no [apêndice em inglês](README.md#original-readme), como fonte histórica.
