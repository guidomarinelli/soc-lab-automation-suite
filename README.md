# soc-lab-automation-suite
A collection of Bash scripts to automate the setup, hardening, and configuration of a complete SOC lab environment.

> ⚠️ **Disclaimer:** Questi script modificano configurazioni di sistema e installano software di sicurezza. Si consiglia di eseguirli in ambienti di laboratorio o su macchine virtuali dedicate.

---

## 📂 Struttura del Progetto

Il progetto è strutturato in modo modulare per configurare i diversi componenti dell'infrastruttura SOC:

*   `setup-workstation-analyst.sh` - Configura la macchina dell'analista (Tool di analisi rete, forensics, terminale ottimizzato).
*   *`setup-server-siem.sh` (In arrivo)* - Configurazione del server SIEM centralizzato.
*   *`setup-server-collector.sh` (In arrivo)* - Configurazione dei nodi di raccolta log.

---

## 💻 1. Setup Workstation Analista

Lo script `setup-workstation-analyst.sh` prepara l'ambiente di lavoro ideale per un Blue Team Analyst, installando utility di sistema e tool di analisi.

### 🛠️ Prerequisiti
*   Sistema Operativo: [Es. Ubuntu 24.04 LTS / Debian 12]
*   Privilegi di `root` o accesso `sudo`.
*   Connessione a internet attiva.

### 🚀 Come Usarlo

Clona il repository ed esegui lo script con i privilegi di amministratore:

```bash
# Clona il repository
git clone [https://github.com/](https://github.com/)[Tuo-Username]/soc-bootstrap.git

# Entra nella cartella
cd soc-bootstrap

# Rendi lo script eseguibile
chmod +x setup-workstation-analyst.sh

# Esegui il setup
sudo ./setup-workstation-analyst.sh
