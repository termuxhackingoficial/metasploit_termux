# Metasploit Framework 6 no Termux
[![Status de teste do GitLab](https://gitlab.com/gushmazuko/metasploit_in_termux/badges/master/pipeline.svg)](https://gitlab.com/gushmazuko/metasploit_in_termux/-/pipelines) ![Estrelas do repositório do GitHub](https://img.shields.io/github/stars/gushmazuko/metasploit_in_termux?style=social) [![](https://img.shields.io/badge/GitLab-Mirror-succes?link=https://gitlab.com/gushmazuko/metasploit_in_termux)](https://gitlab.com/gushmazuko/metasploit_in_termux)

![Metasploit 6 em execução](https://i.imgur.com/yLFQhvP.png)

## Como Instalar
## Antes

Para ter o Termux atualizado:
- **Limpe todos os dados** do Termux nas Configurações do Android
- Desinstale e reinstale a versão mais recente do Termux a partir do [F-Droid](https://f-droid.org/en/packages/com.termux/) (A versão na Play Store está desatualizada)
- Então inicie o Termux para inicialização, feche-o (forçar parada, não trocar)
- Reabra e siga as instruções abaixo

### Automático
```bash
source <(curl -fsSL https://kutt.it/msf)
```

### Manual
```bash
pkg install wget

wget https://github.com/gushmazuko/metasploit_in_termux/raw/master/metasploit.sh

chmod +x metasploit.sh

./metasploit.sh
```

## Iniciar o metasploit
Após a instalação, inicie o Metasploit usando o comando:
```bash
msfconsole
```
