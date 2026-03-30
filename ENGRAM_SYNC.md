# Minecraft Server - Engram Sync

Este archivo sirve como referencia para sincronizar la configuración del servidor con engram.

## Fecha de sincronización
2026-03-30

## Información del servidor

- **IP**: 3.16.135.209 (puede cambiar al reiniciar EC2)
- **Puerto Java**: 25565
- **Puerto Bedrock**: 19132 (UDP)
- **RCON**: 25575 (password: 1233186298b80914915f5b0c)
- **RAM**: 6GB asignados

## Plugins instalados

| Plugin | Versión | Función |
|--------|---------|---------|
| PaperMC | 1.20.1-196 | Servidor |
| EssentialsX | 2.20.1 | Comandos, warps, kits, economía |
| LuckPerms | 5.5.0 | Permisos y grupos |
| Vault | 1.7.3-b131 | Integración de economía |
| EconomyShopGUI | 7.0.0 | Tienda |
| TAB | 5.5.0 | Scoreboard, header/footer |
| PlaceholderAPI | 2.12.2 | Placeholders |
| GriefPrevention | 16.18.1 | Claims/protección de territorio |
| CoreProtect | 23.1 | Protección y rollback |
| PlayerPoints | 3.3.3 | Sistema de puntos |
| LoginSecurity | 3.3.1 | Login/register |
| SkinsRestorer | - | Skins de jugadores |
| ViaVersion | 5.7.2 | Soporte versiones antiguas |
| GeyserMC | 2.9.5 | Bedrock support |
| Floodgate | 2.2.5 | Bedrock sin cuenta Java |

## Grupos de LuckPerms

- **default** - Jugadores normales
- **admin** - Administradores (Santi1708M)

## Kits disponibles

| Kit | Comando | Delay |
|-----|---------|-------|
| starter | /kit starter | 0 (una vez) |
| claim | /kit claim | 0 (una vez) |
| stone | /kit stone | 1 hora |
| food | /kit food | 30 min |
| resources | /kit resources | 2 horas |
| redstone | /kit redstone | 1 hora |
| farm | /kit farm | 1 hora |
| combat | /kit combat | 2 horas |
| enchant | /kit enchant | 4 horas |

## Comandos importantes

### Apagar servidor
```bash
/stop
```

### Iniciar servidor
```bash
~/start-server.sh
```

### Entrar a consola
```bash
screen -r minecraft
```

### Ver sesiones screen
```bash
screen -ls
```

## Configuración de server.properties

- **online-mode**: false (para cuentas no premium)
- **motd**: Servidor Jóvenes Bello
- **max-players**: 20

## GriefPrevention

- Bloques iniciales por jugador: 100
- Bloques ganados por hora: 100
- Máx bloques: 80,000
- Herramienta de claim: Golden Shovel

## Enlace del repo

https://github.com/santi1708M/minecraft-semana-santa
