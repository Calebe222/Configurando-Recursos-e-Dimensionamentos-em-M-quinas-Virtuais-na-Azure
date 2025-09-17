# 🖥️ Computação e Rede no Azure

Resumo do bootcamp abordando a criação e configuração de **Máquinas Virtuais (VMs)** e aspectos de **rede e gerenciamento** no Microsoft Azure.

## 🚀 Criação da Máquina Virtual

- **Opções Iniciais**  
  - É possível criar uma VM com **configuração pré-definida** para **ambiente de teste** ou **produção**.  
  - Para produção, a configuração já vem ajustada automaticamente.

- **Criação Manual**  
  - **Assinatura** e **Grupo de Recursos**: selecione conforme seu ambiente.  
  - **Nome da VM** e **Região**: a região vem padrão, mas pode ser alterada.  
  - **Zonas de Disponibilidade**: neste exemplo, sem redundância.  
  - **Dimensionamento**: selecionado como **automático**.
  - **Credenciais**: defina nome de usuário e senha/padrão de autenticação.  
  - **Portas**: mantidas como padrão.

## 💽 Configuração de Disco

- Recomenda-se **marcar a opção de excluir discos junto com a VM** ao apagá-la, evitando **discos órfãos**.

## 🌐 Rede

- Rede padrão utilizada durante a criação.  
- **Boa prática:** excluir a **NIC (interface de rede)** e o **IP público** quando a VM for removida.

## 🧰 Gerenciamento

- **Desligamento Automático**: pode ser configurado para economizar custos.  
- **Backup**: habilitar se necessário para proteção dos dados.  
- **Monitoramento**: permite acompanhar **métricas**, **alertas** e **diagnósticos** da VM.

## 👥 Área de Trabalho e Colaboração

- É possível criar uma **área de trabalho** para que outro colaborador acesse.  
- O usuário pode fazer login com a **conta Microsoft** e configurar o ambiente conforme suas necessidades.

## 🎯 Conclusão

- O Azure facilita a criação de VMs com configurações padrão ou manuais.  
- Boas práticas como desligamento automático, monitoramento e exclusão de recursos associados evitam **custos desnecessários** e garantem melhor **gestão de infraestrutura**.
