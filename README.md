# ESPHome BME690 BSEC2 Component

External ESPHome component extending `bme68x_bsec2` to support:
- BME690
- Raw sensor readings
- BSEC2 IAQ outputs

## Usage

```yaml
external_components:
  - source: github://YOUR_GITHUB_USERNAME/esphome-bme690-bsec2
    components: [ bme68x_bsec2 ]
