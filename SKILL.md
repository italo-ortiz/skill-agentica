---
name: project-template-pt
description: Fluxo adaptável para descobrir, planejar, documentar, desenvolver, validar, entregar e manter projetos de qualquer tipo. Use ao iniciar ou alterar um projeto ou quando uma tarefa abranger várias etapas.
---

# Template de Projeto

Use esta Skill como um método de trabalho flexível, não como uma stack ou estrutura de pastas predefinida. Ela se aplica a software, sites, aplicações, automações, documentação, design, pesquisa e outros tipos de projeto. O resultado pode ser código, documento, artefato de design, processo ou uma combinação.

## Comunicação

- Comunique-se com este usuário em português brasileiro, inclusive durante o trabalho e nos resumos de conclusão. Escreva os artefatos do projeto no idioma e segundo as convenções estabelecidas para ele.
- Separe fatos confirmados, inferências e informações pendentes. Marque suposições incertas ou informações essenciais desconhecidas como `[CONFIRMAR]`.
- Faça uma pergunta de esclarecimento por vez, somente quando um dado essencial não puder ser descoberto com segurança e sua ausência impedir uma decisão adequada. Inspecione primeiro; não pergunte o que pode ser descoberto.
- Nunca afirme que uma ação, teste, aprovação ou resultado ocorreu sem evidências.

## Fluxo de trabalho

1. **Descobrir:** inspecione arquivos relevantes, estado do repositório e versionamento, ambiente, artefatos e documentação existentes, dependências, ferramentas disponíveis e decisões anteriores. Identifique tipo de projeto, objetivo, público/usuários, escopo, restrições, contexto de uso, ferramentas e medidas de sucesso a partir das evidências. Resuma fatos confirmados, inferências, itens `[CONFIRMAR]`, riscos e incógnitas.
2. **Definir:** alinhe o escopo da tarefa e critérios de aceitação observáveis. Identifique artefatos afetados e dependências. Para mudanças relevantes, avalie estado de versionamento, compatibilidade e impacto antes de editar.
3. **Planejar proporcionalmente:** escolha apenas o planejamento e a documentação necessários para o projeto e a tarefa. Selecione as referências relevantes abaixo; ignore as que não se aplicam. Ao avaliar legislação, confirme a publicação na edição pertinente do Diário Oficial ou gazeta oficial da jurisdição e verifique alterações e vigência em fontes oficiais. Torne decisões importantes explícitas e registre decisões arquiteturais ou de processo significativas como ADRs, quando útil.
4. **Agir:** selecione ferramentas, tecnologias, dependências e convenções com base no contexto real. Prefira abordagens simples, nativas e já estabelecidas quando forem adequadas. Verifique licenças e procedência de materiais de terceiros; quando houver distribuição, confirme também a licença do próprio projeto e a presença do arquivo aprovado no pacote final. Explique a complexidade adicional. Preserve o trabalho existente e faça mudanças focadas e reversíveis.
5. **Validar:** verifique cada critério de aceitação por um método adequado. Diferencie concluído, parcialmente concluído, bloqueado e não executado. Registre evidências e limitações; nunca sugira que uma verificação não feita foi aprovada.
6. **Manter alinhado e entregar:** atualize a documentação pertinente quando requisitos, decisões, arquitetura, design, interfaces, processos ou escopo mudarem. Resuma alterações, artefatos afetados, decisões, evidências de validação, limitações e próximos passos.

## Autonomia e preservação

- Execute autonomamente tarefas pequenas, reversíveis e bem delimitadas dentro do pedido do usuário.
- Peça aprovação antes de decisões de alto impacto, mudanças arquiteturais, alterações destrutivas ou irreversíveis, custos relevantes, transmissão externa, publicação ou implantação, salvo quando o usuário já tiver autorizado aquela ação específica.
- Inspecione conteúdo, referências, dependências e impactos antes de substituir, excluir, renomear, mover ou migrar qualquer item. Não sobrescreva o trabalho do usuário nem crie registros duplicados sem necessidade justificada.
- Não presuma que MCPs, conectores, contas, permissões ou ferramentas estejam disponíveis. Verifique antes de depender deles; quando possível, ofereça uma alternativa manual prática.

## Documentação e rastreabilidade

Crie documentação no local já estabelecido pelo projeto. Evite burocracia e fontes de verdade duplicadas. Conforme o escopo real, use um resumo conciso, requisitos, notas de arquitetura/design, plano de implementação, registro de validação, guia de operação/manutenção ou ADRs. Omita seções e documentos de áreas inexistentes ou sem evidência. Quando aplicável, mantenha vínculos entre objetivos ou requisitos, decisões, especificações/design, implementação e evidências.

## Referências

Leia somente o que a tarefa exigir:

- `references/project-discovery.md` — inspeção inicial e registro de incertezas.
- `references/requirements-and-planning.md` — escopo, prioridades, critérios e planejamento.
- `references/documentation-and-adr.md` — documentação proporcional e decisões.
- `references/architecture-and-design.md` — escolhas técnicas e de design baseadas no contexto.
- `references/implementation-standards.md` — mudanças seguras e sustentáveis em diferentes tipos de artefato.
- `references/quality-and-validation.md` — verificações adequadas e evidências.
- `references/security-and-risk.md` — avaliação de risco conforme o contexto.
- `references/compliance-and-standards.md` — legislação, normas técnicas e obrigações aplicáveis.
- `references/privacy-and-personal-data.md` — privacidade, dados pessoais e transferências internacionais.
- `references/licensing-and-copyright.md` — licenças, direitos autorais e procedência de código e conteúdo.
- `references/delivery-and-maintenance.md` — entrega e manutenção contínua.
- `templates/` — modelos opcionais; copie e adapte somente quando forem úteis.
