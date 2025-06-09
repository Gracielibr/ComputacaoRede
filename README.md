# Configurando Recursos e Dimensionamento em Máquinas Virtuais no Azure  

Este repositório contém informações e exemplos sobre como configurar e dimensionar Máquinas Virtuais (VMs) no Microsoft Azure, garantindo desempenho, escalabilidade e custo-eficiência.  

## Tópicos Abordados  

**Criação e Configuração de VMs**  
   - Seleção de sistema operacional (Windows/Linux)  
   - Escolha do tamanho da VM (séries B, D, F, etc.)  
   - Configuração de discos (SSD Premium, Standard HDD)  
   - Rede virtual (VNet), IPs e Network Security Groups (NSG)  

**Dimensionamento (Scaling)**  
   - **Vertical (Scale Up/Down)**: Aumentar/reduzir recursos da VM (CPU, RAM)  
   - **Horizontal (Scale Out/In)**: Adicionar/remover instâncias com **VM Scale Sets (VMSS)**  

**Autoscaling**  
   - Configuração baseada em métricas (CPU, memória, tráfego)  
   - Escalonamento programado (horários de pico)  

**Monitoramento e Otimização**  
   - Uso do **Azure Monitor** para métricas e alertas  
   - Recomendações do **Azure Advisor** para redução de custos  
   - Utilização de **Spot VMs** para workloads temporários  
