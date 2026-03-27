# Minecraft 1.20.1 - Server Semana Santa

Servidor de Minecraft PaperMC 1.20.1 configurado para jugar con amigos durante Semana Santa.

## Plugins instalados

- **EssentialsX** - Comandos básicos, warps, kits, economía
- **LuckPerms** - Sistema de permisos y rangos
- **Vault** - Integración de economía
- **EconomyShopGUI** - Tienda de items
- **TAB** - Scoreboard, header/footer, formato de TAB
- **PlaceholderAPI** - Placeholders para plugins
- **CoreProtect** - Protección de builds y rollback
- **PlayerPoints** - Sistema de puntos
- **LoginSecurity** - Login/register
- **SkinsRestorer** - Skins de usuarios
- **ViaVersion** - Soporte para versiones anteriores

## Configuración

- **IP**: 3.16.135.209:25565
- **RAM**: 6GB asignados
- **Puerto RCON**: 25575

### Comandos útiles

```bash
# Apagar servidor (dentro del juego)
/stop

# O desde terminal
screen -S minecraft -X stuff "stop\n"

# Iniciar servidor
cd /home/santi/minecraft/data
java -Xms4G -Xmx6G -jar paper-1.20.1-196.jar nogui
```

## Estructura

```
/home/santi/minecraft/data/
├── plugins/          # Plugins del servidor
├── server.properties # Configuración del servidor
├── ops.json          # Operadores
├── spigot.yml        # Configuración de Spigot
├── bukkit.yml        # Configuración de Bukkit
└── world/            # Datos del mundo (no en repo)
```

## Estado

El mundo se guarda automáticamente. NO committing del directorio `world/` al repo por tamaño.