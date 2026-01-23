Projeto Prático de Redes de Computadores – NEWBYTE

Este repositório contém o desenvolvimento de um projeto prático da disciplina Redes de Computadores, realizado no Instituto Federal de Educação, Ciência e Tecnologia da Bahia (IFBA), como parte da avaliação da terceira unidade do curso Técnico em Informática Integrado.

O projeto foi desenvolvido utilizando o software Cisco Packet Tracer, com foco na aplicação prática dos conceitos fundamentais de redes de computadores, respeitando o plano de endereçamento IP previamente definido pelo docente responsável.

Instituição

Instituto Federal de Educação, Ciência e Tecnologia da Bahia
Campus Brumado
Curso Técnico de Nível Médio em Informática

Desenvolvedores

Állison Teixeira da Silva

Cláudio Kauê Ribeiro Oliveira

Gabriel Messias Gomes Bomfim

Orientação

Professor Marcos Santos

Sobre o Projeto

O projeto simula a infraestrutura de rede de uma empresa fictícia denominada NEWBYTE, composta por filiais localizadas em diferentes estados do Brasil. A proposta consiste na construção de uma topologia de rede corporativa capaz de garantir comunicação eficiente entre redes internas e externas, além da implementação de serviços essenciais de rede.

A topologia foi planejada de forma a representar um cenário próximo ao ambiente real de uma organização distribuída geograficamente, utilizando boas práticas de endereçamento, roteamento e segurança.

Objetivo Geral

Implementar uma topologia de rede corporativa funcional no Cisco Packet Tracer, utilizando majoritariamente a interface de linha de comando (CLI), de acordo com o plano de endereçamento fornecido.

Objetivos Específicos

Construir uma topologia de rede representando a empresa fictícia NEWBYTE

Implementar redes locais (LAN) e redes externas (WAN)

Configurar roteamento dinâmico utilizando RIP versão 2

Implementar rota estática para acesso à rede externa (provedor de internet)

Garantir comunicação entre todas as redes internas e externas

Configurar serviços de rede como DHCP, DNS, HTTP e Telnet

Aplicar configurações básicas de segurança nos roteadores

Realizar testes de conectividade e validação dos serviços configurados

Descrição da Topologia

A topologia da empresa NEWBYTE é composta por quatro filiais:

Bahia (BA)

Rio de Janeiro (RJ)

São Paulo (SP)

Pernambuco (PE)

Cada filial possui sua própria rede local (LAN), conectada a um roteador responsável pela comunicação entre as unidades por meio de enlaces WAN. As redes internas utilizam endereços IP privados da faixa 192.168.x.0/24, enquanto as redes externas utilizam endereços da faixa 200.200.x.0/30.

Essa separação entre redes internas e externas permite melhor organização lógica, facilita o roteamento e simula um ambiente corporativo realista.

Tecnologias e Conceitos Utilizados

Cisco Packet Tracer

Roteamento dinâmico (RIP v2)

Roteamento estático

DHCP (Dynamic Host Configuration Protocol)

DNS (Domain Name System)

HTTP (Servidor Web)

Telnet (Acesso remoto)

Endereçamento IP

Configuração de roteadores via CLI

Segurança básica em dispositivos de rede

Funcionalidades Implementadas

Comunicação entre todas as filiais da empresa

Comunicação entre redes internas e externas

Distribuição automática de endereços IP via DHCP

Resolução de nomes através de servidor DNS centralizado

Acesso à página web institucional da empresa

Gerenciamento remoto dos roteadores via Telnet

Proteção básica dos dispositivos com senhas e banners de aviso

Testes Realizados

Foram realizados testes de conectividade utilizando comandos de ping entre dispositivos da mesma rede e de redes distintas, além da verificação do funcionamento correto dos serviços DHCP, DNS, HTTP e Telnet. Todos os testes apresentaram resultados satisfatórios.

Considerações Finais

O projeto proporcionou uma experiência prática relevante, permitindo consolidar os conhecimentos teóricos estudados ao longo da disciplina de Redes de Computadores. A simulação no Cisco Packet Tracer mostrou-se essencial para a compreensão do funcionamento de redes corporativas e da importância do planejamento, da organização e da segurança em ambientes de rede.
