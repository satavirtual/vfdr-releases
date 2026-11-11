# vFDR — SATA Virtual

**vFDR (Virtual Flight Data Recorder)** é a aplicação de voo da SATA Virtual:
acompanha o teu voo no **MSFS 2024** ou **X-Plane**, envia posições e PIREPs à
companhia e mostra tudo num painel web em tempo real.

> Este repositório contém **apenas as distribuições** (binários e notas de versão).

## Downloads

Última versão: **5.2.0** (2026-11-11) — [notas da versão](https://github.com/satavirtual/vfdr-releases/releases/tag/5.2.0).
Todas as versões estão em [**Releases**](../../releases).

| SO | Ficheiro | Como instalar |
|---|---|---|
| Windows 10/11 (x64) | [`vfdr-next-5.2.0.0-windows-x64.msi`](https://github.com/satavirtual/vfdr-releases/releases/download/5.2.0/vfdr-next-5.2.0.0-windows-x64.msi) | Duplo clique no MSI. Instala **por utilizador** (sem administrador), com menu e atalho; instalar por cima faz upgrade. |
| macOS (Intel / Apple Silicon) | *segue em breve* | |
| Linux | *segue em breve* | |

Cada instalador traz o `.sha256` correspondente na mesma página. Os manuais
(`MANUAL.md` / `MANUAL.pdf` em português, `MANUAL.en.md` / `MANUAL.en.pdf` em inglês, em Markdown e em PDF) e o `CHANGELOG.md` também
estão anexos a cada versão.

## Requisitos

- **Windows 10/11 (x64)**, **macOS** (Intel ou Apple Silicon) ou **Linux** (x64).
- **Não é preciso instalar Java**: o instalador já traz o seu próprio runtime.
- **MSFS 2024** (Windows): ligação via FSUIPC, ou via SimConnect (experimental),
  com o módulo MobiFlight opcional para variáveis extra — ou **X-Plane** (qualquer SO).
- Em **macOS** e **Linux** só o conector **X-Plane** está disponível; as métricas
  que o simulador não fornece aparecem como `—`.
- Também funciona em modo offline, sem simulador ligado.

## Atualizações

O vFDR não avisa por si quando existe uma versão nova: consulta esta página (ou a
lista de [**Releases**](../../releases)) de vez em quando. Instalar uma versão nova
por cima da anterior atualiza-a; as tuas configurações e dados são mantidos.

## Instalação e dados

Cada instalador cria o menu e o atalho do vFDR; o painel abre em
`http://localhost:8080`. As configurações e os dados ficam em:

- Windows: `%LOCALAPPDATA%\vFDR-NEXT`
- macOS / Linux: `~/.local/share/vFDR-NEXT`

Desinstalar não apaga esta pasta.

---

*Esta página é gerada automaticamente a partir da versão 5.2.0.0.*
