# Instituto Junges Carvalho — Landing Page

Landing page institucional para o Instituto Junges Carvalho, clínica de emagrecimento médico com protocolos injetáveis de alta performance.

## Tecnologias

- HTML5 semântico
- [Tailwind CSS](https://tailwindcss.com/) via CDN
- Google Fonts (Inter)
- SVGs inline para ícones e logotipo

## Estrutura

```
landing-page/
├── index.html      # Página principal (single-page)
└── assets/         # Imagens de casos antes/depois
```

## Seções

1. **Hero** — headline de quebra de objeção + CTA principal
2. **Diferencial médico** — nota do especialista e diferenciais
3. **Casos de sucesso** — cards antes/depois com depoimentos
4. **Protocolo** — 3 passos do método
5. **CTA final** — agendamento via WhatsApp
6. **Rodapé** — registro médico e conformidade CFM/LGPD

## Como visualizar

Abra `index.html` diretamente no navegador — não requer build ou servidor.

## Observações

- Design responsivo (mobile-first), dark theme com acento dourado
- CTA fixo no rodapé em dispositivos móveis
- Imagens de casos devem ser adicionadas em `assets/` com nomes `case1-antes.jpg`, `case1-depois.jpg`, etc.
- CRM e RQE do médico precisam ser preenchidos antes de publicar
