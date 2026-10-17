# Mapa Doc — prova técnica

Indexa volumes de processo em PDF (com texto ou digitalizados) direto no navegador e gera
`indice.md` (mapa para a IA), `indice.xlsx` e um pacote `.zip` com o texto de cada página.
Nenhum arquivo sai do computador de quem usa.

Acesse: https://laercio10rosa.github.io/mapa-doc/

## O que esta versão faz

- Páginas com texto (ex.: SEI) são lidas direto; páginas digitalizadas passam por OCR em português
  no recorte dos 40% de cima (como na skill), a 150 DPI.
- Regras da skill `indexador-pdf-processo` identificam o tipo de documento e onde cada um começa.
- Páginas sem identificação viram "Sem identificação" com a ação **revisar**.
- Sem IA, sem servidor.
