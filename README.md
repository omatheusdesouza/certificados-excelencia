# Certificados – Excelência Educação

Site de consulta de certificados.

- `index.html`: página de consulta. `cursos.json` lista os cursos; cada curso tem a sua pasta em `cursos/`.
  Cursos em PDF: entra com a senha, filtra a lista pelo nome, vê o certificado e baixa o PDF.
- `admin.html`: painel da equipe (protegido por senha). Sobe os PDFs emitidos pelo sistema credenciado e publica o site.
- `vendor/`: leitor de PDF (pdf.js, licença Apache-2.0) e fontes (Liberation Sans, licença OFL) usados na prévia.

Nos cursos em PDF, a lista de nomes (`cursos/*/lista.json`) e os PDFs (`cursos/*/pdfs/*.bin`) ficam cifrados:
sem a senha do site não há nomes nem certificados legíveis.
