# DIO-Bradesco-Azure-Criando-VM
# Resumo do Lab: Criando uma Máquina Virtual na Azure

Neste lab, aprendi o processo completo de criação de uma máquina virtual (VM) no Microsoft Azure. Abaixo está o passo a passo resumido:

## Passo 1: Acessar o Portal Azure
- Entrar no portal Azure (https://portal.azure.com)
- Fazer login com as credenciais da conta

## Passo 2: Iniciar o Processo de Criação
- Clicar em "Criar um recurso"
- Selecionar "Máquina Virtual" na seção Computação

## Passo 3: Configurar os Detalhes Básicos
- Selecionar a assinatura adequada
- Criar ou selecionar um Grupo de Recursos
- Definir:
  - Nome da VM
  - Região (localização do datacenter)
  - Opções de disponibilidade (se necessário)
  - Imagem do sistema operacional (Windows Server ou Linux)

## Passo 4: Configurar Tamanho da VM
- Escolher o tamanho adequado (CPU, memória, desempenho)
- Verificar os custos estimados

## Passo 5: Configurar Conta de Administrador
- Definir nome de usuário e senha (para Windows)
- Para Linux: configurar autenticação SSH (chave pública ou senha)

## Passo 6: Configurar Regras de Portas de Entrada
- Selecionar portas abertas (RDP para Windows, SSH para Linux)
- Configurar grupos de segurança de rede (NSG)

## Passo 7: Configurar Discos
- Selecionar tipo de disco (SSD Premium, Standard HDD, etc.)
- Configurar tamanho do disco do SO
- Adicionar discos de dados se necessário

## Passo 8: Revisar e Criar
- Revisar todas as configurações
- Clicar em "Criar" para iniciar a implantação
- Aguardar a conclusão do processo (normalmente alguns minutos)

## Gerenciamento Pós-Criação
- Conectar à VM via RDP ou SSH
- Monitorar desempenho e custos no portal
- Configurar backups e atualizações conforme necessário

## Lições Aprendidas
- A importância de escolher a região correta para reduzir latência
- Como dimensionar adequadamente os recursos para otimizar custos
- Noções básicas de segurança na nuvem (NSGs, autenticação)
- Flexibilidade do ambiente cloud para escalar recursos conforme necessidade
