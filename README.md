# Java Exercises — Calculadora e Lógica

Projetos de estudo em Java: calculadora interativa, menu, operações básicas e estrutura de código.

## Conteúdo

- **Calculadora** (`Principal.java`) — menu interativo com soma, subtração, multiplicação, divisão
- Estrutura padrão Maven/Gradle-ready (`src/`, `bin/`)
- Entrada via `Scanner`, loop `while`, métodos estáticos

## Estrutura

```
Java Testes/treinando dnv/
├── src/
│   └── Principal.java      # Ponto de entrada + calculadora
└── bin/                    # Compilados (gerado automaticamente)
```

## Compilar e Executar

```bash
# Compilar
javac -d bin src/Principal.java

# Executar
java -cp bin Principal
```

## Funcionalidades da Calculadora

| Opção | Operação |
|-------|----------|
| 1 | Soma |
| 2 | Subtração |
| 3 | Multiplicação |
| 4 | Divisão |
| 0 | Sair |

## Observações

- Código educacional — foco em clareza, não performance
- Tratamento básico de entrada (sem validação robusta)
- `Thread.sleep` usado apenas para pausa visual no console

---

*Projetos de estudo — Java 8+ compatível.*