# Skill Agêntica

Skill reutilizável para planejar, documentar, desenvolver, validar, entregar e manter projetos de qualquer tipo, com fluxo adaptável ao contexto.

## Sobre

`project-template-pt` é uma Skill independente e genérica para Claude. Ela orienta o agente a entender o projeto existente antes de agir e a adaptar o trabalho ao objetivo, aos usuários, às restrições, ao ambiente e aos critérios de sucesso reais.

O fluxo cobre descoberta, planejamento, documentação, arquitetura e design, implementação, validação, conformidade, entrega e manutenção. Não presume linguagem, framework, domínio, arquitetura ou estrutura de projeto.

## Princípios

- Inspecionar o projeto e os artefatos existentes antes de perguntar ou alterar.
- Separar fatos confirmados, inferências e pendências, marcando estas últimas com `[CONFIRMAR]`.
- Preservar o trabalho existente e pedir aprovação para ações de alto impacto ou irreversíveis.
- Criar documentação proporcional, critérios verificáveis e evidências de validação.
- Avaliar segurança, privacidade, legislação, normas, licenças e direitos autorais conforme o contexto.
- Confirmar legislação em Diários Oficiais ou gazetas oficiais e verificar alterações e vigência em fontes oficiais.
- Evitar copiar código ou ativos visuais de terceiros sem autorização e licença compatível.
- Comunicar-se com o usuário em português brasileiro; produzir artefatos no idioma do projeto.

## Estrutura

```text
project-template-pt/
├── LICENSE
├── README.md
├── SKILL.md
├── references/
│   ├── architecture-and-design.md
│   ├── compliance-and-standards.md
│   ├── delivery-and-maintenance.md
│   ├── documentation-and-adr.md
│   ├── implementation-standards.md
│   ├── licensing-and-copyright.md
│   ├── privacy-and-personal-data.md
│   ├── project-discovery.md
│   ├── quality-and-validation.md
│   ├── requirements-and-planning.md
│   └── security-and-risk.md
└── templates/
    ├── adr.md
    ├── project-brief.md
    └── task-plan.md
```

## Uso

1. Disponibilize a pasta `project-template-pt` no local de Skills suportado pela sua instalação do Claude.
2. Acione a Skill ao iniciar ou alterar um projeto, ou quando uma tarefa envolver várias etapas do ciclo de vida.
3. A Skill principal direciona o agente às referências relevantes. Os modelos são opcionais e devem ser adaptados ao projeto.

Consulte a documentação da sua versão do Claude para os detalhes de instalação e ativação de Skills.

## Escopo e limites

Esta Skill fornece um fluxo de trabalho, não uma garantia de conformidade legal, certificação, segurança ou qualidade. A aplicabilidade de leis e normas depende do contexto; decisões jurídicas ou regulatórias relevantes podem exigir revisão profissional. A Skill não define a licença do projeto: essa escolha cabe ao titular dos direitos.

## Licença deste repositório

Este repositório está sob a licença MIT. Consulte o arquivo [`LICENSE`](LICENSE), que identifica Ítalo de Souza Ortiz como titular e inclui seu perfil no [GitHub](https://github.com/italo-ortiz). A licença permite uso, modificação e redistribuição, desde que o aviso de copyright e o texto da licença acompanhem cópias ou partes substanciais do material.
