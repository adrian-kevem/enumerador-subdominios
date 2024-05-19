# Script "subdomain-enum.py" 
Este script em Python utiliza a biblioteca "dns.resolver" para realizar a varredura de subdomínios de um domínio especificado. Ele lê uma wordlist de um arquivo e tenta resolver cada subdomínio.

### Principais Funcionalidades
- Leitura de argumentos da linha de comando.
- Leitura de subdomínios de um arquivo de wordlist.
- Tentativa de resolução de DNS para cada subdomínio.
- Exibição dos subdomínios encontrados e seus endereços IP.

# Script "subdomain-wordlist.sh"
Este script em Bash utiliza o comando host para resolver subdomínios de um domínio especificado. Ele lê uma wordlist de um arquivo e tenta resolver cada subdomínio.

### Principais Funcionalidades
- Leitura de subdomínios de um arquivo de wordlist.
- Tentativa de resolução de DNS para cada subdomínio utilizando o comando host.
- Exibição dos resultados diretamente no terminal.
