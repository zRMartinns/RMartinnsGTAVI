# RMartinns — Desbloqueie seu próximo UX Designer

Protótipo estático em português, sem instalação de dependências ou processo de build.

## Executar

Abra `index.html` no navegador. Para servir por HTTP, abra um terminal nesta pasta e execute:

```powershell
python -m http.server 8080
```

Acesse http://localhost:8080. Encerre com Ctrl+C. Também funciona em qualquer hospedagem estática; publique todo o conteúdo desta pasta.

## Links de contato

Os links do LinkedIn, Behance e WhatsApp estão configurados em `config.js`. Para alterá-los, edite os campos `linkedinUrl`, `behanceUrl` e `contactUrl`.

## Experiência

Ao abrir o site, o logo animado aparece antes da Home, com opção para pular; em `prefers-reduced-motion`, a introdução é ignorada. O site mantém duas telas de conteúdo: Home e ficha do personagem. O botão “Desbloquear personagem” inicia uma transição de aproximadamente 1,45 segundo diretamente para a ficha; “Voltar ao início” retorna à Home. A ficha usa o personagem original, o monograma e o conector SVG.

Tipografia Barlow Condensed / DM Sans via Google Fonts, com fontes locais de fallback. O restante funciona sem internet. Paleta inspirada no visual de GTA VI: noite violeta #160d29, rosa #ff7eb6, azul #8edbf5, pêssego #ffbd85 e roxo #9d75db. Os valores são uma interpretação visual, não uma especificação oficial. Referência: https://www.rockstargames.com/VI. Não usa logos ou recursos de GTA/Rockstar.

## Conteúdo e acessibilidade

As habilidades vieram do texto da conversa, não de currículo verificado. Revise-as em `index.html` antes da publicação. Nenhuma nota numérica, experiência profissional ou resultado foi inventado.

Idioma pt-BR, HTML semântico, foco visível e movido entre telas, navegação por teclado, link para pular conteúdo e suporte a `prefers-reduced-motion`. As habilidades são etiquetas decorativas com ícones e conectores, sem alegações adicionais de proficiência.

## Conferência manual

- Testar o desbloqueio e verificar que a ficha aparece sem uma tela intermediária.
- Conferir o logo animado na abertura, “Pular introdução” e a preferência por movimento reduzido.
- Conferir a ficha em desktop e mobile e navegar com Tab e Enter.
- Conferir LinkedIn, Behance e Contato.
- Testar “Voltar ao início” e o fluxo de desbloqueio novamente.
- Ativar movimento reduzido no sistema e repetir o fluxo.

Não há coleta de dados, analytics, backend ou armazenamento local.
