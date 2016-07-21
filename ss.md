# Find programs listening on port
# Netstat alternative
ss -antp '( sport = *:22 )'
