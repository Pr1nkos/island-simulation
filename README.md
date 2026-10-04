# island-simulation

Симуляция экосистемы острова: животные и растения взаимодействуют по заданным правилам (питание, размножение, перемещение).
Две реализации одной идеи, собраны из `IslandSimulation` и `IslandSimulationSpringBoot` с историей коммитов.

| Каталог | Описание | Стек |
|---|---|---|
| [`console-gradle`](console-gradle) | Консольная версия | Groovy/Java, Gradle |
| [`spring-boot`](spring-boot) | Версия с веб-интерфейсом, конфигурацией в YAML и планировщиком задач. Подробности в [README](spring-boot/README.md) | Java 21, Spring Boot 3.3, Gradle |

## Запуск

```bash
cd spring-boot
./gradlew bootRun
```

```bash
cd console-gradle
./gradlew run
```

## Лицензия

[MIT](LICENSE)
