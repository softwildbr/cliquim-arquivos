# Instruções para agentes — cliquim-arquivos

**Escopo:** gerenciador de arquivos Android, repositório público. Este arquivo acrescenta orientações de trabalho; não aprova funcionalidades, publicação nem mudança de identidade.

## Ler antes de modificar
1. [README.md](README.md), documentação e decisões locais; lá está o **estado técnico canônico**, que deve ser verificado contra branches, PRs, releases e evidências.
2. [Diretrizes transversais](https://github.com/studiocliquim-max/github-governance/blob/main/docs/GITHUB_GUIDELINES.md), [regras para agentes](https://github.com/studiocliquim-max/github-governance/blob/main/docs/AGENT_RULES.md) e [handoff geral](https://github.com/studiocliquim-max/github-governance/blob/main/docs/HANDOFF.md) (acesso privado quando aplicável).
3. Issues, Pull Requests, branches e workflows relevantes antes de decidir alterar código.

## Cuidados deste projeto
ATENÇÃO: o repositório é público. Não publicar credenciais, relatórios internos, dados de usuários ou ativos restritos. Rever termos de licença antes de divulgar como open source e preservar operações SAF seguras.

## Contribuintes externos

Este repositório é **público**, mas o manual empresarial `github-governance` é privado e só fica acessível a integrantes autorizados. Para contribuições externas, as instruções deste arquivo, do README e do template de Pull Request são autossuficientes; não publicar detalhes internos nem usar documentação privada como pré-requisito obrigatório.

## Protocolo de mudança
- Tratar hipótese, proposta, código implementado, compilação, teste e lançamento como estados diferentes.
- Para alterações de produto, preferir Issue → branch de trabalho → Pull Request → build/teste pertinente → revisão. Não mesclar alterações críticas sem autorização; não assumir que `main` corresponde à última candidata de desenvolvimento.
- Não apagar branches, reescrever histórico, trocar licença/visibilidade, criar gastos, acessar segredos ou redistribuir material de terceiros sem autorização específica.
- Após cada trabalho registrar: objetivo, arquivos, commits/PR, testes executados ou não, riscos e próxima ação. Não afirmar resultado que não foi verificado.
