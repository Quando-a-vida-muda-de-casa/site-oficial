# Quando a Vida Muda de Casa — Site oficial

Primeira versão funcional da página inicial do projeto psicoeducativo **Quando a Vida Muda de Casa**.

## Ver o site

Abrir `index.html` num navegador, ou usar um servidor local simples:

```bash
python -m http.server 8000
```

Depois abrir `http://localhost:8000`.

## Estrutura

- `index.html` — textos, secções e ordem dos conteúdos.
- `style.css` — cores, fontes, espaçamentos, aparência e adaptação ao telemóvel.
- `script.js` — menu móvel e ano automático do rodapé.
- `assets/` — ilustrações originais extraídas do livro do projeto.

## Editar

Esta versão é **editável ao nível dos ficheiros**. O editor visual do tipo arrastar-e-largar ainda **não está integrado** e terá de ser escolhido/configurado posteriormente. O GitHub por si só não disponibiliza edição visual ao estilo do Wix.

No HTML, procurar os títulos (como `As histórias`, `Atividades e recursos` e `Novidades e divulgação científica`) para alterar os respetivos textos. No CSS, alterar as variáveis no topo do ficheiro para modificar as cores.

## Publicação

O repositório pode permanecer privado durante o desenvolvimento. Com o plano gratuito, a publicação pelo GitHub Pages de um projeto num repositório privado não está disponível; antes de o tornar público, verificar cuidadosamente todos os ficheiros e os direitos de utilização dos conteúdos.

Quando se optar por publicar:
1. Carregar todos os ficheiros e a pasta `assets/` no repositório GitHub.
2. Confirmar que os materiais podem ser divulgados.
3. Tornar o repositório público (caso se pretenda GitHub Pages no plano Free).
4. Em **Settings → Pages**, selecionar **Deploy from a branch → main → /(root)** e guardar.

A página é um protótipo inicial: ainda não inclui leitor interativo, downloads de livros, CMS ou notícias reais. Essas funcionalidades exigem próximas etapas.

## Conteúdos e privacidade

- Não publicar dados pessoais de participantes, respostas de questionários ou informação confidencial da investigação.
- Não atribuir conclusões científicas ao projeto antes de existirem resultados aprovados para divulgação.
- As imagens foram extraídas dos ficheiros disponibilizados para o projeto. Verificar a autorização de uso e os créditos antes de publicar o site.
