# 🚀 Laboratório Azure: Criação de Máquina Virtual na Nuvem

![Azure Virtual Machine](https://img.shields.io/badge/Microsoft_Azure-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white)

Este repositório documenta meu aprendizado prático na criação e configuração de uma Máquina Virtual (VM) no Microsoft Azure, aplicando conceitos fundamentais de computação em nuvem.

## 📋 Sumário

- [Objetivos](#🎯-objetivos)
- [Configuração da VM](#🖥️-configuração-da-vm)
- [Conceitos Fundamentais](#🧠-conceitos-fundamentais)
- [Lições Aprendidas](#💡-lições-aprendidas)
- [Próximos Passos](#🔜-próximos-passos)
- [Referências](#📚-referências)

## 🎯 Objetivos

✔ Criar uma VM seguindo melhores práticas do Azure  
✔ Explorar conceitos como SLA e Alta Disponibilidade  
✔ Documentar o processo para futuras consultas  
✔ Compartilhar conhecimento com a comunidade  

## 🖥️ Configuração da VM

### Especificações Técnicas

| Componente           | Configuração Escolhida           |
|----------------------|----------------------------------|
| **Sistema Operacional** | Ubuntu Server 20.04 LTS         |
| **Tamanho**          | Standard B1s (1 vCPU, 1GB RAM)  |
| **Região**           | Brazil South                    |
| **Armazenamento**    | SSD Premium (LRS)               |
| **Autenticação**     | Chave SSH                       |

### Passo a Passo

1. **Criação no Portal Azure**
   - Naveguei para "Máquinas Virtuais" → "Adicionar"
   - Selecionei a imagem do Ubuntu Server
   - Configurei rede e segurança

2. **Conectividade**
   ```bash
   ssh -i ~/.ssh/azure_key.pem azureuser@<IP-PUBLICO>
