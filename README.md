# Trofy Updates

## Português (pt-BR)

Repositório público dedicado exclusivamente a hospedar o manifesto de atualização (`Trofy-update.json`) e os artefatos de release sob demanda (`Trofy.exfat`) para o aplicativo **Trofy** (`PPSA09111`) no PS5.

### Finalidade e privacidade

- **Entrega apenas sob demanda:** o cliente de atualização do Trofy consulta este repositório via HTTPS apenas quando o usuário solicita a verificação/download (ou tem a checagem inicial habilitada nas preferências).
- **Sem dados pessoais ou credenciais:** este repositório contém somente o manifesto JSON e os binários públicos de release. Não inclui e-mails pessoais, tokens, chaves privadas, dados de console ou credenciais de nenhum tipo.
- **Integridade:** cada release lista o tamanho exato e o hash `SHA-256` do arquivo `Trofy.exfat`, verificados localmente pelo Trofy antes de qualquer substituição em `/data/homebrew/`.

### Release de teste atual (`v0.3.46`)

- **Manifesto:** `Trofy-update.json` (esquema `1`, versão de teste `0.3.46`, publicado em `2026-11-25T16:25:00Z`).
- **Conteúdo entregue:** imagem oficial pública `v0.3.42` (`Trofy.exfat`, `134217728` bytes, SHA-256 `67fcf31f85ff28e234a8dff8056aac9fd4d17bad8a3597ce33cc4666aed9c7fe`) para validação ponta a ponta do fluxo de atualização sob demanda.

---

## English (en)

Public repository dedicated exclusively to serving on-demand update manifests (`Trofy-update.json`) and release assets (`Trofy.exfat`) for the **Trofy** PS5 application (`PPSA09111`).

### Purpose and privacy

- **On-demand delivery only:** Trofy's updater fetches manifests and release assets from this repository over HTTPS only when initiated or enabled by the user.
- **No personal email or credentials:** this repository hosts only public release manifests and release binaries. It contains no personal email addresses, tokens, private keys, user data, or credentials.
- **Integrity verification:** every release declares exact byte `size` and `sha256` values for `Trofy.exfat`, validated locally by Trofy before applying any update in `/data/homebrew/`.

### Current test release (`v0.3.46`)

- **Manifest:** `Trofy-update.json` (schema `1`, test version `0.3.46`, published `2026-11-25T16:25:00Z`).
- **Delivered asset:** official public `v0.3.42` `Trofy.exfat` image (`134217728` bytes, SHA-256 `67fcf31f85ff28e234a8dff8056aac9fd4d17bad8a3597ce33cc4666aed9c7fe`) for end-to-end on-demand updater verification.
