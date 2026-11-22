# Barista em Casa — Escola do Barista

Curso online de barista para iniciantes, com foco em métodos manuais para fazer em casa. Criado por **Marcelo Oliveira** (Bilu Coffee / Escola do Barista, Santo André - SP).

## O que tem no curso

- Página de apresentação do curso (grade, público, instrutor, galeria, FAQ)
- 9 módulos (8 obrigatórios + bônus de espresso) e 30 aulas curtas, com fotos reais da escola
- Teste ao final de cada módulo (75% para concluir)
- Ferramentas: calculadora de receita, timer guiado de preparo, diagnóstico da xícara e glossário
- Materiais para download: apostila, livro de receitas, roda de aromas e fichas para imprimir
- Certificado em português ou inglês, gerado ao concluir o curso
- Progresso salvo no navegador do aluno

## Como abrir

Abra o arquivo `index.html` em qualquer navegador. Não precisa instalar nada.

Com o GitHub Pages ativado, o curso fica disponível em:
https://celoma-maker.github.io/Curso-de-Barista/

## Estrutura

- `index.html`: o curso completo (conteúdo, ferramentas e certificado)
- `materiais/`: PDFs liberados para os alunos
- `img/`: fotos da Escola do Barista e do Bilu Coffee, já otimizadas para a web

## Como adicionar os vídeos das aulas

No `index.html`, procure a aula pelo `id` (por exemplo `id:"4-2"`) e cole o link do vídeo no campo `video:""`:

```js
{ id:"4-2", title:"Hario V60", min:10, video:"https://youtu.be/SEU-VIDEO", ... }
```

## Vídeos dentro do site

Vídeos curtos (até ~25 MB) podem ficar na pasta `videos/` e ser ligados à aula com `video:"videos/nome.mp4"`: o player aparece dentro da aula. Para vídeos longos, prefira YouTube (não listado) ou Vimeo e cole o link.

## Contato

- WhatsApp: (11) 99562-9279
- E-mail: marcelo@bilucoffee.com.br
- Site: [escoladobarista.com.br](https://www.escoladobarista.com.br)
- Instagram: [@escoladobarista](https://www.instagram.com/escoladobarista) · [@bilucoffeeandcake](https://www.instagram.com/bilucoffeeandcake)
