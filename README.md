# MeuPrimeiroApp

Aplicativo Android simples criado como projeto inicial para estudos.

## Tecnologias e Bibliotecas Utilizadas
- **Linguagem:** Java
- **SDK:** Android SDK 21+ (target: 34)
- **Build System:** Gradle (Kotlin DSL)
- **Bibliotecas:**
  - [AndroidX AppCompat 1.6.1](https://developer.android.com/jetpack/androidx/releases/appcompat)
  - [Material Components 1.10.0](https://github.com/material-components/material-components-android)
  - [AndroidX Activity 1.9.3](https://developer.android.com/jetpack/androidx/releases/activity)
  - [ConstraintLayout 2.1.4](https://developer.android.com/jetpack/androidx/releases/constraintlayout)
  - [JUnit 4.13.2](https://junit.org/junit4/) (testes)
  - [AndroidX Test JUnit 1.2.1](https://developer.android.com/jetpack/androidx/releases/test)
  - [Espresso Core 3.6.1](https://developer.android.com/jetpack/androidx/releases/espresso)

## Padrões e Estrutura do Projeto
- **Estrutura padrão Android:**
  - `MainActivity` herda de `AppCompatActivity`.
  - Layout principal em `ConstraintLayout`.
  - Temas claros e escuros baseados em Material3.
- **Padrão de código:** Simples, ideal para iniciantes.

## Como Rodar o Projeto
1. **Pré-requisitos:**
   - [Android Studio](https://developer.android.com/studio) instalado
   - Java 11+
2. **Clone o repositório:**
   ```sh
   git clone <url-do-repo>
   ```
3. **Abra o projeto no Android Studio:**
   - Selecione a pasta `MeuPrimeiroApp`.
4. **Sincronize o Gradle:**
   - O Android Studio fará o download das dependências automaticamente.
5. **Execute o app:**
   - Use um dispositivo físico ou emulador.

## Configurações Importantes
- **ProGuard:**
  - Arquivo de regras em `app/proguard-rules.pro` (configuração padrão, sem regras customizadas).
- **Permissões:**
  - Não requer permissões especiais.
- **Backup:**
  - Suporte a backup e restauração via Android (configurado no `AndroidManifest.xml`).

by Rodolfo M F Abreu