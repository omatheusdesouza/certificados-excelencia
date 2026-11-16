# Certificados – Excelência Educação

Site de consulta de certificados. A pessoa escolhe o curso, digita nome e sobrenome, vê o certificado e baixa o PDF.

- `index.html`: página de consulta. `cursos.json` lista os cursos; cada curso tem a sua pasta em `cursos/`.
- `admin.html`: painel da equipe (protegido por senha). Sobe os PDFs emitidos pelo sistema credenciado e publica o site.
- `vendor/`: leitor de PDF (pdf.js, licença Apache-2.0) e fontes (Liberation Sans, licença OFL) usados na prévia.

Os nomes dos participantes não ficam em texto legível (`cursos/*/participantes.json`) e os PDFs ficam cifrados
(`cursos/*/pdfs/*.bin`): só quem digita o nome e o sobrenome corretos consegue abrir o certificado.
