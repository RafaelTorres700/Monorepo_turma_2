# Monorepo_turma_2

Exercício de colaboração: cada estagiário cria uma página pessoal inspirada na referência `torres/`.

## Pastas

As pastas dos projetos ficam lado a lado na raiz do repositório:

```text
Monorepo_turma_2/
├── modelo/
├── torres/
└── <seu-nome>/
```

- `modelo/`: arquivos iniciais em HTML e CSS.
- `torres/`: exemplo pronto, incluindo uma imagem em `assets/`.
- `<seu-nome>/`: pasta que cada estagiário cria na raiz, nunca dentro de `modelo/`.

Na sua página, inclua cabeçalho e rodapé azul-claros, fundo cinza-claro, apresentação e imagem com texto alternativo. 

## Colaboração

Clone o repositório e crie uma branch com seu nome:

```bash
git clone https://github.com/RafaelTorres700/Monorepo_turma_2.git
cd Monorepo_turma_2
git switch -c seu-nome
```

Crie sua pasta na raiz e coloque nela `index.html`, `style.css` e uma pasta `assets/` para guardar sua própria foto. Use um caminho relativo como este no HTML:

```html
<img src="assets/minha-foto.jpg" alt="Descrição da sua foto">
```

Confira e envie somente sua pasta:

```bash
git status
git add seu-nome/
git commit -m "Adiciona página pessoal de Seu Nome"
git push -u origin seu-nome
```

Abra um Pull Request para `main` e peça a revisão de um colega. Não altere a pasta de outra pessoa nem envie alterações diretamente para `main`.
