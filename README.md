# 📱 MedSinal - Aplicativo Android

Aplicativo Android desenvolvido em **Java**, com arquitetura nativa e boas práticas de desenvolvimento. O app tem como objetivo facilitar o acesso à informação sobre ISTs, apoiar na prevenção e direcionar usuários a serviços de saúde próximos, de forma acessível, rápida e segura.

---

## 🏫 Instituição
**Centro Universitário Tiradentes - UNIT/PE**

## 🎓 Curso
**Análise e Desenvolvimento de Sistemas**

## 📅 Período
**5º Período - Embarque Digital**

## 📘 Disciplina
**Desenvolvimento Mobile**

## 👨‍🏫 Professor
**Diógenes Carvalho Matias**

---

## 🎯 Objetivo

Desenvolver um aplicativo Android que:
- Facilite o acesso à informação sobre ISTs;
- Auxilie na prevenção;
- Direcione usuários a serviços de saúde próximos;
- Promova saúde sexual de forma acessível, rápida e segura.

---

## 🛠️ Tecnologias Utilizadas

- **Linguagem:** Java  
- **Plataforma:** Android Nativo  
- **IDE:** Android Studio  
- **Geolocalização:** Google Maps API  
- **Chatbot:** Integração via botão direto com WhatsApp  
- **Design da Interface:** Figma, Canva e Adobe Photoshop  
- **Versionamento:** Git e GitHub  
- **Banco de Dados:** Não utilizado (dados inseridos manualmente no front-end)

---

## 🧭 Estrutura do Projeto

```plaintext
medSinal/
├── app/
│   ├── manifests/
│   │   └── AndroidManifest.xml
│   ├── java/
│   │   └── com.example.medsinal/
│   │       ├── model/
│   │       ├── ActivityConorreia.java
│   │       ├── ActivityHepatite.java
│   │       ├── ActivityHerpes.java
│   │       ├── ActivityHivAids.java
│   │       ├── ActivityHpv.java
│   │       ├── ActivitySifilis.java
│   │       ├── ActivityTaci.java
│   │       ├── BuscaSaudeActivity.java
│   │       ├── MainActivity.java
│   │       └── SaudeConectadaActivity.java
│   ├── res/
│   │   ├── drawable/
│   │   ├── font/
│   │   ├── layout/
│   │   ├── menu/
│   │   ├── mipmap/
│   │   ├── navigation/
│   │   ├── values/
│   │   └── xml/
├── Gradle Scripts/
│   ├── build.gradle (Project)
│   ├── build.gradle (Module :app)
│   ├── proguard-rules.pro
│   ├── gradle.properties
│   ├── gradle-wrapper.properties
│   ├── libs.versions.toml
│   ├── local.properties
│   └── settings.gradle
```

---

## 📁 Explicação das Pastas

### manifests/
- **AndroidManifest.xml**: Define informações essenciais do app (permissões, atividades, serviços, etc).

### java/
- com.example.medsinal: Código principal do app.
- com.example.medsinal (androidTest): Testes de instrumentação (executados em emulador/dispositivo).
- com.example.medsinal (test): Testes unitários locais (executados na JVM).

### res/
Contém os recursos visuais e auxiliares do app:
- drawable/: Imagens, formas e vetores.
- layout/: Arquivos de interface do usuário em XML.
- menu/: Definições de menus.
- mipmap/: Ícones do aplicativo em várias resoluções.
- navigation/: Gráficos de navegação do Jetpack.
- values/: Strings, temas, cores, dimensões e estilos.
- xml/: Arquivos de configuração extra (por exemplo, preferências).

---

## 🔧 Arquivos de Configuração

- **build.gradle (Project)**: Configurações globais do projeto.
- **build.gradle (Module)**: Dependências e configurações específicas do app.
- **proguard-rules.pro**: Regras para otimização e ofuscação de código.
- **gradle.properties**: Parâmetros globais de build.
- **gradle-wrapper.properties**: Versão do Gradle usada no projeto.
- **libs.versions.toml**: Catálogo de versões das bibliotecas utilizadas.
- **local.properties**: Caminho local do Android SDK (**não deve ser versionado**).
- **settings.gradle**: Declaração dos módulos do projeto.

---

## ⚙️ Configuração e Execução

### Pré-requisitos

- Android Studio instalado  
- Java JDK 11 ou superior  
- SDK Android configurado  

### Passos

1. Clone o repositório:
   ```bash
   git clone https://github.com/usuario/MedSinalMobile.git
   ```

2. Navegue até o diretório do projeto:
   ```bash
   cd MedSinal
   ```

3. Abra o projeto no Android Studio.

4. Aguarde a sincronização do Gradle.

5. Execute o projeto em um dispositivo ou emulador:
   - Clique no botão **Run** (▶️)

---

## 🧪 Testes

- **Testes Unitários (JVM):**
  ```bash
  ./gradlew test
  ```

- **Testes Instrumentados (emulador/dispositivo):**
  ```bash
  ./gradlew connectedAndroidTest
  ```

---

## 👨‍💻 Estrutura do Código

### Principais Atividades

- `MainActivity`: Tela inicial  
- `BuscaSaudeActivity`: Busca de locais de saúde  
- `SaudeConectadaActivity`: Integrações de apoio  
- Atividades específicas:
`ActivityHepatite`, `ActivityHivAids`, `ActivityHpv`, `ActivitySifilis`, `ActivityHerpes`, `ActivityConorreia`
- `ActivityTaci`: Assistente virtual

---

## 👥 Integrantes do Grupo

| Nome                                  | RA         |
| ------------------------------------- | ---------- |
| Artur Ribeiro Cavalcante Miranda      | 1241302321 |
| Bruno de Lucas Ferreira da Silva      | 1231310038 |
| Everlyn Marques de Oliveira Lima      | 1241302631 |
| Jordana dos Santos Tavares            | 1231311328 |
| Laryssa Thaynna da Silva Santana      | 1241303069 |
| Marcos Vinicius Nunes da Silva Cunha  | 1241303301 |
| Matheus José Oliveira da Silva Dantas | 1241303328 |
| Osmar Pereira de Menezes              | 1241303735 |
| Paulo Henrique Barros da Silva        | 1231309919 |
| Tamires Silva de Lima                 | 1202303909 |

---

## 🤝 Contribuindo

1. Crie uma branch:
   ```bash
   git checkout -b minha-feature
   ```

2. Faça commits:
   ```bash
   git commit -m "Minha contribuição"
   ```

3. Envie o código:
   ```bash
   git push origin minha-feature
   ```

4. Crie um Pull Request para a branch `main`.

---

## 📌 Observações Finais

- Mantenha o código organizado e bem comentado  
- Não versionar arquivos locais como `local.properties`  
- Verifique compatibilidades de SDK e Gradle ao clonar o projeto
