# Prisma Engenharia & Projetos

Projeto demonstrativo de escritório de engenharia criado para portfólio, com layout lateral, composição diagonal, páginas estáticas pré-renderizadas, SEO por rota e publicação no GitHub Pages.

## Identidade

- azul-petróleo, areia, verde técnico e cobre;
- navegação lateral no desktop e menu tradicional no celular;
- hero assimétrico com composição diagonal;
- serviços apresentados como trilha técnica;
- galeria de projetos em blocos de diferentes proporções;
- equipe, artigos e páginas internas completas;
- imagens reais de arquitetura, obras e profissionais;
- modo demonstração com `noindex, nofollow`;
- auditoria automática do build;
- botão flutuante de WhatsApp.

## Executar localmente

```bash
npm ci
npm run build
```

Os arquivos finais são gerados em `dist/`.

## Publicação

O workflow `.github/workflows/deploy-pages.yml` publica exclusivamente a pasta `dist` no GitHub Pages.

O GitHub Pages está configurado para usar **GitHub Actions**. Este commit dispara a primeira publicação oficial do projeto.

URL esperada:

`https://ricardoribeiro-prof.github.io/prisma-engenharia-projetos/`

## Aviso

Empresa, profissionais, projetos, registros e contatos são fictícios. Antes de uso real, substitua os dados demonstrativos e revise a política de privacidade.
