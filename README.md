# cibersecurity-desafio-ransomware
Neste Repositorio estou criando um codigo em Pyton para o desafio de codigo do curso de cyber segurança
# Ransomware Simulation and Defense

Este projeto foi desenvolvido como parte do curso de Cibersegurança para demonstrar como funcionam ataques de ransomware em um ambiente controlado e seguro. **O objetivo é educar sobre as técnicas de mitigação e resposta a incidentes e NÃO criar ferramentas maliciosas.**

## 🚨 Aviso Legal

Este repositório é estritamente para fins educacionais e de pesquisa. **Não deve ser usado para atividades maliciosas.** Qualquer uso indevido é de inteira responsabilidade do usuário. Respeite as leis e políticas de segurança cibernética do seu país.

## 📋 Funcionalidades

- Simulação de um comportamento de ransomware em ambiente isolado.
- Ferramentas de mitigação e resposta a incidentes.
- Tutoriais para implementar medidas defensivas, como:
  - Backup regular de dados.
  - Monitoramento e detecção em tempo real.
  - Análise de tráfego de rede para identificar ransomware.

## 🛠️ Tecnologias Utilizadas

- **Python**: Para desenvolvimento do script de simulação.
- **Linux**: Ambiente seguro para testes.
- **Wireshark**: Análise de tráfego de rede.
- **Splunk/ELK Stack**: Monitoramento de logs.

## 🖥️ Requisitos

- Python 3.8 ou superior.
- Ambiente virtual isolado.
- Máquina virtual para testes (ex.: VirtualBox, VMware).

## 🚀 Como Usar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/Ransomware-Simulation-and-Defense.git
   cd Ransomware-Simulation-and-Defense

2. Configure o ambiente virtual:

bash
Copiar código
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
Execute o script de simulação:

bash
Copiar código
python simulate_ransomware.py
Siga o guia no diretório docs para implementar e testar medidas de defesa.

🛡️ Boas Práticas de Segurança
Sempre execute os scripts em uma máquina virtual isolada.
Não use dados reais durante os testes.
Monitore o tráfego de rede e logs para entender como as ameaças se propagam.
📂 Estrutura do Repositório
bash
Copiar código
Ransomware-Simulation-and-Defense/
│
├── simulate_ransomware.py      # Script de simulação
├── defense_tools.py            # Ferramentas de mitigação
├── requirements.txt            # Dependências do projeto
├── docs/                       # Tutoriais e documentação
├── tests/                      # Scripts de teste e validação
└── LICENSE                     # Licença do projeto
🤝 Contribuições
Contribuições são bem-vindas! Por favor, siga as diretrizes no arquivo CONTRIBUTING.md
