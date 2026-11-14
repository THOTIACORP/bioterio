# Biotério Forte: site de apresentação

Página única, estática (HTML, CSS e JavaScript sem build), com o equipamento V1 e V2 em 3D, os dois conjuntos de imagens da simulação e a galeria das 54 simulações.

## Conteúdo

```
index.html          a página inteira (modelos 3D simplificados já embutidos no arquivo)
sim/conjunto_1.jpg  conjunto de imagens 1 (seção Validação)
sim/conjunto_2.jpg  conjunto de imagens 2 (seção Validação)
sim/t/              miniaturas das simulações (54 imagens)
sim/f/              imagens ampliadas das simulações (54 imagens)
.nojekyll           evita que o GitHub Pages processe a pasta
```

## Antes de publicar

1. Abra `index.html` num editor de texto e procure por `[adicione seu e-mail de contato]`. Troque pelo e-mail que você quer exibir.
2. Confira o rodapé (nome e ano) e a lista de apoios.

## Publicar no GitHub Pages

1. Crie um repositório novo no GitHub (por exemplo `bioterio-forte`).
2. Envie todos os arquivos desta pasta para a raiz do repositório (Add file > Upload files, ou `git add . && git commit && git push`).
3. Em Settings > Pages, escolha "Deploy from a branch", branch `main`, pasta `/ (root)`, e salve.
4. Em alguns minutos o site abre em `https://SEU-USUARIO.github.io/bioterio-forte/`.

## Testar no seu computador

Abra o `index.html` com duplo clique, ou sirva por HTTP: `python -m http.server 8000` e abra http://localhost:8000.

## Observações

- As fontes (Bricolage Grotesque e Inter) vêm do Google Fonts. Sem internet, a página usa fontes do sistema.
- O 3D usa WebGL puro e precisa de um navegador atual. Os modelos são versões simplificadas das peças.
- Os ajustes feitos no painel "Ajustar montagem" ficam só no navegador de quem os fez.
- O protótipo está em validação e não é um produto certificado. Mantenha esse aviso no rodapé.
