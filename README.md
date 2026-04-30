# A.S.A Serviços

Site institucional da **A.S.A Serviços LTDA** — prestadora de serviços industriais com atuação no Polo de Camaçari/BA, focada em manutenção de tanques e caldeiras, montagem de andaimes, pintura e jateamento industrial, içamento de cargas e limpeza técnica industrial.

- **CNPJ:** 60.762.687/0001-24
- **Endereço:** Loteamento Poloplast, Galpão 01, Camaçari/BA, CEP 42.801-589
- **Telefone:** (71) 3627-6849
- **E-mail:** fiscal@renovacaoconsultoria.com.br
- **Setores:** Óleo & Gás, Petroquímica, Construção e Indústria Pesada

## Como rodar localmente

O site é estático (HTML/CSS/JS puro, sem build). Basta servir a pasta:

```bash
# qualquer servidor estático funciona
npx serve .
# ou
python -m http.server 8000
```

Em seguida abra `http://localhost:3000` (ou `:8000`).

## Estrutura

```
asa-servicos/
├── index.html       # Página única com todo o conteúdo, CSS e JS inline
├── imgs/            # Logo, favicon e fotos
└── README.md
```

## TODO

- [ ] Substituir as fotos da seção Aplicações (5 cards) por fotos reais das operações da A.S.A — atualmente usando imagens genéricas industriais do Unsplash
- [ ] Substituir as fotos das seções "O Problema" e "Especificações Técnicas" por imagens reais da operação
- [ ] Substituir o background do hero por foto real de operação no Polo de Camaçari
- [ ] Configurar domínio próprio (apontar DNS para o GitHub Pages ou hospedagem escolhida)
