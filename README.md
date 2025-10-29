# sql-create-view-video
🧠 CREATE VIEW no SQL Server — Entenda de forma simples!  🎥 Assista ao vídeo completo no YouTube: "https://youtu.be/NKFiytIR-Ps" 📌 o que é a VIEW, 💻 o código SQL usado, 🎥 o link do vídeo no YouTube, e 🔍 uma breve explicação didática.
CREATE VIEW vwProdutos AS
SELECT
    ProductName AS 'Nome do Produto',
    ColorName AS 'Cor',
    UnitPrice AS 'Preço',
    UnitCost AS 'Custo'
FROM
    DimProduct;

-- Visualizar os dados da view criada
SELECT * FROM vwProdutos;
