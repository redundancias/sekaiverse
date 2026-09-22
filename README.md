# 🌸 Sekaiverse

Central de downloads oficiais **fora da Play Store** para os apps Android da suíte: **Doramaya**, **Yomu Manga** e **SekaiAnimes**.

Se você não pode ou não quer instalar pela Play Store, os APKs assinados oficialmente ficam disponíveis aqui, sempre atualizados conforme novas versões saem.

> ⚠️ Estes apps só são distribuídos oficialmente **pela Play Store e por este repositório**. Desconfie de qualquer outro site oferecendo os mesmos apps.

---

## 📦 Apps

| App | Descrição | Versão atual | Android mínimo | Download |
|---|---|:---:|:---:|:---:|
| 🎭 **Doramaya** | Streaming de doramas (novelas asiáticas) | `1.17` | 8.0+ | [⬇️ Baixar APK](https://github.com/redundancias/sekaiverse/releases/download/doramaya-v1.17/Doramaya-v1.17.apk) |
| 📖 **Yomu Manga** | Leitor de mangás com tradução automática | `1.24` | 8.0+ | [⬇️ Baixar APK](https://github.com/redundancias/sekaiverse/releases/download/yomumanga-v1.24/YomuManga-v1.24.apk) |
| ⛩️ **SekaiAnimes** | Streaming de animes | `4.35` | 6.0+ | [⬇️ Baixar APK](https://github.com/redundancias/sekaiverse/releases/download/sekaianimes-v4.35/SekaiAnimes-v4.35.apk) |

Todas as versões publicadas (inclusive antigas) ficam listadas em **[Releases](https://github.com/redundancias/sekaiverse/releases)**.

---

## 📲 Como instalar

1. Baixe o APK do app desejado na tabela acima (ou na aba [Releases](https://github.com/redundancias/sekaiverse/releases)).
2. Se o Android bloquear a instalação, vá em **Ajustes → Segurança → Instalar apps desconhecidos** e libere para o navegador/gerenciador de arquivos que você usou pra baixar.
3. Abra o arquivo `.apk` baixado e confirme a instalação.

Se você já tinha o app instalado pela Play Store, **não precisa desinstalar** — os APKs aqui são assinados com a mesma chave, então a atualização acontece por cima normalmente, sem perder dados.

### 🔐 Verificando a autenticidade

Todos os APKs deste repositório são assinados com a mesma chave oficial. Se quiser conferir antes de instalar:

```
SHA-256: EA:A9:E1:EA:9D:74:3A:57:7E:3B:DE:BF:08:08:31:CB:8F:36:1D:D8:32:EF:62:00:BC:2D:8D:B5:65:C4:AF:33
```

Isso pode ser conferido com `apksigner verify --print-certs` ou qualquer verificador de assinatura de APK.

---

## 🔄 Como isso é mantido

Este repositório é atualizado **manualmente a cada novo lançamento** de qualquer um dos três apps — a tabela acima e a aba Releases sempre refletem a versão mais recente já publicada. Não há nenhuma automação de build aqui: cada nova versão é compilada, assinada e publicada como uma [Release](https://github.com/redundancias/sekaiverse/releases) própria, identificada por uma tag no formato `<app>-v<versão>` (ex.: `doramaya-v1.14`).

Changelog de cada versão fica na descrição da respectiva Release.

---

## ❓ Dúvidas frequentes

**Por que baixar por aqui em vez da Play Store?**
Alternativa pra quem não tem acesso à Play Store, quer uma versão específica mais antiga, ou prefere instalar diretamente.

**É seguro?**
Sim — mesmo build, mesma assinatura, mesmo código que vai pra Play Store. Nada é modificado entre uma distribuição e outra.

**Achei um bug ou tenho uma sugestão.**
Abra uma [issue](https://github.com/redundancias/sekaiverse/issues) neste repositório, especificando qual app.

---

<sub>Sekaiverse não é afiliado a nenhum serviço de streaming ou leitura de conteúdo de terceiros — os apps aqui listados são desenvolvidos de forma independente.</sub>
