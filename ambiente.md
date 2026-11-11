# Configuração do Ambiente de Laboratório

## 1. Objetivo

Documentar a estrutura do ambiente virtual utilizado nos experimentos de cibersegurança, garantindo que os testes sejam realizados de forma controlada e isolada.

## 2. Ferramentas e tecnologias

| Ferramenta | Finalidade |
|---|---|
| Oracle VirtualBox | Virtualização das máquinas |
| Kali Linux | Ambiente de testes de segurança |
| Metasploitable 2 | Sistema intencionalmente vulnerável |
| DVWA | Aplicação web vulnerável para estudos |
| Medusa | Ferramenta de auditoria de autenticação |

## 3. Arquitetura do laboratório

O laboratório utiliza máquinas virtuais configuradas em uma rede Host-only, permitindo a comunicação entre os ambientes virtuais para a realização dos experimentos.

## 4. Máquinas virtuais

### Kali Linux
- Função: máquina utilizada para os testes de segurança.
- Sistema operacional: Kali Linux.
- Endereço IP: [Preencher após conferência].

### Metasploitable 2
- Função: máquina vulnerável utilizada como alvo dos experimentos.
- Sistema operacional: Linux.
- Endereço IP: [Preencher após conferência].

### DVWA
- Função: aplicação web vulnerável utilizada nos testes de autenticação.
- Hospedagem: [Informar onde foi instalada].

## 5. Isolamento e segurança

Os experimentos são realizados em ambiente de laboratório controlado, sem autorização para testar sistemas externos.

## 6. Evidências

As capturas de tela da configuração das máquinas e da rede serão armazenadas na pasta `images/` deste repositório.
