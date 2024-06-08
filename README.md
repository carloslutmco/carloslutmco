def ajustar_velocidade(combustivel):
    if combustivel > 75:
        return "Velocidade Máxima"
    elif combustivel > 50:
        return "Velocidade Alta"
    elif combustivel > 25:
        return "Velocidade Média"
    else:
        return "Velocidade Baixa"

# Teste a função com diferentes valores de combustível
print(ajustar_velocidade(80))  # Saída: Velocidade Máxima
print(ajustar_velocidade(60))  # Saída: Velocidade Alta
print(ajustar_velocidade(30))  # Saída: Velocidade Média
print(ajustar_velocidade(10))  # Saída: Velocidade Baixa

<!---
carloslutmco/carloslutmco is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
