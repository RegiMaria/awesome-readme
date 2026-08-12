<p align="center">
  <a href="#">
    <img src= "https://github.com/user-attachments/assets/1bfcb50d-47d8-4452-a02b-b267ed42b139" width="60" alt="AWS" />
  </a>
  &nbsp;&nbsp;
  <a href="#">
    <img src="https://cdn.simpleicons.org/databricks/FF3621" width="60" alt="Databricks" />
  </a>
  &nbsp;&nbsp;
  <a href="#">
    <img src= "https://github.com/user-attachments/assets/2c5878c3-a282-4ade-b265-1b36ff85eb60"
 width="100" alt="Azure" />
  </a>
  &nbsp;&nbsp;
  <a href="#">
    <img src="https://cdn.simpleicons.org/googlecloud/4285F4" width="40" alt="Google Cloud" />
  </a>
</p>

<h1 align="center">🎨 Guia de Ícones para README</h1>

<p align="center">
  <b>Como usar ícones de marcas e tecnologias no seu README</b>
</p>

---

## <img src="https://cdn.simpleicons.org/googlelens/4285F4" width="22"/> De onde vêm os ícones

Você não precisa desenhar nem fazer upload de nada. Os ícones vem do banco de imagens `icon-guide` aqui no repositório.

Como é tudo baseado em links públicos (a imagem já está hospedada nos servidores do GitHub via user-attachments, e o ícone do Databricks vem do simpleicons, que é público),
qualquer aluna pode:

Copiar o código de dentro do bloco de exemplo (ex: o do "AWS")
Colar direto no README.md do repositório dela
Funciona sem precisar trocar nada, porque o link da imagem não é "seu", é um link compartilhado que qualquer pessoa pode usar

A única coisa que vocês vão querer trocar é o texto "Título do seu projeto aqui" pelo nome do projeto delas, o resto (imagem, tamanho, alinhamento) já vem pronto.

---

## <img src="https://cdn.simpleicons.org/target/FF3621" width="22"/> Ícone no topo do README

Ótimo pra mostrar múltiplas plataformas, certificações ou tecnologias logo de cara — como fizemos no README do Databricks Lakehouse (AWS + Databricks + Azure + GCP).

## Títulos

### Databricks

Código: 
```
<p align="center">
  <img src="https://github.com/user-attachments/assets/2aba3fcf-da06-4f5c-99c3-83ff2fa455a1"
       alt="Databricks Lakehouse"
       width="200">
</p>

<h1 align="center">Título do seu projeto aqui </h1>

```` 

Como vai ficar:
<p align="center">
  <img src="https://github.com/user-attachments/assets/2aba3fcf-da06-4f5c-99c3-83ff2fa455a1"
       alt="Databricks Lakehouse"
       width="200">
</p>

<h1 align="center">Título do seu projeto aqui </h1>



- `width="60"` é um bom tamanho pra ícone de destaque no topo (nem muito grande, nem some)
- O `&nbsp;&nbsp;` cria um espacinho entre um ícone e outro — sem isso eles ficam grudados
- Envolver com `<a href="...">` é opcional, mas deixa o ícone clicável (por exemplo, linkando pra uma credencial ou certificado)

---

## <img src="https://cdn.simpleicons.org/databricks/FF3621" width="22"/> Ícone como marcador de tópico

O truque que usamos direto no `##` — o ícone fica "grudado" no título, como se fosse um marcador personalizado.

```markdown
## <img src="https://cdn.simpleicons.org/databricks/FF3621" width="20"/> Arquitetura
```

- `width="20"` (bem pequeno) é o segredo — em torno de `18` a `24` fica proporcional ao tamanho do texto de um `##`
- **Não** coloque `height` junto — deixa o ícone esticar/achatar se a proporção original não for quadrada
- Funciona em `#`, `##` e `###`, mas em títulos menores (`####` pra baixo) o ícone fica desproporcionalmente grande - melhor não usar

---

## <img src="https://cdn.simpleicons.org/shieldsdotio/000000" width="22"/> Ícone "solto" vs. ícone dentro de badge

São dois efeitos visuais bem diferentes:

| Estilo | Como fica | Código |
|---|---|---|
| **Solto** (só o símbolo) | <img src="https://cdn.simpleicons.org/python/3776AB" width="30"/> | `<img src="https://cdn.simpleicons.org/python/3776AB" width="30"/>` |
| **Dentro de badge** (símbolo + texto + fundo colorido) | <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" /> | `<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />` |

Use o **solto** quando quiser algo discreto (marcador de título, rodapé). Use o **badge** quando quiser destaque, tipo lista de skills ou stack de tecnologias.


---


## <img src="https://cdn.simpleicons.org/googlelens/4285F4" width="22"/> De onde vêm os ícones

Você não precisa desenhar nem fazer upload de nada - existem "bancos de ícones" gratuitos que já têm o logo de milhares de marcas e tecnologias prontos, servidos direto por um link. É só montar a URL certa.

| Serviço | Pra que serve | Como usar |
|---|---|---|
| **[simpleicons.org](https://simpleicons.org)** | Ícone "puro" de qualquer marca (só o símbolo, sem fundo) | `https://cdn.simpleicons.org/NOME-DA-MARCA/COR` |
| **[skillicons.dev](https://skillicons.dev)** | Grade de vários ícones de tecnologia juntos, de uma vez | `https://skillicons.dev/icons?i=js,react,python` |
| **[shields.io](https://shields.io)** | Badge (etiqueta colorida) com ícone + texto dentro | `https://img.shields.io/badge/texto-COR?logo=NOME&logoColor=branco` |
| **[devicon.dev](https://devicon.dev)** | Ícones de linguagens/frameworks, com versão colorida "oficial" pronta | Precisa copiar a tag `<i>` do site, ou usar o link SVG direto |

> 💡 Dica: pra achar o "nome oficial" de uma marca (o que vai no lugar de `NOME-DA-MARCA`), procure ela em [simpleicons.org](https://simpleicons.org) -
>  o nome que aparece na busca é exatamente o que você usa na URL.





---

## <img src="https://cdn.simpleicons.org/googlecloud/4285F4" width="22"/> Grade de várias tecnologias juntas

Quando você quer mostrar 5, 10, 15 tecnologias de uma vez, montar badge por badge é trabalhoso - o `skillicons.dev` resolve isso com uma única linha:

```html
<img src="https://skillicons.dev/icons?i=aws,azure,gcp,python,react,git" />
```

- Cada tecnologia é separada por vírgula, sem espaço
- Pra ver a lista completa de nomes disponíveis, é só visitar [skillicons.dev](https://skillicons.dev) e clicar em cima do ícone desejado - ele copia o nome certo pra você
- Tem parâmetro `&theme=dark` ou `&theme=light` pra combinar com o fundo do seu README

---

## <img src="https://cdn.simpleicons.org/checkmarx/FF3621" width="22"/> Ícone + link, em lista ou tabela

Padrão que usamos nas seções de certificação (AWS, Octodex) — o ícone vira um link clicável, geralmente com uma legenda embaixo.

```html
<p align="center">
  <a href="https://exemplo.com/credencial">
    <img src="https://cdn.simpleicons.org/databricks/FF3621" width="60" alt="Databricks" />
  </a>
</p>
<p align="center"><sub>Databricks Certified</sub></p>
```

---

## Erros comuns

- **Nome errado do ícone** → o nome é o "oficial" da marca no simpleicons.org, não um apelido. `aws` sozinho não funciona — o nome certo é `amazonaws`. Sempre confira no site antes de montar a URL.
- **Cor sem o `#`** → em `cdn.simpleicons.org`, a cor vai **sem** o `#` (`FF3621`, não `#FF3621`). Em CSS normal seria com `#`, mas aqui não.
- **Ícone gigante quebrando o título** → esquecer o `width` faz o ícone aparecer no tamanho original (às vezes gigante), estourando a altura da linha do título. Sempre defina um `width` pequeno (18-24) em ícones de marcador.
- **`height` + `width` juntos** → definir os dois força uma proporção que pode não ser a original da imagem, distorcendo o ícone. Normalmente só um dos dois é necessário.
- **Ícone de marca registrada em conteúdo comercial** → simpleicons e skillicons são bancos de **logos oficiais de marcas** — tudo bem usar pra indicar "eu trabalho com essa tecnologia/certificação", mas não sirva pra criar a impressão de vínculo oficial com a empresa que não existe.

---

<p align="center"><sub>Feito com 💛 — parte do catálogo <a href="https://github.com/RegiMaria/awesome-readme">awesome-readme</a></sub></p>
