# gerador-fichas

Gera e baixa a planilha de importação de fichas tempo do AdvWin+ a partir das fichas encerradas no Cronômetro de Horas, para quem abre o cronômetro sem login no claude.ai.

Publicado pelo GitHub Pages em https://jocaplg.github.io/gerador-fichas/.

As fichas chegam no fragmento do link (`#v1=...`), que o navegador não envia ao servidor. A página lê as fichas, apaga o fragmento do endereço, monta a planilha no próprio navegador e baixa. O modelo embutido não tem nenhuma lista do escritório (clientes, pastas, pessoas, setores ou unidades).

O código-fonte e as instruções de atualização ficam no repositório privado `jocaplg/claude-advwin`, pasta `gerador/`.
