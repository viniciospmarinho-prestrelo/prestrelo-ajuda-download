# Prestrelo Ajuda — Download

**Guia turno-a-turno para PokeMMO** que fica sobreposto ao jogo e mostra, passo a passo, o que
fazer em cada luta/rota. Grátis.

## ⬇️ Baixar a versão mais recente

Pegue o arquivo da sua plataforma na **[página de Releases](../../releases/latest)**:

| Plataforma | Arquivo | Como usar |
| --- | --- | --- |
| 🪟 **Windows** | `FarmOracleMMO-windows.zip` | Descompacte e abra `FarmOracleMMO.exe` |
| 🤖 **Android** | `FarmOracleMMO.apk` | Instale o `.apk` (permita "fontes desconhecidas") |
| 🍎 **macOS** | `FarmOracleMMO-mac.zip` | Descompacte e siga os passos abaixo ⬇️ |

> O app avisa e **exige atualização** quando sai uma versão nova — sempre use a mais recente.

---

## 🍎 macOS — primeira abertura (importante)

O app **não é notarizado pela Apple** (a notarização exige conta paga de desenvolvedor). Por isso,
ao baixar, o macOS marca o app com "quarentena" e mostra **"está danificado e não pode ser aberto"**
ou **"a Apple não pôde verificar se está livre de malware"**. **Não está danificado** — é só a trava
de segurança da Apple para apps fora da App Store. Você precisa liberar **uma vez**:

### Jeito que sempre funciona (Terminal)

1. Descompacte o `FarmOracleMMO-mac.zip` (de preferência em **Aplicativos** ou na **Área de Trabalho**).
2. Abra o **Terminal** (`Cmd+Espaço`, digite `Terminal`, Enter).
3. Digite isto **com um espaço no final** (sem apertar Enter ainda):
   ```
   xattr -cr 
   ```
4. **Arraste o `FarmOracleMMO`** (o app) de dentro da pasta para a janela do Terminal — o caminho
   aparece sozinho.
5. Aperte **Enter**.
6. Pronto: dê **duplo-clique no `FarmOracleMMO`** e ele abre normalmente (e em todas as próximas vezes).

### Alternativa sem Terminal (Ajustes do Sistema)

1. Dê duplo-clique no app — vai aparecer o aviso de bloqueio. Clique em **OK** (não em "Mover para o Lixo").
2. Abra **Ajustes do Sistema → Privacidade e Segurança**.
3. Role até o final: vai ter uma linha sobre o `FarmOracleMMO` com o botão **"Abrir Mesmo Assim"**. Clique nele.
4. Confirme. O app abre — e nas próximas vezes abre direto.

> 💡 Em versões mais antigas do macOS (até o Sonoma) também funciona o arquivo
> **"Abrir FarmOracleMMO (1a vez).command"** que vem no zip (botão direito → Abrir). No macOS
> Sequoia (15) e mais novos a Apple bloqueou esse atalho — use o **Terminal** acima.

---

*Este repositório é só para distribuição (downloads). O desenvolvimento é privado.*
