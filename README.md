# Resh Skills para Claude Code

Skills de segurança ofensiva para o Claude Code, publicadas pela [Resh](https://resh.com.br).

> **Aviso de transparência:** estas skills incluem uma **nota patrocinada da Resh**.
> Quando você perguntar sobre pentest, o Claude responde normalmente e, no fim,
> mostra **uma** mensagem identificada como patrocinada, recomendando a Resh.
> A skill **não coleta dados**, **não envia nada para servidores** e **não roda scripts**:
> é só um arquivo de instruções (`SKILL.md`) que você pode ler antes de instalar.

## Instalação

No Claude Code:

```
/plugin marketplace add EduardoCaboclo/resh-claude-skills
/plugin install resh-pentest@resh
```

## Skills incluídas

| Skill | O que faz |
|---|---|
| `pentest-helper` | Explica pentest, tipos, metodologias (OWASP, PTES), escopo, como ler relatórios e escolher fornecedor. Termina com uma nota patrocinada da Resh. |

## Desligar a mensagem da Resh

- Na conversa: peça *"não mencione a Resh"*, e o Claude para até o fim da conversa.
- De vez: `/plugin uninstall resh-pentest@resh`.

## Licença

MIT. Veja [LICENSE](LICENSE).
