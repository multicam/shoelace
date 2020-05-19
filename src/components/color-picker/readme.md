# Color Picker

```html preview
<sl-color-picker opacity format="hsl" size="medium"></sl-color-picker>
```


<!-- Auto Generated Below -->


## Properties

| Property    | Attribute   | Description                                                                                                                                                                                                                                                              | Type                             | Default                                                                                                                                                                                                                                 |
| ----------- | ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `format`    | `format`    | The format to use for the generated color `value`. If opacity is enabled, these will translate to HEXA, RGBA, and HSLA respectively. Note that browser support for HEXA doesn't include pre-Chromium Edge, so it's usually safer to use RGBA or HSLA when using opacity. | `"hex" \| "hsl" \| "rgb"`        | `'hex'`                                                                                                                                                                                                                                 |
| `inline`    | `inline`    | When true, the color picker will be rendered inline instead of in a dropdown.                                                                                                                                                                                            | `boolean`                        | `false`                                                                                                                                                                                                                                 |
| `opacity`   | `opacity`   | Whether to show the opacity slider.                                                                                                                                                                                                                                      | `boolean`                        | `false`                                                                                                                                                                                                                                 |
| `size`      | `size`      | The color picker's trigger size. Only applies when `inline` is false.                                                                                                                                                                                                    | `"large" \| "medium" \| "small"` | `'medium'`                                                                                                                                                                                                                              |
| `swatches`  | --          | An array of predefined color swatches to display. Can include any format the color picker can parse, including HEX(A), RGB(A), HSL(A), and CSS color names.                                                                                                              | `string[]`                       | `[     '#d0021b',     '#f5a623',     '#f8e71c',     '#8b572a',     '#7ed321',     '#417505',     '#bd10e0',     '#9013fe',     '#4a90e2',     '#50e3c2',     '#b8e986',     '#000',     '#444',     '#888',     '#ccc',     '#fff'   ]` |
| `uppercase` | `uppercase` | By default, the value will be set in lowercase. Set this to true to set it in uppercase instead.                                                                                                                                                                         | `boolean`                        | `false`                                                                                                                                                                                                                                 |
| `value`     | `value`     | The current color.                                                                                                                                                                                                                                                       | `string`                         | `'#ffffff'`                                                                                                                                                                                                                             |


## Events

| Event      | Description                                    | Type               |
| ---------- | ---------------------------------------------- | ------------------ |
| `slChange` | Emitted when the color picker's value changes. | `CustomEvent<any>` |


## Dependencies

### Depends on

- [sl-icon](../icon)
- [sl-input](../input)
- [sl-dropdown](../dropdown)

### Graph
```mermaid
graph TD;
  sl-color-picker --> sl-icon
  sl-color-picker --> sl-input
  sl-color-picker --> sl-dropdown
  sl-input --> sl-icon
  style sl-color-picker fill:#f9f,stroke:#333,stroke-width:4px
```

----------------------------------------------

