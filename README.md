# Barra Clínica Odontológica

Site de uma página da Barra Clínica Odontológica Urgência (Barra Olímpica, Rio de Janeiro).

É HTML, CSS e JavaScript puros em um único arquivo. Não tem build nem dependências: basta abrir `index.html` no navegador.

## Estrutura

```
index.html   página inteira (estilos e script embutidos)
img/         logo e fotos do perfil da clínica no Google
```

## Publicar

Qualquer hospedagem de arquivos estáticos serve. A pasta raiz do repositório é a pasta de publicação.

- **GitHub Pages:** Settings > Pages > Deploy from a branch > `main` / `(root)`.
- **Vercel ou Netlify:** importe o repositório e deixe o comando de build vazio.

## Onde editar

Tudo fica em `index.html`.

| O que | Onde |
| --- | --- |
| Número do WhatsApp | variável `numero` no `<script>` do fim do arquivo, e os `href="https://wa.me/..."` |
| Mensagem de cada botão | atributo `data-wa` do link |
| Horário de funcionamento | objeto `horas` no `<script>` e a tabela `.horas` na seção `#local` |
| Nota e número de avaliações | procure por `4,9` e `398` |
| Cores e fontes | variáveis em `:root`, no topo do `<style>` |
| Fotos | troque os arquivos em `img/` mantendo os nomes |

## Origem do conteúdo

Endereço, telefone, horário, descrição, nota, avaliações e fotos foram extraídos do perfil da clínica no Google Maps em outubro de 2026. Nota e contagem de avaliações mudam com o tempo e precisam ser atualizadas à mão.
