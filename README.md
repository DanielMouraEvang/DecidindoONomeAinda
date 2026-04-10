# TentandoDecidirONomeAinda

Nome atual: *Tentando decidir o nome ainda*

meu modpack fabric sem nome ainda

(*leia o "ME-LEIA.txt" incluso do .mrpack porque ele é sempre atualizado de acordo com a versão*)

## Argumentos JVM, RAM para MInecraft Java edition e a RUNTIME do java

<details>
<summary><b>Clique aqui para ver</b></summary>

Java recomendado:
[Download Java 17 (Temurin)](https://adoptium.net/pt-BR/temurin/releases?version=17)

Argumentos JVM Recomendados:
```Text
-XX:+UseG1GC -XX:+ParallelRefProcEnabled -XX:MaxGCPauseMillis=200 -XX:+UnlockExperimentalVMOptions -XX:+DisableExplicitGC -XX:G1NewSizePercent=30 -XX:G1MaxNewSizePercent=40 -XX:G1HeapRegionSize=8M -XX:G1ReservePercent=20 -XX:G1HeapWastePercent=5 -XX:G1MixedGCCountTarget=4 -XX:InitiatingHeapOccupancyPercent=15 -XX:G1MixedGCLiveThresholdPercent=90 -XX:G1RSetUpdatingPauseTimePercent=5 -XX:SurvivorRatio=32 -XX:+PerfDisableSharedMem -XX:MaxTenuringThreshold=1
```

Memoria recomendada:
6144 de miníma e de maxima
ou se prefirir ```-Xmx6G -Xms6G```, e se o seu computador tiver 16GB de RAM você pode colocar 8192 de miníma e de maxima ou ```-Xmx8G -Xms8G```

</details>
