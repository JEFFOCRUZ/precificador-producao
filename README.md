# Precificador de Produção 3D FDM

Projeto pronto para GitHub Pages ou Vercel.

- `index.html`: entrada única que abre o precificador completo.
- `profissional.html`: precificador completo com fluxo guiado em etapas, conferência obrigatória das dimensões da peça, custos de produção, multimaterial/AMS, depreciação, mão de obra, impostos, taxas, frete, simulador de quantidade e geração de orçamento profissional em PDF.
- O antigo modo simples foi removido para evitar cálculos incompletos e oferecer um único fluxo de precificação.

O PDF usa jsPDF via CDN. Se a biblioteca externa estiver indisponível, o sistema oferece a impressão nativa do navegador como alternativa para salvar em PDF.
