# Trabalho de Redes de Computadores - Servidor Acadêmico

Este projeto implementa um sistema distribuído utilizando **Sockets TCP/IP** para o processamento centralizado de dados académicos (Offloading).

## Funcionalidades Principais
- **Cálculo de Médias**: Processamento de notas (N1, N2, N3) seguindo as regras institucionais.
- **Predição de Resultados**: O servidor calcula a nota necessária na N3 para aprovação.
- **Relatórios para Coordenação**: Geração automática de Média Geral, Moda, Mediana e Desvio Padrão.
- **Descoberta Automática**: Utiliza Broadcast UDP para localizar o servidor na rede local.
- **Concorrência**: Suporte a múltiplos clientes em simultâneo através de Threads.

## Como Executar
1. Inicie o servidor: `python3 servidor.py`
2. Inicie o cliente: `python3 cliente.py`
