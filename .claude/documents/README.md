# Documents - Documentação do Projeto

Esta pasta contém a documentação técnica do projeto e **DEVE ser commitada** no repositório.

## Estrutura

```
documents/
├── adrs/       # Architecture Decision Records
├── specs/      # Especificações de features
└── irs/        # Implementation Records
    ├── backend/
    ├── frontend/
    ├── devops/
    └── [setor]/
```

## Tipos de Documentos

### ADR (Architecture Decision Record)
- **Quando**: Antes de decisões arquiteturais
- **Formato**: `{PROJETO}-ADR-{NUM}-{slug}.md`

### Spec (Especificação)
- **Quando**: Antes de implementar features
- **Formato**: `{PROJETO}-SPEC-{NUM}-{slug}.md`

### IR (Implementation Record)
- **Quando**: Após implementações
- **Formato**: `{PROJETO}-IR-{NUM}-{slug}.md`

## Importante

- ✅ Esta pasta é **COMMITADA** no repositório
- ✅ Documentos pertencem ao **PROJETO**, não ao core
- ⚠️ O restante de `.claude/` é **IGNORADO** pelo git

---

*Ecossistema Claude Agents v1.1.4*
