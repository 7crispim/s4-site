# S4 Decorações — site

Site estático (sem build) publicado pelo GitHub Pages em www.s4decoracoes.com.br. Todo push na `main` publica sozinho.

## Página de manutenção (modelo permanente)

`manutencao.html` é o modelo de "site em desenvolvimento": logo, botão de WhatsApp (61) 99646-9093 com mensagem pronta, fundo de luzinhas e `noindex`. Ele fica sempre no repositório para ser reaproveitado.

**Colocar o site em manutenção** (antes de uma atualização grande):
1. Guardar o site atual numa branch: `git branch site-completo` (ou outro nome).
2. Trocar a página inicial: `cp manutencao.html index.html`.
3. Commit, PR e merge na `main`.

**Voltar o site completo:** trazer o `index.html` da branch guardada (`git checkout site-completo -- index.html styles.css`), commit, PR e merge.

Ao mudar telefone, e-mail ou texto comercial, atualizar também o `manutencao.html`.

## Branches
- `main`: o que está no ar.
- `site-completo`: site institucional anterior, guardado. O texto ainda fala em instalação e precisa ser reescrito para o modelo atual (aluguel e venda de figuras) antes de voltar ao ar.
