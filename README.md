# TailwindCSS Cheatsheet

## Backgroud Classes

```css
.bg-{color}-{shade}
```
| colors | shades |
| ---- | ----- |
| black, white | - |
| gray, red, orange, yellow, green, teal, indigo, blue, purple, pink | 100 - 900 |

#### Example
```html
<div class="bg-blue-200">Header</div>
<div class="bg-white">Body</div>
```

## Element Size
* 1 rem (about 16px) = 4 in Tailwind (multiplied by 4)

### Width and Height
```css
.{w|h}-{size}
```
| Sizes | |
| ----- | ----- |
| 0, 1, 2, 3, 4, 5, 6, | +1 |
| 8, 10, 12, | +2 |
| 16, 20, 24, | + 4 |
| 32, 40, 48, 56, 64 | +8 |
| 1/2 ... | Every digit in fraction
| 1/{3, 4, 5, 6, 12} | |
| screen, full | |

#### Example
```html
<div class="bg-gray-800 w-1/2 h-12">Hello World</div>
<div class="bg-red-200 w-8 h-6/12">Good Morning</div>
```
