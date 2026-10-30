`Projeto_automa-o_abertura_chamados`

```markdown
# 🎫 Automação de Abertura de Chamados (GLPI x Zabbix)

Integração automatizada para monitoramento de infraestrutura e criação automática de tickets de suporte entre Zabbix e GLPI.

---

### 📌 Sobre o Projeto

O objetivo deste projeto é otimizar a operação de suporte e infraestrutura de TI. A automação captura alertas disparados pelo sistema de monitoramento **Zabbix** e realiza a abertura automática de incidentes/chamados na plataforma **GLPI** via API REST, reduzindo o tempo de resposta (MTTR) e eliminando falhas manuais.

### 🛠️ Tecnologias Utilizadas

- **Linguagens:** JavaScript / Node.js (ou Python)
- **APIs & Protocolos:** REST API / JSON-RPC
- **Plataformas de TI:** GLPI API & Zabbix API

---

### 📋 Funcionalidades

- 🔄 Escuta de alertas disparados por gatilhos (triggers) do Zabbix.
- 📝 Criação automática de chamados no GLPI com prioridade e categoria mapeadas.
- 🔄 Atualização de status e encerramento automático de tickets quando o problema é resolvido no Zabbix.
- 📜 Registro detalhado de logs de execução.

---
