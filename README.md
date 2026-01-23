# Projeto Prático de Redes de Computadores – NEWBYTE

[![Cisco Packet Tracer](https://img.shields.io/badge/Simulado%20em-Cisco%20Packet%20Tracer-blue?logo=cisco)](https://www.netacad.com/pt-br/courses/packet-tracer)
[![IFBA](https://img.shields.io/badge/IFBA%20-%20Campus%20Brumado-orange)](https://portal.ifba.edu.br/brumado)

Este repositório contém o desenvolvimento completo do projeto prático da disciplina **Redes de Computadores** (3ª unidade), realizado no **Instituto Federal de Educação, Ciência e Tecnologia da Bahia (IFBA) – Campus Brumado**, no curso **Técnico em Informática Integrado**.

O projeto foi inteiramente simulado no **Cisco Packet Tracer**, respeitando rigorosamente o plano de endereçamento IP definido pelo professor orientador.

## Instituição

- **Instituto**: Instituto Federal de Educação, Ciência e Tecnologia da Bahia (IFBA)  
- **Campus**: Brumado  
- **Curso**: Técnico de Nível Médio em Informática  

## Desenvolvedores

- Állison Teixeira da Silva  
- Cláudio Kauê Ribeiro Oliveira  
- Gabriel Messias Gomes Bomfim  

## Orientação

Professor **Marcos Santos**

## Sobre o Projeto

O projeto simula a infraestrutura de rede de uma empresa fictícia chamada **NEWBYTE**, com filiais distribuídas em diferentes estados do Brasil. A proposta foi construir uma topologia corporativa realista, garantindo comunicação eficiente entre redes internas (LAN) e externas (WAN), além da implementação de serviços essenciais.

A topologia representa um cenário próximo ao de uma organização geograficamente distribuída, aplicando boas práticas de endereçamento, roteamento e segurança básica.

## Objetivo Geral

Implementar uma topologia de rede corporativa funcional no Cisco Packet Tracer, utilizando majoritariamente a interface de linha de comando (**CLI**), conforme o plano de endereçamento fornecido.

## Objetivos Específicos

- Construir a topologia representando a empresa **NEWBYTE**  
- Implementar redes locais (**LAN**) e enlaces WAN  
- Configurar roteamento dinâmico com **RIP versão 2**  
- Definir rota estática para acesso à rede externa (provedor de internet)  
- Garantir comunicação total entre todas as redes internas e externas  
- Configurar serviços de rede: **DHCP**, **DNS**, **HTTP** e **Telnet**  
- Aplicar configurações básicas de segurança nos roteadores  
- Realizar testes completos de conectividade e validação dos serviços  

## Descrição da Topologia

A empresa **NEWBYTE** possui quatro filiais:

| Filial          | Estado | Rede Interna (LAN)     | Rede Externa (WAN)    |
|-----------------|--------|-------------------------|------------------------|
| Bahia           | BA     | 192.168.x.0/24         | 200.200.x.0/30        |
| Rio de Janeiro  | RJ     | 192.168.x.0/24         | 200.200.x.0/30        |
| São Paulo       | SP     | 192.168.x.0/24         | 200.200.x.0/30        |
| Pernambuco      | PE     | 192.168.x.0/24         | 200.200.x.0/30        |

Cada filial possui sua rede local conectada a um roteador, que gerencia a comunicação WAN entre as unidades. A separação clara entre endereços privados (192.168.x.0/24) e públicos simulados (200.200.x.0/30) facilita o roteamento e reflete ambientes corporativos reais.

*(Em breve adicionarei aqui a imagem da topologia completa simulada no Packet Tracer)*

## Tecnologias e Conceitos Utilizados

- Cisco Packet Tracer  
- Roteamento dinâmico (**RIP v2**)  
- Roteamento estático  
- **DHCP** (atribuição automática de endereços)  
- **DNS** (resolução de nomes centralizada)  
- **HTTP** (servidor web institucional)  
- **Telnet** (acesso remoto)  
- Endereçamento IP hierárquico  
- Configuração via **CLI**  
- Segurança básica (senhas, banners de aviso)  

## Funcionalidades Implementadas

- Comunicação plena entre todas as filiais  
- Acesso à rede externa (simulada)  
- Distribuição automática de IPs via DHCP  
- Resolução de nomes com servidor DNS central  
- Acesso à página web institucional da empresa  
- Gerenciamento remoto dos roteadores via Telnet  
- Proteção mínima dos dispositivos (senhas criptografadas e banners)  

## Testes Realizados

Foram executados testes abrangentes de conectividade com o comando **ping** (intra-rede e inter-rede), além da validação completa dos serviços DHCP, DNS, HTTP e Telnet. Todos os resultados foram satisfatórios, comprovando o funcionamento correto da topologia.

## Como Visualizar / Executar o Projeto

1. Instale o **Cisco Packet Tracer** (disponível gratuitamente no site da Cisco Networking Academy).  
2. Clone este repositório:  
   ```bash
   git clone https://github.com/SEU-USUARIO/newbyte-rede-corporativa.git
