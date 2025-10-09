# Config

## Config

As of update 0.4.0, Arceon now offers a config located at: `/plugins/Arceon/config.yml`

If your config is missing any values, you may reference the [default config](config.md#default-configurations) for your version.

### Reload Command

**Permission:** `arceon.admin`

**`/arceon reload`** - reloads the config.

## Settings

#### bStats Metrics

Can the plugin collect anonymous usage metrics?\
Arceon metrics page: https://bstats.org/plugin/bukkit/Arceon/6481

Note: the server must be restarted if you change this value.\
Find global bStats settings in: `/plugins/bStats/config.yml`

```yaml
bstats-metrics: true
```

#### Commands

Command toggles.\
If there's a conflict with any of the built-in informational commands, disable them here.\
Note: the server must be restarted in order for updated command settings to take effect.\
All commands are enabled by default.

```yaml
commands:
  coffee: true
  suggest: true
  wiki: true
```

#### Selection Outline Particle

The particle type used to outline selections (such as the Loft tool).\
Available particles can be found at: https://hub.spigotmc.org/javadocs/spigot/org/bukkit/Particle.html

```yaml
selection-outline-particle: FLAME
```

#### Loft Tool

Loft tool settings.

```yaml
loft:
  # Limits the maximum amount of frames per loft.
  # Default: 50
  max-frames: 50
  # Limits the maximum amount of points per frame.
  # Default: 50
  max-points: 50
  # If enabled, players with 'arceon.bypass.loft' will be allowed to exceed the limits above.
  # Default: true
  enable-bypass: true
  # If enabled, paper without a display name using "loft" in the name won't work.
  # Default: false
  force-item-name: false
```

#### Asset Placer&#x20;

Asset placer settings.

```yaml
asset-placer:
  # Default: true
  enable-preview: true
  # Range the asset can be placed and previewed at.
  # Default: 200
  range: 200
  # Smooths out the movement between previews but makes it less snappy and more delayed.
  # Default: false
  smooth-transitions: false
  # Limits the maximum amount of blocks in an Asset. (only checks on creation)
  # Default: 500000
  max-blocks: 500000
  # Delay between updates on the previews in ticks.
  # Default: 5
  preview-update-delay: 5
  # Delay between clean cycles in ticks to clean up unused displays left over from server crashes & errors.
  # Default: 200
  preview-clean-delay: 200
```

#### Masks

Mask toggles.\
All masks are enabled by default.

```yaml
masks:
  above-mask: true
  ambient-mask: true
  angle-mask: true
  below-mask: true
  cell-mask: true
  color-mask: true
  crack-mask: true
  electric-mask: true
  fractal-mask: true
  noise-mask: true
  proximity-3D-mask: true
  proximity-mask: true
  turbulence-mask: true
  type-mask: true
  voronoi-mask: true
  y-gradient-mask: true
  y-mask: true
```

#### Patterns

Pattern toggles.\
All patterns are enabled by default.

```yaml
patterns:
  blend-pattern: true
  cell-pattern: true
  color-pattern: true
  double-plant-pattern: true
  electric-pattern: true
  fractal-pattern: true
  turbulence-pattern: true
  type-pattern: true
  voronoi-pattern: true
```

#### Tools

Tool toggles.\
All tools are enabled by default.

```yaml
tools:
  text-tool: true
```

## Default Configurations

* [**Latest** default config](https://github.com/Brennian/Arceon-1.14/blob/master/config.yml)
