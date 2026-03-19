# CLAUDE.md

## Projeto
Site pessoal profissional de Josue Serafim em HTML/CSS/JS puro, hospedado no Hostinger (josueserafim.com.br).
Substitui o site antigo que era feito no Notion.

## Repositório GitHub
https://github.com/josueserafim/site-pessoal

## Stack
- HTML + CSS + JavaScript puro (sem frameworks)
- Sem dependências externas
- Compatível com hospedagem estática (Hostinger)

## Estrutura
```
index.html          # arquivo principal do site
images/
  ADS.png           # dashboard tráfego pago
  RH                # dashboard RH (PNG sem extensão)
  FINANCEIRO.png    # dashboard financeiro
  FATURAMENTO.png   # dashboard faturamento
  NPS.png           # dashboard NPS
  BOLSA_VALORES.png # dashboard bolsa de valores
```

## Funcionalidades implementadas
- Design dark/light mode (botão 🌙/☀️)
- Multilíngue PT/EN com detecção automática do idioma do navegador (bandeiras 🇧🇷🇺🇸)
- Preferência de idioma salva no localStorage
- Fundo animado no hero: rede de partículas interativa com o mouse
- Partículas adaptativas: 35 no mobile, 90 no desktop
- Botão flutuante de WhatsApp (+55 49 98436-7172)
- Responsivo: mobile, desktop e telas ultrawide (1400px+)
- 6 projetos Power BI com imagem e link público

## Seções do site
1. Hero (nome, cargo, partículas animadas)
2. Sobre (descrição + stats)
3. Habilidades (barras de progresso)
4. Experiência (timeline)
5. Projetos (6 cards com link Power BI)
6. Formação & Certificações
7. Contato (email, LinkedIn, telefone)

## Dados de contato
- Email: josue.serafim@gmail.com
- LinkedIn: linkedin.com/in/josue-serafim
- GitHub: github.com/josueserafim
- Tel: +55 49 98436-7172

## Git
- Branch principal: main
- Para commitar e fazer push após mudanças:
  ```bash
  git add index.html
  git commit -m "descrição da mudança"
  git push
  ```
