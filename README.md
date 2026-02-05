# testesApiPets 🐾

## Português (PT-BR)

Testes automatizados para a **Swagger Petstore API v2** usando **Java 17**, **Cucumber (BDD)** e **RestAssured**, com **Allure Report**.

### Tecnologias 🧰
![Java](https://img.shields.io/badge/Java-17-007396?logo=openjdk&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-3-C71A36?logo=apachemaven&logoColor=white)
![Cucumber](https://img.shields.io/badge/Cucumber-BDD-23D96C?logo=cucumber&logoColor=white)
![JUnit4](https://img.shields.io/badge/JUnit-4-25A162?logo=junit5&logoColor=white)
![RestAssured](https://img.shields.io/badge/RestAssured-API_Testing-2E7D32)
![Allure](https://img.shields.io/badge/Allure-Report-FF6A00?logo=allure&logoColor=white)

### Estrutura 📁
- `src/test/resources/features/` → arquivos `.feature`
- `src/test/java/.../runner/RunTest.java` → runner do Cucumber
- `src/test/java/.../stepdefs/` → steps + hooks
- `src/test/resources/config.yaml` → `baseUrl` + endpoints
- `target/allure-results/` → resultados do Allure (gerado após os testes)

### Executar ▶️
```bash
mvn clean test
```

### Allure Report 📊
Abrir no navegador:
```bash
mvn allure:serve
```

Gerar HTML estático:
```bash
mvn allure:report
```

Abrir: `target/site/allure-maven-plugin/index.html`

### Observações ⚠️
- A Petstore pública pode ser instável (intermitência).
- IDs fixos podem conflitar com dados já existentes.

---

## English (EN)

Automated tests for **Swagger Petstore API v2** using **Java 17**, **Cucumber (BDD)**, and **RestAssured**, with **Allure Report**.

### Tech stack 🧰
![Java](https://img.shields.io/badge/Java-17-007396?logo=openjdk&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-3-C71A36?logo=apachemaven&logoColor=white)
![Cucumber](https://img.shields.io/badge/Cucumber-BDD-23D96C?logo=cucumber&logoColor=white)
![JUnit4](https://img.shields.io/badge/JUnit-4-25A162?logo=junit5&logoColor=white)
![RestAssured](https://img.shields.io/badge/RestAssured-API_Testing-2E7D32)
![Allure](https://img.shields.io/badge/Allure-Report-FF6A00?logo=allure&logoColor=white)

### Structure 📁
- `src/test/resources/features/` → `.feature` files
- `src/test/java/.../runner/RunTest.java` → Cucumber runner
- `src/test/java/.../stepdefs/` → steps + hooks
- `src/test/resources/config.yaml` → `baseUrl` + endpoints
- `target/allure-results/` → Allure results (generated after tests)

### Run ▶️
```bash
mvn clean test
```

### Allure Report 📊
Open in the browser:
```bash
mvn allure:serve
```

Generate static HTML:
```bash
mvn allure:report
```

Open: `target/site/allure-maven-plugin/index.html`

### Notes ⚠️
- The public Petstore can be unstable (intermittent).
- Fixed IDs may conflict with existing data.
