# Maratona-Bot

Bot de automação com infraestrutura de perfil personalizado para interações técnicas de alto nível com o Claude.

## Estrutura

```
Maratona-Bot/
├── CLAUDE.md              # Perfil do usuário e diretrizes de interação para o Claude
└── profile/
    └── ivo_profile.json   # Configuração estruturada do perfil (consumível por código)
```

## Uso

O `CLAUDE.md` é lido automaticamente pelo Claude Code ao iniciar sessões no repositório, calibrando o nível e o estilo das respostas com base no perfil técnico do usuário.

O `profile/ivo_profile.json` pode ser consumido programaticamente para personalizar prompts, filtrar respostas ou construir contexto dinâmico em integrações com a API do Claude.
