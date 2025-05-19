# Criação e Dimensionamento de Máquinas Virtuais

## Criar máquina virtual

1-Acesse o portal do Microsoft Azure.

2-Busque pelo serviço nomeado de “Máquinas virtuais”, que pode ser encontrado na página inicial ou no painel de serviços.

3-Selecione o botão “Criar” para abrir o menu de criação da máquina virtual.

#### Básico

4-Selecione uma assinatura.

5-Selecione um grupo de recursos.

6-Defina uma região.

7-Defina as opções de disponibilidade:
- Nenhuma redundância de infraestrutura necessária.
- Zonas de disponibilidade: permite escolher de uma a três zonas de disponibilidade para a VM.
- Conjunto de dimensionamento: permite adicionar a máquina virtual a um conjunto de máquinas virtuais de dimensionamento para o otimizar o balanceamento de carga e escalabilidade.
- Conjunto de disponibilidade: permite adicionar a máquina virtual a um conjunto de disponibilidade, que agrupa VMs de acordo com infraestrutura física (domínios de falha) ou instante de atualização em comum (domínio de atualização), para garantir maior disponibilidade.
  
8-Selecione o tipo de segurança.

9-Selecione a imagem.

10-Selecione a arquitetura da VM entre “Arm64” ou “x64”.

11-Selecione se quiser ou não executar com desconto de Spot do Azure, mas tenha cuidado com a necessidade de disponibilidade.

12-Selecione o tamanho.

13-Defina os detalhes da conta de administrador.

14-Defina as regras de porta de entrada.

#### Discos

15-Selecione o tamanho do disco do SO.

16-Selecione o tipo de disco de SO.

17-Deixe ativada a opção “Excluir com VM” para evitar discos órfãos.

#### Rede

18-Selecione uma rede virtual e, caso não apareça nenhuma opção, é necessário criar uma.

19-Defina um IP público.

20-Defina se deve existir ou não portas de entrada públicas. Caso positivo, selecione quais serão as portas de entrada públicas.

21-Marque a opção “Excluir o IP público e a NCI quando a VM for excluída”.

#### Gerenciamento

22-Caso necessário, habilite e configure o desligamento automático.

23-Caso necessário, habilite o backup.

#### Monitoramento

24-Caso necessário, habilite alertas.

25-Para reduzir o consumo, desabilite o “Diagnóstico de inicialização”.

#### Avançado

26-Opcionalmente, pode-se selecionar uma extensão para ser instalada na máquina virtual.

#### Marcas

27-Opcionalmente, é possível aplicar marcações às máquinas virtuais.

#### Revisar + criar

28-Visualize a previsão de custo dessa máquina virtual.

29-Se a previsão estiver de acordo com as suas necessidades, selecione o botão “Criar”.

## Criar conjunto de dimensionamento

1-Selecione uma assinatura.

2-Selecione um grupo de recursos.

3-Defina um nome.

4-Selecione uma região.

5-Defina de uma a três zonas de disponibilidade.

6-Escolha o modo de orquestração entre “flexível” ou “uniforme”.

7-Defina o tipo de segurança.

8-Selecione o modo de dimensionamento entre “Atualizar manualmente a capacidade”, “Dimensionamento automático” ou “Sem perfil de colocação em escala”.

9-Defina a contagem de instâncias.

10-Defina os detalhes das instâncias.

11-Configure a conta de administrador.

12-Selecione o botão “Revisar + criar”.



