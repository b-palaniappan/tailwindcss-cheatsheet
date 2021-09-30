# TailwindCSS Cheatsheet

## Backgroud Classes

```css
.bg-{color}-{shade}
```
| colors | shades |
| ---- | ----- |
| black, white | - |
| gray, red, orange, yellow, green, teal, indigo, blue, purple, pink | 100 - 900 |

> #### Example
> ```html
> <div class="bg-blue-200">Header</div>
> <div class="bg-white">Body</div>
> ```

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

> #### Example
> ```html
> <div class="bg-gray-800 w-1/2 h-12">Hello World</div>
> <div class="bg-red-200 w-8 h-6/12">Good Morning</div>
> ```

## Padding and Margin

* Paddings are inside the element
* Margin are outside the element

```css
.{p|m}-{size}
```
| Sizes | |
| ----- | ----- |
| 0, 1, 2, 3, 4, 5, 6, | +1 |
| 8, 10, 12, | +2 |
| 12, 20, 24, | +4 |
| 32, 40, 48, 56, 64 | +8 |

> #### Example
> ```html
> <div class="bg-blue-500 w-32 h-32 m-4 p-2">Text</div>
> <div class="bg-blue-500 w-32 h-32 m-4 p-2">Text</div>
> ```

### Top, Botton Right and Left margin or padding
```css
.{p|m{l|r|t|b}}-{size}
```

> Example
> ```html
> <div class="bg-blue-500 w-32 h-32 mt-4 pr-2 pl-2">Text</div>
> ```

### Padding and Margin for X axis and Y axis
```css
.{p|m{x|y}}-{size}
```

> #### Example
> ```html
> <div class="bg-blue-500 w-32 h-32 mt-4 px-2">Text</div>
> ```

## Styling Text

### Font Family
```css
.font-{family}
```

| families | |
| ----- | ----- |
| sans | Helvetica or similar |
| serif | Times New Roman or similar | 
| mono | Monospace or similar |

> #### Example
> ```html
> <div class="font-sans">Lorem ipsum dolor sit amet consectetur adipisicing elit.</div>
> ```

### Text Size
```css
.text-{size}
```

| Sizes | rem | Pixels |
| ----- | ----- | ----- |
| xs | .75rem | 12px |
| sm | .875 rem | 14px |
| base | 1 rem | 16px |
| lg | 1.125 rem | 18px |
| xl | 1.25 rem | 20px |
| 2xl | 1.5 rem | 24px |
| 3xl | 1.875 rem | 30px |
| 4xl | 2.25 rem | 36px |
| 5xl | 3 rem | 48px |
| 6xl | 4 rem | 64px |

> #### Example
> ```html
> <div class="text-lg">Lorem ipsum dolor sit amet consectetur adipisicing elit.</div>
> ```

### Text Align
```css
.text-{align}
```

| Alignments |
| ----- |
| left | 
| center |
| right | 
| justify |

> #### Example
> ```html
> <div class="text-right">Lorem ipsum dolor sit amet consectetur adipisicing elit.</div>
> ```

### Text Color
```css
.text-{color}-{shade}
```

| colors | shades |
| ----- | ----- |
| black, white | - |
| gray, red, orange, yellow, green, teal, indigo, blue, purple, pink | 100 -900 |

> #### Example
> ```html
> <div class="bg-blue-800 m-3 p-5 text-lg text-justify text-blue-200">Lorem ipsum dolor sit amet consectetur adipisicing elit.</div>
> ```
