# Design Guidelines

## Typography

### Sizes  
X-Small: `xs`  
Small: `sm`  
Medium: `md`, `default`  
Large: `lg`  
X-Large: `xl`  

### Size Unit  
```
@size-unit: 0.125
```

### Base Size
Base Size: `16px`  
rem(root element)  
```
@base-size: 16px;
```

### Font Sizes  
X-Small: `font-xs`  
Small: `font-sm`    
Medium: `font-md`, `font-size`  
Large: `font-lg`    
X-Large: `font-xl`    

```
@font-size: @base-size
@font-xs: @font-size * (1 - @size-unit*2)
@font-sm: @font-size * (1 - @size-unit)
@font-md: @font-size
@font-lg: @font-size * (1 + @size-unit)
@font-xl: @font-size * (1 + @size-unit*2)
```

```
@font-size: 16px
@font-xs: 12px
@font-sm: 14px
@font-md: 16px
@font-lg: 18px
@font-xl: 20px
```

### Line Height
1.5

### Icon
1.25
vertical-align: -25%

### Button Sizes  
```
@btn-padding-y: @font-base-size * 0.5
@btn-padding-y-xs: @btn-padding-y * (1 - @size-unit*2)
@btn-padding-y-sm: @btn-padding-y * (1 - @size-unit)
@btn-padding-y-md: @btn-padding-y
@btn-padding-y-lg: @btn-padding-y * (1 + @size-unit)
@btn-padding-y-xl: @btn-padding-y * (1 + @size-unit*2)
```

