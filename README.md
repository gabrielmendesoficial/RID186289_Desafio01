# 🏗️ Projeto Escola DNC - Desafio01 - Engenharia de Software

Projeto Solicitado no Modulo 1 do desafio da Escola DNC, onde realizei uma pagina inicial para uma instuição imaginaria de arquitetura.

Link do dataset de dados do formulario: https://docs.google.com/spreadsheets/d/1EzVdt9OQ1bCAaChK4_XfiwWVlca8HLzi_qqlms_xq44/edit?usp=sharing

Link do Projeto Publicado: https://splendorous-narwhal-636b69.netlify.app/

---

## 📌 Objetivos e Funcionabilidades

- Apresentar informações institucionais de forma clara e elegante
- Mostre a experiência da empresa (número de empreendimentos, área construída, anos de atuação)
- Reforce a identidade visual baseada em layout no Figma
- Possua formulário funcional integrado ao Google Sheets via [SheetMonkey](https://sheetmonkey.io)
- Possui tambem uma versão publicada usando [Netlify](https://www.netlify.com/)

---

## 🧩 Tecnologias Utilizadas

- HTML5
- CSS3
- SheetMonkey (para envio de formulários para o Google Sheets)
- Figma (para design base)

---

## 📬 Integração com SheetMonkey

O formulário HTML envia os dados para uma planilha via SheetMonkey:

```html
<form action="https://api.sheetmonkey.io/form/uWmoVEJvtw1tfjSStbbWyF" method="POST">
    <input type="text" name="Name" placeholder="Nome" required><br>
    <input type="email" name="Email" placeholder="Email" required><br>
    <input type="hidden" name="Created" value="x-sheetmonkey-current-date-time" />
    <button type="submit">Fale Conosco</button>
</form>
```
