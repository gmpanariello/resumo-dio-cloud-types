# Resumo DIO Cloud Types

Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do laboratório no módulo **"Tipos de Serviço de Nuvem"** da DIO.

O objetivo principal do módulo foi compreender os diferentes tipos de serviço de nuvem disponíveis no Azure — **IaaS**, **PaaS** e **SaaS** —, identificando suas características, responsabilidades e aplicações práticas para atender às necessidades de negócios de maneira eficiente. Abaixo está um resumo das minhas anotações, com base nas explicações da professora Valéria Baptista.

---

## Tipos de Serviço de Nuvem na Azure

### **IaaS (Infraestrutura como Serviço)**
- Tendem a ser recursos onde nós, como clientes, temos mais acesso à personalização, mas também maior responsabilidade.
- Envolve configurações detalhadas como assinatura, modelo de acesso, redes e backup.
- É necessário monitorar frequentemente, configurar backups e validar atualizações.
- Oferece uma infraestrutura de TI sob demanda, alugando servidores, máquinas virtuais, armazenamento, redes e sistemas operacionais.

### **PaaS (Plataforma como Serviço)**
- Um nível acima na hierarquia, oferecendo um ambiente para criação, teste e implantação de aplicativos.
- O cliente não gerencia mais o sistema operacional ou a infraestrutura subjacente.
- Ideal para quem deseja focar no desenvolvimento de aplicações e suas configurações específicas.
- Exemplos incluem serviços de banco de dados gerenciados e plataformas de desenvolvimento.

### **SaaS (Software como Serviço)**
- Aplicações prontas para uso, acessadas via Internet.
- Os usuários configuram os recursos disponíveis de acordo com suas necessidades e grupos de usuários.
- Exemplos incluem Microsoft Teams, Office 365, email e calendários.
- A responsabilidade do cliente se limita à configuração de acordo com as licenças adquiridas.

---

## Modelo de Responsabilidade Compartilhada

A responsabilidade na nuvem é dividida entre o provedor (Microsoft), o cliente e responsabilidades compartilhadas. Abaixo está a tabela que exemplifica como essas responsabilidades se distribuem:

| **Área**                     | **Microsoft**                         | **Compartilhada**                   | **Cliente**                           |
|-------------------------------|----------------------------------------|-------------------------------------|----------------------------------------|
| **Segurança Física**         | Totalmente gerenciada                 |                                     |                                        |
| **Segurança de Rede**        | Infraestrutura e proteção básicas     | Configuração de regras de acesso    | Configuração de redes privadas e VPNs |
| **Proteção de Dados**        | Ferramentas de criptografia fornecidas | Gerenciamento de chaves             | Configuração de permissões de acesso  |
| **Configuração do Sistema**  | Configuração inicial de sistemas       | Atualizações e ajustes avançados    | Personalização do sistema operacional |
| **Aplicações**               |                                        | Configuração inicial                | Gerenciamento completo e uso          |

---

## Comparação dos Serviços de Nuvem

| **Característica**          | **IaaS**                                      | **PaaS**                                 | **SaaS**                                 |
|-----------------------------|-----------------------------------------------|------------------------------------------|------------------------------------------|
| **Flexibilidade**           | Máxima flexibilidade no gerenciamento         | Divisão equilibrada de responsabilidades | Quase nenhuma responsabilidade técnica   |
| **Responsabilidade**        | Gerenciamento de hardware e software         | Foco em configurações de aplicações      | Uso e configurações de licenças          |
| **Exemplos**                | Máquinas Virtuais, Redes Virtuais             | Serviços de banco de dados gerenciados   | Microsoft Teams, Office 365              |

---

Este módulo foi essencial para ampliar minha compreensão sobre os tipos de serviços em nuvem, suas responsabilidades e aplicações práticas. Aprender sobre **IaaS**, **PaaS** e **SaaS** me ajudou a entender como escolher e implementar a solução mais adequada para diferentes cenários. Além disso, ao consolidar este aprendizado, refleti sobre como esses modelos podem facilitar a inovação tecnológica e agregar valor aos negócios, fortalecendo minha base para futuras implementações no mundo real.
