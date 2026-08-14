# Biblioteca de Imagens — Site

Repositório destinado ao armazenamento e organização das imagens utilizadas no site.

## 📁 Estrutura

As imagens devem ser organizadas por finalidade:

```text
/
├── imagens/
│   ├── banners/
│   ├── produtos/
│   ├── logos/
│   ├── icones/
│   └── outros/
└── README.md
```

## 🔗 Uso das imagens

As imagens podem ser utilizadas diretamente no site por meio dos links do GitHub.

Exemplo:

```html
<img src="https://raw.githubusercontent.com/USUARIO/REPOSITORIO/main/imagens/exemplo.png" alt="Descrição da imagem">
```

Ou em CSS:

```css
background-image: url("https://raw.githubusercontent.com/USUARIO/REPOSITORIO/main/imagens/exemplo.png");
```

## 📌 Padrão de arquivos

Sempre que possível:

* Usar nomes descritivos.
* Evitar espaços e caracteres especiais.
* Utilizar letras minúsculas.
* Preferir `-` ou `_` para separar palavras.
* Otimizar as imagens antes do upload.

### Exemplos

```text
banner-home.png
logo-revvo.svg
produto-learningflix.webp
icone-ia.svg
```

## 🖼️ Formatos

Formatos recomendados:

* **WebP** — imagens para o site
* **SVG** — logos e ícones
* **PNG** — imagens com transparência
* **JPG/JPEG** — fotografias

## ⚠️ Importante

Este repositório é destinado exclusivamente aos arquivos de imagem utilizados no site.

Ao adicionar uma nova imagem, mantenha a organização das pastas e siga o padrão de nomenclatura definido acima.
