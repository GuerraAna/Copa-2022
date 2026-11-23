# App Android Copa 2022

## API
https://digitalinnovationone.github.io/copa-2022-android/api.json

App Android da **Copa do Mundo 2022** — lista partidas e informações da seleção brasileira consumindo a API acima.

## Objetivo

Projeto de estudo (DIO) para praticar **Jetpack Compose** com injeção de dependência e carregamento de imagens.

## Tecnologias

- Kotlin + **Jetpack Compose** (Material)
- **Hilt** (injeção de dependência)
- **Coil** (imagens — escudos das seleções)
- `activity-compose`, `lifecycle-runtime-ktx`
- Gradle 7.3.3 / compileSdk 33 (minSdk 26)

## Pré-requisitos

- **JDK 11**
- Android SDK Platform **33**

## Como rodar

```bash
echo "sdk.dir=$HOME/Library/Android/sdk" > local.properties   # macOS
./gradlew assembleDebug
```

A lista de partidas vem de `https://digitalinnovationone.github.io/copa-2022-android/api.json` — requer internet.
