# Como aplicar a versão 2 do site

## Objetivo
Atualizar apenas o visual/front-end do site, mantendo a estrutura estática em HTML e CSS.

## Branch recomendada
Use a mesma branch já criada:

atualizacao-site-curriculo-certificados

Se essa branch tiver sido apagada após o merge anterior, crie outra com o mesmo nome ou use:

melhoria-visual-site-v2

## Passo a passo no GitHub Desktop

1. Abra o GitHub Desktop.
2. Selecione o repositório `vinimilagres.github.io`.
3. Clique em `Current branch`.
4. Selecione `atualizacao-site-curriculo-certificados`.
5. Se a branch não existir mais, crie uma nova a partir da branch `principal`.
6. Clique em `Fetch origin`.
7. Se aparecer `Pull origin`, clique para atualizar sua máquina.
8. Extraia este pacote ZIP.
9. Copie os arquivos extraídos para dentro da pasta do projeto clonado.
10. Quando o Windows perguntar, escolha substituir os arquivos existentes.
11. Confira no GitHub Desktop a aba `Changes`.
12. Faça o commit com a mensagem:

Melhora visual responsivo do site profissional

13. Clique em `Push origin` ou `Publish branch`.
14. Abra o Pull Request no GitHub.
15. Revise e faça o merge para a branch `principal`.

## Teste local

Abra o arquivo `index.html` com a extensão Live Server do VS Code.

Teste no navegador:
- Página inicial
- Currículo
- Minha história
- Certificados
- Visual em celular, reduzindo a largura da janela

## Arquivos alterados

- index.html
- curriculo.html
- historia.html
- certificados.html
- assets/css/style.css
- assets/certificados/README.md
