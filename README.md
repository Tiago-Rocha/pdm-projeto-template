# Tempo Açores · grupo

Projeto de grupo de PDM (CTeSP DAW, ESTA, Universidade dos Açores, 2026/27).

## Membros

| Nome | Número | GitHub |
|---|---|---|
|  |  |  |

## Como correr

```bash
flutter pub get
flutter devices          # o telemóvel Android tem de aparecer aqui
flutter run              # corre no telemóvel ligado por cabo
flutter run -d chrome    # no browser, quando não há telemóvel
```

Para gerar o APK que se instala noutros telemóveis Android:

```bash
flutter build apk --release
```

O ficheiro fica em `build/app/outputs/flutter-apk/app-release.apk`.

## Estrutura

- `lib/models/` a forma dos dados
- `lib/data/` vai buscar os dados (repositories, cliente da API)
- `lib/state/` guarda o estado e avisa os ecrãs (notifiers)
- `lib/screens/` um ecrã inteiro
- `lib/widgets/` pedaços de UI reutilizáveis
- `lib/main.dart` liga tudo

## Divisão do trabalho

(a preencher na primeira sprint)
