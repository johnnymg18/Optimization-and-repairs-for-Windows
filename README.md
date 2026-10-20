Aqui está uma versão resumida, formatada em Markdown, pronta para você copiar e colar no `README.md` do seu repositório no GitHub:

---

## 🚀 Funcionalidades

### 🛡️ Elevação de Privilégios

* Detecta permissões de execução e solicita acesso como **Administrador** automaticamente via PowerShell.

### 🧹 Limpeza e Otimização de Discos

* **Arquivos Temporários:** Limpa pastas `Temp` do usuário e do sistema.
* **Caches do Sistema:** Esvazia os caches do **Prefetch** e do **Windows Update** (`SoftwareDistribution`).
* **Arquivos de Log:** Remove registros antigos (`*.log`) do disco principal.
* **Desempenho de Energia:** Ativa o plano de **Alto Desempenho**.
* **Otimização de Armazenamento:** Aplica comando **TRIM** para SSDs ou desfragmentação para HDDs.

### 🌐 Rede e Compartilhamento (Impressoras)

* **Limpeza de Cache DNS:** Executa `flushdns` e renovação dos registros de rede.
* **Reset de Protocolos:** Redefine o catálogo **Winsock** e a pilha **TCP/IP**.
* **Correção de Impressoras em Rede:** Injeta regras de registro para solucionar os erros **0x0000011b** (PrintNightmare) e **0x00000709**.
* **Firewall do Windows:** Libera a *Descoberta de Rede* e o *Compartilhamento de Arquivos/Impressoras*.
* **Serviços de Rede:** Força a inicialização automática de serviços essenciais de conectividade (`FDResPub`, `fdPHost`, `lanmanworkstation`, `lanmanserver`).

### 🛠️ Sistema, Reparos e Atualizações

* **DISM:** Repara a imagem base do Windows (`/restorehealth`).
* **SFC:** Rastreia e corrige arquivos do sistema corrompidos (`/scannow`).
* **Limpeza de Componentes:** Executa limpeza na pasta `WinSxS` para liberar espaço em disco.
* **Atualização de Programas:** Atualiza todos os softwares instalados em lote usando o **Winget**, aceitando os termos de licença de forma automatizada.
